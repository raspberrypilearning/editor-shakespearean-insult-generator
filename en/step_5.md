<h2 class="c-project-heading--task">Get a different insult</h2>
--- task ---

Choose a different line.
--- /task ---

Change the `line_number` variable to another number between 0 and one less than the length. 

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 1
line_highlights: 3
---
with open("insults.csv", "r") as f:
  lines = f.readlines()
  line_number = 32
  words = lines[line_number].split(",")
  print(f"Thou {words[0]} {words[1]} {words[2]}")


--- /code ---

--- task ---
</div>

Click **Run**. You should see a different insult printed.

--- /task ---



<div class="c-project-output">
<pre>Thou quailing motley-minded measle</pre>
</div>
