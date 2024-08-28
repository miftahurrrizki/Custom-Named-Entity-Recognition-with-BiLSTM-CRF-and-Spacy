# Named Entity Recognition using BiLSTM-CRF

This project implements a Bidirectional LSTM with Conditional Random Fields (BiLSTM-CRF) for Named Entity Recognition (NER) tasks. The model is designed to identify and classify named entities in text, such as locations and seaweed species.

![image](https://github.com/user-attachments/assets/b0f364d4-745b-4f4b-a8dd-23da59596187)
Model Architecture

------------------

![image](https://github.com/user-attachments/assets/d0cbf44f-28eb-4dea-a40a-bd990f91c534)
Model Accuracy


## Requirements

- Python 3.7+
- TensorFlow 1.15.0
- Keras 2.2.4
- keras-contrib (for CRF layer)

You can install the required packages using:

```bash
pip install tensorflow==1.15.0 keras==2.2.4
pip install git+https://www.github.com/keras-team/keras-contrib.git
