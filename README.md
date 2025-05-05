# 🚀 Rug Solana Checker - Solscan Explorer

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Solana](https://img.shields.io/badge/Network-Solana-purple)

A powerful toolkit to analyze and detect potential rug pulls on the Solana blockchain using Solscan's data. Protect your investments with real-time contract analysis and liquidity monitoring.

---

## 🔍 Features
- **Rug Pull Detection** - Identify high-risk tokens using ML-powered analysis
- **Liquidity Snapshot** - Track pool reserves in real-time
- **Holder Distribution** - Visualize token concentration risks
- **Contract Auditor** - Smart contract vulnerability scanner
- **Historical Rug Database** - Cross-reference with known scam patterns

---

## ⚙️ Installation

### Prerequisites
- Python 3.8+ [(Download)](https://www.python.org/downloads/)
- Git [(Download)](https://git-scm.com/)

bash
# Clone repository
git clone https://github.com/gigabait-100/rug-solana-checker-solscan
cd rug-solana-checker

# Install dependencies
pip install -r requirements.txt
🖥️ Usage
bash
python main.py [OPTIONS]

Options:
  --token ADDRESS      Analyze specific token contract
  --scan-all           Scan all new tokens in last 24h
  --risk-level [1-5]   Set sensitivity threshold (default: 3)
  --output FILE        Generate PDF report
🛠️ Configuration
Get Solscan API Key (Free Tier):

Register at Solscan.io

Add to .env file:

ini
SOLSCAN_API_KEY=your_api_key_here
Customize Alerts in config.yaml:

yaml
alert_triggers:
  liquidity_change: 15%  # Alert on >15% LP changes
  holder_top10: 60%      # Warn if top 10 hold >60%
  contract_risks:
    - mutable_owner
    - hidden_mint
🆘 Support
Common Fixes
❗ ModuleNotFoundError → Run pip install -r requirements.txt
❗ API Limit Reached → Wait 1 hour or upgrade plan

Report Issue |
Discord Support

⚠️ Disclaimer
This tool provides experimental analysis only. Always do your own research (DYOR) before making financial decisions. Not affiliated with Solana Labs or Solscan.

📜 License
MIT License - Use responsibly. By using this software, you agree to hold developers harmless for any outcomes.


**Preview Tip**: Use [Markdown Preview Enhanced](https://shd101wyy.github.io/markdown-preview-enhanced/) in VSCode for best visualization
