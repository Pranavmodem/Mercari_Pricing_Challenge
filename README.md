# Mercari_Pricing_Challenge

[![Vijay Tulluri](https://img.shields.io/badge/Vijay-Tulluri-red.svg)](https://vijaytulluri.com/)
[![Pranav Modem](https://img.shields.io/badge/Pranav%20-Modem-red.svg)](https://www.linkedin.com/in/pranavmodem/)
[![MIT LICENSE](https://img.shields.io/badge/MIT-License-red.svg)](https://github.com/tullurivijay/Malware_Detection/blob/master/LICENSE.MD)


[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/0)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/0)[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/1)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/1)[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/2)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/2)[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/3)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/3)[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/4)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/4)[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/5)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/5)[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/6)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/6)[![](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/images/7)](https://sourcerer.io/fame/Pranavmodem/tullurivijay/Mercari_Pricing_Challenge/links/7)


***
### Can you automatically suggest product prices to online sellers?

**Product pricing gets even harder at scale**, considering just how many products are sold online. Clothing has strong seasonal pricing trends and is heavily influenced by brand names, while electronics have fluctuating prices based on product specs.

**Mercari**, Japan’s biggest community-powered shopping app, knows this problem deeply. They’d like to offer pricing suggestions to sellers, but this is tough because their sellers are enabled to put just about anything, or any bundle of things, on Mercari's marketplace.

In this competition, Mercari’s challenging you to **build an algorithm that automatically suggests the right product prices**. You’ll be provided user-inputted text descriptions of their products, including details like product category name, brand name, and item condition.

### Dataset Features

- **ID**: the id of the listing
- **Name:** the title of the listing
- **Item Condition:** the condition of the items provided by the seller
- **Category Name:** category of the listing
- **Brand Name:** brand of the listing
- **Shipping:** whether or not shipping cost was provided
- **Item Description:** the full description of the item
- **Price:** the price that the item was sold for. This is the target variable that you will predict. The unit is USD.

### Key Words
- Pricing Recommendation
- Product Features
- NLP
- C2C & B2C

# Representing and Mining Text
***
Since, text is the most **unstructured** form of all the available data, various types of noise are present in it and the data is not readily analyzable without any pre-processing. The entire process of cleaning and standardization of text, making it noise-free and ready for analysis is known as **text pre-processing**.

### Fundamental Concepts 

The importance of constructing mining-friendly data representations; Representation of text for data mining. 

### Important Terminologies
- **Document**: One piece of text. It could be a single sentence, a paragraph, or even a full page report. 
- **Tokens**: Also known as terms. It is simply just a word. So many tokens form a document. 
- **Corpus**: A collection of documents. 
- **Term Frequency (TF)**: Measures how often a term is in a single document
- **Inverse Document Frequency (IDF)**: distribution of a term over a corpus

### Pre-Processing Techniques
- **Stop Word Removal:** stop words are terms that have little no meaning in a given text. Think of it as the "noise" of data. Such terms include the words, "the", "a", "an", "to", and etc...
- **Bag of Words Representation:** treats each word as a feature of the document

- **TFIDF**: a common value representation of terms. It boosts or weighs words that have low occurences. For example, if the word "play" is common, then there is little to no boost. But if the word "mercari" is rare, then it has more boosts/weight. 

- **N-grams**: Sequences of adjacent words as terms. For example, since a word by itself may have little to no value, but if you were to put two words together and analyze it as a pair, then it might add more meaning. For example, "iPhone" VS "iPhone Charger"

- **Stemming and Lemmatization**: Get the root meaning of the word

- **Topic Models**: A type of model that represents a set of topics from a sequence of words. 

