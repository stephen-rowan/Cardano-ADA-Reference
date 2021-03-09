---
title: DAO-NFT-Metadata
stage: draft
category: Cardano-NFT-DAO-Notes
kind: Notes
author: Stephen Whitenstall
created: 
modified: 
---

# DAO NFT-Metadata

# Contents
[The DAO NFT-Metadata github](#the-dao-nft-metadata-github)

[An intial Metadata proposal](#an-intial-metadata-proposal)

[Open Standards](#open-standards)

[Use Cases](#use-cases)

[Current NFT-DAO Meeting Notes](#current-nft-dao-meeting-notes)

[Other Current Metadata standards in progress](#other-current-metadata-standards-in-progress)

[Further Metadata Reading](#further-metadata-reading)


## The DAO NFT-Metadata github

https://github.com/NFT-DAO/NFT-Metadata

> **Note** : The location of the official DAO-NFT-Metadata github.


## An intial Metadata proposal 

@alessandro [BERRY] proposes a metadata standard ...

https://forum.cardano.org/t/cip-nft-metadata-standard/45687

> @alessandro [BERRY] - Tokens on Cardano are a part of the ledger. Unlike on Ethereum, where metadata can be attached to a token through a smart contract, this isn’t possible on Cardano because tokens are native and Cardano uses an UTxO ledger, which makes it hard to directly attach metadata to a token.
> 

**Query** : How will the Cardano smart contract upgrade affect this situation ? 

**Query** : Will not the Cardano computation layer (CCL) allow for unique token attachments with the Cardano settlement layer (CSL) ?

**Note** : The parsimonious UTxO ledger only applies to the CCL which can only provide for token exchange (no native smart contracts or accounting). Whilst the CSL allows for verbose contracts. 

**Note** : This paper expands upon the UTxO ledger paradigm contrasting it with Ethereum's account model and proposes an extended EUTXO in Goguen (https://iohk.io/en/research/library/papers/native-custom-tokens-in-the-extended-utxo-model/).


> @alessandro [BERRY] - Cardano has the ability to send metadata in a transaction, that’s the way we can create a link between a token and the metadata. To make the metadata unique to the token, they should be appended to the same transaction, where the token forge happens ..
> 

**Note** : In 'Formal Specification of the Cardano Ledger with a NativeMulti-Asset Implementation' the concept of the coin (Shelley era) is replaced with the concept of value (Goguen era) ...

> @alessandro [BERRY] - a fully worked example of comprehensive JSON-LD Semantic Web/Metadata for digital archiving of photos see this little demo prototype from many years ago https://tgalib.github.io/ 

> Each page is rendered directly from the descriptive metadata see https://github.com/tgalib/ao-682b8dc3-1c9b-4752-96f4-97545f91be18/tree/archiveobject 

### References

> Cardano Ledger Specs

https://github.com/input-output-hk/cardano-ledger-specs


> Native Custom Tokens in the Extended UTXO Model

https://hydra.iohk.io/build/5400786/download/1/eutxoma.pdf

> The Extended UTXO Model

https://iohk.io/en/research/library/papers/native-custom-tokens-in-the-extended-utxo-model/).

> Formal Specification of the Cardano Ledger with a NativeMulti-Asset Implementation

https://hydra.iohk.io/build/5737360/download/1/shelley-ma.pdf


# Open Standards

> @SofiH - Open Standards (W3C) for Cardano (In Reserve)

https://cardano.ideascale.com/a/dtd/Open-Standards-W3C-for-Cardano/338892-48088


# Use Cases

> @wolstaeb - Art is not just the visual presentation (physical or digital) but the idea of the artwork. The best example of this is Comedian by Maurizio Cattelan
> 
> https://en.wikipedia.org/wiki/Comedian_(artwork). 
> 

# Current NFT-DAO Meeting Notes

## Metadata / Schema Notes 2/25/2021

https://docs.google.com/document/d/1eKV7yPE3ng4SPSBW5uxLn_THaUMKL8vi5FBMWExUZ8s


# Other Current Metadata standards in progress

## Progress report: Interchain NFT+Metadata Standards

> The InterNFT Working Group is drafting a set of Interchain standards that will advance the state of the art for Non-fungible Tokens and the Metadata associated with uniquely identified tokenised resources. Our mission is to make NFTs interoperable across blockchain networks and to enable ownership, control and rights management of NFT metadata and linked resources, regardless of where these are located.

https://blog.cosmos.network/progress-report-interchain-nft-metadata-standards-94770dfe3bb1

> **Note** : This working group is already looking at metadata standards as applied to "Interchain NFTs" (Cross blockchain platform NFTs).
> 
> **Quote** "The metadata standard intends to make the representations about the past, current, or desired future states of an NFT resource machine-readable, machine understandable and verifiable. Regardless of where the metadata is located."
> 

Draft whitepaper : https://github.com/interNFT/nft-rfc/blob/main/nft-rfc-002.md


### ERC-721 metadata standards and IPFS

> How BlockRocket & KnownOrigin utilises ERC-721 metadata & IPFS to build a digital assets marketplace 
https://medium.com/blockchain-manchester/erc-721-metadata-standards-and-ipfs-94b01fea2a89


# Further Metadata Reading

> The Coming Merger of Blockchain and Knowledge Graphs
> 

https://medium.com/@kurtcagle/the-coming-merger-of-blockchain-and-knowledge-graphs-685e052c614c


> InterPlanetary Linked Data

https://docs.ipld.io/

> Graph Databases

https://en.wikipedia.org/wiki/Graph_database

