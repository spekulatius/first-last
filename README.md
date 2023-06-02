# first-last

This collection of bash scripts is designed to enhance readability, particularly in complex bash scripts that utilize pipes. The scripts provide convenient functionality to extract specific elements from piped input, making it easier to work with and manipulate data.

## Utils

### `first`

```bash
$ echo "one two three four five six seven eight nine ten" | first
one
```

### `second`

```bash
$ echo "one two three four five six seven eight nine ten" | second
two
```

### `third`

```bash
$ echo "one two three four five six seven eight nine ten" | third
three
```

### `fifth`

```bash
$ echo "one two three four five six seven eight nine ten" | fifth
five
```

### `sixth`

```bash
$ echo "one two three four five six seven eight nine ten" | sixth
six
```

### `seventh`

```bash
$ echo "one two three four five six seven eight nine ten" | seventh
seven
```

### `eighth`

```bash
$ echo "one two three four five six seven eight nine ten" | eighth
eight
```

### `ninth`

```bash
$ echo "one two three four five six seven eight nine ten" | ninth
nine
```

### `tenth`

```bash
$ echo "one two three four five six seven eight nine ten" | tenth
ten
```

### `last`

```bash
$ echo "one two three four" | last
four
```

### `last-1`

```bash
$ echo "one two three four" | last-1
three
```

### `last-2`

```bash
$ echo "one two three four" | last-2
two
```

### `last-3`

```bash
$ echo "one two three four" | last-3
one
```

## Installation

Copy the scripts somewhere and `chmod +x`

## Tests

You can run the test suite as needed:

```bash
$ ./test
Testing 'first':
✓ Test passed

Testing 'second':
✓ Test passed

Testing 'third':
✓ Test passed

Testing 'fifth':
✓ Test passed

Testing 'sixth':
✓ Test passed

Testing 'seventh':
✓ Test passed

Testing 'eighth':
✓ Test passed

Testing 'ninth':
✓ Test passed

Testing 'tenth':
✓ Test passed

Testing 'last':
✓ Test passed

Testing 'last-1':
✓ Test passed

Testing 'last-2':
✓ Test passed

Testing 'last-3':
✓ Test passed
```