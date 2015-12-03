Ubiquitary / Rosetta Project
============================

Hypermedia is available to everyone but is shrowded in obscurity. People are
often intimidated by the word hypermedia, by the choices it present, and by the
implementation details necessary. This is so much the case that the simpler
solution of ignoring hypermedia is more often chosen; because learning
something new is hard. As hard as it might be to learn something new, more
daunting is the choice of hypermedia flavor; the choice of format is a barrier
to entry because choosing is expensive.

  > "Optimize for the better solution and it will be the obvious choice."

The goal of this project is to "Make the use of hypermedia easier and more
attractive than not using hypermedia." The [benefits of hypermedia] in API
responses are many and can solve problems outside just data and metadata
transmission.

## Drilling Down With "How"

Starting with, "Make the use of hypermedia easier."

  1. How will you "make the use of hypermedia esier"?
    + Make the consumption of hypermedia easier
      - One of the biggest oponents to wider adoption of hypermedia is ease of use
      - Foster more demand for hypermedia
  2. How will you "make the consumption of hypermedia easier"?
    + Define a way to unify response parsing
  3. How will you "define a way to unify response parsing"?
    + Define a parsing strategy which will convert any response into a 
    consistent respresentation appropriate to the environment
  4. How will you "define a parsing strategy" and how will you "define a
  'consistent representation'"?
    + Define a plugable parser to allow for community-built common format parsers
    + Define a single and consistent translation target for parser implementers
    to convert standard formats to

## Expected Outcomes

  1. Make hypermedia consumption easier
  2. Ease the burden of format decision
    - Hopefullly encouraging more data-providers to choose hypermedia
    - Increasing the number and quality of hypermedia providers
  3. Ease the use of many different hypermedia APIs in a single application a
  non-issue; as well as APIs changing hypermedia formats

[benefits of hypermedia]: benefits-of-hypermedia.md
