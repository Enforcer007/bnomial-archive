## Date - 2022-04-24

## Title - Mia and the feedback loop

### **Question** :

Mia was crushing her thesis!

She was about to release a new neural network architecture that promised to raise the bar on image classification problems.

Mia did not start from scratch. She modified an existing model but added a key ingredient: feedback loops.

A feedback loop is when connections between units form a directed cycle, thus creating loops in the network. This gave Mia's network the ability to save information in the hidden layers.

Mia did a lot of research before deciding in favor of this architecture. She knew the advantages of her decision.

**Which was the architecture that Mia studied to learn about feedback loops?**

### **Choices** :

- Recurrent Neural Networks
- Convolutional Neural Network
- Multilayer Perceptron
- Radial Basis Function Network

---
## Date - 2022-04-25


## Title - Harper and the small gradients


### **Question** :

Harper's team is struggling with the deep neural network they have been building.

Unfortunately, during backpropagation, the gradient values of their network decrease dramatically as the process gets closer to the initial layers, preventing them from learning at the same pace as the last set of layers.

Harper knows their model suffers from the vanishing gradient problem. She decides to research every possible option to improve their model.

**Which of the following techniques will make Harper's model more robust to the vanishing gradient problem?**


### **Choices** :

- Harper should try ReLU as the activation function since it's well-known for mitigating the vanishing gradient problem.
- Harper should modify the model architecture to introduce Batch Normalization.
- Harper should make sure they are initializing the weights properly. For example, using He initialization should help with the vanishing gradient problem.
- Harper should increase the learning rate to avoid getting stuck in local minima and thus reduce the chance of suffering vanishing gradients.

-----------------------

## Date - 2022-04-26


## Title - Exploring data before anything else


### **Question** :

An essential step in any machine learning project is the Exploratory Data Analysis process.

Before we can train a model, we need to understand our data. As the name suggests, Exploratory Data Analysis allows us to explore the data to discover potential problems or patterns that we can use.

**Which of the following are some of the steps we take during this process?**


### **Choices** :

- Learn the distribution of the target variable.
- Understand the features in the dataset and the distribution of their values.
- Evaluate the performance of our models on this data.
- Assess the data quality, including missing or corrupt values.

-----------------------

## Date - 2022-04-27


## Title - Susan needs to make a decision


### **Question** :

The deadline is approaching, and Susan still hasn't decided which version of her classification model to deploy to production.

She experimented with different hyperparameters, and now she has two models that perform pretty well. 

Her problem is that none of these models is better than the other in every situation. One model has a higher recall but worse precision than the other. Susan can improve the precision by playing with different thresholds, but now the recall decreases.

**How can Susan decide which is the best overall model?**


### **Choices** :

- Susan should tune the thresholds until both have a recall of 95% and choose the one with higher precision.
- Susan should tune the thresholds until both have a precision of 95% and choose the one with a higher recall.
- Susan should compute the area under the curve for both models and choose the one with the higher value.
- There's no objective way to decide which model is best. Susan should pick either one of them.

-----------------------

## Date - 2022-04-28


## Title - Linear regression by hand


### **Question** :

The best way to learn something new is to rip the band-aid and tackle a problem from scratch.

Imagine you get a dataset with thousands of samples of houses sold in the U.S. over the last five years. We know the value of a few different features of each home and the price it was sold for. The goal is to build a simple model capable of predicting the price of a new house given those features.

A linear regression model seems like an excellent place to start. 

But you are not writing any code yet. You want to do this manually, starting with a matrix `X` containing the value of the features and a vector `w` containing the weights.

The next step is to multiply `X` and `w`, but you aren't sure about the result of this operation.

**Which of the following better describes the result of multiplying `X` and `w`?**


### **Choices** :

- The result will be a vector `y` containing the actual price of each house as provided in the dataset.
- The result will be a vector `y` containing the predicted price of each house.
- The result will be a matrix `y` containing the actual price of each house and the features from the matrix `X`.
- The result will be a matrix `y` containing the predicted price of each house and the features from the matrix `X`.

-----------------------

## Date - 2022-04-29


## Title - 20,000 sunny and cloudy samples


### **Question** :

Today is your very first day.

You get access to weather data. Twenty thousand samples with the weather of sunny and cloudy days. You want to build a model to predict whether a future day will be sunny or cloudy.

You already know this is a binary classification problem, and now it's time to pick a model.

**Which of the following techniques can you use to build a binary classification model?**


### **Choices** :

- Logistic Regression
- k-Nearest Neighbors
- Neural Networks
- Decision Trees

-----------------------

## Date - 2022-04-30


## Title - The true meaning of hyperparameter tuning


### **Question** :

Marlene is trying to build an audience.

Writing content seems easy, but taking a complex subject and boiling it down to its essence is not an obvious task.

Marlene wants to start from the basics and write as much as possible about the fundamentals of machine learning.

She picked her first topic: hyperparameter tuning.

**If you were trying to summarize the core idea of hyperparameter tuning, which one of the following sentences would you use?**


### **Choices** :

- Hyperparameter tuning is about choosing the set of optimal features from the data to train a model.
- Hyperparameter tuning is about choosing the set of optimal samples from the data to train a model.
- Hyperparameter tuning is about choosing the optimal parameters for a learning algorithm to train a model.
- Hyperparameter tuning is about choosing the set of hypotheses that better fit the goal of the model.

-----------------------

## Date - 2022-05-01


## Title - One of these shouldn't be here


### **Question** :

Here are four different techniques commonly used in machine learning.

Although they are all related somehow, one of them is different from the rest. Your goal is to determine which of the following doesn't belong on this list.

**Can you select the odd one out?**


### **Choices** :

- Expectation???Maximization
- PCA
- DBSCAN
- K-Means

-----------------------

## Date - 2022-05-02


## Title - The bankruptcy story


### **Question** :

Suzanne wants to build an algorithm to predict whether a company is about to declare bankruptcy over the next few months.

She has access to a labeled dataset with detailed financial information from thousands of companies, including those that have declared bankruptcy over the last 100 years.

Suzanne has some ideas but would love to hear what you think.

**Understanding that there are many ways to approach a problem, what would be your first recommendation to Suzanne?**


### **Choices** :

- The best way to approach this problem is with Supervised Learning by using a regression algorithm.
- The best way to approach this problem is with Supervised Learning by using a classification algorithm.
- The best way to approach this problem is with Unsupervised Learning by using a clustering algorithm.
- The best way to approach this problem is with Reinforcement Learning.

-----------------------

## Date - 2022-05-03


## Title - A batch of rotated pictures


### **Question** :

After looking at the last batch of images, the problem was apparent:

Customers were taking pictures and sending them with different degrees of rotation. The Convolutional Neural Network that Jessica built wasn't ready to handle this.

She knew she needed to do something about it.

A couple of meetings later, Jessica knew what the right solution was. It took some time for the team to agree, but they had a plan now.

**Which of the following approaches could Jessica have proposed?**


### **Choices** :

- Extending the pipeline with a data preprocessing step to properly rotate every image coming from the customer before giving the data to the model.
- Extending the model with a layer capable of rotating the data to the correct position.
- Extending the training data with samples of images rotated across the full 360-degree spectrum to build some rotation invariability into the model.
- Configuring the network correctly since Convolutional Neural Networks are translation and rotation invariant and should handle these images correctly.

-----------------------

## Date - 2022-05-04


## Title - Alex's model is not doing well


### **Question** :

Alex is a Machine Learning Engineer working for a new photo-sharing startup.

His team started building a model to predict the likeability of every new image posted on the platform. They collected some data and built a simple classification model.

Unfortunately, Alex quickly realizes that the model doesn't perform well. He notices that the training error is not as low as expected.

**What do you think is happening with Alex's model?**


### **Choices** :

- It's very likely that the model suffers from high bias and is underfitting. This usually happens when the model is not complex enough and can't capture the relationship between input and output variables.
- It's very likely that the model suffers from low bias and is underfitting. This usually happens when the model is not complex enough and can't capture the relationship between input and output variables.
- It's very likely that the model suffers from high variance and is overfitting. This usually happens when the model is too complex and captures the noise of the data.
- It's very likely that the model suffers from low variance and is overfitting. This usually happens when the model is too complex and captures the noise of the data.

-----------------------

## Date - 2022-05-05


## Title - Behind Gradient Descent


### **Question** :

It's 2030, and neural networks are taught at high schools worldwide.

It makes sense. Few subjects are as impactful to society as machine learning, so it's only appropriate that schools get students onboard from a very early age.

Lillian spent a long time learning about gradient descent and how it's an optimization algorithm frequently used in machine learning applications.

This is Lillian's last exam. The first question asks her to describe in a few words how gradient descent works.

**Which of the following statements is a sensible description of how the algorithm works?**


### **Choices** :

- Gradient descent identifies the minimum loss and adjusts every parameter proportionally to this loss.
- Gradient descent searches every possible combination of parameters to find the optimal loss.
- Gradient descent identifies the slope in all directions and adjusts the parameters to move them in the direction of the negative slope.
- Gradient descent identifies the slope in all directions and adjusts the parameters to move them in the direction of the slope.

-----------------------

## Date - 2022-05-06


## Title - A recommendation for Adrienne


### **Question** :

Kaggle looked like the perfect opportunity for Adrienne to start practicing machine learning.

She went online and started listening to the conversations about popular Kagglers. One particular topic caught her attention: They kept discussing different ways to create ensembles.

Adrienne knew that ensemble learning is a powerful technique where you combine the decisions from multiple models to improve the overall performance. She had never used ensembles before, so she decided this was the place to start.

**Which of the following are valid ensemble techniques that Adrienne could study?**


### **Choices** :

- Max Voting: Multiple models make predictions for each sample. The final prediction is the one produced by the majority of the models.
- Weighted Voting: Multiple models make predictions for each sample, and each model is assigned a different weight. The final prediction considers the importance of the model in determining the final vote.
- Simple Averaging: Multiple models make predictions for each sample. The final prediction is the average of all of those predictions.
- Weighted Averaging: Multiple models make predictions for each sample, and each model is assigned a different weight. The final prediction is the average of all of those predictions, considering the importance of each model.

-----------------------

## Date - 2022-05-07


## Title - Sometimes, small is better


### **Question** :

Fynn is new to a team working on a neural network model. Unfortunately, they haven't been happy with the results so far.

Fynn thinks that he found the problem: they chose a batch size as large as it fits into the GPU memory. His colleagues believe this is the right approach, but Fynn believes a smaller batch size will be better.

**What would be good arguments to support Fynn's suspicion?**


### **Choices** :

- A smaller batch size is more computationally effective.
- A smaller batch size reduces overfitting because it increases the noise in the training process.
- A smaller batch size reduces overfitting because it decreases the noise in the training process.
- A smaller batch size can improve the generalization of the model.

-----------------------

## Date - 2022-05-08


## Title - Reese's baseline


### **Question** :

Starting with a simple baseline is a great way to approach a new problem.

Reese knew that, and her go-to has always been a simple Linear Regression, probably one of the most popular algorithms in statistics and machine learning.

But Reese knows that for Linear Regression to work, she must consider several assumptions about the problem.

**Which of the following are some of the assumptions that Reese should make for Linear Regression to be a good candidate for her baseline?**


### **Choices** :

- The relationship between the features in the data and the target variable must be linear.
- The features in the data are highly correlated between them.
- The features in the data and the target variable are not noisy.
- There must not be more than two relevant features plus the target variable.

-----------------------

## Date - 2022-05-09


## Title - Migrating to PyTorch Lighting


### **Question** :

Many of the old team members have left Layla's company, forcing them to start building a new team.

They have been hiring from local universities, and most new hires brought a lot of experience in PyTorch Lightning. Unfortunately for Layla's company, their main product uses TensorFlow.

After some discussions, Layla's team decided to migrate their model to PyTorch Lightning. This change, however, will not come without making some concessions. 

**Which of the following are some of the downsides of this decision?**


### **Choices** :

- The team will lose the ability to deploy the model in TPUs (Tensor Processing Units), limiting them to GPUs and CPUs.
- The team won't be able to use tools like TensorBoard during the training process, so they will need to find an equivalent tool compatible with PyTorch Lightning.
- The team will have to invest time to migrate the deployment process of their model from TensorFlow Serving to something like TorchServe or PyTorch Live.
- Migrating the existing codebase to PyTorch Lightning could introduce unforeseen problems that could cause issues with the new model.

-----------------------

## Date - 2022-05-10


## Title - The brains behind transformers


### **Question** :

