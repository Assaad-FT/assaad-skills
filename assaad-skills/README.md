# Assaad's Financial Analysis Skills

Elite financial analysis frameworks synthesized from **48 legendary investors and Wall Street analysts**. Portable across AI platforms.

## What's In This Repository

Three comprehensive skill sets, maintained as a single source of truth:

| Skill | Analysts | Use For |
|-------|----------|---------|
| **Analyst Frameworks** | 24 Wall Street analysts | Equity analysis, sector evaluation, macro positioning |
| **Fixed Income Frameworks** | 8 bond legends | Credit analysis, yield curve, sovereign selection |
| **Investing Principles** | 16 legendary investors | Buy/sell discipline, position sizing, behavioral guardrails |

## Repository Structure

```
assaad-skills/
├── master/                          ← Canonical versions (platform-agnostic)
│   ├── analyst-frameworks.md
│   ├── fixed-income-frameworks.md
│   └── investing-principles.md
├── claude/                          ← Claude.ai capabilities format
│   ├── analyst-frameworks.yaml
│   ├── fixed-income-frameworks.md
│   └── investing-principles.md
├── gemini/                          ← Gemini system instructions
│   └── system-instructions.md
├── chatgpt/                         ← ChatGPT Custom GPT instructions
│   └── custom-gpt-instructions.md
└── README.md
```

## How to Use

### Claude.ai (Capabilities)
Upload files from `/claude` to Claude.ai → Settings → Capabilities

### Claude Code
Open this repository as a project. Claude Code reads the skill files automatically.

### Gemini (AI Studio)
Copy contents of `/gemini/system-instructions.md` into System Instructions field.

### ChatGPT (Custom GPT)
Create a Custom GPT and paste contents of `/chatgpt/custom-gpt-instructions.md` into Instructions.

### Financial Analyst App
The web app at `financial-analyst-app.jsx` pulls skills from `/master` at runtime. Set your GitHub repo path in Settings.

## Analyst Coverage

### Macro & Strategy
Ed Hyman (Evercore), Bob Doll (Crossmark), Savita Subramanian (BofA), Hussein Malik (JPMorgan), Haim Israel (BofA)

### Technology/TMT  
Mark Mahaney (Evercore), Katy Huberty (Morgan Stanley), Hans Mosesmann (Rosenblatt), Lloyd Walmsley (Mizuho), Nick McKay (Freedom Capital)

### Financial Services
Chris Kotowski (Oppenheimer), Gerard Cassidy (RBC), Mark Palmer (Benchmark)

### Quantitative
Cliff Asness (AQR), Jim O'Shaughnessy (OSAM), Rich Ross (Evercore)

### Fixed Income
Jeffrey Gundlach (DoubleLine), Bill Gross (PIMCO), Mohamed El-Erian (Allianz), Bob Michele (JPMorgan), Scott Minerd (Guggenheim), Mark Kiesel (PIMCO), Andrew Balls (PIMCO), Chris Iggo (AXA IM)

### Sector Specialists
Bryan Krug (Artisan), Josh Sullivan (JonesTrading), Jeremy Tonet (JPMorgan), Steve Sakwa (Evercore), Umer Raffat (Evercore)

### Investing Legends
Warren Buffett, Charlie Munger, Seth Klarman, Howard Marks, Peter Lynch, Ray Dalio, Stanley Druckenmiller, George Soros, Paul Tudor Jones, David Tepper, Michael Burry, Mohnish Pabrai

## Updating

Edit the `/master` files as the canonical source. Then update platform-specific versions as needed.

## License

Private repository. All frameworks synthesized from publicly available research and methodologies for personal use.
