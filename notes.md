# Web DB IV

## A good data model...

- captures all the data the system needs
- captures only the data the system needs
- reflects reality
- is flexible, can evolve with the system
- guarantees data integrity
- is driven by the way the data will be used

## Components

- entities === resources -> tables
- attributes -> columns
- relationships === sub-routes (/recipes/:id/ingredients) -> Foreign Keys

## Workflow

- identify entities -> squares on paper
- identify relationships -> lines joining the squares
- identify attributes -> bulleted list

### Tracks

- id, pk, integer, auto-incrementing
- name, string(128), unique, required

## Relationships

- one to one -> one to zero or one
- one to many <- most common one
- many to many (smoke and mirrors, an illusion) <- a third table

## Mantras

- for a many to many we need: a third table
- the most important tools for data modelling: pen & paper and ears
- (one to many) relationships translate to: FK (Foreign Keys)
- where does a foreign key go? : on the many side
