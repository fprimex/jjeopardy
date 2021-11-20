## `jeopardy random`

Retrieve random Jeopardy clues

### Synopsis

    jeopardy random [OPTIONS]

### REST endpoint

    GET http://jservice.io/api/random

### Options

* `-count N`

Amount of clues to return, limited to 100 at a time

### Documentation

http://jservice.io/

### Output

| Value    | Question                                           | Answer    |
| -------- | -------------------------------------------------- | --------- |
| `.value` | `.question`                                        | `.answer` |
