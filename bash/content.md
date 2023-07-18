## What is Bash?

- Bourne Again Shell
- Bash is a tool
- sys admin toolbox
- automation
- scripting
- great as gaffer tape
- It is a serious scripting language, mainly used to work with text files (like logs, configs etc) and Linux system administration. (In Linux, almost everything is a file and accessible as text.) 
- Bash is a shell. The job of a shell is to pass commands to the kernel so that you can tell the kernel what software to execute. 	


---

## One liner versus shell scripts

Man kann eine einige Zeile Bash-Code schreiben, aber auch Dateien anlegen, die längere Scripte enthalten (.sh). 

---

## Shebang


```
#!/usr/bin/bash
```

---

## Basic commands

| Befehl |funktion| 
| ---- | ---- |
| touch    | create file |
| mkdir    | create folder |
| rm | remove |
| cp | copy |
| mv | move or rename |
| cat | print content to comand line |
| echo | echo |
| grep | suchen |
| date | Datum anzeigen |
| pwd | Aktuellen Pfad anzeigen |
| ls | Dateien anzeigen |

---

## Variables

```
GREET="Hey Tim"
echo $GREET
```

---

## Script ausführen

```
./script.sh
```

---

## Operators

```
> 

Overwrites the existing file, or creates a file if the file of the mentioned name is not present in the directory.

>>

Appends the existing file, or creates a file if the file of the mentioned name is not present in the directory.

```


---

## Resources

- https://youtu.be/I4EWvMFj37g
- https://google.github.io/styleguide/shellguide.html

