## Dither all images in a folder
´´´
convert ./static/images/*.jpg -resize '400x400' -dither FloydSteinberg -remap pattern:gray50 -set filename:base "%[basename]" "./static/dither/%[filename:base].png"
```

