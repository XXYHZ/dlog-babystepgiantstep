# Discrete Logarithm Solver (BabyStepGiantStep)
This tool aims to solve discrete logarithm problems using the BabyStepGiantStep Alogorithm found by Daniel Shanks.
It is best to use with a prime modulus that is near a power of 2 (p)

## CommandLine Arguments:
Define the Console Parameters according to the equation that should be solved e.g.:  

  __h = g^x mod p__  
  (x being the unknown parameter)    
  
  **-h** The Solution of the Logarithmic Equation   
  **-g** The Base (Generator used in Diffie Hellman)  
  **-p** The Modulus (This algorithm works best with prime modulus)  
    
  More Information on BabyStepGiantStep:  
  https://en.wikipedia.org/wiki/Baby-step_giant-step