It took some time, but Kinsley finished replacing her old model based on a [Long Short-Term Memory](https://machinelearningmastery.com/gentle-introduction-long-short-term-memory-networks-experts/) (LSTM) network with a new version using Transformers.

The results of the new model were impressive. The whole team was thrilled with Kinsley's work, and the company organized an internal session for Kinsley to bring everyone up to speed.

After finishing her speech, a coworker asked Kinsley a question: 

**Which company invented the Transformer architecture?**


### **Choices** :

- Hugging Face
- OpenAI
- Google
- Allen Institute of AI


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>In 2017, a team at [Google Brain](https://en.wikipedia.org/wiki/Google_Brain) published the now-famous paper ["Attention Is All You Need,"](https://arxiv.org/abs/1706.03762) where they introduced the Transformer architecture, which transforms one sequence into another with the help of an Encoder and a Decoder. 

[Hugging Face](https://huggingface.co) is an AI community that hosts many NLP models, including a large number of transformer models. Despite being a pioneer in adopting transformer models, Hugging Face is not behind the creation of Transformers.

OpenAI is another powerhouse that conducts AI research to promote and develop AI to benefit humanity. OpenAI is behind models like [GPT-3](https://en.wikipedia.org/wiki/GPT-3), [CLIP](https://openai.com/blog/clip/), and [DALL-E](https://openai.com/blog/dall-e/), all of which use the Transformer architecture. OpenAI, however, didn't invent Transformers.

Finally, the [Allen Institute of AI](https://allenai.org) (also known as AI2) is the AI research institute behind [Macaw](https://macaw.apps.allenai.org), a high-performance question-answering model capable of giving GPT-3 a run for its money. Despite their work with Transformers, they aren't behind its creation either.

In summary, the correct answer to this question is that Google is the inventor of Transformers.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
* [GPT-3](https://en.wikipedia.org/wiki/GPT-3)
* [CLIP](https://openai.com/blog/clip/)
* [DALL-E](https://openai.com/blog/dall-e/)
* [Macaw](https://macaw.apps.allenai.org)</p></details>

-----------------------

## Date - 2022-05-11


## Title - Trending recession


### **Question** :

The company's accounting team used a spreadsheet with some rudimentary charts, but it was time to get serious.

That's when Peyton came in.

Payton had a lot of experience doing time series analysis. Her mandate was simple: using the financial data of past years, predict where the company is going over the next few quarters.

Despite Payton's credentials, the team was worried: the company has been slowly recovering from a recession, and they were concerned this would skew future data. 

Payton went over the different components of time series analysis and explained how to classify this specific trend.

**Which of the following was Payton's explanation about this recession period?**


### **Choices** :

- The company's recession is part of a secular variation.
- The company's recession is part of a seasonal variation.
- The company's recession is part of a cyclical variation.
- The company's recession is part of an irregular variation.


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>There are four components of a time series analysis: 
1. Secular trends???or simple trends.
2. Seasonal variations???or seasonal trends.
3. Cyclical fluctuations???or cyclical trends.
4. Irregular variations???or irregular trends.

A secular trend refers to the tendency of the series to increase, decrease, or stagnate over a long time. For example, a country's population could show an upward direction, while the number of death rates may show a downward trend. This trend is not seasonal or recurring.

On the other hand, a seasonal trend is a short-term fluctuation in a time series that occurs periodically. For example, sales during holidays trend much higher than during any other month, and the same happens every year.

A cyclical fluctuation is another variation that usually lasts for more than a year, and it's the effect of business cycles. Organizations go through these fluctuations in four different phases: prosperity, recession, depression, and recovery.

Finally, irregular variations are unpredictable fluctuations. We classify any variation that's not secular, seasonal, or cyclical as irregular. For example, we can't anticipate the effects of a hurricane on the economy.

The company here is dealing with a recession. Recessions are one of the phases of a cyclical fluctuation, so this was Payton's explanation. An important note is that cyclical variations do not have a fixed period???like seasonal variations do???but we can still predict them because we usually understand the sequence of changes that lead to these trends. 

In summary, the third choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Introduction to Time Series Analysis](https://www.jigsawacademy.com/introduction-time-series-analysis/)
* [Definition of Time Series Analysis](https://www.toppr.com/guides/fundamentals-of-business-mathematics-and-statistics/time-series-analysis/definition-of-time-series-analysis/)</p></details>

-----------------------

## Date - 2022-05-12


## Title - A way to win Kaggle competitions


### **Question** :

Victoria joined Kaggle, and halfway through her first competition, she realized her single model wouldn't perform very well on the leaderboard. 

She learned that most people were using multiple models working together. Looking into that extra boost from ensembles was the only way she would be able to increase her score.

Victoria spent a couple of days reading about stacking and blending, two of the most popular techniques for building ensemble models. Although she was clear about the high-level idea, she wasn't sure about some of the differences between both techniques.

**Which of the following are valid differences between stacking and blending?**


### **Choices** :

- The meta-model created using stacking learns how to combine the predictions from multiple models. In contrast, the meta-model created using blending uses the predictions of the best contributing model.
- Stacking doesn't need models of comparable predictive power. In contrast, blending works like a weighted average and requires models to contribute positively to the ensemble.
- The meta-model created using stacking is trained on out-of-fold predictions made during cross-validation. In contrast, a meta-model created using blending is trained on predictions made on a holdout set.
- Stacking works well for both classification and regression problems. In contrast, Blending only works for regression problems.


### **Answer** :

<details><summary>CLICK ME</summary><p>0110</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Victoria is right. Stacking and blending are powerful ensemble techniques and a must if you want to score high in Kaggle competitions.

Although both techniques have the same ultimate goal, there are essential differences in how they work. Let's start unraveling each of the available choices for this question to determine which ones are correct.

Stacking and blending use the concept of a "meta-model," a model that you train to average the results of other models. At a high level, both ensemble techniques use multiple models to generate predictions, and a meta-model to average those predictions and provide a final result.

The first choice argues that blending uses the predictions of the best contributing model, which is not true. Just like stacking, blending's meta-model uses the predictions of multiple models. Therefore, this is not a valid difference between both techniques.

An advantage of stacking is that it can benefit even from models that don't perform very well. In contrast, blending does require that models have a similar, good predictive power. Here is an excerpt from ["The Kaggle Book"](https://amzn.to/3kbanRb):

> (...) one interesting aspect of stacking is that you don't need models of comparable predictive power, as in averaging and often blending. In fact, even worse-performing models may be effective as part of a stacking ensemble. 

So even when using an individual model that performs poorly compared to all of the other models used by the stacking ensemble, the meta-model can use its out-of-fold predictions to improve its performance. Therefore, the second choice is a valid difference between both techniques.

Another valid difference between stacking and blending is the data they use to train the meta-model. The stacking meta-model is trained in the entire training set, using the [out-of-fold](https://machinelearningmastery.com/out-of-fold-predictions-in-machine-learning/) prediction strategy. The blending meta-model is trained in a holdout set that we randomly extract from the training dataset. Therefore, the third choice is also a valid difference between these techniques.

Finally, stacking and blending work well for regression and classification problems, so the final choice is incorrect.

In summary, the second and third choices are the correct answers to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Stacking and Blending ??? An Intuitive Explanation](https://medium.com/@stevenyu530_73989/stacking-and-blending-intuitive-explanation-of-advanced-ensemble-methods-46b295da413c)
* [Stacking Ensemble Machine Learning With Python](https://machinelearningmastery.com/stacking-ensemble-machine-learning-with-python/)
* [Blending Ensemble Machine Learning With Python](https://machinelearningmastery.com/blending-ensemble-machine-learning-with-python/)
* [How to Use Out-of-Fold Predictions in Machine Learning](https://machinelearningmastery.com/out-of-fold-predictions-in-machine-learning/)
* [The Kaggle Book](https://amzn.to/3kbanRb)</p></details>

-----------------------

## Date - 2022-05-13


## Title - Pick the one you don't like


### **Question** :

Let's get straight to the point.

Your goal is to determine which of the following doesn't belong on this list.

**Can you select the odd one out?**


### **Choices** :

- AdaGrad
- RMSProp
- Adam
- SGD


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Every example here is an optimization method used when training a machine learning model. 

However, [AdaGrad](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#AdaGrad), [RMSProp](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#RMSProp), and [Adam](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#Adam) are adaptive learning rate methods, while [SGD](https://en.wikipedia.org/wiki/Stochastic_gradient_descent) is not.

[Adaptive learning rate methods](https://towardsdatascience.com/learning-rate-schedules-and-adaptive-learning-rate-methods-for-deep-learning-2c8f433990d1) track and update different learning rates for each model parameter, while SGD uses the same learning rate for all parameters.

The last choice is the correct answer.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- [Learning Rate Schedules and Adaptive Learning Rate Methods for Deep Learning](https://towardsdatascience.com/learning-rate-schedules-and-adaptive-learning-rate-methods-for-deep-learning-2c8f433990d1)
- [Stochastic gradient descent: Extensions and variants](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#Extensions_and_variants)
- [How to Configure the Learning Rate When Training Deep Learning Neural Networks](https://machinelearningmastery.com/learning-rate-for-deep-learning-neural-networks/)
- [Deep Learning](https://amzn.to/3CSjPkR)</p></details>

-----------------------

## Date - 2022-05-14


## Title - Depth perception


### **Question** :

Richard finally got a job as a self-driving car engineer!

His first task is to help the car perceive depth using the onboard cameras. He wants to start with an overview of the different approaches he can use to estimate the distance to every pixel in the image.

Before diving into the existing techniques, Richard has to think about the different ways he can capture pictures.

**Which of the following mechanisms do you think Richard can use to estimate depth?**


### **Choices** :

- An image from a single camera.
- A sequence of images from a single camera.
- A pair of images from a stereo camera.
- Cameras are 2D sensors, so Richard can't use them to estimate depth.


### **Answer** :

<details><summary>CLICK ME</summary><p>1110</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Cameras are indeed 2D sensors, but there are many ways to estimate distance using pictures from a camera, so the last choice is incorrect.

Using a stereo camera is one of the classical approaches to do this. For every point observed in both camera images, we can triangulate its 3D position. Therefore, the third choice is correct.

We can also use a sequence of images from a single camera to triangulate fixed points over different frames. This method is called [Structure from Motion](https://en.wikipedia.org/wiki/Structure_from_motion) and is also a correct choice. I'd recommend listening to [Andrej Karpathy's talk](https://youtu.be/Ucp0TTmvqOE?t=8479) covering the work they are doing at Tesla to estimate depth using video.

The most interesting correct choice is the first one. We don't have enough information to triangulate the distance to a point in the image, but we can use our knowledge of the world to make some assumptions and solve the problem.

Remember, we are only interested in a car driving on the street, so we can exploit our understanding of the scene and our knowledge of standard dimensions of objects to estimate the distance to each point on the image. Over the last few years, we have seen several methods to train deep neural networks using this approach. ["Single Image Depth Estimation: An Overview"](https://arxiv.org/abs/2104.06456) is a good paper covering this topic.

In summary, every choice but the last one is correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- [Stereo Vision](https://en.wikipedia.org/wiki/Computer_stereo_vision)
- [Structure from Motion](https://en.wikipedia.org/wiki/Structure_from_motion)
- [Monocular depth estimation](https://paperswithcode.com/task/monocular-depth-estimation)
- [Depth from vision by Andrej Karpathy](https://youtu.be/Ucp0TTmvqOE?t=8479)
- [Single Image Depth Estimation: An Overview](https://arxiv.org/abs/2104.06456)
- [Multiple View Geometry](https://amzn.to/3KNPhmN)</p></details>

-----------------------

## Date - 2022-05-15


## Title - The benefits of the Huber loss


### **Question** :

The Huber loss is a popular loss function used for regression problems in machine learning.

[Here is the formula](https://en.wikipedia.org/wiki/Huber_loss). Take a second and look at it. 

The formula may look complex, but there are two things you need to know about the Huber loss. 

First, it behaves like a square function for values smaller than a parameter ?? (similar to MSE.) Second, it acts as the absolute function for larger values (similar to MAE.)

In essence, the Huber loss is a combination of two other popular loss functions: Mean Squared Error (MSE) and Mean Absolute Error (MAE.)

**What are the benefits of combining these two functions?**


### **Choices** :

- It adds an additional hyperparameter ?? which helps tune the model.
- It is more robust against large outliers than MSE.
- It is smooth around 0 helping the training converge better.
- It is continuous and differentiable.


### **Answer** :

<details><summary>CLICK ME</summary><p>0111</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The [Huber loss](https://en.wikipedia.org/wiki/Huber_loss) tries to combine the advantages of both MSE and MAE. Here is a picture showing a comparison between these three functions (Image credit to ["Regression loss functions for machine learning"](https://www.evergreeninnovations.co/blog-machine-learning-loss-functions/)):

![image](https://user-images.githubusercontent.com/1126730/167011014-92c64b36-689e-4a89-bc6e-1e963807a982.png)

If we want to have a loss function that is not affected by outliers, we typically use MAE instead of MSE. When using MAE, we don't square the errors as we do with MSE, so outliers aren't amplified. However, MAE has the problem that it is not smooth around 0 (the derivative jumps a lot at 0,) which may cause issues with convergence. 

The Huber loss behaves like MAE for large values, so it's robust against outliers, but it acts like MSE around 0, so it is smooth. In a way, we get our cake and eat it too with the Huber loss! Therefore, the second and third options are correct.

An important goal for the Huber loss was to make it continuous and differentiable. This makes the fourth choice correct as well.

Finally, the Huber loss comes with an additional hyperparameter ??. That extra parameter means that the training process will be harder to tune. Although the parameter is essential in the design of the Huber loss, it's not an advantage compared to a loss function that doesn't require tuning. Therefore, the first choice is incorrect.

In summary, the second, third, and fourth choices are correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- [Huber loss](https://en.wikipedia.org/wiki/Huber_loss)
- [Huber Loss: Why Is It, Like How It Is?](https://www.cantorsparadise.com/huber-loss-why-is-it-like-how-it-is-dcbe47936473)
- [Regression loss functions for machine learning](https://www.evergreeninnovations.co/blog-machine-learning-loss-functions/)</p></details>

-----------------------

## Date - 2022-05-16


## Title - Climbing a hill


### **Question** :

Gabriela wanted her friend to grow an appreciation for the outdoors, so they started meeting every Saturday and going for a hike together.

And what better way to spend their time than starting a discussion about hill climbing and how it relates to their day-to-day work.

It turns out that hill climbing is an optimization algorithm that attempts to find a better solution by making incremental changes until it doesn't see further improvements.

Her friend couldn't help but notice how similar to gradient descent the process was, but Gabriela knew there were a few critical differences between them. 

**Can you select every correct statement from the following comparison list?**


### **Choices** :

- Hill climbing is a general optimization algorithm, but gradient descent is only used to optimize neural networks.
- Unlike gradient descent, hill climbing can return an optimal solution even if it's interrupted at any time before it ends.
- Gradient descent is usually more efficient than hill climbing, but there are fewer problems we can tackle with gradient descent.
- Both hill climbing and gradient descent can find optimal solutions for convex problems.


### **Answer** :

<details><summary>CLICK ME</summary><p>0011</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>[Hill climbing](https://en.wikipedia.org/wiki/Hill_climbing) is an optimization algorithm, just like [gradient descent](https://en.wikipedia.org/wiki/Gradient_descent) is. You can use both to minimize a function, regardless of whether it's related to a neural network, so the first choice is incorrect. For example, the following animation comes from ["Linear Regression using Gradient Descent."](https://towardsdatascience.com/linear-regression-using-gradient-descent-97a6c8700931) It shows a linear regression model that uses gradient descent as the optimization algorithm:

![Linear regression using gradient descent](https://miro.medium.com/max/1400/1*CjTBNFUEI_IokEOXJ00zKw.gif)

The second choice is also incorrect. Hill climbing can return a valid solution even if it's interrupted before it ends, but there's no guarantee that this will be the optimal solution. We call these types of algorithms ["anytime algorithms."](https://en.wikipedia.org/wiki/Anytime_algorithm) They find better and better solutions the longer they keep running but can return a reasonable solution at any time.

Gradient descent looks at the slope in the local neighborhood and moves in the direction of the steepest slope. This makes it much more efficient than hill climbing, which needs to look at all neighboring states to evaluate the cost function in each of them. 

The efficiency gained by gradient descent presents a trade-off: the algorithm assumes that you can compute the function's gradient in any given state, limiting the problems where we can use it. Therefore, the third choice is correct.

Finally, the fourth choice is also a correct answer. Both algorithms can find the optimal solution for a convex problem. Look at the following example of a [convex function](https://en.wikipedia.org/wiki/Convex_function). Assuming we configure hill climbing to optimize for finding the minimum, neither function should have trouble getting all the way to the bottom of this problem:

![A convex function](https://user-images.githubusercontent.com/1126730/167182794-30f47b44-2149-4700-b642-616d8d6dce51.png)

In summary, the third and fourth choices are the correct answers to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Hill Climbing Algorithms (and gradient descent variants) IRL](https://umu.to/blog/2018/06/29/hill-climbing-irl)
* [Linear Regression using Gradient Descent](https://towardsdatascience.com/linear-regression-using-gradient-descent-97a6c8700931)
* [Hill climbing](https://en.wikipedia.org/wiki/Hill_climbing)
* [Gradient descent](https://en.wikipedia.org/wiki/Gradient_descent)</p></details>

-----------------------

## Date - 2022-05-17


## Title - Which function is she using?


### **Question** :

Kiara was leaving her team, but she didn't want to go without having some fun.

She put together a simple neural network with one hidden layer. Never trained it, but she initialized its parameters and told her team that they should expect every node from the hidden layer to return a value resembling the following formula:

```
y = max(0.01 * x, 0)
```

Kiara saved the model and asked her team to test the node results without looking at the code. They found out that, in effect, the results always followed the formula mentioned by Kiara.

Kiara's question to her team was simple:

**Which of the following activation functions am I using in this network?**


### **Choices** :

- Kiara is using the sigmoid activation function.
- Kiara is using the Rectified Linear Unit activation function.
- Kiara is using the Leaky Rectified Linear Unit activation function.
- None of the above activation functions can produce this output.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>This is a fun, interesting question and one where we need to be very careful to find the correct answer.

The team doesn't have access to the network architecture, so all they know is that node outputs follow a specific pattern. They also know Kiara is using an activation function. If we use ?? to represent this activation function, the result of each node should look like this:

```
z = ??(y)
```

Here, `z` is the output the team is getting out of the node, and `y` is the input to the activation function. This input results from `y = w * x + b`, where `b` is the bias, and `w` is the weight assigned to that node. Putting everything together:

```
z = ??(w * x + b)
```

Let's start with [sigmoid](https://en.wikipedia.org/wiki/Sigmoid_function), which doesn't use the `max` operation, so we can safely discard it.

Here is the formula of the [Leaky Rectified Linear Unit](https://paperswithcode.com/method/leaky-relu) (Leaky ReLU):

```
y = max(0.01 * x, x)
```

This one looks promising, and it's how Kiara wanted to prank her team. Assuming that `x` results from `w * x + b`, Leaky ReLU would almost make sense, except it returns the maximum between a scaled version of `x` and `x`, while the team is seeing something different. Leaky ReLU can't possibly be the answer.

Here is the formula of the [Rectified Linear Unit](https://en.wikipedia.org/wiki/Rectifier_(neural_networks)) (ReLU):

```
y = max(x, 0)
```

It looks similar, but where is the scaling factor? Well, Kiara initialized the network, so there's a good chance she did it in a way to confuse everyone. If Kiara set every weight `w` to be `0.01` and every bias term to be zero, we would get the following:

```
z = ??(w * x + b)
z = ??(0.01 * x + 0)
```

Assuming that ?? is the ReLU activation function, we will get the following:

```
z = max(0.01 * x + 0, 0)
z = max(0.01 * x, 0)
```

This is the pattern the team is seeing. Kiara used ReLU as her activation function.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [A Gentle Introduction to the Rectified Linear Unit (ReLU)](https://machinelearningmastery.com/rectified-linear-activation-function-for-deep-learning-neural-networks/)
* [Rectifier (neural networks)](https://en.wikipedia.org/wiki/Rectifier_(neural_networks))
* [Leaky ReLU](https://paperswithcode.com/method/leaky-relu)
* [Activation Functions](https://himanshuxd.medium.com/activation-functions-sigmoid-relu-leaky-relu-and-softmax-basics-for-neural-networks-and-deep-8d9c70eed91e)</p></details>

-----------------------

## Date - 2022-05-18


## Title - Riley's speed-dating match


### **Question** :

If you spend all day sitting at a desk, you can't expect to have many opportunities to meet interesting people.

Riley decided to get to bull by the horns and checked in on one of those speed-dating sites that promise to find your perfect match.

But of course, Silicon Valley is a ridiculous caricature of the impossible, and Riley's first match decided to start blabbing about machine learning and dimensionality reduction algorithms.

And if this wasn't crazy enough, Riley didn't think this person knew what he was talking about.

**Can you guess all the possible statements about dimensionality reduction that would make Riley's match incorrect?**


### **Choices** :

- Supervised learning algorithms can be used as dimensionality reduction techniques.
- Every dimensionality reduction technique is a clustering technique, but every clustering technique is not a dimensionality reduction algorithm.
- Dimensionality reduction algorithms are primarily considered unsupervised learning techniques.
- Nowadays, the most successful dimensionality reduction techniques are deep learning algorithms.


### **Answer** :

<details><summary>CLICK ME</summary><p>0101</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Here is something clear to Riley: Dimensionality reduction algorithms reduce the number of input variables in a dataset to find a lower-dimensional representation that still preserves the salient relationships in the data.

For example, PCA???short for [Principal Component Analysis](https://en.wikipedia.org/wiki/Principal_component_analysis)???is a dimensionality reduction algorithm often used to reduce the number of variables in a dataset while preserving as much information as possible. Another dimensionality reduction technique is [Independent Component Analysis](https://en.wikipedia.org/wiki/Independent_component_analysis) (ICA).

Everywhere you go, dimensionality reduction algorithms are classified as unsupervised learning techniques. Even auto-encoders that require training a neural network are not considered a supervised technique, as mentioned in ["Machine Learning: A Probabilistic Perspective"](https://amzn.to/3s39PRD):

> An auto-encoder is a kind of unsupervised neural network that is used for dimensionality reduction and feature discovery. More precisely, an auto-encoder is a feedforward neural network that is trained to predict the input itself.

This doesn't mean that you can't use a supervised learning method to reduce the dimensionality of a dataset. For example, here is an excerpt from ["Seven Techniques for Data Dimensionality Reduction"](https://www.knime.com/blog/seven-techniques-for-data-dimensionality-reduction):

> Decision Tree Ensembles, also referred to as random forests, are useful for feature selection in addition to being effective classifiers. One approach to dimensionality reduction is to generate a large and carefully constructed set of trees against a target attribute and then use each attribute's usage statistics to find the most informative subset of features.

At this point, we know that the first and the third choices are correct statements about dimensionality reduction. But what about the other two options?

The second choice is incorrect because every dimensionality reduction technique is not a clustering technique. For example, neither PCA nor ICA are clustering methods.

The fourth option is also incorrect because it's not true that the most successful dimensionality reduction techniques are limited to deep learning algorithms. For example, PCA is one of the most popular dimensionality reduction techniques and has nothing to do with deep learning.

If Riley's match was incorrect, he must have mentioned the second or fourth statements, so they are the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Introduction to Dimensionality Reduction for Machine Learning](https://machinelearningmastery.com/dimensionality-reduction-for-machine-learning/)
* [Machine Learning: A Probabilistic Perspective](https://amzn.to/3s39PRD)
* [Seven Techniques for Data Dimensionality Reduction](https://www.knime.com/blog/seven-techniques-for-data-dimensionality-reduction)
* [A Gentle Introduction to LSTM Autoencoders](https://machinelearningmastery.com/lstm-autoencoders/)</p></details>

-----------------------

## Date - 2022-05-19


## Title - Occam's Razor showoff


### **Question** :

Tiara's manager was a showoff. No matter the situation, he always found a way to show everyone how smart he was.

Tiara noticed that he's been getting into machine learning lately, and as cringe as it sounds, he has been using "Occam's Razor" on every occasion, even incorrectly.

Tiara started a secret list collecting every scenario when her manager used Occam's Razor to explain a situation. At the end of the week, she sent it to many of her friends to have a good laugh.

**Which of the following situations from Tiara's list are you comfortable justifying with Occam's Razor?**


### **Choices** :

- We should prefer simpler models with fewer coefficients over complex models like ensembles.
- Feature selection and dimensionality reduction help simplify models to get better results.
- Keeping the training process as fast as possible avoids overtraining and prevents overcomplicated results.
- Starting the training of the model using sensible values for the hyperparameters.


### **Answer** :

<details><summary>CLICK ME</summary><p>1100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>[Occam's Razor](https://en.wikipedia.org/wiki/Occam%27s_razor) is a principle that says that if you have two competing ideas to explain the same phenomenon, you should prefer the simpler one.

There are a couple of situations in this list where using Occam's Razor is a stretch. The third choice is probably the simplest one to tackle first: it talks about "the speed of the training process" and relates it to overtraining and overcomplicating results. Not only does this has nothing to do with Occam's Razor, but a quick training process doesn't necessarily reduce complexity. 

The fourth choice is also not correct. Starting training using sensible values for the hyperparameters is essential, but we can't explain this using Occam's Razor.

Occam's Razor fits the first choice like a glove. Given two learning algorithms with similar tradeoffs, we should use the least complex and most straightforward to interpret. At least this time, Tiara's boss was correct.

Finally, the second choice is not an obvious fit, but we could argue it's also a correct answer. Feature selection and dimensionality reduction simplify the data we use to train our models. We use these steps to remove redundant or irrelevant information, therefore getting a simpler dataset that should perform better than a more complex one.

In summary, Tiara's manager was correct on the first two but was incorrect on the last two.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Ensemble Learning Algorithm Complexity and Occam???s Razor](https://machinelearningmastery.com/ensemble-learning-and-occams-razor/)
* [How does Occam's razor apply to machine learning?](https://www.techopedia.com/how-does-occams-razor-apply-to-machine-learning/7/33087)
* The [Occam's razor](https://en.wikipedia.org/wiki/Occam%27s_razor) definition in Wikipedia.</p></details>

-----------------------

## Date - 2022-05-20


## Title - Emma's list


### **Question** :

Nothing is perfect.

And no matter how much they said otherwise, Emma knew that gradient descent was no exception.

They have been discussing some of the most popular optimization algorithms for neural networks, and the team didn't want to listen despite Emma's comments regarding some of the downsides of gradient descent.

Emma decided to post a detailed list of problems on the company's Slack channel.

**Which of the following practical issues of gradient descent deserve to be on Emma's list?**


### **Choices** :

- Gradient descent can take a long time to converge to a local minimum.
- There's no guarantee that gradient descent will converge to the global minima.
- Gradient descent is susceptible to the initialization of the network's weights.
- Gradient descent is not capable of optimizing continuous functions.


### **Answer** :

<details><summary>CLICK ME</summary><p>1110</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Gradient descent is one of the most popular optimization algorithms used in machine learning applications. But, despite its popularity, there are several practical issues that Emma wanted to mention.

The first issue is how gradient descent updates the model parameters after calculating the derivatives for all the observations. When working with large datasets, finding a local minimum may take a long time because the algorithm needs to compute many gradients before making a single update. [Stochastic Gradient Descent](https://en.wikipedia.org/wiki/Stochastic_gradient_descent) (SGD), a variation of gradient descent, works differently and updates the model parameters for each observation speeding up the process. Since the team is focusing on gradient descent, the first choice made it to Emma's list.

The second choice is also on the list. Assuming the are multiple local minima in a problem, there is no guarantee that gradient descent will find the global minimum. Here is an excerpt from ["Gradient Descent,"](http://www.cs.umd.edu/~djacobs/CMSC426/GradientDescent.pdf) a publication from the Computer Science Department of the University of Maryland:

> When a problem is nonconvex, it can have many local minima. And depending on where we initialize gradient descent, we might wind up in any of those local minima since they are all fixed points.

But it doesn't end there. As the previous quote mentions, gradient descent is also susceptible to the initialization of the network's weights. Assuming there are multiple local minima, the initialization of the network weights will play a fundamental role in whether the algorithm finds the global minimum: it may converge to a less optimal solution if we initialize the network too far from the global minimum. Therefore, the third choice is also a correct answer.

Finally, gradient descent can optimize a continuous function with no issues, so the fourth choice is not a correct answer.

In summary, Emma included the first three choices on her list.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Gradient Descent](http://www.cs.umd.edu/~djacobs/CMSC426/GradientDescent.pdf) is a deep dive into gradient descent and its variants from the Computer Science Department of the University of Maryland.
* [Problems with Gradient Descent](https://www.encora.com/insights/problems-with-gradient-descent)
* [Gradient Descent For Machine Learning](https://machinelearningmastery.com/gradient-descent-for-machine-learning/)</p></details>

-----------------------

## Date - 2022-05-21


## Title - Zoe's looking into KNN


### **Question** :

It was the first time Zoe dealt with k-Nearest Neighbors (KNN). She inherited the code, and now she was responsible for making it work.

Before touching the code, she decided to do some research. Her first stop was on one of the fundamental topics in machine learning: bias, variance, and their relationship with the algorithm.

She knows there's always a tradeoff between these two.

**Which of the following statements are correct concerning the bias and variance tradeoff of KNN?**


### **Choices** :

- Zoe can increase the bias of KNN by using a larger value of `k`.
- Zoe can increase the variance of KNN by using a larger value of `k`.
- Zoe can decrease the bias of KNN by using a smaller value of `k`.
- Zoe can decrease the variance of KNN by using a smaller value of `k`.


### **Answer** :

<details><summary>CLICK ME</summary><p>1010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>[KNN](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) is an algorithm with low bias and high variance. 

Let's imagine Zoe decides to use a small value of `k`, for example, `k=1`. In this case, the algorithm will likely predict the training dataset perfectly. The smaller the value of `k`, the less bias and larger variance KNN will show. This, of course, is not a great outcome because the model will overfit and have difficulty predicting unseen data.

Now let's assume Zoe decides to use a very large value of `k`; for example, set `k` to the number of samples on her training dataset. This will increase the algorithm's bias and reduce its variance, resulting in an underfit model that can't adequately capture the variance in the training dataset. Here is a quote from ["Why Does Increasing k Decrease Variance in kNN?"](https://towardsdatascience.com/why-does-increasing-k-decrease-variance-in-knn-9ed6de2f5061):

> If we take the limit as k approaches the size of the dataset, we will get a model that just predicts the class that appears more frequently in the dataset [...]. This is the model with the highest bias, but the variance is 0 [...]. High bias because it has failed to capture any local information about the model, but 0 variance because it predicts the exact same thing for any new data point.

As Zoe suspects, neither case will lead to a proper solution. She needs to find the appropriate tradeoff between the bias and variance of the algorithm.

In summary, the smaller the value of `k` is, the lower the bias and higher the variance. The larger the value of `k` is, the higher the bias and lower the variance. This means that the first and third choices are correct: we can control the algorithm's bias as explained in these two choices.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Why Does Increasing k Decrease Variance in kNN?"](https://towardsdatascience.com/why-does-increasing-k-decrease-variance-in-knn-9ed6de2f5061) is a really good article diving into the relationship of `k` and the variance of KNN.
* For a more general introduction to the bias-variance trade-off, check ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/).
* In case you prefer Twitter threads with a summary of how this works, check out ["Bias, variance, and their relationship with machine learning algorithms."](https://twitter.com/svpino/status/1506964069646884864)</p></details>

-----------------------

## Date - 2022-05-22


## Title - The 3-sigma accuracy


### **Question** :

Clara and her team are working on a drone localization project.

They have developed a neural network model that uses drone cameras to determine its position in the world so the drone can come back and land at the same spot it took off.

Clara was discussing the latest evaluation results with her colleagues when Jan mentioned that their latest model reached a 3-sigma accuracy of 20cm. 

Clara is new to the industry, and _"3-sigma accuracy of 20cm"_ didn't make much sense.

**What does a "3-sigma accuracy of 20cm" mean in this context?**


### **Choices** :

- In 66.6% of the cases, the model's error is less than 20cm
- In 68.2% of the cases, the model's error is less than 20cm
- In 95.4% of the cases, the model's error is less than 20cm
- In 99.7% of the cases, the model's error is less than 20cm


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The 3-sigma accuracy is a common way to quantify the accuracy of a model when estimating a continuous variable. Here is a quote from [Wikipedia's explanation of the 68 - 95 - 99.7 rule](https://en.wikipedia.org/wiki/68%E2%80%9395%E2%80%9399.7_rule):

> In the empirical sciences, the so-called three-sigma rule of thumb (or 3?? rule) expresses a conventional heuristic that nearly all values are taken to lie within three standard deviations of the mean, and thus it is empirically useful to treat 99.7% probability as near certainty.

We can often assume that the error of estimating a continuous variable (such as the drone's position) follows the normal distribution. If we denote the standard deviation of the normal distribution as ?? (sigma), then 68.2% of the samples should fall in the region from -1?? to 1?? around the mean.

![Standard deviation](https://user-images.githubusercontent.com/1126730/169593614-ee0ecdf7-a262-41b3-943f-5ae6865afcc8.png)

If we take a larger range from -2?? to 2??, then 95.4% of a normally distributed dataset will fall in this interval. Finally, a 3?? interval will cover 99.73% of the samples.

Therefore, when we talk about a 3-sigma accuracy of 20cm, we mean that 99.73% of the model predictions are more accurate than 20cm (because they fall in the -3?? to 3?? interval). Thus, the correct answer is the fourth choice.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- [Normal distribution](https://en.wikipedia.org/wiki/Normal_distribution#Standard_deviation_and_coverage)
- [68???95???99.7 rule](https://en.wikipedia.org/wiki/68%E2%80%9395%E2%80%9399.7_rule)</p></details>

-----------------------

## Date - 2022-05-23


## Title - Scheduled learning


### **Question** :

A company???a bad one, because there are plenty of those out there???has been experiencing some turnaround, and they wanted to ensure the new team members were up to speed with the neural network model they were using in production.

The team has been looking at the code and writing notes every time they find something new.

They stumbled upon the training scripts and noticed the last team used a learning rate scheduler.

**Which of the following statements could explain why the last team used this scheduler? Select all that apply.**


### **Choices** :

- The last team used the learning rate scheduler to increase the learning rate as training progressed.
- The last team used the learning rate scheduler to decrease the learning rate as training progressed.
- The last team used the learning rate scheduler to give the network a better chance to converge.
- The last team used the learning rate scheduler to save the learning rate at specific intervals during the training process.


### **Answer** :

<details><summary>CLICK ME</summary><p>0110</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>When training a neural network, setting the hyperparameters of the optimizer is essential for getting good results. One of the most critical parameters is the [learning rate](https://en.wikipedia.org/wiki/Learning_rate). Setting the learning rate too high or too low will cause problems during training.

A simple way to think about the learning rate is as follows: if we set it too low, the training process will be very slow; it will take a long time for the network to converge. Conversely, if we use a learning rate that's too high, the process will oscillate around the minimum without converging. Here is a chart from ["Deep Learning Wizard"](https://www.deeplearningwizard.com/deep_learning/boosting_models_pytorch/lr_scheduling/) illustrating the effect of different learning rates:

![Differences in learning rates](https://user-images.githubusercontent.com/1126730/167927199-f6a2add7-91be-4bc6-8459-bf00ff0ea4b6.png)

A popular technique to find a good balance is to use a learning rate scheduler. This predefined schedule adjusts the learning rate between epochs or iterations as the training progresses.

The most common scenario is to start with a high learning rate and decrease it over time. In the beginning, we take significant steps towards the minimum but move more carefully as we hone in on it. 

Looking at the available choices, we can see the first choice is incorrect, but the second and third choices are correct. The team was likely trying to decrease the learning rate as training progressed. Although there are experiments showing the use of [cyclical learning rates](https://arxiv.org/abs/1506.01186), the most common practice when using a scheduler is to start with a high learning rate and reduce it over time.

Finally, the fourth choice is incorrect as well. A learning rate scheduler has nothing to do with saving the learning rate. 

In summary, the second and third choices are the correct answers to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- ["Learning Rate Scheduling"](https://d2l.ai/chapter_optimization/lr-scheduler.html) is a great introduction to learning rate schedulers.
- ["How to Choose a Learning Rate Scheduler for Neural Networks?"](https://neptune.ai/blog/how-to-choose-a-learning-rate-scheduler) is an article from [Neptune AI](https://neptune.ai/), focusing on some practical ideas on how to use schedulers.
- ["Cyclical Learning Rates for Training Neural Networks"](https://arxiv.org/abs/1506.01186) is the paper discussing a technique to let the learning rate cyclically vary between reasonable boundary values.</p></details>

-----------------------

## Date - 2022-05-24


## Title - Balancing bias and variance


### **Question** :

The very first chapter of her machine learning book was about bias, variance, and their tradeoff. 

Callie knew that she had no alternative: she had to spend the time trying to understand these concepts before moving on.

But at the end of the day, it wasn't easy to remember the nuances of each concept, so Callie decided to get help.

**Which of the following descriptions of bias and variance are correct?**


### **Choices** :

- Bias refers to the assumptions a model makes to simplify the process of finding answers. The more assumptions it makes, the more biased the model is.
- Variance refers to the assumptions a model makes to simplify finding answers. The more assumptions it makes, the more variance in the model.
- Bias refers to how much the answers given by the model will change if we use different training data. The model has low bias if the answers stay the same regardless of the data.
- Variance refers to how much the answers given by the model will change if we use different training data. The model has low variance if the answers stay the same regardless of the data.


### **Answer** :

<details><summary>CLICK ME</summary><p>1001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Every machine learning algorithm deals with three types of errors: 
* Bias error 
* Variance error 
* Irreducible error 

To answer this question, let's forget about the irreducible error and focus on the other two.

Here is what [Jason Brownlee](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) has to say about _bias_:
> Bias are the simplifying assumptions made by a model to make the target function easier to learn.

Think about a simple linear model. It assumes that the target function is linear, so the model will try to fit a line through the data regardless of its appearance. This assumption helps the model simplify the process of finding the answer, and the more assumption it makes, the more biased the model is. Often, linear models are high-bias, and nonlinear models are low-bias.

Here is a [funny depiction of biases](https://xkcd.com/2618/): the speaker believes everyone must understand selection bias. Whenever we put people in buckets to characterize or predict how they act, we use our biases to simplify our understanding of the world.

![An example of selection bias](https://user-images.githubusercontent.com/1126730/168139417-8e5d8ce5-929e-4f8f-96a1-80232d61c73e.png)

Regarding variance, [Jason](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) continues:
> Variance is the amount that the estimate of the target function will change if different training data is used.

Variance refers to how much the answers given by the model will change if we use different training data. The model has low variance if the answers stay the same regardless of the data. 

Think about a fickle person that constantly changes their mind with the news. Every new article makes the person believe something completely different. I don't want to overextend the analogy, but this is an example of high variance. Often, linear models are low-variance, and nonlinear models are high-variance.

If we consider all of this, the first and fourth choices are the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Here is Jason Brownlee's article I mentioned before: ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/).
* The Wikipedia page on bias and variance is also a good resource: ["Bias???variance tradeoff"](https://en.wikipedia.org/wiki/Bias???variance_tradeoff).
* In case you like the simplicity of Twitter threads, here is one for you about this topic: ["Bias, variance, and their relationship with machine learning algorithms"](https://twitter.com/svpino/status/1390969728504565761).</p></details>

-----------------------

## Date - 2022-05-25


## Title - Cutting down features


### **Question** :

When Nicole finished collecting the data, she realized that there were just too many features.

She was staring at hundreds of potential variables, and it was evident that any model would have a hard time navigating them. Nicole knew that she had to reduce the dimensionality of her dataset.

Dimensionality reduction algorithms reduce the number of input variables in a dataset to find a lower-dimensional representation that still preserves the salient relationships in the data.

**Which of the following are dimensionality reduction techniques that Nicole could use?**


### **Choices** :

- Singular Value Decomposition
- Principal Component Analysis
- Linear Discriminant Analysis
- Isomap Embedding


### **Answer** :

<details><summary>CLICK ME</summary><p>1111</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Every one of these is a valid dimensionality reduction technique.

The problem doesn't specify the type of data that Nicole is using, so it's hard to determine which of these techniques will be most effective, but every one of them could be potentially valuable.

Therefore, all choices are correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Singular value decomposition](https://en.wikipedia.org/wiki/Singular_value_decomposition)
* [Understanding Dimension Reduction with Principal Component Analysis (PCA)](https://blog.paperspace.com/dimension-reduction-with-principal-component-analysis/)
* [Linear Discriminant Analysis ??? Bit by Bit](https://sebastianraschka.com/Articles/2014_python_lda.html)
* [Dimension Reduction - IsoMap](https://blog.paperspace.com/dimension-reduction-with-isomap/)</p></details>

-----------------------

## Date - 2022-05-26


## Title - But why deep learning?


### **Question** :

Martin met an old friend for a coffee.

They discussed Martin's latest work on image classification using deep learning. While Martin's friend used to work in computer vision 12 years ago, he is not aware of any of the latest developments.

He asks Martin why deep learning is so successful in image classification compared to the classical computer vision methods. He's heard that deep learning is better but doesn't understand why.

**If Martin wanted to summarize his reasoning with one sentence, which of the following is the best way to explain why deep learning is better for computer vision tasks?**


### **Choices** :

- Deep neural networks have many fully connected layers making the model more powerful.
- Deep neural networks can learn the best features for the task, while traditional methods rely on engineered features.
- Deep learning methods can use much larger datasets and achieve better performance.
- Deep learning algorithms can take advantage of GPUs, and we can therefore train much larger and more powerful models.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>These options explain why deep learning methods can achieve good results on computer vision tasks, but not all explain why deep learning is better than classical computer vision methods.

Having more data and algorithms optimized for GPUs can improve the results of a model. However, this is not exclusive to deep learning methods. Many traditional machine learning models can handle large datasets and take advantage of GPUs. Therefore, neither the third nor fourth choices correctly explain why deep learning is better for computer vision tasks.

The first choice is also incorrect. Although deep learning models can use many fully connected layers, the main benefits when solving computer vision problems come from using specialized layers???like convolutional layers???and not fully connected ones.

Finally, traditional computer vision methods typically rely on pre-computed features. Contrast this with [Convolutional Neural Networks](https://en.wikipedia.org/wiki/Convolutional_neural_network) and [Vision Transformers](https://en.wikipedia.org/wiki/Vision_transformer), which can learn features directly from the dataset and don't need pre-computed features to provide good results.

The ability to learn powerful features is one of the main reasons for the superior performance of deep learning methods in computer vision, making the second choice the best explanation for Martin's friend.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- Here is an introduction to ["Convolutional Neural Networks"](https://en.wikipedia.org/wiki/Convolutional_neural_network).
- And this is the introduction to ["Vision Transformers"](https://en.wikipedia.org/wiki/Vision_transformer).
- ["Learned Features"](https://christophm.github.io/interpretable-ml-book/cnn-features.html) is an excellent explanation covering the features that we can learn using convolutional layers.
- Check out ["OpenAI Microscope"](https://openai.com/blog/microscope/) for a fascinating look at the visual features inside a neural network.</p></details>

-----------------------

## Date - 2022-05-27


## Title - Choosing a loss function


### **Question** :

Ariana and Zach need to compute how different their model predictions are from the expected results.

They have been going back and forth between two different loss functions: Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE). These two metrics have properties that will shine depending on the problem they want to solve.

**Which of the following is the correct way to think about these two metrics?**


### **Choices** :

- RMSE penalizes larger differences between the predictions and the expected results.
- RMSE is significantly faster to compute than MAE.
- From both metrics, RMSE is the only one indifferent to the direction of the error.
- From both metrics, MAE is the only one indifferent to the direction of the error.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>When we train a machine learning model, we need to compute how different our predictions are from the expected results. For example, if we predict a house's price as `$150,000`, but the correct answer is `$200,000`, our "error" is `$50,000`.

There are multiple ways we can compute this error, but two common choices are:
* RMSE ??? [Root Mean Squared Error](https://en.wikipedia.org/wiki/Root-mean-square_deviation)
* MAE ??? [Mean Absolute Error](https://en.wikipedia.org/wiki/Mean_absolute_error)

These have different properties that will shine depending on the problem we want to solve. Remember that the optimizer will use this error to adjust the model. We want to set up the right incentives so the model learns appropriately.

Let's focus on a critical difference between these two metrics. Remember the "squared" portion of the RMSE? You are "squaring" the difference between the prediction and the expected value. Why is this relevant?

Squaring the difference "penalizes" larger values. If you expect a prediction to be 2, but you get 10, using RMSE, the error will be (2 - 10)?? = 64. However, if you get 5, the error will be (2 - 5)?? = 9. Do you see how it penalizes larger errors?

MAE doesn't have the same property. The error increases proportionally with the difference between predictions and target values. Understanding this is important to decide which metric is better for each case. 

Predicting a house's price is a good example where `$10,000` off is twice as bad as `$5,000`. We don't necessarily need to rely on RMSE here, and MAE may be all we need. 

But predicting the pressure of a tank may work differently. While 5 psi off may be within the expected range, 10 psi off may be a complete disaster. Here "10" is much worse than just two times "5", so RMSE may be a better solution.

Looking at the first choice, we already know it is a correct answer. RMSE penalizes larger differences between predictions and expected results.

Looking at both formulas, RMSE has extra squaring and root squaring operations, so it can't be faster to compute than MAE. The second choice is, therefore, not correct.

The third choice states that RSME is indifferent to the direction of the error, but MAE isn't. This is not correct: MAE uses the absolute value of the error, so both negative and positive values will end up being the same.

The fourth choice states that MAE is indifferent to the direction of the error, but RMSE isn't. This is not correct either: RMSE squares the error, so both negative and positive values will be the same.

In summary, the only correct answer to this question is the first choice.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["RMSE vs MAE, which should I use?"](https://stephenallwright.com/rmse-vs-mae/) this is a great summary by Stephen Allwright about the properties of these two functions and how you should think about them.
* ["Root-mean-square deviation"](https://en.wikipedia.org/wiki/Root-mean-square_deviation) is the Wikipedia page covering RMSE.
* ["Mean absolute error"](https://en.wikipedia.org/wiki/Mean_absolute_error) is the Wikipedia page covering MAE.</p></details>

-----------------------

## Date - 2022-05-28


## Title - Rolling down the hill


### **Question** :

Brooklyn was dealing with a complex problem. Although gradient descent was working relatively well, she read that adding momentum could benefit her use case.

Brooklyn needed to justify spending more time on this problem, so she wrote an email summarizing her reasoning behind using momentum, hit send, and patiently waited for her manager to respond.

**Which of the following statements are some of the reasons that Brooklyn included in her email?**


### **Choices** :

- Momentum helps when there's a lot of variance in the gradients.
- Momentum helps overcome local minima.
- Momentum helps the training process converge faster.
- Momentum helps when there aren't flat regions in the search space.


### **Answer** :

<details><summary>CLICK ME</summary><p>1110</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>There's a problem with [gradient descent](https://en.wikipedia.org/wiki/Gradient_descent): it depends entirely on the gradients it computes along the way, so whenever there's a lot of variance in these gradients, the algorithm can bounce around the search space making the optimization process slower.

Adding [momentum](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#Momentum) to gradient descent will help overcome this problem. Here is Jason Brownlee on ["Gradient Descent With Momentum from Scratch"](https://machinelearningmastery.com/gradient-descent-with-momentum-from-scratch/):

> Momentum involves adding an additional hyperparameter that controls the amount of history (momentum) to include in the update equation, i.e. the step to a new point in the search space. 

This parameter will help gradient descent accelerate in one direction based on past updates. A good analogy is a ball rolling down the hill. The more momentum it gains, the faster the ball will move in the direction of travel. If we have noisy gradients, momentum will help dampen the noise and keep the algorithm moving in the correct direction. Therefore, the first choice is correct.

This explanation also helps understand why the third choice is correct as well. Having gradients with a lot of variance will cause gradient descent to spend a long time bouncing around, while adding momentum will straighten the direction of the search. This will lead to faster convergence.

Momentum helps the optimization overcome small local minima by rolling past them. Going back to our example of a ball rolling down the hill, the more momentum it has, the more likely it will be to overcome small dips in the ground. This makes the second choice correct as well.

Finally, the fourth choice is not correct because momentum does help with flat regions in the search space. In the same way it can overcome small dips in the surface, momentum can help gradient descent get past a flat region by continuing its previous movement. Here is [Jason Brownlee](https://machinelearningmastery.com/gradient-descent-with-momentum-from-scratch/) again:

> (...) momentum is helpful when the search space is flat or nearly flat, e.g. zero gradient. The momentum allows the search to progress in the same direction as before the flat spot and helpfully cross the flat region.

In summary, the first three choices are correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- ["Gradient Descent With Momentum from Scratch"](https://machinelearningmastery.com/gradient-descent-with-momentum-from-scratch/) covers this question very well and includes practical examples of how to implement momentum.
- ["Momentum"](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#Momentum) is the Wikipedia page covering momentum as part of [Stochastic Gradient Descent](https://en.wikipedia.org/wiki/Stochastic_gradient_descent).
- The ["Deep Learning"](https://amzn.to/3CSjPkR) book by Goodfellow, et. al. is a fantastic source covering this topic.</p></details>

-----------------------

## Date - 2022-05-29


## Title - Choosing the wrong metric


### **Question** :

Let's assume you are working with a severely imbalanced dataset. 

We've all been there. It's a pretty typical scenario.

Now let's imagine you want to split the data into two categories using a classification learning algorithm.

It's hard to pick the best evaluation metric for this problem if we don't know what we want to accomplish. But at least we can rule out the ones that we shouldn't use.

**Which of the following metrics should you avoid using when evaluating your model's performance?**


### **Choices** :

- Recall
- Precision
- F1-Score
- Accuracy


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Let's illustrate this with a hypothetical example. 

Let's imagine that your team wants to build a machine learning model to predict whether a specific car will get in an accident. 

You are pretty funny, so you decide to play a prank on everyone else by committing this as a solution to the problem:

```
def is_the_car_going_to_crash_today():
    return False
```

Your team evaluates the model against a test set, and your dummy code is 99% accurate!

The National Safety Council reports that the odds of being in a car crash in the United States are less than 1%. This means that even the dumb function above will be very accurate!

The problem here is probably obvious by now: Accuracy is not a good metric when you face a very imbalanced problem. You can achieve very high accuracy even with a model that does nothing useful.

Some examples of imbalanced problems:
* Detecting fraudulent transactions
* Classifying spam messages
* Determining if a patient has cancer

The other three metrics will give you much more information than accuracy, depending on the problem and how you want to approach it.

In summary, the fourth choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Random Oversampling and Undersampling for Imbalanced Classification](https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/)
* Check ["Failure of Classification Accuracy for Imbalanced Class Distributions"](https://machinelearningmastery.com/failure-of-accuracy-for-imbalanced-class-distributions/) to understand why accuracy fails when working with imbalanced datasets.
* If you are into Twitter, [here is a much more detailed story](https://twitter.com/svpino/status/1357302018428256258) about predicting crashes with 99% accuracy.</p></details>

-----------------------

## Date - 2022-05-30


## Title - A non-boring government job


### **Question** :

Nobody thought that Hazel's job was going to be this interesting.

Her first assignment working for the government was in a lab, but not any lab. She was working with bright people on audio surveillance applications.

A week in and she got a package with maximum urgency. The government recorded a known terrorist at a coffee shop, but unfortunately, the audio was almost inaudible because the music was playing simultaneously.

Hazel needs to clean the audio so they can listen to the target.

**Which of the following techniques should Hazel use?**


### **Choices** :

- Hazel could use Independent Component Analysis to reveal the mixed-signal sources from the audio recording.
- Hazel could use a clustering algorithm to cluster the voice and the music apart on the audio recording.
- Hazel could use supervised learning to identify the signal coming from the voice from the signal coming from the music.
- There's not a good way to clean the audio.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>This problem is known as the "Cocktail Party Problem," where we need to separate two independent but previously mixed audio sources. If we make some assumptions, Hazel should be able to solve this problem.

Let's go straight to the correct answer: [Independent Component Analysis](https://en.wikipedia.org/wiki/Independent_component_analysis) (ICA) is a dimensionality reduction algorithm that should do the trick for Hazel. Here is a quote and an image depicting the problem from ["A Tutorial on Independent Component Analysis"](https://arxiv.org/pdf/1404.2986.pdf):

> Solving blind source separation using ICA has two related interpretations ??? filtering and dimensional reduction. (...) Filtering data based on ICA has found many applications (...), most notably audio signal processing.

![ICA](https://user-images.githubusercontent.com/1126730/169366606-b019ba62-7999-45a1-8c37-abe333e8f932.png)

Keep in mind that, for ICA to work, the source signals have to be independent of each other and not normally distributed. 

Using a clustering algorithm to separate both signals sounds like something that could potentially work, even if for a constrained use case. I wouldn't be surprised if clustering has been used before for this purpose, but I couldn't find any successful examples of solving the Cocktail Party Problem using clustering, so this is not a correct answer for this question.

The third choice argues for a supervised algorithm. I can see a scenario where we could model the problem in a way that a dataset and a trained neural network help us separate the sources, but this doesn't seem like a viable alternative for this case. I didn't find any examples about this either, so this choice is also incorrect.

In summary, the first choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [A Tutorial on Independent Component Analysis](https://arxiv.org/pdf/1404.2986.pdf)
* [Cocktail Party Problem - Eigentheory and Blind Source Separation Using ICA](https://gowrishankar.info/blog/cocktail-party-problem-eigentheory-and-blind-source-separation-using-ica/)
* [Independent component analysis](https://en.wikipedia.org/wiki/Independent_component_analysis)</p></details>

-----------------------

## Date - 2022-05-31


## Title - Fewer false negatives


### **Question** :

Allison is the Chief Data Scientist of the hospital, and she's been leading a revolutionary machine learning application to help identify patients that could potentially develop a rare disease.

The main goal of the model is to identify every patient that's prone to developing the condition. Allison has worked very hard to reduce the number of false negatives as much as possible.

**From the following list, select every accurate statement describing Allison's situation.**


### **Choices** :

- Allison has worked hard to ensure her model has high sensitivity.
- Sensitivity is the same as the True Positive Rate of the model.
- Higher sensitivity means that the model minimizes the number of false negatives.
- Allison can compute the True Positive Rate of her model by dividing the number of patients that could develop the disease by all patients selected as positive by the model.


### **Answer** :

<details><summary>CLICK ME</summary><p>1111</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The problem gives us an important clue about what Allison has been doing: she wants to reduce the number of false negatives as much as possible.

Let's start from the beginning and work on this problem step by step. 

A positive sample represents a patient that could develop the disease, and a negative sample represents a patient that will not develop it. Allison wants to reduce the number of false negatives, which is the number of patients that could become sick, but the model misses. In other words, if a patient could become ill and the model misses it, the hospital won't be able to offer treatment, so Allison wants to make sure that happens as infrequently as possible.

Sensitivity refers to the probability of selecting a patient as positive if the person has a genuine chance of developing the disease. We can compute sensitivity by dividing every true positive patient by every patient we think is positive. In short, `sensitivity = TP / P`. 

A model with high sensitivity minimizes the number of false negatives. To get here, we can look back at the formula for sensitivity and break down positive samples (P) into True Positives (TP) + False Negatives (FN). This will give us that `sensitivity = TP / (TP + FN)`. The more False Negatives we have, the lower the sensitivity, so a high-sensitive model keeps false negatives as low as possible.

Allison wants to keep the number of false negatives down, so she wants a high-sensitive model. This makes the first and third choices correct answers to this question.

Finally, we can compute the model's [True Positive Rate](https://www.ibm.com/docs/en/cloud-paks/cp-data/4.0?topic=overview-true-positive-rate-tpr) (TPR) as `TPR = TP / P`. Notice how this is the same formula we use to calculate sensitivity, so we can conclude that the second choice is also correct. The fourth choice's description of True Positive Rate is conveniently also accurate.

In summary, every single choice of this question is correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Everything you need to know about [Sensitivity and specificity](https://en.wikipedia.org/wiki/Sensitivity_and_specificity) you can find in Wikipedia.
* ["Machine Learning ??? Sensitivity vs Specificity Difference"](https://vitalflux.com/ml-metrics-sensitivity-vs-specificity-difference/) is a great article covering the differences between these two concepts.</p></details>

-----------------------

## Date - 2022-06-01


## Title - The Fukushima nuclear disaster


### **Question** :

The Fukushima nuclear disaster was the most severe nuclear accident since Chernobyl. Together, they have been the only ones with a level 7 classification on the International Nuclear and Radiological Event Scale.

In 2011, an earthquake followed by a tsunami caused the disaster in the Japanese plant, and it all traces back to a mistake in the safety model.

The engineers used historical earthquake data to build a regression model to determine the likelihood of significant earthquakes. Instead of using the accepted [Gutenberg-Richter](https://en.m.wikipedia.org/wiki/Gutenberg%E2%80%93Richter_law) model, they saw a kink in the data and assumed the appropriate regression was not linear but polynomial.

The correct linear model would have predicted that earthquakes of 9.0 magnitude were 70 times more likely than what the incorrect polynomial model predicted. But the engineers, in their pursuit of following the data too closely, came up with a very different conclusion.

The plant was designed to withstand a maximum earthquake of 8.6 magnitude and a tsunami as high as 5.7 meters. The earthquake of 2011 measured 9.0 and resulted in a 14-meter high tsunami.

**How would you summarize the mistake made by the engineers in this incident?**


### **Choices** :

- The engineers built a model that wasn't powerful enough and ended up underfitting the historical earthquake data.
- The engineers built a model that wasn't powerful enough and ended up overfitting the historical earthquake data.
- The engineers built a model that was too powerful and ended up overfitting the historical earthquake data.
- The engineers built a model that was too powerful and ended up underfitting the historical earthquake data.


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>When designing the model, the engineers saw a kink in the data. A linear model couldn't follow those data points closely, so they switched to a more complex, polynomial model.

The most important result of the [Gutenberg-Richter law](https://en.m.wikipedia.org/wiki/Gutenberg%E2%80%93Richter_law) is that the relationship between the magnitude of an earthquake and the logarithm of the probability that it happens is linear. The engineers ignored this.

This is a devastating example of overfitting. Here is an excerpt from [Berkeley's machine learning crash course](https://ml.berkeley.edu/blog/posts/crash-course/part-4/):

> As the name implies, overfitting is when we train a predictive model that "hugs" the training data too closely. In this case, the engineers knew the relationship should have been a straight line, but they used a more complex model than they needed to.

The third choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Fukushima: The Failure of Predictive Models](https://mpra.ub.uni-muenchen.de/69383/1/MPRA_paper_69383.pdf)
* [Machine Learning Crash Course: Part 4](https://ml.berkeley.edu/blog/posts/crash-course/part-4/)
* [Gutenberg???Richter law](https://en.m.wikipedia.org/wiki/Gutenberg%E2%80%93Richter_law)</p></details>

-----------------------

## Date - 2022-06-02


## Title - Classifying waste


### **Question** :

A group of students decided to build an application to classify household waste using smartphone pictures.

They want to start with a simple solution, so they are focusing the first version on the most commonly found types of waste: liquid, solid, organic, recyclable, and hazardous waste.

The tricky part of the application is that it needs to recognize every type of waste present on every image uploaded by users.

The students decided to use a convolutional neural network to solve this problem. The only question left is on the best way to architect it.

**Which of the following would be the best approach to design this network?**


### **Choices** :

- The output layer of the network should have a softmax activation function. The loss function should be categorical cross-entropy.
- The output layer of the network should have a sigmoid activation function. The loss function should be binary cross-entropy.
- The output layer of the network should have a softmax activation function. The loss function should be binary cross-entropy.
- The output layer of the network should have a sigmoid activation function. The loss function should be categorical cross-entropy.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The students are trying to build a [multi-label classification](https://en.wikipedia.org/wiki/Multi-label_classification) model. In multi-label classification, every image might show multiple types of waste. This is different from [multi-class classification](https://en.wikipedia.org/wiki/Multiclass_classification), where a photo would show only one kind of waste.

When building multi-label classification models, we need an output layer where every class is independent. Remember that we can have more than one active class for each input. The softmax activation function doesn't work because it uses every score to output the probabilities of each class. Softmax is the correct output for multi-class classification but not for multi-label classification problems. 

Since we shouldn't use softmax, the first and third choices are incorrect. The sigmoid function converts output scores to a value between 0 and 1, independently of all the other scores.

Multi-label classification problems borrow the same principles from binary classification problems. The difference is that we end up with multiple sigmoid outputs instead of a single one. In our example problem, we have a combination of five different binary classifiers. This is why we should use a binary cross-entropy as the loss function.

In summary, multi-class classification models should use a softmax output with the categorical cross-entropy loss function. Multi-label classification models should use a sigmoid output and the binary cross-entropy loss function.

The second choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* The Wikipedia explanation of [Multi-label classification](https://en.wikipedia.org/wiki/Multi-label_classification) should give you most of what you need to understand for this type of task.
* ["Difference between multi-label classification and multi-class classification"](https://towardsdatascience.com/multi-label-image-classification-with-neural-network-keras-ddc1ab1afede) is an excellent article comparing these two types of problems.
* ["How to choose cross-entropy loss function in Keras?"](https://androidkt.com/choose-cross-entropy-loss-function-in-keras/) explains the differences between the loss functions that we discussed in this question.</p></details>

-----------------------

## Date - 2022-06-03


## Title - Everyone on the same page


### **Question** :

Willow overheard her two friends arguing about the best way to handle a few categorical features on their dataset.

One suggested Label encoding, while the other was pushing for One-Hot encoding. Both are popular encoding techniques, but Willow didn't know enough to understand the difference.

She decided to write a quick summary of both techniques to get everyone on the same page, but the discussion had her confused. She came up with two different explanations for each method, but she wasn't sure which one was correct. 

**Which of the following statements are correct about these two encoding techniques?**


### **Choices** :

- One-Hot encoding replaces each label from the categorical feature with a unique integer based on alphabetical ordering.
- One-Hot encoding creates additional features based on the number of unique values in the categorical feature.
- Label encoding replaces each label from the categorical feature with a unique integer based on alphabetical ordering.
- Label encoding creates additional features based on the number of unique values in the categorical feature.


### **Answer** :

<details><summary>CLICK ME</summary><p>0110</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Before analyzing this question, we need to understand what "categorical data" means.

Categorical data are variables that contain label values rather than numeric values. For example, a variable representing the weather with values "sunny," "cloudy," and "rainy" is a categorical variable.

Although some algorithms can use categorical data directly, the majority can't: they require the data to be numeric. We can use One-Hot or Label encoding to do this.

[One-Hot encoding](https://hackernoon.com/what-is-one-hot-encoding-why-and-when-do-you-have-to-use-it-e3c6186d008f) creates a new feature for each unique value of the original categorical variable.

For example, assume we have a dataset with a single feature called "weather" that could have the values "sunny," "cloudy," and "rainy." Applying One-Hot Encoding will get us a new dataset with three features, one for each value of the original "weather" column. 

A sample that had the value "cloudy" in the previous column will now have the value 0 for both "sunny" and "rainy" and the value 1 under the "cloudy" feature.

This means that the second choice is the correct explanation of how One-Hot Encoding works.

On the other hand, [Label encoding](https://www.mygreatlearning.com/blog/label-encoding-in-python/) replaces each categorical value with a consecutive number starting from 0. 

For example, Label Encoding would replace our weather feature with a new one containing the values 0 instead of "cloudy," 1 instead of "rainy," and 2 instead of "sunny."

This means that the third choice is the correct explanation of how Label Encoding works.

Therefore, the second and third choices are the correct answers to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["What is One Hot Encoding? Why and When Do You Have to Use it?"](https://hackernoon.com/what-is-one-hot-encoding-why-and-when-do-you-have-to-use-it-e3c6186d008f) is an excellent introduction to One-Hot encoding.
* ["Label Encoding in Python Explained"](https://www.mygreatlearning.com/blog/label-encoding-in-python/) is an introduction to Label encoding.
* ["One-Hot Encoding vs. Label Encoding using Scikit-Learn"](https://www.analyticsvidhya.com/blog/2020/03/one-hot-encoding-vs-label-encoding-using-scikit-learn/) covers both techniques and when to use each one.</p></details>

-----------------------

## Date - 2022-06-04


## Title - Cutting down neurons


### **Question** :

Denise had an idea she wanted to try on the neural network she built to identify handwritten digits.

Her output layer had 10 neurons, one for each digit she wanted to
recognize. She thought she could optimize the training process by cutting the number of neurons down to 4.

The goal of the model was to recognize the digit represented by an input image, and with 4 neurons, she could encode a total 16 different values, so she thought this was enough.

After training for some time, Denise found out that the network didn't perform well.

**What conclusions can you draw from Denise's experience?**


### **Choices** :

- To get better results, Denise should experiment with different optimization algorithms and learning rate values.
- Denise's network is working correctly. She can improve the results by modifying her evaluation criteria and discarding any mistakes due to the extra capacity supported by her new architecture.
- With this architecture, the first output neuron has to decide what the most significant bit of the digit represented by the image was. Unfortunately, there's no apparent relationship between the shapes that make up a digit and this information.
- Instead of replacing the 10-neuron layer, Denise should have kept it as a hidden layer and added the 4-neuron layer as the new output. The new network should be capable of finding the bitwise representation of the digit without much trouble.


### **Answer** :

<details><summary>CLICK ME</summary><p>0011</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>In his excellent book [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/chap1.html#a_simple_network_to_classify_handwritten_digits), [Michael Nielsen](https://twitter.com/michael_nielsen) presents this problem and his results after trying both architectures:

> The ultimate justification is empirical: we can try out both network designs, and it turns out that, for this particular problem, the network with 10 output neurons learns to recognize digits better than the network with 4 output neurons. 

But why does the 10-neuron output network outperforms the 4-neuron output network?

> If we had 4 outputs, then the first output neuron would be trying to decide what the most significant bit of the digit was. And there's no easy way to relate that most significant bit to simple shapes (...) It's hard to imagine that there's any good historical reason the component shapes of the digit will be closely related to (say) the most significant bit in the output.

This means that the third choice is a correct explanation of what's happening to Denise with her new architecture. She won't solve the problem by exploring alternate optimization functions or experimenting with different learning rate values. Her architecture is fundamentally flawed.

The fourth choice is a potential avenue that Denise could use to improve the results. She could keep the original layer with 10 neurons to identify the correct digit but add the extra 4-neuron layer as the output to find the digit's binary representation. The network should have no issues solving this problem.

In summary, the third and fourth choices are the correct answer.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Using neural nets to recognize handwritten digits"](http://neuralnetworksanddeeplearning.com/chap1.html#a_simple_network_to_classify_handwritten_digits) is Michael Nielsen's book chapter that discusses this problem.
* ["But what is a neural network?"](https://www.youtube.com/watch?v=aircAruvnKk) is a YouTube video with one of the best explanations out there about how neural networks work.</p></details>

-----------------------

## Date - 2022-06-05


## Title - Regression x 4


### **Question** :

Here are four popular machine learning methods.

Imagine you want to build a simple binary classification model. Your goal is to predict whether a sample is positive or negative.

You could make any of these four algorithms give you the results you want with enough work. That's awesome, but you are interested in the easiest way to make this happen.

**Which of these four algorithms would you use?**


### **Choices** :

- Linear regression
- Lasso regression
- Logistic regression
- Random Forest regression


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The correct answer is Logistic regression. 

[Logistic regression](https://en.wikipedia.org/wiki/Logistic_regression) is an excellent fit for binary classification tasks. It outputs the probability of one event, in our case, the probability of a sample being positive.

All other methods are used to perform regression, in which the algorithm will predict a continuous outcome. We, however, want a categorical output, so logistic regression is the best approach.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- Check out ["Logistic Regression for Machine Learning"](https://machinelearningmastery.com/logistic-regression-for-machine-learning/) for an introduction to Logistic regression.
- ["Logistic Regression"](https://en.wikipedia.org/wiki/Logistic_regression) is the Wikipedia page introducing logistic regression.
- For a list and a quick introduction to regression algorithms, check out ["5 Regression Algorithms you should know ??? Introductory Guide!"](https://www.analyticsvidhya.com/blog/2021/05/5-regression-algorithms-you-should-know-introductory-guide/)</p></details>

-----------------------

## Date - 2022-06-06


## Title - Supervised learning workshop


### **Question** :

Lydia is going to be teaching a new machine learning class.

Among other things, she will be covering Supervised Learning techniques. Lydia knows how important this is, so she is preparing to turn the class into a giant hands-on workshop.

The University has access to many different datasets, and Lydia decides to pick a few interesting problems with enough data for students to explore.

**Which of the following problems should Lydia pick to teach supervised learning?**


### **Choices** :

- Determine whether a website displays content for a mature audience.
- Learn the best way to split a group of car buyers into different categories based on their buying patterns.
- Given the medical records from patients suffering a specific illness, learn whether we can split them into different groups for better treatment.
- Predict next year's crop yields taking into account data of the past decade.


### **Answer** :

<details><summary>CLICK ME</summary><p>1001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>There are always multiple ways to approach these problems, but some are better for [supervised learning](https://en.wikipedia.org/wiki/Supervised_learning), while others can benefit from [unsupervised learning](https://en.wikipedia.org/wiki/Unsupervised_learning).

To answer this question, we need to assume that the datasets from the university are labeled when necessary. Remember that supervised learning algorithms require these labels.

Let's start with the first choice. Given any website, we want a "Yes" or "No" answer depending on whether the site displays mature content. Lydia could tackle this problem with a binary classification algorithm, which is a supervised learning technique. 

Splitting a group of car buyers into different categories requires a technique that helps Lydia cluster buyers based on their buying patterns. We can't foresee these patterns beforehand, so any problem that involves finding out the best way of grouping samples is a good fit for clustering algorithms. [Clustering](https://en.wikipedia.org/wiki/Cluster_analysis) is an unsupervised learning technique, so this option is not a good fit for supervised learning. 

The same happens with the problem related to the medical records. We don't have a predefined set of categories to split the group of patients, so this problem seems to be more amenable to clustering techniques.

Finally, predicting next year's crop yields seems a good candidate for a regression algorithm. Regression algorithms are supervised learning techniques that help us predict a continuous value???in this case, how much a crop will yield. This is another valid answer to this question.

In summary, the first and fourth choices are the correct answers.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Supervised and Unsupervised Machine Learning Algorithms"](https://machinelearningmastery.com/supervised-and-unsupervised-machine-learning-algorithms/) is an excellent introduction to the differences between supervised and unsupervised learning.
* Check out ["Customer Segmentation with Machine Learning"](https://towardsdatascience.com/customer-segmentation-with-machine-learning-a0ac8c3d4d84) for more information about how to tackle problems where we need to cluster samples into groups.</p></details>

-----------------------

## Date - 2022-06-07


## Title - Making email fun


### **Question** :

Let's be honest: dealing with email is not fun.

Waking up to an inbox full of unsolicited messages is the worst way to kick off your day. Email applications do their best, but a lot of spam still gets through the cracks.

How about building your own personalized spam detection model? 

One morning, Sue decided to do it, and after a few iterations, she ended with a working model.

Time to find out how good it is!

**Which method should Sue use to evaluate her spam detection model?**


### **Choices** :

- Sue should use the model's accuracy as defined by the percentage of legitimate messages that go through with respect to the total number of received emails.
- Sue should use the model's recall as defined by the percentage of detected spam messages with respect to the total of spam messages received.
- Sue should use the F??-Score of the model with a high value of ??.
- Sue should use the F??-Score of the model with a low value of ??.


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Spam detection is an imbalanced problem: you will always have more legitimate emails than spam emails. 

Whenever you need to work with an imbalanced dataset, accuracy will not be a good metric to decide how good your model is. You can achieve very high accuracy even with a model that does nothing useful. For example, if only 1% of the emails you receive are spam, by simply assuming none of it is spam, your model will be 99% accurate. Therefore, the first choice is not a good approach for Sue.

The recall is a helpful metric to understand how much spam you can detect, but by itself could also be deceiving. For example, Sue's model could flag every single email message as spam, which will give her a 100% recall. This, of course, it's not helpful, so the second choice is also not correct.

Using the [F??-Score](https://en.wikipedia.org/wiki/F-score), however, is a good choice. 

The F?? score lets us combine precision and recall into a single metric. When using ?? = 1, we place equal weight on precision and recall. For values of ?? > 1, recall is weighted higher than precision; for values of ?? < 1, precision is weighted higher than recall. 

You are probably familiar with F1-Score. F1-Score is just F??-Score with ?? = 1.

Sue doesn't want to flag valid legitimate messages as spam. Doing this runs the risk of people missing important emails. Therefore, a good strategy is to prioritize a system with high precision, so using a lower value of ?? is the way to go. Therefore, the correct answer is the fourth choice.

Notice that by prioritizing the precision of her model, Sue will let some spam messages through. Although this is not ideal, it's a better outcome than getting the spam filter to catch legitimate emails.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["What is the F-Score?](https://deepai.org/machine-learning-glossary-and-terms/f-score) is a short introduction to this metric.
* For a more in-depth analysis of the F??-Score, check ["A Gentle Introduction to the Fbeta-Measure for Machine Learning"](https://machinelearningmastery.com/fbeta-measure-for-machine-learning).
* Check ["Failure of Classification Accuracy for Imbalanced Class Distributions"](https://machinelearningmastery.com/failure-of-accuracy-for-imbalanced-class-distributions/) to understand why accuracy fails when working with imbalanced datasets.</p></details>

-----------------------

## Date - 2022-06-08


## Title - Non-linearities


### **Question** :

River learned an important lesson when trying to implement a neural network from scratch: 

For her network to learn anything useful, she needed to introduce non-linearities.

Whenever she didn't do it, the results were utter trash.

**Which of the following will add non-linearities to River's neural network?**


### **Choices** :

- Using Rectifier Linear Unit (ReLU) as an activation function.
- Adding convolution operations to the network.
- Using Stochastic Gradient Descent to train the network.
- Implementing the backpropagation process.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>For a neural network to learn complex patterns, we need to ensure that the network can approximate any function, not only linear ones. This is why we call it "non-linearities."

The way we do this is by using activation functions. 

An interesting fact: the [Universal approximation theorem](https://en.wikipedia.org/wiki/Universal_approximation_theorem) states that, when using non-linear activation functions, we can turn a two-layer neural network into a universal function approximator. This is an excellent illustration of how powerful neural networks are.

Some of the most popular activation functions are [sigmoid](https://en.wikipedia.org/wiki/Logistic_function), and [ReLU](https://machinelearningmastery.com/rectified-linear-activation-function-for-deep-learning-neural-networks). Therefore, the first choice is the correct answer to this question.

The second choice is incorrect; a [convolution operation is a linear operation](https://en.wikipedia.org/wiki/Convolution#Properties). You can check [this answer](https://ai.stackexchange.com/questions/19879/arent-all-discrete-convolutions-not-just-2d-linear-transforms) in Stack Exchange for an excellent explanation.

Finally, neither Stochastic Gradient Descent nor backpropagation has anything to do with the linearity of the network operations. Therefore, they aren't correct answers.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Activation function"](https://en.wikipedia.org/wiki/Activation_function) from Wikipedia to understand more about this topic.
* I find the ["Universal approximation theorem"](https://en.wikipedia.org/wiki/Universal_approximation_theorem) fascinating.</p></details>

-----------------------

## Date - 2022-06-09


## Title - Accuracy as a loss function


### **Question** :

Luna knows that the entire goal of gradient descent is to minimize the value of a function. The lower its value, the better the model will be. She has been thinking about designing a custom loss function for her use case.

She wants to use the inverse of the model's accuracy as the loss function. This way, the model will try to minimize the number of mistakes it makes by looking directly at the accuracy of the predictions.

Unfortunately, she soon discovers that this doesn't work. 

**What is the problem with this approach?**


### **Choices** :

- Accuracy is not a differentiable function, so it can't be optimized using gradient descent.
- Luna wants to optimize for high accuracy but gradient descent is a minimization algorithm; the opposite of what she needs.
- Minimizing the inverse of the accuracy is a very slow process because of the extra computations needed to compute the final value.
- Gradient descent only works with a predefined set of loss functions.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>We use loss functions to optimize a model. We use accuracy to measure the performance of that model.

Usually, we can see how the accuracy of a classification model increases as the loss decreases. This is not always the case, however. The loss and the accuracy measure two different aspects of a model. Two models with the same accuracy may have different losses. 

An important insight: The loss function must be continuous, but accuracy is discrete. When training a neural network with gradient descent, we need a differentiable function because the algorithm can't optimize non-differentiable functions. One of the required characteristics for a function to be differentiable is that it must be continuous. Since accuracy isn't, we can't use it.

This makes the first choice the correct answer to this question.

The second and third choices assume that we can use accuracy as the loss function one way or the other, so they are incorrect. The fourth choice claims that gradient descent can only work with a predefined subset of functions, which is also wrong.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- ["Loss and Loss Functions for Training Deep Learning Neural Networks"](https://machinelearningmastery.com/loss-and-loss-functions-for-training-deep-learning-neural-networks/) is a great introduction to loss functions.
- Check ["How to Choose Loss Functions When Training Deep Learning Neural Networks"](https://machinelearningmastery.com/how-to-choose-loss-functions-when-training-deep-learning-neural-networks/) for a guide on how to choose and implement different loss functions.</p></details>

-----------------------

## Date - 2022-06-10


## Title - Psychologists speak another language


### **Question** :

A group of psychologists is visiting the office, and Scarlett is in charge of showing them around.

The first stop will be in the Data Science department. They are very excited about showing them the results of their latest machine learning model.

Ten minutes into the presentation, it's painfully apparent that the crew is not fully grasping what is going on. Scarlett decides to summarize her ideas using a familiar language: statistics.

In statistics, the notion of statistical error is an integral part of hypothesis testing. There are two types of errors when testing the null hypothesis: type I and type II errors. Scarlett wants to explain their results regarding the latter.

**Do you remember what the correct definition of a type II error is?**


### **Choices** :

- A type II error occurs when the null hypothesis is true and is not rejected.
- A type II error occurs when the null hypothesis is true but is rejected.
- A type II error occurs when the null hypothesis is false but is not rejected.
- A type II error occurs when the null hypothesis is false and is rejected.


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>It makes sense for those who are more used to machine learning terminology to compare type I and type II errors with false positives and false negatives.

Type I errors are the same as false positives. For example, if we mark a valid email as spam, we are in the presence of a false positive. Type I errors are the rejection of a true [null hypothesis](https://www.investopedia.com/terms/n/null_hypothesis.asp) by mistake.

Type II errors are the same as false negatives. For example, if we let a spam message pass as a valid email, we are in the presence of a false negative. This is a type II error because we accept the conclusion of the email being good, even though it is incorrect. Type II errors are the acceptance of a false null hypothesis by mistake.

In other words, a type II error is when we incorrectly accept the null hypothesis even though the alternative hypothesis is true. Therefore, The third choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["What Is a Null Hypothesis?"](https://www.investopedia.com/terms/n/null_hypothesis.asp) covers the basics you need to understand before going into hypothesis testing.
* Check out ["Type I and type II errors"](https://en.wikipedia.org/wiki/Type_I_and_type_II_errors) for the definition and examples of each type of error. 
* ["Understanding Null Hypothesis Testing"](https://opentextbc.ca/researchmethods/chapter/understanding-null-hypothesis-testing/) is an excellent article about hypothesis testing.</p></details>

-----------------------

## Date - 2022-06-11


## Title - Penelope is looking for more


### **Question** :

Penelope needs to finish her homework. The final step is to make her neural network "deeper."

She tried to solve the problem using a shallow network architecture, but her professor wanted her to try a deeper network.

**What should Penelope do to turn her architecture into a deep neural network?**


### **Choices** :

- Penelope should increase the dimensionality of the input data.
- Penelope should add more layers to the network.
- Penelope should use images, text, voice, or video as the input.
- Penelope should add more neurons to the existing layers.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>A deep neural network is an artificial neural network with multiple layers between the input and output layers. The more layers we add, the "deeper" the network becomes.

A deep neural network can process all sorts of data. Neither the type of input nor its dimensionality has any relationship with the depth of the network. Therefore, neither the first nor the third choices are correct.

Adding neurons alone doesn't change the depth of the network either. It does change its capacity, but a network with the same number of layers but more neurons will still have the same depth. 

The only choice for Penelope is to add more layers to the network.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Wikipedia's definition of ["Deep neural networks"](https://en.wikipedia.org/wiki/Deep_learning#Deep_neural_networks) serves as a succinct summary of what deep neural networks are.
* Check ["A Layman???s Guide to Deep Neural Networks"](https://towardsdatascience.com/a-laymans-guide-to-deep-neural-networks-ddcea24847fb) for a non-mathematical introduction to deep neural networks.</p></details>

-----------------------

## Date - 2022-06-12


## Title - Low-variance model


### **Question** :

Usually, the best approach is to start experimenting with a few different algorithms to narrow down the possibilities and pick a good path forward.

That's what Sophia did. She ran her dataset through four different algorithms and noticed something peculiar.

Since she had a lot of data, she trained each algorithm with different batches separately. Only one of the models gave consistent results regardless of what portion of the data she used.

Sophia knew this was a variance issue. Low-variance models usually produce consistent results regardless of the data used to train them.

**Which of the following algorithms was the one giving consistent results?**


### **Choices** :

- Support Vector Machine (SVM)
- Decision Trees
- Logistic Regression
- k-Nearest Neighbors (KNN)


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Every machine learning algorithm deals with three types of errors: bias, variance, and irreducible error. We need to focus specifically on the variance error to answer this question.

Here is what [Jason Brownlee](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) has to say about variance: "Variance is the amount that the estimate of the target function will change if different training data was used."

In other words, variance refers to how much the answers given by the model will change if we use different training data. The model has low variance if the answers stay the same when using different portions of our training dataset.

Generally, linear models with little flexibility have low variance. For example, Linear and logistic regression are low-variance models. Nonlinear algorithms with a lot of flexibility have high variance, for example, Decision Trees, Support Vector Machines, and k-Nearest Neighbors.

Therefore, the third choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) is Jason Brownlee's article covering bias, variance, and their tradeoff.
* The Wikipedia page on bias and variance is also a good resource: ["Bias???variance tradeoff"](https://en.wikipedia.org/wiki/Bias???variance_tradeoff).
* In case you like the simplicity of Twitter threads, here is one for you about this topic: ["Bias, variance, and their relationship with machine learning algorithms"](https://twitter.com/svpino/status/1390969728504565761).</p></details>

-----------------------

## Date - 2022-06-13


## Title - Looking for labels


### **Question** :

The company had a lot of data, but none was labeled. 

As soon as the team started planning the work, Blake's first recommendation was to look into Supervised Learning. She knew, however, that without labeled data, they weren't going anywhere.

There are many different ways to produce labels, and Blake will have to decide how to move forward.

**Which of the following techniques could Blake use to label the data?**


### **Choices** :

- Assemble a team of people that go through the data and label each sample.
- Use feedback from an existing process to automatically produce the labels.
- Use a Supervised Learning technique to infer the labels directly from the existing data.
- Use Semi-Supervised Learning to propagate labels across all of your data.


### **Answer** :

<details><summary>CLICK ME</summary><p>1100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>If Blake wants to use a Supervised Learning method, she has no other option than to produce labels for the data. There are many different techniques she can use to accomplish this.

The most common way to label data is to use human labelers. Blake could assemble a team that will go through each sample assigning the appropriate label. For example, assuming the company wants to classify car pictures, the labelers could review each image and set the correct make and model of the car. Therefore, the first choice is correct.

Sometimes, we can use feedback from an existing process to create labels, also known as "direct labeling." For example, a video site recommending movies to different users can use actual clicks from its audience to determine which posters work and which don't. 

Unfortunately, direct labeling is very dependent on your use case, and it's not something you can always do. Also, notice that direct labeling doesn't necessarily capture the "true ground-truth," but only a useful approximation. Nevertheless, direct labeling is a good approach, so the second choice is correct.

The third choice argues that we could use a Supervised Learning method to infer the labels from the existing dataset, but this doesn't make sense. Supervised Learning requires the existence of labels, and that's what Blake doesn't have. If we could use the data to predict labels, we could also use it to solve the problem in the first place. This choice is incorrect.

Finally, we could use [Semi-Supervised Learning](https://machinelearningmastery.com/semi-supervised-learning-with-label-propagation/) assuming we already have a few labels. For example, if we had 10% of the labels, we could build a model to generate the other 90% of labels. However, there's no indication that Blake has any labeled data, so Semi-Supervised Learning is not an option. This choice is also incorrect.

[Active Learning](https://rapidminer.com/glossary/active-learning-machine-learning/) and [Weak Supervision](https://snorkel.ai/weak-supervision/) are also techniques to generate labels. They aren't part of this question, but it's helpful to know about them.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* The ["Machine Learning Data Lifecycle in Production"](https://www.coursera.org/learn/machine-learning-data-lifecycle-in-production) course in Coursera, part of the [Machine Learning Engineering for Production (MLOps) Specialization](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops).
* Check out ["Semi-Supervised Learning With Label Propagation"](https://machinelearningmastery.com/semi-supervised-learning-with-label-propagation/) for an introduction to how to use a few labels with semi-supervised learning.
* ["Active Learning in Machine Learning"](https://rapidminer.com/glossary/active-learning-machine-learning/) is a short explanation of Active Learning, enough if all you need is a high-level overview.
* If you are serious about Active Learning, ["Active Learning Literature Survey"](https://burrsettles.com/pub/settles.activelearning.pdf) is the publication you want to read. 
* ["Weak Supervision: A New Programming Paradigm for Machine Learning"](http://ai.stanford.edu/blog/weak-supervision/) is a good article from Stanford introducing Weak Supervision.
* An introduction to [Weak Supervision](https://snorkel.ai/weak-supervision/) by Snorkel AI, a labeling platform. This one even includes a video.</p></details>

-----------------------

## Date - 2022-06-14


## Title - Rebecca's rotation


### **Question** :

After a very late coffee, Rebecca felt plenty of energy to crack open the book she's been dreading to read the entire week.

It was a dense read. A computer vision masterpiece that went all the into the mathematical reasoning behind every topic.

The latest chapter combined deep learning, linear algebra, and geometric transformations. Rebecca promised herself to watch a movie as soon as she finished the first problem on the topic.

It seemed straightforward: Rebecca had to rotate a two-dimensional square 90 degrees counterclockwise using matrix multiplication. She knew she had to multiply the coordinates of her square with a specific 2x2 matrix, but she didn't remember how exactly it worked.

**Which of the following is the correct matrix R to rotate a 2D square 90 degrees counterclockwise?**


### **Choices** :

- The matrix R is `[[0, -1], [1, 0]]`.
- The matrix R is `[[0, 1], [-1, 0]]`.
- The matrix R is `[[1, 0], [0, 1]]`.
- The matrix R is `[[-1, 0], [0, -1]]`.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>At its core, deep learning mostly boils down to many tensor operations chained together. These operations have a corresponding geometric interpretation, and understanding them is an excellent exercise to shed some light on how deep learning networks work.

When we talk about [rotating](https://en.wikipedia.org/wiki/Rotation_(mathematics)) an object, we can think of moving each point of that object circularly around a center. Assuming that we use a column vector to represent the coordinate of each point, we can use matrix multiplication to rotate the object.

We need a rotation matrix R to multiply with the object's coordinates and obtain the new set of rotated coordinates. The structure of this matrix R to rotate an object counterclockwise is `[[cos(??), -sin(??)], [sin(??), cos(??)]]` where ?? represents the rotation angle.

Rebecca needs to rotate the 2D square 90 degrees. Remember that `cos(90) = 0` and `sin(90) = 1`, so the matrix R that Rebecca needs is `[[0, -1], [1, 0]]`, which is the first choice of this question.

Just for fun, we can go through all the other choices and determine what would be the corresponding rotation angle. 

The second choice rotates the 2D square 90 degrees clockwise???in the opposite direction that Rebecca wanted. Notice how the only difference with the correct answer is the position of the signs.

The third choice does not rotate the square????? is 0 degrees. To see this, let's start with the matrix `[[cos(??), -sin(??)], [sin(??), cos(??)]]` and assume we multiply it by a vector `[x, y]` to get a new, rotated vector `[x', y']`:

```
x' = x * cos(??) - y * sin(??)
y' = x * sin(??) + y * cos(??)
```

Replacing the values of each component as specified in the third choice:

```
x' = x * 1 - y * 0 = x - 0 = x
y' = x * 0 + y * 1 = 0 + y = y
```

Notice how we get the exact coordinates after we apply the rotation. 

Finally, the fourth choice rotates the square 180 degrees counterclockwise. 

In summary, the first choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Rotations and reflections in two dimensions"](https://en.wikipedia.org/wiki/Rotations_and_reflections_in_two_dimensions) for an explanation of how to rotate and reflect objects in a two-dimensional space.</p></details>

-----------------------

## Date - 2022-06-15


## Title - Two similar models


### **Question** :

One of the most critical steps in your machine learning process is selecting a good baseline.

Before you start looking into more complex problems, a simple baseline gives you a solid foundation to understand where you are and what improvements you can make.

Margot and Jan wanted to use a different algorithm to build their baseline. Jan wanted to go with a simple neural network, but Margot argued for using a linear regression model.

They didn't want to pick, so they decided to try each baseline and choose the best one. But before starting, Margot and Jan agreed to research the similarities between both models so they could reuse as much as possible when building them.

They wrote down a list.

**Which of the following are true about Jan's neural network and Margot's linear regression model?**


### **Choices** :

- Both models require every input feature to be a numeric value. Margot and Jan will need to transform every non-numeric feature to feed both baselines.
- Both models require every numerical input to be between 0 and 1. Margot and Jan will need to standardize every numeric feature and squeeze them into this range.
- Both models output a vector of probabilities. Margot and Jan can build a common logic to interpret the results of their respective baselines.
- Both models output the result of a linear sum of the weighted input values. Margot and Jan should be able to explain the results from their respective baselines in a similar fashion.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>I'd go with Margot on this one. A linear regression model sounds simpler to build a baseline than a neural network. The former is easy to set up and tune, while the latter will require much more work.

Of course, this is just a gut feeling. There's nothing on this problem that suggests one way or the other.

But that's not the question. We want to understand which of the four statements is something that both models have in common.

Starting with the first choice, both neural networks and linear regression models require the input features to be numeric. Neither works with categorical features. Decision Trees, for example, don't have this limitation, but these two models do. Therefore, Margot and Jan will need to transform non-numeric features before using them.

The second choice is interesting because it's usually the case that both models work better if their input features are appropriately scaled or standardized. Training a model with a feature ranging from 0 to 10,000 and another feature ranging from 0 to 1 is never a good recipe. However, neither one of these models requires features within 0 and 1, so this is not a correct statement.

The third choice is not correct either. The output of a linear regression model is a single numerical value, not a vector of probabilities. There's also no requirement for a neural network to have such an output. 

Finally, while both linear regression and neural networks use a linear sum of weighted inputs, neural networks introduce non-linearities in the form of activation functions. This is a crucial difference. It makes neural networks much more powerful than linear regression, but at the same time, it makes it much harder to explain the results.

In summary, the correct answer to this question is the first choice.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Linear Regression v.s. Neural Networks"](https://towardsdatascience.com/linear-regression-v-s-neural-networks-cd03b29386d4) for a comparison between these two techniques.
* ["3 Reasons Why You Should Use Linear Regression Models Instead of Neural Networks"](https://www.kdnuggets.com/2021/08/3-reasons-linear-regression-instead-neural-networks.html) is another great article talking about their differences.
* ["Linear Regression for Machine Learning"](https://machinelearningmastery.com/linear-regression-for-machine-learning/) is a great introduction to linear regression.
* ["Intro to Neural Networks"](https://developers.google.com/machine-learning/crash-course/introduction-to-neural-networks/video-lecture) is a good summary of neural networks.</p></details>

-----------------------

## Date - 2022-06-16


## Title - Samples per batch


### **Question** :

Gradient Descent is an optimization algorithm frequently used in machine learning applications.

The algorithm can vary in how many data samples we use to calculate the error: a single sample, all available samples, or a batch of samples (more than one but fewer than the entire dataset.)

Naomi read about "Mini-Batch Gradient Descent," and now she is trying to research how it works. 

**Which of the following statements is true about Mini-Batch Gradient Descent?**


### **Choices** :

- Mini-Batch Gradient Descent uses a single sample of data during every iteration.
- Mini-Batch Gradient Descent uses a batch of data (more than one sample but fewer than the entire dataset) during every iteration.
- Mini-Batch Gradient Descent uses all of the available data at once during every iteration.
- Mini-Batch Gradient Descent is an entirely different optimization algorithm, and Trevor shouldn't look at it as something related to Gradient Descent.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Here is a simplified explanation of how [Gradient Descent](https://en.wikipedia.org/wiki/Gradient_descent) works: We take samples from the training dataset, run them through the model, and determine how far our results are from what we expect. We then use this difference (error) to compute how much we need to update the model weights to improve the results.

A critical decision we need to make is how many samples we use to compute the gradient of the objective function. We have three choices:
* Use a single instance of data.
* Use all of the data at once.
* Use some of the data.

Using a single sample of data is called "Stochastic Gradient Descent" or SGD. Using all the data at once is called "Batch Gradient Descent." Finally, using some of the data???more than one sample but fewer than the entire dataset???is called "Mini-Batch Gradient Descent." 

Notice that we always make a tradeoff between the accuracy of the updates and the time it takes to calculate them. While using a single instance of data is faster, the updates will be more inaccurate. On the other hand, using all of the data available while producing more accurate updates requires storing the entire dataset in memory, and it's very slow.

In summary, the second choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["An overview of gradient descent optimization algorithms"](https://ruder.io/optimizing-gradient-descent/index.html#gradientdescentvariants) for a deep dive into gradient descent and every one of its variants.
* ["Gradient Descent For Machine Learning"](https://machinelearningmastery.com/gradient-descent-for-machine-learning/) is another great introduction to gradient descent.
* ["A Gentle Introduction to Mini-Batch Gradient Descent and How to Configure Batch Size"](https://machinelearningmastery.com/gentle-introduction-mini-batch-gradient-descent-configure-batch-size/) covers Batch and Mini-Batch Gradient Descent.</p></details>

-----------------------

## Date - 2022-06-17


## Title - Sorting tomatoes


### **Question** :

Maya's model caused a false alarm, and the tomato sorting line at the factory stopped working for the third time today.

Maya designed a computer vision model to estimate the size of tomatoes entering a sorting machine. The device has a problem handling unusually small or large tomatoes and can get damaged if one of these enters it.

Unfortunately, the factory didn't have the budget to replace the whole machine. So, they hired Maya to install a camera and implement a computer vision model to check the size of the tomatoes. If it detects a tomato that's too small or too large, the machine stops automatically and raises the alarm.

Whenever Maya's model predicts a regular-sized tomato as an outlier, the production line stops and costs the factory money. Maya suspects there is a problem with the loss function she is using.

**Which of the following loss functions should Maya use for this problem?**


### **Choices** :

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Huber Loss
- Binary Cross-entropy Loss


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Maya should focus on improving how the model handles outliers, and the loss function she is using plays an important role.

Loss functions like the [Mean Absolute Error ](https://en.wikipedia.org/wiki/Mean_absolute_error)(MAE) or the [Huber loss](https://en.wikipedia.org/wiki/Huber_loss) have a linear behavior for outliers. The [Mean Squared Error](https://en.wikipedia.org/wiki/Mean_squared_error) (MSE), on the other hand, penalizes errors quadratically, which means that significant outliers will get much higher penalties.

For example, consider Maya's model estimating the size of a 5cm tomato to be 15cm. The difference between the actual and predicted size is 10 if she uses MAE or the Huber loss, but it will become 100 if she uses MSE.

Therefore, if Maya uses MSE as the loss function, her model will optimize in a way that avoids significant outliers. Smaller errors are not critical in this case since she is only interested in very small or large tomatoes.

With this in mind, the first choice is the correct answer, while the second and the third are not. The fourth choice is the cross-entropy loss which doesn't apply to regression problems and is therefore incorrect.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Regression Metrics for Machine Learning"](https://machinelearningmastery.com/regression-metrics-for-machine-learning/) for an overview of some of the most popular metrics used for regression problems.
* ["RMSE vs MAE, which should I use?"](https://stephenallwright.com/rmse-vs-mae/) is a great summary by Stephen Allwright about the properties of these two functions and how you should think about them.
* For more information about the Huber loss, take a look at ["Huber Loss: Why Is It, Like How It Is?"](https://www.cantorsparadise.com/huber-loss-why-is-it-like-how-it-is-dcbe47936473).</p></details>

-----------------------

## Date - 2022-06-18


## Title - A dataset of car pictures


### **Question** :

This is the first team that Delilah manages.

She didn't have much experience as a manager, but she knew how important it's for a new team to nail down their process.

A couple of weeks in, the team is working on classifying different car makes and models from pictures captured with smartphones. 

As the first step, Delilah asked the team to ensure that each make and model of the cars they care about is properly represented in both the training and test sets. Delilah knows they need to avoid testing for classes that the model didn't see during training or vice versa.

**Which of the following is the correct term that refers to the process that Delilah asked her team to follow?**


### **Choices** :

- Delilah asked her team to cross-validate their dataset.
- Delilah asked her team to stratify their dataset.
- Delilah asked her team to validate their dataset.
- Delilah asked her team to bootstrap their dataset.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>[Stratified sampling](https://en.wikipedia.org/wiki/Stratified_sampling) is a method of splitting a dataset to produce splits that contain a properly balanced set of samples.

Delilah is working on a classification problem. In her case, stratified sampling will ensure that her training and test sets have approximately the same percentage of class samples as the complete set.

For example, let's assume the dataset has 10,000 pictures of Audis and 30,000 pictures of Hondas. Delilah would like to ensure that the team keeps this ratio when splitting the data into training and test sets. If the group selects 32,000 total images to train a model, Delilah would like to see 8,000 pictures of Audis (25%) and 24,000 of Hondas (75%.)

Therefore, the second choice is the correct answer to this question.

Something else to mention: there's a process called ["Stratified Cross-Validation."](https://towardsdatascience.com/what-is-stratified-cross-validation-in-machine-learning-8844f3e7ae8e) If you knew about this, you might have been tempted to select the first choice as a valid answer. Notice, however, that Delilah is not asking the team to validate a model yet. She is just focused on how to split the dataset.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Stratified sampling in Machine Learning"](https://medium.com/analytics-vidhya/stratified-sampling-in-machine-learning-f5112b5b9cfe) is a quick introduction to stratified sampling.
* Check ["What is Stratified Cross-Validation in Machine Learning?"](https://towardsdatascience.com/what-is-stratified-cross-validation-in-machine-learning-8844f3e7ae8e) for more information about stratified cross-validation.</p></details>

-----------------------

## Date - 2022-06-19


## Title - Helping Charlie with statistics


### **Question** :

There's a lot about machine learning that comes straight from statistics.

Charlie wasn't surprised when she started recognizing terms from her statistics course while reading a newly published paper. 

In statistics, the notion of statistical error is an integral part of hypothesis testing. There are two types of errors when testing the null hypothesis: type I and type II errors. The paper used both terms, and Charlie was already confused.

Let's help her out.

**Which of the following statements is correct about type I errors?**


### **Choices** :

- A type I error occurs when the null hypothesis is true and is not rejected.
- A type I error occurs when the null hypothesis is false but is not rejected.
- A type I error occurs when the null hypothesis is false and is rejected.
- A type I error occurs when the null hypothesis is true but is rejected.


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>It makes sense for those who are more used to machine learning terminology to compare type I and type II errors with false positives and false negatives.

Type I errors are the same as false positives. For example, if we mark a valid email as spam, we are in the presence of a false positive. Type I errors are the rejection of a true [null hypothesis](https://www.investopedia.com/terms/n/null_hypothesis.asp) by mistake.

Type II errors are the same as false negatives. For example, if we let a spam message pass as a valid email, we are in the presence of a false negative. This is a type II error because we accept the conclusion of the email being good, even though it is incorrect. Type II errors are the acceptance of a false null hypothesis by mistake.

Based on the above description, the fourth choice is the correct answer to this question: A type I error occurs when the null hypothesis is true but is rejected.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["What Is a Null Hypothesis?"](https://www.investopedia.com/terms/n/null_hypothesis.asp) covers the basics you need to understand before going into hypothesis testing.
* Check out ["Type I and type II errors"](https://en.wikipedia.org/wiki/Type_I_and_type_II_errors) for the definition and examples of each type of error. 
* ["Understanding Null Hypothesis Testing"](https://opentextbc.ca/researchmethods/chapter/understanding-null-hypothesis-testing/) is an excellent article about hypothesis testing.</p></details>

-----------------------

## Date - 2022-06-20


## Title - Kendall's interview


### **Question** :

Kendall showed up early to her interview.

She was fresh out of her Master's, and this was going to be her first job after school.

After a few pleasantries, the interviewer started talking about high-variance models and how they typically pay a lot of attention to the training data.

Kendall nodded and smiled while imagining the question that was coming. She didn't have to wait longer.

**Which of the following algorithms can be considered high-variance models?**


### **Choices** :

- Linear Regression
- Decision Trees
- Logistic Regression
- k-Nearest Neighbors (KNN)


### **Answer** :

<details><summary>CLICK ME</summary><p>0101</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Every machine learning algorithm deals with three types of errors: bias, variance, and irreducible error. We need to focus specifically on the variance error to answer this question.

Here is what [Jason Brownlee](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) has to say about variance: "Variance is the amount that the estimate of the target function will change if different training data was used."

In other words, variance refers to how much the answers given by the model will change if we use different training data. The model has high variance if the answers differ significantly when using different portions of our training dataset.

Generally, non-linear machine learning algorithms with a lot of flexibility are high variance. For example, Decision Trees and k-Nearest Neighbors are high-variance models. Linear models, on the other hand, are usually low-variance.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) is Jason Brownlee's article covering bias, variance, and their tradeoff.
* The Wikipedia page on bias and variance is also a good resource: ["Bias???variance tradeoff"](https://en.wikipedia.org/wiki/Bias???variance_tradeoff).
* In case you like the simplicity of Twitter threads, here is one for you about this topic: ["Bias, variance, and their relationship with machine learning algorithms"](https://twitter.com/svpino/status/1390969728504565761).</p></details>

-----------------------

## Date - 2022-06-21


## Title - The elbow method


### **Question** :

After using a clustering algorithm on her dataset, Veronica fell in love with how easy it was to set everything up, run it, and get quick results back. After years of experience with supervised learning methods, K-Means was a breath of fresh air.

It took her some time to go through the documentation, and while reading online, she kept bumping into the "elbow method." It was clear that she needed to understand more about it.

**Which of the following statements is true about the elbow method?**


### **Choices** :

- In cluster analysis, the elbow method is used to determine the existing biases in a dataset.
- In cluster analysis, the elbow method is used to select the outliers in a dataset.
- In cluster analysis, the elbow method is used to determine the optimal number of clusters.
- In cluster analysis, the elbow method is used to determine the features that better explain the patterns in a dataset.


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The story doesn't tell us, but I'm sure Veronica discovered something very early: No matter how many clusters she specified, the algorithm was happy to oblige. When she wanted 2 clusters, she got them. When she wanted 10, here they were.

The [elbow method](https://en.wikipedia.org/wiki/Elbow_method_(clustering)) is a way to determine the optimal number of clusters. 

Veronica is running K-means. She could run the algorithm on her dataset for a range of values of `k`, and for each value, calculate the sum of squared errors. Then, she could plot a line chart of these errors for each value of `k`. If the line chart [looks like an arm](https://en.wikipedia.org/wiki/Elbow_method_(clustering)#/media/File:DataClustering_ElbowCriterion.JPG), then the "elbow" on the arm is the best number of clusters (`k`) that she should use.

The elbow method is a way to choose the point where diminishing returns are no longer worth the cost. It's a very popular technique when using clustering algorithms.

Therefore, the third choice is the correct answer.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Using the elbow method to determine the optimal number of clusters for k-means clustering"](https://bl.ocks.org/rpgove/0060ff3b656618e9136b) for an explanation of how to use the elbow method.
* ["Elbow method (clustering)"](https://en.wikipedia.org/wiki/Elbow_method_(clustering)) is the Wikipedia page covering the elbow method.
* Check ["Knee of a curve"](https://en.wikipedia.org/wiki/Knee_of_a_curve) for a precise explanation of looking at the "elbow" of a curve.</p></details>

-----------------------

## Date - 2022-06-22


## Title - Claudia needed a walk


### **Question** :

After hours of work, Claudia decided to take a break.

She has been working on a model to classify music into different genres, and while her neural network is doing great during training, its accuracy struggles with the test data.

Claudia took a walk and came back with a fresh perspective. She wrote down a few strategies to approach the problem.

**Which of Claudia's strategies would you say is likely to help her solve the issue?**


### **Choices** :

- Decrease the complexity of the model by cutting down layers and reducing the number of neurons.
- Switch to a different optimization algorithm.
- Regularize the model.
- Increase the amount of training data.


### **Answer** :

<details><summary>CLICK ME</summary><p>1011</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Claudia's model is overfitting. 

Her model is doing great with the training data but struggling on the test set, which is a sign that her model is not generalizing well to unseen samples.

If Claudia decreases the complexity of the model, she could prevent the neural network from "memorizing" the training samples. Complex models tend to overfit because they have too much capacity. It's easier for them to memorize the training data instead of trying to generalize. Therefore, the first choice is a valid strategy to solve the problem.

Switching the optimization algorithm is unlikely to solve this problem. Nothing in the statement gives us any information about which algorithm Claudia is currently using, and we don't have any reason to believe it's not a good one. We also know that her model is learning the training data, which wouldn't be possible if the optimization algorithm wasn't appropriate.

Claudia could also use regularization techniques to help with overfitting. Regularization discourages the model from becoming too complex or flexible, which helps prevent the model from "memorizing" the training data.

Finally, there's a chance that the training data that Claudia is using doesn't fully capture the breadth of valid samples for her problem. In other words, her training dataset might not be enough to teach the model how to predict the test data correctly. In this case, adding more data to the training set gives Claudia a better chance to build a model that generalizes better.

The first, third, and fourth choices are good strategies to solve Claudia's problem.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Overfitting and Underfitting With Machine Learning Algorithms"](https://machinelearningmastery.com/overfitting-and-underfitting-with-machine-learning-algorithms/) for an introduction to overfitting and underfitting in machine learning.
* ["How to Solve Underfitting and Overfitting Data Models"](https://allcloud.io/blog/how-to-solve-underfitting-and-overfitting-data-models/) covers several strategies to solve overfitting and underfitting.</p></details>

-----------------------

## Date - 2022-06-23


## Title - Research vs production


### **Question** :

A common question among people new to artificial intelligence is about the path they would like to pursue.

Many opt for an academic role, where they can spend time doing research. Others prefer getting an industry job, where they get to experience putting machine learning systems into production.

Kathy isn't sure yet, so we will counsel her by highlighting some differences between both paths.

**Select every statement that correctly highlights the differences between machine learning modeling in a research environment versus production machine learning.**


### **Choices** :

- The data used in a research environment is usually static, while the data used in a production setting is dynamic and constantly shifting.
- The design priority in a research environment is usually higher performance???either the highest accuracy or other relevant metrics. Production environments put more emphasis on costs, scalability, and explainability.
- Research is usually not concerned with fairness, but fairness is crucial when building models in a production environment.
- When building machine learning models in a research environment, most of the work goes towards monitoring and maintaining models. In production environments, most of the work centers around the initial training and validation of the model.


### **Answer** :

<details><summary>CLICK ME</summary><p>1100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Kathy's story is not unique. In my experience, this is one of the most frequent questions I hear from people coming into the industry.

Although this question doesn't cover every difference, it's a good start, so let's start from the top.

Researchers like to test their work on popular datasets. This gives them a fair comparison with other existing methods and ensures its easy to reproduce their results. On the other hand, production data is constantly shifting. The datasets you used to train and test your models can quickly become obsolete. Therefore, the first choice is correct.

A lot of emphasis on academia centers around better algorithms and techniques. Can we solve this particular problem and do it more accurately? Can we do it faster? Research jobs are about inventing new methods and squeezing as much as we can from what we already know.

The focus on better techniques and algorithms leads to the main priority in many research positions: achieving better "performance." It could be about higher accuracy, a faster method, or fewer constraints. These, however, aren't usually the same concerns in the industry.

Production machine learning is generally more focused on the interpretability of results and the cost of the solution. "Higher accuracy" is not the most critical metric in many cases???it's still important but usually not at the expense of other factors. This is one of the main differences between a research position and an industry job. Therefore, the second choice is also correct.

Fairness is crucial. Yes, fairness is fundamental when putting machine learning into production, but it's equally necessary for any research environment. Therefore, the third choice is not correct.

Finally, in production environments, creating an initial model is just a small portion of work. After that, most of the time goes towards monitoring the model's results and maintaining it to combat [concept and data drift](https://evidentlyai.com/blog/machine-learning-monitoring-data-and-concept-drift). Conversely, in academia, the goal is usually to build a model. Since data is primarily static, models don't suffer any drift. Therefore, the fourth choice is incorrect.

In summary, the first and second choices are the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* The ["Machine Learning Data Lifecycle in Production"](https://www.coursera.org/learn/machine-learning-data-lifecycle-in-production) course in Coursera, part of the [Machine Learning Engineering for Production (MLOps) Specialization](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops).
* Check ["Why You Should Care About Data and Concept Drift"](https://evidentlyai.com/blog/machine-learning-monitoring-data-and-concept-drift) to understand the importance of monitoring machine learning models.
* ["A Gentle Introduction to Concept Drift in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-concept-drift-machine-learning/) is an excellent introduction to concept drift.</p></details>

-----------------------

## Date - 2022-06-24


## Title - Pruning the tree


### **Question** :

Ana has been scratching her head for a while.

She is using a Decision Tree on a dataset, and although her training performance is excellent, the test performance is terrible.

After discussing with her professor, the recommendation was to prune the tree, but Ana didn't understand why this would solve the problem.

**Which statements explain why pruning the tree will solve Ana's problem? Select all that apply.**


### **Choices** :

- By pruning the Decision Tree, Ana will increase the model's bias.
- By pruning the Decision Tree, Ana will increase the model's variance.
- By pruning the Decision Tree, Ana will decrease the model's bias.
- By pruning the Decision Tree, Ana will decrease the model's variance.


### **Answer** :

<details><summary>CLICK ME</summary><p>1001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>A Decision Tree is an algorithm with low bias and high variance. This means that a Decision Tree makes almost no assumptions about the target function.

Because of its high variance, Decision Trees tend to overfit easily to the training dataset. Ana saw this as soon as she tried the model on her test data.

To avoid overfitting, Ana should prune the tree. We force the tree to generalize better and make assumptions by reducing the number of nodes. In other words, by pruning the tree, we increase its bias and decrease its variance.

Therefore, the first and fourth choices are the correct answer.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) is an excellent introduction to the bias and variance tradeoff.
* The Wikipedia page on bias and variance is also a good resource: ["Bias???variance tradeoff"](https://en.wikipedia.org/wiki/Bias???variance_tradeoff).
* In case you like the simplicity of Twitter threads, here is one for you about this topic: ["Bias, variance, and their relationship with machine learning algorithms"](https://twitter.com/svpino/status/1390969728504565761).</p></details>

-----------------------

## Date - 2022-06-25


## Title - Accuracy is coming down


### **Question** :

Natalia is developing a computer vision model to classify images of birds using a CNN. 

She has a dataset of 20,000 images, split 50% into training and testing. The dataset is well balanced, containing an equal amount of bird and non-bird photos.

After some work, Natalia's model gets to around 90% accuracy, but she knows she can do better. It turns out that the model is not good at detecting birds from Madagascar, so Natalia asks her team to collect more data.

After several days, the data collection and labeling team provides 1,000 well-balanced new labeled images, which Natalia splits in half to extend the existing training and testing datasets.

The accuracy of the new model dropped to 88%.

**Which of the following is the approach that Natalia should follow to fix the problem?**


### **Choices** :

- There must be a problem with the labels on the last batch of 1,000 images from Madagascar. Natalia should work with the labeling team to correct the labels.
- The architecture of the CNN model is no longer valid for the new batch of data. Natalia should recalibrate the network to ensure she gets a better result.
- The accuracy here might not tell the story of what's happening. Natalia should evaluate the model on the original 10,000-image test dataset for a valid comparison.
- Better data always leads to a better model, so Natalia should review her code because the accuracy must improve or stay where it was.


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Natalia compared the 90% accuracy computed on the 10,000 test images to the 88% accuracy on the augmented test dataset containing 10,500 images. There is a problem with this.

What if the new images from Madagascar are just much more difficult for the network? Even if the model improved, Natalia would not realize it because the additional pictures are causing the overall accuracy to drop.

Here is a hypothetical scenario of two models illustrating how the new model could improve even when returning a lower accuracy:
* Old model's accuracy on the 10,000 test images: 90% (9,000 images correctly classified.)
* Old model's accuracy on the new 500 test images: 10% (50 images correctly classified.)
* New model's accuracy on the 10,000 test images: 91% (9,100 images correctly classified.)
* New model's accuracy on the new 500 test images: 28% (140 images correctly classified.)
* New model's accuracy on the 10,500 test images: 88% (9,240 images correctly classified.)

In this hypothetical example, the new model is better on the original 10,000 test images (from 90% to 91%) and the 500 new images (from 10% to 28%.) However, the approach used by Natalia to evaluate the results made us believe the model got worse (going down from 90% to 88% accuracy.)

This is called the [Simpson's paradox](https://en.wikipedia.org/wiki/Simpson%27s_paradox). When comparing two experiments, we need to make sure that we evaluate the same data or at least data having the same underlying distribution. If we change the distribution, we can't compare the results anymore and may take the wrong conclusion. Therefore, the third choice is the correct answer.

The wrong labels or architecture could be reasons for the model performing worse. However, we need to check if the model is performing worse in the first place, so assuming this is the case is premature.

The fourth choice is also not correct. Adding more data doesn't automatically mean better results.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Simpson's Paradox"](https://www.britannica.com/topic/Simpsons-paradox) for a complete explanation about the paradox.
* If you prefer videos, [watch this video](https://blog.chriszacharias.com/page-weight-matters) about the Simpson's Paradox.</p></details>

-----------------------

## Date - 2022-06-26


## Title - Rolling two dice


### **Question** :

I have a bag in front of me containing a 6-sided and a 12-sided dice.

My friend pulls one out at random, rolls it, and tells me that the result is 3. 

**What is the probability that my friend pulled out the 6-sided die?**


### **Choices** :

- The probability is 1/3
- The probability is 1/2
- The probability is 2/3
- The probability is 3/4


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Let's assume that `A` represents the event of rolling the die and getting a `3`, `B1` represents the event of pulling out the 6-sided die, and `B2` represents the event of pulling out the 12-sided die.

We can compute the probability of my friend holding the 6-sided die using the [Bayes theorem](https://en.wikipedia.org/wiki/Bayes%27_theorem):

```
P(B1|A) = (P(A|B1)*P(B1))/P(A)
P(B1|A) = (1/12)/P(A)

P(A) = P(A???B1)*P(B1)+P(A???B2)*P(B2)
P(A) = 1/12 + 1/24???
P(A) = 1/8

P(B1|A) = (1/12)/(1/8)
P(B1|A) = 2/3???
```

Thus, the answer is `2/3`.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["A Gentle Introduction to Bayes Theorem for Machine Learning"](https://machinelearningmastery.com/bayes-theorem-for-machine-learning/) is a great starting point to understand the Bayes theorem and how to use it.
* You can also check the Wikipedia page of [the Bayes theorem](https://en.wikipedia.org/wiki/Bayes%27_theorem).</p></details>

-----------------------

## Date - 2022-06-27


## Title - The attributes of a tensor


### **Question** :

A "tensor" is one of the most basic data structures used in machine learning systems. 

Let's go back to basics and focus on the fundamental characteristics of a tensor.

**Which of the following are valid attributes that represent a tensor?**


### **Choices** :

- Its number of axes. This attribute is also called the "rank" of the tensor.
- Its cardinality. This attribute represents the numerical relationship between the axes of the tensor.
- Its shape. This attribute represents how many dimensions the tensor has along each axis.
- Its data type. This attribute represents the type of values contained in the tensor.


### **Answer** :

<details><summary>CLICK ME</summary><p>1011</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Three primary attributes define a tensor:

1. Its rank, or the number of axes.
2. Its shape, or the number of dimensions per axis.
3. Its data type, or the type of data contained in it.

The rank of a tensor refers to the tensor's number of axes.

Examples:
* Rank of a matrix is 2.
* Rank of a vector is 1.
* Rank of a scalar is 0.

The shape of a tensor describes the number of dimensions along each axis.

Examples:
* `()` ??? scalar
* `(2,)` ??? vector 
* `(3, 2)` ??? matrix
* `(3, 2, 5)` ??? 3D tensor

The data type of a tensor refers to the kind of data contained in it.

Examples:
* `float32`
* `float64`
* `uint8`
* `int64`

The second choice mentions "the cardinality of a tensor" as "the numerical relationship between the axes of the tensor." This is not a correct answer. 

In summary,  the correct answer to the question is the first, third, and fourth choices.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Deep Learning with Python, Second Edition](https://amzn.to/3K3VZoy) covers the topic of tensors really well.
* Check ["A Gentle Introduction to Tensors for Machine Learning with NumPy"](https://machinelearningmastery.com/introduction-to-tensors-for-machine-learning/) for a quick introduction to tensors and practical code.</p></details>

-----------------------

## Date - 2022-06-28


## Title - Convolutions are the answer


### **Question** :

Jane is arguing with her colleague.

They are creating a neural network model to classify images uploaded to the company website. 

Jane wants to use a Convolutional Neural Network, but her colleague disagrees. Instead, he wants to keep things simple and use a fully-connected neural network. 

Jane feels that a Convolutional Neural Network is the right tool for the job, but how can she convince her colleague?

**What are the advantages of using a Convolutional Neural Network in this case?**


### **Choices** :

- Convolutional Neural Networks are usually shallower than fully-connected networks, making the training process easier and faster.
- Using a Convolutional Neural Network requires fewer parameters than a fully-connected network.
- The local structure of the image can be used more efficiently by a Convolutional Neural Network, resulting in much better features and performance.
- Convolutional Neural Networks can learn a hierarchy of visual features similar to the human brain, which results in better performance.


### **Answer** :

<details><summary>CLICK ME</summary><p>0111</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>A [Convolutional Neural Network](https://en.wikipedia.org/wiki/Convolutional_neural_network) (CNN) is a much better choice when dealing with image classification problems than a fully-connected network.

The first choice is not correct. A CNN is more time and memory efficient than a fully-connected network, so we can use deeper networks with many layers, which is impossible in a fully-connected network. You should always expect CNNs to be deeper than fully-connected networks.

CNNs require fewer parameters than fully-connected networks and reuse the same set of parameters over the whole image. The number of weights in a convolutional layer depends on the kernel size and number of channels and not on the image resolution. For example, in the [AlexNet architecture](https://en.wikipedia.org/wiki/AlexNet), the five convolutional layers are responsible for only 4% of the parameters of the network. In comparison, the final three fully-connected layers contain the remaining parameters. This makes the second choice a correct answer.

One reason CNNs are very effective in dealing with pictures is that they exploit the local structure of images. Since pixels located next to each other tend to be related, convolutional kernels can capture this information, making the third option a correct answer.

Finally, a CNN can learn visual features of increasing complexity. The initial layers typically learn to recognize low-level details, like edges and colors, while deeper layers can handle more complex structures like corners and patterns. The final layers of a CNN can learn complex representations like faces or any complex objects. Therefore, the fourth choice is correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["A Beginner???s Guide to Convolutional Neural Networks (CNNs)"](https://towardsdatascience.com/a-beginners-guide-to-convolutional-neural-networks-cnns-14649dbddce8) is a great introduction to CNNs.
* If you want to get deeper into how convolutions work, check out ["A guide to convolution arithmetic for deep learning"](https://arxiv.org/pdf/1603.07285.pdf).</p></details>

-----------------------

## Date - 2022-06-29


## Title - The black sheep


### **Question** :

Here you have a list containing three popular deep learning architectures.

But there's one black sheep. One of these is not a deep learning architecture.

**Can you determine which of the following doesn't belong on this list?**


### **Choices** :

- ImageNet
- AlexNet
- GoogleNet
- VGG16


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>While [AlexNet](https://www.analyticsvidhya.com/blog/2021/03/introduction-to-the-architecture-of-alexnet/), [GoogleNet](https://arxiv.org/abs/1409.4842v1), and [VGG16](https://arxiv.org/abs/1409.1556) are deep learning architectures, [ImageNet](https://www.image-net.org/) is an image database with millions of images, so it has nothing to do with the rest.

The first choice is the correct answer.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Introduction to The Architecture of Alexnet"](https://www.analyticsvidhya.com/blog/2021/03/introduction-to-the-architecture-of-alexnet/).
* ["Going Deeper with Convolutions"](https://arxiv.org/abs/1409.4842v1) is the paper introducing GoogleNet.
* ["Very Deep Convolutional Networks for Large-Scale Image Recognition"](https://arxiv.org/abs/1409.1556) is the paper introducing VGG16.
* Check the [ImageNet](https://www.image-net.org/) website for more information about one of the most popular public datasets in the world.</p></details>

-----------------------

## Date - 2022-06-30


## Title - 120 shirt combinations


### **Question** :

Amanda wants to buy the perfect shirt.

She knows somebody at a warehouse, so she pulls a favor one Sunday afternoon, and to her amusement, they have thousands of different shirts. 

If Amanda only cared about a size that fits her, and there are four different sizes, she could buy one right after trying four shirts.

But if Amanda also cared about the color, and there are ten different colors, Amanda would have to try `4 x 10 = 40` combinations to find the perfect shirt.

What would happen if she also wanted to take the material into account? Assuming three different types, Amanda could only find the perfect shirt after trying `4 x 10 x 3 = 120` shirts.

All of a sudden, Amanda is overwhelmed.

**Which of the following ideas explains what's happening to Amanda?**


### **Choices** :

- Occam's Razor
- No Free Lunch Theorem
- Curse of Dimensionality
- Universal Approximation Theorem


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Occam's Razor is the idea that, given two solutions with similar characteristics, the simplest and most direct one is the correct answer. This idea is unrelated to Amanda's problem, so it's not the right choice.

The No Free Lunch Theorem implies that no single algorithm is universally the best-performing algorithm for all problems in machine learning. This idea is also unrelated to what's happening here.

The Universal Approximation Theorem states that a feed-forward network with a single hidden layer containing a finite number of neurons can approximate any continuous function. Not a correct choice either.

Finally, the Curse of Dimensionality refers to various phenomena when working with data in high-dimensional spaces. It states that, as the dimensionality of the data increases, the amount of data needed to train a learning algorithm grows exponentially.

That's what's happening to Amanda: as she wants to consider more shirt attributes, it becomes more problematic to pick the perfect shirt.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check out ["Curse of Dimensionality"](https://en.wikipedia.org/wiki/Curse_of_dimensionality) in Wikipedia.
* For a deeper dive, check ["What is the Curse of Dimensionality?"](https://deepai.org/machine-learning-glossary-and-terms/curse-of-dimensionality).</p></details>

-----------------------

## Date - 2022-07-01


## Title - No high-bias models


### **Question** :

Lyla's project wasn't a walk in the park. She had a large dataset and had to deal with more than 20 relevant features.

A fundamental topic in machine learning is bias, variance, and their relationship with learning algorithms. 

High bias models typically include more assumptions about the target function, while low bias models incorporate fewer assumptions about the target function. 

Lyla knows she needs to stay away from high-bias models. 

**Which of the following algorithms should Lyla avoid?**


### **Choices** :

- Linear Regression
- Logistic Regression
- Decision Trees
- k-Nearest Neighbors


### **Answer** :

<details><summary>CLICK ME</summary><p>1100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Every machine learning algorithm deals with three types of errors: bias, variance, and irreducible error. We need to focus specifically on the bias error to answer this question.

Here is what [Jason Brownlee](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) has to say about bias: "Bias are the simplifying assumptions made by a model to make the target function easier to learn."

In other words, bias refers to the assumptions the model makes to simplify the process of finding answers. The more assumptions it makes, the more biased the model is.

Often, linear models are high-bias. They are easier to understand but make too many assumptions about the target function, preventing them from performing well on complex problems. Linear and logistic regression are two examples of high-bias models.

Nonlinear models are usually low-bias. Decision Trees and k-Nearest Neighbors are two examples.

Therefore, the first and second choices answer this question correctly.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Here is Jason Brownlee's article I mentioned before: ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/).
* The Wikipedia page on bias and variance is also a good resource: ["Bias???variance tradeoff"](https://en.wikipedia.org/wiki/Bias???variance_tradeoff).</p></details>

-----------------------

## Date - 2022-07-02


## Title - Binary cross-entropy for the first time


### **Question** :

Yasmin heard about binary cross-entropy for the first time at work.

Despite being used to working with different machine learning models, it didn't take her long to understand how this loss function works.

After reading the math behind the scenes, there was only one question left for Yasmin to answer.

**Which neural network problems should use binary cross-entropy as their loss function?**


### **Choices** :

- Binary cross-entropy is the loss function used for multi-label classification problems.
- Binary cross-entropy is the loss function used for multi-class classification problems.
- Binary cross-entropy is the loss function used for binary classification problems.
- Binary cross-entropy is the loss function used for regression problems.


### **Answer** :

<details><summary>CLICK ME</summary><p>1010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Binary cross-entropy is the loss function we use when training binary classifiers. When working on a binary classification task, we categorize every sample into two classes. For example, given images of dogs or cats, a binary classifier will decide whether a picture shows a dog or a cat.

But binary classifiers aren't the only time we use binary cross-entropy.

Binary cross-entropy is also the loss function we use in multi-label classification problems. These are problems where we categorize every sample into one or more classes. For example, organizing movies based on the type of content they show: violence, adult language, smoking, or sex, where each film could belong to one or more categories.

In multi-label classification models, the output layer returns values independent from each other. It's helpful to think of a model that outputs ten possible classes as a combination of ten different binary classifiers, and thus binary cross-entropy helps.

Neither multi-class classification nor regression problems use binary-cross entropy.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- ["Understanding binary cross-entropy / log loss: A visual explanation"](https://towardsdatascience.com/understanding-binary-cross-entropy-log-loss-a-visual-explanation-a3ac6025181a) is an excellent introduction to binary cross-entropy.
- Another article that helps understand binary cross-entropy is ["Binary Cross Entropy/Log Loss for Binary Classification"](https://www.analyticsvidhya.com/blog/2021/03/binary-cross-entropy-log-loss-for-binary-classification/).</p></details>

-----------------------

## Date - 2022-07-03


## Title - Happy kitties


### **Question** :

Understanding how deep neural networks work is essential for anyone trying to become proficient at using them.

We don't know precisely how deep neural networks break down an image and distribute different patterns across the layers, but we have some general ideas.

**Imagine that we are working with pictures of happy kitties. Which of the following statements reasonably simplifies how the network works?**


### **Choices** :

- The deeper layers of a neural network compute more complex features than earlier layers.
- The earlier layers of a neural network compute more complex features than deeper layers.
- The complexity of the features computed by the neural network layers is proportionally distributed among all layers.
- The complexity of the features computed by the neural network layers has no relationship with the layer's position.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Focus on a picture of a kitty. You'll see the eyes, nose, mouth, ears, fur, and other characteristics. Notice how groups of pixels form edges, shapes, and the rest of the cat's features. 

A reasonable explanation for how a neural network works is to assume that earlier layers focus on detecting more basic features, like edges and shapes of the image. Later layers could use these earlier pieces to form more recognizable shapes like the eyes and nose of the cat.

While the network deals with pixels early on, the deeper we go into it, the more it will work with complete patterns until it reaches the output layer.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["But what is a neural network?"](https://www.youtube.com/watch?v=aircAruvnKk) is Grant Sanderson's introduction to neural networks on YouTube. Highly recommended!
* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html) is a free online book written by [Michael Nielsen](https://twitter.com/michael_nielsen).</p></details>

-----------------------

## Date - 2022-07-04


## Title - Euclidean distance


### **Question** :

Many machine learning algorithms need a way to measure the similarity between observations.

For example, when using an algorithm like [K-Means](https://en.wikipedia.org/wiki/K-means_clustering), we need a way to determine how close different samples are in our dataset before deciding whether those samples belong in the same cluster.

There are different metrics to compute the distance between observations, and one of the most popular ones is the Euclidean distance.

**From the following list, select every correct statement about the Euclidean distance.**


### **Choices** :

- The Euclidean distance is a way to compute the distance between two points in two-dimensional spaces. The Euclidean distance doesn't work in multidimensional spaces.
- The Euclidean distance between two points does not depend on which of the two points is the start and which is the destination. In other words, the distance between _p_ and _q_ is the same as between _q_ and _p_.
- The Euclidean distance between two distinct points is always positive.
- Traveling from a point _p_ to a point _q_ via a point _r_ cannot be any shorter than traveling directly from _p_ to _q_.


### **Answer** :

<details><summary>CLICK ME</summary><p>0111</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>We can use the [Euclidean distance](https://en.wikipedia.org/wiki/Euclidean_distance) in one or more dimensions. For example, in a line, the distance between two points is the numerical difference between their coordinates. In a plane, the distance is the [Pythagorean distance](https://en.wikipedia.org/wiki/Pythagorean_theorem). 

But can we use it in multidimensional spaces?

The answer is yes; the Euclidean distance works in [multidimensional spaces](https://hlab.stanford.edu/brian/euclidean_distance_in.html). Intuitively, this should make sense because we can use it as the metric to compute the distance between multi-feature observations in our dataset. Therefore, the first choice is incorrect.

The distance from a point _p_ to another point _q_ is the same regardless of whether we start from _p_ or _q_. This distance is always a positive value as long as _p_ and _q_ are different points. If _p_ and _q_ are the same point, the distance is 0.

In the [Euclidean plane](https://en.wikipedia.org/wiki/Euclidean_space), the distance between any two distant points is the length of the line segment joining them. So this segment joining points _p_ and _q_ can't be any shorter, regardless of whether we get from _p_ to _q_ via a third point _r_.

In summary, the last three choices are correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Euclidean Distance In 'n'-Dimensional Space"](https://hlab.stanford.edu/brian/euclidean_distance_in.html) for a summary and visualization of how the Euclidean distance works in multi-dimensional spaces.
* ["Euclidean distance"](https://en.wikipedia.org/wiki/Euclidean_distance) and ["Euclidean space"](https://en.wikipedia.org/wiki/Euclidean_space) are Wikipedia articles that will help with this topic.</p></details>

-----------------------

## Date - 2022-07-05


## Title - A classifier nobody saw coming


### **Question** :

After several experiments, it was clear that something was happening: the model wasn't returning good predictions on the test data.

The team was tired and ready to get back to the drawing board to try and find a different approach to solve the problem, but Raelynn had an idea.

She took the training dataset, removed the target variable, and mixed it with all their available test data. She then created a new binary target and set it to `1` for every test sample and `0` for every training sample.

"Run a classifier on this dataset, and let me know how good the predictions are," she asked.

**Her team seemed confused. What is Raelynn trying to do?**


### **Choices** :

- This classifier will estimate the performance of the team's model on unseen test data. It will help the team understand whether they are overfitting or underfitting the training data.
- This classifier will turn the initial problem into a more straightforward approach that will serve as a baseline for the team to continue their work and find a better solution.
- This classifier will estimate how different the training data is from the test data, potentially explaining why the team is struggling.
- Combining the training and test data is never a good idea, so this classifier's results will not be valid.


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Raelynn's approach should be familiar if you have experience participating in Kaggle competitions. 

Popular validation techniques, like cross-validation, allow you to test your models on unseen data, as long as that data comes from the same distribution as your training dataset. Unfortunately, that's not always the case, and even slight differences between the training and test data will considerably affect the result of your model.

[Adversarial validation](https://www.kaggle.com/code/carlmcbrideellis/what-is-adversarial-validation/notebook) is a technique to estimate the degree of difference between your training and test data. [The Kaggle Book](https://amzn.to/3kbanRb) introduces it as follows:

> [adversarial validation] was long rumored among Kaggle participants and transmitted from team to team until it emerged publicly thanks to a post by Zygmunt Zaj??c on his FastML blog.

Let's think about what Raelynn did. She created a new dataset by joining the training and test data. The target of that new dataset is a binary variable differentiating the training and test samples. She can determine how easy it's to separate both datasets by running a classifier on that new data.

Adversarial validation relies on computing the [ROC-AUC](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc), a graph showing the True Positive Rate and the False Positive Rate at different classification thresholds. The area under this curve (AUC) measures the model's performance. A perfect model will have an area of `1.0`, while a model that only makes mistakes will have an area of `0.0`.

If they run the classifier and the ROC-AUC is around `0.5`, Raelynn will know that the training and test data are not easily distinguishable, which is good because it means the data comes from the same distribution. If the ROC-AUC is too high???closer to `1.0`???the classifier can tell training and test data apart, which means they come from a different distribution.

Adversarial validation is a very clever technique. The result could help explain why the team is struggling and guide it on how to continue.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Adversarial validation"](https://blog.zakjost.com/post/adversarial_validation/) is a great introduction to adversarial validation.
* Check ["What is Adversarial Validation?"](https://www.kaggle.com/code/carlmcbrideellis/what-is-adversarial-validation/notebook) for a discussion about this technique in Kaggle.
* [The Kaggle Book](https://amzn.to/3kbanRb) is an amazing reference for those looking to participate in Kaggle.</p></details>

-----------------------

## Date - 2022-07-06


## Title - Tensors and trolls


### **Question** :

Yesterday was Samantha's first day, and she started learning how to use a deep learning library.

Unsurprisingly, "Tensors" was the first concept she needed to understand. Samantha read everything she could about them and is now ready to write a short article with everything she learned.

But she knows that making a mistake online will bring people out of the woodwork to troll her forever.

**Samantha has to get this right. Which of the following are accurate descriptions of tensors of different ranks?**


### **Choices** :

- A vector that contains only one number is called a "scalar" or a rank-0 tensor. An example of a scalar is any numeric value like a person's age or today's temperature.
- An array of numbers is called a "vector" or a rank-1 tensor. An example of a vector is an array containing the age of every person represented in a dataset.
- An array with two dimensions is called a matrix or a rank-2 tensor. An example is an array containing the age and the sex of every person represented in a dataset.
- An array with three dimensions is a rank-3 tensor. An example is a 3D array containing the information of an image: its width, height, and the number of channels.


### **Answer** :

<details><summary>CLICK ME</summary><p>1111</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Let's get something out of the way: This question is about tensors as we use them in deep learning, not the mathematical definition of a tensor.

The rank of a tensor refers to its number of axes???or dimensions. For example:

* The rank of a scalar is 0.
* The rank of a vector is 1.
* The rank of a matrix is 2.
* The rank of a 3D tensor is 3.

A scalar, or 0D tensor, has a rank of 0 and contains a single number. These are also called "0-dimensional tensors." Therefore, the first choice is correct.

A vector, or 1D tensor, has a rank of 1 and represents an array of numbers. Therefore, the second choice is also correct.

A matrix, or 2D tensor, has a rank of 2 and represents an array of vectors. We refer to the two axes of a matrix as "rows" and "columns." Therefore, the third choice is also correct.

You can obtain higher-dimensional tensors (3D, 4D, etc.) by packing lower-dimensional tensors in an array. For example, packing a 2D tensor in an array gives you a 3D tensor. 

For example, to store a color image, we need three dimensions: one representing the image's width, another representing the height, and a final dimension for the color channels. Assuming we have three channels (red, blue, and green), you can think of having three different matrices, each containing the pixels for each one of the channels. Therefore, the fourth choice is also correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Deep Learning with Python, Second Edition](https://amzn.to/3K3VZoy) covers the topic of tensors really well.
* Check ["A Gentle Introduction to Tensors for Machine Learning with NumPy"](https://machinelearningmastery.com/introduction-to-tensors-for-machine-learning/) for a quick introduction to tensors and practical code.</p></details>

-----------------------

## Date - 2022-07-07


## Title - Start with Decision Trees


### **Question** :

When I started with machine learning, the first model I built was a Decision Tree.

As a long-time software developer, Decision Trees made perfect sense. It took me little time to understand the basics and build something useful to solve an example problem.

Since then, I always recommend newcomers start with Decision Trees. There are simpler models, but I think they strike a perfect balance between power and complexity.

**Which of the following would you categorize as an advantage of using a single Decision Tree?**


### **Choices** :

- The predictions generated by a Decision Tree are easy to interpret and explain.
- A Decision Tree is very resistant to overfitting.
- You can use a Decision Tree to solve regression and classification tasks.
- A Decision Tree doesn't require tuning to get good predictions.


### **Answer** :

<details><summary>CLICK ME</summary><p>1010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>As a developer, [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree_learning) have always made sense. 

I'm not talking about the process of building a good Decision Tree but about how they work to find predictions. In a short sentence, a Decision Tree is just a bunch of nested conditions that get us to the final solution.

And this property is precisely what makes them very popular: we can look at a prediction and fully understand why the model arrived at that conclusion. In other words, the predictions generated by Decision Trees are easy to interpret, an essential advantage of using Decision Trees over more obscure techniques, like neural networks or Support Vector Machines.

Decision Trees, unfortunately, are prone to overfitting if we don't take careful care of their depth. In other words, unless we ensure our tree doesn't go too deep, it will tend to fit noisy samples and output the wrong prediction. We can control overfitting in a Decision Tree by a process called "pruning."

Remember that while a single Decision Tree is prone to overfitting, using an ensemble of trees is more resistant. Here is a quote from "[To Boost or not to Boost: On the Limits of Boosted Neural Networks](https://arxiv.org/pdf/2107.13600.pdf)":

> [these experiments] confirm that training single large decision trees is prone to overfitting while boosted ensembles of decision trees are resistant to overfitting.

Many people relate Decision Trees with classification tasks, but they are also valuable for solving regression tasks. A classification task is when the predicted outcome is a discrete class, while the result of a regression task is a Real number. This flexibility makes Decision Trees very useful.

Finally, we discussed above how Decision Trees are prone to overfit if we aren't careful with their depth. This is just one of the hyperparameters that we can tune. Like with most techniques, Decision Trees require experimentation and tuning to improve the quality of their results.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["To Boost or not to Boost: On the Limits of Boosted Neural Networks"](https://arxiv.org/pdf/2107.13600.pdf), the paper cited above comparing the overfitting tendency of a single Decision Tree versus an ensemble of trees.
* ["Decision tree pruning"](https://en.wikipedia.org/wiki/Decision_tree_pruning) covers the process of pruning a tree to reduce overfitting.
* Check ["Random Forest"](https://en.wikipedia.org/wiki/Random_forest) for more information about a widely used class of Decision Tree ensembles.</p></details>

-----------------------

## Date - 2022-07-08


## Title - What model is she using?


### **Question** :

Alicia's team was having a hard time with their model.

Everything was going according to plan until the customer showed up with more data. 

The team decided to retrain the model with the new data, and to their surprise, they discovered that the test error increased significantly during evaluation.

They kept training the model with different portions of the data and testing it with their test dataset. Still, none of the models was good enough: the model was learning something different depending on the portion of the data that Alicia's team used.

**If you were to guess the model that Alicia's team is building, which of the following would be your picks?**


### **Choices** :

- Alicia is probably using a Linear Regression model.
- Alicia is probably using a Logistic Regression model.
- Alicia is probably using a k-Nearest Neighbors model.
- Alicia is probably using a Decision Tree model.


### **Answer** :

<details><summary>CLICK ME</summary><p>0011</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The problem description has an essential clue: The testing error is high as we use different data portions to train the model. The various models can't generalize.

High-variance models usually suffer from this problem.

Here is what [Jason Brownlee](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) has to say about variance: "Variance is the amount that the estimate of the target function will change if different training data was used."

As we change the training data, a low-variance model should still return good predictions on the test data, but Alice's model doesn't. 

Often, linear models are low-variance, and nonlinear models are high-variance. This means that Alicia is probably using a k-Nearest Neighbors or a Decision Tree model since they are high-variance models.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Here is Jason Brownlee's article I mentioned before: ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/).
* The Wikipedia page on bias and variance is also a good resource: ["Bias???variance tradeoff"](https://en.wikipedia.org/wiki/Bias???variance_tradeoff).</p></details>

-----------------------

## Date - 2022-07-09


## Title - Hot equipment


### **Question** :

Sarah is building a model to recognize pieces of equipment running too hot in a warehouse. She has a large enough dataset of thermal images, and she is using a deep learning model to build a classifier.

The problem is that the dataset is severely imbalanced, with most images showing normal temperatures. Sarah's model results aren't good enough.

**Which of the following are helpful strategies to help Sarah deal with imbalanced datasets?**


### **Choices** :

- Augment the minority class???images showing hot equipment???with synthetically-generated data.
- Reduce the training time to prevent the learning algorithm from overfitting.
- Resample the dataset by either oversampling the minority class or undersampling images showing normal temperatures.
- A deep learning model is not a good solution to solve this problem.


### **Answer** :

<details><summary>CLICK ME</summary><p>1010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>From the list of choices, two strategies could help Sarah overcome the problem: augmentation and resampling.

Sarah's model is struggling because the dataset is severely imbalanced: it doesn't have too many pictures showing equipment running hot. We could alleviate this problem by adding more photos of this minority class. The first choice proposes adding synthetically-generated images, which is usually a cheaper option to generate a lot of valid data. Augmenting the dataset will allow Sarah to balance both classes, which will help her classifier.

The second strategy that could also help is resampling the dataset. Instead of training with the data as-is, Sarah could oversample the photos showing equipment running hot. For example, she could duplicate every hot image. Sarah could also undersample the normal images; for instance, she could only take every other picture.

Reducing the training time is not a helpful strategy for this problem. Also, nothing on the problem statement would suggest that deep learning is not a good approach.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Random Oversampling and Undersampling for Imbalanced Classification"](https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/) for an introduction to oversampling and undersampling.
* ["Failure of Classification Accuracy for Imbalanced Class Distributions"](https://machinelearningmastery.com/failure-of-accuracy-for-imbalanced-class-distributions/) covers the problem of using accuracy as the metric in imbalanced classification problems.
* ["Learning from imbalanced data"](https://www.jeremyjordan.me/imbalanced-data/) discusses a number of considerations and techniques for dealing with imbalanced data.</p></details>

-----------------------

## Date - 2022-07-10


## Title - Self-supervised learning


### **Question** :

Julia regularly works with supervised and unsupervised learning methods.

However, she keeps seeing new methods that use self-supervised learning techniques. Julia doesn't understand how these methods compare to supervise and unsupervised learning, so she is here to ask for your help.

**Which of the statements on self-supervised learning are true?**


### **Choices** :

- Self-supervised learning is just a fancy name for unsupervised learning.
- Similar to supervised learning, self-supervised methods can judge if their prediction is correct or not during training.
- Like unsupervised learning, self-supervised methods don't require labeled training data.
- Self-supervised methods require only a small number of labeled samples.


### **Answer** :

<details><summary>CLICK ME</summary><p>0110</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Self-supervised methods are considered a form of unsupervised learning. However, not all unsupervised methods are self-supervised. This reasoning allows us to exclude the first choice.

Self-supervised methods have similarities to both supervised and unsupervised learning. They don't require labeled data, which makes them similar to unsupervised learning. On the other hand, in self-supervised methods, "supervision" can be derived directly from the data. Therefore, like supervised learning, we can judge whether a prediction is true or false.

An example would be a neural network that predicts the next word given a part of a sentence. We can take the text of a book and create random samples by picking parts of sentences. We don't need any labels, but for every instance, we still know what the correct answer is. Therefore, the second and the third choice are correct.

The last choice is the definition of semi-supervised learning, which is different than self-supervised learning and is therefore incorrect.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Self-supervised learning"](https://project.inria.fr/paiss/files/2018/07/zisserman-self-supervised.pdf) is a presentation by Andrew Zisserman covering self-supervised learning for images.
* ["Self-supervised learning: The dark matter of intelligence"](https://ai.facebook.com/blog/self-supervised-learning-the-dark-matter-of-intelligence/) is an excellent post from Meta's AI Research team.</p></details>

-----------------------

## Date - 2022-07-11


## Title - Pictures and tensors


### **Question** :

I've been teaching a friend a little bit of computer vision.

Well, I'll be honest, I'm focusing directly on deep learning and how to use pre-trained models to tell cat pictures apart from dog pictures.

We have a dataset of 1,000 color pictures of size 512 x 512. Five hundred of those are images of cats, and the other half are images of dogs.

Soon after we started looking into the problem, he asked a question that I hadn't thought about in a long time.

**What's the correct shape of a tensor capable of storing all of this data at once?**


### **Choices** :

- We can store it in a tensor of shape `(1000, 512, 512)`
- We can store it in a tensor of shape `(512, 512, 3)`
- We can store it in a tensor of shape `(1000, 512, 512, 3)`
- We can store it in a tensor of shape `(500, 512, 512, 1)`


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>When working with images, we need to store three components: the height, the width, and the color depth. Color images have three color channels (one for red, one for green, and one for blue), and grayscale images have a single color channel.

In other words, assuming our pictures are of size 512 x 512, we need to store the 3 RGB values for each pixel in the image, so we need a tensor of shape `(512, 512, 3)`. If we don't care about colors, we could keep every pixel of a single image in a tensor of shape `(512, 512)`. 

But even when working with grayscale images, we always add a dimension to store the color depth by convention. That's nice because we can use the same structure for grayscale and color images. If we don't care about color, we could store one picture in a `(512, 512, 1)` tensor. Since we are working with color pictures, our tensor will be `(512, 512, 3)` to accommodate the three channels.

Great! So far, we know how to store a single color picture of size 512 x 512. How about keeping 1,000 of them? We need another dimension: `(1000, 512, 512, 3)`. 

The order I chose for each dimension is intentional. By convention, we structure tensors that hold images the following way: (samples, height, width, channels). There's a different convention where channels go in front of the dimensions of the images, but most people use them at the end.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Deep Learning with Python, Second Edition](https://amzn.to/3K3VZoy) covers the topic of tensors really well.
* Check ["A Gentle Introduction to Tensors for Machine Learning with NumPy"](https://machinelearningmastery.com/introduction-to-tensors-for-machine-learning/) for a quick introduction to tensors and practical code.</p></details>

-----------------------

## Date - 2022-07-12


## Title - Betty's surprise


### **Question** :

Discovering that Gradient Descent has different names based on how many samples it uses to calculate the error was something Betty wasn't expecting.

There are three popular variations of the algorithm: Mini-Batch Gradient Descent, Stochastic Gradient Descent, and Batch Gradient Descent.

Betty found this fascinating, and although it made sense, she always found that Stochastic Gradient Descent was the hardest for her to define.

**Which of the following statements is true about this version of the algorithm?**


### **Choices** :

- Stochastic Gradient Descent determines the optimal amount of data required to compute the gradient of the cost function.
- Stochastic Gradient Descent uses a single sample of data during every iteration.
- Stochastic Gradient Descent uses all available data once during every iteration.
- Stochastic Gradient Descent uses a batch of data (more than one sample but fewer than the entire dataset) during every iteration.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Here is a simplified explanation of how Gradient Descent works: We take samples from the training dataset, run them through the model, and determine how far our results are from what we expect. We then use this "error" to compute how much we need to update the model weights to improve the results.

A critical decision we need to make is how many samples we use on every iteration to run through the model. We have three choices: 
* Use a single sample of data.
* Use all of the data at once.
* Use some of the data.

Using a single sample of data on every iteration is called "Stochastic Gradient Descent" or SGD. In other words, the algorithm uses one sample to compute the updates. 

Using all the data at once is called "Batch Gradient Descent." After processing every sample, the algorithm takes the entire dataset and computes the updates. 

Finally, using some of the data???more than one sample but fewer than the entire dataset???is called "Mini-Batch Gradient Descent." The algorithm works like Batch Gradient Descent, with the only difference that we use fewer samples.

Therefore, the second choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["An overview of gradient descent optimization algorithms"](https://ruder.io/optimizing-gradient-descent/index.html#gradientdescentvariants) for a deep dive into gradient descent and every one of its variants.
* ["Gradient Descent For Machine Learning"](https://machinelearningmastery.com/gradient-descent-for-machine-learning/) is another great introduction to gradient descent.
* ["A Gentle Introduction to Mini-Batch Gradient Descent and How to Configure Batch Size"](https://machinelearningmastery.com/gentle-introduction-mini-batch-gradient-descent-configure-batch-size/) covers Batch and Mini-Batch Gradient Descent.</p></details>

-----------------------

## Date - 2022-07-13


## Title - Arya's confusion


### **Question** :

Arya is always confused about this.

We have multi-class classification problems when every sample in the dataset belongs to one class. We have multi-label classification problems when every instance belongs to one or more categories.

These types of problems look similar, but they are very different.

Arya never remembers the correct loss function to train a neural network to solve these problems.

**Which two of the following statements are correct?**


### **Choices** :

- Binary cross-entropy is the loss function used for multi-label classification problems.
- Binary cross-entropy is the loss function used for multi-class classification problems.
- Categorical cross-entropy is the loss function used for multi-label classification problems.
- Categorical cross-entropy is the loss function used for multi-class classification problems.


### **Answer** :

<details><summary>CLICK ME</summary><p>1001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The goal of the output layer of a [multi-class classification](https://en.wikipedia.org/wiki/Multiclass_classification) model is to return the class that better represents the network's input. Softmax is ideal because it uses the output score to produce a probability for each category. 

The categorical cross-entropy loss function quantifies the difference between two probability distributions. When working on multi-class classification tasks, the categorical cross-entropy is the perfect loss function to pair with a softmax output layer.

In the case of [multi-label classification](https://en.wikipedia.org/wiki/Multi-label_classification) models, our output layer should return values independent from each other. Sigmoid is perfect because it converts the output scores to a value between 0 and 1.

Multi-label classification problems borrow the same principles from binary classification problems. The difference is that we end up with multiple sigmoid outputs instead of one. It's helpful to think of a model that outputs ten possible classes as a combination of ten different binary classifiers. Remember the loss function we use to train binary classification models? Binary cross-entropy. 

In summary, multi-class classification models should use a softmax output with the categorical cross-entropy loss function. Multi-label classification models should use a sigmoid output and the binary cross-entropy loss function.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Binary crossentropy"](https://peltarion.com/knowledge-center/documentation/modeling-view/build-an-ai-model/loss-functions/binary-crossentropy) for an explanation of how Binary Cross-Entropy works.
* Check ["Categorical crossentropy"](https://peltarion.com/knowledge-center/documentation/modeling-view/build-an-ai-model/loss-functions/categorical-crossentropy) for an explanation of how Categorical Cross-Entropy works.</p></details>

-----------------------

## Date - 2022-07-14


## Title - Only one hidden layer


### **Question** :

Sarah wants to add a few slides about neural networks as part of a new course she's been working on for the past month.

Most of her students don't have a machine learning background, so Sarah wants to ensure she uses accurate and simple language during her presentation to avoid confusing them.

She plans to show an example of how a neural network with a single hidden layer works, but she is having difficulty choosing the right way to refer to this model.

**Which of the following is the correct way to talk about a neural network with a single hidden layer?**


### **Choices** :

- A deep neural network
- A recurrent neural network
- A hidden neural network
- A shallow neural network


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>We refer to neural networks that use a few hidden layers between the input and output as "shallow neural networks." There's no specific number for how many hidden layers is too many, but one single layer makes Sarah's model a shallow network.

A deep neural network consists of multiple layers between the input and output layers. The more layers we add, the "deeper" the network becomes.

The term "hidden neural network" doesn't exist, and while recurrent neural networks exist, Sarah's network is not one of them.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["But what is a neural network?"](https://www.youtube.com/watch?v=aircAruvnKk) is Grant Sanderson's introduction to neural networks on YouTube. Highly recommended!
* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html) is a free online book written by [Michael Nielsen](https://twitter.com/michael_nielsen).</p></details>

-----------------------

## Date - 2022-07-15


## Title - Eden's schedule


### **Question** :

Eden is building a deep learning model, but she is not having a lot of success getting it to converge.

One idea she wants to explore is to use a learning rate scheduler. Several of her colleagues recommended it, but she still isn't sure how this could help.

Eden decided that the first step for her is to understand how learning rate schedulers work.

**Which of the following is a correct definition of what a learning rate scheduler does?**


### **Choices** :

- The learning rate scheduler will help the optimization algorithm get past a flat region by continuing its previous movement.
- The learning rate scheduler will help the optimization algorithm accelerate in one direction based on past updates.
- The learning rate scheduler will save a copy of the network weights according to the value of the learning rate.
- The learning rate scheduler will adjust the learning rate during training according to a pre-defined schedule.


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>When training a neural network, setting the hyperparameters of the optimizer is essential for getting good results. One of the most critical parameters is the [learning rate](https://en.wikipedia.org/wiki/Learning_rate). Setting the learning rate too high or too low will cause problems during training.

A simple way to think about the learning rate is as follows: if we set it too low, the training process will be slow; it will take a long time for the network to converge. Conversely, if we use a learning rate that's too high, the process will oscillate around the minimum without converging. 

A popular technique to find a good balance is to use a learning rate scheduler. This predefined schedule adjusts the learning rate between epochs or iterations as the training progresses.

The most common scenario is to start with a high learning rate and decrease it over time. In the beginning, we take significant steps towards the minimum but move more carefully as we hone in on it. 

The first two choices of this question refer to [momentum](https://en.wikipedia.org/wiki/Stochastic_gradient_descent#Momentum). A learning rate scheduler's goal is neither rolling by flat regions nor accelerating in one direction based on previous updates. The third choice is also incorrect since a learning rate scheduler has nothing to do with saving the learning rate.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- ["Learning Rate Scheduling"](https://d2l.ai/chapter_optimization/lr-scheduler.html) is a great introduction to learning rate schedulers.
- ["How to Choose a Learning Rate Scheduler for Neural Networks"](https://neptune.ai/blog/how-to-choose-a-learning-rate-scheduler) is an article from [Neptune AI](https://neptune.ai/), focusing on some practical ideas on how to use schedulers.</p></details>

-----------------------

## Date - 2022-07-16


## Title - Evaluating object detection


### **Question** :

Rose started a new job, and her first task was to develop an object detection model that detects cars in drone footage.

Rose wanted to build a generic model that she could use for different applications. 

It would help if she had some solid evaluation of the model's performance to compare different versions and choose the best one.

**Which evaluation metrics should Rouse use to evaluate her model?**


### **Choices** :

- Recall
- ROC Curve
- Precision-Recall Curve
- F1 score


### **Answer** :

<details><summary>CLICK ME</summary><p>0011</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>The recall is a helpful metric for object detection, but it won't tell Rose the whole picture without looking at the precision. Rose could build a useless model with high recall but abysmal precision. Therefore, she can't use recall as the definitive metric.

There's a problem with [ROC Curves](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc) for object detection problems: there's no concept of True Negatives, and the ROC curve needs it to display the False Positive Rate on one of the axes. On object detection, the number of bounding boxes that won't contain a relevant object is too large, and that's why we avoid any metrics that depend on True Negatives.

Instead, Rose can compute a [Precision-Recall Curve](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_recall_curve.html). This curve is similar to the ROC curve, but instead of using the False Positive Rate, it uses the model's precision that doesn't depend on the True Negatives. 

Finally, computing the [F1-score](https://en.wikipedia.org/wiki/F-score) is also an option because it considers both the precision and recall of the model.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Classification: ROC Curve and AUC"](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc) for an explanation of how to create and interpret a ROC curve.
* For more information about Precision-Recall curves, check [Scikit-Learn's documentation](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_recall_curve.html).</p></details>

-----------------------

## Date - 2022-07-17


## Title - Illegitimate traffic


### **Question** :

Rachel's team built a decision tree model to determine illegitimate requests to their application. 

While working on a prototype with fake data, everything worked as expected. But as soon as they tried to use real traffic, it was clear that the problem was more complex than expected: most requests were legitimate, and the decision tree had difficulty finding the problematic ones.

Rachel still thought a decision tree was the right approach, so she decided to find a solution.

**What's the appropriate next step to solving this problem?**


### **Choices** :

- Rachel should balance the dataset before training the decision tree. After doing this, she can fit the model again.
- Rachel should fit the decision tree and then scale the model's results appropriately, following the weight of each class.
- Rachel should fit the decision tree on each class separately???illegitimate and legitimate requests. Then, she should combine the results proportionally to the weight of each class.
- Rachel cannot make a decision tree work with an imbalanced dataset. She should pick a different model.


### **Answer** :

<details><summary>CLICK ME</summary><p>1000</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Let's imagine there's no problem with 99% of the traffic. If Rachel's model classifies every request as legitimate, it will have 99% accuracy. Unfortunately, this is useless, so Rachel needs to find a different solution.

If Rachel balances the dataset before fitting the decision tree, she will have a better chance. There are many different strategies to balance a dataset, and they all aim to amplify the impact of the minority class so the model can better predict it.

The second choice is not a solution. It doesn't make sense to scale the model results following the weight of the classes. Something similar happens with the third choice: fitting the decision tree on each separate class doesn't make sense either.

Finally, the fourth choice argues that decision trees don't work with imbalanced datasets, which is not true. Besides balancing the dataset, Rachel could use each class' weight to penalize the model more harshly when it misses illegitimate requests.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["Random Oversampling and Undersampling for Imbalanced Classification"](https://machinelearningmastery.com/random-oversampling-and-undersampling-for-imbalanced-classification/) for an introduction to oversampling and undersampling.
* ["Failure of Classification Accuracy for Imbalanced Class Distributions"](https://machinelearningmastery.com/failure-of-accuracy-for-imbalanced-class-distributions/) covers the problem of using accuracy as the metric in imbalanced classification problems.
* ["Learning from imbalanced data"](https://www.jeremyjordan.me/imbalanced-data/) discusses a number of considerations and techniques for dealing with imbalanced data.</p></details>

-----------------------

## Date - 2022-07-18


## Title - Increasing dropout


### **Question** :

Quinn's approach to learning something new is to run as many experiments as she needs to grasp how things work.

Today, it was the turn of Dropout. 

Quinn wants to know how it works, and one of her experiments is to increasingly modify the Dropout rate in a neural network and see how it affects the model's accuracy on the test data.

**Which of the following do you think is the result that Quinn will observe after running this experiment?**


### **Choices** :

- As the Dropout rate increases, the accuracy will go down until it hits a low value.
- As the Dropout rate increases, the accuracy will go down, and at some point, it will begin to increase.
- As the Dropout rate increases, the accuracy will go up until it hits its maximum potential.
- As the Dropout rate increases, the accuracy will go up, and at some point, it will begin to decrease.


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Dropout is a regularization method that works well and is vital for reducing overfitting.

Sometimes, the nodes in a neural network create strong dependencies on other nodes, which may lead to overfitting. An example is when a few nodes on a layer do most of the work, and the network ignores all the other nodes. Despite having many nodes on the layer, you only have a small percentage of those nodes contributing to predictions. We call this phenomenon "[co-adaptation](https://machinelearning.wtf/terms/co-adaptation/)," and we can tackle it using Dropout.

During training, Dropout randomly removes a percentage of the nodes, forcing the network to learn in a balanced way. Now every node is on its own and can't rely on other nodes to do their work. They have to work harder by themselves. 

As Quinn increases the Dropout rate, she will reduce overfitting and see the model's accuracy improve. At some point, however, the rate will be so high that the model will start underfitting, and the accuracy will come down. This drop happens because removing too many of the neurons during training will effectively reduce the model's capacity too much. In other words, while some regularization is good, too much of it will prevent the model from learning.

Therefore, the fourth choice is the correct answer to this question.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* For more information about co-adaptation and how to use Dropout, check ["Improving neural networks by preventing
co-adaptation of feature detectors"](https://arxiv.org/pdf/1207.0580.pdf).
* ["A Gentle Introduction to Dropout for Regularizing Deep Neural Networks"](https://machinelearningmastery.com/dropout-for-regularizing-deep-neural-networks/) is an excellent introduction to Dropout.</p></details>

-----------------------

## Date - 2022-07-19


## Title - Convolutions are better


### **Question** :

When Nora finished the chapter about neural networks, she was ready to step it up with a more complex problem.

The next stop was computer vision using convolutional neural networks (CNN.) These worked differently than fully connected networks and were better suited for processing image data.

Before diving in, Nora wanted to summarize the advantages of using a CNN.

**Which of the following are characteristics of convolutional neural networks?**


### **Choices** :

- Convolutional neural networks are scale invariant.
- Convolutional neural networks are rotation invariant.
- Convolutional neural networks are translation invariant.
- Convolutional neural networks do not need human preprocessing or supervision to detect relevant features in an image.


### **Answer** :

<details><summary>CLICK ME</summary><p>0011</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>To answer this question, we need to consider that Nora is focusing on out-of-the-box [convolutional neural networks](https://en.wikipedia.org/wiki/Convolutional_neural_network) and how they compare to fully-connected networks. [Some implementations](https://arxiv.org/abs/1411.6369) improve the capabilities of CNNs in different ways, but here we are focusing on their fundamental characteristics.

Convolutional neural networks are [neither scale nor rotation invariant](https://pyimagesearch.com/2021/05/14/are-cnns-invariant-to-translation-rotation-and-scaling/); you need to include rotated images at different scales as part of your training dataset to teach the network how to recognize them. They are, however, translation invariant: they can recognize the same patterns independently of where they show in an image. This characteristic differentiates them from fully-connected networks.

Finally, convolutional neural networks can learn relevant features of an image without needing human supervision. Back in the day, when trying to get a neural network to work with image data, we had to preprocess the images and manually curate data points to help the network learn what we considered important. This was time-intensive, didn't scale, and made the training process brittle and slow. Therefore, the fourth choice is also correct.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>- ["Are CNNs invariant to translation, rotation, and scaling?"](https://pyimagesearch.com/2021/05/14/are-cnns-invariant-to-translation-rotation-and-scaling/) goes into more detail about whether convolutional neural networks are translation, rotation, and scale invariant.
- Check ["How Do Convolutional Layers Work in Deep Learning Neural Networks?"](https://machinelearningmastery.com/convolutional-layers-for-deep-learning-neural-networks/) for an introduction to how convolutional layers work.</p></details>

-----------------------

## Date - 2022-07-20


## Title - Crossing the bridge


### **Question** :

To cross the bridge, Rylee had to solve a final puzzle.

She had four pieces in front of her, each representing a layer used in Convolutional Neural Networks (CNN). Rylee had to put them in the correct order, and only then will the doors to the bridge reveal.

There's only one chance and no time to waste.

**Which of the following is the correct order in which these four layers appear in a CNN?**


### **Choices** :

- Input Layer, Pooling Layer, Convolutional Layer, Non-linearity.
- Input Layer, Convolutional Layer, Pooling Layer, Non-linearity.
- Input Layer, Convolutional Layer, Non-linearity, Pooling Layer.
- Input Layer, Pooling Layer, Non-linearity, Convolutional Layer.


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Look at the structure of a CNN, and you'll see a pattern repeated multiple times: Convolution, non-linearity, pooling. ReLU and Max Pooling are popular choices for non-linearity and pooling layers.

Here is an illustration of the [architecture of VGG16](https://medium.com/mlearning-ai/an-overview-of-vgg16-and-nin-models-96e4bf398484). Notice the pattern:

![Architecture of VGG16](https://user-images.githubusercontent.com/1126730/174477391-272e2265-415a-49ef-b3c5-8573e96b153a.png)

The convolutional layer creates feature maps by applying learned filters to the input image. The pooling layer downsamples the feature maps and makes the model robust against location differences of the features detected. They work together, which is why they appear in this order.

Introducing non-linearities is crucial if we want our model to learn complex functions. The non-linearity is applied directly after the convolution layer to produce the final feature map.
 
If Rylee wants to stay alive, she must order the pieces as indicated by the third choice.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Convolutional Neural Networks ??? A Beginner???s Guide"](https://towardsdatascience.com/convolution-neural-networks-a-beginners-guide-implementing-a-mnist-hand-written-digit-8aa60330d022) is a great introduction to Convolutional Neural Networks.
* Check ["A Gentle Introduction to Pooling Layers for Convolutional Neural Networks"](https://machinelearningmastery.com/pooling-layers-for-convolutional-neural-networks/) for more information about how the combination of convolutions and pooling layers work.</p></details>

-----------------------

## Date - 2022-07-21


## Title - Roman numerals


### **Question** :

Tracy is taking part in the [Data-Centric AI Competition](https://https-deeplearning-ai.github.io/data-centric-comp/) by [Andrew Ng](https://twitter.com/andrewyng). The competition's goal is to train a model to classify Roman numerals. However, unlike most other challenges, in this one, the participants are only allowed to change the data and not the model.

Every competitor has access to a balanced dataset with examples of Roman literals, but Tracy decided to use a Generative Adversarial Network (GAN) to generate new samples.

She implemented a GAN and trained it on her dataset. Both loss functions converged nicely, and she started sampling from the model. However, something was off: the GAN only generated images for two of the numerals but never produced any others.

**Why is Tracy's network not producing the expected results?**


### **Choices** :

- The GAN is overfitting. That's why the loss functions converged, but the results in practice are not good.
- The dataset isn't perfectly balanced. The network probably ignored any underrepresented classes.
- Training GANs requires vast amounts of training data. Tracy didn't have a large enough dataset.
- The discriminator network is stuck in a local minimum allowing the generator to cheat.


### **Answer** :

<details><summary>CLICK ME</summary><p>0001</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Tracy's idea is good. We can use [Generative Adversarial Networks](https://en.wikipedia.org/wiki/Generative_adversarial_network) to create new data samples and augment the original dataset. However, a lot of work is involved in training a GAN correctly. 

The first hypothesis is that the GAN is suffering from overfitting. However, the network seems to work well for some numerals but not others. That is an unlikely behavior for a model that's overfitting.

Neither the second nor the third choices are correct either. First, the description of this problem states that Tracy's dataset is well balanced. Even if there are minor differences, it's unlikely for the network to struggle to generate some of the numerals. Second, the amount of samples doesn't seem to be a problem for the classes produced by the network, so it shouldn't be causing the issue either.

Finally, the fourth choice seems to hit the nail: we are in the presence of one of the most common problems when training a GAN: "[Mode collapse.](https://developers.google.com/machine-learning/gan/problems#mode-collapse)"

Mode collapse happens when the discriminator network gets stuck in a local minimum, and the generator learns to fool it by consistently producing a few samples repeatedly. At this point, the generator stops producing images for most of the numerals, and we end up with results from a few classes.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* [Andrej Karpathy](https://twitter.com/karpathy) built a [Generative Adversarial Network tool](https://cs.stanford.edu/people/karpathy/gan/) that you can use to play around with different hyperparameters when training a GAN.
* For a deep dive into Generative Adversarial Networks, check Neuromatch's Academy [Introduction to GANs](https://deeplearning.neuromatch.io/tutorials/W2D4_GenerativeModels/student/W2D4_Tutorial2.html).</p></details>

-----------------------

## Date - 2022-07-22


## Title - Agatha Christie's novels


### **Question** :

Maeve wanted to win the hackathon, so she went with a fun and impressive application.

She downloaded the text of three dozen Agatha Christie novels and used it to train a model to impersonate the author and generate short stories using her style.

The most exciting part was that Maeve's model wrote the stories one character at a time!

**Which of the following models do you think Maeve used to build her solution?**


### **Choices** :

- A Feed-forward Neural Network
- A Convolutional Neural Network
- A Recurrent Neural Network
- A Text Generation Neural Network


### **Answer** :

<details><summary>CLICK ME</summary><p>0010</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Maeve used a [Recurrent Neural Network](https://en.wikipedia.org/wiki/Recurrent_neural_network) (RNN) to build her model. This choice gave Maeve an essential advantage.

Maeve's model receives a large chunk of text, one character at a time, and outputs the probability distribution of the next character in the sequence. This approach may not sound impressive until you think carefully about what it does when generating a word like "HELLO": the first time she feeds the model the letter "L," its output should be another "L," but the second time, the output switches to an "O."

This ability reveals a critical characteristic of Recurrent Neural Networks: they don't solely rely on their input to make predictions. Instead, they have a memory to keep context and use it to generate their output. In other words, the RNN's output is influenced not only by its input but also by the history of inputs Maeve used in the past.

Keeping context around and using it for text generation is crucial for Maeve's application.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* Check ["The Unreasonable Effectiveness of Recurrent Neural Networks"](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) by Andrej Karpathy for the motivation behind Recurrent Neural Networks.
* ["An Introduction To Recurrent Neural Networks And The Math That Powers Them"](https://machinelearningmastery.com/an-introduction-to-recurrent-neural-networks-and-the-math-that-powers-them/) is an excellent introduction to Recurrent Neural Networks.
* Neuromatch's Academy ["Time series for Language"](https://deeplearning.neuromatch.io/tutorials/W2D5_TimeSeriesAndNaturalLanguageProcessing/student/W2D5_Tutorial2.html) also introduces Recurrent Neural Networks.</p></details>

-----------------------

## Date - 2022-07-23


## Title - Different twins


### **Question** :

Mary and Jane were twins.

Despite their striking physical similarities, they were very different people.

Mary was stubborn. She had a specific mental model for everything, and no matter the situation, she would follow her model regardless of the consequences. As Jane frequently said, Mary was always biased in her process.

On the other hand, Jane was all over the place, sometimes, even to a fault. She could not generalize and gave too much importance to small and irrelevant details. Her variability drove Mary crazy.

**If Mary and Jane were machine learning models, which of the following would be correct?**


### **Choices** :

- Mary will be more likely to overfit. Jane will be more likely to underfit.
- Mary will be more likely to underfit. Jane will be more likely to overfit.
- Mary will be more likely to underfit. Jane will be similarly likely to overfit and underfit.
- Mary will be similarly likely to overfit and underfit. Jane will be more likely to overfit.


### **Answer** :

<details><summary>CLICK ME</summary><p>0100</p></details>


### **Explaination** :

<details><summary>CLICK ME</summary><p>Neither Mary nor Jane are machine learning models, but this makes for an interesting question, so let's go with it.

We know that Mary has a high bias. She pays little attention to the situation that she is in and instead always follows a specific mental model. Her inability to adapt to scenarios that aren't part of her mental models makes her decisions suboptimal.

Because of the high bias, Mary will be more likely to underfit. She isn't capable of adapting to new situations, so she wouldn't take advantage of new opportunities and will always get mediocre results.

On the other hand, Jane has the opposite problem: She is high variance. Jane pays a lot of attention to every detail, no matter how unimportant. Her lack of mental models will take her down rabbit holes that won't be productive. Because of this, Jane will be more likely to overfit.</p></details>


### **References**: 

<details><summary>CLICK ME</summary><p>* ["Understanding the Bias-Variance Tradeoff"](https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-165e6942b229) is a great introduction to bias, variance, and their tradeoff.
* ["Gentle Introduction to the Bias-Variance Trade-Off in Machine Learning"](https://machinelearningmastery.com/gentle-introduction-to-the-bias-variance-trade-off-in-machine-learning/) is an excellent introduction to the bias and variance tradeoff.
* The Wikipedia page on bias and variance is also a good resource: ["Bias???variance tradeoff"](https://en.wikipedia.org/wiki/Bias???variance_tradeoff).</p></details>

-----------------------

