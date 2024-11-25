---
date: '2022-09-01T22:36:31-05:00' # date in which the content is created - defaults to "today"
title: 'Zuva'
draft: false # set to "true" if you want to hide the content
jobTitle: "Staff Software Developer" # job description/title. Fill-in
company: "Zuva" # name of the company you worked for. Fill-in
location: "Remote, ON, Canada" # place/city/country for the experience. Fill-in.
duration: "2022-2023" # from-to, for example "2022-2024". Fill-in.

## For the content, you can use a title and a job description.
## For example:
# ### Fixing the world, one byte at a time
# The beginning of a great career.
#
---
In this role I expanded on the work myself and our team had performed at Kira and ultimately released the
[DocAI product](https://zuva.ai/api/). This was effectively an API wrapper and orchestration layer around
a series of machine learning models which extracted information from legal contracts. Most of my time was
spent tracking down issues that customers were experiencing due to the scale and size of their requests.

Customers would upload large documents (generally in PDF or DOCX format) via the API and then we used [KNative](https://knative.dev) to orchestrate
those requests through the system, first converting them into a useful format and then instantiating the
appropriate machine learning models to extract data from them, and then return those results to the user
in an asynchronous fashion.

Using knative here was definitely a learning curve, and it was also the first time I had used Azure in earnest
as well, having only seen it used by customers at MongoDB but hadn't gotten my hands dirty with it.

In the latter part of my time at Zuva I also came to line manage my team as well as manage the project
technically.
