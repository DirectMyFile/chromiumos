## Chromium OS Builds by DirectCode

Thanks for choosing DirectCode as your Chromium OS Build provider!

### Flashing the Image to USB

You will need to have a 4GB+ Flash Drive.

#### Linux

Run the Following Commands:
```bash
tar zxvf ChromiumOS.tar.gz
sudo dd if=chromiumos_image.bin of=/dev/sdx bs=1M
```
