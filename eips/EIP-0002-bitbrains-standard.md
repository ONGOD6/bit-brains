# EIP-0002 — Bity Nodes  NFT Standard

## Abstract

This document defines the Bit Brains NFT collection within the Bity Nodes ecosystem.

Bity Nodes are Ethereum-based ERC-721 digital artifacts that represent the conceptual identity of the Bit Brains project.

---

## Collection Details

Collection Name: Bity Nodes
Token Standard: ERC-721  
Blockchain: Ethereum  
Maximum Supply: 1500

---

## Metadata Standard

Each Bity Nodes token must implement the ERC-721 metadata extension.

Required metadata fields include:

- name
- description
- image
- attributes

Example metadata structure:

{
  "name": "Bity Nodes  #1",
  "description": "A Bity Nodes artifact within the Bity Nodes ecosystem.",
  "image": "ipfs://CID/1.png",
  "attributes": []
}

---

## Immutability

Once minted, Bit Brains tokens and their supply limits cannot be modified.

The collection supply is permanently capped.
