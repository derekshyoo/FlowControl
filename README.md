# FlowControl
Flow Control between the Data Link Layers of two hosts

## Stop and Wait Protocol
First, we want to implement the stop and wait protocol
for the flow control between two hosts and their Data Link Layers

The way this works is one host sends frames to the other host
and waits for acknowledgement frame from tthe receiver.
If the sender doesn't get an acknowledgement after some time,
it resends the frame.
