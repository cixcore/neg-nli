### **InferBR**

- **Train ([23.65%] 1986/8399)**
    
    **>> Premises with negation: 788 (9.38%)**
    label
    1    33.63%
    0    33.63%
    2    32.74%
    >> **Hypotheses with negation: 1402 (16.69%)**
    label
    0    82.03%
    1    16.12%
    2     1.85%
    
- **Test ([25.88%] 455/1758)**
    
    **>> Premises with negation: 204 (11.60%)**
    label
    2    33.33%
    0    33.33%
    1    33.33%
    >> **Hypotheses with negation: 308 (17.52%)**
    label
    0    77.27%
    1    21.10%
    2     1.62%
    

### ASSIN

- **Train ([20.40%] 1020/5000)**
    
    **>> Premises with negation: 689 (13.78%)**
    entailment_judgment
    0    74.46%
    1    19.45%
    2     6.10%
    >> **Hypotheses with negation: 584 (11.68%)**
    entailment_judgment
    0    76.37%
    1    15.92%
    2     7.71%
    
- **Test ([19.57%] 783/4000)**
    
    **>> Premises with negation: 492 (12.30%)**
    entailment_judgment
    0    75.00%
    1    18.29%
    2     6.71%
    >> **Hypotheses with negation: 473 (11.82%)**
    entailment_judgment
    0    79.70%
    1    13.95%
    2     6.34%
    

### ASSIN 2

- **Train ([17.43%] 1133/6500)**
    
    **>> Premises with negation: 573 (8.82%)**
    entailment_judgment
    0    92.50%
    1     7.50%
    >> **Hypotheses with negation: 580 (8.92%)**
    entailment_judgment
    0    93.62%
    1     6.38%
    
- **Test ([19.36%] 474/2448)**
    
    >> **Premises with negation: 247 (10.09%)**
    entailment_judgment
    0    89.88%
    1    10.12%
    >> **Hypotheses with negation: 244 (9.97%)**
    entailment_judgment
    0    89.34%
    1    10.66%
    

### Merged

- **Train ([20.80%] 4139/19899)**
    
    **>> Premises with negation:** **2050 (10.30%)**
    entailment_judgment
    0    76.39%
    1     23.61%
    >> **Hypotheses with negation: 2566 (12.90%)**
    entailment_judgment
    0    84.37%
    1     15.63%
    
- **Test ([20.86%] 1712/8206)**
    
    >> **Premises with negation: 943 (11.49%)**
    entailment_judgment
    0    77.09%
    1     22.91%
    >> **Hypotheses with negation: 1025 (12.49%)**
    entailment_judgment
    0    81.76%
    1     18.24%
    
- Negation types
    
    Train:
    
    | type | total count | entailment 1 | neutral/contr 0 |
    | --- | --- | --- | --- |
    | lex | 93 (2.83%) | 19 (20.43%) | 74 (79.57%) |
    | morph | 239 (7.28%) | 73 (30.54%) | 166 (69.46%) |
    | syn | 2953 (89.89%) | 347 (11.75%) | 2606 (88.25%) |
    
    Test:
