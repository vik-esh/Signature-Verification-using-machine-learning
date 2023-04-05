Here are my requirements for the project:

1. Use the following mmachine learning algorithms to determine the authenticity of a signature
                 CNN - SVM - Random Forests
                 
2. Can use any ADDITIONAL python libraries or modules necessary for the machine learning algo and for feature extractions - but everything should be done in the
Jupyter Notebook

3. Add comments to the code. for e.g: comment where the CNN, SVM, Random Forests model are initiated with how many neurons/networks and where the accuracies of results
are determined and saved etc. Important: add comments where evaluation metrics are used like precision, recall, accuracy and f1 score.

4. Add a validation method to validate user input for the following criteria:
      - person's id should be only 001 to 015, else display error message to try again
      - path of signature image should exist in the format: C:\Users\Vikesh\Desktop\Dataset2\real\001001_002.png , else display error message to try again

5. After authenticating a signature, create a Results folder, containing a CSV file(ComparingModels.CSV) to compare each models accuracies. It should contains values 
in this format:

        Testing signature <path of signature image>
        CNN - SVM - Random Forests
        93% - 87% - 97%
        
         Note: (i) The values can be in terms of percentage or decimals.
              (ii) ComparingModels.CSV values should be overriden each time a person test a new signature with new values 
              
6. Use the real and forged datasets only(found within this repo) to train and test the models. The format of each image is as follows:

      Images are stored in the format : XXXZZZ_YYY.png
      XXX denotes id of the person who has signed on the document(eg: 001)
      ZZZ denotes the id of the person to whom the sign belongs in actual(eg: 001)
      YYY deontes the n'th no.of attempt
      
      Note: Each datasets comprise of 15 genuine and 15 forged signatures. There have been 5 total attempts for each of the 15 genuine and forged signatures.

7. Use the already done template to add the requirements.
