---
author: Noah Jones
title: Proof of Burn
---

Charles Hoskinson asked us to implement
[Proof-of-burn](https://eprint.iacr.org/2019/1096.pdf).

The proof-of-burn satisfies the following: 

1. Unspendability
2. Binding
3. Uncensorability

> We propose the following properties for burn
> protocols. Unspendability, which mandates that an address which
> verifies correctly as a burn address cannot be used for spending;
> binding, which allows associating metadata with a particular burn;
> and uncensorability, which mandates that a burn address is
> indistinguishable from a regular cryptocurrency address.

In addition to this model, I wonder if one can be performed in which
money is sent to an address the redeemer of which requires the UTXO
that created the redeemer in the first place, essentially causing the
tokens at that address to be unspendable by the same logic as that
which makes an NFT an NFT -- by virtue of fees and the uniqueness of
the UTxO address.
