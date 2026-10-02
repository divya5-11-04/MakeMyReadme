<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=200&section=header&text=word-counter&fontSize=52&fontColor=ffffff&animation=fadeIn)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=7c5cff&center=true&vCenter=true&width=640&lines=A%20small%20command-line%20tool%20that%20downloads%20a%20web%20page%20and%20coun" alt="tagline">

![license](https://img.shields.io/badge/license-MIT-7c5cff?style=for-the-badge)

![Requests](https://img.shields.io/badge/Requests-7c5cff?style=flat-square)

</div>

## Overview

A small command-line tool that downloads a web page and counts the words on it.

## Features

| Feature | What it does |
|---|---|
| **Fetch page** | Download a web page and return its text. |
| **Count words** | Count how many words appear in the text. |
| **Report** | Print a word count for a URL. |

## How it works

Which functions call which:

```mermaid
flowchart TD
  N2["report"]
  N0["fetch_page"]
  N1["count_words"]
  N2 --> N0
  N2 --> N1
```

<details open>
<summary><b>Getting started</b></summary>

```bash
git clone <your-repo-url>
cd word-counter
pip install requests
python main.py
```

</details>

<details>
<summary><b>Command-line options</b></summary>

| Option | Description |
|---|---|
| `--url` | Page to analyze |

</details>

<details>
<summary><b>Project structure</b></summary>

```
word-counter/
├── main.py
```

</details>

## License

MIT
