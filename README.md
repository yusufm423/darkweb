# Dark Web Traffic Detection and Characterization system 

## Abstract
Network traffic detection is closely associated with network security which makes it a hot
research topic. With the development of encryption technology, many crimes have occurred
on the dark web due to the fact that traffic from such networks is becoming more difficult to
filter out. Nowadays adversaries are working on multi-layer encryption strategies in
dark-web. For example, instead of just using Tor, they are using VPN and Tor together which
make it more complicated and difficult to monitor and detect. So, classifying traffic flows
according to the applications that generate them like VoIP, Audio Streaming, P2P,
File-Transfer and Video Streaming is an important task for monitoring the trends of the
applications in multilayer network communications. However, an accurate method that can
reliably identify the generating application of flow is still to be developed. Most of the
existing techniques are based on machine learning classifiers but there are less efforts made
to detect and characterize darknet traffic using deep learning.
The objective of this project is to classify data into 8 different constituents of Darknet using
various machine learning (ML) algorithms, including Decision Tree, K-Nearest Neighbors
(KNN), Random Forest Classifier, Gradient Boosting Machine (GBM), and LightGBM. The
classification is based on parameters such as source and destination IP, flow ID, and packet
information. To improve classification accuracy, a novel ensemble model is proposed that
combines different algorithms using voting techniques. Feature extraction is performed to
identify the most useful and correlated parameters out of the 85 available. The performance
of each classifier and the proposed model is evaluated using baseline classification, 10-fold
cross-validation, and hyperparameter tuning. The evaluation measures used are accuracy,
precision, recall, and F1 score. The proposed ensemble model is compared to existing
state-of-the-art models and other classifiers
