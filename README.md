# addresspedia
Web3 address wiki

# Project one-pager
## Problem: 
1. there's a lot of spam on chain that's not trivial to filter out and it can lead compromising users.
2. looking at address' transactions it's usually not clear what was done.

## Existing solutions:
1. There are tags on Etherscan
2. There are a few vendors that have theirs black-bocks spam score
3. There is transaction-marking mechanism on Zapper.fi (which is also proprietal)

## On existing solutions:
1. Etherscan, Zapper.fi, a few others — all of them are blackbox/proprietal — you can't use them in commercial projects
2. More importantly, every company want's to build it's own, so data remain scattered.

## Solution:
1. Open protocol for address markup (spamminess and name tag)
2. Since it's open, and data is free for all, there's no barrier to contribute and even willingnes (like in Openstreetmap or Wikipedia)
3. Chicken and egg problem is solved using existing Zerion userbase
4. There will be an open-sourced AI-aggregation of signals that will output most probable data and it's reliability score — so any project on web3 may not compromise on spam protection and/or tx history readability.

# Timeline
- Q4 2023
-   Talking to other wallets, gathering soft commits to use protocol, tuning requirements
-   Launching version one — fully functional, but may yet not have high adoption due to it's a first attempt
- Q1 2024
-   Optimising solution (more ways to upload data, better AI, bigger coverage by data providers)
