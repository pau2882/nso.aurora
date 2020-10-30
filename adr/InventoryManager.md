# ADR template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections:

# Title
Inventory Manager should take care of the fridges

## Status

accepted

## Context

Should we have an Inventory Manager and a Fridge Manager where the Inventory Manager would hold the food items and Fridge would manage the physical fridges?

## Decision

Inventory Manager can manage the following:
- manage fridges
- manage food items including their pricing
- manage the number of items in each fridge

## Consequences

It would be easier to have an Inventory Manager to take care of all items rather than 2 separate managers.
