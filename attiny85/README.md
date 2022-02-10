## project init
```
pio project init -b attiny85
```

## write
```
pio run -t upload
```

## 書き込み装置


### usbasp
装置
https://www.amazon.co.jp/AVR-usbasp/s?k=AVR+usbasp

つなぎ方
https://55life555.blog.fc2.com/blog-entry-3203.html

設定
```
echo "upload_protocol = usbasp" >> platformio.ini
```

### ArduinoISP
Arduino(nano/UNO)にスケッチを書き込んでおく
https://docs.arduino.cc/built-in-examples/arduino-isp/ArduinoISP


設定
```
upload_protocol = arduino
```
