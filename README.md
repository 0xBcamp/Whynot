# Project Description: Moon-API Integrated Meeting Bot 🌙

## Table of Contents
- [Challenge](#challenge)
- [Solution](#solution)
- [How It Works](#how-it-works)
- [Front End](#front-end)
- [Back End](#back-end)
- [Why it Matters](#why-it-matters)

## Challenge 
Traditional online meetings lack real-time recognition and financial rewards for participant contributions. Additionally, there is typically no mechanism in place for conditions and storage on meeting recognition - such as sending a user crypto if they get 5 "claps" while presenting or storing the total number of "claps" a participant receives throughout the year.

## Solution 
This dApp, utilizing the Moon-API, is a blockchain-based platform for engagement and financial rewards during virtual meetings.

- **Authentication via Moon-API:** 🌌
  Users securely log in, granting access to sign transactions from their Moon Wallets.

- **Real-Time Recognition and Rewards on the Blockchain:** 🚀
  Express reactions, cast votes, and receive crypto rewards for valuable contributions, all captured on the blockchain. Transactions are dictated by smart contract logic, and meeting interaction data can be queried/analyzed on the blockchain.

- **User-Friendly UI for Interactions:** 🎨
  A simple meeting participant list with options to react, send crypto, or set up a vote with other authenticated meeting participants.

## How It Works
The Meeting Bot utilizes the Moon-API library to simplify interactions with the Moon blockchain platform.

-**Pre-Built Components and SDK:** 🛠️
   The Moon platform provides pre-built components and an SDK forming the basis for the Meeting Bot.

-**User Authentication:** 🔐
   Participants securely log in, granting the Meeting Bot access to sign transactions from their Moon Wallets.

-**JWT Acquisition:** 🌐
   After authentication, the Meeting Bot acquires a JWT to sign transactions when users interact.

-**Secure Private Key Storage:** 🔐
   The HashCorp Vault securely stores private keys authenticated by the Moon-API, ensuring robust cryptographic security.

-**Smart Contract Conditional Logic:** 🧠
   Selecting reactions, sending crypto, and voting are governed by smart contract logic.

## Front End 
**User Journey:**

1. **Sign Up for Moon Account:** 🚀
   Users initiate their journey by signing up for a Moon account.

2. **Sign In with Moon Account:** 🔐
   After signing up, users securely sign in using their Moon account credentials.

3. **Authenticated Wallet Address:** 💼
   Upon successful sign-in, users receive an authenticated wallet address from Moon.

4. **Virtual Meeting Interactions:** 🚀
   - **Send Reactions:** 👏💖
     Express reactions like claps and hearts during virtual meetings.
   - **Send Crypto as Rewards:** 💰
     Reward presenters with cryptocurrency during virtual meetings.
   - **Voting Mechanism for Polls:** 🗳️
     Participate in polls using a secure voting mechanism.

5. **Blockchain Recording and Reports:** 📊
   All user interactions, including reactions, crypto transactions, and votes, are recorded on the blockchain. Users can generate reports by querying the blockchain for insights.

## Back End 
**Moon Platform & Smart Contract:**

- **Moon Platform Handles Sign-Up, Sign-In, Authentication, and Wallet Generation:** 🌙
  The Moon platform takes care of user onboarding, secure sign-in processes, user authentication, and the generation of authenticated wallet addresses.

- **Ease of Transactions with Moon Platform:** 💸
  Provides a seamless experience for users to perform transactions such as submitting reactions, sending crypto, and participating in voting.

- **Smart Contract Conditions:** 🧠
  The backend employs smart contracts to enforce conditions on voting, reactions, and the amount of crypto sent. This ensures secure and transparent interactions.

## Why it Matters

- **Enhanced Engagement:** 🌟
  Participants feel recognized and rewarded in real-time.

- **Real-Time Recognition and Financial Incentives:** 💸
  Instant tracking of reactions, votes, and financial rewards.

- **Motivation and Financial Benefits:** 💡
  Express reactions, cast votes, and receive crypto rewards for contributions.

- **Secure Private Key Storage:** 🔐
  Enhanced security through Moon-API's HashCorp Vault for secure private key storage.
