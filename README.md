# AirBNB
Udacity - Data Scientist Nanodegree [Project 01 - Write a Data Science Blog Post]

The goal of this project is writing a data science blog post on Medium. As I could choose any topic, I decided to follow the reccomendation at the project guide and use the datasets provided by Airbnb, regarding the american cities of Boston(MA) and Seattle(WA).

The full datasets are available on the Kaggle website (please find the links below):

*   [Boston Dataset](https://www.kaggle.com/airbnb/boston)
*   [Seattle Dataset](https://www.kaggle.com/airbnb/seattle/data)

I've chosen specifically the listings dataset, which is the one that describes the properties available to book, to compare both cities and find out where a guest is more likely to have a better Airbnb experience.

The criteria to this comparison is based on three questions:

*   (1) Is there a specific host profile to each city?
*   (2) Which city is cheaper for a one night booking?
*   (3) Which city has the best properties available (based on the guest reviews)?

## Instalation

There's no need to install any filles to check the code and the results at the jupyter notebook file (.ipynb)

## Libraries

I've used the following libraries available for Python in this project:

*   PanDas - open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.  [documentation](https://pandas.pydata.org/docs/)
*   Matplotlib - plotting library for the Python programming language and its numerical mathematics extension NumPy. [documentation](https://matplotlib.org/3.2.0/contents.html)
*   Seaborn - data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. [documentation](https://seaborn.pydata.org/)
*   Numpy - library consisting of multidimensional array objects and a collection of routines for processing those arrays. [documentation](https://numpy.org/doc/)
*   Locale - The locale module is part of Python's internationalization and localization support library. It provides a standard way to handle operations that may depend on the language or location of a user. For example, it handles formatting numbers as currency, comparing strings for sorting, and working with dates. [documentation](https://docs.python.org/2/library/locale.html)

## Files in the repository

*   *jupyter_notebook_image.jpg* - Airbnb logo used on the jupyter notebook's header;
*   *listings_Boston.csv* - .csv file containing the data from the Airbnb listed properties in Boston(MA);
*   *listings_Seattle.csv* - .csv file contatining the data from the Airbnb listed properties in Seattle(WA);
*   *Air_Boston_Seattle.ipynb* - Jupyter notebook containing the code and the results of the analysis;

## Summary of results

###   (1) Is there a specific host profile to each city?

*   **Number of hosts registered**

There are 2181 host registered in Boston, and 2751 in Seattle;
The ratio of [Available Listings / Host] is higher in Boston (1.64) than in Seattle (1.39), which means that there are more hosts listing more than one property in Boston;

*   **Superhosts** ([What is a Airbnb superhost?](https://www.airbnb.com/help/article/828/what-is-a-superhost))

There are more superhosts in Seattle (19.52 %) than in Boston  (11.78 %);

*   **Host response time**

Hosts normally have similar behavior regarding the response time in both cities. However, the percentage of hosts which answer within a hour is higher in Seattle (44.31 %) than in Boston (38.60 %);

*   **Response Rate**

Response rate distribution is similar to both cities, however the number of listings which have 100% response rate is higher in Seattle (62.10 %) then in Boston (57.80 %).

(Missing values percengate for this featue is quite the the same in both cities - Boston: 13.14% and Seattle: 13.69%)

*   **Acceptance Rate**

It's much more likely to have your booking accepted in Seattle than in Boston, according to the acceptance rate distribution;

*   **Verification Methods**

The verification methods used more frequently are the same for both cities: phone, email and reviews at Airbnb.

Facebook, Google +, Kba and Linkedin users are more likely to be used in Seattle, while Jumio is more common in Boston;

*   **Hosts live in the same city as the listed property?**

Is more likely to Seattle hosts to live in the same city of the listed property. 89.90% for Seattle, and 64.88 % for Boston;

*   **Cancelation Policy**

It's possible to notice that hosts in Boston have more strict cancelation policies than the ones in Seattle; 
  
###   (2) Which city is cheaper for a one night booking?

*   **Types of property**

House and Appartments are the most common type of property listed in both cities, however Boston has way more appartments, while Seattle has a ballance between houses and appartments;

Boston: Houses - 15.67% ; Appartments - 72.86%;

Seattle: Houses - 45.39% ; Appartments - 44.73%;

*   **Prices Comparison** 

Boston has higher booking prices for all the types of properties which are common to both, besides house (which is quite the same) and boat (which is quite higher in Seattle);

###   (3) Which city has the best properties available (based on the guest reviews)?

*   **Features reviewed at Airbnb**
*   Accuracy (Seattle 9.63 > Boston 9.43)
*   Cleanliness (Seattle 9.55 > Boston 9.25)
*   Check in (Seattle 9.78 > Boston 9.64)
*   Communication (Seattle 9.81 > Boston 9.64
*   Location (Seattle 9.61 > Boston 9.41)
*   Value (Seattle 9.45 > Boston 9.17)
*   General Rating (Seattle 94.54 > Boston 91.91)

Seattle has better review ratings at all the features, and also has best general reviews to all the common property types;

###  Conclusion

From a guest point of view, it's possible to say that Seattle is more likely to provide a better Airbnb experience, as we have seen that:

*   The hosts seem to be more attentions and flexible, besides the fact of being close to help out with any problems;
*   Prices for one night booking are better or the same for all the property types, but Boats;
*   Booking reviews for all the types of properties are better in Seattle;
*   All the six evaluated features have higher average values in Seattle;

## Acknowledgments

*   [Python Graph Gallery](https://python-graph-gallery.com/11-grouped-barplot/)
