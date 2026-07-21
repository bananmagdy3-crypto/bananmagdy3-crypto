<p align="right">
  <img src="https://skillicons.dev/icons?i=python&theme=dark" width="26"/>&nbsp;&nbsp;<b>banan_magdy.ipynb</b>&nbsp;&nbsp;<sub>Jupyter Notebook — last run just now</sub>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e1e1e,100:1e1e1e&height=2&width=1000"/>

<br/>

**In [1]:**
```python
import banan_magdy as me
from mansoura_university import cs_department

me = banan_magdy.Student(
    name        = "Banan Magdy",
    major       = cs_department,
    focus       = ["Data Science", "Machine Learning", "Problem Solving"],
    status      = "leveling up my programming skills",
)

print(me.bio())
```

**Out [1]:**
```
>>> Computer Science student at Mansoura University.
>>> Passionate about turning messy data into clear decisions.
>>> Currently sharpening skills across Python, C#, and SQL.
```

<br/>

**In [2]:**
```python
me.skills.plot(kind="barh")
```

**Out [2]:**
```
Python          ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░  90%
Pandas / NumPy  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░  80%
Jupyter         ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░  85%
C#              ▓▓▓▓▓▓▓▓▓▓░░░░░░░░░░  50%
SQL             ▓▓▓▓▓▓▓▓▓▓▓▓░░░░░░░░  60%
Machine Learning▓▓▓▓▓▓▓▓▓▓▓░░░░░░░░░  55%
```

<div align="center">

![Python](https://img.shields.io/badge/-Python-1e1e1e?style=flat-square&logo=python&logoColor=3776AB)
![C++](https://img.shields.io/badge/-C++-1e1e1e?style=flat-square&logo=cplusplus&logoColor=00599C)
![C#](https://img.shields.io/badge/-C%23-1e1e1e?style=flat-square&logo=csharp&logoColor=239120)
![MySQL](https://img.shields.io/badge/-MySQL-1e1e1e?style=flat-square&logo=mysql&logoColor=4479A1)
![NumPy](https://img.shields.io/badge/-NumPy-1e1e1e?style=flat-square&logo=numpy&logoColor=013243)
![Pandas](https://img.shields.io/badge/-Pandas-1e1e1e?style=flat-square&logo=pandas&logoColor=150458)
![Jupyter](https://img.shields.io/badge/-Jupyter-1e1e1e?style=flat-square&logo=jupyter&logoColor=F37626)
![Git](https://img.shields.io/badge/-Git-1e1e1e?style=flat-square&logo=git&logoColor=F05032)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e1e1e,100:1e1e1e&height=2&width=1000"/>

<br/>

**In [3]:**
```python
me.projects.sort_values("stars", ascending=False)
```

**Out [3]:**

| # | repo | description | stack | stars |
|---|------|--------------|-------|:-----:|
| 0 | [**FiFa-2026**](https://github.com/bananmagdy3-crypto/FiFa-2026) | FIFA World Cup 2026 player performance analysis using advanced football metrics | Jupyter Notebook | ⭐ 2 |
| 1 | [**Uber-Data-Analysis**](https://github.com/bananmagdy3-crypto/Uber-Data-Analysis) | End-to-end EDA on Uber trips — peak demand hours, round trips, ride-completion efficiency | Jupyter Notebook | ⭐ 1 |
| 2 | [**E-Commerce-Data-Project**](https://github.com/bananmagdy3-crypto/E-Commerce-Data-Project) | Exploring e-commerce data for sales & customer behavior patterns | Python | ⭐ 1 |
| 3 | [**numpyandpandas_practise**](https://github.com/bananmagdy3-crypto/numpyandpandas_practise) | Beginner sales analysis project, built to master NumPy & Pandas | Python | ⭐ 1 |
| 4 | [**MindSprintCoders-main**](https://github.com/bananmagdy3-crypto/MindSprintCoders-main) | Team project built during a coding sprint | C# | ⭐ 1 |

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e1e1e,100:1e1e1e&height=2&width=1000"/>

<br/>

**In [4]:**
```python
me.activity.describe()
```

**Out [4]:**

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bananmagdy3-crypto&show_icons=true&theme=github_dark&hide_border=true&bg_color=1e1e1e&title_color=ffffff&icon_color=6cb6ff&text_color=c9d1d9" width="49%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bananmagdy3-crypto&layout=compact&theme=github_dark&hide_border=true&bg_color=1e1e1e&title_color=ffffff&text_color=c9d1d9" width="42%"/>

</div>

<br/>

**In [5]:**
```python
me.contributions.plot(kind="calendar_heatmap")
```

**Out [5]:**

<div align="center">
<img src="https://raw.githubusercontent.com/bananmagdy3-crypto/bananmagdy3-crypto/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

> **ملاحظة:** أنيميشن الثعبان محتاج إعداد لمرة واحدة (GitHub Action يومي) — الخطوات تحت في آخر الملف.

<br/>

**In [6]:**
```python
print("Kernel: always learning. Restarting daily.")
```

**Out [6]:**
```
Kernel: always learning. Restarting daily.
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1e1e1e,100:1e1e1e&height=2&width=1000"/>

---

<details>
<summary>⚙️ <b>إزاي تفعّلي أنيميشن الثعبان (خطوة واحدة بس)</b></summary>

<br/>

1. من الريبو `bananmagdy3-crypto` → **Settings → Actions → General** → فعّلي **Read and write permissions**.
2. أنشئي ملف `.github/workflows/snake.yml` بهذا المحتوى:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. بعد أول تشغيل، الملف هيظهر تلقائي.

</details>
