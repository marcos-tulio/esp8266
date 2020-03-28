# Comandos AT
### Firmware para módulos com 4MB de memória flash (Testado com NodeMCU Amica)

Windows:
```
C:/> esptool --port COM4 erase_flash
C:/> esptool --port COM4 write_flash --flash_mode dio --flash_size 4MB 0x0 at_ai_thinker_0.9.5.0.bin
```

Outros firmwares podem ser encontrados neste <a href="https://www.espressif.com/en/support/download/at?keys=&field_type_tid%5B%5D=14">link</a>. 



### Escrever firmware na flash
esptool write_flash --flash_size 4MB-c1 --flash_mode dio 0x0 eagle.flash.bin 0x10000 eagle.irom0text.bin 0x3FC000 esp_init_data_default_v05.bin
