# Waste Power
## A Circular Economy Platform

The Objective of the project is to enable and facilitate contact between industries so that the waste from one can be used as raw materials in another.

Here you can create posts with information on what materials you want to be disposed of or which materials you are interested in getting.

Then any user is able to search and filter by what they are interested in and make contact with the corresponding companies.


> **Note:** Along with the platform we also built and deployed an API with FastAPI which is deployed [here](https://z5kmfo.deta.dev/docs).


Video link https://youtu.be/cD0Xwhzlqao


Many industries generate waste in the course of their activities, often ending up having to pay collection services for it, which then ends up in landfills.

In a study carried out in 2000 by across the globe, it was estimated that in 2015 there would be around 29 million tons of industrial waste generated that year, of which around 500 thousand tons would be from the textile and footwear industries.

The value proposition of this project is to enable and facilitate contact between industries so that the waste from one can be used as raw materials in another

As a solution, we propose to develop a circular economy platform that will enable and facilitate contact between companies of different industries.

Each company would create posts on the platform with information on what materials they want to be disposed of or which materials they are interested in getting, and any user would be able to search and filter by what they were interested in (think of a marketplace).

Another interesting feature would be to have a recommender system, i.e., recommend a company that has some material being wasted to another company that needs it. This would also be filtered by company/material/geographic location/…

Please find out more information about this project in the PDF document in Assets.

Final results:

We created a circular economy platform, usingWordpress.

This platform works like a marketplace where companies can post ads with materials they have available to sell or donate and also post what they are looking for.

The ads can then be filtered by many different parameters so that it is easier for the user to find what they are looking for. From the ads it is possible to send messages, allowing the user to get in contact with the company that posted the ad.

We also wanted to add a recommendations page where the user can look for companies that aren’t in the platform but might be aligned with their interests. To do that we scraped information about several companies, including address, type of materials used, url, etc. We then developed an API, using FastAPI, that returns this information based on certain filters.

Our next steps are to connect the API to the wordpress platform, so that it is user friendly. We also want to contact some companies to test the value and usability of the platform.
