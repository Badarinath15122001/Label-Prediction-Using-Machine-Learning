# 🚀 Label Prediction Using Machine Learning  

## 📌 Overview  
Stack Overflow is the largest online platform for developers to ask and answer coding-related questions. Manually tagging questions can be **time-consuming** and **prone to errors**.  

This project uses **Machine Learning (ML) and Natural Language Processing (NLP)** to **automatically predict relevant tags** for Stack Overflow questions based on their **title and description**. The model is trained using **Logistic Regression with OneVsRest Classifier**, optimizing **accuracy and recall** for multi-label classification.  

---  

## 🎯 Features  
✅ Predicts relevant Stack Overflow tags based on the question.  
✅ Uses **Logistic Regression + OneVsRest Classifier**.  
✅ Includes **NLP preprocessing** (tokenization, stopwords removal).  
✅ Trained on **large Stack Overflow datasets**.  
✅ Implemented in **Jupyter Notebook**.  

---  

## 📂 Project Structure  
```
📂 Label-Prediction-Using-Machine-Learning/
│── 📄 README.md          # Project documentation
│── 📄 LICENSE            # MIT License
│── 📄 requirements.txt   # Python dependencies
│── 📂 data/              # Store datasets (not included in repo)
│   ├── download_data.txt # Instructions to download dataset
│── 📂 notebooks/         # Store Jupyter Notebooks
│   ├── StackOverflow_Prediction.ipynb  # Main notebook
```

---  

## 🔧 Installation & Usage  

### 📥 1️⃣ Clone the Repository  
```sh
git clone https://github.com/Badarinath15122001/Label-Prediction-Using-Machine-Learning.git
cd Label-Prediction-Using-Machine-Learning
```

### 📦 2️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 📝 3️⃣ Running in Jupyter Notebook  
```sh
jupyter notebook
```
📌 Open `notebooks/StackOverflow_Prediction.ipynb` and run all cells.  

---  

## 📊 Dataset  
Download the dataset from these links:  
- **Train Dataset:** [Google Drive Link](https://drive.google.com/file/d/1c3I_5A2VXfR418p8Fc2dpn9oY_x5XAyP/view?usp=drive_link)  
- **Test Dataset:** [Google Drive Link](https://drive.google.com/file/d/1GvvPEIk8oaHs2pd853TLn7CMchqlL_3l/view?usp=drive_link)  

---  

## 📈 Results  

| Metric                | Score  |
|-----------------------|--------|
| **Accuracy**         | 81%    |
| **Micro F1-Score**   | 0.67   |
| **Macro F1-Score**   | 0.37   |
| **Hamming Loss**     | 0.0004 |

---  

## 🔥 Future Enhancements  
🔹 Use **Deep Learning Models (LSTM, Transformers)** for better accuracy.  
🔹 Integrate with **Stack Overflow API** for real-time tagging.  
🔹 Optimize dataset preprocessing for larger training sets.  

---  

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---  

## 👨‍💻 Author  
Developed by **Badarinath Sai Balaji**  
🔗 **LinkedIn:** https://www.linkedin.com/in/badarinathsaibalaji/  
📧 **Email:** badarinath15122001@gmail.com  
