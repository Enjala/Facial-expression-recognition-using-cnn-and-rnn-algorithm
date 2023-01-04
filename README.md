# Facial-expression-recognition-using-cnn-and-rnn-algorithm

    ----------------- total documentation---------


**ABSTRACT**
In current days for identifying a person emotion takes a lot of time because of varying expressions and features present in human faces. There was a lot of study going on to detect the several types of expressions from human’s in different environments such as work ,play ,relax, break and so on. Home room correspondence includes instructor's conduct and understudy's reactions. There was a lot of research work done on the investigation of below average students and average students by the instructor to identify those students and take some special care. In the primitive day’s almost human emotions are identified manually based on the current expression and feelings of the human’s in day to day environment. But there was no accurate method designed in primitive days for identifying the emotions or expressions automatically. 

This emotion recognition is becoming an interesting aspect which is used mainly for diagnosis of human brain and psychological disorders. In a recent survey conducted by a team of experts, we came to know that deep learning has gained a lot of user’s attention in the field of image classification. These emotions is used for not only diagnosis of human brain but also used as a recommended systems to assist users in finding items that match their needs and preferences. Hence this motivated me to develop a system which can effectively and efficiently recognizes emotions from the facial expressions of the user. In this proposed article we try to develop an application which can be used for prediction of expressions of both still images. Here we try to develop a system by using two well-known models such as CNN and RNN and then check which model suits best for facial expression recognition. The highest probability value to the corresponding expression will be the predicted expression for the image.

We have conducted experiments on FER_2013 Data set which we collected from KAGGLE website and try to train the system to detect the emotions accurately. Experimentation results show critical execution acquire on boundaries like exactness, F1-score, and review.




INTRODUCTION
Now a days it is very interesting and challenging task to detect expressions from pictures and recordings and has become extremely huge on account of its various applications in the PC vision area, for example, in human computer collaboration , expanded and computer generated reality, advance driver help framework (ADASs), and video recovery and security frameworks . Human expressions and emotions have been analyzed in examinations with the assistance of acoustic and semantic highlights, looks, body pose, hand development, bearing of look, and use of electroencephalograms (EEGs) and electrocardiograms (ECGs) .Educators show various     feelings which are brought about by different reasons, e.g., a teacher may encounter delight when an instructive goal is being satisfied or when understudies follow given headings. At the point when understudies show an absence of interest and reluctance to get a handle on an idea, it causes dissatisfaction. Also, outrage is reflected when understudies need discipline. As indicated by educators, these looks regularly emerge from disciplinary study hall collaborations, and dealing with these looks oftentimes helps them in accomplishing their objectives. The impression of data preparing has totally changed by these profound learning draws near. Because of its amazing capacity of self-learning, profound learning is viewed as a superior choice for vision and characterization issues. Different methodologies for arrangement incorporate pretrained networks which decrease the cycle of long preparing by presenting the utilization of pretrained loads. Nonetheless, learning here includes tuning of millions of organization boundaries and colossal marked information for preparing. Since FER is fundamentally pertinent to various fields, we trust FER utilizing profound highlights can be appropriate in understanding the semantics of educator's looks in a study hall climate. 
Now a days it is becoming a challenging task to identify or detect the facial features in the fields of video surveillance camera or image cameras, biometrics and a lot more. There are nearly seven basic emotions in the universe to detect the current emotion of human beings, namely neutral, angry, disgust, fear, happy, sad, and surprise and these basic emotions can be recognized from human’s facial expression. In general to solve the problem of recognizing facial features is very complex job because each and every individual has several facial features when compared with one person to other person.
 
 FIGURE 1: Denote the Several Factors which are considered for Face Emotion Recognition
In general there are a lot of factors which influence the features like physical characteristics, sex, genes, and age. In the real world environment there are many factors that have to be taken emotion recognition system which is shown in figure .The main step for any face processing system is the ability to classify the face accurately and then try to detect the emotion from that facial expression. A general emotion detection system has four stages of process flows:	
1)	Face Detection
2)	Preprocessing
3)	Feature Extraction
4)	Emotion Recognition


 

