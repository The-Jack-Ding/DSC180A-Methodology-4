---
title: Jack Ding | DSC 180A Methodology Assignment 4
---

# Jack Ding

[jading@ucsd.edu](mailto:jading@ucsd.edu)

**Section:** D12 — NLP Credit Score Development  
**Mentor:** Goutham Valeti

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic to me is turning short, ambiguous bank transaction memos into useful categories. A merchant name can point to a platform without telling us whether the transaction was a purchase, transfer, deposit, payout, or fee, so careful labeling matters.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would investigate whether transaction categories add reliable, interpretable signal to credit-risk prediction beyond raw memo strings and basic cash-flow totals. I would first verify that suitable outcome labels are available, then compare predictive value and calibration across held-out accounts.

**What is a potential change you would make to the approach taken in your current Quarter 1 Project?**

I would make human-adjudicated labels for ambiguous and rare categories, together with account-held-out evaluation, the basis for model comparisons from the start. That would reduce the risk of treating provisional labels as ground truth and show whether the model generalizes across accounts.

**What other techniques would you be interested in using in your project?**

I would compare FastText with TF-IDF logistic regression and character n-gram models, then add a confidence-based review or abstention step for ambiguous memos. This would show whether more complex text modeling improves on a simple baseline and help direct human review toward uncertain predictions.
