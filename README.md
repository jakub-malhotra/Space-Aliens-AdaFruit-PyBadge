# ICS3U ⇢ Unit #X-YY

[![Mr Coxall's Super Linter](https://github.com/<OWNER>/<REPOSITORY>/workflows/Mr%20Coxall's%20Super%20Linter/badge.svg)](https://github.com/<OWNER>/<REPOSITORY>/actions)

[![CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)](./LICENSE)

---

**Python**
- to interpret your python program
```console
  python main.py
```
- to run black to lint your python code
```console
  black --check --diff ./*.py
```

**C**
- to compile and run your C program
```console
  gcc ./Main.c -o ./ Main.app
  ./Main.app
```
- if you are using CS50's C Library then
```console
  gcc ./Main.c -o ./ Main.app -lcs50
  ./Main.app
```
- to run cpplint to lint your C code
```console
  cpplint ./*.c
```

**GitHub**
- ensure you commit your code after every major change, to keep your history and not loose anything
```console
  git add -A
  git commit -m "𝑐𝑜𝑚𝑚𝑖𝑡 𝑚𝑒𝑠𝑠𝑎𝑔𝑒"
  git push origin main
```
