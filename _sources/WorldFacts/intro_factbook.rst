Introduction
============

The World Factbook provides information on the history, people, government, economy, geography, communications, transportation, military, and transnational issues for 267 world entities.  It is a rich source of information that can be combined with many data sets.  In fact you used a form of this data in the World Happiness project.  In this module we will go more in-depth and use Pandas to explore and visualize the data.


Reading List
------------

-  `One Dataset Visualized 25 Different
   Ways <https://flowingdata.com/2017/01/24/one-dataset-visualized-25-ways/>`__
   This is a great article to help you think about visualization
- `What is Exploratory Data Analysis <https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15>`_

-  `Getting Started with
   Altair <https://altair-viz.github.io/getting_started/starting.html>`__
   Read the overview and then move to the `User
   Guide <https://altair-viz.github.io/user_guide/data.html>`__ Read
   this through data transformations.
-  `A Comprehensive Guide to the Grammar of
   Graphics <https://towardsdatascience.com/a-comprehensive-guide-to-the-grammar-of-graphics-for-effective-visualization-of-multi-dimensional-1f92b4ed4149>`__
-  `Introduction to Pandas Part
   I <http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/>`__
-  `Screen Scraping
   101 <https://hackernoon.com/web-scraping-tutorial-with-python-tips-and-tricks-db070e70e071>`__
-  `Web Scraping Weather
   Forecasts <https://www.dataquest.io/blog/web-scraping-tutorial-python/>`__
-  `Beautiful Soup
   docs <https://www.crummy.com/software/BeautifulSoup/bs4/doc/>`__

As a warmup exercise and maybe to stimulate some questions for
investigation take the `Gapminder
quiz <http://forms.gapminder.org/s3/test-2018>`__

Let’s start by loading some data about countries. This data has been
compiled by combining information from files at:
http://gsociology.icaap.org/dataupload.html we are going to use it to
warm up our pandas skills. In this first part of the module we will
continue with some data that should be familair to you but we will use
it in Pandas instead of a spreadsheet. In the second part we will focus
on several different kinds of textual analysis using data from the
United Nations.

The goals for Part I of the module are:

-  Loading data into pandas
-  Using Altair to make some quick visualization of the data
-  Querying (filtering) our data
-  Sorting data
-  Adding new columns of data

Exploratory Questions to get started
------------------------------------

-  What are the minimum and maximum values of the data in each column?
-  How does the birth rate compare across countries? What is the
   distribution of the birth rates?
-  Is there are connection between the area of a country and its
   population?
-  How can we find all of the details on a specific country?
