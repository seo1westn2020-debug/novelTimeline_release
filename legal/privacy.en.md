# Privacy Policy

**Product**: novel-timeline
**Provider**: Seo Ilseon
**Effective date**: 2026-04-19

novel-timeline is designed with user privacy as a first-class concern. **Your manuscripts and project data stay on your own device and are never transmitted to the Provider's servers.**

> **Controlling version**: In case of any discrepancy between this English text and the Korean translation ([privacy.md](./privacy.md)), **this English text prevails**.

---

## 1. Core principle — "your data stays on your device"

- All project data you create — manuscripts, characters, events, foreshadowing, relationship graphs, reference material — is stored **exclusively on your local device** (desktop filesystem or the browser's IndexedDB).
- The Provider has **no access to this data, does not receive it, and does not analyze it**.
- AI features (writing assistance, consistency checks) call the AI provider (Anthropic / OpenAI / Google) **directly** using the API key you provisioned yourself (Bring-Your-Own-Key). The Provider's servers are **not** in the request path.

## 2. Information we collect

The Provider only processes data strictly necessary for **billing and license validation**.

### 2.1 Lemon Squeezy (payment processor / Merchant of Record)
Lemon Squeezy collects the following information on our behalf. The Provider views only what is necessary via the Lemon Squeezy dashboard.

| Data | Purpose | Retention |
|---|---|---|
| Name | Receipts, tax filings | **5 years** after payment (Korean tax code) |
| Email address | Delivering the license key, refund/renewal notices, receipts | License lifetime + 5 years |
| Payment instrument metadata (masked card, country) | Fraud prevention | Per Lemon Squeezy policy |
| Billing country | VAT / sales tax | 5 years |

Full payment card numbers are **never collected or stored by the Provider** — they are processed only within Lemon Squeezy's PCI-DSS-compliant environment.

### 2.2 License validation
The following is transmitted to the Provider (or Lemon Squeezy's License API) when your license key is validated:

| Data | Purpose | Retention |
|---|---|---|
| License key | Validity / expiration check | License lifetime |
| App version | Compatibility check | Kept in logs, aggregated anonymously after 90 days |
| Request timestamp | Abuse detection (rate limiting) | Logs, 90 days |

### 2.3 What the application does NOT collect
The following is **never collected**:

- The content of manuscripts, notes, footnotes, or project settings you create
- The content of images or files you attach
- Your IP address (no server-side logging by the Provider)
- Device identifiers (device ID, MAC address)
- Behavioral analytics, advertising identifiers, tracking cookies

## 3. Third-party services

| Service | Role | Privacy policy |
|---|---|---|
| Lemon Squeezy | Payment processing, receipts/tax, license key delivery | https://www.lemonsqueezy.com/privacy |
| GitHub | Product distribution (Releases), public documentation | https://docs.github.com/site-policy |
| Anthropic / OpenAI / Google (the AI provider you choose) | Called **directly** from your machine with your own API key. The Provider does not relay these calls. | Each provider's policy |

## 4. Your rights (GDPR / Korean PIPA)

You have the following rights with respect to your personal data:

- **Right of access**
- **Right to rectification and erasure**
- **Right to restrict processing**
- **Right to data portability**
- **Right to object**
- **Right to withdraw consent** (for consent-based processing)

Requests can be made via email to `askNovelTimeline@gmail.com`. We will respond within **10 business days** of receipt.

## 5. Security measures

- The Lemon Squeezy dashboard is protected by **two-factor authentication (2FA)**.
- All license-API traffic is encrypted via **HTTPS (TLS)**.
- Because your manuscripts stay local, **your device's own security** (OS login password, full-disk encryption) is the primary protection. Regular backups are strongly recommended.

## 6. Children's privacy

novel-timeline is not directed to children under 14. We do not knowingly collect personal information from children in this age group; if we become aware that we have, we will delete it promptly.

## 7. International transfers

Lemon Squeezy is headquartered in the United States (Delaware) and may process billing data in the U.S. and EU regions. By completing checkout, you are deemed to consent to this transfer. See Lemon Squeezy's privacy policy for details.

## 8. Changes to this policy

This policy may be updated to reflect legal changes or product changes. Updates are announced via **GitHub Releases** and the application's **Settings → About** section. Material changes are additionally communicated by email.

## 9. Contact — Data Controller

- Data Controller: Seo Ilseon
- Email: `askNovelTimeline@gmail.com`
- Correspondence languages: Korean, English

---

*Last updated: 2026-04-19*
