# Veres One Nodes

Nodes are responsible for providing computational and storage resources for
the Network. As the system is permissionless, any person or organization may
run one or more Nodes.

## What is a Node?

A Node on the Veres One Network contains a record of every event that has
has made its way into the blockchain over time. It is connected to many of
the other Nodes in the Network and can "gossip" events to other Nodes in the
Network. When a Node receives an event, if it is an Elector, it may suggest
that an event is included in the blockchain. If 2/3rds of the Network sees
the event, and it is valid, then the event will be included in the blockchain.

A node contains a programmatic interface that developers can use to submit
new events to the Network as well as query the blockchain history and
its current state.

## Running a Node

Anyone may run a node by using the instructions provided by the
[Veres One Node Software](https://github.com/veres-one/veres-one).

## Electors

An Elector is a special type of Node in the Network that can suggest events
for inclusion in the blockchain. There are often many electors for a particular
block in the blockchain and these electors are randomly chosen per block to
increase Network security. A constantly shifting set of Electors means that
it is far more difficult for an attacker to disrupt the normal operation of
the Network.

## Becoming an Elector

Since Electors hold a position of privilege on the Network, they must go
through a lightweight approval process such that the individual or organization
running the Node provides contact information, such as a phone number and
email address, where they may be contacted in the event of an emergency. This
is done in an attempt to reduce the number of bad actors in the Network and
ensure that the Node operator may be reached in the event of an emergency.

To become an Elector you must:

1. Log into your Node.
2. Go to "Administration/Elector".
3. Fill out every field that is required.
4. Click the "Request Elector Credential" button.

An individual from the Veres One Project will check the information submitted
and, if approved, will transmit the Elector Credential to your Node. Your
Elector Credential will not be active until you log back into your Node and
activate it.
