# GeoCalculus: Calculus in the Geosciences

Teaching material for **SCMA 111 Calculus** (ทคณ ๑๑๑ แคลคูลัส) for Geoscience students: 46 worked examples that apply each syllabus topic to a real Earth-science problem, ordered from easy to hard, in English and Thai.

สื่อการสอนประกอบรายวิชา **ทคณ ๑๑๑ แคลคูลัส** สำหรับนักศึกษาธรณีศาสตร์ ตัวอย่างพร้อมวิธีทำ 46 ตัวอย่างที่นำแต่ละหัวข้อในประมวลรายวิชาไปใช้กับปัญหาจริงทางธรณีศาสตร์ เรียงจากง่ายไปยาก มีทั้งภาษาอังกฤษและภาษาไทย

## What is here

| | English | ไทย |
|---|---|---|
| Jupyter notebook | [`Calculus_in_Geosciences.ipynb`](Calculus_in_Geosciences.ipynb) · [view](https://nbviewer.org/github/Songkhun/GeoCalculus/blob/main/Calculus_in_Geosciences.ipynb) · [Colab](https://colab.research.google.com/github/Songkhun/GeoCalculus/blob/main/Calculus_in_Geosciences.ipynb) | [`Calculus_in_Geosciences_TH.ipynb`](Calculus_in_Geosciences_TH.ipynb) · [ดู](https://nbviewer.org/github/Songkhun/GeoCalculus/blob/main/Calculus_in_Geosciences_TH.ipynb) · [Colab](https://colab.research.google.com/github/Songkhun/GeoCalculus/blob/main/Calculus_in_Geosciences_TH.ipynb) |
| Interactive app | [GeoCalculus Lab](https://songkhun.github.io/files/geocalculus_app.html) (switch language in the app) | [GeoCalculus Lab](https://songkhun.github.io/files/geocalculus_app.html) (สลับภาษาในแอป) |

**Notebooks.** Seven parts (A–G) follow the syllabus: limits and continuity → derivatives of elementary functions → higher-order, implicit and differentials → applications of derivatives → several variables → integration techniques → applications of integration. Every example has the geoscience context, a detailed step-by-step hand solution, SymPy/NumPy code with a plot, what the answer means, common mistakes, and a "Try it" exercise. A course map links each syllabus week to its examples, and each part ends with a **worksheet** (52 questions in total) whose answers open on click.

**App** ([`app/index.html`](app/index.html), one HTML file). Each example has sliders, live formulas and a chart, plus the step-by-step explanation. It also has an auto-graded **quiz** for each part and a **course map by week** that highlights the current week. Thai/English and light/dark switches; works on phones.

## Running the notebooks

```bash
pip install -r requirements.txt      # numpy, scipy, sympy, matplotlib (all in Anaconda)
jupyter lab Calculus_in_Geosciences.ipynb
```

Then `Kernel → Restart & Run All`. Data sets are synthetic (generated in code) with realistic values, so every result can be reproduced.
