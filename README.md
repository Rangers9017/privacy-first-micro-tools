# Privacy-First Micro Web Tools

A small collection of browser tools for practical tasks. The current app is a budget and debt tracker built with HTML, CSS, and JavaScript.

**License:** MIT

## Budget & Debt Tracker

[Open the app](./tools/para-programlama/index.html) · [Read the full guide](./tools/para-programlama/README.md)

The tracker brings monthly income, expenses, and debt payments together in one view. It supports credit cards, overdraft accounts (KMH), and loans, and lets you compare estimated payoff timelines with extra monthly payments.

## Run locally

Open `tools/para-programlama/index.html` in a modern browser. There is no package manager, build step, or backend for the current app. Tailwind CSS is loaded from its CDN, so the page needs an internet connection to load those styles.

## Data and privacy

The app saves entries in that browser profile's `localStorage`. It does not send financial data to a server. Clearing browser data also removes the saved entries, and data does not move automatically to another browser or device. Review the source before entering sensitive information, especially on a shared computer.

Payoff dates are estimates based on the figures entered and the app's calculation assumptions. They are for planning and are not financial advice.

## Development note

Mahmutcan Zaman set the app's requirements and reviews its behavior. AI assistance was used during development.

## Türkçe

Bu depodaki araçlar tarayıcıda çalışır. Şu an gelir, gider, kredi kartı, ek hesap ve kredi borçlarını takip etmeye yardımcı olan bir bütçe aracı bulunuyor. Veriler kullandığın tarayıcı profilinde saklanır. Ayrıntılar ve kullanım için [Türkçe uygulama rehberine](./tools/para-programlama/README.md) bakabilirsin.
