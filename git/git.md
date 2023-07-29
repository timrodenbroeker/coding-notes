## Credentials speichern
run
```
git config --global credential.helper store
```
then
```
git pull
```

---

## Änderungen pushen
```
git add .
```

```
git commit -m "message"
```

```
git push
```

---

## Status anzeigen

```
git status 
```


## Reset local repository branch to be just like remote repository HEAD

```
git fetch origin
git reset --hard origin/master
```
