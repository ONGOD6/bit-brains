# EIP-0001 — Pickle Punks NFT Standard

## Abstract

This document defines the standard for the Pickle Punks NFT collection within the Bit Brains ecosystem.

Pickle Punks are Ethereum ERC-721 digital collectibles representing pixel-art pickle characters.

---

## Collection Details

Name: Pickle Punks  
Token Standard: ERC-721  
Blockchain: Ethereum  
Maximum Supply: 1500

---

## Metadata Standard

Each Pickle Punk token MUST provide metadata using the ERC-721 metadata extension.

Required metadata fields:

- name
- description
- image
- attributes

Example:

{
  "name": "Pickle Punk #1",
  "description": "A Pickle Punk from the Bit Brains ecosystem.",
  "image": "ipfs://CID/1.png",
  "attributes": []
}

---

## Traits

Traits define visual characteristics of each Pickle Punk.

Examples include:

- Background
- Body
- Eyes
- Mouth
- Accessories

---

## Immutability

Once minted, Pickle Punks metadata and supply are immutable.

The collection supply cannot exceed the maximum cap.
