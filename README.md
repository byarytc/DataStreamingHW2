# DataStreamingHW2
Code for Investigation of kafka throughput 

# Investigation of kafka throughput using Twitter data
To set up kafka environment, open the terminal in root folder and type docker-compose up.
This command wil spin up kafka environment, containing zookeeper and broker services. 
Topic "raw_message" will be generated wil setting up docker environment.

To cretate producer or publisher, kafka_publisher or kafka_reader modules should be used respectivelly.
