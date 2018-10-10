### Data Related to the Paper:

# Variability in Pharmacologically-induced Coma for Treatment of Refractory Status Epilepticus
### (PONE-D-18-11621R1)

Jingzhi An B.Eng.1,2; Durga Jonnalagadda M.D.3; Valdery Moura Junior M.S.3; Patrick L. Purdon Ph.D.3; Emery N. Brown M.D., Ph.D.1,2,3,4,5; M. Brandon Westover M.D.Ph.D.3

1, Massachusetts Institute of Technology
2. Harvard-MIT Division of Health Science and Technology
3. Massachusetts General Hospital, Harvard Medical School
4. MIT Department of Brain and Cognitive Sciences
5. Institute of Medical Engineering and Sciences

Corresponding Author:
Jingzhi An, M.D., Ph.D. candidate
jzan@mit.edu


-------------------------------------------------------------------------------------------

Each data file contains two struct: 

1. eegdata
   * patient: string - a code to identify the patient by
   * Bin: logical - location of the 
   * Bin_num: double - time stamp for binary data measured in days

2. drugdata
   * Attempt: logical - indicates the clinical attempt for burst suppression
   * MDL: double - midazolam infusion rate
   * PROP: double - propofol infusion rate
   * timestamp: double - time stamp for Attempt, MDL and PROP
   * Weight: double - patient weight
   * patient: string - a code to identify the patient by