FIGURE 2: Denote the General Flow of Emotion Detection from Facial Expression
From the above figure 2, we can clearly identify the system is going to identify the emotions collected from input image and initially we try to load the input dataset which contains a set of images. 
All the images are given for the system for training purpose and once the images are loaded into the application they are pre-processed and features are extracted. All the features are extracted and kept ready for classification of input image. If any user who wish to find out the emotion he need to load the image either through web cam or he can browse for an image and then try to train with already pre-loaded images and now after classification is done, emotion is detected.
During the process of emotion detection the accuracy of emotion depend on the quality of image and factors which are influenced for emotion detection. If the image is clear and having bright appearance then emotion will be accurately detected and if the input contains any noise or factors which affect the image recognition then emotion may not be accurate.


 
LITERATURE SURVEY:
Literature survey is that the most vital step in the software development process. Before developing the new application or model, it's necessary to work out the time factor, economy, and company strength. Once all these factors are confirmed and got approval then we can start building the application. The literature survey is one that mainly deals with all the previous work which is done by several users and what are the advantages and limitations of those previous models. This literature survey is mainly used for identifying the list of resources to construct this proposed application.

MOTIVATION
1)	Automated Facial Expression Recognition System Using Neural Network Classifiers
Creators: Jyh-Yeong et al.
In this proposed paper the author proposes automated facial expression recognition system using neural network classifiers. The author used Rough Contour Estimation Routine (RCER) technique for extracting the features from a human face like eyebrows, eyes, mouth with the help of Point Contour Detection Method (PCDM)
 in order to improve and detect the precision of eye and mouth. In this proposed paper                the author try to find out a novel method like Action Units (AU)  in which we can able to see the basic movements of face muscles.
2)	A real time face emotion classification and recognition using deep learning model
Creators: Dr. Shaik Asif Hussain, Ahlam Salim Abdallah Al Balushi
The proposed authors try to discuss about face emotion classification and recognition under real time manner by using deep learning model. In this paper the authors try to extract the main features with deep learning, Haar cascade and VGG 16 model to recognize face and try to build the classification and recognition. From the experimental results the authors clearly prove that the network architecture which was designed for this current paper has better advancements than compared with existing algorithms. Here the proposed deep learning models are comparatively having more improvement than compared with several other models which were used in the literature of facial expression detection.
 
3)	A Real-Time Recognition System for User Characteristics Based on Deep Learning.
 Creators: Dan Duncan
This author proposes a real time recognition system for user characteristics based on deep learning models. In this paper the author try to design a VGG is an innovative object-recognition model that supports up to 19 layers. This is mainly built on the top of CNN and based on this CNN we can able to outperform baseline on many tasks and datasets outside of ImageNet. This proposed system is designed by overcoming the pre-processing difficulties which is present in the CNN and this proposed system we can able to prove much larger dataset in order to improve the model’s generality. The proposed system can able to provide accuracy in perfect manner and prove straight angle.

 
SYSTEM ANALYSIS
EXISTING SYSTEM AND ITS LIMITATIONS
In the existing system, there was no concept like facial expression recognition using CNN & RNN models. All the prediction is done using manual approach or by using primitive Machine Learning models.
In the ML we can able to classify only few emotions accurately depend on the human expression at that appropriate situation, but the manual approach or primitive methods are not accurate to classify the emotions accurately in all situation.
LIMITATIONS OF THE EXISTING SYSTEM
1.	All the existing schemes are limited to the manual classification of expression.
2.	All the existing systems are failed to detect all emotions from the human expressions.
3.	All the existing methods try to classify the emotions either 3 or 4 emotions but not all the seven emotions.
4.	All the existing ML approaches fail to classify the emotions accurately if the image is captured in low lighting conditions or poor appearance.
5.	There is no accurate model to classify the human emotions automatically from the given input image with prediction values.
 
PROPOSED SYSTEM
In this proposed article we try to develop an application which can be used for prediction of expressions of both still images. Here we try to develop a system by using two well-known models such as CNN and RNN and then check which model suits best for facial expression recognition. The highest probability value to the corresponding expression will be the predicted expression for the image.
We have conducted experiments on FER_2013 Data set which we collected from KAGGLE website and try to train the system to detect the emotions accurately. Experimentation results show critical execution acquire on boundaries like exactness, F1-score, and review.

