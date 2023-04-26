# Generative-Algorithm-for-N-Doped-Novel-Aromatics (GANNA)
This algorithm can be used to add heteroatoms in a combinatorial manner to PAH structures. It takes into account the symmetry of the compounds, preventing the repetition of two compounds with identical structures (canonical smiles). The algorithm optimizes the structure of generated structures using force field.

The idea behind this code is to keep it simple so that anyone working in the field of doped PAH compounds can use it to generate their compounds in a combinatorial fashion. Users are required to provide the following information: 

INPUT:
   
--inp_dir -> (Str) The directory that houses all of the PAH xyz files;
   
--out_dir -> (Str) The directory where the N-doped PAH must be saved;
   
--hetero_nr -> (Int) The total amount of dopants (Nitrogen atoms);

--iters -> (Int) The maximum iteration value of the force field.
