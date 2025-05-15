# 🖼️ Image-Driven Captioning with Custom Music Recommendation 🎵

This project showcases a unique end-to-end system that generates social-media-friendly captions and music recommendations for any image. It combines cutting-edge computer vision, natural language processing, and music analysis techniques to enhance storytelling on digital platforms.


## Project Overview

Given an input image, our system performs the following:
- Extracts features using a **VGG16** Convolutional Neural Network.
- Generates descriptive captions using an **LSTM** model trained on the **Flickr30k** dataset.
- Enhances the caption with **NLP** techniques: POS tagging, stemming, and synonym enrichment.
- Scrapes quote websites to curate relevant captions and generate hashtags.
- Recommends music from Spotify based on the sentiment and themes of the generated caption.
- Uses **LDA Topic Modeling**, **Sentiment Analysis**, and **Cosine Similarity** to align songs with image-based captions.

The system is built using **TensorFlow**, **NLTK**, **Gensim**, **scikit-learn**, **BeautifulSoup**, and deployed with **Streamlit**.

##  Key Features

-  **Contextual Captioning**: Automatically creates platform-friendly, meaningful captions from images.
-  **Visual Processing**: VGG16 + LSTM for understanding scenes and generating descriptions.
-  **Quote & Hashtag Generation**: NLP + web scraping from Goodreads, Lifewire, and Oberlo.
-  **Music Recommendation**: Integration with Spotify and Genius APIs to align mood and theme.
-  **ML Techniques Used**:
  - LDA Topic Modeling
  - TF-IDF & Cosine Similarity
  - Sentiment Analysis
  - KNN classification
  - Transformers for tag generation

##  Demo Flow

1. **Upload** an image via the Streamlit interface.
2. **Generate** a caption and hashtags.
3. **Recommend** a music track that fits the mood of the caption.
4. **Preview** song and metadata (album, artist, genre) and play it directly via an embedded player.

##  Code Repository

All code and application files are available on my collaborator’s GitHub:  
 **[GitHub Repository – ImageDrivenCaptioningAndCustomMusicRecommendations](https://github.com/ManishaMatta/ImageDrivenCaptioningAndCustomMusicRecommendations)**


##  Authors

- **Sabnam Pandit** – Big Data Analytics @ SDSU  
- **Susheel Chebrolu**  
- **Manisha Radhakrishna**  
- **Anurima Saha**

---

>  _This project was developed as part of an academic collaboration and showcases end-to-end machine learning application development, integrating computer vision, NLP, and recommender systems._
