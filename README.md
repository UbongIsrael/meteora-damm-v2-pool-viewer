# 🌊 Meteora Pool Viewer

![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive%20Design-success)
![Powered by Meteora API](https://img.shields.io/badge/Powered%20by-Meteora%20API-purple)

A lightweight web app that lets you explore **Meteora DAMM-V2 liquidity pools** on Solana.  
Simply input a token address, choose between quote **SOL** or **USDC**, and get detailed pool data in real-time.

---

## 🚀 Features

- 🔍 **Fetch pools** directly from the [Meteora API](https://dammv2-api.meteora.ag)
- 📊 **Sort by:** TVL, APR, or 24h Volume (ascending or descending)
- 💧 **Filter:** show only active pools (TVL > 0)
- 📋 **Copy pool address** with one click
- 📱 **Responsive layout** — optimized for both desktop and mobile

---

## 🧠 Tech Stack

- **HTML5**  
- **CSS3** (custom responsive layout, no frameworks)  
- **Vanilla JavaScript**  
- **Meteora API** for live Solana pool data  

---

## ⚙️ How It Works

1. Enter a `Token Address` (token address)
2. Select **SOL** or **USDC** as `Quote Token`
3. Click **Fetch Pools**
4. Sort and filter results as needed
5. Click any **Pool Address** to copy it to clipboard

Example API request:
```bash
GET https://dammv2-api.meteora.ag/pools?token_a_mint=F5qFr17LeunQk5ikRM9hseSi2bbZYXYRum8zaTegtrnd&token_b_mint=So11111111111111111111111111111111111111112
````

---

## 📱 Mobile Optimization

* Pool cards resize smoothly on smaller screens
* Long addresses wrap neatly without overflow
* Buttons and dropdowns remain touch-friendly

---

## 🌐 Hosting Options

You can host this project **free** on:

* [Netlify](https://www.netlify.com/)
* [Cloudflare Pages](https://pages.cloudflare.com/)
* [Vercel](https://vercel.com/)
* [GitHub Pages](https://pages.github.com/)
* [Tiiny Host](https://tiiny.host/)

All options include HTTPS and custom domain support.

---

## 🧩 Possible Improvements

* Search/filter pools by name
* Collapsible cards for compact mobile display
* Add dark/light mode toggle
* Cache recent searches locally

---

## 👤 Author

**Digital Sheikh**
Built for exploring and analyzing Meteora liquidity pools on Solana.

Follow on X: [@0xBonge](https://x.com/0xBonge)

---

## 📜 License

Open-source under the MIT License.
Free to use and modify for educational or personal projects.

