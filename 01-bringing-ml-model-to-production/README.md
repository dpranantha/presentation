# Space Summit 2020

## Topic
Selective topics for Bol.com Space Summit 2020 for team 2a:
1. Bringing predictive models to Production
2. Measuring your service and your slots
3. REST API for exposing predictive models: dependency management, tips/tricks of deployment, framework, performance
4. ~~Production grade data science project for dummies~~

# Topic 1. Bringing predictive models to Production
## Abstract
Providing an engaging customer experience is no longer optional but is instead, demanded by customers. The 5th edition of Salesforce "State of Marketing Report" reveals 
that 60% of customers expect companies to step up in anticipating their needs. This involves a variety of ways such as, better pricing, personalized contents, intelligent chat-bot, 
fast and reliable delivery; richer, seamless, and natural interactions, etc. One of ways to better customer experiences is becoming AI (artificial intelligence) driven company. 

AI and its subset, Machine Learning (ML), provide avenues for delegating complex decisions to intelligent entities based on facts (data). 
For instance, we create a model that predicts customers intention during visit based on historical visits. 
Using cloud infrastructure, theoretically we can create and train various models and use them for various purposes within the company.

Having several ML models in production, we would like to share our experiences in deploying models into production. We will provide a list of things you need to consider
when you are planning to train a model and bring it to production.   

## Talk Description
### Objectives:
- As a team who had deployed and tested several models in production, we'd like to share **lesson learned** when you bring model to production

### What we will cover:
1. What you'll NOT learn from this talk:  
- ~~Machine learning (ML) algorithm?~~
- ~~Deep learning and tensorflow~~
- ~~Techniques/tools in data science~~
- ~~Cloud architecture for machine learning~~
2. What you'll learn from this talk:
- What does it take to develop and bring models to production?
- What do you need to prepare before running experiment on models?

### Background/ Why This Talk: 
- data science is gaining more traction within the company
- cloud technology allows scalable data collection 
- cloud technology allows scalable model training
=> promote model authoring and experimentation (given that the necessary data is readily available)

As we embrace data science mode in our organization, it's good to know common obstacles in bringing predictive model to production. 


## Presentation

* [Half Hour Long Presentation](https://dpranantha.github.io/presentation/01-bringing-ml-model-to-production/index.html#/)


Lifecycle:

1. Before model training:
    - Hypotheses
    - Feature engineering, KPI, and Data collection IF needed
        - Brainstorming or testing features;
        - Deciding what features to create;
        - Creating features;
        - Checking how the features work with your model;
        - Improving your features if needed;
        - Go back to brainstorming/creating more features until the work is done.
2. During model training:
    - Feature selection
        - consider not all available features?
    - Model training
    - Model evaluation: more data, more features, different model?
    - Model selection
3. After model training:
    - Model deployment for inference
4. Experiments:
    - Accept/Reject null hypothesis

Lessons:
1. Make sure features are available for both training and prediction
2. Make sure features are aligned for both training and prediction
3. Make sure you are able to track your model performance and think about what you need for improvement ahead
   - Make sure you tag your model which describes what kind of algo it was trained and to what purpose
4. Make sure you choose performing framework for serving/inference
5. Make sure you test thoroughly
   - prediction: use training data
   - performance test: mimic real-time request loads 

Notes on working with Python:

* Proper dependency management and packaging: https://johnfraney.ca/posts/2019/03/06/pipenv-poetry-benchmarks-ergonomics/
* Manage end-to-end ML lifecycle https://mlflow.org/docs/latest/index.html
* Other sources: 
  * https://towardsdatascience.com/all-machine-learning-models-explained-in-6-minutes-9fe30ff6776a

## Plan to be delivered at

* Bol.com Space Summit 2020

# Topic 2. Measuring your service and your slots
## Abstract
TODO

## Talk Description
### Objectives:
- As a team who had deployed and tested several models, personal campaigns variations in production, we'd like to share our technique in performing end to end measurements 
- What those measurements are useful for? 2 use cases

### What we will cover:
1. What you'll NOT learn from this talk:  
- ~~Data processing framework?~~
2. What you'll learn from this talk:
- some techniques in performing end to end measurements:
    1. annotating each unit (read: function) in our service
    2. measuring our own service
    3. transferring annotation into m2 adhering to m2 schema
    4. collecting and processing data from m2
    5. correlating service measurement to m2 measurement
- use cases
    1. satori measurement
    2. octo measurement

### Background/ Context/ Why This Talk: 
- we're experiments driven company
- we are trying to reason experimental results by measuring more: M2/K2 teams 
=> we know why things work or why things don't work?

As we are experiment driven organization, we would like to learn why certain things work or not. The key is to measure important events such that we can analyze, correlate, and reason about. 
This talk will provide you a working example of measuring every unit of your experiment.

## Presentation

* [Article]()
* [Half Hour Long Presentation]()

## Plan to be delivered at

* Bol.com Space Summit 2020

# Topic 3.  REST API for exposing predictive models: dependency management, tips/tricks of deployment, framework, performance
## Abstract
TODO

## Talk Description
### Objectives:
- As a team who had deployed and tested several models, we'd like to share our technique in creating performing REST API

### What we will cover:
1. What you'll NOT learn from this talk:  
    - ~~Machine learning model~~
    - ~~Machine learning algorithm~~
    - ~~Micro-services and RESTful API architecture~~
2. What you'll learn from this talk:
    - TBD
    
### Background/ Context/ Why This Talk: 
TBD

## Presentation

* [Article]()
* [Half Hour Long Presentation]()

## Plan to be delivered at

* Bol.com Space Summit 2020

