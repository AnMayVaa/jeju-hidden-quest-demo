# Jeju Hidden Quest

A mobile web prototype of a **tourist treasure-hunt app for Jeju Island**. Travelers discover hidden local spots, prove they visited, earn **Jeju Tokens** and trade them for real rewards.

## Demo flow

1. **Discover a hidden gem.** An example is *Grandma Kim's Bibimbap House (김할머니 비빔밥)*, a traditional spot running since 1980, shown with a story and a translated menu.
2. **Claim the location.** An anti-cheat check asks a question you can only answer on site ("What color is the old wooden mailbox next to the entrance?").
3. **Earn tokens.** A correct answer adds +100 Jeju Tokens to your wallet, with a confetti celebration.
4. **Reward Store.** Spend tokens on experiences. Rewards stay locked until you have enough, and each shows how many more tokens you need:
   - Skip the Line: Jeju National Museum (150)
   - Free Hanbok Rental, 1 hour (100)
   - Free Tangerine Ice Cream (120)
5. **Redeem.** You get a QR voucher to show staff, with a 15-minute countdown.

## Tech

- A single `index.html` with vanilla JavaScript and Tailwind CSS (CDN)
- QR codes from the [goQR.me API](https://goqr.me/api/)
- Mobile-first layout. The demo uses mock data and has no backend.

## Run

Open `index.html` in a browser. Use the device toolbar in DevTools for a phone-sized view.
