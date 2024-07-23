Traditional username-based authentication, eventhough common and easily accessible, can be exploited. 
While biometric solutions such as facial recognition, fingerprints, and iris scans offer strong security, they often require specialized hardware and tools, which can be both expensive and cumbersome. 
Therefore, it is crucial to explore additional methods of safeguarding our data that are cost-effective, non-intrusive, and widely accessible. 

This project explores an alternative approach to user verification using mouse dynamics. 
By analyzing time series data of mouse coordinates, we developed a deep learning model to classify users based on their unique mouse movement patterns. 
We employed various architectures, including InceptionTime, XceptionTimePlus, LSTM_FCNPlus, and a custom LSTM-based model, to compare their performance in user verification tasks. 

The models were trained and evaluated using a dataset consisting of mouse dynamics data from five users. 
The best-performing model achieved an accuracy of slightly less than 75% for the five-class classification problem.
The results demonstrate the potential of mouse dynamics as a complementary security measure, particularly for software companies handling sensitive data and online examination invigilation.
