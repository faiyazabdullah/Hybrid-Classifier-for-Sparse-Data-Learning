# Feature Engineered Naïve Bayes Classifier, Decision Tree, Random Forest, and Hybrid Ensemble Classifier for Sparse Data Learning

<strong>Experiment Outine</strong><br>
Firstly, the traditional Naive Bayes, Decision Tree, and Random forest algorithms are trained with the non-feature-engineered datasets.  In addition to these existing algorithms, we also trained an Ensemble Learning Classifier. Then, their corresponding accuracy matrices (discussed in the evaluation matrices section below) were calculated. This set of experiments later served as the baseline accuracy that was targetted by our proposed algorithms to prove as the better alternatives.

Secondly, the selected datasets were feature-engineered by incorporating the Bayesian probabilities extracted from the previously trained Naive Bayes Classifier. These enriched datasets were used for training a new set of models and will be referred to as the "processed" version of the algorithm. So, in total 8 models were trained (4 with non-enhanced dataset and 4 with enhanced dataset). Following the training of these models, their corresponding accuracy matrices were also calculated.

Finally, for better visualization of the model's performance graphs showing the accuracy across the different datasets were plotted for each classifier. This aids us in conducting a rigorous analysis of the consistency of the proposed algorithms across various classification objectives. 

<!DOCTYPE html>
<html>
<head>
</head>
<body>

  <h2>Dataset Information</h2>

  <table>
    <tr>
      <th>Serial</th>
      <th>Dataset Name</th>
      <th>Dataset URL</th>
    </tr>
    <tr>
      <td>1</td>
      <td>SMS Spam Collection Dataset</td>
      <td><a href="https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset" target="_blank">https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td>Ling Spam Dataset</td>
      <td><a href="https://www.kaggle.com/datasets/mandygu/lingspam-dataset" target="_blank">https://www.kaggle.com/datasets/mandygu/lingspam-dataset</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td>Sentiment140 dataset with 1.6 million tweets dataset</td>
      <td><a href="https://www.kaggle.com/datasets/kazanova/sentiment140" target="_blank">https://www.kaggle.com/datasets/kazanova/sentiment140</a></td>
    </tr>
    <tr>
      <td>4</td>
      <td>Breast Cancer Dataset</td>
      <td><a href="https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset" target="_blank">https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset</a></td>
    </tr>
    <tr>
      <td>5</td>
      <td>Load Digit Dataset</td>
      <td><a href="https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html" target="_blank">https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html</a></td>
    </tr>
  </table>

  <h2>Code</h2>
  <p>Here is a folder called <strong>notebooks</strong> which contains five notebooks of our experiment. We have shared five of our experimental notebooks publicly so that our readers can understand the workflow of our experiment and can use the codes if they need them. The rest of the experimental notebooks will be shared on request.</p>

  <h2>Contact</h2>
  <p>For inquiries or feedback, feel free to contact us at msayeedi212049@bscse.uiu.ac.bd.</p>


</body>
</html>
