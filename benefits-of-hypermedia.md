The Benefits of Hypermedia
==========================

  - Explorable API ([soabits])
  - Inline Documentation ([soatbits])
  - Simple Client Logic ([soatbits])
  - Server-owned URLs ([soatbits])
  - Content Offloading ([soatbits])
  - Versioning With Links ([soatbits])
  - Multiple Implementations ([soatbits])
  - Isolation Of Changes
  - Explicit Workflow

### Isolation of Changes

Isolation of changes refers to keeping changes to as few "layers" as possible;
ideally one. Where changes need to be made, and subsequently where errors need
to be tracked down, is of great importance to teams managing applications.

**An overly simplified example:**

  > A client application exists which displays a list of links to users; which
  links to display are decided by the authorization rights of a given user. The
  user's access rights will likely change over time, and across many users will
  happen frequently. The solution using a Hypermedia API would be to provide
  the list of links in API responses and simply display thos links in the
  application; this keeps a single point of authority in the API.

### Explicit Workflow

Explicit workflow allows the API to control the path through a set of steps
allowing that path to change and evolve over time. Consuming applications need
only know how to "follow the path".

**An overly simplified example:**

  > A client application is developed to follow links, in API responses, to
  establish a "flow" in the application; the flow being "A -> B -> C -> Z". A
  business decision is made that changes the flow to "A -> C -> B -> D -> Z".
  The necessary change is then made only in the API layer of the system and the
  client application remains unchanged.

[soabits]: http://soabits.blogspot.no/2013/12/selling-benefits-of-hypermedia.html
