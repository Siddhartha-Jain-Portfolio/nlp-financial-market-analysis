# NLP-Based Financial Market Analysis

## Overview

This project explores whether unstructured data — such as financial news, themes, and earnings communication — can provide meaningful insight into market behaviour.

Instead of building a predictive model, the focus is on **signal understanding**:

* What type of information matters?
* Which signals align with market movement?
* Where do limitations exist?

---

## Objective

To evaluate whether text-based signals can help explain market behaviour beyond traditional structured data.

---

## Data Used

* Financial News Data
* Earnings Communication Data
* Market Returns (Nifty Index + Selected Stocks)

All datasets are aligned using the **date** as the common reference.

---

## Methodology

The project follows a step-by-step analytical approach:

1. **Sentiment Analysis**
   Converts news tone into numerical signals

2. **Entity Analysis**
   Identifies key subjects (companies, events, macro factors)

3. **Theme Analysis**
   Groups related information into broader narratives

4. **Multi-Signal Analysis**
   Combines sentiment, entity, and theme signals

5. **Earnings + Theme Analysis**
   Combines company-level communication with market context

---

## Key Findings

* **Sentiment Signal** → Weak (~50% alignment)
* **Entity Signal** → Noisy and inconsistent
* **Theme Signal** → Stronger, more interpretable
* **Multi-Signal Combination** → Introduces noise
* **Earnings + Theme** → Improves at stock level (~70%), weak at market level

---

## Final Insight

Market behaviour is better understood through **context and narratives** rather than isolated signals.

Unstructured data:

* Helps explain *why* markets move
* Does not reliably predict *what* will happen

---

## Project Structure

* `NLP_Project_Report.pdf` → Final structured report
* `NLP_Working_Analysis.pdf` → Detailed step-by-step analysis
* `NLP_Project_Summary.pdf` → Short summary of findings
* `nlp_news_data.csv` → Processed news dataset
* `nlp_earnings_data.csv` → Earnings dataset
* `nlp_stocks_returns.csv` → Market returns dataset

---

## Tools & Approach

* Python (NLP processing: sentiment, entities, phrases)
* BigQuery SQL (data structuring and analysis)
* View-based pipeline for modular workflow

---

## Limitations

* Limited and event-based dataset
* Bias in news and earnings data
* Subjective theme construction
* Weak signal strength at market level

---

## Conclusion

Unstructured data adds **context**, not certainty.
Theme-based signals provide the most meaningful insight, while other signals remain weak or noisy when used independently.

---

## Author

Siddhartha Jain
PGDM Finance | Analytical & Data-Driven Research

---

