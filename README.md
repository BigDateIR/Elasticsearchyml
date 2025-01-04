# Elasticsearchyml
This reppository for final result for elasticsearch and kibana without run any code:
to run it :
1.un zip 2 files elasticsearch_data.tar.gz and kibana_data.tar.gz


2.edit docker-compose.yml to volumes for elasticsearch and kibana  to make it 
for kibana  
volumes:
 - PULL PATH TO (kibana_data)file :/usr/share/kibana/data

   for elasticsearch  
volumes:
 - PULL PATH TO (elasticsearch_data)file:/usr/share/elasticsearch/data

3.make go  to file that contane (elasticsearch_data , kibana_data and docker-compose.yml) by use cd

4.then run in TERMINAL to run docker-compose -f docker-compose.yml up -d ,and i run the containers 

5.open :http://localhost:5601 to run kibana, and http://localhost:9200/ to see elasticsearch
 
          
