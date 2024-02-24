# platform-detector
Model that indicates platform with green stickers on it on an image

# Prerequisites
```
python3 git os torch torchvision
```
You should also have MPS installed if you're using MacOS silicon GPU. Installation of MacOS MPS can be found here: https://developer.apple.com/metal/pytorch/

# Usage:
```bash
# make
make

# test
make test

# test manually
./image-to-grayscale.py qrcode.png > qrcode_600x600_grayscale.bin
./qr-bmp < qrcode_600x600_grayscale.bin
```

