---
description: High level architecture diagram for Explorer platform
---

# Architecture

AlgoWorld Explorer relies on the following technologies:

* Algorand - authentication, signing and sending transactions, compiling smart signatures. Additionally, AlgoExplorer APIs are the main source of interaction with the public Indexer.
* Github Actions -  for periodic cron jobs that process tasks and assist webapp functionality
* Vercel - hosting provider

The high level diagram below demonstrates the explorer interaction with various third party components, clients and technologies:
