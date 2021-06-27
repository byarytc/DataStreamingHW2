# DataStreamingHW2
Code for Investigation of kafka throughput 

# Investigation of kafka throughput using Twitter data
To set up Kafka environment, open the terminal in the root folder and type docker-compose up. 
This command will spin up Kafka environment, containing zookeeper and broker services.
Topic "raw_message" will be generated will setting up the docker environment.

To create producer or publisher, kafka_publisher or kafka_reader modules should be used respectively.

Folder Data contains file all_annotated.csv with Twitter dataset.
generator module contains logic to create stream of messages.
