## What is Messaging?

> *Messaging* is a technology that enables high-speed, asynchronous, program-to-program communication with reliable delivery.

Programs communicate by sending packets of data called *messages* to each other.

*Channels*, also known as queues, are logical pathways that connect the programs and convey messages.

A *sender* or *producer* is a program that sends a message by writing the message to a channel.

A *receiver* or *consumer* is a program that receives a message by reading (and deleting) it from a channel.

A message actually contains two parts, a *header* and a *body*.

1.  The *header* contains meta-information about the message — who sent it, where it’s going, and so on; this information is used by the messaging system and is mostly ignored by the applications using the messages.
2.  The *body* contains the application data being transmitted and is usually ignored by the messaging system. In conversation, when an application developer who is using messaging talks about a message, usually referring to the data in the body of the message.
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzIwNTEwODk2LDE4MDgzNTUxOTZdfQ==
-->