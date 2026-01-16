# OSEA Service Report Form

A mobile-friendly web form for field engineers to document service visits on-site. Generates professional PDF reports and auto-saves to Google Drive.

## Live Form

**[Open Service Report Form](https://osea-in.github.io/Service-Report/Service%20report.html)**

## Features

- **Mobile-First Design** — Works on phones, tablets, and desktops
- **Auto-Save to Cloud** — Reports saved to Google Drive with full audit trail
- **Offline Support** — Works without internet, syncs when back online
- **PDF Generation** — Professional reports via browser print dialog
- **GPS Verification** — Location captured for audit purposes

## Form Sections

1. **Report Details** — Auto-generated report number and date
2. **Client Details** — Company, contact person, phone, email
3. **Visit Details** — Visit type, engineers on-site, arrival/departure dates
4. **Machines** — Multiple machines per report with:
   - Problem reported
   - Observations (numbered list)
   - Activities performed (numbered list)
   - Conclusions (bullet points)
   - Machine status
   - Pending actions table
   - Parts required table
5. **General Recommendations**
6. **Signatures** — OSEA and client representatives

## How to Use

1. Open the form link on your phone
2. Allow location access when prompted
3. Fill out the report sections
4. Tap "Preview & Generate PDF"
5. Review and tap "Generate PDF"
6. Tap "Print / Save PDF" to save

## Technical Details

- **No external dependencies** — Runs entirely in browser
- **No server required** — Works via GitHub Pages
- **Data storage** — Google Drive via Apps Script webhook

## About OSEA

**OmSai Engineering & Automation (OSEA)** provides troubleshooting, AMC, and machine manufacturing services for the extrusion lamination industry.

---

*Built with care for field engineers who need reliable documentation tools.*
