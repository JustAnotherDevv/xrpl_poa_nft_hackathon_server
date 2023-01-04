# Attendify XRPL API library

## Project information

Project was firstly developed during [XRPL NFT hackathon.](https://devpost.com/software/xrp-nft-attendence)

## Features
⚫ Creating new events and batch minting NFTs for it

⚫ Uploading NFT metadata to IPFS 

⚫ Checking if it's possible to claim NFTs for particular event

⚫ Requresting claim for NFT from particular event. The new sell offer for NFT that has to be accepted by the user is returned

⚫ Event attendees lookup

⚫ NFT ownership verification

## ToDo
⚫ Tests

⚫ More sophisticated documentation

⚫ Whitelist system

⚫ Configuration: e.g. choosing whether or not NFTs are soulbound

⚫ If called again by the same user the claim endpoint should check if sell offer that wasn't accepted exists and it should be returned instead of showing that NFT was claimed

⚫ Checking whether or not deadline for claiming NFTs has passed

⚫ Integration with updated UI and XUMM wallet

⚫ Example integration with database

## Description
A PoA(proof of attendance system) built on the XRP ledger has the potential to provide an easy and secure way to verify attendance at a wide range of events and activities happening in real life or online. Few potential uses for it are: 

⚫University students can use the system to quickly verify attendance at lectures, seminars or other educational events. 

⚫Large events like conferences etc where it can be difficult to keep track of who has attended and who didn't. 

⚫Verifying employee showing up at meetings, training sessions etc.

This repository contains just server for the project, for the frontend see [this one.](https://github.com/JustAnotherDevv/XRPledgerAttendance)

## How to setup

⚫execute `npm i` in CLI

⚫copy .env.example content to .env file and fill with your data and API keys

⚫execute `npm run start` in CLI

## Documentation

Work In Progress
