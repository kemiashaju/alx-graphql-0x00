# Episode Query by ID

This directory contains GraphQL queries to retrieve episode details using the `episode(id: ID!)` field.

## Files Included

- episode-id-1.graphql
- episode-id-1-output.json
- episode-id-2.graphql
- episode-id-2-output.json
- episode-id-3.graphql
- episode-id-3-output.json
- episode-id-4.graphql
- episode-id-4-output.json

## Fields Queried

- id  
- name  
- air_date  
- episode  

## Example Query

```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
