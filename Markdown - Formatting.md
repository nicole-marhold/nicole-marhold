# 📘 GitHub Code-Style

> Das .md-Format steht für Markdown.
> Markdown ist eine einfache Auszeichnungssprache, mit der man Text so formatieren kann, dass er sowohl leicht lesbar ist als auch leicht in HTML umgewandelt werden kann.

Diese Übersicht zeigt alle wichtigen Markdown‑Elemente, die im GitHub genutzt werden:

---

## 🧱 Überschriften

```markdown
# H1
## H2
### H3
#### H4
```

---

## ✨ Fett, Kursiv, Durchgestrichen

```markdown
**Fett**
*Kursiv*
~~Durchgestrichen~~
**_Fett + Kursiv_**
```

---

## 🧩 Zeilenumbrüche & Abstand

```markdown
Zeile 1  
Zeile 2  ← (Zwei Leerzeichen am Ende für Zeilenumbruch)

Absatz durch eine leere Zeile:

Textblock 1

Textblock 2
```

---

## 📋 Listen

### Ungeordnete Liste
```markdown
- Punkt A
- Punkt B
  - Unterpunkt
```

### Geordnete Liste
```markdown
1. Erster
2. Zweiter
```

---

## 🧪 Code & Commands

### Inline-Code
```markdown
`command`
```

### Codeblock
```markdown
```bash
gobuster dir -u https://target -w list.txt
```
```

---

## 📦 Zitate / Hinweisboxen

```markdown
> Dies ist ein Hinweis oder eine Info-Box.
```

---

## 🔗 Links

```markdown
[Linktext](https://example.com)
```

---

## 🖼️ Bilder

```markdown
![Alt-Text](https://beispiel.com/bild.png)
```

---

## 📊 Tabellen

```markdown
| Name     | Beschreibung     | Beispiel               |
|----------|------------------|------------------------|
| Gobuster | Dir enum tool    | `gobuster dir ...`     |
| FFUF     | Web Fuzzer       | `ffuf -w ...`          |
```

---

## 🎛️ Faltbare Abschnitte (sehr praktisch!)

```markdown
<details>
<summary>Klicken zum Öffnen</summary>

Inhalt, Code, Beispiele usw.

</details>
```

---

## 🎨 Emojis

```markdown
🔥 🚀 🛠️ ✔️ ❗ 📌 📁 🧠
```

---

## 📁 Ordnerstruktur darstellen

```markdown
/web-security
│── /recon
│   ├── dir-enum.md
│   └── parameter-discovery.md
│── /vulnerabilities
│   ├── sqli.md
│   ├── xss.md
│── /tools
│   ├── gobuster.md
│   ├── ffuf.md
│── README.md
```

---

## ➖ Trennlinien

```markdown
---
```

---

## ☑️ Checkboxen

```markdown
- [x] Erledigt
- [ ] Offene Aufgabe
```

---

## 🏷️ Badges (Beispiele)

```markdown
![Status](https://img.shields.io/badge/status-active-brightgreen)
![TryHackMe](https://img.shields.io/badge/learning-TryHackMe-blue)
```

---

## 🔥 Inline-Highlight für Befehle

```markdown
**`gobuster dir -u https://target -w list.txt`**
```
