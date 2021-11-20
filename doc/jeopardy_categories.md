## `jeopardy categories`

Retrieve Jeopardy categories

### Synopsis

    jeopardy categories [OPTIONS]

### REST endpoint

    GET http://jservice.io/api/categories

### Options

* `-count N`

Amount of clues to return, limited to 100 at a time

* `-offset N`

Offsets the returned clues for e.g. pagination

### Documentation

http://jservice.io/

### Output

| ID    | Clues Count    | Title    |
| ----- | -------------- | -------- |
| `.id` | `.clues_count` | `.title` |
