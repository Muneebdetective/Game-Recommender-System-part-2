# Game-Recommender-System-part-2
This engine will use data on how much time users spent playing previous games, as well as their similarity to other video game players, to recommend new games that they might enjoy. The goal is to provide personalized game recommendations to users that are tailored to their individual gaming habits and preferences.
  
   
   *What is the problem you want to solve?
     The problem we want to solve is to develop a game recommendation engine for Steam users. This engine will use data on how much time users spent playing previous games, as well as their similarity to other video game players, to recommend new games that they might enjoy. The goal is to provide personalized game recommendations to users that are tailored to their individual gaming habits and preferences.
    *Which strategic goal is it linked to?
      This Game recommender engine is  linked to various strategic goals such as increasing user engagement, improving user retention, enhancing the user experience, and increasing revenue by promoting relevant games to users.


2. Problem Definition:
   * What specific output do you want to predict?
      The specific output that the code aims to predict is the list of recommended games for a user based on their previous game playing history and the similarity of their gaming preferences with other Steam users.


   * What input data do you have for the algorithm?
      The input data for the algorithm is Steam Game name, including the total amount of time each user has spent playing each game, as well as a list of other users who have played the same games.

   *What are the most relevant factors for predicting your specific output?
     The most relevant factors for predicting the recommended games for a user are the amount of time they have spent playing previous games and the similarity of their playtime to other users who have played the same games.

3. Relevant Method/Model:
    * What specific output do you want to predict?
       The specific output that the algorithm predicts is a list of recommended games for users.
     * What input data do you have for the algorithm?
        The input data for the algorithm is Steam Game name, including the total amount of time each user has spent playing each game, as well as a list of other users who have played the same games.
4. Performance Measurement:
    * How will you measure the accuracy of the predictions?
       The accuracy of the predictions can be measured using various metrics such as precision, recall, F1-score, or accuracy. In this case, we could use accuracy, which is the number of correctly predicted recommended games divided by the total number of recommended games.



      * What is the minimum level of accuracy you expect?
         The minimum level of accuracy expected can be set based on the project requirements and goals. It is important to have a realistic expectation of the accuracy based on the complexity of the data and the limitations of the algorithm.

5. Risks and Dependencies:
    * List any risks that may apply to this project and how those risks would be mitigated if encountered.
      One risk that may apply to this project is the availability and quality of the data. This could be mitigated by performing data cleaning, preprocessing, and augmentation to ensure the data is complete and accurate.
Another risk is the algorithm's performance and scalability, especially with a large dataset. This could be addressed by using efficient algorithms, optimizing the code, and using parallel processing techniques.
Finally, the risk of over fitting or under fitting the model could be mitigated by using appropriate machine learning techniques such as cross-validation, regularization, and hyper parameter tuning.
   * List any constraints that apply to this project:
      One constraint that may apply to this project is the computational resources available for processing the data and training the algorithm. This could limit the size of the dataset or the complexity of the algorithm used.
Another constraint could be the privacy and ethical considerations regarding the use of user data. It is important to ensure that the data is anonymized and that appropriate consent is obtained from the users.




6. Run performance checks:
    * Classification Accuracy: number of correct predictions vs number of predictions made: 
      Yes, classification accuracy is the number of correct predictions divided by the total number of predictions made.
    * Confusion Matrix: Similar to Accuracy, but more visual?
       Yes, a confusion matrix is a visual representation of the classification results, which includes the number of true positives, true negatives, false positives, and false negatives. It can provide more detailed information about the performance of the classifier than just the accuracy.
