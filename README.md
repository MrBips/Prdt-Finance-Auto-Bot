# PRDT Miner Auto

A Node.js script for automatic mining and check-in on PRDT Finance for multiple wallets simultaneously, with proxy support and 24h loop execution.

## Features
- Reads a list of private keys from `key.txt` and proxies from `proxy.txt` (if available)
- Automatically sends mining and check-in requests for each wallet
- Supports random proxy and random public IP
- Repeats the process every 24 hours

## Requirements
- Node.js >= 16
- Libraries: axios, ethers, https-proxy-agent

## Installation