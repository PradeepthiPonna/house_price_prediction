# 🏡 House Sales Prediction

This project predicts house prices using Machine Learning with Linear Regression.  
It utilizes a dataset from an online source and applies data preprocessing techniques before training the model.

## 📂 **Files in this Repository**
- 📜 `prodigytask01-ML.ipynb` → Jupyter Notebook with the ML model.
- 📜 `requirements.txt` → List of required Python libraries.
- 📜 `train.csv` → Dataset used for training the model.
- 📜 `README.md` → Project documentation.

## 📌 **How to Run**
1. **Clone the repository**  
   ```bash
   git clone https://github.com/PradeepthiPonna/house_price_prediction.git
   cd house_price_prediction

Install required dependencies

pip install -r requirements.txt
Open the Jupyter Notebook

jupyter notebook prodigytask01-ML.ipynb
Run all the cells step by step to see the results.



🔍 Usage Example
After running the model, you should see a predicted price for a new house like this:


# Example prediction
new_house = [[3, 1500, 2]]  # 3 rooms, 1500 sq. ft, 2 bathrooms
predicted_price = model.predict(new_house)
print(f"Predicted House Price: ${predicted_price[0]:,.2f}")

📌 Output Example:
Predicted House Price: $250,000.00
📌 Dependencies
This project requires the following Python libraries:

🐍 Python
📦 NumPy
🗃️ Pandas
📊 Scikit-learn
📈 Matplotlib
🎨 Seaborn
📓 Jupyter Notebook

Install them using:
pip install -r requirements.txt

🚀 Future Improvements
Add feature engineering for better accuracy.
Implement additional ML models for comparison.
Deploy the model as a web application.
Author :  Pradeepthi Ponna
📧Email:pradeepthiponna3@gmail.com
🔗LinkedIn:www.linkedin.com/in/ponnasatyapradeepthi

### **Instructions to Add This to GitHub**
1. Copy the above text.
2. Open your `README.md` file in **GitHub or a text editor**.
3. Paste the copied content and **save the file**.
4. (Optional) Upload a **scatter plot image** (`sample_output.png`).
5. Commit and push the changes to GitHub:
   ```bash
   git add README.md sample_output.png
   git commit -m "Updated README with output graph and example"
   git push origin main

