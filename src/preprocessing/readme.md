
Please also check this folder [`intermediate_files`](../../intermediate_files) for the intermediate data files and code for data preprocessing.

## query codes
- get\_link\_info\_feature\_beijing.py: for each link, extract link info feature;
- get\_query\_distribution\_feature\_beijing\_1km\_seq.py: get query distribution feature (algorithm 1);
- get\_query\_info\_beijing.py: get query information;
- new\_anomalty1109.py: event discovery algorithm;
- query\_d.py: import the query data into the dict;
- s\_grid\_and\_d\_grid.py: import the query data into the source dict and destination dict, respectively;

## traffic codes  
- filter\_around\_link\_set\_beijing\_1km.py: filter the link set so that each link has the traffic data;
- filter\_around\_traffic\_beijing.py: filter the link with the ratio of the data completion (true, >90%; false, otherwise);
- get\_around\_traffic\_beijing\_mv\_avg\_1km.py: import the traffic data from text files, and use moving average to smooth it and dump the traffic data to pkl;
