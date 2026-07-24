---
title: "Background"
permalink: /background/
layout: single
author_profile: false
---
Traditionally, plant diseases are checked by hand simply through visual cues that the human eye can perceive. However, there are a great number of faults related to manual observation and assessment, namely that they can be inaccurate and time-consuming. 

In order to make this process easier and more efficient, researchers are looking at machine learning as a way to quickly and effectively assess crops for a variety of types of plants. By providing hybrid quantum-classical systems with data of existing diseases, researchers hope to increase the accuracy and detail of disease detection. Specifically, quantum systems are generally stronger at analyzing patterns - given data and actual cases - compared to classical systems. In one study, the hybrid quantum-classical system was found to be 95.2% accurate, with all other deep learning systems only being about 91-93% accurate. [^1]
Studies have already taken place that utilize this technology with a wide variety of crops including [apples](https://www.researchgate.net/profile/Saurabh-Srivastava-14/publication/400349244_Hybrid_Quantum-Classical_Convolutional_Neural_Network_HQC-CNN_for_Apple_Leaf_Disease_Classification/links/6980ac5642f94d1212a5d61a/Hybrid-Quantum-Classical-Convolutional-Neural-Network-HQC-CNN-for-Apple-Leaf-Disease-Classification.pdf), [wheat](https://www.researchgate.net/publication/379357870_Application_of_quantum_computing_in_image_processing_for_recognition_of_infectious_diseases_of_wheat), and [rice](https://onlinelibrary.wiley.com/doi/10.1155/int/9911441). 

Currently researchers are using both quantum and classical systems to achieve these results. Classical computing is utilized to process data and optimize the entire system, while quantum parameterized circuits and gates are used to analyze the data. In one case, qubits are encoded with the brightness of the image pixels and processed through quantum gates (like the Hadamard gate and the CP gate) to ultimately filter out unnecessary information and reveal pertinent information.[^2] In other cases, sensory information about the environment is analyzed by quantum algorithms to determine chances for disease. [^3] Additionally, entanglement enables systems to understand interdependencies and complex or nonlinear correlations exhibited in the data which are difficult to classify with a classical view, making it easier for these systems to detect diseases when they occur. Overall, researchers have found that quantum algorithms allow for greater ease in analyzing diseases given a wide variety of data, understanding nonlinear relationships that can determine the behavior of pathogens, and even understanding diseases in crops overall using spectral signals.

![Variational quantum algorithm (VQA) architecture with classical optimization](example.png)
Example of a hybrid quantum-classical system that might be used

[![Next](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSpAMYI_Dl6lGoIbPM2UTkuf0GYQYEWJhorwEje6anPzw&s=10){:width="100px" height="100px"}](https://purplerigel-oss.github.io/Quantum-Disease-Detection/motivations/)

[^1]: Lakhani, S. (2025). Revolutionizing smart farming: Quantum computing applications in plant disease detection: A hybrid quantum-classical approach for sustainable agriculture. International Journal of Compututing Programming Database Management, 6(2), 191–231997. https://www.doi.org/10.33545/27076636.2025.v6.i2b.127 
[^2]: Mukhamedieva1, D. T. & Sobirov, R. A. (2024). Application of quantum computing in image processing for recognition of infectious diseases of wheat. BIO Web of Conferences, 95(01003), 1–9. https://doi.org/10.1051/bioconf/20249501003 
[^3]: Wu, Y., Nagy, A., Rajnai, Z., Fregan, B., & Takács- Györg, K. (2025). Quantum Machine Learning in Crop Disease Monitoring: Opportunities and Challenges to Practical Implementation. 2025 12th International Conference on Computational Cybernetics and Cyber-Medical System, 59–64. https://www.researchgate.net/profile/Yue-Wu-265/publication/391898833_Quantum_Machine_Learning_in_Crop_Disease_Monitoring_Opportunities_and_Challenges_to_Practical_Implementation/links/68e3c7ce220a341aa152facd/Quantum-Machine-Learning-in-Crop-Disease-Monitoring-Opportunities-and-Challenges-to-Practical-Implementation.pdf  

