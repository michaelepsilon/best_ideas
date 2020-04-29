# Aggregate Alpha in the Hedge Fund Industry: A Further Look at Best Ideas 
Repository containing all files for the following paper, https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3586138

## Relevant Notation
<img src="http://www.sciweavers.org/tex2img.php?eq=%20%20%20%20%5Cbar%20w_k%26%3D%5Cfrac%7BN_kS_k%7D%7B%5Csum_%7B%5Cell%5Cin%20A%7DN_%5Cell%20S_%5Cell%20%7D%5Cqquad%5Cforall%20k%5Cin%20A%20%20%5C%5C%0A&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="    \bar w_k&=\frac{N_kS_k}{\sum_{\ell\in A}N_\ell S_\ell }\qquad\forall k\in A  \\" width="211" height="31" />

## Methods
* Method 1
  * Market Tilt
* Method 2
  * Variance-adjusted Market Tilt
* Method 3
  * Intra-Cap Weight Tilt
* Method 4
  * Variance-adjusted Intra-Cap Weight Tilt
* Method 5
  * Mean-Variance Tilt
* Method 6
  * Cap-Weight Adjusted Mean-Variance Tilt
* Method 7
  * Intra-Cap Weight Adjusted Mean-Variance Tilt
* Method 8
  * Raw Portfolio Weight
* Method 9
  * Asset Weighted HFU Tilt
  
## File Structure
* Title and Imports
* Fetch holdings, benchmark, returns information
* Calculate Best Ideas with respect to tilt and additional filters
* Back-test the portfolio and report cumulative / yearly performance
* Fetch Factor Models (Carhart Four, Fama French Five, Q Factor Model)
* Present Regressions
  * Full Time Period
    * Carhart Four, Fama French Five, Q Factor Model
      * Unadjusted, Newey West (9 lag), Newey West (18 lag)
  * Pre-Crisis
    * Carhart Four, Fama French Five, Q Factor Model
      * Unadjusted, Newey West (9 lag), Newey West (18 lag)
  * Post-Crisis
    * Carhart Four, Fama French Five, Q Factor Model
      * Unadjusted, Newey West (9 lag), Newey West (18 lag)
      
For more information on Epsilon, please see our website: https://www.epsilonmgmt.com/
