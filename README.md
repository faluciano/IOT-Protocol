# IOT-Protocol

Internet protocol implementation for IOT lightbulb

## Goals:

Design an internet protocol that communicates over UDP with an IOT lightbulb.

## Requirements:

1. Turn light on and set color
2. Change color of the lightbulb
3. Determine if the status of the lightbulb(on/off,color)
4. Turn the light off
5. Error reporting (Bulb not working, not a valid color etc.)
6. Show that the operation was successful 

## Must specify:

1. Message format(fields in message,size in bytes, possible values)
2. Message semantics(What function each message type performs and possible results)
3. Trace output that client and server program should display
4. Command-line arguments that specify ip and port the server is running on and enable any test case to be executed 