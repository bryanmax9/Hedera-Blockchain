# Hedera Hashgraph Transaction Showcase

This project demonstrates basic blockchain transactions using the Hedera JavaScript SDK.

## 🚀 Getting Started

### Prerequisites

- Node.js installed on your machine.
- A Hedera Testnet Account. If you don't have one, sign up [here](https://portal.hedera.com/).

### Installation and Setup

1. **Clone the repository:**

   ```bash
   git clone git@github.com:bryanmax9/Hedera-Blockchain.git
   cd hello-hedera-js-sdk
   ```

2. **Install the required dependencies:**

   ```bash
   npm install
   ```

3. **Run the transaction script:**

   ```bash
   node index.js
   ```

🧠 How It Works

    Connection to Hedera Testnet: The script initiates a connection to the Hedera Testnet.
    Account Creation: It then programmatically generates and creates a new Hedera account with a set initial balance.
    Balance Display: Once the account is created, the new account's ID and balance are displayed.
    Hbar Transfer: The script transfers Hbars from the main account to the newly created account.
    Transaction Confirmation: After the transfer, the script confirms the transaction status and displays the updated balance of the new account.

🔐 Security Note

Always handle your private keys with care. Never expose them in your codebase or any public platform. Use environment variables or other secure methods for handling them.

📚 References

    Hedera Official Documentation

📝 License

This project is licensed under the ISC License.
