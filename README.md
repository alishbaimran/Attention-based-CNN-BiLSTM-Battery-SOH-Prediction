# Attention-based-CNN-BiLSTM-Battery-SOH-Prediction
Attention-based CNN-BiLSTM for SOH prediction of lithium-ion batteries

The state of health (SOH) and remaining useful life (RUL) of lithium-ion batteries are important aspects of a cell chemistry which describe the current aging degree of the batteries from different perspectives. To improve the effectiveness and accuracy of the batteries’ health assessment models, I've implemented a method for SOH and RUL estimation of lithium-ion batteries using convolutional neural networks (CNNs), bi-directional long short-term memory (BiLSTM), and attention mechanism (AM) to build a hybrid network model for capacity estimation of lithium-ion batteries, and calculate the SOH and RUL. 

Specifically, this project predicts the life of the Lithium Ion battery with an attention-based-CNN-BiLSTM based on the voltage, current and temperature of the charging cycles. 

Lithium ion battery data has been taken from NASA Ames Prognostics Data Repository [1]. I've also included a notebook for initial data exploration of this dataset and an SVM model for SOC prediction. 

![images_large_10 1177_17483026221130598-fig6](https://github.com/alishbaimran/Attention-based-CNN-BiLSTM-Battery-SOH-Prediction/assets/44557946/27c6170e-6723-40fa-8551-27f878d784e9)


[1] B. Saha and K. Goebel (2007). "Battery Data Set", NASA Ames Prognostics Data Repository (https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#battery), NASA Ames Research Center, Moffett Field, CA
