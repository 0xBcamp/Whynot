
# Project Description: Moon-API Integrated Meeting Bot

## Challenge
Traditional online meetings lack real-time recognition and financial rewards for participant contributions. 

Additionally, there is typcially no mechanism in place for conditions and storage on meeting recognition - such as sending a user crypto if they get 5 "claps" while they are presneting...or storing the total number of "claps" a participant receives throughout the year.


## Solution

This dApp, utilizing with Moon-API, is a blockchain-based platform for engagement and financial rewards during virtual meetings.

- **Authentication via Moon-API:**
  Users log in securely, granting access to sign transactions from their Moon Wallets.

- **Real-Time Recognition and Rewards on the Blockchain:**
  Express reactions, cast votes, and receive crypto rewards for valuable contributions, all captured on the blockchain. Transactions are dictated my smart contract logic, and meeting reaction/reward/voting data can be 
  queried/anaylzed on the blockchian

- **Simple UI for Interactions:**
  User-friendly interface for seamless interactions. Simple meeting participant list with options to react, send crypto, or set up a vote with other authenticated meeting participants.


## How It Works
The Meeting Bot utilizes the Moon-API library to simplify interactions with the Moon blockchain platform. Here's how it functions:

1. **Pre-Built Components and SDK:**
   - The Moon platform provides pre-built components and an SDK that form the basis for the Meeting Bot.

2. **User Authentication:**
   - Participants log in securely, granting the Meeting Bot access to sign transactions from their Moon Wallets.

3. **JWT Acquisition:**
   - After authentication, the Meeting Bot acquires a JSON Web Token (JWT) to effectively sign transactions, when users select reactions, send crypto, or vote.

5. **Secure Private Key Storage:**
   - The HashCorp Vault securely stores private keys authenticated by the Moon-API, ensuring robust cryptographic security.
     
5. **Smart Contract Conditional Logic:**
   - Selecting reactions, sending crypto, and voting is governed by smart contract logic.


## Why it Matters

**Target Audience:**
- Team leads and organizers
- Participants seeking an engaging and rewarding meeting experience.


**Impact on Target Audience:**
- **Enhanced Engagement:**
  Participants feel recognized and rewarded in real-time.

- **Real-Time Recognition and Financial Incentives:**
  Instant tracking of reactions, votes, and financial rewards.

- **Motivation and Financial Benefits:**
  Express reactions, cast votes, and receive crypto rewards for contributions.

- **Secure Private Key Storage:**
  Enhanced security through Moon-API's HashCorp Vault for secure private key storage.

This Moon-API-integrated meeting bot creates a positive, dynamic, and financially incentivized virtual meeting environment.
