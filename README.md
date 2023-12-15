# Feature Engineered Naïve Bayes Classifier, Decision Tree, Random Forest, and Hybrid Ensemble Classifier for Sparse Data Learning

<strong>Abstract</strong><br>
Sparse data, where most features are either irrelevant or missing, presents a significant challenge in machine learning. Text Classification, Image Classification, Medical Diagnosis, and Fraud/Spam Detection are the major domains where we need to deal with sparse data. To address this, we introduce an innovative methodology that combines the simplicity of Naïve Bayes with the robustness of Decision Tree and Random Forest classifiers. Our approach begins by leveraging Naïve Bayes, a probabilistic algorithm, to handle sparse data efficiently. The Naïve Bayes component captures conditional probabilities, allowing it to model the basic structure of the sparse dataset. We then integrate these probabilities as features into the original dataset, enriching the feature space. Next, we employ Decision Tree and Random Forest classifiers on the enriched dataset. Decision Tree excels in capturing intricate data patterns, while Random Forest, an ensemble learning technique, ensures model stability and accuracy. Furthermore, we introduce an Ensemble Classifier, combining the strengths of Naïve Bayes and Random Forest predictions through a weighted average. This hybrid model compensates for individual model weaknesses, resulting in a more accurate and reliable classification. Our study rigorously evaluated four novel feature-engineered algorithms alongside existing classifiers, employing comprehensive metrics like classification accuracy, precision, recall, and f1-score, along with 10-fold cross-validation on 9 benchmark datasets from Kaggle, UCI (University of California, Irvine) machine learning repository, and sklearn datasets websites. The outcomes demonstrated the exceptional performance of our proposed methods in addressing real-life sparse data challenges. These techniques not only showcased impressive classification results but also demonstrated their capability to automatically discern crucial training data and identify effective attributes within noisy and complex datasets with substantial attribute dimensions.

<strong>Experiment Outine</strong><br>
Firstly, the traditional Naive Bayes, Decision Tree, and Random forest algorithms are trained with the non-feature-engineered datasets.  In addition to these existing algorithms, we also trained an Ensemble Learning Classifier. Then, their corresponding accuracy matrices (discussed in the evaluation matrices section below) were calculated. This set of experiments later served as the baseline accuracy that was targetted by our proposed algorithms to prove as the better alternatives.

Secondly, the selected datasets were feature-engineered by incorporating the Baysian probabilities extracted from the previously trained Naive Bayes Classifier. These enriched datasets were used for training a new set of models and will be referred to as the "processed" version of the algorithm. So, in total 8 models were trained(4 with non-enhanced dataset and 4 with enhanced dataset). Following the training of these models, their corresponding accuracy matrices were also calculated.

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

</body>
</html>
