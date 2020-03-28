# Comandos AT
### Firmware para módulos com 4MB de memória flash (Testado com NodeMCU Amica)

Windows:
```
C:/> esptool --port COM4 erase_flash
C:/> esptool --port COM4 write_flash --flash_mode dio --flash_size 4MB 0x0 at_ai_thinker_0.9.5.0.bin
```

Outros firmwares podem ser encontrados neste <a href="https://www.espressif.com/en/support/download/at?keys=&field_type_tid%5B%5D=14">link</a>. 
