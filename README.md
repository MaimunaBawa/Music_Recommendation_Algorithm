# Music_Recommendation_Algorithm

# About dataset

* Artist_name: The name of the artist

* Track_name: The name of the song

* Release_date: When this song was released

* Genre: The categorical genre of this song

* Lyrics: The pre-tokenized lyrics of this song. Disclaimer: note that as this is real-world data, lyrical content is often obscene. 

* Len:  The number of words in the lyrics of this song

* Dating: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with dating.

* Violence: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with violence.

* World/life: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the world or life in general terms.

* Night/time: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do night-life or time.

* Shake the audience: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with provocative feeling.

* Family/gospel: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with family-oriented content or the gospel.

* Romantic: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with romantic feeling.

* Communication: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with communication (either in romantic terms or otherwise).

* Obscene: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with obscene content (money, rockstar-lifestyle, etc).

* Music: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with music (music about music, basically).

* Movement/places: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with movement or various locations.

* Light/visual perceptions: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the sun or other physical weather-related patterns.

* Family/spiritual: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

* Sadness: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with the importance of family or spirituality.

* Feelings: A score from 0 to 1 expressing how likely it is that this song’s lyrics have something to do with emotions, either positive or negative.

* Topic: The categorical label of lyrical content

* Age: A score from 0 to 1 expressing how “old” a song is from our perspective. 1 being the oldest, and 0 being the newest.

# Hypothesis 

#### Songs with similar lyrical themes and emotional tones can be grouped together using K-Means clustering, regardless of their genre or release year.

# Tools
* Python
* NumPy for mathmatical & statistical operations
* Pandas for data manipulation
* Matplotlib & Seaborn for data visualization
* Scikit-learn for machine learning and data processing
* Statsmodels for statistical data exploration
* Jupyter Notebooks