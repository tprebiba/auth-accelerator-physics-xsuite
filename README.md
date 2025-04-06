# Προσομοιώσεις Πλεγμάτων Επιταχυντών με Python και Xsuite
#### Φυσική των Επιταχυντών
#### Μεταπτυχιακό Υποατομικής Φυσικής, 2o έτος
#### Τμήμα Φυσικής / Αριστοτέλειο Πανεπιστήμιο Θεσσαλονίκης
#### Εαρινό εξάμηνο 2025 

*T. Prebibaj, F. Antoniou, F. Asvesta, Y. Papaphilippou*

Για διορθώσεις: [tirsi.prebibaj@cern.ch](mailto:tirsi.prebibaj@cern.ch)

Βασίζεται σε μεγάλο βαθμό στο μάθημα «[Hands-On Lattice and Longitudinal Calculations - Python version](https://github.com/cerncas/hands-on-lattice-exercises)» που διδάσκεται στο «CERN Accelerator School (CAS) – Introduction to Accelerator Physics», αλλά και στο «[Advanced Training School on Operation of Accelerators](https://github.com/tprebiba/eurolabs-atsoa-psb)» του «EUROLABS».

Το μάθημα είναι χωρισμένο σε 5 μέρη:

- Μάθημα 1ο: Tracking basics (**Python notebook 1A**)
    - Representing particles
        - Exercise 1: representing a single particle in Python
        - Exercise 2: representing multiple particles (a beam) in Python
    - Accelerator elements
        - Exercise 3: transfering particles in a drift space
        - Exercise 4: focusing particles 
    - Simple beamlines
        - Exercise 5: transfer a particle in a beamline

- Μάθημα 2ο: Single particle dynamics in simple beamlines (**Python notebook 1B**)
    - The FODO cell
        - Exercise 6: tracking in a FODO cell
        - Exercise 7: x' of the FODO cell
        - Exercise 8: multiple FODO cells
        - Exercise 9: betatron oscillations
        - Exercise 10: stability of the FODO cell

- Μάθημα 3ο: Single particle dynamics in periodic systems (ring) (**Python notebook 2A**)
    - Transverse dynamics in a ring
        - Exercise 11: phase space in a stable ring
        - Exercise 12: optics, trace and single particle emittance of the ring
        - Exercise 13: stability of the ring
        - Exercise 14: transport of Twiss functions

- Μάθημα 4ο: Tracking multiple particles (**Python notebook 2B**)
    - Transverse dynamics of a beam
        - Exercise 15: evolution of beam along a ring
        - Exercise 16: beam with an offset 
    - Beam emittance
        - Exercise 17: preservation of the beam emittance
        - Exercise 18: emittance and phase space area

- Μάθημα 5ο: Tracking with Xsuite  (**Python notebook 3**)
    - The CERN Proton Synchrotron Booster (PSB)
        - Exercise 19 (guided): load and plot the layout of the PSB
        - Exercise 20 (guided): plot the optics functions
        - Exercise 21 (guided): matching
        - Exercise 22 (guided): tracking
        - Exercise 23 (guided): reconstruct tune from turn-by-turn data
        - Exercise 24 (guided): motion near a quadrupolar resonance - beta-beating
        - Exercise 25 (guided): motion on a quadrupolar resonance - phase space