# Discrete Logarithm Solver (BabyStepGiantStep)
This tool aims to solve discrete logarithm problems using the BabyStepGiantStep Alogorithm found by Daniel Shanks.
It is best to use with a prime modulus that is near a power of 2 (p).

## CommandLine Arguments:
Define the Console Parameters according to the equation that should be solved e.g.:  

  __h = g^x mod p__  
  (x being the unknown parameter)    
  
  **-h** The Solution of the Logarithmic Equation   
  **-g** The Base (Generator used in Diffie Hellman)  
  **-p** The Modulus (This algorithm works best with prime modulus)  
    
  More Information on BabyStepGiantStep:  
  https://en.wikipedia.org/wiki/Baby-step_giant-step
  
## Example Usage:
----------------------------------

__1059878588 = 3116701003^x mod 3696837919__  
```python3 BabyStepGiantStep.py -h 1059878588 -g 3116701003 -p 3696837919```  
  
Solution:   
x = 399870943

----------------------------------
  
__37 = 6^x mod 131__  
```python3 BabyStepGiantStep.py -h 37 -g 6 -p 131```  
  
Solution:   
x = 127  

----------------------------------
