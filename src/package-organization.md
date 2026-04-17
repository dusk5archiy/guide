# Package Organization

A package is a container used to group related pieces of code into a single
unit.

Elements that share a common any of the following:

- Target domain
- Visibility
- Technical role
- Implementation structure
- Change coupling

...will be grouped into a container named after that similarity.

When multiple similarities apply, prioritize the one that minimizes change 
impact across containers when one of them is modified.

Allow nesting to satisfy secondary similarities, provided the nesting 
clarifies context without over-complicating the hierarchy.
