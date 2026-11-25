# Paid Media ROI Intelligence and Mathematical Modelling

[![ROI Calculator](https://img.shields.io/badge/TAVARDT-ROI%20Calculator-5b3cf5.svg)](https://tools.tavardt.com/uk/paid-media-roi-calculator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Mathematical modelling utility for ROAS, ROI, and diminishing returns budget scaling projections across enterprise performance media.

***

## Mathematical Modelling and Core Metrics

* **Base ROAS**: Direct ratio between gross generated revenue and paid media expenditure.
* **Base ROI**: Net percentage return on capital allocated to paid advertising.
* **Scale Forecasting with Diminishing Returns**: Algorithmic decay modelling (standard coefficient 0.85) projecting marginal efficiency and performance degradation as budgets scale.
* **Structured Output Formats**: Terminal table output or JSON payloads ready for ingestion into analytics pipelines.

***

## Installation and Quick Start

Requires Python 3.8 or higher using strictly standard library modules with zero third-party packages.

```bash
git clone https://github.com/TAVARDT-UK/ads-roi-intelligence-uk.git
cd ads-roi-intelligence-uk
python roi_engine.py -spend 10000 -revenue 50000 -target-spend 25000
```

To export results in structured JSON format:

```bash
python roi_engine.py -spend 10000 -revenue 50000 -target-spend 25000 -json
```

Also includes the Node.js and browser-compatible JavaScript utility in `calculator.js`.

***

## Revenue Engineering Consulting

For corporate media spend optimisation, econometric modelling, and high-ticket B2B scale in the United Kingdom, contact **TAVARDT United Kingdom**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/uk/
* **Diagnostic Suite:** https://tools.tavardt.com/uk/
* **Technical Contact:** https://ag.tavardt.com/uk/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
