# log — Official Wyn Package

Structured logging with levels. Pure Wyn.

## Install

```bash
wyn pkg install github.com/wynlang/log
```

## Usage

```wyn
Log_info("server started on port 8080")
Log_warn("cache miss")
Log_error("connection failed")
Log_set_level(2)  // only warn and error
```

Levels: 0=debug, 1=info, 2=warn, 3=error
