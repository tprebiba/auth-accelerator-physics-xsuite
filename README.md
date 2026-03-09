# Προσομοιώσεις Πλεγμάτων Επιταχυντών με Python και Xsuite
#### Φυσική των Επιταχυντών
#### Μεταπτυχιακό Υποατομικής Φυσικής, 2o έτος
#### Τμήμα Φυσικής / Αριστοτέλειο Πανεπιστήμιο Θεσσαλονίκης
#### Εαρινό εξάμηνο 2026 

*T. Prebibaj, F. Antoniou, Y. Papaphilippou*

Για διορθώσεις: [tirsi.prebibaj@cern.ch](mailto:tirsi.prebibaj@cern.ch)

Βασίζεται σε μεγάλο βαθμό στο μάθημα «[Hands-On Lattice and Longitudinal Calculations - Python version](https://github.com/cerncas/hands-on-lattice-exercises)» που διδάσκεται στο «CERN Accelerator School (CAS) – Introduction to Accelerator Physics», αλλά και στο «[Advanced Training School on Operation of Accelerators](https://github.com/tprebiba/eurolabs-atsoa-psb)» του «EUROLABS».

Το μάθημα είναι χωρισμένο σε 5 μέρη:

- Μάθημα 1ο: Τα βασικά του tracking (**Python notebook 1A**)
    - Σύστημα συντεταγμένων και αναπαράσταση σωματιδίων
        - Exercise 1: αναπαράσταση ενός σωματιδίου σε Python
        - Exercise 2: αναπαράσταση πολλών σωματιδίων (δέσμης) σε Python  
    - Μαγνητικά Στοιχεία
        - Exercise 3: μεταφορά σωματιδίων σε χώρο ολίσθησης
        - Exercise 4: εστίαση σωματιδίων
    - Simple beam lines (γραμμες δεσμης)
        - Exercise 5: μεταφορά σωματιδίου σε γραμμή δέσμης

- Μάθημα 2ο: Δυναμική ενός σωματιδίου σε απλές γραμμές δέσμης (**Python notebook 1B**)
    - FODO cell
        - Exercise 6: tracking σε ένα κελί FODO
        - Exercise 7: x' του κελιού FODO  
        - Exercise 8: πολλαπλά κελιά FODO  
        - Exercise 9: ταλαντώσεις βήτατρον
        - Exercise 10: σταθερότητα του κελιού FODO  

- Μάθημα 3ο: Δυναμική ενός σωματιδίου σε περιοδικά συστήματα (δακτύλιοι) (**Python notebook 2A**)
    - Εγκάρσια δυναμική σε δακτύλιο
        - Exercise 11: φασικός χώρος σε σταθερό δακτύλιο (phase space in a stable ring)
        - Exercise 12: οπτική, ίχνος (trace) και single particle emittance σε δακτύλιο
        - Exercise 13: σταθερότητα του δακτυλίου  
        - Exercise 14: μεταφορά των συναρτήσεων Twiss

- Μάθημα 4ο: Tracking πολλών σωματιδίων σε δακτύλιο (**Python notebook 2B**)
    - Εγκάρσια δυναμική δέσμης σωματιδίων
        - Exercise 15: δέσμη σωματιδίων κατά μήκος ενός δακτυλίου
        - Exercise 16: δέσμη με αρχική μετατόπιση
    - Εκπεμπτικότητα δέσμης (beam emittance)
        - Exercise 17: διατήρηση της εκπεμπτικότητας δέσμης (beam emittance)
        - Exercise 18: emittance και εμβαδόν φασικού χώρου

- Μάθημα 5ο: Tracking with Xsuite  (**Python notebook 3**)
    - The CERN Proton Synchrotron Booster (PSB)
        - Exercise 19: load and plot the layout of the PSB
        - Exercise 20: plot the optics functions
        - Exercise 21: matching
        - Exercise 22: tracking
        - Exercise 23: reconstruct tune from turn-by-turn data
        - Exercise 24: motion near a quadrupolar resonance - beta-beating
        - Exercise 25: motion on a quadrupolar resonance - phase space