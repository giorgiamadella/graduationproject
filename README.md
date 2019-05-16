# graduationproject
featuring mediation outputs as per conceptual model

mediation #1 - example

Run MATRIX procedure: 
 
*************** PROCESS Procedure for SPSS Version 3.3 ******************* 
 
          Written by Andrew F. Hayes, Ph.D.       www.afhayes.com 
    Documentation available in Hayes (2018). www.guilford.com/p/hayes3 
 
************************************************************************** 
Model  : 4 
    Y  : voting_i 
    X  : microtar 
   M1  : positive 
   M2  : negative 
   M3  : cognitio 
 
Sample 
Size:  599 
 
Coding of categorical X variable for analysis: 
 microtar       X1       X2 
     ,000     ,000     ,000 
    1,000    1,000     ,000 
    2,000     ,000    1,000 
 
************************************************************************** 
OUTCOME VARIABLE: 
 positive 
 
Model Summary 
          R       R-sq        MSE          F        df1        df2          p 
       ,029       ,001       ,956       ,256      2,000    596,000       ,775 
 
Model 
              coeff         se          t          p       LLCI       ULCI 
constant      2,878       ,088     32,645       ,000      2,705      3,051 
X1            -,088       ,125      -,703       ,482      -,333       ,157 
X2            -,033       ,102      -,327       ,744      -,234       ,168 
 
Standardized coefficients 
        coeff 
X1      -,090 
X2      -,034 
 
************************************************************************** 
OUTCOME VARIABLE: 
 negative 
 
Model Summary 
          R       R-sq        MSE          F        df1        df2          p 
       ,160       ,026      1,220      7,825      2,000    596,000       ,000 
 
Model 
              coeff         se          t          p       LLCI       ULCI 
constant      3,925       ,100     39,420       ,000      3,730      4,121 
X1            -,220       ,141     -1,561       ,119      -,497       ,057 
X2            -,443       ,116     -3,835       ,000      -,670      -,216 
 
Standardized coefficients 
        coeff 
X1      -,197 
X2      -,397 
 
************************************************************************** 
OUTCOME VARIABLE: 
 cognitio 
 
Model Summary 
          R       R-sq        MSE          F        df1        df2          p 
       ,040       ,002      1,121       ,471      2,000    596,000       ,625 
 
Model 
              coeff         se          t          p       LLCI       ULCI 
constant      2,496       ,095     26,139       ,000      2,308      2,683 
X1             ,131       ,135       ,969       ,333      -,135       ,397 
X2             ,061       ,111       ,546       ,585      -,157       ,278 
 
Standardized coefficients 
        coeff 
X1       ,124 
X2       ,057 
 
************************************************************************** 
OUTCOME VARIABLE: 
 voting_i 
 
Model Summary 
          R       R-sq        MSE          F        df1        df2          p 
       ,479       ,229      1,075     35,309      5,000    593,000       ,000 
 
Model 
              coeff         se          t          p       LLCI       ULCI 
constant      1,529       ,207      7,373       ,000      1,122      1,936 
X1            -,304       ,133     -2,283       ,023      -,566      -,042 
X2            -,060       ,110      -,547       ,584      -,276       ,156 
positive       ,559       ,057      9,842       ,000       ,448       ,671 
negative      -,098       ,039     -2,527       ,012      -,175      -,022 
cognitio       ,014       ,052       ,276       ,782      -,088       ,117 
 
Standardized coefficients 
              coeff 
X1            -,258 
X2            -,051 
positive       ,464 
negative      -,093 
cognitio       ,013 
 
************************** TOTAL EFFECT MODEL **************************** 
OUTCOME VARIABLE: 
 voting_i 
 
Model Summary 
          R       R-sq        MSE          F        df1        df2          p 
       ,105       ,011      1,373      3,310      2,000    596,000       ,037 
 
Model 
              coeff         se          t          p       LLCI       ULCI 
constant      2,789       ,106     26,392       ,000      2,581      2,996 
X1            -,330       ,150     -2,201       ,028      -,624      -,036 
X2            -,034       ,123      -,280       ,779      -,275       ,206 
 
Standardized coefficients 
        coeff 
X1      -,280 
X2      -,029 
 
************** TOTAL, DIRECT, AND INDIRECT EFFECTS OF X ON Y ************** 
 
Relative total effects of X on Y: 
       Effect         se          t          p       LLCI       ULCI       c_ps 
X1      -,330       ,150     -2,201       ,028      -,624      -,036      -,280 
X2      -,034       ,123      -,280       ,779      -,275       ,206      -,029 
 
Omnibus test of total effect of X on Y: 
    R2-chng          F        df1        df2          p 
       ,011      3,310      2,000    596,000       ,037 
---------- 
 
Relative direct effects of X on Y 
       Effect         se          t          p       LLCI       ULCI      c'_ps 
X1      -,304       ,133     -2,283       ,023      -,566      -,042      -,258 
X2      -,060       ,110      -,547       ,584      -,276       ,156      -,051 
 
Omnibus test of direct effect of X on Y: 
    R2-chng          F        df1        df2          p 
       ,008      3,173      2,000    593,000       ,043 
---------- 
 
Relative indirect effects of X on Y 
 
 microtar    ->    positive    ->    voting_i 
 
       Effect     BootSE   BootLLCI   BootULCI 
X1      -,049       ,068      -,184       ,084 
X2      -,019       ,058      -,133       ,096 
 
 microtar    ->    negative    ->    voting_i 
 
       Effect     BootSE   BootLLCI   BootULCI 
X1       ,022       ,018      -,006       ,066 
X2       ,044       ,023       ,007       ,096 
 
 microtar    ->    cognitio    ->    voting_i 
 
       Effect     BootSE   BootLLCI   BootULCI 
X1       ,002       ,011      -,020       ,029 
X2       ,001       ,007      -,014       ,019 
 
Partially standardized relative indirect effect(s) of X on Y: 
 
 microtar    ->    positive    ->    voting_i 
 
       Effect     BootSE   BootLLCI   BootULCI 
X1      -,042       ,058      -,157       ,072 
X2      -,016       ,049      -,114       ,082 
 
 microtar    ->    negative    ->    voting_i 
 
       Effect     BootSE   BootLLCI   BootULCI 
X1       ,018       ,016      -,005       ,056 
X2       ,037       ,019       ,006       ,081 
 
 microtar    ->    cognitio    ->    voting_i 
 
       Effect     BootSE   BootLLCI   BootULCI 
X1       ,002       ,010      -,017       ,025 
X2       ,001       ,006      -,012       ,016 
 
*********************** ANALYSIS NOTES AND ERRORS ************************ 
 
Level of confidence for all confidence intervals in output: 
  95,0000 
 
Number of bootstrap samples for percentile bootstrap confidence intervals: 
  5000 
 
NOTE: Standardized coefficients for dichotomous or multicategorical X are in 
      partially standardized form. 
 
NOTE: Variables names longer than eight characters can produce incorrect output. 
      Shorter variable names are recommended. 
 
------ END MATRIX -----

