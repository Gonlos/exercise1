# MessageApp

## Methods

### send(destination,message) -> {status,data}
destination -> String, max 50 char

message -> String, max 200 char

## End points

### POST /message body -> {destination,message} -> {status,data}
destination -> String, max 50 char
message -> String, max 200 char

## Founded Errors
without body must indicate needed fields
json format
send number
empty string
objects
functions
scape characters
very characters
