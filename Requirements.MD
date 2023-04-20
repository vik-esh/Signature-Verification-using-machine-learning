Here are my requirements for the project:

1. Use the following machine learning algorithms to determine the authenticity of a signature:
        SVM - Random Forests
                 
2. Can use any ADDITIONAL python libraries or modules necessary for the machine learning algo and for feature extractions - but everything should be done in the
Jupyter Notebook

3. Add comments to the code. for e.g: where the algorith mmodels are initiated with how many neurons/networks and where the accuracies of results
are determined and saved etc. Important: add comments where evaluation metrics are used like precision, recall, accuracy and f1 score.

4. After authenticating a signature, create a Results folder, containing a CSV file(ComparingModels.CSV) to compare each models accuracies. It should contains values 
in this format:

        Testing signature <path of signature image>
        CNN - SVM - Random Forests
        93% - 87% - 97%
        
         Note: (i) Values can be in terms of percentage or decimals
              (ii) ComparingModels.CSV values should be overriden each time a person test a new signature with new values 
              
5. Use the real and forged datasets only(found within this repo) to train and test the models. The format of each image is as follows:

        Images are stored in the format : XXXZZZ_YYY.png
        XXX denotes id of the person who has signed on the document(eg: 001)
        ZZZ denotes the id of the person to whom the sign belongs in actual(eg: 001)
        YYY deontes the n'th no.of attempt

        Note: Each datasets comprise of 15 genuine and 15 forged signatures. There have been 5 total attempts for each of the 15 genuine and forged signatures.

6. Use and modify the already done template to add the requirements (CNN - Signature verification using machine learning.ipynb) to implement the rest of the algorithms. Everything should be in one single .ipynb file
