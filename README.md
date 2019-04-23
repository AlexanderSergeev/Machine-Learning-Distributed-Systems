# Machine-Learning-Distributed-Systems

Research addressing the problems of distributed systems in machine learning.

Instructions:
1. Download the TensorFlow Serving Docker image and repo:

docker pull tensorflow/serving

2. Set your local model path in docker-compose.yml volumes section

3. Deploy on Kubernetes (bind to port 8501)

docker stack deploy --compose-file docker-compose.yml news

4. Use the following command to get the information about running nodes

kubectl get all
