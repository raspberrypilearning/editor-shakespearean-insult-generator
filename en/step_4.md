<h2 class="c-project-heading--task">Create a sentence</h2>
--- task ---
Each line has three words.
You can build a sentence using each word.
--- /task ---

Add code to split the line up wherever there is a comma, and save it as a list of `words`.

Change the final line to first output `Thou`, then each word in the list of words in turn.

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 1
line_highlights: 4,5
---
with open("insults.csv", "r") as f:
    lines = f.readlines()
    line_number = 0
    words = lines[line_number].split(",")
    print(f"Thou {words[0]} {words[1]} {words[2]}")

--- /code ---
</div>

--- task ---

Click **Run** to check the result looks like this.

--- /task ---

<div class="c-project-output">
<pre>Thou artless base-court apple-john</pre>
</div>

