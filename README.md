##SentimentModel

Model generated with Mahout for calculating the sentiment in tweets.
This model was generated with 3 Millions of tweets.

For the training 80% of the tweets was used, remaining 20% was used for testing the model.

##Accuracy

	=======================================================
	Summary
	-------------------------------------------------------
	Correctly Classified Instances          :     459066	   85,7292%
	Incorrectly Classified Instances        :      76418	   14,2708%
	Total Classified Instances              :     535484

	=======================================================
	Confusion Matrix
	-------------------------------------------------------
	a    	b    	<--Classified as
	207805	56028	 |  263833	a     = Negative
	20390	251261	 |  271651	b     = Positive

	=======================================================
	Statistics
	-------------------------------------------------------
	Kappa                                      -0,7059
	Accuracy                                   85,7292%
	Reliability                                 57,086%
	Reliability (standard deviation)            0,4991


##Manual Classification

The manual classification of the tweets was done based in emoticons.

###Positive Tweets

Any tweet with the following emoticon was considered Positive:

	:)
	:-)
    :]
    =)
    ;)
    ;-)	
    :-D
    :D
    =D
    :-P
    :P
    :-p
    :p
    =P
    =p
    ^_^
  
###Negative Tweets

	:-(
    :(
    :[
    (TT)
    TT
    =(
    >:(
    >:-(
    :-/
    :\\
    :-\\
    ;(


  






