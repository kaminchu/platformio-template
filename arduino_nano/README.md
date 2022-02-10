## project init
```
pio project init -b nanoatmega328 -O "monitor_speed=9600"
```

## write
```
pio run -t upload
```

## serial monitor
```
pio device monitor -b 9600
```
