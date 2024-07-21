# Story I: Spotting cat art in the Metropolitan Museum of Art (The Met), New York

## This project is done as part of the Lede Program at Columbia University.

The story webpage is here: https://surbhi-bh.github.io/cats_of_museum_of_modern_art.html

### Data sources
Data for this project is sourced from the API of Metropolitan Museum of Art (The Met), New York. In 2020, The Met made details of over 470,000 artworks in their collection publicly accessible through an API, along with high-resolution images of the works. API documentation can be accessed here: https://metmuseum.github.io/

### API calls
After exploring the data on the artwork of the museum, I decided to look at cats and dogs that feature in the museum's art collection. Soon the list expanded to include a total of nine animals: cats, dogs, bull, rabbit, monkey, lion, dog, pig, horse and elephant. To get API results faster, I limited the scope of the project to artwork currently on display in the museum. Data from the API calls for the nine animals was saved as csvs for analysis.

### Analysis
For the analysis, I looked at four measures:
- No. of artworks featuring each of the nine animals; and the share of famous paintings in it.
- The department that is in-charge of art pieces featuring the animals.
- The medium of the art work. (For famous paintings only.)
- The country where the artwork was found or created. (For cats only.)

All analysis is done using pandas in Python. Charts are made using Flourish. The HTML page is rendered using RMarkdown.

### This directory
This directory contains the following files:
- prj-met-api-data.ipynb: The python script for fetching data using API.
- prj-met-cat-art-analysis.ipynb: The python script for data analysis.
- DATA: Directory with nine files, each for an animal, containing data on paintings featuring the animal that are currently on view.
- README.md: This file.

### Key findings
- Cats reign supreme in paintings at The Met!
- Most cat artifacts come from Egypt!

During the process, I also reached out to The Met to get a sense of the number of paintings that are on display, in general, on any given day. Had I received this number, it would have been possible to say what share of the paintings is cats. The API gives data on all paintings, but I could not estimate the total number of "OnView" paintings, and wanted to verify it with the museum records.

### Future Work
There is so much more to be explored in this dataset. I would like to look at:
- Accession years of paintings for different animals.
- Artist nationalities.

I hope to come back to this soon!