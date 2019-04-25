# Real time machine learning pipelines with Kafka and Spark Streaming

## [View Live Presentation](https://axsauze.github.io/kafka-spark-real-time-ml-slides
/#/)

Topics covered:

* Intro
    * About me
    * About the institute
    * Presentation outline
* Conceptual intro
    * What is etl
    * Emphasising the breadth of ETL with all acronyms 
    * Talking about the downsides of etl
    * Introducing streaming 
    * Talk about both backends being the same from high level
    * Push for unified interface 
    * Talk about all the tools that are available for bath + streams
    * Talk about one not being better than the other, and how tools have relevant usecases
    * Talking about Machine Learning
    * Machine Learning pipelines
    * How ML pipelines are different to traditional ETL flows (and general software)
* Hands on demo
    * Introducing the challenge
    * Talking about the setup with dockercompose

## Running Presentation

You can also run the presentation on a local web server. Clone this repository and run the presentation like so:

```
npm install
grunt serve
```

The presentation can now be accessed on `localhost:8080`. Note that this web application is configured to bind to hostname `0.0.0.0`, which means that once the Grunt server is running, it will be accessible from external hosts as well (using the current host's public IP address).

