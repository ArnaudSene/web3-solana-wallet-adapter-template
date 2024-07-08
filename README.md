# Web3 dApp template using Solana Wallet Adpater and NETX.js 14


## Tech stack

- Next.js 14
- Tailwindcss
- Solana Wallet Adapter


## 1. Installation

```bash
git clone https://github.com/ArnaudSene/web3-solana-wallet-adapter-template.git
cd web3-solana-wallet-adapter-template
```

Install dependencies

```bash
pnpm install
```


### 2. Environment files
Copy the sample.env file to: 

- .env.development
- .env.production

`NEXT_PUBLIC_ENABLE_LOCAL_TESTNET` : Enable the local testnet
`NEXT_PUBLIC_LOCAL_TESTNET` : Define the local testnet endpoint (e.g. "http://127.0.0.1:8899")


### 3. Start application

```bash
# Start : dev mode
pnpm run dev

# Build and start : prod mode
pnpm run build && pnpm run start
```
