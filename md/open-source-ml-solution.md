# Open Source Solution

## Towards Building an Intelligent Anti-Malware System: A Deep Learning Approach using Support Vector Machine for Malware Classification 
[malware-classification github](https://github.com/AFAgarap/malware-classification)

Effective and efficient mitigation of malware is a long-time endeavor in the information security community. The development of an anti-malware system that can counteract previously-unknown malware is a prolific activity that may benefit several sectors. We envision an intelligent anti-malware system that utilizes the power of deep learning (DL) models. Using such models would enable the detection of newly-released malware through mathematical generalization. That is, finding the relationship between a given malware x and its corresponding malware family y, f : x → y. To accomplish this feat, we used the Malimg dataset[12] which consists of malware images that were processed from malware binaries, and then we trained the following DL models 1 to classify each malware family: CNN-SVM[16], GRU-SVM[3], and MLP-SVM. Empirical evidence has shown that the GRU-SVM stands out among the DL models with a predictive accuracy of ≈84.92%. This stands to reason for the mentioned model had the relatively most sophisticated architecture design among the presented models. The exploration of an even more optimal DL-SVM model is the next stage towards the engineering of an intelligent anti-malware system.