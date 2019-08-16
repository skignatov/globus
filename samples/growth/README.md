Global optimizations in "Cluster Growth"  mode
----------------------------------------------
This example demonstrates global optimization of platinum clusters in a "cluster growth" mode 
i.e. the successive optimization of clusters structures in a prescribed nuclearity range (here, Pt20-Pt29)
Sutton-Chen interatomic potential, Artificial Bee Colony (ABC) algorithm for GO

Input file :  pt-sc400437-growth-20-29.inp  
Run command:  globus-r4060-win32.exe pt-sc400437-growth-20-29.inp  
Output     : *.out      - optimization monotoring
             *.lm-Pt*   - local minima structures and energies for individual clusters
             *.gpt      - global minimum otimization details
             *.gro      - summary for all clusters in a range


Note: globus-r4060-win32.exe version is given to achieve the complete coincidence with the output files. 
      Other versions can give somewhat different output.
