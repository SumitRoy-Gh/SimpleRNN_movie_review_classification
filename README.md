🎬 Movie Review Sentiment Classification using SimpleRNN

A Deep Learning based NLP project that classifies IMDb movie reviews as Positive or Negative using a Simple Recurrent Neural Network (SimpleRNN) built with TensorFlow/Keras.

This project demonstrates the complete workflow of:

Text preprocessing
Tokenization & sequence padding
Building a SimpleRNN model
Training and evaluation
Real-time sentiment prediction
🚀 Features
IMDb movie review sentiment classification
Built using TensorFlow & Keras
Sequence preprocessing using Tokenizer
SimpleRNN architecture for sequential learning
Real-time prediction support
Beginner-friendly Deep Learning NLP project
🧠 Tech Stack
Python
TensorFlow / Keras
NumPy
Pandas
Scikit-learn
Matplotlib
📂 Project Structure
SimpleRNN_movie_review_classification/
│
├── simple_rnn.ipynb        # Main training notebook
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
└── saved_model/            # Trained model files
📊 Dataset

This project uses the IMDb Movie Reviews Dataset containing 50,000 highly polarized movie reviews for binary sentiment classification.

Classes:

Positive Review
Negative Review
⚙️ Model Architecture
Embedding Layer
       ↓
SimpleRNN Layer
       ↓
Dense Layer
       ↓
Sigmoid Activation

The model learns sequential patterns from text reviews to predict sentiment polarity.

🏗️ Installation

Clone the repository:

git clone https://github.com/SumitRoy-Gh/SimpleRNN_movie_review_classification.git

Move into the project directory:

cd SimpleRNN_movie_review_classification

Install dependencies:

pip install -r requirements.txt
▶️ Run the Project

Launch Jupyter Notebook:

jupyter notebook

Open:

simple_rnn.ipynb

Run all cells to:

preprocess the data
train the model
evaluate performance
test custom reviews
📈 Results

The model successfully learns sentiment patterns from movie reviews and achieves strong binary classification performance on the IMDb dataset.

Example Predictions:

Review	Prediction
"This movie was absolutely amazing!"	Positive
"Worst movie I have ever watched."	Negative
🧪 Sample Prediction
review = "The movie was fantastic and emotionally powerful."

prediction = model.predict(review)

print("Positive Sentiment")
📚 Learning Outcomes

Through this project, you can understand:

Fundamentals of NLP preprocessing
Tokenization and padding
Sequential data handling
Working of Recurrent Neural Networks
Binary text classification using Deep Learning
🔮 Future Improvements
Upgrade to LSTM/GRU architecture
Add attention mechanism
Deploy using Streamlit/Flask
Hyperparameter tuning
Use pretrained embeddings like GloVe or Word2Vec
🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

Fork the repository
Create a new branch
Commit your changes
Open a Pull Request
📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author
Sumit Roy
GitHub: SumitRoy-Gh
Passionate about Machine Learning, Deep Learning, NLP, and Data Science
⭐ Show Your Support

If you found this project useful, consider giving it a ⭐ on GitHub!
