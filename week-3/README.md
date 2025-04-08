# Week 3

## Week Overview

We will continue talking about the Unix operating system that we started last week. Time permitting we will begin looking at web scraping through [The New York Times Developer Network](https://developer.nytimes.com) API.

So that we all are using the same environment we will use a Docker Image for the book [Data Science at the Command Line](https://www.datascienceatthecommandline.com/index.html) by Jeroen Janssens. 

First we need to pull the image using the follwing:

`docker pull datasciencetoolbox/dsatcl2e`

Then to run the image

`docker run --rm -it datasciencetoolbox/dsatcl2e`

To leave the environment simply type `exit`

Now to mount your local directory as a volume using the following commands

On a Mac:
`docker run --rm -it -v "$(pwd)":/data datasciencetoolbox/dsatcl2e`

In Windows command line
`docker run --rm -it -v "%cd%":/data datasciencetoolbox/dsatcl2e`

In Windows powershell (hasn't worked)
`docker run --rm -it -v ${PWD}:/data datasciencetoolbox/dsatcl2e`

## Resources

[Slides](https://github.com/natelangholz/stat418-tools-in-datascience-2025/blob/master/week-3/slides-week-3.pdf)

-----

This Docker Image for the Unix environment we will use as a class came from this great book

[Data Science at the Command Line](https://www.datascienceatthecommandline.com/index.html) by Jeroen Janssens.

We won't be using all the resources from this book nor going through all the chapters but I suggest doing so outside of this course. They are valuable tools that will only improve your productivity as a Data Scientist.

-----

[Interesting New York Times article](https://www.nytimes.com/interactive/2019/04/16/opinion/facial-recognition-new-york-city.html?action=click&module=Opinion&pgtype=Homepage) by Sahil Chinoy

