## `jeopardy category`

Retrieve Jeopardy category

### Synopsis

    jeopardy category -id CATEGORY_ID

### Description

The `category` subcommand retrieves clues from a specified category by numeric ID.

### REST endpoint

    GET http://jservice.io/api/category

### Output

* Category listing
  * Category Title: `.title`
  * Category ID: `.id`
  * Clues Count: `.clues_count`

* Format
  * `.title` (`.id`) (`.clues_count`)

* Table from `.clues`
  * Question: `.question`
  * Value: `.value`
  * Answer `.answer`

    Category Title: \(.title) - \(.id)
    Clues: \(.clues_count)
    
    Clue 1 for \(.clues[0].value):
    \(.clues[0].question)

    Answer: \(.clues[0].answer)

### Options

* `-id ID`

ID of the category to return [required]

### Online documentation

http://jservice.io/