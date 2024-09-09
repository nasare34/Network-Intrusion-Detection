# Network-Intrusion-Detection

Background
The dataset to be audited was provided which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.
For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two categories:
• Normal
• Anomalous

The performance metrics  from three different machine learning classification algorithms i used and evaluated on a dataset.
1. **K-Nearest Neighbors (KNN)**:
   - **Train Score: 98.90%** - The model achieved 98.90% accuracy on the training dataset, meaning it correctly classified 98.90% of the training samples.
   - **Test Score: 98.29%** - On the test dataset, it correctly classified 98.29% of the samples, indicating strong generalization to unseen data.

2. **Bernoulli Naive Bayes (BNB)**:
   - **Train Score: 88.51%** - The model achieved 88.51% accuracy on the training dataset.
   - **Test Score: 88.70%** - On the test dataset, it slightly improved to 88.70%, showing a good balance between training and testing performance, though overall scores are lower than KNN.

3. **Decision Tree Classifier (DTC)**:
   - **Train Score: 99.98%** - The model performed exceptionally well on the training dataset, with a near-perfect accuracy of 99.98%.
   - **Test Score: 99.36%** - It maintained a high accuracy of 99.36% on the test dataset, indicating that it generalized well to new data.

In summary, KNN and DTC show high accuracy with good generalization, while BNB performs well but at a lower accuracy rate compared to the other two models.
