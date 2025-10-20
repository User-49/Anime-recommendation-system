# Anime-recommendation-system using Content Based Filtering(CBF)
this is a part of my semester 3 assignment


The Database was taken from Kaggle
https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset


This is the Structure of anime Database

#   Column        Non-Null Count  Dtype  
---  ------        --------------  -----  
 0   anime_id      24905 non-null  int64  
 1   Name          24905 non-null  object 
 2   English name  10328 non-null  object 
 3   Other name    24777 non-null  object 
 4   Score         15692 non-null  float64
 5   Genres        19976 non-null  object 
 6   Synopsis      24905 non-null  object 
 7   Type          24831 non-null  object 
 8   Episodes      24294 non-null  float64
 9   Aired         24905 non-null  object 
 10  Premiered     5506 non-null   object 
 11  Status        24905 non-null  object 
 12  Producers     11555 non-null  object 
 13  Licensors     4735 non-null   object 
 14  Studios       14379 non-null  object 
 15  Source        21216 non-null  object 
 16  Duration      24242 non-null  object 
 17  Rating        24236 non-null  object 
 18  Rank          20293 non-null  float64
 19  Popularity    24905 non-null  int64  
 20  Favorites     24905 non-null  int64  
 21  Scored By     15692 non-null  float64
 22  Members       24905 non-null  int64  
 23  Image URL     24905 non-null  object



 Anime Dataset Column Descriptions

    anime_id: A unique numerical identifier assigned to the specific anime entry within the database.

        Example: 1 (for the TV series Cowboy Bebop)

    Name: The primary title of the anime, often in its original Japanese form.

        Example: Cowboy Bebop

    English name: The commonly known English title of the anime.

        Example: Cowboy Bebop

    Other name: Alternative titles the anime may be known by, which can include localizations or acronyms.

        Example: カウボーイビバップ (Japanese for Cowboy Bebop)

    Score: A numerical rating or score given to the anime, likely an average from user or critic reviews.

        Example: 8.76

    Genres: A comma-separated list of the categories or types of narrative the anime belongs to.

        Example: Action, Adventure, Comedy, Sci-Fi

    Synopsis: A brief summary or description of the anime's plot or themes.

        Example: Ad Astra, Ad astra (This specific example appears truncated or placeholder in the image, but it signifies the plot summary).

    Type: The format in which the anime was released.

        Example: TV (indicating a television series) or Movie

    Episodes: The total number of episodes released for this entry. Can be a number or a descriptive phrase.

        Example: 26 or 1 (for the movie entry)

    Aired: The date range or season during which the anime was broadcast or released.

        Example: 26 Apr 3, 1998 to 24 Apr 1999

    Premiered: The specific season and year the anime began its broadcast, particularly relevant for TV series.

        Example: Spring 1998

    Producers: The studios or companies responsible for the anime's production.

        Example: Sunrise

    Licensors: The companies responsible for distributing and licensing the anime outside of its original release region.

        Example: Funimation

    Studios: The animation studio or production house that created the animation.

        Example: Sunrise

    Source: The original material the anime was adapted from.

        Example: Original (meaning it was not based on a manga, game, etc.) or Manga

    Duration: The runtime of an episode or the entire film.

        Example: 24 min per ep or 1 hr 55 min

    Rating: The age-appropriateness rating of the content.

        Example: R - 17+ (Violence & Profanity)

    Rank: The anime's overall rank in popularity or score among all entries in the database.

        Example: 43

    Popularity: A measure of how many users have marked this anime, often related to the number of members following it. Lower number means higher popularity.

        Example: 41

    Favorites: The raw count of users who have marked the anime as a favorite.

        Example: 78325

    Scored By: The total number of users who contributed to the overall Score.

        Example: 964393

    Members: The total number of users who are members of the anime's page (e.g., watching, planning to watch, or just following).

        Example: 177225

    Image URL: A web address pointing to the primary image or thumbnail for the anime.

        Example: https://cdn.myanimelist.net/images/anime/4/19644.jpg

