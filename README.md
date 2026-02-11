# binance-spot-dashboard
币安现货市场实时监控 - 支持价格、FDV、流通市值等指标
binance-dashboard/
├── package.json
├── next.config.js
├── tsconfig.json
├── tailwind.config.ts
├── postcss.config.js
├── .eslintrc.json
├── .gitignore
├── README.md
├── app/
│   ├── layout.tsx
│   ├── globals.css
│   └── page.tsx
├── components/
│   ├── PriceCard.tsx
│   ├── VolumeChart.tsx
│   └── MarketCapCard.tsx
└── lib/
    ├── cache.ts
    ├── binance.ts
    └── websocket.ts
