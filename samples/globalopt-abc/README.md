Global optimizations using ABC algorithm
----------------------------------------
This example demonstrates the global optimization of three small magnesium  clusters Mg13, Mg14, Mg19 (all three one by one) 
using the Artificial Bee Colony (ABC) algorithm and Gupta interatomic potential. It takes ~3.2 min on i7/3.5GHz under Windows.

Input file :  MgN-globalopt-GP.inp  
Run command:  globus-r5512-win32.exe MgN-globalopt-GP.inp  
Output     : *.out      - optimization monotoring for all structures
             *.ab-Mg*   - opimization monitoring for individual clusters
             *.lm-Mg*   - local minima structures and energies found for individual clusters
             *.gpt      - global minimum otimization details for each cluster
             *.gro      - summary for all clusters optimized


