# Comandos AT
#### Módulos com 4MB de memória flash (Testado com NodeMCU Amica)

```
C:/> esptool --port COM4 erase_flash
C:/> esptool --port COM4 write_flash --flash_mode dio --flash_size 4MB 0x0 at_ai_thinker_0.9.5.0.bin
```

