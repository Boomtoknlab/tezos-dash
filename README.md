# Tezos Dash

**Tezos Dash** is a lightweight, modern **Tezos blockchain explorer dashboard** built to visualize on-chain data such as blocks, transactions, accounts, and smart contracts in a clean UI.

The project is designed for developers, validators, and Tezos ecosystem builders who want an **open-source, customizable explorer** or dashboard layer on top of Tezos indexers and RPC APIs.

---

## 🚀 Features

- 🔍 Explore Tezos blocks, transactions, and operations  
- 👛 View account balances and activity  
- 📜 Inspect smart contracts and metadata  
- 📊 Network statistics and chain insights  
- 🎨 Modern, responsive UI  
- ⚙️ Easily extendable and customizable  

---

## 🧱 Tech Stack

- **Frontend:** TypeScript, modern JavaScript framework (React/Vite-style setup)
- **Styling:** Tailwind CSS
- **Blockchain Data:** Tezos RPC & indexer APIs (e.g. TzKT)
- **Tooling:** Node.js, npm / yarn

---

## 📂 Project Structure

```bash
tezos-dash/
├── src/              # Application source code
├── public/           # Static assets
├── scripts/          # Utility and build scripts
├── package.json      # Project dependencies and scripts
├── tailwind.config.ts
├── tsconfig.json
└── README.md

🛠️ Installation

Clone the repository
git clone https://github.com/BoomchainLabs/tezos-dash.git
cd tezos-dash


Install dependencies
npm install
# or
yarn install


Run the development server
npm run dev
# or
yarn dev


The app will be available locally (usually at http://localhost:3000).

⸻

⚙️ Configuration

Configure your Tezos data source using environment variables.

VITE_TEZOS_RPC=https://mainnet.api.tez.ie
VITE_INDEXER_API=https://api.tzkt.io


🧩 Customization Ideas
	•	Wallet integration (Temple, Kukai)
	•	Multi-network support (Mainnet, Ghostnet)
	•	Smart contract source viewer
	•	Token & NFT explorer
	•	Baker / validator analytics

⸻

📌 Roadmap
	•	Multi-network support
	•	Token and NFT dashboards
	•	Smart contract interaction views
	•	Performance optimizations
	•	Production deployment guide

⸻

🤝 Contributing

Contributions are welcome.
	1.	Fork the repository
	2.	Create a feature branch
	3.	Commit your changes
	4.	Open a pull request

⸻

📄 License

This project is licensed under the MIT License.

⸻

🌐 About BoomchainLabs

Built by Boomchain Labs to support open blockchain infrastructure and developer tooling in the Tezos ecosystem.
