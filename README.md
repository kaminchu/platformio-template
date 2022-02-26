# これなに

platformioでマイコン書き込むときの設定のテンプレ


# platformioのコマンドtips

モジュール検索
```
pio lib search <module word>
```

モジュールインストール
```
pio lib install <id>
```

モジュール削除
```
pio lib uninstall <id>
```

シリアルモニタを開く
```
pio device monitor -b <bps>
```

コードを書き込む
```
pio run -t upload
```

usbの権限周り参考
https://docs.platformio.org/en/latest//faq.html#platformio-udev-rules
