# DeepLearning-AlphabetCharity

Problem: In this project I'm utilizing Deep Learning Neural Networks in order to help Alphabet Soup create an algorithm in which they will be able to predict whether or not 
applicants will be successful for requesting funding.  In this project, I received a list of 34,000 organization that have requested funding over the years.  


Data Metrics:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

Preprocessing: 
- utilized StandardScaler() to standardize the data and fit the data
- utilized pd.get_dummies() to turn categorical data into numerical data

Execution of Model:
- utilized TenserFlow to create Keras models 

Models:

Model 1: "sequential_1"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense_3 (Dense)             (None, 8)                 352       
                                                                 
 dense_4 (Dense)             (None, 5)                 45        
                                                                 
 dense_5 (Dense)             (None, 1)                 6         
                                                                 
=================================================================
Total params: 403
Trainable params: 403

Model 2 : "sequential_2"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense_6 (Dense)             (None, 8)                 352       
                                                                 
 dense_7 (Dense)             (None, 5)                 45        
                                                                 
 dense_8 (Dense)             (None, 5)                 30        
                                                                 
 dense_9 (Dense)             (None, 1)                 6         
                                                                 
=================================================================
Total params: 433
Trainable params: 433
Non-trainable params: 0

Model 3: "sequential_3"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense_10 (Dense)            (None, 8)                 352       
                                                                 
 dense_11 (Dense)            (None, 5)                 45        
                                                                 
 dense_12 (Dense)            (None, 5)                 30        
                                                                 
 dense_13 (Dense)            (None, 1)                 6         
                                                                 
=================================================================
Total params: 433
Trainable params: 433
Non-trainable params: 0
