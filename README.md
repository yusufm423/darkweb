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
In this project, we present a novel approach of leveraging graph-based representations. Feature matrices and adjacency matrices are derived from network flow data of CIC‑Darknet‑2020 dataset, where pairwise cosine similarity is used to construct the adjacency matrix, enabling effective graph construction. Our technique achieves an accuracy of 98.6% on this classification task, distinguishing between benign and darknet traffic with high precision.
