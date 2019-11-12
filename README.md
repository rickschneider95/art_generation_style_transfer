# art_generation_style_transfer
2 goals: generate art with DCGAN and apply a style transfer

To run the art scraping python (genre-scraper.py) must do the following:
-In the same folder as genre-scraper.py create an images folder, in the images folder create a test folder
-now scrape using the genre, the style and the number of pages you want to scrape:
-python3 genre-scraper.py --genre abstract --style surrealism --num_pages 1000

This will create a folder containing all the images scraped, named abstract in the test folder created above


**CREDITS**
Source for the image generation DCGAN: https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html
Source for style transfer: https://github.com/gsurma/style_transfer

