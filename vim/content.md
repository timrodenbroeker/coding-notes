## Warum Vim?

- Schreibmaschine
- Fokussiertes Arbeiten
- Ablenkungsfreies Schreiben
- Man braucht keinen teuren Rechner
- Refurbishing
- Fokus
- Flow

---

## Was is Vim?

Vim ist ein Text-Editor für die so genannte Command-Line. 

---

## Modes

- Command Mode
	- Befehle ausführen
- Command Line Mode
	- Commands prefixed with `:`
- Insert Mode
	- Text/Code schreiben
- Visual Mode
	- Markieren

---

## Search mode
```
/pattern
```
`n` drücken um zur nächsten Vorkommen des Suchbegriffs zu navigieren
`*` macht dasselbe (?)
---


### Search and Replace
```
:[range]s/{pattern}/{string}/[flags]
```
---

### Undo und Redo
Undo macht man mit `u` und Redo mit `ctrl+r`

---

## Command Mode

| Command | Funktion                      |
| ------- | ----------------------------- |
| i       | insert mode                   |
| v       | visual mode                   |
| y       | copy |
| p       | paste |
| d       | cut |
| u       | undo |
| Ctrl+R  | Redo |

---

## Insert Mode

---

## Visual Mode

---

## Copy and Paste zwischen verschiedenen Dateien

1. v für visual mode 
2. d oder x um auszuschneiden
3. p um zu pasten 

---

## Customization

- Die Settings für Vim finden sich in .vimrc

---

# Nerdtree

## Tab Datei in neuem Tab wechseln
Einfach mit `t` statt mit `enter` öffnen

## Refresh
`r`
# Settings

## Wörter in die nächste Zeile laufen lassen statt sie umzubrechen
```
:set linebreak
```


---

## Resources
- https://sean-warman.medium.com/why-vim-is-better-than-vscode-d09e2355eb37
- https://vi.stackexchange.com/
- https://youtu.be/RZ4p-saaQkc
- https://www.youtube.com/channel/UCd3dNckv1Za2coSaHGHl5aA
- https://neovim.io/
- https://vimawesome.com/


