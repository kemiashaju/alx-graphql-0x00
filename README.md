# alx-graphql-0x00
# Character Query by ID

This directory contains GraphQL queries to retrieve character information using the `character(id: ID!)` field from the GraphQL API.

## Files Included

- `character-id-1.graphql`
- `character-id-1-output.json`
- `character-id-2.graphql`
- `character-id-2-output.json`
- `character-id-3.graphql`
- `character-id-3-output.json`
- `character-id-4.graphql`
- `character-id-4-output.json`

## Fields Queried
- id
- name
- status
- species
- type
- gender

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
