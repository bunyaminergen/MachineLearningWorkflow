# Adversarial Attacks

## What is Adversarial Attack

Adversarial attack refers to the deliberate manipulation of input data, 
typically in the context of machine learning models, with the intention of causing the model 
to misclassify or produce erroneous results.

Adversarial attack refers to a technique used to deliberately mislead or confuse a machine learning model, by presenting it with carefully crafted input samples. These inputs, called adversarial examples, are specifically designed to cause the model to make incorrect predictions, even though they are similar to normal inputs in most respects. The goal of adversarial attacks is to evaluate the robustness and security of machine learning systems and highlight their limitations.

- Adversarial attacks are a type of security threat that can affect machine learning models.
- These attacks involve manipulating input data in a way that causes the model to make mistakes or produce inaccurate results.
- Adversarial attacks can be targeted or random and can occur at different stages of the model's lifecycle, from training to deployment.
- Adversarial attacks can be carried out in various forms, such as adding imperceptible noise to input data or modifying pixels in images.
- Adversarial attacks are of concern because they can potentially compromise the security and reliability of machine learning applications, especially those used in critical domains such as healthcare or autonomous driving.
- Researchers and practitioners are actively working on developing defenses against adversarial attacks, such as robust models and detection mechanisms.

## Logic of Adversarial Attacks


## History of Adversarial Attack

Adversarial attacks have a long history in the field of computer security and cryptography. Some of the earliest adversarial attacks were performed against encryption systems, where the adversary would try to manipulate the encrypted message to recover the plaintext or to cause the decryption system to fail.

In the field of machine learning, adversarial attacks have been a research topic for several decades. The earliest studies on adversarial attacks in the context of machine learning focused on the development of algorithms for generating adversarial examples and for defending against adversarial attacks. 

### Chronological Order

