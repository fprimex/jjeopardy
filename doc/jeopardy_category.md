## `jeopardy category`

Retrieve Jeopardy category

### Synopsis

    jeopardy category -id CATEGORY_ID

### Description

The `category` subcommand retrieves clues from a specified category by numeric ID.

### REST endpoint

    GET http://jservice.io/api/category

### Options

* `-id ID`

ID of the category to return [required]

### Online documentation

http://jservice.io/

### Output

Category Title: `.title`
Category ID: `.id`
Clues Count: `.clues_count`

| Value    | Question                                           | Answer    |
| -------- | -------------------------------------------------- | --------- |
| `.value` | `.question`                                        | `.answer` | `.clues` |
