# facial-recognition-using-ConvNet-Inception

This project was built using CNN and Transfer Learning, we will be using a pre-trained model which represents ConvNet activation.

# Facial Recognition

In this notebook, we will build a face recognition system. Many of the ideas presented here are from [FaceNet](https://arxiv.org/pdf/1503.03832.pdf) and [DeepFace](https://research.fb.com/wp-content/uploads/2016/11/deepface-closing-the-gap-to-human-level-performance-in-face-verification.pdf). 

Face recognition problems commonly fall into two categories: 

- **Face Verification** - "is this the claimed person?". For example, at some airports, you can pass through customs by letting a system scan your passport and then verifying that you (the person carrying the passport) are the correct person. A mobile phone that unlocks using your face is also using face verification. This is a 1:1 matching problem. 
- **Face Recognition** - "who is this person?". For example, the video lecture showed a face recognition video (https://www.youtube.com/watch?v=wr4rx0Spihs) of Baidu employees entering the office without needing to otherwise identify themselves. This is a 1:K matching problem. 

FaceNet learns a neural network that encodes a face image into a vector of 512 numbers. By comparing two such vectors, you can then determine if two pictures are of the same person.
    
**In this notebook, we will:**
- Implement the triplet loss function
- Use a pretrained model to map face images into encodings
- Use these encodings to perform face verification and face recognition


![image](https://user-images.githubusercontent.com/50231750/193011010-95a2f21d-60ad-42c2-b50f-026eb5b49292.png)

## Triplet Loss 
![image](https://user-images.githubusercontent.com/50231750/193011358-207c6a83-5d9b-4081-8521-4799c9b67404.png)