ADVANTAGES OF THE PROPOSED SYSTEM
1.	The proposed scheme is very accurate in emotion detection from several expressions.
2.	The proposed system gives accurate results for the end users in order to identify the current mental state of that human from his expressions.
3.	The proposed system is capable of classifying a large set of images which are captured either short distances or long distances.
4.	The proposed system is designed based on CNN and RNN model to improve the accuracy of human emotion detection.
5.	The proposed system can accurately identify the human emotions based on expressions in very low lighting conditions or poor appearance.
6.	We can get comparative analysis of two models for automatically facial expression recognition for the given input images.
 
SYSTEM STUDY
FEASIBILITY STUDY:
The feasibility of the project is analyzed in this phase and business proposal is put forth with a very general plan for the project and some cost estimates. During system analysis the feasibility study of the proposed system is to be carried out. This is to ensure that the proposed system is not a burden to the company.  For feasibility analysis, some understanding of the major requirements for the system is essential.
Three key considerations involved in the feasibility analysis are	
•	ECONOMICAL FEASIBILITY
•	TECHNICAL FEASIBILITY
•	SOCIAL FEASIBILITY
	
ECONOMICAL FEASIBILITY
This study is carried out to check the economic impact that the system will have on the organization. The amount of fund that the company can pour into the research and development of the system is limited. The expenditures must be justified. Thus the developed system as well within the budget and this was achieved because most of the technologies used are freely available. Only the customized products had to be purchased. 

TECHNICAL FEASIBILITY
This study is carried out to check the technical feasibility, that is, the technical requirements of the system. Any system developed must not have a high demand on the available technical resources. This will lead to high demands on the available technical resources. This will lead to high demands being placed on the client. The developed system must have a modest requirement, as only minimal or null changes are required for implementing this system.   


 
SOCIAL FEASIBILITY
The aspect of study is to check the level of acceptance of the system by the user. This includes the process of training the user to use the system efficiently. The user must not feel threatened by the system, instead must accept it as a necessity. The level of acceptance by the users solely depends on the methods that are employed to educate the user about the system and to make him familiar with it. His level of confidence must be raised so that he is also able to make some constructive criticism, which is welcomed, as he is the final user of the system.

















SYSTEM SPECIFICATION:
HARDWARE REQUIREMENTS:
	System		        :   Pentium IV 2.4 GHz.
	Hard Disk	        :   40 GB.
	Floppy Drive	        :   1.44 Mb.
	Monitor	        :   14’ Colour Monitor.
	Mouse		        :   Optical Mouse.
	Ram		        :   512 Mb.
SOFTWARE REQUIREMENTS:
	Operating system 	:   Windows 7 Ultimate.
	Coding Language	:   Python.
	Front-End		:   Python.
	Designing		:   Html, CSS, Javascript.
	Data Base		:   My SQL.


 
REQUIREMENT ANALYSIS:
The project involved analyzing the design of few applications so as to make the application more users friendly. To do so, it was really important to keep the navigations from one screen to the other well ordered and at the same time reducing the amount of typing the user needs to do. In order to make the application more accessible, the browser version had to be chosen so that it is compatible with most of the Browsers. 
REQUIREMENT SPECIFICATION
Functional Requirements
	Graphical User interface with the User.
Software Requirements
For developing the application the following are the Software Requirements:
1.	Python
2.	Django
3.	My Sql
4.	MySqlclient
5.	WampServer 2.4
Operating Systems supported
1.	Windows 7
2.	Windows XP
3.	Windows 8
Technologies and Languages used to Develop
1.	Python
Debugger and Emulator
	Any Browser (Particularly Chrome)

Hardware Requirements
For developing the application the following are the Hardware Requirements:
	Processor: Pentium IV or higher
	RAM: 256 MB
	Space on Hard Disk: minimum 512MB

 
