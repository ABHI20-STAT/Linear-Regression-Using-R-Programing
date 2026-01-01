# Linear Regression for Insight (R)  
**1-Month Course (4 Weeks): Univariate → Bivariate → Multiple Linear Regression**  
*Colab-ready Markdown notebook (copy/paste into a Google Colab text cell).*

---

## 0) How to use this notebook
This notebook is designed for **teaching + hands-on practice**.

**Each week contains:**
- ✅ Learning goals  
- ✅ Sufficient theory (only what you need to interpret results)  
- ✅ R coding labs  
- ✅ Diagnostics + interpretation checklist  
- ✅ Weekly assignment  

> **Tip (Colab):** Use **Runtime → Change runtime type → R** (if available).  
If R runtime isn’t available, you can still use this notebook in any R environment (RStudio / Posit Cloud).

---

## 1) Setup (Run once)

### 1.1 Install and load packages
```r
# If needed:
# install.packages(c("tidyverse","broom","car","lmtest","sandwich"))

library(tidyverse)
library(broom)
library(car)
library(lmtest)
library(sandwich)

