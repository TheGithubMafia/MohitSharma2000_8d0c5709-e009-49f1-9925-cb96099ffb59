# IMDb_Recommendation

This script, can help one choose a Movie according to his/her mood at the time.
By using this script, and feeding one of the supported emotion, the person can retrieve a list of movies.
The script uses genres from IMDb websites and hence are always updated according to user ratings.


## Dependency

- requests
- BeautifulSoup
- lxml

These are summarised in [`requirements.txt`](requirements.txt)


## Setup

1. A virtual environment (recommended)
1. `pip install -r requirements.txt`
1. Determine the motion according to which movies shall be listed.
1. Run the Script, follow the subsequent guidelines.

## Usage

Sample Usage -

`
python movie_mood.py
`

Output -

```
Select Your Emotion:
 1. Anger
 2. Anticipation
 3. Disgust
 4. Fear
 5. Joy
 6. Sad
 7. Surprise
 8. Trust
Enter the emotion: Sad
Pieces of a Woman
The Karate Kid
The Midnight Sky
Promising Young Woman
```

## Disclaimer

- This implementation uses crawling as a technique for recommendation.
- Deep Learning is a better tool, although lack of dataset is a major problem.

## Author(s)  

Made by [Vybhav Chaturvedi](https://www.linkedin.com/in/vybhav-chaturvedi-0ba82614a/)

