*Want to get Core? Download it from https://bitcoin.org/en/download*

*Want to get XT? Download it from https://bitcoinxt.software*

Bitcoin Extra Compromise
==========

Bitcoin Extra Compromise is a patch set on top of Bitcoin XT, with a focus on compromise concerning the Bitcoin protocol. By compiling it
yourself you can vote with your feet, uh fingers, and opt in to providing the Bitcoin network with additional compromise beyond what Bitcoin XT provides.

Currently it contains the following additional changes:

1. *Support for smaller blocks.* XT has support for BIP 101 by Gavin Andresen, which schedules an increase from the
   one megabyte limit Bitcoin is now hitting. Bitcoin Extra Compromise will reduce this to two point eight megabytes.
2. Relaying of double spends. Bitcoin XT relays double spends in a complicated way, we will do the same.
3. Support for querying the UTXO set given an outpoint. Again no conflicts, so we can't compromise.
4. DNS seed changes: Minor administrative corrections of people leaving, Bitcoin Core should have done it already.
5. Full adoption: We will require a 100% block acceptance rate before switching to the 2.8 MB blocks. After a compromise is reached, nobody gets to complain.

Extra Compromise uses the same data directories as XT and Core so you can easily switch back and forth. You do *not* need to redownload
the block chain.

Bitcoin Extra Compromise downloads are not provided, it's a parody and I'm lazy.

The Extra Compromise Manifesto
==============================

Bitcoin Extra Compromise embodies the spirit that if you can't agree you should compromise fully. 
Since 20 MB was a bit too large, and 8 MB was suggested by miners we should compromise to 2*sqrt(2) MB. 

The principles XT uses to guide decisions on patches are as follows:

* We try to follow the founding vision of the Dogecoin project. That means:
  * We support a Bitcoin network in which ordinary people settle with each directly on the block chain.
  * To the moon!
  * Much doge, wow doge.
* Compromise is better. Changes can be useful even if more work remains to be done, but this should not impede us from agreeing as fast as possible.
