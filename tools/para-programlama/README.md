# Budget & Debt Tracker | Bütçe ve Borç Takip

A single-page browser app for keeping monthly income, expenses, and debt payments together.

[Open the app](./index.html)

## Features

- Add monthly income and recurring expenses.
- Track credit card, overdraft (KMH), and loan balances separately.
- See monthly income, fixed expenses, debt installments, and remaining cash in one summary.
- Estimate the remaining payoff time and projected payoff month for each debt.
- Compare payoff plans by changing the extra monthly amount.
- Record a regular installment or a one-off extra payment.

Payoff timing is an estimate based on the values entered and the app's calculation assumptions. It is not a guaranteed date or financial advice.

## Use and saved data

Open `index.html` in a modern browser. The app stores its data in that browser profile's `localStorage`; it does not sync between browsers or devices. Clearing browser data also removes the saved entries. Back up important information before clearing the browser.

## Technical notes

- The app is a single `index.html` file using HTML, CSS, and JavaScript.
- Tailwind CSS is loaded from a CDN, so an internet connection is needed for those styles.
- Mahmutcan Zaman set the app's requirements and reviews its behavior. AI assistance was used during development.

## Türkçe

Gelir, gider ve borç bilgilerini aynı ekranda tutan tek sayfalık bir tarayıcı uygulamasıdır.

### Özellikler
- Aylık gelir ve düzenli giderleri kaydetme
- Kredi kartı, ek hesap (KMH) ve kredi borçlarını ayrı izleme
- Gelir, gider, taksit ve kalan tutarı özet ekranda görme
- Girilen değerlere göre tahmini borç kapanış süresini inceleme
- Ek ödeme tutarını değiştirerek farklı planları karşılaştırma
- Taksit veya tek seferlik ara ödeme kaydetme

### Kullanım ve kayıtlar
`index.html` dosyasını güncel bir tarayıcıda aç. Veriler tarayıcı profilinin `localStorage` alanında saklanır; başka tarayıcıya veya cihaza otomatik aktarılmaz. Tarayıcı verilerini silmek kayıtları da siler. Kapanış tarihleri tahmindir, kesin sonuç veya finansal tavsiye değildir.