SYSTEM DESIGN:
INPUT DESIGN
The input design is the link between the information system and the user. It comprises the developing specification and procedures for data preparation and those steps are necessary to put transaction data in to a usable form for processing can be achieved by inspecting the computer to read data from a written or printed document or it can occur by having people keying the data directly into the system. The design of input focuses on controlling the amount of input required, controlling the errors, avoiding delay, avoiding extra steps and keeping the process simple. The input is designed in such a way so that it provides security and ease of use with retaining the privacy. Input Design considered the following things:
	What data should be given as input?
	 How the data should be arranged or coded?
	 The dialog to guide the operating personnel in providing input.
	Methods for preparing input validations and steps to follow when error occur.

OBJECTIVES
1. Input Design is the process of converting a user-oriented description of the input into a computer-based system. This design is important to avoid errors in the data input process and show the correct direction to the management for getting correct information from the computerized system.
2. It is achieved by creating user-friendly screens for the data entry to handle large volume of data. The goal of designing input is to make data entry easier and to be free from errors. The data entry screen is designed in such a way that all the data manipulates can be performed. It also provides record viewing facilities.
3. When the data is entered it will check for its validity. Data can be entered with the help of screens. Appropriate messages are provided as when needed so that the user will not be in maize of instant. Thus the objective of input design is to create an input layout that is easy to follow


OUTPUT DESIGN
A quality output is one, which meets the requirements of the end user and presents the information clearly. In any system results of processing are communicated to the users and to other system through outputs. In output design it is determined how the information is to be displaced for immediate need and also the hard copy output. It is the most important and direct source information to the user. Efficient and intelligent output design improves the system’s relationship to help user decision-making.
1. Designing computer output should proceed in an organized, well thought out manner; the right output must be developed while ensuring that each output element is designed so that people will find the system can use easily and effectively. When analysis design computer output, they should Identify the specific output that is needed to meet the requirements.
2. Select methods for presenting information.
3. Create document, report, or other formats that contain information produced by the system.
The output form of an information system should accomplish one or more of the following objectives.
	Convey information about past activities, current status or projections of the
	Future.
	Signal important events, opportunities, problems, or warnings.
	Trigger an action.
	Confirm an action.







UML DIAGRAMS
UML stands for Unified Modeling Language. UML is a standardized general-purpose modeling language in the field of object-oriented software engineering. The standard is managed, and was created by, the Object Management Group. 
The goal is for UML to become a common language for creating models of object oriented computer software. In its current form UML is comprised of two major components: a Meta-model and a notation. In the future, some form of method or process may also be added to; or associated with, UML.

The Unified Modeling Language is a standard language for specifying, Visualization, Constructing and documenting the artifacts of software system, as well as for business modeling and other non-software systems. 
The UML represents a collection of best engineering practices that have proven successful in the modeling of large and complex systems.

The UML is a very important part of developing objects oriented software and the software development process. The UML uses mostly graphical notations to express the design of software projects.

GOALS:
	The Primary goals in the design of the UML are as follows:
1.	Provide users a ready-to-use, expressive visual modeling Language so that they can develop and exchange meaningful models.
2.	Provide extendibility and specialization mechanisms to extend the core concepts.
3.	Be independent of particular programming languages and development process.
4.	Provide a formal basis for understanding the modelling   language.
5.	Encourage the growth of OO tools market.
6.	Support higher level development concepts such as collaborations, frameworks, patterns and components.
7.	Integrate best practices.


USE CASE DIAGRAM:
A use case diagram in the Unified Modeling Language (UML) is a type of behavioral diagram defined by and created from a Use-case analysis. Its purpose is to present a graphical overview of the functionality provided by a system in terms of actors, their goals (represented as use cases), and any dependencies between those use cases. The main purpose of a use case diagram is to show what system functions are performed for which actor. Roles of the actors in the system can be depicted.







CLASS DIAGRAM:
In software engineering, a class diagram in the Unified Modeling Language (UML) is a type of static structure diagram that describes the structure of a system by showing the system's classes, their attributes, operations (or methods), and the relationships among the classes. It explains which class contains information.

 












