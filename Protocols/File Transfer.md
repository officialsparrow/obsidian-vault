New messages are pushed to a open socket if there is one for the receiver. If there is none, it is added to a "new messages queue". If a new socket is created, the "new messages queue" is checked and all messages for the receiver are sent to it.

All files, including pictures etc. are treated as binary data.