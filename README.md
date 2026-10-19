# Privacy-First Micro Web Tools

A small collection of dependency-free browser tools built to solve practical, everyday tasks. The apps run on the client side and keep their working data in the browser.

**Languages:** HTML · CSS · JavaScript  
**License:** MIT

## Available tools

| Tool | What it does | Source |
| --- | --- | --- |
| Budget & Debt Tracker | Organizes income, expenses, debts, and payoff scenarios. | [Open source folder](./tools/para-programlama/) |

The tracker can be opened directly from its [HTML app](./tools/para-programlama/index.html). No package manager, build step, or backend is required for the current tool.

## Design principles

- **No build step:** the app is plain web technology and can be opened as a static page.
- **Local-first:** the tool stores its data in the browser's local storage.
- **User-controlled:** review the source before entering personal financial information; clearing browser data removes local app data.

## Run locally

1. Download or clone this repository.
2. Open `tools/para-programlama/index.html` in a modern browser.
3. Use the app in that browser; its saved data stays in that browser profile.

No financial data is sent to a server by this static app. The calculations are planning aids and are not financial advice.

## Credits

The app’s requirements and behavior are directed and reviewed by Mahmutcan Zaman, with implementation developed in collaboration with generative AI.

## Türkçe

Günlük ihtiyaçlar için hazırlanmış, harici paket gerektirmeyen küçük tarayıcı araçları koleksiyonudur. Mevcut araç, gelir, gider, borç ve erken ödeme senaryolarını takip etmeye yardımcı olur.

`tools/para-programlama/index.html` dosyasını doğrudan tarayıcıda açabilirsin. Uygulama verileri kullandığın tarayıcının yerel hafızasında tutulur; bu nedenle kişisel finans bilgilerini girmeden önce kaynak kodunu incele ve ortak kullanılan cihazlarda dikkatli ol.

Yapay zekâ iş birliğiyle geliştirilmiş olsa da araçların gereksinimleri ve davranışı Mahmutcan Zaman tarafından yönlendirilip gözden geçirilmiştir.
