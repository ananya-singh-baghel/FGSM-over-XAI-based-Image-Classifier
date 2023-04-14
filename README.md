# FGSM-over-XAI-based-Image-Classifier

Recent methods have concentrated on three distinct areas: 

(a) developing and improving explainability methods that help users better understand the inner workings of ML models and their outputs; 

(b) attacking interpreters in a white box setting; and (c) defining the precise properties and metrics of the explanations produced by models. 

However, they have not addressed attacks on explainable models in black box settings or security attributes and threat models pertinent to the cybersecurity area. 
To close this gap, they have investigated how susceptible a XAI LIME-based image classifier or SHAP unified framework 
is utilised to interpret the output of different types of models, such as neural networks, decision trees, and linear models,
is to FGSM adversarial assaults and evaluate the effect on the predictability of the model. LIME and SHAP work as valuable 
tools for understanding and interpreting the output of machine learning models. It can help to increase transparency, 
build trust in AI systems, and support decision-making in various fields, such as healthcare, finance, and criminal justice.

This project elaborates a conceptual understanding of XAI along with the importance of explainability by showing its importance 
through an implementation of FGSM attack on a CNN model.

# RESULTS 
The results of an adversarial attack on an XAI-based image classifier using FGSM can vary depending on the specific project 
and methodology used. However, some potential results and findings could include:
1. Successful generation of adversarial examples: Using the FGSM method, it is possible to generate adversarial examples 
   that are specifically designed to fool the XAI-based image classifier
2. Decreased accuracy of the XAI-based image classifier: When the XAI-based image classifier is exposed to the generated 
   adversarial examples, its accuracy can decrease significantly compared to its performance on regular examples.
3. Identification of vulnerabilities in the XAI-based image classifier: By analyzing the generated adversarial examples, 
   it may be possible to identify specific weaknesses or vulnerabilities in the XAI-based image classifier that make it 
   more susceptible to adversarial attacks.
4. Evaluation of the effectiveness of defense mechanisms: If defense mechanisms are implemented to protect the XAI-based image classifier
   against adversarial attacks, the project can evaluate the effectiveness of these mechanisms in mitigating the impact of FGSM-generated
   adversarial examples.
   
 We have analysed the algorithm proposed in [4] which suggests a unique algorithm for attacking explainable artificial intelligence 
 (XAI) methods in the context of cybersecurity. The approach is meant to take advantage of the shortcomings of XAI techniques, 
 which interpret judgements made by black box machine learning models.
 In contrast, we have applied a technique for attacking neural networks is the Fast Gradient Sign Method (FGSM) attack on an
 image classification model. It includes altering the input image in a way that maximises the loss function and is a form of 
 adversarial assault. The model misclassifies the image as a result.
 LIME and FGSM are combined to provide an explanation for the model's choices. The portions of the image that the model anticipated 
 would be significant are visualised using LIME to offer an explanation for the model's forecast. The cat's eyes and nose are the 
 primary characteristics that LIME recognised in this case.
 
 
The algorithm used in [14] consists of a novel detection method that uses Shapley Additive Explanations (SHAP) values computed for
the internal layers of a DNN classifier to discriminate between normal and adversarial inputs.
LIME provides a local, interpretable explanation for a machine learning model's predictions by perturbing the input data and observing 
how the model's output changes. In contrast, SHAP provides a more comprehensive understanding of a model's decision-making process by 
quantifying the contribution of each feature to the prediction. By implementing both the XAI techniques, LIME was identified to be faster and more flexible than SHAP.

LIME provides a local, interpretable explanation for a machine learning model's predictions by perturbing the input data and observing 
how the model's output changes. In contrast, SHAP provides a more comprehensive understanding of a model's decision-making process by 
quantifying the contribution of each feature to the prediction. By implementing both the XAI techniques, LIME was identified to be faster
and more flexible than SHAP.
