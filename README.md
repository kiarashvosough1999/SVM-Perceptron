# SVM-Perceptron

[![Python](https://img.shields.io/badge/Python-3.10_or_Higher-yellow?style=flat-square)](https://img.shields.io/badge/Swift-5.1_5.2_5.3_5.4-Orange?style=flat-square)
[![SciKit-Learn](https://img.shields.io/badge/SciKit_Learn-1.1.1_or_Higher-orange?style=flat-square)](https://img.shields.io/badge/Swift-5.1_5.2_5.3_5.4-Orange?style=flat-square)
[![Twitter](https://img.shields.io/badge/twitter-@Vosough_k-magenta.svg?style=flat-square)](https://twitter.com/AlamofireSF)
[![Linkedin](https://img.shields.io/badge/linkedin-@KiarashVosough-blue.svg?style=flat-square)](https://www.linkedin.com/in/kiarashvosough/)
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

This is one of the project assigned to me by Computation Intelegence course.

I was asked to use Perceptron, SVM and new Perceptron (uses kernel) models with specific Flight dataset.
I used sklearn models for this purpose and analized the result in detail with visual charts and diagram.

- [Features](#features)
- [Contributors](#Contributors)
- [License](#license)


# Features

For each model I tested each **Hyperparameters** to obtain the best value for them in order to increase the overal accuracy.

Used models:

- [x] Perceptron
- [x] GridSearchCV
- [x] RepeatedStratifiedKFold
- [x] SVC (with 4 different kernel)
- [x] LinearSVC
- [x] KerneledPerceptron

## KerneledPerceptron

In order to maximize the accuracy of Perceptron model for non-linear datasets I reimplemeted **KerneledPerceptron** to use kernels like gussian, polynomial and linear.

# Contributors

Feel free to share your ideas or any other problems. Pull requests are welcomed.

# License

SVM-Perceptron is released under an MIT license. See [LICENSE](https://github.com/kiarashvosough1999/SVM-Perceptron/blob/master/LICENSE) for more information.

