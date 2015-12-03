Ubiquitary / Rosetta Project
============================

  > "Optimize for the better solution and it will become the obvious choice."

The goal of this project is to "Make the use of hypermedia easier and more
attractive than not using hypermedia." The [benefits of hypermedia] in API
responses are many and can solve problems outside just data and metadata
transmission.

## Drilling Down With "How"

Starting with, "Make the use of hypermedia easier."

  1. How will you do that?
    + Make the consumption of hypermedia easier
  2. How will you do that?
    + Define a way to unify response parsing
  3. How will you do that?
    + Define a parsing strategy
    + Define a consistent representation format for the parser to output
  4. How will you do those?
    + Define a plugable parser to allow for community-built common format
      parsers allowing custom parsers to be plugged in where necessary
    + Define a single and consistent translation target for parser implementers
      to convert standard formats to

## Expected Outcomes

  1. Make hypermedia consumption easier
    + Foster more demand for hypermedia
  2. Ease the burden/risk of format decision
    + Hopefullly encouraging more data-providers to choose hypermedia
    + Increasing the number and quality of hypermedia providers
  3. Ease the use of many different hypermedia APIs in a single application a
    non-issue; as well as APIs changing hypermedia formats

[benefits of hypermedia]: benefits-of-hypermedia.md
