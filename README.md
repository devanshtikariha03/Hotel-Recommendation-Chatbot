# Hotel-Recommendation-Chatbot

This repository contains a chatbot for recommending hotels based on specific tags provided in Hindi. The chatbot interacts in both English and Hindi, allowing users to receive hotel suggestions by specifying their preferences. The dataset includes translated tags in Hindi, and the chatbot uses natural language processing to interpret and respond to queries.

**Features:**


Dual Language Support: Interacts in both English and Hindi, making it versatile for users who prefer Hindi for tag-based searches.
Hotel Recommendations: Recommends hotels based on specific Hindi tags related to room types, amenities, and preferences.
Interactive Chatbot: Engages users with conversational responses, making it easier to search for hotels by preferences.

**Requirements:**


Ensure the following libraries are installed:

pip install pandas nltk


**Dataset Preparation:**


The initial dataset (new_dataset.csv) contains tags in English. A predefined dictionary in the code translates these tags into Hindi, creating new_dataset_hindi.csv. This translated dataset is used to filter and recommend hotels based on Hindi tags that users specify.

**How it Works:**


Tag Matching: The chatbot accepts Hindi tags as input and compares them with each hotel’s tags in the dataset. If the tags match the user’s criteria, the corresponding hotel names are returned as suggestions.


Chatbot Response: Using natural language processing, the chatbot recognizes different input patterns and responds in Hindi, providing hotel recommendations or addressing general questions.

**Example Interaction:**


User: मुझे क्लब लाउंज के साथ जूनियर सूट जैसे होटल सुझाएं।


Chatbot: बिल्कुल, मैं आपको क्लब लाउंज के साथ जूनियर सूट जैसे होटल सुझा सकता हूँ:

XYZ Hotel


ABC Hotel

**Configuration:**


Hindi Tags Dictionary: The hindi_tags dictionary in the code maps each English tag to its Hindi equivalent. You can add or modify entries in this dictionary for more customized recommendations.


**Dependencies:**


Pandas: For loading and processing the dataset.


NLTK (Natural Language Toolkit): For building the chatbot and managing language patterns.


**Acknowledgments:**


This project leverages NLTK for natural language processing to create an interactive chatbot.


Data filtering through Pandas allows efficient matching of hotels based on Hindi tags specified by users.
