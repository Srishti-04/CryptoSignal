# 📈 CryptoSignal – Crypto Analytics Dashboard (Next.js + TradingView)

🚀 **Live Repo:** https://github.com/Srishti-04/CryptoSignal  

A high-performance **Crypto Analytics Dashboard** built with **Next.js (App Router)**, featuring real-time price tracking, interactive charts, and scalable architecture using modern web technologies.

---

## 🚀 Features

- 📊 Live Crypto Price Tracking
  - Polling-based near real-time updates
  - Monitor market trends and price movements

- 🔍 Global Coin Explorer
  - Browse and search cryptocurrencies
  - View detailed coin data and metrics

- 📈 Interactive Charts
  - TradingView candlestick charts
  - Historical price analysis

- 🔥 Trending Assets
  - Track top-performing and trending coins

- ⚡ Performance Optimizations
  - Server-Side Rendering (SSR)
  - Parallel data fetching using Promise.all
  - Suspense for smooth UI loading

- 🎨 Responsive UI
  - Built with Tailwind CSS + Shadcn UI
  - Clean, modern, and mobile-friendly design

---

## 🛠️ Tech Stack

**Frontend**
- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS
- Shadcn UI

**APIs & Integrations**
- CoinGecko API
- TradingView Charts

**Architecture**
- REST APIs
- Next.js API routes (proxy layer)

---

## 📂 Project Structure

/app            → App Router pages & layouts  
/components     → Reusable UI components  
/lib            → API utilities & helpers  
/pages/api      → API proxy routes  
/styles         → Global styles  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Srishti-04/CryptoSignal.git
cd CryptoSignal
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_API_URL=https://api.coingecko.com/api/v3
```

---

### 4️⃣ Run the application

```bash
npm run dev
```

App will run on:
```
http://localhost:3000
```

---

## 🔗 Key Functionalities

- Real-time crypto price tracking (polling)  
- Coin search and exploration  
- Trending coins section  
- Interactive TradingView charts  
- Optimized API calls via proxy layer  

---

## 📈 Performance Improvements

- ⚡ Reduced API latency using proxy layer  
- 🚀 Improved performance by ~20%  
- 🔄 Faster rendering using SSR + Suspense  
- 📦 Efficient parallel fetching (Promise.all)  

---

## 🧪 Future Improvements

- WebSocket-based real-time updates  
- Portfolio tracking feature  
- Alerts & notifications  
- Dark/light theme toggle  

---

## 👩‍💻 Author

**Srishti Jaiswal**  
GitHub: https://github.com/Srishti-04  

---

## ⭐ Contribute

Feel free to fork this repo, raise issues, or submit PRs!
