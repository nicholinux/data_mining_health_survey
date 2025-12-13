This was my final project for my Data Mining Class.

According to the World Health Organization (WHO), depression and anxiety cause up to **12 billion** missed work days every year, resulting in economic damages of about **$1 trillion USD** [1]. It's an issue that has seen explosive growth over the last few years.
This project serves as a proof of concept for the usage of ML to aid decision-making in public health policy. 

Using Mood_Swings (Yes/No column) as my target variable, I built a decision tree to classify people's risk for mood swings based on lifestyle information gathered from survey data.
Mood swings are often a warning sign for an impending mental health crisis, so by being able to predict the liklihood of an individual experiencing these symptoms, local and state governments can more effectively allocate healthcare resources for vulnerable populations.

With the decision tree model, I was able to predict the likelihood of an individual having mood swings using their survey data with an accuracy rate of **96%**.
High accuracy, however, does not necessarily indicate optimal model performance - it may be an indicator of overfitting. Luckily, the accuracies of the test and train data were nearly identical, meaning the model performs well on unseen data.

-------------------------------------------------------------------------------------------------------------------

Sources:

[1] https://www.who.int/news-room/fact-sheets/detail/mental-health-at-work


