<div align="left">

  # Odin Bitcoin
  High-performance Bitcoin protocol implementations in the Odin programming language.

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Language: Odin](https://img.shields.io/badge/Language-Odin-blue.svg)](https://odin-lang.org/)
  [![Bitcoin: Protocol](https://img.shields.io/badge/Bitcoin-Protocol-orange.svg)](https://bitcoin.org)
  [![Topic: Bitcoin](https://img.shields.io/badge/Topic-Bitcoin-orange.svg)](https://github.com/topics/bitcoin)

</div>

---

## About Odin-Bitcoin

**Odin-Bitcoin** is an open-source initiative dedicated to implementing various Bitcoin protocols, cryptographic primitives, and related Bitcoin projects using the **Odin** programming language.

Our core idea is to use Odin’s focus on performance, clarity, and *Data-Oriented Design* to build a suite of Bitcoin tools that are not only efficient but also easy to audit and reason about.

## Why Odin?

We chose Odin for our implementations because it provides the low-level control of C with a much safer and more modern approach to systems programming. Key benefits for Bitcoin development include:

* Precise Memory Management: Critical for handling large blockchain data and validation.
* Data-Oriented Design: Optimized for the high-performance requirements of P2P networking and block processing.
* Built-in Modern Features: Native support for slices, maps, and distinct types, which reduces boilerplate for cryptographic logic.
* Simple & Readable: A smaller language specification means easier audits for security-critical Bitcoin code.

## Planned Initiatives

While we are currently in the initial setup phase, our roadmap includes the following project areas:

* Networking: Implementing the Bitcoin P2P wire protocol and handshake.
* Light Clients: Exploring Utreexo, and build lightweight node tools to run in multiple high and low-end devices.
* Cryptography: Bindings for `secp256k1` in Odin, and pure Odin implementations of Schnorr signatures, MuSig2, Nested MuSig2 e others.

## Contributing

We do not have a general contributing set of rules yet, but first of all just don't be an asshole and we'll be fine.

As we begin pushing our first repositories, feel free to open issues, start discussions, or submit Pull Requests (do not be an asshole).
