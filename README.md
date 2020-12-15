# JavaScript, Bootstrap, and UFOs
## Overview of Project
> Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape. 

1. ***Deliverable 1***: Filter UFO sightings on multiple criteria
2. ***Deliverable 2***: A written report on the UFO analysis [`README.md`](https://github.com/emmanuelmartinezs/UFOs). 

## Resources and Before Start Notes:

* Data Source: `ufo_starterCode.js` and `index.html`
* Data Tools: ECMAScript, JavaScript, Jupyter Notebook, Python and MongoDB
* Software: ES6+, ECMAScript, MongoDB, Python 3.8.3, Visual Studio Code 1.50.0

For more information, read the [`Documentation on MongoDB and other data typess`](https://docs.mongodb.com/). 

## Overview of ES6+
ECMAScript, also referred to as "ES," is a scripting language designed to help standardize JavaScript. This means that ES provides guidelines and rules for JavaScript to follow, such as how a function should be created to run correctly, also known as the **proper syntax**.

Because ES has provided standardization for JavaScript, it also brings updates to the language. There are updates to every major coding language that fix bugs, update code, and provide overall quality of life improvements for the developers. ES6 is no exception!

There have been many updates to ES over the years, though the sixth update was a major one. You'll probably see "ES6+" mentioned out in the wild pretty often; this is a reference to the "big" update (ES6) as well as the later ones. It's also commonly known as "ES2015" or "ECMAScript 2015." (It was such an important update that it's even known by its year!) There are quite a few different ways to reference this language, but we'll be referring to it as ES6, JavaScript, or JS in this project.

## Benefits of the ES6 Update
We've briefly mentioned that the ES6 update was useful, but let's talk a bit more about why it was such a big deal.

Imagine two laptops, one old and one new, side by side. They're similar enough: they're close in size and shape and can complete many of the same tasks, but the newer laptop has an edge. It is faster and can perform tasks with greater efficiency than the older model.

JavaScript after the ES6 update is like the newer computer. This update included many updates to the syntax, which streamlined the code and made it easier to both read and write. Additional, quality of life improvements were implemented as well, such as adding Python-like generators and `for...of` loops. Even functions were updated and streamlined!

### NOTE:
> `for...of` loops is a new syntax associated with JavaScript, so it's okay to not be familiar with it yet! We'll discuss this syntax in more detail as we learn more about the language.

Later editions of ECMAScript brought about new additions as well, but they are for more advanced uses of the language. In this module, our focus will be on basic JavaScript and ES6 capabilities such as arrow functions. Both are still used today, and there's a chance you'll come up against older versions of JavaScript during interviews as well.


## Deliverable 1:  Filter UFO sightings on multiple criteria
### Deliverable Requirements:
Using JavaScript and HTML, you’ll modify the code in your `index.html` file to create more table filters. In addition to the date filter you created in this module, you’ll add filters for the city, state, country, and shape, as shown in the following image:

![name-of-you-image](https://github.com/emmanuelmartinezs/UFOs/blob/main/Resources/Images/s1.png?raw=true)

Using JavaScript, you’ll replace the handleClick() function in your app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".


1. The list element that creates the button is removed, and there are five list elements for filtering in the `index.html` file. 
2. The event listener is modified to detect changes to each filter in the `app.js` file.
3. ​The `updateFilters()` function saves the element, value, and the id of the filter that was changed.
4. The filterTable() function loops through all of the filters and keeps any data that matches the filter values.
5. The webpage filters the table correctly based on user input.

 
### Results with detail analysis:

1. **The list element that creates the button is removed, and there are five list elements for filtering in the `index.html` file.**


> Image with `JavaScript`, `MongoDB` & `HTML` Code below.

**Code and Image**


````python
# Mission to Mars (Module Code)
# by Emmanuel Martinez

# Import Splinter and BeautifulSoup
import pandas as pd
from splinter import Browser
from bs4 import BeautifulSoup as soup
from webdriver_manager.chrome import ChromeDriverManager
````

![name-of-you-image](https://github.com/emmanuelmartinezs/Mission-to-Mars/blob/main/Resources/Images/1.1.JPG?raw=true)



2. **The event listener is modified to detect changes to each filter in the `app.js` file.**


> Image with `JavaScript`, `MongoDB` & `HTML` Code below.

**Code and Image**


````python
# Mission to Mars (Module Code)
# by Emmanuel Martinez

# Import Splinter and BeautifulSoup
import pandas as pd
from splinter import Browser
from bs4 import BeautifulSoup as soup
from webdriver_manager.chrome import ChromeDriverManager
````

![name-of-you-image](https://github.com/emmanuelmartinezs/Mission-to-Mars/blob/main/Resources/Images/1.1.JPG?raw=true)



3. ​**The `updateFilters()` function saves the element, value, and the id of the filter that was changed.**


> Image with `JavaScript`, `MongoDB` & `HTML` Code below.

**Code and Image**


````python
# Mission to Mars (Module Code)
# by Emmanuel Martinez

# Import Splinter and BeautifulSoup
import pandas as pd
from splinter import Browser
from bs4 import BeautifulSoup as soup
from webdriver_manager.chrome import ChromeDriverManager
````

![name-of-you-image](https://github.com/emmanuelmartinezs/Mission-to-Mars/blob/main/Resources/Images/1.1.JPG?raw=true)



4. **The `filterTable()` function loops through all of the filters and keeps any data that matches the filter values.**


> Image with `JavaScript`, `MongoDB` & `HTML` Code below.

**Code and Image**


````python
# Mission to Mars (Module Code)
# by Emmanuel Martinez

# Import Splinter and BeautifulSoup
import pandas as pd
from splinter import Browser
from bs4 import BeautifulSoup as soup
from webdriver_manager.chrome import ChromeDriverManager
````

![name-of-you-image](https://github.com/emmanuelmartinezs/Mission-to-Mars/blob/main/Resources/Images/1.1.JPG?raw=true)



5. **The webpage filters the table correctly based on user input.**


> Image with `JavaScript`, `MongoDB` & `HTML` Code below.

**Code and Image**


````python
# Mission to Mars (Module Code)
# by Emmanuel Martinez

# Import Splinter and BeautifulSoup
import pandas as pd
from splinter import Browser
from bs4 import BeautifulSoup as soup
from webdriver_manager.chrome import ChromeDriverManager
````

![name-of-you-image](https://github.com/emmanuelmartinezs/Mission-to-Mars/blob/main/Resources/Images/1.1.JPG?raw=true)



## Deliverable 2: A written report on the UFO analysis
### Deliverable Requirements:
For your written analysis, be sure to use complete and coherent sentences. Your written analysis should contain three sections, which cover the following:

1. **Overview of Project:** Explain the purpose of this analysis. 
2. **Results:** Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
3. **​Summary:** In a summary statement, describe one drawback of this new design and two recommendations for further development.


 
### Results with detail analysis:


1. **Overview of Project:** Explain the purpose of this analysis. 


> Image with `Python`, `MongoDB` & `HTML` Code below.

**Code and Image**


````python
## MISSION TO MARS CHALLENGE
## By Emmanuel Martinez 

# Import Flask, PyMongo, and scraping.py 
from flask import Flask, render_template
from flask_pymongo import PyMongo
import scraping

````

![name-of-you-image](https://github.com/emmanuelmartinezs/Mission-to-Mars/blob/main/Resources/Images/2.1.JPG?raw=true)



2. **Results:** Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.


> Image with `Python`, `MongoDB` & `HTML` Code below.

**Code and Image**


````python
## MISSION TO MARS CHALLENGE
## By Emmanuel Martinez 

# Import Flask, PyMongo, and scraping.py 
from flask import Flask, render_template
from flask_pymongo import PyMongo
import scraping


````

![name-of-you-image](https://github.com/emmanuelmartinezs/Mission-to-Mars/blob/main/Resources/Images/2.2.JPG?raw=true)



3. ​**​Summary:** In a summary statement, describe one drawback of this new design and two recommendations for further development.


> Image with `Python`, `MongoDB` & `HTML` Code below.

**Code and Image**


````html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Mission to Mars</title>
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
````


##### JavaScript, Bootstrap, and UFOs Analysis Completed by Emmanuel Martinez
