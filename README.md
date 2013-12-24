Ponycoin, an equestion cryptocurrency
=====================================
Just when you though the bitcoin fad couldn't get any weirder...

http://pr.saltyhashes.com/blog/introducing-the-weirdest-bitcoin-derivative-yet/

Ponycoin Copyright (c) 2013 Josh and Contributers
Bitcoin Copyright (c) 2009-2013 Bitcoin Core Developers

* RPC 9338
* P2P 9339

What is Bitcoin?
----------------

From the bitcoin README:

Bitcoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Bitcoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Bitcoin Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Bitcoin Core software, see http://www.bitcoin.org/en/download.

What is Ponycoin?
----------------

In laymans terms:

Ponycoin is a modification of the bitcoin currency. Unlike bitcoin, however, the blockchain
in Ponycoins generate much faster than the bitcoin block chain, but give a smaller reward
to ponycoin miners.

License
-------

Bitcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Fork from bitcoin->Change stuff that I don't want in ponycoin->Merge with ponycoin.

Q/A
---

Q: Why would I want to use ponycoin, isn't there like a bazillion other cyptocurrencies?
* A: Heaven knows why you'd want to use something like this..

Q: Who are you?
* A1: Are you stalking me?
* A2: I was a person who jumped into the bitcoin wagon during 2010, when bitcoin wasn't so commercialized.

Q: Ponycoin is for retarded losers. You're a loser.
* A1: First of all, that isn't even a question.
* A2: What are you doing over at my github page then?

Q: This is amazing, I love you! How can I show you how much I love you?
* A: Well, you could talk about ponycoins to your Brony friends, or maybe even contribute.

Q: I know C, C++, XML, Javascript, Aseembly, QT, GTK, Cryptography, and a gazillion other things! How can I help?
* A: You could use your fantastic Git skillz to contribute to the code by forking, modifying,
and sending me a pull request.

Q: Is this like dogecoins or something?
* A: Yes

Q: Should I invest in ponycoins?
* A: If you want to lose all of your money, then yes.

Q: Do you think something like bronycon or EQD will use these things in the future?
* A: Maybe.

Documentation on the Ponycoin distribution algorithm
-----------------------------------------------------------------
* Ponycoins use the same address type as Litecoins. (As ponycoins are based on litecoins)
* There are a total of 100,000,000,000 avaiable coins (BITS).
* For the first 60,000 coins: 1 + (sqrt(nHeight)*64) reward.
* For the first 120,000 coins: 1 + (sqrt(nHeight)*32) reward.
* For the first 240,000 coins: 1 + (sqrt(nHeight)*16) reward.
* For the first 480,000 coins: 1 + (sqrt(nHeight)*8) reward.
* For the first 960,000 coins: 1 + (sqrt(nHeight)*4) reward.
* For the first 1,920,000 coins: 1 + (sqrt(nHeight)*2) reward.
* All other blocks past 1,920,000: Cut in half every 2,560,000 blocks.

Coin values
-----------

* BITS = 1 Ponycoin
* mBITS = 1/1000 of a BIT
* μBITS = 1/1,000,000 of a BIT
