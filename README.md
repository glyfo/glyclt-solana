# Solana Quickstart

Command Line Tool to compile/deploy Smart Contract on Solana

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Prerequisite 

+ Docker 

## Install 

```console
$ git clone https://github.com/glyfo/solana-quickstart
$ cd solana-quickstart ; chmod +x glyctl.sh
$ ./glyctl.sh
Usage: ./glyctl.sh [setup|wallet|airdrop|compile|deploy|delete]
```

Summary:

```console
+ setup   : Using Rust Imagen from Docker Hub to added Base & Solana tools to compile smart contract.
+ wallet  : create a wallet to deploy smart contract on solana
+ airdrop : Sol airdrop to wallet 
+ compile : compile smart contract 
+ deploy  : deploy smart contract on solana
```
## Solana Fundamentals

+ All is a Account 
+ All Smart Program are Stateless 
+ Data & Program are separete 
+ System Program support Account creation
+ Token Program support Token creation. ( Funglble & No-Fungible support )

## Smart Contract Examples 

+ Counter Vote 
+ Counter Vote using PDA 
+ Event Ticket System 
+ NFTs 

## Reference

[Solana Docs](https://docs.solana.com/)

[Anchor Framework](https://github.com/project-serum/anchor)

[Anchor Book](https://book.anchor-lang.com/)

[Docker] (https://docker.com)