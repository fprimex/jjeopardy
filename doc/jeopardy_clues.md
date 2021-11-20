## `jeopardy clues`

Retrieve Jeopardy clues

### Synopsis

    jeopardy clues [OPTIONS]

### REST endpoint

    GET http://jservice.io/api/clues

### Options

* `-value VALUE`

The value of the clue in dollars

* `-category CATEGORY`

The id of the category you want to return

* `-min_date MIN_DATE`

Earliest date to show, based on original air date

* `-max_date MAX_DATE`

Latest date to show, based on original air date

* `-offset NUM`

Offsets the returned clues for e.g. pagination

### Documentation

http://jservice.io/

### Output

| Value    | Question                                           | Answer    |
| -------- | -------------------------------------------------- | --------- |
| `.value` | `.question`                                        | `.answer` |
