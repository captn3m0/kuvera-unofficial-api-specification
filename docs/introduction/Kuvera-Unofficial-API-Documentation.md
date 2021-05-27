---
tags: [introduction]
---

# Kuvera Unofficial API Specification

Welcome to the unofficial Kuvera API docs. Kuvera has a decent good read-only API that this project documents.



## Data Available:

1. NIFTY50 Historical Value
2. List of AMCs
3. List of Mutual Fund Plans
4. Categories of Mutual Funds, along with returns for various time ranges.
5. Details about a specific Mutual Fund Plan(s)
6. Top bought, sold, and watched funds on Kuvera
7. Fixed Deposit Plans
8. Crypto Tokens (in INR)
9. Gold rates, both hisorical and latest
10. Exchange rate for USD
11. User Profile information

## Authentication

Most APIs don't need any authentication. APIs that require authentication are marked with a 🔒.

## CORS

CORS is enabled for all requests across all domains, so you don't need to proxy any requests. You can directly build your static site using this API.

## Disclaimer

I've documented this for educational purposes, because I wanted a way to get the latest NAV of my Mutual Funds in a script. If you use this for any purpose, it is at your own liability. If Kuvera makes any changes, this may break - I don't give any guarantees. This is a read only API, so you can't use this to manage your funds.

## Stoplight

The API was documented using Stoplight Studio, and is hosted on the stoplight website. The API is documented using OpenAPI v3 in the `Kuvera.yaml` file. The source code can be found at https://github.com/captn3m0/kuvera-unofficial-api-specification