## project init
```
pio project init -b nodemcuv2 -O "monitor_speed=9600"
```

## write
```
pio run -t upload
```

## serial monitor
```
pio device monitor -b 9600
```

## tips

WiFi使うときはこうする(libのinstallは不要)

```
#include <ESP8266WiFi.h>
```

Time使うときはこうする(libのinstallは不要)
```
#include <TimeLib.h>
```
