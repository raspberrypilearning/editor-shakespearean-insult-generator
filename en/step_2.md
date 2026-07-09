## Lists in Python

Each line contains three words - the first two are **adjectives** (describing words) and the last is a **noun** (a thing).

Change your code so that it only prints the first line in the list. The numbering of the lines always **starts from zero** so the first line in the list is `lines[0]`.

```python line_numbers="true" line_number_start="1" line_highlights="3-4"
with open("insults.csv", "r") as f:
    lines = f.readlines()
    line_number = 0
    print(lines[line_number])
```

## Now run your code

Run your code and check that the first line from `insults.csv` is printed in the text output.

```
artless,base-court,apple-john
```
