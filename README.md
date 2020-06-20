# Gait Assistive aid for Parkinson patients--EdgeML Approach.
Parkinson disease patients suffer from "Freezing of Gait"(FOG)  events during daily normal activities. Medical research has shown Rhythmic auditory cueing can recover normal gait when freezing events occur. The occurence of FOG events need to be detected using sensors and this can be achieved using body worn accelerometer based systems. Thess system can be made more cheaper and scalable with implementation of low sized ML models. Microsoft India 's EgdeML models - ProtoNN and Bonsai are implemented in order to achieve system model sizes as low as 1.4KB while that of Standard ML models are at hundreds of KBs. 

# Software requirements: 
To download: 
 - EdgeML git repository from Microsoft India Research. EdgeML requirements are available in the same.
 - Daphnet Dataset from UCI ML data repository. Contains accelerometer data.

Code base is available as python notebooks. We recommend google colab notebooks.
Packages:
 - sklearn,
 - pandas,
 - numpy,
 - pickle,
 - math, 
 - os.

# Repository Description: 
  - Datapreprocessing.ipynb performs necessary window extraction and feature extraction to synthesize data for training and testing in ML algorithms.
  - ML_Models.ipynb contains research done with standard ML models listed in the paper.
  - protoNN.ipynb contains implementation of the work in low size protoNN Model.
  - Bonsai.ipynb contains implementation of the work in low size Bonsai Model.

PS: Publication will be updated after presentation at iEEE SysCon 2020
