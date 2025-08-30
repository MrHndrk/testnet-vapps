# vApp Submission: [Your Project Name]

## Verification
```yaml
github_username: "MrHndrk"
discord_id: "514037081144557574"
timestamp: "2025-08-30"
```

## Developer
- **Name**: Hendrik
- **GitHub**: @MrHndrk
- **Discord**: mrhndrk
- **Experience**: WEB3 Enthusiast

## Project

### Name & Category
- **Project**: FinAI (Financial Artificial Intelligence)
- **Category**: defi

### Description
FinAI solves the problem of complexity and time commitment required for crypto trading. Many retail investors struggle to monitor the market 24/7 and make informed trading decisions. FinAI provides an AI-powered auto-trading solution, allowing users to deposit USDT and select their risk profile. The AI then automatically manages the funds by performing asset rebalancing based on real-time analysis of market indicators like RSI, volume, and the Fear & Greed Index. This gives everyone a chance to participate in the DeFi market with a smart, automated, and well-measured strategy.

### SL Integration  
FinAI will leverage the Soundness Layer (SL) to ensure the integrity and security of the AI's trading decisions. We will use the zkApp feature to verify the execution of our off-chain trading logic via zero-knowledge proofs. This means every AI rebalancing decision can be proven to be valid and in line with our algorithm without revealing the sensitive data the AI uses for analysis. The use of zkApps guarantees transparency and trust, as users can verify that the AI is not acting outside of their pre-set risk profile

## Technical

### Architecture
- Frontend: Antarmuka pengguna akan memungkinkan pengguna untuk mendepositkan USDT, mengatur profil risiko, dan melihat riwayat trading serta performa portofolio mereka.

- Smart Contract (On-chain): Smart contract akan mengelola deposit dan penarikan dana, serta otorisasi bagi AI untuk melakukan rebalancing.

- AI Engine (Off-chain): Mesin AI akan menganalisis data pasar secara real-time dan menghitung keputusan rebalancing yang optimal. Keputusan ini akan dibuat dalam bentuk transaksi yang kemudian akan dikirim ke smart contract untuk dieksekusi.

- Verifikasi ZK (Off-chain): Setiap keputusan AI akan diproses melalui zkApp untuk menghasilkan bukti zero-knowledge yang memverifikasi bahwa logika trading telah dieksekusi dengan benar. Bukti ini akan disertakan dalam setiap transaksi yang dikirim ke smart contract.

### Stack
- **Frontend**: React
- **Backend**: Python
- **Blockchain**: SL + others
- **Storage**: IPFS

### Features
1. USDT Deposit & Withdrawal
2. Custom Risk Profiles: Users can choose their risk level (Conservative, Moderate, Aggressive) 
3. Auto-Rebalancing: AI automatically rebalances assets based on market indicators
4. Portfolio Dashboard: A real-time view of investment performance
5. Transaction History: A complete record of all trading activity

## Timeline

### PoC (2-4 weeks)
- [ ] Smart contract for deposits/withdrawals and a simple frontend.
- [ ] Initial zkApp implementation for verifying basic trading logic.
- [ ] A minimal interface for demonstration.

### MVP (4-8 weeks)  
- [ ] Implementation of risk profiles, AI rebalancing, and the dashboard.
- [ ] Code optimization, security audit, and infrastructure setup.
- [ ] Testing with a group of users to get feedback.

## Innovation
FinAI is unique because it combines artificial intelligence with Web3 transparency. Most auto-trading platforms are centralized and lack transparency, but FinAI uses zero-knowledge proofs from the Soundness Layer to prove that the AI is acting according to its promised algorithm. This offers a level of trust that other platforms cannot. People will use it because FinAI provides a smart, secure, and transparent passive investment solution in the world of DeFi.

## Contact
Discord and Twitter.


**Checklist before submitting:**
- [ ] All fields completed
- [ ] GitHub username matches PR author  
- [ ] SL integration explained
- [ ] Timeline is realistic
