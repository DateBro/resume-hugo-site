+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

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
  title = "Software Developement Engineer"
  company = "Beijing Sankuai Online Technology Co., Ltd."
  company_url = "https://about.meituan.com/home"
  location = "Beijing, China"
  date_start = "2021-07-11"
  date_end = "2022-07-29"
  description = """
  — **Development of marketing and customer management services for offline acquring.**
  - Implemented a marketing service with Spring Cloud and Thrift as the back-end of Meituan wechat-mini program, accmulating over **600,000** post-payment reviews and favorites for a total of **10,000** merchants.
  - Built an ElasticSearch cluster, and integrated ElasticSearch into the customer management system to facilitate merchants to get the statistics of reviews and favorites, acceleratting **70%** for each request.
  - Constructed an Unit Test SDK based on JUnit5 and Mockito, reducing the working hour ratio of R&D to Unit Test from **1:2.5** to **1:1**, and increasing the average branch coverage of **30+** services from **40%** to **80%**.
  - Assisted Software Testing Engineers to create and maintain CI/CD pipeline to replace manual way of build- deployment by Kubernetes and Jenkins, resulting in **4X** reduction of average deployment and testing time.
  """

[[experience]]
  title = "Research Assistant"
  company = "Human Computer Interaction and Virtual Reality Lab"
  company_url = "http://vr.sdu.edu.cn/index.htm"
  location = "Jinan, China"
  date_start = "2020-09-01"
  date_end = "2021-05-13"
  description = """
  — **Development of Online Judge system to automatically grade students' homework for the Algorithms course.**
  - Developed an Online Judge system to automatically grade students' homework for the Algorithms course and produce charts of scores for professors, which saved their time spent on grading homework by an average of **80%**.
  - Reduced the latency by **30%** when editing code snippets by utilizing a Redis cache layer for frequently-used contents. 
  - Dockerized all services and deployed the system in the cluster to secure stability and serve **396** students **24/7**.
  - Wrote a detailed documentation of **40+** pages about environment installation and setup, system usage guide, back-end APIs, and system designs for a team of **8** people.
  """
+++
