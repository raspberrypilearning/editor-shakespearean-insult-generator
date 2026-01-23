<h2 class="c-project-heading--task">Random insults</h2>
--- task ---

You can select random words to build a random insult.
--- /task ---


Add some code to import the `random` library.

Then use the `randint` function from the `random` library to choose a random line from the file to generate the insult. 

<div class="c-project-code">
--- code ---
---
language: python
line_numbers: true
line_number_start: 1
line_highlights: 1, 4
---
import random
with open("insults.csv", "r") as f:
  lines = f.readlines()
  line_number = random.randint(0, len(lines)-1)
  words = lines[line_number].split(",")
  print(f"Thou {words[0]} {words[1]} {words[2]}")

--- /code ---
</div>

--- task ---

Click **Run**. You should see a _random_ insult printed.

**Note**: This example is random, so your output will probably be different!

--- /task ---

<div class="c-project-output">
<pre>Thou mewling idle-headed lewdster</pre>
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- The line chosen will be a line between 0 and the number of lines available minus one.
- The random choice needs to be between 0 and the length minus one because the line numbering starts at 0. For example, in the list `['a', 'b', 'c']`, the length of the list is 3 because it contains 3 items, but the last item in the list is numbered `2` because the numbering system starts with 0.

</div>
