# Domain Naming Suite

Three specialized tools to find and verify available domains. Real-time DNS checking via Cloudflare + price lookup across registrars.

## 🛠️ Tools

### 1. **Domain Hunter** ⚡
Generate brandable domain names from keywords.
- **Quick generation** from a single keyword
- **TLD filtering** (.com, .io, .app, .co, etc.)
- **Direct links** to Namecheap, Porkbun & GoDaddy for instant price checking
- **Copy-to-clipboard** for bulk workflows

**Use case:** Find short, memorable names quickly

### 2. **Domain Hunter Pro** 🔬
Coin invented words like Spotify, Robinhood, and Revolut.
- **Portmanteau engine** - combines two words creatively
- **Consonant mutations** - drops vowels for shorter variants
- **Pronunciation scoring** - hot 🔥 (≤5 chars), good (≤7), ok
- **Tab filters** - view coined names only, short only, hot only
- **Batch generation** with two keywords

**Use case:** Brand-building with invented, defensible names

### 3. **Live DNS Checker** 🟢
Real availability verification via Cloudflare DNS.
- **Batch check** multiple domains at once
- **Live status** - NXDOMAIN = Available, NOERROR = Taken
- **Registrar links** for instant purchase
- **Progress tracking** with stats (available/taken/checked)
- **Auto-generator** from keywords to feed the checker

**Use case:** Verify which names are actually available before buying

---

## 🚀 Getting Started

### Online Access
All tools are live on **GitHub Pages**:
```
https://aveca.github.io/naming
```

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/aveca/naming.git
   cd naming
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

---

## 🔍 How It Works

### Domain Hunter
1. Enter a keyword (e.g., "edge", "signal", "trade")
2. Select desired TLDs
3. Click **Generate ⚡**
4. Browse results sorted by quality score
5. Click registrar links to check price and availability

### Domain Hunter Pro
1. Enter 1-2 keywords
2. Click **Generate ⚡**
3. Filter by:
   - **All** - all generated names
   - **🔬 Coined** - portmanteaus only
   - **⚡ Short** - 6 characters or fewer
   - **🔥 Hot** - top quality (pronounceable, memorable)
4. Copy domain or visit registrar

### Live DNS Checker
1. Paste domain names (comma or newline separated)
2. Select TLDs to check
3. Click **Check DNS ⚡**
4. Results show:
   - 🟢 **Available** - domain is free to register
   - ✗ **Taken** - domain already registered
5. Click Porkbun/Namecheap to buy available domains

---

## 🛡️ Privacy First
- **No WHOIS lookups** - faster, more private
- **Live DNS via Cloudflare** - direct, accurate results
- **Client-side only** - no backend server needed
- **No tracking** - completely transparent

---

## 💡 Tips

**For quick domain finds:**
1. Use Domain Hunter for broad generation
2. Copy results into Live DNS Checker
3. Buy available domains instantly

**For branded names:**
1. Use Domain Hunter Pro with two keywords
2. Filter for Hot + Short combinations
3. Verify with Live DNS Checker
4. Register immediately (popular coined names get taken fast)

**Best TLDs to check:**
- `.com` - most valuable, highest conversion
- `.io` - tech startups
- `.app` - applications/SaaS
- `.co` - business/startup alternative
- `.ai` - AI/ML companies

---

## 📊 Examples

**Keyword: "edge"**
- Domain Hunter generates: edge, edgr, edgex, edgify, getedge, etc.
- Domain Hunter Pro with "edge" + "trade": edgetrade, tradeedge, edgr, tradify, etc.
- Live DNS checks which are available across TLDs

**Keyword: "signal"**
- Top results: signal, signlr, signify, getsignal, pro-signal
- Coined (Spotify-style): sgnlr, signfy, vosignal, etc.

---

## 🔧 Tech Stack

- **HTML5** - structure
- **CSS3** - dark theme UI with gradients
- **Vanilla JavaScript** - all generation & checking logic
- **Cloudflare DoH API** - real DNS lookups
- **GitHub Pages** - static hosting

---

## 📝 License

Open source. Use freely for personal or commercial domain hunting.

---

**Made for founders, marketers, and domain enthusiasts.** 🚀
