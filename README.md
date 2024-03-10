# Sentiment-Analysis
This Project will show you how to develop a Deep Neural Network for text classification (sentiment
analysis).  Preprocessing using a pre-trained model that converts text into
numeric vectors
Convert text to embedding vectors using the Universal Sentence Encoder model
- Build a hotel review Sentiment Analysis model
- Use the model to predict sentiment on unseen data
# The Data
The dataset is hosted on https://www.kaggle.com/datasets/jiashenliu/515k-hotel-reviews-data-in-europe and is provided by Jiashen Liu³⁰⁶. It contains European hotel
reviews that were scraped from https://www.booking.com/
This dataset contains 515,000 customer reviews and scoring of 1493 luxury hotels across
Europe. Meanwhile, the geographical location of hotels are also provided for further
analysis
# Load the Data
df = pd.read_csv("Hotel_Reviews.csv, parse_dates=["Review_Date"])
# Univeral Sentence Encoder
Unfortunately neural network don’t understand text data. To deal with the issue, you must figure
out a way to convert text into numbers. There are a variety of ways to solve the problem, but most
well-performing models use https://developers.google.com/machine-learning/crash-course/embeddings/video-lecture
