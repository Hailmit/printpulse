# Firmware Binary

Place the merged ESP32-C3 firmware binary here:

```text
docs/firmware/printpulse-c3.bin
```

The web installer manifest expects a single merged binary at offset `0`.

For ESP32 Arduino builds, merge the bootloader, partition table, boot app, and app firmware with `esptool.py merge_bin` before publishing the file here.
