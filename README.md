# PySpark from zero — interactive course

14 Jupyter notebooks that take you from "what is Spark?" to tuning jobs and streaming.
Each lesson explains a concept, gives runnable examples, then has **exercises** with **auto-checks**.

Created by George Forrest-Moore, with troubleshooting help from [Claude Code](https://claude.com/claude-code).

## Setup
You need Java 17 (Spark runs on the JVM) and Python 3.12. Then, from the repo folder:

```
uv venv --python 3.12 .venv
uv pip install --python .venv pyspark "pandas<3" pyarrow ipykernel
```

## Get started in VS Code
1. Open this folder in VS Code. Install the **Python** and **Jupyter** extensions if prompted.
2. Open `notebooks/00_welcome_and_first_steps.ipynb`.
3. Top-right **Select Kernel** → *Python Environments → .venv*.
4. Run cells with **Shift+Enter**. Always run the setup cell first.

## Layout
| Folder | What |
|---|---|
| `notebooks/` | the lessons — work in these |
| `solutions/` | the same lessons with answers filled in and outputs shown |
| `data/` | the course dataset (an online shop: customers, products, orders, messy orders, click events) |
| `output/` | created by the lessons when they write files — safe to delete |

## Lessons
00 Welcome & lazy evaluation · 01 DataFrame basics · 02 Reading & writing · 03 Columns & functions ·
04 Aggregations · 05 Joins · 06 Window functions · 07 Spark SQL · 08 Structs/arrays/maps/JSON ·
09 UDFs & pandas UDFs · 10 Partitions, shuffles, plans & RDDs · 11 Performance tuning ·
12 Capstone project · 13 Bonus: Structured Streaming

Reset an exercise notebook: `git checkout` it, or copy it from `solutions/` and delete your answers.
