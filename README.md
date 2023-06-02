# first-last

This collection of bash scripts aims to improve readability in complex bash scripts that involve piped data processing. It provides a set of convenient utilities to extract specific elements from piped input, simplifying data manipulation.

## Utils

### `first` / `1`, `second` / `2`, `third` / `3`, ...

These utilities retrieve the corresponding element from the piped input:

```bash
echo "one two three four five six seven eight nine ten" | first
one
```

Alternatively, you can use numeric equivalents like `1`, `2`, `3`, and so on:

```bash
echo "one two three four five six seven eight nine ten" | 1
one
```

You can use select any element from 1 to 10.

### `last`-utils

Additionally, the `last` utility retrieves the last element from the input. To access the elements in reverse order, you can use `last-1`, `last-2`, `last-3`, and so on.

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

You can run the provided test suite to validate the functionality of each utility. The test results will be displayed, indicating whether each test passed or failed, represented by a green tick (✓) for passed tests.

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
