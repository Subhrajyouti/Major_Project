

# Discharge Rate Prediction for Return Period of 25, 50 and 100 year Estimation using Python

**Hydrodynamic Modeling of Hooghly River – Chapter 5 Results Analysis**

This repository presents the Python-based analysis used to estimate discharge values for different return periods (25, 50, 100 years) as part of the final year B.Tech project: *Hydrodynamic Modeling of the Hooghly River (from Howrah Bridge to Gadiara)* using HEC-RAS.

---

## \[✔] Project Objective

To develop statistical models using Python to estimate discharge rates for various return periods, supporting flood forecasting and risk assessment in the Hooghly River basin.

---

## \[📍] Study Area

* **River:** Hooghly River, a distributary of the Ganges
* **Location:** From Howrah Bridge to Gadiara
* **Region Characteristics:**

  * Tidal influences from the Bay of Bengal
  * Prone to sedimentation and flood events
  * Urban zones such as Kolkata are highly vulnerable

---

## \[🧪] Methodology

### 1. Data Collection

* Historical maximum discharge data from river gauges
* Associated return period estimations using hydrological methods

### 2. Modeling Techniques Used

| Method                    | Description                                                         |
| ------------------------- | ------------------------------------------------------------------- |
| **Linear Regression**     | Fits a straight line to predict discharge using return period       |
| **Polynomial Regression** | Fits a second-degree curve to capture non-linear trends             |
| **Log-Log Regression**    | Fits a power-law model (`Q = a*T^b`) after log transformation       |
| **Gumbel Distribution**   | Applies extreme value theory to model flood discharge probabilities |

---

## \[📊] Results Overview

| Return Period (years) | Discharge (Log-Log Model) | Discharge (Gumbel Model) |
| --------------------- | ------------------------- | ------------------------ |
| 25                    | Estimated value (Python)  | Gumbel predicted value   |
| 50                    | Estimated value (Python)  | Gumbel predicted value   |
| 100                   | Estimated value (Python)  | Gumbel predicted value   |

* Log-log regression gave the best fit on the scatter plot.
* Gumbel distribution validated the estimates with hydrological consistency.

---

## \[📁] Project Structure

```
.
├── data/
│   └── discharge_return_period.csv       # Processed input data
├── notebooks/
│   └── discharge_estimation.ipynb        # Core Jupyter notebook
├── plots/
│   └── return_period_fits.png            # Output graphs
├── README.md
└── requirements.txt                      # Required Python packages
```

---

## \[🧰] Tools and Libraries Used

* **Python 3.10**
* **NumPy** – Numerical operations
* **Pandas** – Data manipulation
* **Matplotlib** – Plotting
* **Scikit-learn** – Regression modeling
* **SciPy** – Gumbel distribution and curve fitting

---

## \[📚] References

* HEC-RAS User Manual – USACE
* Gumbel Extreme Value Analysis – WMO
* Engineering Hydrology (for flood estimation techniques)
* Python statistical libraries documentation

---

## \[👤] Authors

* Subhrajyoti Mahanta (2021CEB094)
* Vijay Prakash (2020CEB063)
  *B.Tech Final Year – Civil Engineering Department*
  *Indian Institute of Engineering Science and Technology, Shibpur*

---

## \[📅] Date of Submission

May 2025

