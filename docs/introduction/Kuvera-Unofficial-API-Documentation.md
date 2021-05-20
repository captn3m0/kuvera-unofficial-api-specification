---
tags: [introduction]
---

# Kuvera Unofficial API Documentation

Welcome to the unofficial Kuvera API docs. Kuvera has a pretty good read-only API that has CORS enabled for all domains. As an example, you can find a demo of the complete NIFTY 50 graph generated here.

## Data Available:

1. NIFTY50 Historical Value
2. List of AMCs
3. List of Mutual Fund Plans
4. Categories of Mutual Funds, along with returns for various time ranges.
5. Details about a specific Mutual Fund Plan
6. Top bought, sold, and watched funds on Kuvera

## Authentication

None of the APIs need any authentication.

## CORS

CORS is enabled for all requests across all domains, so you don't need to proxy any requests. You can directly build your static site using this API.

## Disclaimer

I've documented this for educational purposes, because I wanted a way to get the latest NAV of my Mutual Funds in a script. If you use this for any purpose, it is at your own liability. If Kuvera makes any changes, this may break - I don't give any guarantees.