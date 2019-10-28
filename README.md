<div align="center">
  <img src="https://github.com/CODAIT/max-central-repo/raw/master/images/title.png">
</div>


#

##  :exclamation: We are Open Source and We Welcome Contributions  :exclamation:

Our mission at [CODAIT](http://codait.org) is to democratize AI, to make AI technologies accessible to practitioners who understand real-world problems and enable them to develop AI solutions that solve these problems.

The core technologies behind today’s AI systems rely heavily on open-source software projects. Going from raw data to training data to models to solutions requires many open technologies, and it’s crucial that these technologies not only work well, but work well together. Our developers and data scientists are continually improving these frameworks with our targeted open source contributions, making them work better both individually and as an integrated pipeline. Hence our name — the Center for Open-Source Data and AI Technologies.

Subscribe to our newsletters to keep updated with the recent announcements [here](https://developer.ibm.com/newsletters/).

# Model Asset Exchange

The Model Asset Exchange on IBM Developer is a place for developers to find and use free, open source, state-of-the-art deep learning models for common application domains.
The curated list includes deployable models that you can run as a microservice locally or in the cloud on contanerization platforms like Docker, Kubernetes or OpenShift, and trainable models where you can use your own data to train the models.

Models are licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

Domains covered: Text, Vision, Audio, and Time-Series. 

Models can be consumed via:
 
1. Any [programming language](https://github.com/IBM/MAX-Object-Detector/blob/master/demo.ipynb)
2. [WebApp](https://developer.ibm.com/patterns/create-a-web-app-to-interact-with-objects-detected-using-machine-learning/)
3. [NodeRed Flow](http://ibm.biz/max-for-node-red)
4. [Serverless App](https://developer.ibm.com/tutorials/deploy-a-model-asset-exchange-microservice-on-red-hat-openshift/)
5. [CodePen](https://codepen.io/)

# Contributing to the Model Asset Exchange

We welcome anyone who wants to make contributions to the Model Asset Exchange. Please review the [contribution guidelines](contribution.md). This project adheres to code of conduct mentioned [here](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.

For those who want to contribute a model to MAX, here is a quick summary of the process:
1. To contribute code, documentation, or tests, please submit a pull request using the [template](PULL_REQUEST_TEMPLATE.md) to this GitHub repository. 
2. Our [maintainers](MAINTAINERS.md) will review your proposal.
3. If approved, wrap the model using the [MAX-Skeleton as a guide](https://github.com/IBM/MAX-Skeleton).

We use Github Pull Requests for tracking requests and bugs, please direct any questions to [our Slack channel](https://model-asset-exchange.slack.com/join/shared_invite/enQtNDQ4OTQxODUyMTYwLTI1NzgyMTRlNWE4ZGE3NmQ5ZjJhYjEwZjA3ZmY4NWViN2MxMWJiZjg0NzM1MTNiZGYwYmQ0MjQ2Mzk3YzI1Yjc).

# Model Information

1. [Deployable Models](#deployable-models)
2. [Deployable and Trainable Models](#deployable-and-trainable-models)

## Deployable Models

| Domain | Model                                 | Framework  | Dataset | Application | Model Consumption |
| ----   | --------------------------------------| ---------- | ------- | ----------- | ----------------- |
| Audio  | [Audio Classifier](https://developer.ibm.com/exchanges/models/all/max-audio-classifier/)| Keras/TensorFlow | [Google AudioSet](https://research.google.com/audioset/) | Classification | <p> [Demo](https://developer.ibm.com/patterns/train-and-evaluate-an-audio-classifier-using-keras-and-jupyter-notebook/) <br> [Node-RED](https://flows.nodered.org/flow/eaef0871ea62242d32f370d9352ee4ca) <br> [CodePen](https://codepen.io/collection/DzdpJM/)|
| Audio  | [Audio Embedding Generator](https://developer.ibm.com/exchanges/models/all/max-audio-embedding-generator/)| TensorFlow | [Google Audio Dataset](https://research.google.com/audioset/) | Embeddings ||
| Audio  | [Audio Sample Generator](https://developer.ibm.com/exchanges/models/all/max-audio-sample-generator/)| TensorFlow | [Speech Commands](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data) and [FMA](http://freemusicarchive.org/) |Audio Modeling ||
| Audio  | [Speech to Text Converter](https://developer.ibm.com/exchanges/models/all/max-speech-to-text-converter/)| TensorFlow | [Mozilla Common Voice](https://voice.mozilla.org/en) | Speech Recognition ||
| NLP    | [Text Summarizer](https://developer.ibm.com/exchanges/models/all/max-text-summarizer/)| TensorFlow | [CNN / Daily Mail](https://github.com/JafferWilson/Process-Data-of-CNN-DailyMail) | Text Summarization||
| NLP    | [Toxic Comment Classifier](https://developer.ibm.com/exchanges/models/all/max-toxic-comment-classifier/)| PyTorch | [Kaggle Toxic Comment Classification dataset](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data) | Text Classification ||
| NLP    | [Chinese Phonetic Similarity Estimator](https://developer.ibm.com/exchanges/models/all/max-chinese-phonetic-similarity-estimator/)| Python || Text Clustering/Phonetics ||
| NLP    | [News Text Generator](https://developer.ibm.com/exchanges/models/all/max-news-text-generator/)| TensorFlow | [One Billion Word Benchmark Dataset](http://www.statmt.org/lm-benchmark/) | Language Modeling ||
| NLP    | [Review Text Generator](https://developer.ibm.com/exchanges/models/all/max-review-text-generator/) | Keras | [Kaggle Yelp Reviews Dataset](https://www.kaggle.com/c/yelp-recruiting/data) | Language Modeling ||
| Vision | [Breast Cancer Mitosis Detector](https://developer.ibm.com/exchanges/models/all/max-breast-cancer-mitosis-detector/)| Keras | [TUPAC16](http://tupac.tue-image.nl/node/3) | Image Classification ||
| Vision | [Fast Neural Style Transfer](https://developer.ibm.com/exchanges/models/all/max-fast-neural-style-transfer/)| PyTorch | [COCO 2014](http://mscoco.org/dataset/#download) | Style Transfer ||
| Vision | [Human Pose Estimator](https://developer.ibm.com/exchanges/models/all/max-human-pose-estimator/)| TensorFlow | [COCO](http://cocodataset.org/)| Human Pose Estimation |<p> [Demo](https://developer.ibm.com/patterns/making-music-with-the-max-human-pose-estimator-and-tensorflowjs/) <br> [WebApp](https://ibm.github.io/max-human-pose-estimator-tfjs/) <br> [Node-RED](https://flows.nodered.org/flow/1ef026c41e36a6f2fcca1ec2de342678) <br> [CodePen](https://codepen.io/collection/DzdpJM/)|
| Vision | [Image Caption Generator](https://developer.ibm.com/exchanges/models/all/max-image-caption-generator/)| TensorFlow | [COCO](http://mscoco.org/) | Image Caption Generator | <p> [Demo](https://developer.ibm.com/patterns/create-a-web-app-to-interact-with-machine-learning-generated-image-captions/) <br> [WebApp](http://max-image-caption-generator-web-app.mybluemix.net/?_ga=2.142126706.134192302.1567630407-1923667995.1567630407) <br> [Node-RED](https://flows.nodered.org/flow/ab4de9fdc1e2f63e472ada8976b422b7) <br> [CodePen](https://codepen.io/collection/DzdpJM/)|
| Vision | [Image Colorizer](https://developer.ibm.com/exchanges/models/all/max-image-colorizer/)| TensorFlow | [COCO](http://mscoco.org/) | Image Coloring ||
| Vision | [Image Resolution Enhancer](https://developer.ibm.com/exchanges/models/all/max-image-resolution-enhancer/)| TensorFlow | [OpenImages v4](https://storage.googleapis.com/openimages/web/index.html)|Super-Resolution ||
| Vision | [Inception-ResNet-v2](https://developer.ibm.com/exchanges/models/all/max-inception-resnet-v2/)| Keras | [ImageNet](http://www.image-net.org/)| Image Classification | [Node-RED](https://flows.nodered.org/flow/8e6fbc1ad88a156c040aa0f96031f04a)|
| Vision | [Nucleus Segmenter](https://developer.ibm.com/exchanges/models/all/max-nucleus-segmenter/)| Keras | [2018 Data Science Bowl](https://data.broadinstitute.org/bbbc/BBBC038/) | Object Detection ||
| Vision | [Scene Classifier](https://developer.ibm.com/exchanges/models/all/max-scene-classifier/)| PyTorch | [Places365](http://places2.csail.mit.edu/download.html) | Image Classification | [Node-RED](https://flows.nodered.org/flow/196917d2af313396a0bf3c737c9d2d5b) |
| Vision | [Sports Video Classifier](https://developer.ibm.com/exchanges/models/all/max-sports-video-classifier/)| TensorFlow | [Sports-1M](https://cs.stanford.edu/people/karpathy/deepvideo/) | Video Classification ||
| Time-Series| [Weather Forecaster](https://developer.ibm.com/exchanges/models/all/max-weather-forecaster/)| TensorFlow/Keras | [JFK Airport Weather Data, NOAA](https://www.ncdc.noaa.gov/cdo-web/datasets/LCD/stations/WBAN:94789/detail) | Weather Prediction ||


## Deployable and Trainable Models

| Domain | Model                                 | Framework  | Training Dataset for Deployable Model| Application | Model Consumption |
| ----   | --------------------------------------| ---------- | ------- | ----------- | ----------------- |
| NLP    | [Text Sentiment Classifier](https://developer.ibm.com/exchanges/models/all/max-text-sentiment-classifier/)| TensorFlow | [IBM Claim Stance Dataset](http://www.research.ibm.com/haifa/dept/vst/debating_data.shtml?_ga=2.71410259.134192302.1567630407-1923667995.1567630407) | Sentiment Analysis ||
| NLP    | [Named Entity Tagger](https://developer.ibm.com/exchanges/models/all/max-named-entity-tagger/)| Keras | [Groningen Meaning Bank (GMB) Dataset](http://gmb.let.rug.nl/data.php) | Named Entity Recognition ||
| NLP    | [Question Answering](https://developer.ibm.com/exchanges/models/all/max-question-answering/) | TensorFlow | [SQuAD 1.1 Dataset](https://rajpurkar.github.io/SQuAD-explorer/) | Question and Answer ||
| NLP    | [Word Embedding Generator](https://developer.ibm.com/exchanges/models/all/max-word-embedding-generator/)| TensorFlow | Random Text | Word Embeddings |
| Vision | [Object Detector](https://developer.ibm.com/exchanges/models/all/max-object-detector/)| TensorFlow | [COCO](http://mscoco.org/) | Object Detection | <p> [WebApp](http://max-object-detector.max.us-south.containers.appdomain.cloud/app/) <br> [Node-RED](https://flows.nodered.org/flow/33d3214c1f5774009ffbc983c96f1594) <br> [CodePen](https://codepen.io/collection/DzdpJM/)|
| Vision | [ResNet-50](https://developer.ibm.com/exchanges/models/all/max-resnet-50/)| Keras | [ImageNet](http://www.image-net.org/) | Image Classification ||
| Vision | [Image Segmenter](https://developer.ibm.com/exchanges/models/all/max-image-segmenter/)| TensorFlow | [VOC2012 ~10k images](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/) | Semantic image segmentation | <p> [Demo](https://developer.ibm.com/patterns/max-image-segmenter-magic-cropping-tool-web-app/) <br> [WebApp](https://codait.github.io/max-photo-booth/) <br> [Node-RED](https://flows.nodered.org/flow/d905e599add7f49cb71890df78b458d7) <br> [CodePen](https://codepen.io/collection/DzdpJM/) |


## General resources

- Check the current status for the [Model Asset Exchange](https://developer.ibm.com/exchanges/models/) ecosystem [here](http://ibm.biz/max-status).

- MAX Framework: Python package that contains common code shared across all MAX models - ([link](https://github.com/IBM/MAX-Framework))

- MAX Skeleton: Docker based deployment skeleton for deep learning models on the Model Asset Exchange - ([link](https://github.com/IBM/MAX-Skeleton))

## Tutorials

1. [Get started with the Model Asset Exchange](https://developer.ibm.com/tutorials/getting-started-with-the-ibm-code-model-asset-exchange/)
2. [Use Node-RED Node Generator to create new nodes from APIs and services](https://developer.ibm.com/tutorials/use-node-red-node-generator-to-create-new-nodes-from-apis-and-services/)
3. [Leverage deep learning in your Node-RED flows](https://developer.ibm.com/tutorials/learn-how-to-leverage-deep-learning-in-your-node-red-flows/)
4. [Deploy MAX models to the cloud with Kubernetes](https://developer.ibm.com/tutorials/deploy-max-models-to-ibm-cloud-with-kubernetes/)

## Blogs

1. [Get an introduction to the Model Asset Exchange on IBM Developer](https://developer.ibm.com/articles/introduction-to-the-model-asset-exchange-on-ibm-developer/)
2. [Open source and AI at IBM](https://developer.ibm.com/blogs/open-source-ibm-and-ai/)
3. [Expanding the reach of the IBM Model Asset eXchange](https://developer.ibm.com/blogs/announcing-a-new-batch-of-model-asset-exchange-models/)
4. [Real-time video annotation with deep learning model](https://developer.ibm.com/blogs/real-time-video-annotation-with-deep-learning-model/)
5. [An introduction to the internals of the Model Asset eXchange](https://developer.ibm.com/blogs/an-introduction-to-the-internals-of-model-asset-exchange/)
6. [Where are my new models for NLP? They’re here!](https://developer.ibm.com/blogs/max-models-for-natural-language-processing)

## Slides and Video Recordings

### Slides

1. [Slide - Ready to use Deep Learning Models: All You Need is 5 Minutes (Gabriela de Queiroz)](https://speakerdeck.com/kroz/ready-to-use-deep-learning-models-all-you-need-is-5-minutes)

2. [Slide - Demystifying Data Science (Gabriela de Queiroz)](http://bit.ly/dl-for-all)

### Videos

1. [Video - Image Cropping Web App (Nick Kasten)](https://www.youtube.com/watch?v=Kxnzpbl0YEQ) (based on the [demp application](https://developer.ibm.com/patterns/max-image-segmenter-magic-cropping-tool-web-app/) code pattern)

   *About* : Use a free, open-source deep learning model to detect different types of objects in an image, then interact with them in a drag-and-drop web application.
   
2. [Video - Object Detector Web App demo (Alex Bozarth)](https://www.youtube.com/watch?v=Hs6sVWmfVFw)

   *About* : The IBM Model Asset eXchange (MAX) has given application developers without data science experience easy access to prebuilt machine learning models. 
   This web app uses the Object Detector from MAX and creates a simple web UI that displays bounding boxes around detected objects in an image and lets you filter 
   the objects based on their label and probable accuracy given by the model.

3. [Video - Lighting Talk: IBM Code Model Asset Exchange (Brendan Dwyer)](https://youtu.be/4MFgJNDPGjU)

   *About*: This talk walks you through the process of building Model Asset Exchange

4. [Video - Bringing an AI Ecosystem to the Domain Expert and Enterprise AI Developer (Frederick Reiss & Vijay Bommireddipalli)](https://youtu.be/mNLl9E5p-xE)

   *About* : In this talk, we’ll break down the challenges a domain expert faces today in applying AI to real-world problems. 
   We’ll talk about the challenges that a domain expert needs to overcome in order to go from “I know a model of this type exists” to “I can tell an application developer how to apply this model to my domain.”
   
5. [Video - Deploying Machine Learning Models in Practice (Nick Pentreath)](https://youtu.be/9tOlyKxkRcc)

   *About* : The talk will cover various options for the most popular and widely used ML libraries, including MLeap, TF Serving and open standards such as PMML, PFA and the recently announced ONNX for Deep Learning. I will also introduce Aardpfark, initially covering Spark ML pipelines - as well as experimental work for exporting Spark ML pipelines to TensorFlow graphs for use with TF Serving.

6. [Video - Lessons Learned Building an Open Deep Learning Model Exchange (Nick Pentreath)](https://youtu.be/6vvl8OdmS14)
 
   *About* : This talk walks you through the process of building MAX and shares challenges and problems encountered, 
   the solutions developed, and the lessons learned, along with best practices for cross-framework, standardized deep learning model training and deployment.

7. [Video - Deploy Deep Learning models as Microservices in minutes - Gabriela de Queiroz, Karthik Muthuraman and Saishruthi Swaminathan](https://www.youtube.com/watch?v=L8nuj_RxbUk&t=1117s)

   *About* The talk will cover Model Asset Exchange, Data Asset Exchange and explains steps for wrapping a custom model using MAX-Framework.
   
## Community

1. [Join Community Slack](https://model-asset-exchange.slack.com/join/shared_invite/enQtNDQ4OTQxODUyMTYwLTI1NzgyMTRlNWE4ZGE3NmQ5ZjJhYjEwZjA3ZmY4NWViN2MxMWJiZjg0NzM1MTNiZGYwYmQ0MjQ2Mzk3YzI1Yjc)
2. [CODAIT Twitter](https://twitter.com/ibmcodait)
3. [CODAIT Medium](https://medium.com/codait)
4. [IBM Developer](https://developer.ibm.com/newsletters/)




