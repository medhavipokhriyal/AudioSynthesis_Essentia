Real Time Audio Synthesis using Essentia's TensorFlow Models

TensorFlow models in Essentia are now run to perform real-time music audio annotation for the audio clips. This project aims to deploy the TensorFlow models in Essentia on Google Cloud Platform for real-time music audio annotation. Deployment is the approach that integrates a machine learning model into an existing production environment to make realistic enterprise choices primarily based totally on data. It is one of the closing ranges withinside the machine learning life cycle. Model deployment is one of the most difficult processes of gaining value from machine learning as it ensures that the model works reliably in the organization’s production environment. 

Using GCP Storage to store the TensorFlow Models as well as the list of audio clips. The audio clips & the deep learning models stored in the GCP are then transferred to Google Colab, for the real-time audio synthesis of the clips with the help of TensorFlow models. It is streamed to Essentia, an open-source library & tools for audio & music analysis, description, and synthesis. Streaming occurs in real-time to predict the music tags that can be associated with the audio. It uses a pre-trained auto-tagging model based on the MusiCNN architecture, adapted to work with small chunks of audio.


