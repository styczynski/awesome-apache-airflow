This is a curated list of resources about [Apache Airflow](https://airflow.apache.org/) ([incubating](https://incubator.apache.org/)).  Please feel free to contribute any items that should be included.  Items are generally added at the top of each section so that more fresh items are featured more prominently.

# Vital links
* Latest release: [1.9.0-incubating](https://cwiki.apache.org/confluence/display/AIRFLOW/Announcements#Announcements-Jan2,2018)
* Official Twitter account: [Apache Airflow](https://twitter.com/ApacheAirflow)

# Airflow deployment solutions
* [Puckel's Docker Image](https://github.com/puckel/docker-airflow) - [@Puckel_](https://twitter.com/Puckel_)'s well-crafted Docker image has become the base for many Airflow installations.  It is regularly updated and closely tracks the official Apache releases.
* [kube-airflow](https://github.com/mumoshu/kube-airflow) - This repository contains both an Airflow Docker image (that appears to have been based on Puckel's work) and Kubernetes service definition.  [mumoshu](https://github.com/mumoshu)'s repository has not been recently updated, but there are numerous forks that may be based on more recent releases.
* [airflow-cookbook](https://github.com/bahchis/airflow-cookbook) Chef cookbook for deploying Airflow.
* [Running Airflow on top of Apache Mesos](http://agrajmangal.in/blog/big-data/running-airflow-on-top-of-apache-mesos/) - Blog describing how to configure [Mesos](http://mesos.apache.org/) to run all of the Airflow componenents. 

# Introductions and tutorials
* [Understanding Apache Airflow’s key concepts](https://medium.com/@dustinstansbury/understanding-apache-airflows-key-concepts-a96efed52b1a) - Part three of a series detailing [Quizlet](https://quizlet.com/)'s quest for a workflow manager, [Dustin Stansbury](https://twitter.com/corrcoef) provides a detailed overview of the key concepts Airflow offers users.
* [Apache Airflow for the confused](https://blog.capitalplanning.nyc/apache-airflow-for-the-confused-b588935669df) - This short tutorial by [Jonathan Pichot](https://twitter.com/_pichot) takes a different tack than most by using airplane and airport operations as an analogy for Airflow.

# Best practices, lessons learned and cool use cases
* [Airflow Lessons from the Data Engineering Front in Chicago](https://medium.com/stanton-ventures-insights/airflow-lessons-from-the-data-engineering-front-in-chicago-9489e6ad5c3d) - [Alison Stanton](https://twitter.com/alison985) provides a list of tips to avoid gotchas in Airflow jobs. 
* [Data’s Inferno: 7 Circles of Data Testing Hell with Airflow](https://medium.com/@ingwbaa/datas-inferno-7-circles-of-data-testing-hell-with-airflow-cef4adff58d8) - The Wholesale Banking Advanced Analytics team at ING details how they torture test their Airflow DAGs before deployment.
* [Data quality checkers](https://drivy.engineering/data-quality/) - [Antoine Augusti](https://twitter.com/AntoineAugusti) describes the framework [drivy](https://www.drivy.co.uk/) has built atop Airflow to test their datasets for completeness, consistency, timeliness, uniquess, validity and accuracy.

# Slide deck presentations
* [How I learned to time travel, or, data pipelining and scheduling with Airflow](https://www.slideshare.net/LauraLorenz4/how-i-learned-to-time-travel-or-data-pipelining-and-scheduling-with-airflow) - Comprehensive deck by [Laura Lorenz](https://twitter.com/lalorenz6) for why Airflow is necessary and how [Industry Dive](https://www.industrydive.com/) uses it.
* [Introduction to Apache Airflow - Data Day Seattle 2016](https://www.slideshare.net/r39132/introduction-to-apache-airflow-data-day-seattle-2016) - [Sid Anand](https://twitter.com/r39132) gives a thorough introduction to Airflow and how it was used at [Agari](https://www.agari.com/).

# Libraries, Hooks, Utilities
* [fileflow](https://github.com/industrydive/fileflow) - Collection of modules to support large data transfers between Airflow operators through either local file system or S3.  This addresses a gap where data is too large for XCOMs but too small or inconvenient for loading directly in the operator.  Built by [Industry Dive](https://www.industrydive.com/).

# Meetups
* [Bay Area Apache Airflow Meetup](https://www.meetup.com/Bay-Area-Apache-Airflow-Incubating-Meetup)