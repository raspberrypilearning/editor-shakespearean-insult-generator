<h2 class="c-project-heading--task">Lists in Python</h2>
--- task ---

Each line contains three words - the first two are **adjectives** (describing words) and the last is a **noun** (a thing). 

--- /task ---

Change your code so that it only prints the first line in the list. The numbering of the lines always **starts from zero** so the first line in the list is `lines[0]`.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 1
line_highlights: 3-4
---
with open("insults.csv", "r") as f:
    lines = f.readlines()
    line_number = 0
    print(lines[line_number])

--- /code ---
</div>

--- task ---

Click **Run** and you should see this in Text output.

--- /task ---

<div class="c-project-output">
<pre>artless,base-court,apple-john</pre>
</div>
