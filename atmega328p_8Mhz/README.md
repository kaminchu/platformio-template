## project init
```
pio project init -b 328p8m -O "upload_protocol=usbasp" -O "upload_flags=-e" -O "board_build.f_cpu=80000000L"
```

## write
```
pio run -t upload
```

