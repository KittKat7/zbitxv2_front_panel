The code tft_ili9488.* files are extracted from TFT_eSPI library to be specific to the zbitx front panel code

## Building
Font libraries are required.

```bash
mkdir -p fonts

curl -fL https://raw.githubusercontent.com/Bodmer/TFT_eSPI/master/Fonts/glcdfont.c -o fonts/glcdfont.c
curl -fL https://raw.githubusercontent.com/Bodmer/TFT_eSPI/master/Fonts/Font16.c -o fonts/Font16.c
curl -fL https://raw.githubusercontent.com/Bodmer/TFT_eSPI/master/Fonts/Font32rle.c -o fonts/Font32rle.c
```
