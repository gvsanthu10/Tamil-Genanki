# Genanki for tamil

This Juputer notebook is a modified version of [jm-moreau](https://github.com/jm-moreau) French Anki card creation notebook. Link to his depository:  (https://github.com/jm-moreau/french-genanki-jupyter)
The notebook uses 1000 most common Tamil words web-scraped on a website. Used googletrans python package for translation and IPA, gTTS python package for the creation of pronunciation and finally pixbay for images. The images may not be relavant.

## Steps
1. Webscrape tamil words (top 500 words, or nouns or any list)\
2. Get english translation along with IPA(pronunciation)\
3. Stroring the data as pandas dataframe
4. Get relavant images with Pixabay API. some images might be silly as most of the words are non-specific. For example: as, that, this
5. Using gTTS, get pronunciation mp3 files.
6. Store the file locations in dataframe columns
7. Creating Genanki model -> note -> Deck and finally saving it.

## Instructions
1. Get Pixabay API key from [Pixabay](https://pixabay.com/api/docs/)
2. You may have you tweak the webscraping code if you are using different webistes

  
