
<img width="940" alt="Pod" src="https://user-images.githubusercontent.com/81834520/247380521-33a7d81c-d3ee-4f52-a00d-6e91e1988591.png">
Each pod has its own IP address.<br>
Each time when pod dies, a new IP address is generated.<br> 
So here comes service...
<img width="940" alt="service" src="https://user-images.githubusercontent.com/81834520/247380548-20b825f9-95a4-459e-83a0-f798a65ac008.png">
Pods communicate with each other using a service

<img width="940" alt="external internal service" src="https://user-images.githubusercontent.com/81834520/247380559-d210cc12-7a50-4b2f-a468-2a7651618818.png">

<img width="940" alt="Ingress" src="https://user-images.githubusercontent.com/81834520/247373939-bd65c60f-d546-4392-a36d-54783f7963cb.png">

<img width="862" alt="Screen Shot 2023-06-20 at 10 44 50 PM" src="https://github.com/leiliangmichelle/Kubernetes-mongoExpress-mongoDB/assets/81834520/fc218f64-8579-4e51-86f8-da15cd3226b0">
Request --> Ingress --> service

<img width="864" alt="Screen Shot 2023-06-20 at 11 02 53 PM" src="https://github.com/leiliangmichelle/Kubernetes-mongoExpress-mongoDB/assets/81834520/bde1b760-fa51-4dcf-b2ee-0f73dfb43fb7"> <br>
Service 
<br> Persistent/permenant IP address with a DNS name</br>
<br> Load Balancer - forward to whichever pod is less busy </br> 