SEQUENCE DIAGRAM:
A sequence diagram in Unified Modeling Language (UML) is a kind of interaction diagram that shows how processes operate with one another and in what order. It is a construct of a Message Sequence Chart. Sequence diagrams are sometimes called event diagrams, event scenarios, and timing diagrams.









 
ACTIVITY DIAGRAM:
Activity diagrams are graphical representations of workflows of stepwise activities and actions with support for choice, iteration and concurrency. In the Unified Modeling Language, activity diagrams can be used to describe the business and operational step-by-step workflows of components in a system. An activity diagram shows the overall flow of control.

 
SYSTEM ENVIRONMENT
PYTHON:
Python is a general-purpose interpreted, interactive, object-oriented, and high-level programming language. An interpreted language, Python has a design philosophy that emphasizes code readability (notably using whitespace indentation to delimit code blocks rather than curly brackets or keywords), and a syntax that allows programmers to express concepts in fewer lines of code than might be used in languages such as C++or Java. It provides constructs that enable clear programming on both small and large scales. Python interpreters are available for many operating systems. CPython, the reference implementation of Python, is open source software and has a community-based development model, as do nearly all of its variant implementations. CPython is managed by the non-profit Python Software Foundation. Python features a dynamic type system and automatic memory management. It supports multiple programming paradigms, including object-oriented, imperative, functional and procedural, and has a large and comprehensive standard library
 
DJANGO
Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source.
Django's primary goal is to ease the creation of complex, database-driven websites. Django emphasizes reusabilityand "pluggability" of components, rapid development, and the principle of don't repeat yourself. Python is used throughout, even for settings files and data models. 

 
Django also provides an optional administrative create, read, update and delete interface that is generated dynamically through introspection and configured via admin models

 

 
CNN (Convolution Neural Network):
Neural networks are computing systems with interconnected nodes that work much like neurons in the human brain. Using algorithms, they can recognize hidden patterns and correlations in raw data, cluster and classify it, and over time continuously learn and improve. 
Neural Network works
A Neural Network consists of different layers as follows
Input Layer
Output Layer
Hidden Layers
The Layers are connected via nodes and nodes will have weight 
 
As the hidden layers increases the Deep Neural Network will be created. The Next Level of DNN is Machine Learning. Convolutional Neural Network (CNN) is a Deep Learning algorithm specially designed for working with Images and videos. It takes images as inputs, extracts and learns the features of the image, and classifies them based on the learned features. 
 
Simple Architecture of CNN:

 
 
CNN Works:
CNN has Layered concept that we need to understand.
 	Convolution,
 	ReLu,
 	Pooling and
 	Full Connectedness (Fully Connected Layer).
Convolution of an Image:
We use filters in CNN. Those filters normally represents features. The CNN will learn features from filters.
Image convolution needs to perform the following steps
–	Lineup the features and image
–	Multiply each image pixel by corresponding feature pixel
–	Add the values and find the sum
–	Divide the sum by total number of pixels in the feature
ReLu Layer:
Rectified Linear Unit (ReLU) transform function only activates a node if the input is above a certain quantity, while the input is below zero, the output is zero, but when the input rises above a certain threshold, it has a linear relationship with the dependent variable. 


Pooling Layer:
In this layer we shrink the image stack into a smaller size. Pooling is done after passing through the activation layer. We do this by implementing the following 4 steps:
–	Pick a window size (usually 2 or 3)
–	Pick a stride (usually 2)
–	Walk your window across your filtered images
–	From each window, take the maximum value
Full Connectedness (Fully Connected Layer):
The last layers in the network are fully connected, meaning that neurons of preceding layers are connected to every neuron in subsequent layers. 
This mimics high level reasoning where all possible pathways from the input to output are considered. Also, fully connected layer is the final layer where the classification actually happens. 


 
RNN (RECURRENT NEURAL NETWORK):
Recurrent neural networks (RNN) are a class of neural networks that are helpful in modeling sequence data. Derived from feedforward networks, RNNs exhibit similar behavior to how human brains function. Simply put: recurrent neural networks produce predictive results in sequential data that other algorithms can’t.
When do you need to use a RNN?
“Whenever there is a sequence of data and that temporal dynamics that connects the data is more important than the spatial content of each individual frame.”
How Recurrent Neural Networks Work:
To understand RNNs properly, you'll need a working  knowledge of "normal“ feed-forward neural networks and sequential data. Sequential data is basically just ordered data in which related things follow each other. Examples are financial data or the DNA sequence. The most popular type of sequential data is perhaps time series data, which is just a series of data points that are listed in time order.
RNN VS FEED-FORWARD NEURAL NETWORKS
 
