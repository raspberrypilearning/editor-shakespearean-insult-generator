## Create a sentence

Each line has three words.

You can build a sentence using each word.

Add code to split the line up wherever there is a comma, and save it as a list of `words`.

Change the final line to first output `Thou`, then each word in the list of words in turn.

```python line_numbers="true" line_number_start="1" line_highlights="4-5"
with open("insults.csv", "r") as f:
    lines = f.readlines()
    line_number = 0
    words = lines[line_number].split(",")
    print(f"Thou {words[0]} {words[1]} {words[2]}")
```

## Now run your code

Run your code and check that the first line is turned into an insult that starts with `Thou`.

```
Thou artless base-court apple-john
```
