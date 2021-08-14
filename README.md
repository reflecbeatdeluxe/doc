# doc

## Fumen

### GET

GET returns fumen list

#### Params

- id
- name
- description
- uploader
- creator
- artist
- is_unlocked

### POST

POST create a new fumen metadata

### PUT

PUT updates an existing fumen metadata

## Pack

### GET

GET returns pack list

#### Params

- id
- name
- description
- creator

### POST

POST create a new pack metadata

### PUT

PUT updates a new pack metadata

## Comment

### GET

Get returns comment list

#### Params

- type: enum of `["fumen_comment", "pack_comment"]`
- creator
- id: fumen id or pack id

### POST

Post creates a new comment

### PUT

Put updates an existing comment