RNN’s and feed-forward neural networks get their names from the way they channel information. In a feed-forward neural network, the information only moves in one direction — from the input layer, through the hidden layers, to the output layer. The information moves straight through the network. 
Feed-forward neural networks have no memory of the input they receive and are bad at predicting what’s coming next. Because a feed-forward network only considers the current input, it has no notion of order in time. It simply can’t remember anything about what happened in the past except its training.
In a RNN the information cycles through a loop. When it makes a decision, it considers the current input and also what it has learned from the inputs it received previously. The two images below illustrate the difference in information flow between a RNN and a feed-forward neural network.

 
Imagine you have a normal feed-forward neural network and give it the word "neuron" as an input and it processes the word character by character. By the time it reaches the character "r," it has already forgotten about "n," "e" and "u," which makes it almost impossible for this type of neural network to predict which character would come next.
A recurrent neural network, however, is able to remember those characters because of its internal memory. It produces output, copies that output and loops it back into the network.
Simply put: recurrent neural networks add the immediate past to the present.
Therefore, a RNN has two inputs: the present and the recent past. This is important because the sequence of data contains crucial information about what is coming next, which is why a RNN can do things other algorithms can’t.

Training Recurrent Neural Networks:
Recurrent Neural Networks use backpropagation algorithm for training, but it is applied for every timestamp. It is commonly known as Back-propagation Through Time (BTT).
WHAT IS BACKPROPAGATION?
Backpropagation (BP or backprop, for short) is known as a workhorse algorithm in machine learning. Backpropagation is used for calculating the gradient of an error function with respect to a neural network’s weights. The algorithm works its way backwards through the various layers of gradients to find the partial derivative of the errors with respect to the weights. Backprop then uses these weights to decrease error margins when training.

 

There are some issues with Back-propagation such as:
•	Vanishing Gradient
•	Exploding Gradient
EXPLODING GRADIENTS
Exploding gradients are when the algorithm, without much reason, assigns a stupidly high importance to the weights. Fortunately, this problem can be easily solved by truncating or squashing the gradients.
VANISHING GRADIENTS
Vanishing gradients occur when the values of a gradient are too small and the model stops learning or takes way too long as a result. This was a major problem in the 1990s and much harder to solve than the exploding gradients. Fortunately, it was solved through the concept of LSTM by Sepp Hochreiter and Juergen Schmidhuber.

What universal emotions can be detected and how are they recognized?

There are seven recognized universal emotions according to psychologist Dr. Paul Ekman. Below are the seven emotions and the commonly associated facial characteristics (facial expressions) that come with them. These characteristics are learned by deep learning, emotion detection technologies through large quantities of image training data.  
Happiness – Raised eyebrows and corners of the mouth 
Surprise – Raised eyebrows but not drawn together, raised upper eyelids, jaw dropped down
Anger – Eyebrows pulled down, eyes open wide, lips pursed tightly together
Fear – Jaw dropped open, lips pressed backwards horizontally, upper eyelids raised  
Sadness – frowned smile with lip corners pulled down, inner corners of the eyebrows pulled together, eyelids drooped.  
Disgust – Upper lip raised in a ‘u’ like shape, eyebrows lowered, wrinkling of the nose 
Contempt – Raised lip corner on one side of the face, this is the only signifier but it can also be accompanied by a smile or angry expression. 

 
Fig: Fear


 
Fig: Surprise




 
Fig: Sadness


 
Fig:Disgust




 
Fig:Smile












Fig: Neutral




 




 
Fig: Anger




 
SYSTEM TESTING
The purpose of testing is to discover errors. Testing is the process of trying to discover every conceivable fault or weakness in a work product. It provides a way to check the functionality of components, sub assemblies, assemblies and/or a finished product It is the process of exercising software with the intent of ensuring that the Software system meets its requirements and user expectations and does not fail in an unacceptable manner. There are various types of test. Each test type addresses a specific testing requirement.

TYPES OF TESTS:

