# nlp-airbnb-reviews
Airbnb Victoria — NLP &amp; Sentiment Analysis of Guest Reviews

Dataset: 100,000 guest reviews + Airbnb listings.

Methods: VADER Lexicon Sentiment Analysis; Aspect-Based Sentiment Analysis (ABSA); LDA Topic Modelling.

pandas · numpy · matplotlib · seaborn  · vaderSentiment · nltk · scikit-learn (CountVectorizer, LatentDirichletAllocation)

__________
💡 Insight 1: Which neighbourhoods have highest/lowest guest satisfaction?

Method: VADER Sentiment Analysis.

Finding: Yarra Ranges (highest) vs Monash (lowest).



💡 Insight 2: Which experience aspects drive dissatisfaction?

Method: Aspect-Based Sentiment Analysis (ABSA).

Finding: 5 aspects: Listing accuracy, Safety, Amenities & Facilities, Value for Money, and Cleanliness.



💡 Insight 3: What topics are most discussed by guests?

Method: LDA (Latent Dirichlet Allocation) Topic Modelling.

Finding: 3 topics: Overall Experience, Host & Check-in, Location & Transit.

__________
Business Recommendations

1. For hosts in general: Improve listing accuracy (current photos, accurate descriptions), upgrade high-use amenities, and strengthen door security.

2. For hosts in Monash: Reposition listings to target Monash University students — upgrade Wi-Fi, study furniture, and update listings with accurate, student-oriented descriptions.

3. For hosts in outer suburbs: Offer Myki card welcome basket or airport pickup to address reviews about Location & Transit.
