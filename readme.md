﻿# TOC
- [Use Cases](https://github.com/lankastersky/neuromantic#use-cases)
  - [Design](https://github.com/lankastersky/neuromantic#design)
  - [Games](https://github.com/lankastersky/neuromantic#games)
  - [Gesture Recognition](https://github.com/lankastersky/neuromantic#gesture-recognition)
  - [Image Recognition](https://github.com/lankastersky/neuromantic#image-recognition)
    - [Face Recognition](https://github.com/lankastersky/neuromantic#face-recognition)
    - [Person Detection](https://github.com/lankastersky/neuromantic#person-detection)
    - [Semantic segmentation](https://github.com/lankastersky/neuromantic#semantic-segmentation)
  - [Interpretability](https://github.com/lankastersky/neuromantic#interpretability)
  - [Programming and ML](https://github.com/lankastersky/neuromantic#programming-and-ml)
  - [NLP](https://github.com/lankastersky/neuromantic#nlp)
    - [Chatbots](https://github.com/lankastersky/neuromantic#chatbots)
    - [Crossword question answerers](https://github.com/lankastersky/neuromantic#crossword-question-answerers)
    - [Database queries](https://github.com/lankastersky/neuromantic#database-queries)
    - [Named entity resolution](https://github.com/lankastersky/neuromantic#named-entity-resolution)
    - [Reverse dictionaries](https://github.com/lankastersky/neuromantic#reverse-dictionaries)
    - [Sequence to sequence](https://github.com/lankastersky/neuromantic#sequence-to-sequence)
    - [Sentiment analysis](https://github.com/lankastersky/neuromantic#sentiment-analysis)
    - [Spelling](https://github.com/lankastersky/neuromantic#spelling)
    - [Summarization](https://github.com/lankastersky/neuromantic#summarization)
  - [Personality recognition](https://github.com/lankastersky/neuromantic#personality-recognition)
  - [Search](https://github.com/lankastersky/neuromantic#search)
  - [Sound recognition](https://github.com/lankastersky/neuromantic#sound-recognition)
  - [Transfer Learning](https://github.com/lankastersky/neuromantic#transfer-learning)
  - [Video recognition](https://github.com/lankastersky/neuromantic#video-recognition)
    - [Body recognition](https://github.com/lankastersky/neuromantic#body-recognition)
    - [Video segmentation](https://github.com/lankastersky/neuromantic#video-segmentation)
- [Tools](https://github.com/lankastersky/neuromantic#tools)
  - [Google Cloud AutoML](https://github.com/lankastersky/neuromantic#google-cloud-automl)
  - [Google Cloud ML Engine](https://github.com/lankastersky/neuromantic#google-cloud-ml-engine)
  - [Google Mobile Vision](https://github.com/lankastersky/neuromantic#google-mobile-vision)
  - [Chatbot platforms](https://github.com/lankastersky/neuromantic#chatbot-platforms)
    - [Oscova](https://github.com/lankastersky/neuromantic#oscova)
  - [Playgrounds](https://github.com/lankastersky/neuromantic#playgrounds)
- [Models](https://github.com/lankastersky/neuromantic#models)
  - [Decision trees](https://github.com/lankastersky/neuromantic#decision-trees)
  - [Distillation](https://github.com/lankastersky/neuromantic#distillation)
  - [Embedding models](https://github.com/lankastersky/neuromantic#embedding-models)
  - [Metrics of dataset quality](https://github.com/lankastersky/neuromantic#metrics-of-dataset-quality)
  - [Neural Networks](https://github.com/lankastersky/neuromantic#neural-networks)
    - [Distributed Neural Networks](https://github.com/lankastersky/neuromantic#distributed-neural-networks)
- [Articles](https://github.com/lankastersky/neuromantic#articles)
  - [Deep learning](https://github.com/lankastersky/neuromantic#deep-learning)
- [Books](https://github.com/lankastersky/neuromantic#books)
- [MOOC](https://github.com/lankastersky/neuromantic#mooc)

# Use Cases

## Design
- [Google Design: People + AI Research](https://design.google/library/ai/)
- [PAIR | People+AI Research Initiative](https://ai.google/pair)

## Games
- [Mastering the game of Go without human knowledge by David Silver et al, 2017](https://www.gwern.net/docs/rl/2017-silver.pdf)

## Gesture Recognition

### Using wearable sensors (phones, watches etc.)

Articles
- [Physical Human Activity Recognition Using Wearable Sensors by Ferhat Attal et al, 2015](http://www.mdpi.com/1424-8220/15/12/29858)
- [Activity Recognition with Smartphone Sensors by Xing Su et al, 2014](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6838194&tag=1)
- [Motion gesture detection using Tensorflow on Android](http://blog.lemberg.co.uk/motion-gesture-detection-using-tensorflow-android)
- [Run or Walk : Detecting Motion Activity Type with Machine Learning and Core ML](https://towardsdatascience.com/run-or-walk-detecting-user-activity-with-machine-learning-and-core-ml-part-1-9658c0dcdd90)
- Android [DetectedActivity class](https://developers.google.com/android/reference/com/google/android/gms/location/DetectedActivity)
- Android [ActivityRecognitionApi](https://developers.google.com/android/reference/com/google/android/gms/location/ActivityRecognitionApi)

Apps
- [Exercise Tracker: Wear Fitness](https://play.google.com/store/apps/details?id=vimo.co.seven)
- [Google Fit - Fitness Tracking](https://play.google.com/store/apps/details?id=com.google.android.apps.fitness)

Code repositories
- https://github.com/droiddeveloper1/android-wear-gestures-recognition
- https://github.com/drejkim/AndroidWearMotionSensors

## Image Recognition
- [Large-Scale Evolution of Image Classifiers by Esteban Real et al, 2017](https://arxiv.org/pdf/1703.01041.pdf)
- [TensorFlow-Slim image classification model library](https://github.com/tensorflow/models/tree/master/research/slim)
- [Rethinking the Inception Architecture for Computer Vision by Christian Szegedy et al, 2015](https://arxiv.org/abs/1512.00567)
- [Inception in TensorFlow](https://github.com/tensorflow/models/tree/master/research/inception) - 1.4M images and 1000 classes
- [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications by Andrew G. Howard et al, 2017](https://arxiv.org/abs/1704.04861)
  - Similar approach on practice: [How HBO’s Silicon Valley built “Not Hotdog” with mobile TensorFlow, Keras & React Native](https://medium.com/@timanglade/how-hbos-silicon-valley-built-not-hotdog-with-mobile-tensorflow-keras-react-native-ef03260747f3)
- [ImageNet Classification with Deep Convolutional Neural Networks by Alex Krizhevsky et al, 2012](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks)
  - [ImageNet](http://image-net.org/)
  - the model is based on CNN
- [Xception: Deep Learning with Depthwise Separable Convolutions by François Chollet, 2017](https://arxiv.org/abs/1610.02357)
- [ImageNet Classification with Deep Convolutional Neural Networks by Alex Krizhevsky, Ilya Sutskever, Geoffrey E. Hinton, 2012](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)

### Face Recognition
- [FaceNet: A Unified Embedding for Face Recognition and Clustering by Florian Schroff et al, 2015](https://arxiv.org/abs/1503.03832)
  - the model: FaceNet

### Person Detection
- [Automatic Portrait Segmentation for Image Stylization by Xiaoyong Shen1 et al, 2016](http://www.cse.cuhk.edu.hk/leojia/papers/portrait_eg16.pdf)

### Semantic Segmentation
- https://github.com/facebookresearch/Detectron, see links to articles at the end of the page
- [Rethinking Atrous Convolution for Semantic Image Segmentation by Liang-Chieh Chen et al, 2017](https://arxiv.org/pdf/1706.05587.pdf)
- [DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs by Liang-Chieh Chen et al, 2017](https://arxiv.org/pdf/1606.00915.pdf)
- [Mask R-CNN by Kaiming He et al, 2017](https://arxiv.org/abs/1703.06870)

## Interpretability
- [Attributing a deep network’s prediction to its input features by MUKUND SUNDARARAJAN, 2017](http://www.unofficialgoogledatascience.com/2017/03/attributing-deep-networks-prediction-to.html)
  - Integrated Gradients method
- [A unified approach to interpreting model predictions by Scott M Lundberg et al, 2017](https://nips.cc/Conferences/2017/Schedule?showEvent=10008)
- ["Why Should I Trust You?": Explaining the Predictions of Any Classifier by Marco Tulio Ribeiro et al, 2016](https://arxiv.org/abs/1602.04938)
  - [Lime Framework: Explaining the predictions of any machine learning classifier](https://github.com/marcotcr/lime)
- [Monotonic Calibrated Interpolated Look-Up Tables by Maya Gupta et al, 2016](http://jmlr.org/papers/v17/15-243.html)
- see [Decision trees](https://github.com/lankastersky/neuromantic#decision-trees)
- see [Distillation](https://github.com/lankastersky/neuromantic#distillation)

## Programming and ML
- [Software	is	eating	the	world,	but	ML	is	going	to	eat	software by Erik Meijer, Facebook, 2018](https://pps2018.soic.indiana.edu/files/2017/12/PPS2018Meijer.pdf)
- [To type or not to type: quantifying detectable bugs in JavaScript by Gao et al, 2017](https://blog.acolyer.org/2017/09/19/to-type-or-not-to-type-quantifying-detectable-bugs-in-javascript/)
- [A Survey of Machine Learning for Big Code and Naturalness by Miltiadis Allamanis et al, 2017](https://arxiv.org/abs/1709.06182)
- https://www.deepcode.ai/

## NLP
- [How to Clean Text for Machine Learning with Python](https://machinelearningmastery.com/clean-text-machine-learning-python/)

### Chatbots
- [How I Used Deep Learning To Train A Chatbot To Talk Like Me (Sorta)](https://adeshpande3.github.io/How-I-Used-Deep-Learning-to-Train-a-Chatbot-to-Talk-Like-Me)
  - Short-Text Conversations generative model based on Tensorflow’s embedding_rnn_seq2seq() with custom dataset. Deployed as a Facebook chatbot using heroku (hosting)+express(frontend)+flask(backend)
- [Deep Learning for Chatbots, Part 1 – Introduction, 2016](http://www.wildml.com/2016/04/deep-learning-for-chatbots-part-1-introduction/)
- [Deep Learning for Chatbots, Part 2 – Implementing a Retrieval-Based Model in Tensorflow, 2016](http://www.wildml.com/2016/07/deep-learning-for-chatbots-2-retrieval-based-model-tensorflow/)
- https://github.com/gunthercox/ChatterBot
  - Retrieval-based model based on [naive Bayesian classification and search algorithms](http://chatterbot.readthedocs.io/en/stable/faq.html#what-kinds-of-machine-learning-does-chatterbot-use) 
  - see [Sequence to sequence](https://github.com/lankastersky/neuromantic#sequence-to-sequence)
- [A Persona-Based Neural Conversation Model by Jiwei Li et al, 2016](https://arxiv.org/abs/1603.06155)
- Smart reply
  - [Smart Reply: Automated Response Suggestion for Emai by Anjuli Kannan et al, 2016](https://arxiv.org/abs/1606.04870)
  - [Computer, respond to this email, 2015](https://research.googleblog.com/2015/11/computer-respond-to-this-email.html)
- Chatbot projects: https://github.com/fendouai/Awesome-Chatbot
- see [Chatbot platforms](https://github.com/lankastersky/neuromantic#chatbot-platforms)

### Crossword question answerers
- see [Reverse dictionaries](https://github.com/lankastersky/neuromantic#reverse-dictionaries)

### Database queries
- [LEARNING A NATURAL LANGUAGE INTERFACE WITH NEURAL PROGRAMMER by Arvind Neelakantan et al, 2017](https://arxiv.org/pdf/1611.08945.pdf)
  - weakly supervised, end-to-end neural network model mapping natural language queries to logical forms or programs that
provide the desired response when executed on the database

### Named entity resolution
Also known as deduplication and record linkage (but [not entity recognition](https://stackoverflow.com/questions/8589005/difference-between-named-entity-recognition-and-resolution) which is picking up the names and classifying them in running text)
- [Collective Entity Resolution in Familial Networks by Pigi Kouki et al, 2017](https://linqspub.soe.ucsc.edu/basilic/web/Publications/2017/kouki:icdm17/kouki-icdm17.pdf)
  - combines machine learning (although not NNs) with collective inference
- [Entity Resolution Using Convolutional Neural Network by Ram DeepakGottapu et al, 2016](https://www.sciencedirect.com/science/article/pii/S1877050916324796)
- [Adaptive Blocking: Learning to Scale Up Record Linkage by Mikhail Bilenko et al, 2006](http://www.cs.utexas.edu/~ml/papers/blocking-icdm-06.pdf)
  - extremely high recall but low precision
- https://stats.stackexchange.com/questions/136755/popular-named-entity-resolution-software

### Reverse dictionaries
Other name is concept finders
Return the name of a concept given a definition or description:
- [Learning to Understand Phrases by Embedding the Dictionary by Felix Hill et al, 2016](http://www.aclweb.org/anthology/Q16-1002)
  - used models: Bag-of-Words NLMs and LSTM
- comparing definitions in a database to the input query, and returning the word whose definitionis ‘closest’ to that query
- see RNNs (with LSTMs)
- see bag-of-word

### Sequence to sequence
- [Generating High-Quality and Informative Conversation Responses with Sequence-to-Sequence Models by Louis Shao et al, 2017](https://research.google.com/pubs/pub45936.html)
  - trained on a combined data set of over 2.3B conversation messages mined from the web
  - The model: LSTM on tensorflow
- [Unsupervised Learning of Sentence Embeddings using Compositional n-Gram Features by Matteo Pagliardini et al, 2017](https://arxiv.org/pdf/1703.02507.pdf)
  - the model: Sent2Vec based on vec2vec
- [Skip-Thought Vectors by Ryan Kiros et al, 2015](https://arxiv.org/abs/1506.06726)
  - based on RNN encoder-decoder models
- [Sequence to Sequence Learning with Neural Networks by Ilya Sutskever et al, 2014](https://arxiv.org/abs/1409.3215)
  - the model: seq2seq based on LSTM
- [Distributed Representations of Sentences and Documents by Quoc V. Le, Mikolov, 2014](https://arxiv.org/abs/1405.4053)
  - [gensim's doc2vec](https://radimrehurek.com/gensim/models/doc2vec.html)
  - [python example to train doc2vec model (with or without pre-trained word embeddings)](https://github.com/jhlau/doc2vec)
- [Distributed Representations of Words and Phrases and their Compositionality by Tomas Mikolov et al, 2013](https://arxiv.org/abs/1310.4546)
  - word2vec based on Mikolov's Skip-gram model
- [Learning Continuous Phrase Representations and Syntactic Parsing with Recursive Neural Networks by Richard Socher et al, 2010](http://ai.stanford.edu/~ang/papers/nipsdlufl10-LearningContinuousPhraseRepresentations.pdf)
  - based on context-sensitive recursive neural networks (CRNN)
- see [Reverse dictionaries](https://github.com/lankastersky/neuromantic#reverse-dictionaries)
- [How to calculate the sentence similarity using word2vec model](https://stackoverflow.com/questions/22129943/how-to-calculate-the-sentence-similarity-using-word2vec-model-of-gensim-with-pyt)
  - Doc2Vec
  - Average w2v vectors
  - Weighted average w2v vectors (e.g. tf-idf)
  - RNN-based embeddings (e.g. deep LSTM networks)
  - [Document Similarity With Word Movers Distance](http://jxieeducation.com/2016-06-13/Document-Similarity-With-Word-Movers-Distance/)
    - [From Word Embeddings To Document Distances by Matt J. Kusner et al, 2015](http://proceedings.mlr.press/v37/kusnerb15.pdf)
  - [A SIMPLE BUT TOUGH-TO-BEAT BASELINE FOR SENTENCE EMBEDDINGS by Sanjeev Arora et al, 2017](https://openreview.net/pdf?id=SyK00v5xx)
    - uses smooth inverse frequency
    - computing the weighted average of word vectors in the sentence and then remove the projections of the average vectors on their first principal component
    - [example](http://sujitpal.blogspot.com/2017/05/evaluating-simple-but-tough-to-beat.html)
    - https://github.com/peter3125/sentence2vec - requires writing the get_word_frequency() method which can be easily accomplished by using Python's Counter() and returning a dict with keys: unique words w, values: #w/#total doc len

Evaluation:
- [Semantic Textual Similarity Wiki](http://ixa2.si.ehu.es/stswiki/index.php/Main_Page)

### Sentiment analysis
- [doc2vec example, 2015](http://linanqiu.github.io/2015/10/07/word2vec-sentiment/)

### Spelling
- [How to Write a Spelling Corrector](http://norvig.com/spell-correct.html)

### Summarization
- [Generating Wikipedia by Summarizing Long Sequences by Peter J. Liu et al, 2018](https://arxiv.org/abs/1801.10198)

## Personality recognition
- Mining Facebook Data for Predictive Personality Modeling (Dejan Markovikj,Sonja Gievska, Michal Kosinski, David Stillwell)
- Personality Traits Recognition on Social Network — Facebook (Firoj Alam, Evgeny A. Stepanov, Giuseppe Riccardi)
- The Relationship Between Dimensions of Love, Personality, and Relationship Length (Gorkan Ahmetoglu, Viren Swami, Tomas Chamorro-Premuzic)

## Search
- [Neural Architecture Search with Reinforcement Learning by Barret Zoph et al, 2017](https://arxiv.org/abs/1611.01578)
- [Can word2vec be used for search?](https://www.reddit.com/r/MachineLearning/comments/4mw927/can_word2vec_be_used_for_search/)
  - alternative search queries can be built using approximate nearest neighbors in embedding vectors space of terms (using https://github.com/spotify/annoy e.g.)
  - [Improving Document Ranking with Dual Word Embeddings by Eric Nalisnick et al, 2016](https://www.microsoft.com/en-us/research/publication/improving-document-ranking-with-dual-word-embeddings/?from=http%3A%2F%2Fresearch.microsoft.com%2Fapps%2Fpubs%2Fdefault.aspx%3Fid%3D260867)
  

## Sound recognition

Annotated Datasets
- [The VU sound corpus](https://github.com/CrowdTruth/vu-sound-corpus) - based on https://freesound.org/ database
  - See article [The VU Sound Corpus by Emiel van Miltenburg et al](http://www.lrec-conf.org/proceedings/lrec2016/pdf/206_Paper.pdf)
- [AudioSet](https://research.google.com/audioset/) - consists of an expanding ontology of 632 audio event classes and a collection of 2,084,320 human-labeled 10-second sound clips drawn from YouTube videos
- [How do I listen for a sound that matches a pre-recorded sound?](https://arduino.stackexchange.com/questions/8781/how-do-i-listen-for-a-sound-that-matches-a-pre-recorded-sound)
- The Sound Sensor Alert App [sentector](http://sentector.com/)

## Transfer Learning
- [Deep Learning & Art: Neural Style Transfer – An Implementation with Tensorflow in Python](https://www.datasciencecentral.com/profiles/blogs/deep-learning-amp-art-neural-style-transfer-an-implementation)
- [Image Classification using Flowers dataset on Cloud ML Enginge](https://cloud.google.com/ml-engine/docs/flowers-tutorial)

## Video recognition

### Body recognition
- [Enabling full body AR with Mask R-CNN2Go by Fei Yang et al, 2018](https://research.fb.com/enabling-full-body-ar-with-mask-r-cnn2go/)

### Video segmentation
Detects when one video (shot/scene/chapter) ends and another begins
- [Ridiculously Fast Shot Boundary Detection with Fully Convolutional Neural Networks by Michael Gygli, 2017](https://arxiv.org/abs/1705.08214)
- [Video Shot Boundary Detection based on Color Histogram by J. Mas and G. Fernandez, 2003](http://www-nlpir.nist.gov/projects/tvpubs/tvpapers03/ramonlull.paper.pdf)
- Unsupervised Learning from Narrated Instruction Videos, Arxiv, 2015
- Recurrent Switching Linear Dynamical Systems, CVPR, 2016
- DeepStory: Video Story QA by Deep Embedded Memory Networks, Arxiv, 2017
- Hierarchical Deep Recurrent Architecture for Video Understanding, Arxiv, 2017
- Automatic Video Scene Segmentation based on Spatial-Temporal Clues and Rhythm, Networking and Information Systems Journal, 2000
- Video Scene Segmentation Using Markov Chain Monte Carlo, TMM, 2006
- Sound:
  - S. Hershey et al., CNN Architectures for Large-Scale Audio Classification, Arxiv 2017.
  - A. Jansen et al., Large-Scale Audio Event Discovery in One Million YouTube Videos, ICASSP 2017
  - C. Szegedy et al., Going Deeper with Convolutions, CVPR 2015.

# Tools

## [Google Cloud AutoML](https://cloud.google.com/automl/)

Pros:
- let users train their own custom machine learning algorithms from scratch, without having to write a single line of code
- uses Transfer Learning (the more data and customers, the better results)
- is fully integrated with other Google Cloud services (Google Cloud Storage to store data, use Cloud ML or Vision API to customize the model etc.)

Cons:
- limited to image recognition (2018-Q1)
- doesn't allow to download a trained model

## [Google Cloud ML Engine](https://cloud.google.com/ml-engine/)
- [Samples & Tutorials](https://cloud.google.com/ml-engine/docs/tutorials)

## [Google Mobile Vision](https://developers.google.com/vision/)

Pros:
- Detect Faces (finds facial landmarks such as the eyes, nose, and mouth; doesn't identifies a person)
- Scan barcodes
- Recognize Text

Cons:

## Chatbot platforms

### [Oscova](https://developer.syn.co.in/tutorial/bot/oscova/machine-learning.html)
- [finds similarity between the expressions](https://forum.syn.co.in/viewtopic.php?t=1845&p=3209)
- https://github.com/SynHub/syn-bot-samples
- MS Visual Studio is required (doesn't work with VS Code)
- activating Deep Learning feature requires [license activating](https://developer.syn.co.in/tutorial/bot/activate-license.html)
- number of requests to the server is limited by the license

## Playgrounds
- [Teachable Machine by Google](https://teachablemachine.withgoogle.com/)

# Models

## Decision Trees
Pros:
- can model nonlinearities
- are highly interpretable
- do not require extensive feature preprocessing
- do not require enormous data sets

Cons:
- tend to overfit
  - fixed by building a decision forest with boosting
- unstable/undeterministic (generate different results while trained on the same data)
  - fixed by using bootstrap aggregation/bagging (a boosted forest)
- do mapping directly from the raw input to the label
  - better use neural nets that can learn intermediate representations

Hyperparameters:
- tree depth
- maximum number of leaf nodes

## Distillation
  - trains a model to mimic the behavior of a pretrained model so it can work independently of the pretrained model
  - can train the smaller model with unlabeled examples
  - not all target classes need to be represented in the distillation training set
  - reduces the need for regularization
  - [Distilling the Knowledge in a Neural Network by Geoffrey Hinton et al, 2015](https://arxiv.org/abs/1503.02531)
  - [“Why Should I Trust You?” Explaining the Predictions of Any Classifier by Marco Tulio Ribeiro et al, 2016](https://arxiv.org/abs/1602.04938)
  - [Detecting Bias in Black-Box Models Using Transparent Model Distillation by Sarah Tan et al, 2017](https://arxiv.org/abs/1710.06169)

## Embedding models
- https://github.com/Hironsan/awesome-embedding-models
- [gensim's word2vec](https://code.google.com/archive/p/word2vec/source) (embedded words and phrases)
  - [online vocaburary update tutorial](https://github.com/RaRe-Technologies/gensim/blob/develop/docs/notebooks/online_w2v_tutorial.ipynb)
  - [How to Develop Word Embeddings in Python with Gensim](https://machinelearningmastery.com/develop-word-embeddings-python-gensim/)
- [gensim's doc2vec](https://radimrehurek.com/gensim/models/doc2vec.html)
- https://github.com/jhlau/doc2vec
- see recursive autoencoders
- see bag-of-words models

## Metrics of dataset quality
- Statistical metrics
  - descriptive statistics: dimensionality, unique subject counts, systematic replicates counts, pdfs, cdfs (probability and cumulative distribution fx's)
  - cohort design
  - power analysis
  - sensitivity analysis
  - multiple testing correction analysis
  - dynamic range sensitivity
- Numerical analysis metrics
  - number of clusters
  - PCA dimensions
  - MDS space dimensions/distances/curves/surfaces
  - variance between buckets/bags/trees/branches
  - informative/discriminative indices (i.e. how much does the top 10 features differ from one another and the group)
  - feature engineering differnetiators

## Neural Networks
[Approaches](https://medium.com/@sayondutta/nuts-and-bolts-of-applying-deep-learning-by-andrew-ng-89e1cab8b602) when our model doesn’t work:
- Fetch more data
- Add more layers to Neural Network
- Try some new approach in Neural Network
- Train longer (increase the number of iterations)
- Change batch size
- Try Regularisation
- Check Bias Variance trade-off to avoid under and overfitting
- Use more GPUs for faster computation

Back-propagation problems:
- it requires labeled training data; while almost all data is unlabeled
- the learning time does not scale well, which means it is very slow in networks with multiple hidden layers
- it can get stuck in poor local optima, so for deep nets they are far from optimal.

### Convolutional Neural Networks

### Distributed Neural Networks
- [Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer by Jeff Dean et al](https://arxiv.org/abs/1701.06538)
- [PathNet: Evolution Channels Gradient Descent in Super Neural Networks by deepmind](https://deepmind.com/research/publications/pathnet-evolution-channels-gradient-descent-super-neural-networks/)
- Feature extraction - uses layers of a pretrained model as inputs to another model, effectively chaining two models together

### Feed-Forward Neural Networks
- Perceptrons

### Long-Short Term Memory Networks
- [Offline Handwriting Recognition with Multidimensional Recurrent Neural Networks by Graves & Schmidhuber, 2009](http://people.idsia.ch/~juergen/nips2009.pdf)
  - showed that RNNs with LSTM are currently the best systems for reading cursive writing
- [LONG SHORT-TERM MEMORY by Hochreiter & Schmidhuber, 1997](http://www.bioinf.jku.at/publications/older/2604.pdf)

### Recurrent Neural Networks
- see [Long-Short Term Memory Networks](https://github.com/lankastersky/neuromantic/blob/master/readme.md#long-short-term-memory-networks)

### Symmetrically Connected Networks
- Hopfield Nets (without hidden units)
  - [Neural networks and physical systems with emergent collective computational abilities by Hopfield, 1982](http://www.pnas.org/content/pnas/79/8/2554.full.pdf)
- Boltzmann machines (stochastic recurrent neural network with hidden units)
 -  Restricted Boltzmann Machines by Salakhutdinov and Hinton, 2014
 - [Deep Boltzmann Machines by Salakhutdinov and Hinton, 2012](http://proceedings.mlr.press/v5/salakhutdinov09a/salakhutdinov09a.pdf)
 

# Articles
- [Machine Learning: The High Interest Credit Card of Technical Debt by D. Sculley et al, 2014](https://research.google.com/pubs/pub43146.html)
  - Complex Models Erode Boundaries
    - Entanglement
    - Hidden Feedback Loops
    - Undeclared Consumers
  - Data Dependencies Cost More than Code Dependencies
    - Unstable Data Dependencies
    - Underutilized Data Dependencies
    - Static Analysis of Data Dependencies
    - Correction Cascades
  - System-level Spaghetti
    - Glue Code
    - Pipeline Jungles
    - Dead Experimental Codepaths
    - Configuration Debt
  - Dealing with Changes in the External World
    - Fixed Thresholds in Dynamic Systems
    - When Correlations No Longer Correlate
    - Monitoring and Testing

## Deep learning
- [Deep Learning: A Critical Appraisal by Gary Marcus, 2018](https://arxiv.org/abs/1801.00631)
  - Deep learning thus far is data hungry 
  - Deep learning thus far is shallow and has limited capacity for transfer
  - Deep learning thus far has no natural way to deal with hierarchical structure
  - Deep learning thus far has struggled with open-ended inference 
  - Deep learning thus far is not sufficiently transparent 
  - Deep learning thus far has not been well integrated with prior knowledge
  - Deep learning thus far cannot inherently distinguish causation from correlation
  - Deep learning presumes a largely stable world, in ways that may be problematic
  - Deep learning thus far works well as an approximation, but its answers often cannot be fully trusted
  - Deep learning thus far is difficult to engineer with 
- [Software 2.0 by Andrej Karpathy, 2017](https://medium.com/@karpathy/software-2-0-a64152b37c35)

# MOOC

# Books


