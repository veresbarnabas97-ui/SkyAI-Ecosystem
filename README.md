🌌 SkyAI Empire | The Central Intelligence Hub
> The Ultimate Convergence of Artificial Intelligence and Ethical DeFi.
> A SkyAI ökoszisztéma központi dokumentációs és konfigurációs tárhelye.
> 
🗺️ Architektúra Áttekintés
A SkyAI nem egyetlen alkalmazás, hanem 5 szorosan integrált modulból álló birodalom. Ez a repozitórium (Master) szolgál az "egyetlen igazság forrásaként" (Single Source of Truth), amely szinkronizálja az adatokat a hálózat többi részével.
📂 Repository Struktúra
| Modul Neve | Repo Link | Leírás | Tech Stack |
|---|---|---|---|
| 🏛️ The Empire | skyai-empire | A központi Hub és Landing page. | Next.js, React |
| 🧠 Web3 Terminal | skyai-web3-terminal | Professzionális kereskedő felület (DApp). | Web3.js, Charting Libs |
| 🤖 Trading Eco | skyai-trading-ecosystem | Telegram botok és backend logika. | Node.js, Python |
| 👤 Founder Profile | skyai-founder-profile | Transzparencia és csapat bemutatása. | Static Site, On-chain Data |
| ⚙️ Master Config | Jelenlegi Repo | Központi konfiguráció és dokumentáció. | JSON, Markdown |
💎 Tokenomics (Dual-Token System)
A rendszer két, egymást kiegészítő tokenre épül. Az adatok automatikusan frissülnek a skyai-master-config.json fájlból.
1. 🏛️ Governance Token (Az Irányító)
Ez a token biztosítja a hozzáférést a Prémium Terminálhoz és a DAO szavazatokhoz.
 * Név: SkyAI Governance
 * Total Supply: 100,000,000 (Fix)
 * Contract Address: 0x4B30d92243e88907751E016d33A23D3A1A560026
 * Funkció: Voting, VIP Access, Revenue Share.
2. ⛽ Utility Token (Az Üzemanyag)
Ez a token mozgatja a botokat, fizeti a tranzakciós díjakat és jutalmazza a stakingelőket.
 * Név: SkyAI Fuel
 * Total Supply: 97,000,000 (Fix - Deflációs)
 * Contract Address: 0xcBbaDC40Cde0F12679a6b0b74fB732E02E60fa83
 * Funkció: Gas for Bots, Rewards, Liquidity.
🛠️ Fejlesztői Dokumentáció
Hogyan használd a Központi Konfigurációt?
Ahelyett, hogy "beégetnéd" a címeket, használd a központi API-t.
Telepítés:
npm install skyai-config-sdk
# vagy másold be a 'utils/skyaiConfig.js' fájlt

Használat:
import { fetchSkyAIConfig } from './utils/skyaiConfig';

const config = await fetchSkyAIConfig();
console.log(config.tokens.governance.address); 
// Output: 0x4B30...

CI/CD Pipeline
Minden JSON módosítás automatikusan lefut a GitHub Actions rendszeren keresztül:
 * Validáció: Ellenőrzi a JSON szintaxist.
 * Biztonság: Ellenőrzi, hogy a kritikus Contract címek helyesek-e.
 * Dispatch: Értesíti a többi 4 repót, hogy frissítsék magukat.
🚀 Roadmap & Státusz
 * [x] Phase 1: Koncepció és Smart Contract Deploy (Kész)
 * [ ] Phase 2: Presale Indítása & Marketing (Folyamatban)
 * [ ] Phase 3: Web3 Terminal Béta teszt (Q3)
 * [ ] Phase 4: Telegram Botok nyilvános indítása (Q4)
 * [ ] Phase 5: DAO Governance aktiválása (Jövő év)
🔗 Hivatalos Linkek
 * 🌐 Website: empire.skyai.io
 * ✈️ Telegram: t.me/skyai_official
 * 🐦 Twitter: x.com/skyai
 * 📜 Whitepaper: docs.skyai.io
🛡️ Security & Disclaimer
A SkyAI tokenek (Governance & Utility) kísérleti technológiák. A Smart Contract auditált, de a DeFi kockázatokkal jár. Kérjük, olvassa el a Kockázati Nyilatkozatot.
© 2024 SkyAI Empire. All Rights Reserved.
