# NIDS-Using-CICIDS2017-Dataset

We have developed an IDS using deep learning and machine learning techniques. We will be training deep learning models like artificial neural network (ANN) and machine learning models using random forest algorithm, decision tree, KNN algorithm to compare the accuracy and recall score to find the best model. <br>
First, we will be initiating DoS attack using hping3 to target machine. These packets will be captured by packet sniffer (packetsniff.sh) which is a shell script developed using tcpdump. This shell script generates PCAP file as an output. This PCAP file will be fed into CICFlowMeter which extracts the features from the packets. The output of the application is the CSV format file that has six columns labeled for each flow (FlowID, Source IP, DestinationIP, SourcePort, DestinationPort, and Protocol) with more than 80 network traffic analysis features. This will be fed as an input to the developed ANN model which will predict whether the flow is benign or malicious flow. When malicious network flow is detected, the user will be notified.

# Contributors
* Manigandan Ramadasan : https://github.com/NotManigandan
* Prasham Titiya : https://github.com/prasham1515
* Varun Kamath : https://github.com/VarunK1505 
* Ronit Naik : https://github.com/RonitNaik9
