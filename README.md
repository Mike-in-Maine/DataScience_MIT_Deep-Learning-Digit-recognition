Facial Emotion Detection based on the domain - Deep Learning
MIT Applied Data Science Program - September 2023 cohort
By Michal Dusik


Problem Definition
The context:
Facial emotion recognition in machine learning and AI is crucial for several reasons. Humans express emotions primarily through facial expressions, and understanding these expressions can significantly enhance human-computer interactions, social robotics, and various applications across industries. In fields such as human-computer interaction, healthcare, customer service, and security, the ability of machines to recognize and respond to human emotions is becoming increasingly important.

Facial expression of emotions is cross-cultural, and several studies have shown its globality. (See references 1, 2, 3, 4) By deciphering facial expressions, machines can adapt their responses, improving user experience and personalization. For instance, in healthcare, emotion recognition can aid in monitoring mental health or assist individuals with conditions like autism. In customer service, recognizing emotions can enhance chatbot interactions or improve sentiment analysis. In security, it can contribute to more sophisticated surveillance systems, helping identify potentially harmful situations.

The objectives:
The primary goal of facial emotion recognition in machine learning and AI is to enable machines to accurately interpret and understand human emotions based on facial expressions. This involves training models to classify facial features into different emotional states, such as happiness, sadness, anger, surprise, fear, and neutrality. The objective is to achieve high accuracy and robustness across diverse demographics, lighting conditions, and facial expressions. (See references 5, 6, 7, 8)

Furthermore, the goal extends beyond mere emotion classification. Effective facial emotion recognition systems should also consider temporal aspects, understanding changes in emotion over time. This can lead to more context-aware systems that respond appropriately to evolving emotional states.

The key questions:

Data Representation: How can facial expressions be effectively represented in a way that captures the nuances of human emotion? This includes addressing challenges such as variations in lighting, pose, and facial characteristics.

Model Training: What machine learning or deep learning architectures are most effective for facial emotion recognition? How can models be trained on diverse datasets to ensure generalization to various populations?

Cross-Cultural Considerations: How do cultural differences influence facial expressions, and how can models be made culturally sensitive? Ensuring the robustness of models across diverse populations is crucial.

Real-time Processing: How can real-time facial emotion recognition be achieved, and what computational resources are required for efficient deployment in applications such as video conferencing or human-computer interaction?

Ethical Implications: What are the ethical considerations in developing facial emotion recognition systems, particularly regarding privacy, consent, and potential biases in the training data?


The problem formulation:
In data science, the problem involves developing models that can accurately classify facial expressions into distinct emotional categories. This requires the collection and preprocessing of labeled facial expression datasets, the exploration of suitable feature representations, and the training of robust machine learning models. Evaluating and fine-tuning these models on diverse datasets is crucial to ensure their effectiveness across different demographic groups and real-world conditions. Additionally, addressing ethical considerations and potential biases is an integral part of the problem formulation to ensure responsible and fair deployment of facial emotion recognition systems.


About the dataset
The data set consists of 3 folders, i.e., 'test', 'train', and 'validation'. Each of these folders has four subfolders:

‘happy’: Images of people who have happy facial expressions.
‘sad’: Images of people with sad or upset facial expressions.
‘surprise’: Images of people who have shocked or surprised facial expressions.
‘neutral’: Images of people showing no prominent emotion in their facial expression at all.

**No dataset, why?**
This dataset is about 440,000 KB or 440MB and it cannot be uploaded to github. Shoot me an email and I will send it to you.


**Description**
**Context:**
One of the most interesting tasks in deep learning is to recognize objects in natural scenes. The ability to process visual information using machine learning algorithms can be very useful as demonstrated in various applications.

The SVHN dataset contains over 600,000 labeled digits cropped from street-level photos. It is one of the most popular image recognition datasets. It has been used in neural networks created by Google to improve the map quality by automatically transcribing the address numbers from a patch of pixels. The transcribed number with a known street address helps pinpoint the location of the building it represents.

 

**Objective:**
Our objective is to predict the number depicted inside the image by using Artificial or Fully Connected Feed Forward Neural Networks and Convolutional Neural Networks. We will go through various models of each and finally select the one that is giving us the best performance. 

 

**Dataset:**
Our dataset is present in .h5 format. We will use a subset of our dataset to save ourselves a lot of computation time. This is for demonstration only.

