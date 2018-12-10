## The Motivation and the Goal
Music intrinsically is a part of everyone’s everyday life, whether they’re hyper-aware of it or not
at all. It comes up in all instances, varying from sounds in the park to going straight to the
source and listening to it intentionally. It pervades throughout our daily lives and as a result, it
tends to become an important part of society. It maintains value for its cultural meaning in
addition to how it individually provides meaning to some, whether one establishes a connection
in the lyrics or within the instrumentals. However, while there are many types of music out there,
not everyone listens to the same things. There might be some music out there that nearly no
one listens to out at all. As an extension of this, we beg to answer the question, what makes
music enjoyable to listen to? What properties make certain music enjoyable by the populous
and others not as enjoyable? Is there some music that can be defined as “the best?” Can we
figure out, if given a song, what will it mean to the people before it's even heard?

In this project, we aim to find a solution to this problem. Through analyzing various attributes of
a plethora of songs, we aim to determine what makes a song “the best.” In this instance, we will
define “best” by popularity. While music is obviously subjective, we aim to see if given the
properties of a song, if we can determine how well it would fare commercially, identifying the
common traits of the tunes that are currently considered popular and comparing any song that
may be made, observing if the properties of the song matches what’s currently trending. If we
are able to do this, we might be able to utilize such information to identify song traits necessary
to create commercial successes. This data can result in a lot of potential outcomes, ranging
from using it to make our own success through creating “better” songs, to understanding what’s
musically and culturally valued in our current society.

## The Dataset
To build our dataset, we first had to create a collection of songs because there currently isn’t a
way to pull random songs from the Spotify API. In order to accomplish this, we scraped the
website songfacts.com, which has a database of every song released sorted by year. So now we
have a list of songs and their respective artist from 2008 - 2018, with 2000 songs per year for a
total of 20,000 songs.

We are then able to work with the Spotify API to gather the statistics of each of these songs. The
Spotify API, given a song, can provide a wide range of attributes about the song itself. For the
purposes of this project, we are concerned with the following: duration, acousticness,
danceability, energy, instrumentalness, liveness, loudness, speechiness, valence, tempo, and
popularity. Spotify is able to provide numeric values for each of these attributes for each song,
and with this, we plan to determine what traits are common in the most popular song and
understand what makes a song popular.

## Solution

## Testing and Training

## Results 

## Final Report

## Team Contributions and Contact Information
Justin Chen - justinchen2020@u.northwestern.edu
- Learned how to use Spotify API to write Python script to connect Spotify API with Kenneth's web scraping code
- Contributed to discussion, viability, and usage of various machine learning algorithms for this project
- Created website

Kenneth Gomez - kennethgomez2020@u.northwestern.edu 
- Wrote Python script to web scrape songs for dataset and gathered dataset in the process
- Spearheaded discussion, viability, and usage of various machine learning algorithms for this project
- Created logistics for using dataset for testing and training 

Leanna Hue - leannahue2020@u.northwestern.edu
- Wrote code to implement dataset with machine learning algorithms from Scikit-learn
- Generated graphs and final results using weka
- Contributed to discussion, viability, and usage of various machine learning algorithms for this project




## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/JustinFC/Culture-Clock/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JustinFC/Culture-Clock/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
