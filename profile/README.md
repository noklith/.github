<div align="center">
  <img src="logo.png" alt="Noklith" width="110">

  <h1>Noklith</h1>

  <p><strong>A virtual Visa card you refill from your own crypto wallet.</strong></p>

  <p>
    <a href="https://noklith.com">Site</a> ·
    <a href="https://noklith.com/dashboard.html">Dashboard</a>
  </p>
</div>

---

Sign in by signing a message in your wallet, refill the card with USDT or USDC on **Polygon** or
**BNB Smart Chain**, and spend it anywhere Visa is accepted online. No password, no account form,
and nobody ever asks for your private key.

Cards are issued through **IZIPAY Business**. The balance in the app is read from the issuer, so
purchases and refunds show up in your history on their own.

### Three decisions worth knowing

**A refill lands once.** The server checks the transfer on chain (token, sender, recipient, amount,
confirmations) before the card is loaded, and retries never credit it twice.

**Connecting is not signing in.** A session starts only after you sign a SIWE message bound to
`noklith.com`.

**Money is never a float.** Cents and token units are whole numbers end to end.

### Repositories

**[noklith](https://github.com/noklith/noklith)**: the website and dashboard, the iOS app (SwiftUI,
iOS 17+) and the API, in one repository.
