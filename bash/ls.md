## Nur Dateien mit bestimmter Endung anzeigen
```
ls *.{mp3,exe,mp4}
```

oder

```
ls *.mp4 *.mp3 *.exe
```

oder

```
find . -iregex '.*\.\(mp3\|mp4\|exe\)' -printf '%f\n'
```
