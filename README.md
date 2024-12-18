# p2pk Playground
A site for creating P2PK outputs in bitcoin i.e. paying someone's raw public key

# Here's how to try it
Just click here: https://supertestnet.github.io/p2pk_playground/

# FAQ

## What is a P2PK output?

Don't ask that yet! First ask "what's an output?" It's easier that way.

## Okay...what's an output?

An output is basically another name for a "recipient" in a bitcoin transaction. Every transaction contains two sections, Inputs and Outputs. Inputs are essentially the senders; outputs are essentially the recipients. Normally, an output in a bitcoin transaction contains two things: (1) the recipient's bitcoin address (2) an amount sent there in that transaction.

## Now can I ask what a P2PK output is?

Yes!

## This is the weirdest FAQ I've ever read.

That's not a question.

## Why is this the weirdest FAQ ever?

Because I thought it would be funny if I wrote it this way.

## What is a P2PK output?

P2PK means "pay to pubkey." A P2PK output is an output like normal except instead of sending money to a bitcoin address, the transaction sends money to a "raw pubkey." So the output looks funny -- there's just a public key there, not a normal bitcoin address.

## Wait, you can send someone bitcoin without having their bitcoin address?

Yes!

## I don't know, Rick, sounds fake.

No, really! In the early days of bitcoin, it was common to send money directly to your recipient's public key, by requesting a new one from their node whenever you wanted to send them money. Eventually, it became popular to use bitcoin addresses instead, because they were designed for "offline" usage -- you could just stick them on a website somewhere without needing to run a node and keep it online to dole out pubkeys. But bitcoin still supports the old ways because devs are sticklers about backward compatibility.

## Do people still use P2PK outputs?

The short answer is no. The long answer is yes. If you visit [Clark Moody's Bitcoin Dashboard](https://bitcoin.clarkmoody.com/dashboard/) and go to the section "Output Type Counts (90 Days)" you can see that people do occasionally use them:

![screenshot of stats about there being 30 p2pk bitcoin outputs created during a typical 90 day period](https://i.ibb.co/PNv9PLX/still-in-use.png)

But hardly ever.

##  Can I make a P2PK output?

Yes! Just follow the instructions [on this page](https://supertestnet.github.io/p2pk_playground/) and you'll make a P2PK output of your own.
