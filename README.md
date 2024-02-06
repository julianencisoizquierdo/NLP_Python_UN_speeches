# Deriving Insights from UN Speeches

## Content of the project
The dataset contains all of the speeches made in the UN General Assembly between the years 1975 and 2015 (both inclusive). The goal of this project is to derive some insights from this dataset using common natural language processing techniques (tokenization, document frequency, inverse document frequency, N-grams…) and present them graphically, mostly with wordclouds. This file can be download from https://drive.google.com/file/d/16pj2NcArxciJuRMmXA_3Ny47ZBzRVcsI/view?usp=sharing

## Instructions
The information contained in the file is the following:
- The `session` number
- The `year` of the speech
- The individual country codes (in three-letter format) in `country`
- The `country_name`
- The `speaker` name
- The `position` of the speaker, that is, his/her political role (minister, president...)
- The `text`

When running the code, make sure that the filepath for the read_csv Panda function has been updated correctly.


## Explanation

The visuals presented in the project include:
- A boxplot of the length of the speeches for the 5 countries members of the UN Security Council taking the whole period (1975-2015) into account
- The evolution of the amount of countries over time
- The evolution of the average speech length over time
- A horizontal bar plot of the most frequent words
- Wordclouds for the year 2008, 2001 and 2010
- Wordclouds with bigrams for the year 2015
- The evolution of certain keywords over time
- A frequency heatmap with certain words, including their evolution over time

## Usage

To run the analysis, open the `NLP_Deriving Insigths from the UN.ipynb` notebook and execute each cell sequentially.


## Dependencies

Find the libraries used in the project below, as well as their installation code:

```
import pandas as pd
import numpy as np
import math
import re
import glob
import os
import sys
import json
import random
import pprint as pp
import textwrap
import sqlite3
import logging
import matplotlib
import spacy
import nltk
import seaborn as sns
tqdm.pandas()

from matplotlib import pyplot as plt
from tqdm.auto import tqdm
from collections import Counter
from wordcloud import WordCloud
from collections import Counter
```

## Installation
Ensure that you have Python installed on your system. If not, you can download it from [python.org](https://www.python.org/downloads/).


## Usage
You are allowed to view and fork the repository for personal use. If you have any questions or would like to discuss potential collaborations, feel free to reach out.


## Contributing
Although this project is not open-source, I welcome feedback, bug reports, and suggestions. If you encounter any issues or have ideas for improvements, feel free to send me an email to julian.enciso.izquierdo@gmail.com.


## License
This project is not open-source, and it does not come with a specific open-source license. All rights are reserved, and usage, modification, or distribution of the code is not permitted without explicit permission.

If you are interested in using or collaborating on this project, please send me an email to julian.enciso.izquierdo@gmail.com.


## Acknowledgments
This project makes use of the materials used in the Natural Language Processing class I took during my Master's. Special thanks to Franck Jaotombo for the teaching.
