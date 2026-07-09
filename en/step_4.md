## Get a different insult

Choose a different line.

Change the `line_number` variable to another number between 0 and one less than the length.

```python line_numbers="true" line_number_start="1" line_highlights="3"
with open("insults.csv", "r") as f:
    lines = f.readlines()
    line_number = 32
    words = lines[line_number].split(",")
    print(f"Thou {words[0]} {words[1]} {words[2]}")
```

## Now run your code

Run your code and check that changing the line number prints a different insult.

```
Thou quailing motley-minded measle
```
