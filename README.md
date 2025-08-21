🐦 Deepfake Tweet Detection Using CNN + FastText + Random Forest
📌 Overview

This project focuses on detecting AI-generated (deepfake) tweets on social media. With the rise of generative AI, distinguishing between human-written and machine-generated text is crucial for preventing misinformation.

We propose a hybrid deep learning model that integrates Convolutional Neural Networks (CNN) with Random Forest classification.

FastText embeddings are used for effective word representation.

CNN extracts local linguistic features from tweets.

Random Forest provides robust classification between human-written and AI-generated tweets.

🚀 Features

✅ Detects AI-generated tweets with high accuracy
✅ FastText embeddings for subword-level word representation
✅ CNN for feature extraction
✅ Random Forest for robust classification
✅ Scalable for real-time tweet analysis

🛠 Tech Stack

Programming Language: Python 3.8+

Deep Learning Framework: TensorFlow / Keras

Word Embeddings: FastText

Machine Learning: Scikit-learn (Random Forest)

Data Handling: Pandas, NumPy

Visualization: Matplotlib, Seaborn

📂 Project Structure
📦 deepfake-tweet-detection  
 ┣ 📂 dataset/             # Dataset (tweets: human + AI-generated)  
 ┣ 📂 models/              # Saved models (CNN + RF)  
 ┣ 📂 notebooks/           # Jupyter notebooks for experiments  
 ┣ 📜 requirements.txt     # Dependencies  
 ┣ 📜 train_cnn.py         # CNN training script  
 ┣ 📜 train_rf.py          # Random Forest training script  
 ┣ 📜 hybrid_model.py      # CNN + RF integration  
 ┣ 📜 evaluate.py          # Model evaluation  
 ┣ 📜 app.py               # Deployment / Flask app (optional)  
 ┣ 📜 README.md            # Project documentation  

⚙️ Installation & Usage

1️⃣ Install dependencies

pip install -r requirements.txt


3️⃣ Train CNN model

python train_cnn.py


4️⃣ Train Random Forest on CNN features

python train_rf.py


5️⃣ Evaluate hybrid model

python evaluate.py

📊 Results

High accuracy in distinguishing AI vs. human tweets

Reduced false positives compared to traditional models

Faster classification compared to RNN-based approaches

🔮 Future Scope

Extend to multi-lingual tweet detection

Deploy as a real-time social media monitoring tool

Integrate with transformer-based models (BERT, RoBERTa)

🤝 Contributing

Contributions are welcome! Feel free to fork the repo, create a branch, and submit a pull request.

📧 Contact

👤 Palukuru Hemanth Kumar

🔗 LinkedIn: Hemanth Kumar Palukuru

📧 Email: p.hemanth591@gmail.com
