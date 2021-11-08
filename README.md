OmniLite
=========================================

[![Build Status](https://travis-ci.com/omnilite/OmniLite.svg?branch=0.9.0)](https://travis-ci.org/omnilite/omnilite)

What is the Omni Layer
----------------------

The Omni Layer is a communications protocol that uses the Litecoin block chain to enable Smart Properties (tokens) and a Decentralized Exchange. A common analogy that is used to describe the relation of the Omni Layer to Litecoin is that of HTTP to TCP/IP: HTTP, like the Omni Layer, is the application layer to the more fundamental transport and internet layer of TCP/IP, like Litecoin.

What is OmniLite
-----------------

OmniLite is a fast, portable Omni Layer implementation that is based off the Litecoin codebase (currently 0.18.1). This implementation requires no external dependencies extraneous to Litecoin, and is native to the Litecoin network just like other Litecoin nodes. It currently supports a wallet mode and is seamlessly available on three platforms: Windows, Linux and MacOS. Omni Layer extensions are exposed via the JSON-RPC interface. Development has been consolidated on the OmniLite product, and it is the reference client for the Omni Layer.

Current feature set:
--------------------

* Broadcasting of simple send (tx 0) [doc](src/omnicore/doc/rpc-api.md#omni_send), and send to owners (tx 3) [doc](src/omnicore/doc/rpc-api.md#omni_sendsto)

* Obtaining a Omni Layer balance [doc](src/omnicore/doc/rpc-api.md#omni_getbalance)

* Obtaining all balances (including smart property) for an address [doc](src/omnicore/doc/rpc-api.md#omni_getallbalancesforaddress)

* Obtaining all balances associated with a specific smart property [doc](src/omnicore/doc/rpc-api.md#omni_getallbalancesforid)

* Retrieving information about any Omni Layer transaction [doc](src/omnicore/doc/rpc-api.md#omni_gettransaction)

* Listing historical transactions of addresses in the wallet [doc](src/omnicore/doc/rpc-api.md#omni_listtransactions)

* Retrieving detailed information about a smart property [doc](src/omnicore/doc/rpc-api.md#omni_getproperty)

* Retrieving active and expired crowdsale information [doc](src/omnicore/doc/rpc-api.md#omni_getcrowdsale)

* Sending a specific FTC amount to a receiver with referenceamount in `omni_send`

* Creating and broadcasting transactions based on raw Omni Layer transactions with `omni_sendrawtx`

* Functional UI for balances, sending and historical transactions

* Creating any supported transaction type via RPC interface

* Support for class B (multisig) and class C (op-return) encoded transactions

* Support of unconfirmed transactions

* Creation of raw transactions with non-wallet inputs

Support:
--------

* [GitHub](https://github.com/omnilite/omnilite/issues)
* [Email](mailto:contact@litecoinfoundation.net)

Disclaimer, warning
-------------------

This software is EXPERIMENTAL software. USE ON MAINNET AT YOUR OWN RISK.

By default this software will use your existing Litecoin wallet, including spending litecoins contained therein (for example for transaction fees or trading).
The protocol and transaction processing rules for the Omni Layer are still under active development and are subject to change in future.
OmniLite should be considered a beta product, and you use it at your own risk. Neither the Litecoin Developers, Omni Foundation nor the OmniLite developers assumes any responsibility for funds misplaced, mishandled, lost, or misallocated.

Further, please note that this installation of OmniLite should be viewed as EXPERIMENTAL. Your wallet data, litecoins and Omni Layer tokens may be lost, deleted, or corrupted, with or without warning due to bugs or glitches. Please take caution.

This software is provided open-source at no cost. You are responsible for knowing the law in your country and determining if your use of this software contravenes any local laws.

PLEASE DO NOT use wallet(s) with significant amounts of litecoins or Omni Layer tokens while testing!
