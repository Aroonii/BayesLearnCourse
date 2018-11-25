<!-- font: frutiger -->

### Bayesian Learning (aka Bayesian Statistics I)

![alt text](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/Images/BayesTheoremNeon.jpg "Bayesian Learning")

<div style="background-color:#eaeff7; padding:20px 47px;">

</div>

\

<div style="background-color:#eaeff7; padding:20px 47px;">

### Aims

The course aims to give a solid introduction to the Bayesian approach to statistical inference, with a view towards applications in data mining and machine learning. After an introduction to the subjective probability concept that underlies Bayesian inference, the course moves on to the mathematics of the prior-to-posterior updating in basic statistical models, such as the Bernoulli, normal and multinomial models. Linear regression and nonlinear regression are also analyzed using a Bayesian approach. The course subsequently shows how complex models can be analyzed with simulation methods like Markov Chain Monte Carlo (MCMC) or approximate methods like Variational Inference. Bayesian prediction and marginalization of nuisance parameters is explained, and introductions to Bayesian model selection and Bayesian decision theory are also given.
</div>

\

<div style="background-color:#eaeff7; padding:20px 47px;">

### Course literature

The course will use the following book as the main course literature:

* Gelman, A., Carlin, J.B., Stern H.S., Dunson, D.B., Vehtari, A., Rubin, D.B. (2014)
Bayesian Data Analysis. Chapman & Hall/CRC: Boca Raton, Florida. 3rd edition.
* My slides on this page
* Additional course material linked from this page, such as articles and tutorial.

</div>

\

<div style="background-color:#eaeff7; padding:20px 47px;">

### Computer labs

* The computer labs is a central part of this course and you should expect to allocate substantial time for each lab. Many of the exam questions will be computer based, so working on the labs will also help you with the exam.
* The labs should be done in pairs of students. 
* Each lab report should be submitted as a PDF along with the .R file with code. Submission is done through the Mondo system.
* There is only two hours of supervised time allocated to each lab. This will not be enough time to complete each lab. The idea is that you should start working on the lab before the computer session, so that you are in a position to ask questions at the session.

</div>

\


<div style="background-color:#eaeff7; padding:20px 47px;">

### Teachers

##### Lecturer
[Mattias Villani](https://mattiasvillani.com) \
Professor \
Department of Statistics, Stockholm University \
Division of Statistics and Machine Learning, Linköping University 

##### Lab assistants
[Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
PhD Candidate \
Department of Statistics, Stockholm University \

[Munezero Parfait](https://www.su.se/english/profiles/pmune-1.218608) \
PhD Candidate \
Department of Statistics, Stockholm University 

</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 1 - The Basics
##### Lecture 1 - Basics concepts. Likelihood. The Bernoulli model.

Reading: [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/GPregression.pdf) | Chapters 2.1-2.5 in [GPML](http://www.gaussianprocess.org/gpml/chapters/RW.pdf). \
Code: \
Other material: \
Software: [Google's TensorFlow](https://www.tensorflow.org/)

##### Lecture 2 - Gaussian model. Conjugate priors. The Poisson model. Prior elicitation. Noninformative priors.

Reading: [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/GPregression.pdf) | Chapters 2.1-2.5 in [GPML](http://www.gaussianprocess.org/gpml/chapters/RW.pdf). \
Code: \
Other material: \
Software: [Google's TensorFlow](https://www.tensorflow.org/)

##### Lecture 3 - Multi-parameter models. Marginalization. Multinomial model. Multivariate normal model.

Reading: [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/GPregression.pdf) | Chapters 2.1-2.5 in [GPML](http://www.gaussianprocess.org/gpml/chapters/RW.pdf). \
Code: \
Other material: \
Software: [Google's TensorFlow](https://www.tensorflow.org/) 

##### Computer Lab 1 - Exploring posterior distributions in one-parameter models by simulation and direct numerical evaluation.
Reading: Lab \
Submission tool:

</div>
\

<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 2 - Bayesian Regression and Classification
##### Lecture 4 - Prediction. Making Decisions.

Reading: [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/GPregression.pdf) | Chapters 2.1-2.5 in [GPML](http://www.gaussianprocess.org/gpml/chapters/RW.pdf). \
Code: \
Other material: \
Software: [Google's TensorFlow](https://www.tensorflow.org/)

##### Lecture 5 - Linear Regression. Nonlinear regression. Regularization priors.

Reading: [Slides](https://github.com/mattiasvillani/ESOBE2017/raw/master/Slides/GPregression.pdf) | Chapters 2.1-2.5 in [GPML](http://www.gaussianprocess.org/gpml/chapters/RW.pdf). \
Code: \
Other material: \
Software: [Google's TensorFlow](https://www.tensorflow.org/)

##### Lecture 6 - Classification. Posterior approximation. Logistic regression. Naive Bayes.

Reading: [Slides](https://github.com/mattiasvillani/ML4Industry/raw/master/Slides/LectureIntro.pdf) | Chapters 2.1-2.5 in [GPML](http://www.gaussianprocess.org/gpml/chapters/RW.pdf). \
Code: \
Other material: 

##### Computer Lab 2 - Polynomial regression and classification with logistic regression.

Reading: Lab \
Submission tool:
</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 3 - More Advanced Models, MCMC and Variational Bayes
##### Lecture 7 - Bayesian computations. Monte Carlo simulation. Gibbs sampling. Data augmentation.

Reading: \
Code: \
Other material: \
Software: 

##### Lecture 8 - MCMC and Metropolis-Hastings

Reading: \
Code: \
Other material: \
Software: 

##### Lecture 9 - HMC, Variational Bayes and Stan.

Reading: \
Code: \
Other material: \
Software:

##### Computer Lab 3 - Gibbs sampling for the normal model, mixture of normals and probit regression.

Reading: Lab \
Submission tool:

</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 4 - Model Inference and Variable Selection
##### Lecture 10 - Bayesian model comparison.

Reading: \
Code: \
Other material: \
Software: 

##### Lecture 11 - Computing the marginal likelihood, Bayesian variable selection, model averaging.

Reading: \
Code: \
Other material: \
Software: 

##### Lecture 12 - Model evaluation and course summary.

Reading: \
Code: \
Other material: \
Software: 

##### Computer Lab 4 - Metropolis-Hastings for Poisson regression.

Reading: Lab \
Submission tool:
</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Examination

The course examination consists of:

* Written lab reports (deadlines will be given in Mondo)
* Take home exam:
    - 1st attempt: handed out on January 14. To be returned on January 18.
    - 2nd attempt: handed out on TBD. To be returned on TBD.
</div>
\