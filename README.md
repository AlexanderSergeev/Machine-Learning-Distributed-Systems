# Machine-Learning-Distributed-Systems

Research addressing the problems of distributed systems in machine learning.

Instructions:
1. Download the TensorFlow Serving Docker image and repo:

docker pull tensorflow/serving

2. Start multiple(5) scaled TensorFlow Serving containers and open the REST API ports:

docker-compose up --scale tensorflow-serving=5
