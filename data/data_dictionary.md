# Data Dictionary

Dataset: South Korean Newspaper Twitter Posts (2018–2019)

| Column         | Type      | Description                             | Example     |
| -------------- | --------- | --------------------------------------- | ----------- |
| text           | string    | Original tweet text                     | "문재인 정부..." |
| newspaper      | string    | Newspaper source                        | "Hankyoreh" |
| pol_id         | string    | Ideological classification of newspaper | "left"      |
| favoriteCount  | integer   | Number of likes/favorites               | 124         |
| retweetCount   | integer   | Number of retweets                      | 56          |
| created_at     | date/time | Tweet publication timestamp             | 2017-05-01  |
| processed_text | string    | Preprocessed version used for analysis  | "문재인 정부 개혁" |

Notes:

- Tweets originate from six South Korean newspapers.
- Left-leaning newspapers: Hankyoreh, Kyunghyang.
- Right-leaning newspapers: Chosun Ilbo, Dong-a Ilbo, Joongang Ilbo, Hankyung.
- Sentiment scores were generated using KNU sentiment dictionaries.
- Topic modeling was conducted after preprocessing and stopword removal.

