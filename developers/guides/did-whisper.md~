# Send Encrypted Messages with DID Whisper Bin

[DID Whisper Bin](https://github.com/digitalbazaar/did-whisper) is a demo
application designed to showcase what you can do once you've generated a DID.

## Requirements

* [Node v8.6+](https://nodejs.org/en/download/)
* Recipient will need a registered DID
* Sender can install `did-whisper` client to send the message, or use the
  [demo whisper client](https://whisper.demo.veres.one/)
* To decrypt the message, recipient will need to install `did-whisper` client

## Recipient - Generate a Decentralized Identifier

To receive an encrypted message that only you can decode, you need to have a
DID registered on a ledger (the Testnet ledger is fine).

If you have not already done so:
[Create a DID (Decentralized Identifier)](create-did.md)

## Sender - Get Recipient's DID

Much like you need to know a recipient's email address to send them an email,
you'll need their DID to send them an encrypted message. Ask the recipient to
give you their DID (it will look something like `did:v1:test:nym:2pfPix2t...`).

## Sender - Use `did-whisper` To Send Message

Once you know somebody's DID, you can send them self-expiring encrypted
messages, either by:

1. Follow the instructions to [Install a `did-whisper
   client`](https://github.com/digitalbazaar/did-whisper#install), or
2. Use the [demo whisper client](https://whisper.demo.veres.one/) hosted by
   Veres One.

In either case, you will end up with a URL to an anonymous encrypted message,
something like `https://whisper.demo.veres.one/whisper/r1uKEuLnM`.

Send that URL to the recipient via your preferred channel (email, chat, etc).

## Recipient - Decrypt Message

If you receive a Whisper URL, to decrypt it, you will need to:

1. [Install a `did-whisper
   client`](https://github.com/digitalbazaar/did-whisper#install) (on the same
   machine that your DID was generated on).
2. Run `did-whisper decrypt <saved message url>`

For advanced usage, see the [decrypting
instructions](https://github.com/digitalbazaar/did-whisper#decrypting-messages).
