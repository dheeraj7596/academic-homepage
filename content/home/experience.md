+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 60  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Data Scientist"
  company = "Sprinklr"
  company_url = "https://www.sprinklr.com/"
  location = "Gurgaon, India"
  date_start = "2018-04-01"
  date_end = "2019-07-01"
  description = """
  Part of Machine Learning team:
  
  * Architected and built most of Sprinklr AI's visual insights module that is now used by over 1200 Sprinklr clients.
  * Developed in-house computer vision models for visual sentiment, gender, age, inappropriate content detection in images and videos.
  * Implementation was done using asynchronous programming and as a result, throughput was increased by 65% and total resources cost reduced by 50%.
  * Built in-house computer vision model that identifies the font and suggests similar fonts from an image.
  * Developed a dockerized auto-scaling python-based framework which is deployed in kubernetes for image classification. It works over a stream of data published to Kafka and thus is auto-scaled based on lag in Kafka queue.
  * Developed a scalable system capable of running classification models over 500 million messages per day using the latest technologies like Caffe, Tensorflow, Kafka and Elasticsearch.
  * Deployed a centralized monitoring environment(Grafana, InfluxDB) which gather system metrics as well as docker run-time metrics.
  """

[[experience]]
  title = "Product Engineer"
  company = "Sprinklr"
  company_url = "https://www.sprinklr.com/"
  location = "Gurgaon, India"
  date_start = "2017-07-01"
  date_end = "2018-04-01"
  description = """
  Part of Paid Advertising team:

  * Implemented an end to end pipeline that incorporates DoubleClick tracking in ads for integrated reporting.
  * Expanded the reach of the product by integrating Ads APIs of various social media channels like LinkedIn, Twitter, Google DCM.
  * Researched, Designed and Implemented core functionalities in backend code to improve the feature of importing and exporting ads which is the primary way, the users undergo to create ads.
  """

[[experience]]
  title = "Machine Learning Intern"
  company = "Microsoft India"
  company_url = "https://www.microsoft.com/en-in"
  location = "Bangalore, India"
  date_start = "2016-05-01"
  date_end = "2016-07-01"
  description = """
  Developed tree-based models for predicting the ideal assignment candidate for a case in Microsoft Dynamics CRM.
  """

[[experience]]
  title = "Software Development Intern"
  company = "ASnTech & Engineering Services"
  company_url = "http://www.asntech.in/"
  location = "Hyderabad, India"
  date_start = "2015-12-01"
  date_end = "2015-01-01"
  description = """
  Designed and implemented an algorithm to speed up search queries related to the location of a vehicle, from 120 seconds to 5 seconds.
  """
+++
