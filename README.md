# Classification of Gas Hazard Level
The presence of hazardous gases can pose a serious hazard to humans. The gas is important to be able to classify the level of danger in order to take appropriate precautions. One type of dangerous gas that can appear is the leakage of **liquid petroleum gas (LPG)**, which can experience the formation of toxic gas carbon monoxide (CO). This study designed a simple electronic nose device for gas detection using an Arduino Nano microcontroller and gas sensors, such as the **MQ2, MQ6, MQ7, and MQ9 sensors**. The design of this electronic nose device is used to classify the danger level of LPG gas leaks using the **variant recurrent neural network (RNN)** method, namely **long short-term memory (LSTM)** and **gated recurrent unit (GRU)**, as well as a combination of variants of recurrent neural network (RNN) with a **convolutional neural network (CNN)**. This study also compares the classification results with several popular classification methods, such as **multi- layer percetron (MLP)** and **support vector machine (SVM)**. The research resulted in the design of a simple electronic nose device, and the classification results showed that the proposed method achieves different performance values and gives better values than popular classification methods, such as MLP and SVM. Of the five proposed model designs, the lowest performance is owned by the RNN variant method, namely LSTM with an accuracy value of 97.680557%, while the highest performance is owned by the combination method of CNN with LSTM and GRU with an accuracy value of 98.180556%.

## Target Data

Indeks standar pencemaran udara (ISPU) is determined by converting the measured air pollution levels into a dimensionless number. The range of index values ​​determined by ISPU

| Range     |  Category     |     Explanation      |
| :-------: |:-------------:|:--------------------:|
|   1-50    | Good          |  Very good air quality level, does not have negative effects on humans, animals and plants |
|   51-100  | Moderate      | Air quality level is still acceptable for human, animal and plant health | 
|   101-200 | Unhealthy     | Air quality level that is detrimental to humans, animals and plants | 
|   201-300 | Very Unhealthy| Air quality level that can increase health risks in some segments of the exposed population |
|   301+    | Hazardous     | Air quality level that can cause serious health damage to the population and requires immediate action |

The above values ​​are used to determine data categories.