# Web3 Integrated Secure Area Mapper
Web application to draw, save, and export secure map zones which is integrated with blockchain technology. It can be used for smart city planning, campus security, geo-fencing, and more.
### Features
- **Draw Secured Zones Freely -** Use freehand drawing with customizable colors & stroke widths.
- **Save & Share -** Export your map as PDF or save drawings as JSON for easy sharing.
- **Tamper-Proof Security -** Optional blockchain-backend logging ensures data integrity.
- **No Hassle -** Intuitive UI, no login required.
<br/>
### Tech Stack
- HTML5
- CSS
- JavaScript
- [jsPDF](https://github.com/parallax/jsPDF)
- Blockchain (Solidity for Smart Contract)
- Vercel for deployment
<br/>
### How Blockchain is Integrated
- Generated a hash map data using SHA-256
- Stored the hash or simulated transaction ID in local storage or a mock server
- Enabled future integration with smart contracts to store zone metadata on-chain
  <br/>
### Project Structure
secure-area-mapper/ │ ├── index.html # Main web page ├── style.css # Custom styles ├── script.js # JavaScript logic ├── assets/├── logo/└── README.md # You are here!
<br/>
### Getting Started
Use cases:
- Campus boundary mapping
- Geo-fencing logistics zones
- Protected environmental zones
- Blockchain-secured land/property tagging
Challenges Faced:
- Managing dynamic canvas drawing with JavaScript
- Implementing accurate export to PDF
- Mocking blockchain functionality in a frontend-only app
- Future Improvement
- Real-time sync with a blockchain backend (e.g., Ethereum/Polygon smart contracts)
- User authentication and map sharing
- Uploading saved maps to IPFS for decentralization
