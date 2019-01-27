# pastebin
A basic pastebin-like application


## Requirements

Functional Requirements:
- users should be able to upload/paste their data and get a unique url to access it
- users will only be able to upload text
- data and links will expire after a specific timespan automatically. the expiration time can be specified by the user.
- users should be able to pick a custom alias for their paste (in some ways, this makes the application less secure, as other user can simply guess the endpoint. Also, how to deal with duplicate namespace?)

Non-functional requirements:
- the system should be highly reliable, any data uploaded should not be lost
- the system should be highly available. If the service is down, no users will be able to access their pastes.
- users should be able to access their pastes in real-time with minimum latency.
- paste links should not be guessable.

Extended requirements:
- APIs can be available as SASS
- analytics on the number of pastes by the user
- rate-limit of the number of API calls by users
- limit the size of the pastable content


## Capacity Estimation and Constraints

- Traffic Estimates
- Storage Estimates
- Bandwidth Estimates
- Memory Estimates

## APIs

## TODOs

Look into minio for storage.
