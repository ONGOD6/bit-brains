# EIP-0001 — NODE PICKLES NFT Standard

## Abstract

This document defines the standard for the NODE PICKLES NFT collection within the Bit Brains ecosystem.

NODE PICKLES are Ethereum ERC-721 digital collectibles representing pixel-art pickle characters.

---

## Collection Details

Name: NODE PICKLES 
Token Standard: ERC-721  
Blockchain: Ethereum  
Maximum Supply: 1500

---

## Metadata Standard

Each NODE PICKLES token MUST provide metadata using the ERC-721 metadata extension.

Required metadata fields:

- name
- description
- image
- attributes

Example:

{
  "name": "NODE PICKLES  #1",
  "description": "A NODE PICKLES from the Bity Nodes  ecosystem.",
  "image": "ipfs://CID/1.png",
  "attributes": []
}

---

## Traits

Traits define visual characteristics of each NODE PICKLES .

Examples include:

- Background
- Body
- Eyes
- Mouth
- Accessories

---

## Immutability

Once minted, NODE PICKLES metadata and supply are immutable.

The collection supply cannot exceed the maximum cap.
