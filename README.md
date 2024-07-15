# 🗳️ Blockchain-Based Voting System

## Overview
A decentralized voting system using blockchain technology to ensure transparency and security. The system comprises two modules: **Admin** and **Voter**. Voters can create accounts but need verification to vote. Admins can create polls, manage elections, and more.

## Tech Stack
- **TypeScript**
- **Solidity**
- **React**
- **Ganache**
- **MySQL**

## Features
- **📝 Voter Registration and Verification**: Voters must create an account and wait for verification before voting.
- **📊 Admin Poll Management**: Admins can create and end elections.
- **🔐 Secure Voting**: Voters can only vote once per election.
- **📈 Real-time Results**: Live tracking of votes during the election.
- **🛡️ Immutable Records**: Ensures votes cannot be tampered with.
- **📅 Election Scheduling**: Schedule elections for specific dates and times.

## Project Structure
### 🛠️ Admin Module
- Create Polls
- End Elections
- Verify Users

### 👥 Voter Module
- Create Account
- Login
- Vote in Verified Polls

## Installation
1. **📥 Clone the repository**
    ```bash
    git clone https://github.com/your-repo/blockchain-voting-system.git
    cd blockchain-voting-system
    ```

2. **📦 Install Dependencies**
    ```bash
    npm install
    ```

3. **🛠️ Start Ganache**
    ```bash
    ganache-cli
    ```

4. **🔨 Compile and Deploy Contracts**
    ```bash
    truffle compile
    truffle migrate
    ```

5. **🚀 Start the Application**
    ```bash
    npm start
    ```

## Usage
1. **🏠 Landing Page**
    ![Landing Page](./images/Landing_page.png)

2. **🆕 Create Account**
    ![Create Account](./images/Create_account.png)
    ![Account Created](./images/createaccount_filled.png)

3. **🔐 Login**
    ![Login](./images/Login.png)

4. **⛔ Unverified User Login Attempt**
    ![Unverified Login](./images/triedtologin_but_not_verified_by_evoter.png)

5. **👤 Profile and Logout**
    ![Profile with Logout](./images/profile_with_logout.png)

6. **📅 Admin Creates Poll**
    ![Create Poll](./images/creation_of_poll.png)
    ![Poll Created](./images/poll_created.png)

7. **🛑 Admin Ends Election**
    ![End Election](./images/admin_end_election.png)

8. **🗳️ Voting Process**
    ![User Voted](./images/jhon_voted.png)

9. **✅ Admin Verifies Users**
    ![Verify Users](./images/verify_users_by_evoter.png)

## Thank you 💖
