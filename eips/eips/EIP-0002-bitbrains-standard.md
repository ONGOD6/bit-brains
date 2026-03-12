# EIP-0002 — Bit Brains NFT Standard

## Abstract

This document defines the Bit Brains NFT collection within the Bit Brains ecosystem.

Bit Brains are Ethereum-based ERC-721 digital artifacts that represent the conceptual identity of the Bit Brains project.

---

## Collection Details

Collection Name: Bit Brains  
Token Standard: ERC-721  
Blockchain: Ethereum  
Maximum Supply: 1500

---

## Metadata Standard

Each Bit Brain token must implement the ERC-721 metadata extension.

Required metadata fields include:

- name
- description
- image
- attributes

Example metadata structure:

{
  "name": "Bit Brain #1",
  "description": "A Bit Brain artifact within the Bit Brains ecosystem.",
  "image": "ipfs://CID/1.png",
  "attributes": []
}

---

## Immutability

Once minted, Bit Brains tokens and their supply limits cannot be modified.

The collection supply is permanently capped.
