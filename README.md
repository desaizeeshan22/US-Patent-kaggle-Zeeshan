This is a competition for UT Dallas MIS/BUAN students. The purpose of this competition is to introduce students to Kaggle Competition. We will use a subset of the patent dataset that was used in the last assignment.

Competition Description
In this competition, students will predict the forward citations a patent will receive. The data set has 16 variables. The data set was collected from USPTO and combined with firm-level variables from Compustat

Practical Skills
Data Pre-processing
Advanced regression techniques like random forest and gradient boosting


# US-Patent-kaggle-Data fields
pat : Patent Number

fwd: Number of forward citation received by patent. This is the target variable that you will predict.

lag_d: Difference between grant date and application date in years.

noc: Number of claims in the patent. The claims in a patent document delineate the legal scope of the patent in precise language.

gy: year in which patent was granted

ay: year in which patent was applied at USPTO (United State Patent Office)

noi: number of inventors

umc: 3-digit technology primary classes of patents.

firm : firm to whom the patent is assigned

MSA: Regional ID: MSA (Metropolitan statistical area) ID for the region of first inventor of patent. Country ID for Non-US countries.

tbm: total backward citations made by the patent. Total number of patents cited by this patent

tbru: technical breadth of patent: defined for the focal patent as where refers to the fraction of patents cited by patent i that belong to technology class j. A higher value indicate that patent is broad.

PAD: Prior art age: Patents are numbered sequentially, with newer patents being assigned higher patent numbers. Based on this information, we measure the age of the prior art for the focal patent as the average patent number of the patents that it cites . A higher value for this variable indicates that the inventors have built the patent on relatively newer technology.

npr: the number of non-patent references cited by the focal patent

fpr: Foreign Patent References: number of foreign patent references cited by focal patent.

FT: Firm_Type: Based On NBER Data types - 7 types of Assigneee: 1 - unassigned; 2 - US non government organization; 3- non US non government organization; 4- US individuals; 5-non US individuals; 6- US government; 7- non US government

fs: Firm Size : Total no of employees from Compustat - based on data for one year before patent application
