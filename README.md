# Just the Basics - Strata 2013 Kaggle Competition

Welcome to the **Just the Basics** competition, part of an introductory tutorial at Strata 2013 presented by two of Kaggle's very own: **Ben Hamner** and **William Cukierski**. Targeted for those with basic programming experience, this hands-on tutorial covers the end-to-end analysis of predictive data problems and concludes with a live Kaggle competition!

---

## 🗓️ Competition Details

- **Date:** Tuesday, February 26, 2013
- **Location:** Ballroom AB, Strata 2013
- **Competition Start:** 11:15 AM PT (2:15 PM ET)
- **Competition End:** 12:30 PM PT (3:30 PM ET)
- **Open to the public:** Yes, you can participate even if you’re not attending the tutorial.
- **Countdown:** [Click here to view countdown](https://freesecure.timeanddate.com/countdown/i3icdhlm/n886/cf12/cm0/cu4/ct3/cs1/ca0/co0/cr0/ss0/cac333/cpcf00/pct/tcfff/fn3/fs200/szw320/szh135/iso2013-02-26T12:30:00)

---

## 🎯 Competition Format

- **For Fun:** No Kaggle points, no money – just a fun sprint and the glory of Strata bragging rights.
- **Duration:** Just over an hour from start to finish – it’s going to be intense!
- **Unlimited Submissions:** Show our servers who’s boss! (*for small values of unlimited…*)
- **Data Release:** Data will be provided at the start of the competition to prevent any head starts.

---

## 👨‍🏫 About the Presenters

- **Ben Hamner**
  - Expertise in natural language processing, computer vision, web classification, and neuroscience.
  - Former Whitaker Fellow at École Polytechnique Fédérale de Lausanne (EPFL), Switzerland.
  - BSE in Biomedical Engineering, Electrical Engineering, and Math from Duke University.

- **William Cukierski**
  - Bachelor’s degree in physics from Cornell University.
  - Ph.D. in Biomedical Engineering from Rutgers University, with a focus on applying ML in cancer research.

---

## ⚙️ Evaluation Metric

Submissions are judged based on the **Area Under the ROC Curve (AUC)**.

### In Matlab (using the stats toolbox):
```matlab
[~, ~, ~, auc] = perfcurve(true_labels, predictions, 1);

Citation
Ben Hamner and Will Cukierski. Just the Basics - Strata 2013. https://kaggle.com/competitions/just-the-basics-strata-2013, 2013. Kaggle
