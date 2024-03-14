[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ixM8stRx)
# tPythonModule05spr24
tPythonModule05spr24

---

## Chapter 11 Video code

`import re`
`hand = open('mbox-short.txt')`
`numlist = list()`
`for line in hand:`
    `line = line.rstrip()`
    `stuff = re.findall('X-DSPAM-Confidence: ([0-9.]+)', line)`
    `if len(stuff) !=1 : continue`
    `num = float(stuff[0])`
    `numlist.append(num)`
    `print('Maximum:', max(numlist))`

    ### Windows PowerShell Terminal

    (.venv) PS C:\Users\Brendan\PycharmProjects\CIT95SPRING2024\CIT95python> py regex_Chapter11_Module5.py
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.8475
Maximum: 0.9846
Maximum: 0.9846
Maximum: 0.9907
