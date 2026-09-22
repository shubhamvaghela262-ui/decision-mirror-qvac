# Decision Mirror — QVAC Local AI

Decision Mirror is a private decision-mapping web app powered by **QVAC SDK 0.19.1**. It reflects priorities, benefits, drawbacks, trade-offs, questions and information gaps without selecting a winner.

## Requirements
- Node.js 22.17+
- npm 10.9+
- QVAC SDK 0.19.1+

## Run
```bash
npm install
npm run verify
npm start
```
Open `http://localhost:3000`.

## Demo
Decision: `Should I buy a laptop or build a desktop for college and gaming?`
Priorities: `Budget, portability, gaming performance, upgradeability`
Options: Laptop (portable, simple / less upgradeable), Desktop (performance, upgradeable / not portable).

## QVAC implementation
The backend uses `loadModel()`, `completion()`, and `LLAMA_3_2_1B_INST_Q4_0`. SDK version: **0.19.1**. The inference flow is local/on-device and does not require a cloud AI API key.

## License
MIT
