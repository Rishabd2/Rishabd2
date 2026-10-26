# Rishab Doshi

I build benchmarks and evaluations for healthcare AI, with a focus on animal health data.
I spent two years inside UIUC's VetMed Innovation Hub, in the AI group working on unstructured clinical records.
I work in translational oncology and support One Health.

## Research focus

- **Evals and benchmarking for veterinary AI:** test sets and scoring that show where clinical models fail.
- **Clinical record pipelines:** ingestion and retrieval over unstructured veterinary records.
- **Veterinary software:** clinical tools built for veterinary practices.
- **Translational medicine:** carrying findings between animal and human health.
- **Comparative oncology:** canine osteosarcoma as a model for the human disease.

## Replications

**[canine-osteosarcoma-signatures](https://github.com/Rishabd2/canine-osteosarcoma-signatures)**: a claim-by-claim replication of Mannheimer et al. 2023 (*Communications Biology*), on whether prognostic gene signatures from 300+ dogs in an NCI trial transfer to human osteosarcoma (TARGET-OS). Two human clusters match the paper patient for patient, and the immune signature holds up best. The repo also adds checks the paper did not run: multiple-testing control, a random-signature null, frozen signatures, and a one-to-one ortholog sensitivity analysis. It ends with what I learned and why I tested each claim.

## Selected projects

| Project | What it is | Key result | Stack |
| --- | --- | --- | --- |
| [fake-reviews-analysis](https://github.com/Rishabd2/fake-reviews-analysis) | Three-way detector for truthful, crowdsourced-fake and GPT-4o-mini hotel reviews on the Ott corpus, with hotel-disjoint folds | 92.7 macro F1 (82.3 with prompt artifacts removed); LLM fakes recalled 400 of 400, truthful vs crowdsourced stays the hard pair | Python, scikit-learn, PyTorch |
| [wearable-running-intensity](https://github.com/Rishabd2/wearable-running-intensity) | Running intensity from Apple Watch, treadmill HR and cadence data on three open datasets, evaluated on held-out participants | 0.71 accuracy on 3 intensity levels (majority baseline 0.34); HR rises 6.3 bpm per km/h across 847 treadmill tests | Python, scikit-learn, pandas |
| [prairielearn-er-diagram](https://github.com/Rishabd2/prairielearn-er-diagram) | Open-source PrairieLearn element for drawing and auto-grading Chen-style ER diagrams (AGPL-3.0) | Partial-credit grader that resists padded answers; 46 tests | JavaScript, Python, Mustache |
| [hft-maker-taker](https://github.com/Rishabd2/hft-maker-taker) | Event-driven backtest of imbalance takers and market makers on a reconstructed IEX DEEP book (with Lester Wang and Nikita Volynskiy) | 461 train runs plus held-out tests on 4 symbols, with PnL split into spread, adverse selection, inventory and fees | Python, NumPy |

## Contact

- Email: [rishabd2@illinois.edu](mailto:rishabd2@illinois.edu)
- Site: [rishabd2.github.io](https://rishabd2.github.io)
- LinkedIn: [rishab-doshi](https://www.linkedin.com/in/rishab-doshi/)
- X: [@rishabdoshi88](https://x.com/rishabdoshi88)

San Francisco, California
