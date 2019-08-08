## General

All tests have been compiled on a Manjaro Arch x64 desktop using PlatformIO 4.0 and the current versions of the board support packages and compiler toolchains. 

## Test Failures
| Board Name | Failure Notes|
|---|---|
| Arduino Uno/Nano | Resets when attempting to run coremark_main() |
| ESP8266 | Resets when attempting to run coremark_main(), and does not appear to be watchdog related |