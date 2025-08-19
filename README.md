
# 🌦️ Weather Modeling using Quadratic Equation  
**Development Process: Iterative Model**

This project demonstrates **Weather Modeling** using a **quadratic function**:

$$
f(t) = a t^2 + b t + c
$$

The software is developed following the **Iterative Development Model**, with **three iterations**, each adding new functionality:

1. **Iteration 1:** Basic model plots  
2. **Iteration 2:** Add summary statistics (min, max, avg temperatures)  
3. **Iteration 3:** Add combined comparison plot  

---

## 📌 Features by Iteration

### 🔹 Iteration 1
- Reads coefficients `(a, b, c)` from a CSV file  
- Generates and displays individual plots for each model  

### 🔹 Iteration 2
- Includes **Iteration 1 features**  
- Adds **summary statistics table** (min, max, avg temperatures for each model)  

### 🔹 Iteration 3
- Includes **Iteration 1 & 2 features**  
- Adds a **combined comparison plot** with all models on the same graph  

---

## 📂 Project Structure
```

iterative\_weather\_model/
│── iteration1.py   # Basic plots
│── iteration2.py   # Adds summary statistics
│── iteration3.py   # Adds combined comparison plot
│── abc\_values.csv  # Example coefficients
│── README.md       # Documentation

````

---

## ⚙️ Installation
1. Clone this repo or copy the files  
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib
````

---

## 📊 Input Data Format

CSV file `abc_values.csv` should contain the coefficients for the quadratic model:

```csv
a,b,c
0.1,2,10
0.05,1.5,15
-0.02,3,5
0.2,-1,20
-0.05,0.5,8
```

* Each row = one model
* Columns = `a, b, c`

---

## ▶️ Running the Project

### **Iteration 1: Basic Plots**

```bash
python iteration1.py
```

### **Iteration 2: With Statistics**

```bash
python iteration2.py
```

### **Iteration 3: Comparison Plot**

```bash
python iteration3.py
```

---

## ✅ Sample Output

* **Iteration 1:** Plots per model
* **Iteration 2:** Plots + table of summary statistics
* **Iteration 3:** Single graph comparing all models

Example statistics output:

```
   Model  Min Temp  Max Temp  Avg Temp
0      1   10.0000   100.000   55.0000
1      2   15.0000    80.000   45.1234
```

---

## 🔮 Future Improvements

* Add support for seasonal trends (sine/cosine functions)
* Allow dynamic number of iterations
* Provide GUI/Streamlit app for uploading CSV and visualizing results

---

## 👨‍💻 Author

Developed as part of a **Software Engineering project** following the **Iterative Development Model**.

