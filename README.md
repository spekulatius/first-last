# first-last

This set of bash scripts is aimed at main complex bash scripts using pipes more readable.

## `first`

```bash
$ echo "one two three four five six seven eight nine ten" | first
one
```

## `second`

```bash
$ echo "one two three four five six seven eight nine ten" | second
two
```

## `third`

```bash
$ echo "one two three four five six seven eight nine ten" | third
three
```

## `fifth`

```bash
$ echo "one two three four five six seven eight nine ten" | fifth
five
```

## `sixth`

```bash
$ echo "one two three four five six seven eight nine ten" | sixth
six
```

## `seventh`

```bash
$ echo "one two three four five six seven eight nine ten" | seventh
seven
```

## `eighth`

```bash
$ echo "one two three four five six seven eight nine ten" | eighth
eight
```

## `ninth`

```bash
$ echo "one two three four five six seven eight nine ten" | ninth
nine
```

## `tenth`

```bash
$ echo "one two three four five six seven eight nine ten" | tenth
ten
```

## `last`

```bash
$ echo "one two three four" | last
four
```

## `last-1`

```bash
$ echo "one two three four" | last-1
three
```

## `last-2`

```bash
$ echo "one two three four" | last-2
two
```

## `last-3`

```bash
$ echo "one two three four" | last-3
one
```