Unit testing
Unit testing involves the design of test cases that validate that the internal program logic is functioning properly, and that program inputs produce valid outputs. All decision branches and internal code flow should be validated. It is the testing of individual software units of the application .it is done after the completion of an individual unit before integration. This is a structural testing, that relies on knowledge of its construction and is invasive. Unit tests perform basic tests at component level and test a specific business process, application, and/or system configuration. Unit tests ensure that each unique path of a business process performs accurately to the documented specifications and contains clearly defined inputs and expected results.
Integration testing
Integration tests are designed to test integrated software components to determine if they actually run as one program.  Testing is event driven and is more concerned with the basic outcome of screens or fields. Integration tests demonstrate that although the components were individually satisfaction, as shown by successfully unit testing, the combination of components is correct and consistent. Integration testing is specifically aimed at   exposing the problems that arise from the combination of components.




Functional test
Functional tests provide systematic demonstrations that functions tested are available as specified by the business and technical requirements, system documentation, and user manuals.
Functional testing is centered on the following items:
Valid Input               :  identified classes of valid input must be accepted.
Invalid Input             : identified classes of invalid input must be rejected.
Functions                  : identified functions must be exercised.
Output           	          : identified classes of application outputs must be exercised.
Systems/Procedures: interfacing systems or procedures must be invoked.
Organization and preparation of functional tests is focused on requirements, key functions, or special test cases. In addition, systematic coverage pertaining to identify Business process flows; data fields, predefined processes, and successive processes must be considered for testing. Before functional testing is complete, additional tests are identified and the effective value of current tests is determined.
System Test
System testing ensures that the entire integrated software system meets requirements. It tests a configuration to ensure known and predictable results. An example of system testing is the configuration oriented system integration test. System testing is based on process descriptions and flows, emphasizing pre-driven process links and integration points.
White Box Testing
White Box Testing is a testing in which in which the software tester has knowledge of the inner workings, structure and language of the software, or at least its purpose. It is purpose. It is used to test areas that cannot be reached from a black box level.



Black Box Testing
Black Box Testing is testing the software without any knowledge of the inner workings, structure or language of the module being tested. Black box tests, as most other kinds of tests, must be written from a definitive source document, such as specification or requirements document, such as specification or requirements document. It is a testing in which the software under test is treated, as a black box .you cannot “see” into it. The test provides inputs and responds to outputs without considering how the software works.
Unit Testing:
Unit testing is usually conducted as part of a combined code and unit test phase of the software lifecycle, although it is not uncommon for coding and unit testing to be conducted as two distinct phases.
Test strategy and approach
	Field testing will be performed manually and functional tests will be written in detail.

Test objectives
•	All field entries must work properly.
•	Pages must be activated from the identified link.
•	The entry screen, messages and responses must not be delayed.

Features to be tested
•	Verify that the entries are of the correct format
•	No duplicate entries should be allowed
•	All links should take the user to the correct page.

Integration Testing
Software integration testing is the incremental integration testing of two or more integrated software components on a single platform to produce failures caused by interface defects.
The task of the integration test is to check that components or software applications, e.g. components in a software system or – one step up – software applications at the company level – interact without error.
Test Results: All the test cases mentioned above passed successfully. No defects encountered.
Acceptance Testing
User Acceptance Testing is a critical phase of any project and requires significant participation by the end user. It also ensures that the system meets the functional requirements.
Test Results: All the test cases mentioned above passed successfully. No defects encountered.












 
SCREEN SHOTS
To implement this project we are using facial expression dataset which contains faces of seven emotions. See below screen shots of dataset
 
Each folder contains its related faces which can be seen in below happy folder with happy faces
 
In above screen we can see faces from each emotion and using above dataset we have implemented following modules
In title 1 we are applying PCA feature extraction algorithm to extract important features from dataset and then train CNN and RNN algorithm and then  compare accuracy of both algorithms
Below screen showing implementation of  title1
 
In above screen go inside title1 folder and then click on ‘run.bat’ file to get below screen
 
In above screen click on ‘Upload Facial Emotion Dataset’ button to upload dataset

 
In above screen selecting and uploading ‘X.txt.npy’ file which contains images of all emotion faces and then click on ‘Open’ button to load dataset and to get below screen
 
