# Blockchain icons

Nothing else than Blockchain icons with chain ID filename.

## Introduction

This repository is used by AmiChain ChainList SDK [`@amichain/chainlist`](https://github.com/Amichain/chainlist) to display icons from any chain with a known icon.

## Usage

Each icon can be accessed directly in GitHub raw:
```
https://github.com/Amichain/chain-icons/blob/main/svg/<chain-id>.<ext>>?raw=true
```

However, this method has some limitations and cannot be used in HTML `<img>` tags due to CORS policy.

We suggest using a CDN service such as [`jsdelivr.net`](https://jsdelivr.net) in that case:
```
https://cdn.jsdelivr.net/gh/Amichain/chain-icons/svg/<chain-id>.<ext>
```


Note that SVG icons are preferred, but not all chains have an SVG icon.  
You should use the appropriate file extension for each chain.  
You can use [AmiChain ChainList SDK](https://github.com/Amichain/chainlist) to determine the correct icon extension for a given chain.

## Contribute

Please follow these instructions to add a chain logo:

1. Prepare your file:  
   Prefer the SVG format and optimize the file with [svgomg.net](https://svgomg.net).
2. Fork this repository and add your logo to the folder corresponding to your file extension.
3. Create a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
4. Repeat the operation for [AmiChain ChainList SDK](https://github.com/Amichain/chainlist) if it is a new logo or if you updated it with a different file extension.
