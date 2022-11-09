---
theme: shibainu
themeConfig:
  primary: '#5d8392'
  secondary: white
background: /dark_background.jpeg
class: 'text-center'
layout: cover
---

# Session 3
## Lists & Loops

---
layout: default
---

# Today's Agenda

- Lesson 2 Recap
- Activity
- Lesson 3 Preview
- Q & A

---
layout: cover
background: /dark_background.jpeg
---
# Lesson 2 Recap

---
layout: two-cols-header
---
# Lesson 2 Recap - Python Loops

<br>
<br>

::left::

## Key Questions
<br>

- what is a Python Loop?
- Why is a Python Loop important?

::right::

## Code Example

<br>

```python
for x in [1, 2, 3]:
    print(x)

"""
Output:
1
2
3
"""
```

---
layout: two-cols-header
---
# Lesson 2 Recap - Python Loops

There're 2 different types of loops in Python

::left::

## For-loop

```python
for x in [1,2,3]:
    print(x)
```

::right::

## While-Loop

```python {monaco}
x = 1
while x < 4:
    print(x)
    x += 1
```

---
layout: two-cols-header
---
# Lesson 2 Recap - Python Loops

::left::
## Nested Loops

<br>

- What are nested loops?
- How can they help optimize the code?

::right::

```python
for x in [1, 2]:
    for y in ['a', 'b']:
        print(x, y)
```