In above screen dataset loaded and now click on ‘Preprocess Dataset’ button to read all images and then apply feature extraction algorithm called PCA to read important features from dataset and to get below screen. This module may take 5 to 8 minutes time to give output so please wait till process complete like below screen
 
In above screen we can see dataset contains total 28709 images and before applying feature extraction algorithm total images features/pixels are 3072 and then after applying features reduces to 2352 as PCA remove unimportant pixels and used only important pixels/features. Now image data is ready and now click on ’Train CNN Algorithm’ button to train CNN with process image features
 
In above screen CNN accuracy is 48 and now click on ‘Train RNN Accuracy’ button to train dataset with RNN
 
In above screen RNN accuracy is 88% and now click on ‘Accuracy Comparison Graph’ to get below graph of both algorithms
 
In above screen x-axis represents epoch/iteration ad y-axis represents accuracy and in above graph orange line represents RNN accuracy and green line represents CNN accuracy and from above graph we can see with further epoch/iteration both algorithm accuracy get better and better and from above graph we can conclude that RNN is giving better result. Now click on ‘Predict Facial Expression’ button to upload new test image and the application predict emotion from it
 
In above screen selecting and uploading im38.png image and then click on ‘Open’ button to get below result
 
In above screen we got detected emotion as ‘happy’ and similarly you can upload any image and then predict emotion. So this is the output of TITLE 1.
 
CONCLUSION:
In this project, a novel approach has been proposed for facial expression recognition by incorporating a feed forward learning model with deep features. In contrast to back propagation approaches, the proposed model works in a feed forward fashion. It extracts the deep features from a neural model for high-level representation gain, without updating the weights iteratively, causing a reduction in computational time complexity. Extensive experimentations are performed with state-of-the-art techniques, traditional classifiers, and other deep neural models. .e proposed method has proven to be successful in evaluating. From the implementation, we can abserve the following points .
 1)The accuracy of CNN is 48% 
2)The accuracy of RNN is 88% 
From the above two points, we can conclude that RNN is best and  most suitable for  facial expression recognition system than compared with CNN.
 
REFERENCES:
[1] D. C. B. Silva, P. P. Cruz, A. M. Gutierrez, and ´ L. A. S. Avendaño, Applications of Human-Computer Interaction and Robotics Based on Artificial Intelligence, Editorial Digital del Tecnol´ogico de Monterrey, Monterrey, M´exico, 2020.
[2] C.-H. Chen, I.-J. Lee, and L.-Y. Lin, “Augmented reality-based self-facial modeling to promote the emotional expression and social skills of adolescents with autism spectrum disorders,” Research in Developmental Disabilities, vol. 36, pp. 396–403, 2015.
[3] S. Hickson, N. Dufour, A. Sud, V. Kwatra, and I. Essa, “Eyemotion: classifying facial expressions in VR using eyetracking cameras,” in Proceedings of the 2019 IEEE Winter Conference on Applications of Computer Vision (WACV), Waikoloa Village, HI, USA, January 2019.
[4] M. A. Assari and M. Rahmati, “Driver drowsiness detection using face expression recognition,” in Proceedings of the 2011 IEEE International Conference on Signal and Image Processing Applications (ICSIPA), November 2011.
[5] T. Bai, Y. F. Li, and X. Zhou, “Learning local appearances with sparse representation for robust and fast visual tracking,” IEEE Transactions on Cybernetics, vol. 45, no. 4, pp. 663–675, 2015.
[6] T. Chen and K. H. Yap, “Discriminative BoW framework for mobile landmark recognition,” IEEE Transactions on Cybernetics, vol. 44, no. 5, pp. 695–706, 2014.
[7] S. Prosen and H. S. Vitulic, “Emotion regulation and coping ´ strategies in pedagogical students with different attachment styles,” Japanese Psychological Research, vol. 58, no. 4, pp. 355–366, 2016.
[8] E. Jensen, M. Dale, P. J. Donnelly et al., “Toward automated feedback on teacher discourse to enhance teacher learning,” in Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems, pp. 1–13, Florence, Italy, April 2020.
[9] https://www.edureka.co/blog/convolutional-neural-network/
[10]https://www.edureka.co/blog/recurrent-neural-networks/
		


