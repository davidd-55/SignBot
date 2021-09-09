# SignBot: The Hand-Guided Robot

![Tello EDU](https://cdn.shopify.com/s/files/1/0675/6963/products/TELLO_EDU_V4.88.png?v=1581170530)

## Project Description

#### The Project:
For this project, I hope to use neural networks (NNs) to create a controller-less robot of some kind. To do this, I aim to train a NN to classify various hand signals and map these classifications to movement in the physical world. 

In the long term or in case of a project extension, it could be interesting to experiment with how the NN reacts to multiple humans giving commands or building in an autonomous "follow mode" to default to during lapses in commands.

#### The Software:
After creating a dataset and using it to train an image classification NN, it will be necessary to explore the nuances of mapping NN outputs to robotic motor controls. A successfully deployed version of this may look like an aerial drone that can take off, navigate in space, and land with a "pilot" solely giving natural, hand-based commands.

#### The Hardware: 
The image above is a [Tello EDU](https://www.ryzerobotics.com/tello-edu) drone - a $100, fully programmable microdrone that I believe would be an excellent candidate for this project. However, I also think it would be interesting to experiment with creating a ground-based robot from individual components ([cool example](https://www.instructables.com/Remote-Control-Tank-Drive/)) for a more robotics-heavy project.

## Project Goals

1. Create/find (or both!) a dataset of hand signal images ([potential dataset](https://www.kaggle.com/gti-upm/leapgestrecog))
2. Train a NN to recognize these hand signals
3. Map recognized hand signals to directional output from the robot
4. Become more familiar with robotic hardware and the software system that drive it
5. Explore the ethics of computer vision use in drones

## Project Unknowns

- Should we create or find a dataset?
- Would we like to dig into the actual robotics by building our own (ground-based) drone?
- What does "success" look like?
