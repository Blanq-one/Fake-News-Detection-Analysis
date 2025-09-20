📰 Fake News Detection using LSTM


📌 About the Project

The spread of fake news has become a major concern in today’s digital world. This project leverages Natural Language Processing (NLP) and Deep Learning (LSTM) to automatically identify whether a news article is reliable or unreliable.

📂 Dataset Information

Each news article contains the following attributes:

id → Unique identifier for the article

title → Title of the news article

author → Author of the news article

text → Main content of the article (may be incomplete)

label → Target variable

1 → Unreliable (fake news)

0 → Reliable (real news)

🔑 Features

Text preprocessing with NLTK

Word embeddings for semantic understanding

LSTM network for sequential text classification

High accuracy with sufficient training epochs (>50)

📚 Libraries Used

pandas

matplotlib

keras

tensorflow

scikit-learn

🧠 Model Architecture

Embedding Layer for text vectorization

LSTM Layers for sequence learning

Dense Output Layer with binary classification (real/fake)

📊 Results

Achieved 95% accuracy after training for more than 50 epochs.

Model effectively distinguishes between fake and real news articles.

🔮 Future Improvements

Use pre-trained embeddings (GloVe, Word2Vec, BERT)

Explore advanced architectures (Bi-LSTM, GRU, Transformers)

Extend dataset for broader coverage across sources and domains

🤝 Contributing

Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests for improvements.


✨ “Fighting misinformation with the power of AI and Deep Learning.”