- *In* **2004**,
Nilesh Dalvi and others noted that linear classifiers used in spam filters could be defeated by simple "evasion attacks" as spammers inserted "good words" into their spam emails. [[paper]](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md)
- *In* **2006**, 
Marco Barreno and others published "Can Machine Learning Be Secure?", outlining a broad taxonomy of attacks. [[paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md)]
- *Around* **2007**, 
some spammers added random noise to fuzz words within "image spam" in order to defeat OCR-based filters. [[paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md)]
- *As late as* **2013**,
many researchers continued to hope that non-linear classifiers (such as support vector machines and neural networks ) might be robust to adversaries, until Battista Biggio and others demonstrated the first gradient-based attacks on such machine-learning models (2012 -2013) [[paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md)] - [[paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md)]
- *Starting in* **2014**, 
Some of the earliest works in this area include the seminal paper by Szegedy et al. on "Intriguing properties of neural networks" in 2013, which demonstrated that neural networks are vulnerable to adversarial examples, using a gradient-based attack to craft adversarial perturbations. [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
- *In* **2014**, 
the paper by Goodfellow et al. on "Explaining and Harnessing Adversarial Examples" , which introduced the fast gradient sign method (FGSM) for generating adversarial examples. [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md)]
- *In* **2016**,
The paper "Adversarial examples in the physical world" by Kurakin, Goodfellow, and Bengio is a seminal work in the field of adversarial machine learning. It was published in 2016 and is one of the first works to explore the concept of adversarial examples in the physical world. 
The paper investigates the vulnerability of machine learning models to adversarial examples in real-world physical environments. The authors show that machine learning models can be easily fooled by adversarial examples in the physical world, and they propose a number of techniques for creating such examples, such as adding small perturbations to input images or using fast gradient sign methods to generate adversarial examples. 
The paper also explores the implications of adversarial examples in the physical world for various real-world applications, such as computer vision and biometric authentication, and highlights the need for more robust machine learning models that can better resist these attacks. 
Overall, the paper is an important contribution to the field of adversarial machine learning and provides a valuable foundation for further research in this area. [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
- *In* **2018**,
Battista Biggio and Fabio Roli are well-known researchers in the field of machine learning security and privacy. The paper "Wild Patterns: Ten Years after the Rise of Adversarial Machine Learning" was published in December 2018 and reflects on the state of the art in the field of adversarial machine learning ten years after the discovery of adversarial examples.
The paper provides an overview of the various attack and defense techniques that have been developed over the past decade and highlights some of the key challenges and open questions in the field. It also discusses the implications of adversarial machine learning for the security and privacy of machine learning models and systems. Overall, the paper provides a comprehensive overview of the current state of the field and the direction of future research. [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
- *In* **2019**,
The paper "Algorithmic Decision-Making in AVs: Understanding Ethical and Technical Concerns for Smart Cities" by Lim and Taeihagh addresses the topic of algorithmic decision-making in autonomous vehicles (AVs). In this paper, the authors discuss the potential impact of algorithmic decision-making on smart cities and the ethical and technical concerns associated with the use of AVs. 
Adversarial attacks are one of the technical concerns mentioned in the paper. Adversarial attacks refer to the manipulation of inputs to a machine learning system in order to cause it to make incorrect decisions. The authors note that AVs, which rely on machine learning algorithms for decision-making, are vulnerable to adversarial attacks and that these attacks can have significant consequences for the safety and reliability of AVs. 
Therefore, the paper highlights the importance of considering adversarial attacks as a potential threat when designing and deploying machine learning algorithms for AVs, and it discusses the need for methods to detect and defend against such attacks. Overall, the paper provides valuable insights into the ethical and technical challenges associated with algorithmic decision-making in AVs and the potential impact of adversarial attacks. [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
- *In* **2019**, 
Google Brain's Nicholas Frosst point out that it is much easier to make self-driving cars miss stop signs by physically removing the sign itself, rather than creating adversarial examples. Frosst also believes that the adversarial machine learning community incorrectly assumes models trained on a certain data distribution will also perform well on a completely different data distribution. He suggests that a new approach to machine learning should be explored, and is currently working on a unique neural network that has characteristics more similar to human perception than state of the art approaches. [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
- ***Present,***
While adversarial machine learning continues to be heavily rooted in academia, large tech companies such as Google, Microsoft, and IBM have begun curating documentation and open source code bases to allow others to concretely assess the robustness of machine learning models and minimize the risk of adversarial attacks. [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ] - [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ] - [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
In recent years, the research on adversarial attacks in the context of machine learning has become more active, driven by the increasing use of machine learning in security-sensitive applications, such as computer vision, speech recognition, and autonomous systems. The rise of deep learning has also fueled interest in adversarial attacks, as deep learning models have been shown to be more vulnerable to adversarial examples compared to traditional machine learning models.

## Methods of Adversarial Attacks

There are several methods to perform adversarial attacks, some of the most common ones include:

1. Gradient-based methods: This involves computing the gradient of the model's loss with respect to the input and then perturbing the input in the direction of the gradient that maximizes the loss.
2. Evolutionary methods: This involves searching for adversarial examples using a population-based optimization algorithm, such as genetic algorithms or particle swarm optimization.
3. Decision-based methods: This involves generating adversarial examples by making small, targeted perturbations to the input that cause the model to change its prediction.
4. Black-box methods: This involves generating adversarial examples without access to the model's internal workings, typically by using gradient estimates obtained through queries to the model.

It's important to note that adversarial attacks can have serious consequences and can be used maliciously, so their use should be carefully considered and responsibly conducted within ethical guidelines.

## Most Common Adversarial Attacks

In adversarial machine learning, there are several threat models that are commonly used to evaluate the robustness of a machine learning model. Some of the most common threat models include:

1. Fast Gradient Sign Method (FGSM)
2. Projected Gradient Descent (PGD)
3. Carlini and Wagner (C&W) attack
4. Adversarial patch attack
5. Targeted attacks: In a targeted attack, the adversary has a specific target class in mind and tries to manipulate the input data in such a way that the model predicts the target class, even though the input data is not representative of that class.
6. Non-targeted attacks: In a non-targeted attack, the adversary tries to manipulate the input data in such a way that the model predicts any class other than the true class.
7. Poisoning attacks: Poisoning attacks involve the adversary adding carefully crafted malicious samples to the training data to manipulate the learned model parameters.
8. Evasion attacks: In an evasion attack, the adversary manipulates the input data at test time to cause the model to make an incorrect prediction.
9. Data poisoning attacks: In data poisoning attacks, the adversary manipulates the training data to compromise the accuracy of the learned model.
10. Backdoor attacks: In a backdoor attack, the adversary adds a hidden trigger to the input data that causes the model to make an incorrect prediction when the trigger is present.
11. Model inversion attacks: In a model inversion attack, the adversary uses the learned model to recover sensitive information, such as training data or model parameters, from the model predictions.
12. Byzantine attacks
13. Model extraction

These threat models are commonly used to evaluate the robustness of machine learning models and to identify potential weaknesses that can be exploited by adversaries.

## How to perform an Adversarial Attack

Adversarial attacks are performed by adding small, carefully crafted perturbations to input data, in order to cause a machine learning model to make incorrect predictions. Here are the general steps to perform an adversarial attack:

1. Choose a model: Select the machine learning model you want to attack.
2. Select an input data: Choose a sample input data that you want to attack, for example, an image or a text.
3. Choose a loss function: Define a loss function that measures the difference between the true label and the predicted label of the input data.
4. Generate the adversarial perturbation: Compute the gradient of the loss function with respect to the input data and use an optimization algorithm, such as gradient descent, to generate a perturbation that maximizes the loss.
5. Evaluate the attack: Verify that the model makes incorrect predictions for the adversarial input data.

Note that adversarial attacks are often used to evaluate the robustness and security of machine learning models, so it's important to conduct them in an ethical and responsible manner.

## Examples of Adversarial Attack

- **Adversarial Attacks on SMS Spam Detectors by Lowri Williams**
    
    [📱Adversarial Attacks on SMS Spam Detectors](https://towardsdatascience.com/adversarial-attacks-on-sms-spam-detectors-12b16f1e748e)
    
    [SMS_Adversarial_Machine_Learning/Adversarial_Machine_Learning.ipynb at master · LowriWilliams/SMS_Adversarial_Machine_Learning](https://github.com/LowriWilliams/SMS_Adversarial_Machine_Learning/blob/master/Adversarial_Machine_Learning.ipynb)
    
- **Adversarial Email Generation against Spam Detection Models through Feature Perturbation by Qi Cheng, Anyi Xu, Xiangyang Li, Leah Ding**
    
    [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
    
- **NLP Deep Dive: 5 types of adversarial attacks on large language models by Rachael Tatman**
    
    [https://www.youtube.com/watch?v=cwGXeUyvaUU](https://www.youtube.com/watch?v=cwGXeUyvaUU)
    
- **TextAttack: A Framework for Data Augmentation and Adversarial Training in NLP by Elvis Saravia**
    
    [https://www.youtube.com/watch?v=VpLAjOQHaLU](https://www.youtube.com/watch?v=VpLAjOQHaLU)
    
- **Adversarial Attacks on Deep Leaning Models in NLP by Sakshi Shukla**
    
    [https://www.youtube.com/watch?v=JACkw_5zG2Y](https://www.youtube.com/watch?v=JACkw_5zG2Y)
    
- **Generating adversarial patches against YOLOv2 by Simen Thys, Wiebe Van Ranst, and Toon Goedemé**
    
    [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ] - [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
    
    [https://www.youtube.com/watch?v=MIbFvK2S9g8](https://www.youtube.com/watch?v=MIbFvK2S9g8)
    
- **Model Hacking in the Real World (Tesla's former Mobileye system) by McAfee**
    
    McAfee attacked Tesla's former Mobileye system, fooling it into driving 50 mph over the speed limit, simply by adding a two-inch strip of black tape to a speed limit sign. [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
    
    [https://www.youtube.com/watch?v=4uGV_fRj0UA](https://www.youtube.com/watch?v=4uGV_fRj0UA)
    
- **Why deep-learning AIs are so easy to fool by Douglas Heaven**
    
    [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ] - [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
    
- **Robust Physical-World Attacks on Deep Learning Visual Classification by Kevin Eykholt and friends**
    
    [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ] 
    
- **Slight Street Sign Modifications Can Completely Fool Machine Learning Algorithms by Evan Ackerman**
    
    [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]
    
- **Adversarial Patch by Tom B. Brown and friends**
    
    [ [paper](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ] 
    
    [https://www.youtube.com/watch?v=i1sp4X57TL4](https://www.youtube.com/watch?v=i1sp4X57TL4)
    

## Codes

### Adversarial Robustness Toolbox (ART) Library Example

Adversarial Robustness Toolbox (ART) is a Python library for Machine Learning Security. ART is hosted by the Linux Foundation AI & Data Foundation (LF AI & Data). ART provides tools that enable developers and researchers to defend and evaluate Machine Learning models and applications against the adversarial threats of Evasion, Poisoning, Extraction, and Inference. ART supports all popular machine learning frameworks (TensorFlow, Keras, PyTorch, MXNet, scikit-learn, XGBoost, LightGBM, CatBoost, GPy, etc.), all data types (images, tables, audio, video, etc.) and machine learning tasks (classification, object detection, speech recognition, generation, certification, etc.).

[adversarial-robustness-toolbox/get_started_scikit_learn.py at main · Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox/blob/main/examples/get_started_scikit_learn.py)

[Trusted-AI](https://github.com/Trusted-AI)

```python
"""
The script demonstrates a simple example of using ART with scikit-learn. The example train a small model on the MNIST
dataset and creates adversarial examples using the Fast Gradient Sign Method. Here we use the ART classifier to train
the model, it would also be possible to provide a pretrained model to the ART classifier.
The parameters are chosen for reduced computational requirements of the script and not optimised for accuracy.
"""
from sklearn.svm import SVC
import numpy as np

from art.attacks.evasion import FastGradientMethod
from art.estimators.classification import SklearnClassifier
from art.utils import load_mnist

# Step 1: Load the MNIST dataset

(x_train, y_train), (x_test, y_test), min_pixel_value, max_pixel_value = load_mnist()

# Step 1a: Flatten dataset

nb_samples_train = x_train.shape[0]
nb_samples_test = x_test.shape[0]
x_train = x_train.reshape((nb_samples_train, 28 * 28))
x_test = x_test.reshape((nb_samples_test, 28 * 28))

# Step 2: Create the model

model = SVC(C=1.0, kernel="rbf")

# Step 3: Create the ART classifier

classifier = SklearnClassifier(model=model, clip_values=(min_pixel_value, max_pixel_value))

# Step 4: Train the ART classifier

classifier.fit(x_train, y_train)

# Step 5: Evaluate the ART classifier on benign test examples

predictions = classifier.predict(x_test)
accuracy = np.sum(np.argmax(predictions, axis=1) == np.argmax(y_test, axis=1)) / len(y_test)
print("Accuracy on benign test examples: {}%".format(accuracy * 100))

# Step 6: Generate adversarial test examples
attack = FastGradientMethod(estimator=classifier, eps=0.2)
x_test_adv = attack.generate(x=x_test)

# Step 7: Evaluate the ART classifier on adversarial test examples

predictions = classifier.predict(x_test_adv)
accuracy = np.sum(np.argmax(predictions, axis=1) == np.argmax(y_test, axis=1)) / len(y_test)
print("Accuracy on adversarial test examples: {}%".format(accuracy * 100))

# run time with google colab: 37m 57s

"""
clean accuracy:  93.8 %
robust accuracy for perturbations with
  Linf norm ≤ 0.0   : 93.8 %
  Linf norm ≤ 0.0002: 87.5 %
  Linf norm ≤ 0.0005: 81.2 %
  Linf norm ≤ 0.0008: 50.0 %
  Linf norm ≤ 0.001 : 37.5 %
  Linf norm ≤ 0.0015: 18.8 %
  Linf norm ≤ 0.002 :  6.2 %
  Linf norm ≤ 0.003 :  0.0 %
  Linf norm ≤ 0.01  :  0.0 %
  Linf norm ≤ 0.1   :  0.0 %
  Linf norm ≤ 0.3   :  0.0 %
  Linf norm ≤ 0.5   :  0.0 %
  Linf norm ≤ 1.0   :  0.0 %

we can also manually check this:

robust accuracy for perturbations with
  Linf norm ≤ 0.0   : 93.8 %
    perturbation sizes:
     [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
  Linf norm ≤ 0.0002: 87.5 %
    perturbation sizes:
     [0.0002 0.0002 0.0002 0.0002 0.0002 0.0002 0.0002 0.0002 0.0002 0.0002
     0.0002 0.0002 0.0002 0.0002 0.0002 0.0002]
  Linf norm ≤ 0.0005: 81.2 %
    perturbation sizes:
     [0.00050002 0.00050002 0.00050002 0.00050002 0.00050002 0.00050002
     0.00050002 0.00050002 0.00050002 0.00050002 0.00050002 0.00050002
     0.00050002 0.00050002 0.00050002 0.00050002]
  Linf norm ≤ 0.0008: 50.0 %
    perturbation sizes:
     [0.00080001 0.00080001 0.00080001 0.00080001 0.00080001 0.00080001
     0.00080001 0.00080001 0.00080001 0.00080001 0.00080001 0.00080001
     0.00080001 0.00080001 0.00080001 0.00080001]
  Linf norm ≤ 0.001 : 37.5 %
    perturbation sizes:
     [0.001 0.001 0.001 0.001 0.001 0.001 0.001 0.001 0.001 0.001 0.001 0.001
     0.001 0.001 0.001 0.001]
  Linf norm ≤ 0.0015: 18.8 %
    perturbation sizes:
     [0.00150001 0.00150001 0.00150001 0.00150001 0.00150001 0.00150001
     0.00150001 0.00150001 0.00150001 0.00150001 0.00150001 0.00150001
     0.00150001 0.00150001 0.00150001 0.00150001]
  Linf norm ≤ 0.002 :  6.2 %
    perturbation sizes:
     [0.002 0.002 0.002 0.002 0.002 0.002 0.002 0.002 0.002 0.002 0.002 0.002
     0.002 0.002 0.002 0.002]
  Linf norm ≤ 0.003 :  0.0 %
    perturbation sizes:
     [0.00300002 0.00300002 0.00300002 0.00300002 0.00300002 0.00300002
     0.00300002 0.00300002 0.00300002 0.00300002 0.00300002 0.00300002
     0.00300002 0.00300002 0.00300002 0.00300002]
"""
```

### Foolbox Library Example

Foolbox is a Python toolbox to create adversarial examples that fool neural networks. It comes with support for many frameworks to build models including TensorFlow PyTorch Keras JAX MXNet Theano Lasagne and it is easy to extend to other frameworks.

[foolbox/single_attack_pytorch_resnet18.py at master · bethgelab/foolbox](https://github.com/bethgelab/foolbox/blob/master/examples/single_attack_pytorch_resnet18.py)

```python
#!/usr/bin/env python3
"""
A simple example that demonstrates how to run a single attack against
a PyTorch ResNet-18 model for different epsilons and how to then report
the robust accuracy.
"""
import torchvision.models as models
import eagerpy as ep
from foolbox import PyTorchModel, accuracy, samples
from foolbox.attacks import LinfPGD

def main() -> None:
    # instantiate a model (could also be a TensorFlow or JAX model)
    model = models.resnet18(pretrained=True).eval()
    preprocessing = dict(mean=[0.485, 0.456, 0.406], std=[0.229, 0.224, 0.225], axis=-3)
    fmodel = PyTorchModel(model, bounds=(0, 1), preprocessing=preprocessing)

    # get data and test the model
    # wrapping the tensors with ep.astensors is optional, but it allows
    # us to work with EagerPy tensors in the following
    images, labels = ep.astensors(*samples(fmodel, dataset="imagenet", batchsize=16))
    clean_acc = accuracy(fmodel, images, labels)
    print(f"clean accuracy:  {clean_acc * 100:.1f} %")

    # apply the attack
    attack = LinfPGD()
    epsilons = [
        0.0,
        0.0002,
        0.0005,
        0.0008,
        0.001,
        0.0015,
        0.002,
        0.003,
        0.01,
        0.1,
        0.3,
        0.5,
        1.0,
    ]
    raw_advs, clipped_advs, success = attack(fmodel, images, labels, epsilons=epsilons)

    # calculate and report the robust accuracy (the accuracy of the model when
    # it is attacked)
    robust_accuracy = 1 - success.float32().mean(axis=-1)
    print("robust accuracy for perturbations with")
    for eps, acc in zip(epsilons, robust_accuracy):
        print(f"  Linf norm ≤ {eps:<6}: {acc.item() * 100:4.1f} %")

    # we can also manually check this
    # we will use the clipped advs instead of the raw advs, otherwise
    # we would need to check if the perturbation sizes are actually
    # within the specified epsilon bound
    print()
    print("we can also manually check this:")
    print()
    print("robust accuracy for perturbations with")
    for eps, advs_ in zip(epsilons, clipped_advs):
        acc2 = accuracy(fmodel, advs_, labels)
        print(f"  Linf norm ≤ {eps:<6}: {acc2 * 100:4.1f} %")
        print("    perturbation sizes:")
        perturbation_sizes = (advs_ - images).norms.linf(axis=(1, 2, 3)).numpy()
        print("    ", str(perturbation_sizes).replace("\n", "\n" + "    "))
        if acc2 == 0:
            break

if __name__ == "__main__":
    main()
```

### Cleverhans Library Example

You can find codes in this notebook of the cleverhans library creating an adversarial patch. [ [page](Adversarial%20Attacks%202cad7afd70fa49239c48e8505b2764e5.md) ]

[cleverhans/AdversarialPatch.ipynb at master · cleverhans-lab/cleverhans](https://github.com/cleverhans-lab/cleverhans/blob/master/cleverhans_v3.1.0/examples/adversarial_patch/AdversarialPatch.ipynb)

### From me

If I have a study that includes Adversarial Attack or Adversarial Patch, I will share it both here and on Github.

## Papers

- Adversarial Classification

    [Adversarial Classification](MachineLearningWorkflow/MachineLearningWorkflow/docs/AdversarialClassification.pdf)
    
- Can Machine Learning Be Secure
    
    [https://people.eecs.berkeley.edu/~adj/publications/paper-files/asiaccs06.pdf](https://people.eecs.berkeley.edu/~adj/publications/paper-files/asiaccs06.pdf)

- Filtering Image Spam with Near-Duplicate Detection
    
    [https://www.cs.princeton.edu/cass/papers/spam_ceas07.pdf](https://www.cs.princeton.edu/cass/papers/spam_ceas07.pdf)
    

- Poisoning Attacks against Support Vector Machines
    
    [https://arxiv.org/pdf/1206.6389v3.pdf](https://arxiv.org/pdf/1206.6389v3.pdf)
    
- Evasion attacks against machine learning at test time
    
    [https://arxiv.org/pdf/1708.06131.pdf](https://arxiv.org/pdf/1708.06131.pdf)
    
- Intriguing properties of neural networks
    
    [https://arxiv.org/pdf/1312.6199.pdf](https://arxiv.org/pdf/1312.6199.pdf)
    
- Explaining and Harnessing Adversarial Examples
    
    [https://arxiv.org/pdf/1412.6572.pdf](https://arxiv.org/pdf/1412.6572.pdf)
    
- Adversarial examples in the physical world
    
    [https://arxiv.org/pdf/1607.02533.pdf](https://arxiv.org/pdf/1607.02533.pdf)
    
- Wild Patterns: Ten Years After the Rise of Adversarial Machine Learning
    
    [https://arxiv.org/pdf/1712.03141.pdf](https://arxiv.org/pdf/1712.03141.pdf)
    
- Algorithmic Decision-Making in AVs: Understanding Ethical and Technical Concerns for Smart Cities
    
    [https://arxiv.org/ftp/arxiv/papers/1910/1910.13122.pdf](https://arxiv.org/ftp/arxiv/papers/1910/1910.13122.pdf)
    
- Adversarial Email Generation against Spam Detection Models through Feature Perturbation
    
    [https://isi.jhu.edu/wp-content/uploads/2022/04/Adversarial_Attacks_Against_Machine_Learning_Based_SpamFilters__IEEE.pdf](https://isi.jhu.edu/wp-content/uploads/2022/04/Adversarial_Attacks_Against_Machine_Learning_Based_SpamFilters__IEEE.pdf)
    
- Fooling automated surveillance cameras: adversarial patches to attack person detection
    
    [https://arxiv.org/pdf/1904.08653.pdf](https://arxiv.org/pdf/1904.08653.pdf)
    
- Why deep-learning AIs are so easy to fool
    
    [https://www.nature.com/articles/d41586-019-03013-5.pdf](https://www.nature.com/articles/d41586-019-03013-5.pdf)
    
- Robust Physical-World Attacks on Deep Learning Visual Classification
    
    [https://arxiv.org/pdf/1707.08945.pdf](https://arxiv.org/pdf/1707.08945.pdf)
    
- Adversarial Patch
    
    [https://arxiv.org/pdf/1712.09665.pdf](https://arxiv.org/pdf/1712.09665.pdf)
    

## Pages

[Adversarial machine learning - Wikipedia](https://en.wikipedia.org/wiki/Adversarial_machine_learning#cite_note-9)

[Google Brain's Nicholas Frosst on Adversarial Examples and Emotional Responses | Synced](https://syncedreview.com/2019/11/21/google-brains-nicholas-frosst-on-adversarial-examples-and-emotional-responses/)

[Responsible AI practices - Google AI](https://ai.google/responsibilities/responsible-ai-practices/)

[https://github.com/Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox)

[Failure Modes in Machine Learning - Security documentation](https://learn.microsoft.com/en-us/security/engineering/failure-modes-in-machine-learning)

[CV-COPS 2019](https://cvcops19.cispa.saarland/)

[A Tiny Piece of Tape Tricked Teslas Into Speeding Up 50 MPH](https://www.wired.com/story/tesla-speed-up-adversarial-example-mgm-breach-ransomware/)

[Why deep-learning AIs are so easy to fool](https://www.nature.com/articles/d41586-019-03013-5)

[Slight Street Sign Modifications Can Completely Fool Machine Learning Algorithms](https://spectrum.ieee.org/slight-street-sign-modifications-can-fool-machine-learning-algorithms)

[Welcome to the cleverhans blog](http://www.cleverhans.io/)

## *Bonuses*

### *Bonus*: Andrew Ng Adversarial Attacks

[https://www.youtube.com/watch?v=Exd6CLAYOh0](https://www.youtube.com/watch?v=Exd6CLAYOh0)

### *Bonus* : Stanford CS230: Deep Learning | Autumn 2018 | Lecture 4 - Adversarial Attacks / GANs

[https://www.youtube.com/watch?v=ANszao6YQuM](https://www.youtube.com/watch?v=ANszao6YQuM)

### *Bonus* : Project Idea

- **Adversarial patches for Defense Industry**
Adversarial patches can be used in defense industry for defense purposes. It is possible to make a drone equipped with object detection overlook or miss a tank. I am openly sharing this idea as I am not interested in the security aspect of machine learning and deep learning.
- **Adversarial Attack to Chat-GPT3**
Ways to find the weaknesses of the recently popular Chat GPT can be tried.

### *Bonus* : Attacking Machine Learning with Adversarial Examples from Open AI

[https://openai.com/blog/adversarial-example-research/](https://openai.com/blog/adversarial-example-research/)

### *Bonus* : Noise reduction (Denoisining)

[https://en.wikipedia.org/wiki/Noise_reduction](https://en.wikipedia.org/wiki/Noise_reduction)



