# ReviewCarHire - Car Rental Calculator

> A free browser extension that calculates how much revenue your business loses to missed calls.

![Chrome Web Store](https://img.shields.io/chrome-web-store/v/placeholder?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

## What This Extension Does

Small businesses lose an average of **$126,000 per year** to missed calls. This extension provides a simple daily reminder of that cost — and points you toward a solution.

### Calculator Inputs

| Field | Description |
|-------|-------------|
| Calls missed/week | How many calls go unanswered |
| Average job value | $ value of a typical job |
| Conversion rate | % of call inquiries that become paying customers |

**Formula:** `calls × value × rate × 52 = $/year`

## Installation

### Chrome / Edge / Brave

1. Download the latest `.zip` from the [releases page](../../releases)
2. Unzip the file
3. Go to `chrome://extensions/`
4. Enable **Developer mode** (top right toggle)
5. Click **Load unpacked** → select the `calculator-extension` folder

### Firefox

*(Firefox add-on version coming soon — same functionality)*

## Screenshots

*(Add screenshots here: popup-open.png, calculator-result.png)*

## Who This Is For

- Tradies and contractors
- Service businesses with phone inquiries
- Any SMB where phone calls = revenue

## The Solution

If you're tired of losing jobs to missed calls, **[https://reviewcarhire.com](https://reviewcarhire.com)** provides an AI receptionist that answers every call, 24/7 — without hiring staff.

## Tech Stack

- Manifest V3 Chrome Extension
- Vanilla HTML/CSS/JavaScript (no framework needed for a popup)
- PIL for icon generation

## Development

```bash
# View extension structure
ls -la calculator-extension/

# Repackage for Chrome Web Store
zip -r calculator-extension.zip calculator-extension/
```

## License

MIT License — free to use, modify, distribute.

---

**Get the extension:** [https://reviewcarhire.com](https://reviewcarhire.com)
