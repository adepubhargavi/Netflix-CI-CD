# Netflix-CI-CD

code base : https://github.com/N4si/DevSecOps-Project

Ports:
```
Jenkins - 8080
--Sonarqube - 9000
--Prometheus - 9090
--Grafana - 3000
--Node Exporter - 9100
```

Project Architecture:

![DevSecOps](https://github.com/user-attachments/assets/db86bba7-55d4-4b93-a7ea-befd5a981b7c)

1.Implemented CI/CD

![image](https://github.com/user-attachments/assets/a94b888f-66a6-4900-9f24-bc234cc85a20)

2.Invoked security (sonarqube) to check the code vulnerabilities

![image](https://github.com/user-attachments/assets/109b9b8e-b068-4974-aefe-7f488ad1c1b0)

3. Invoked Trivy scan for docker image scanning and DP-check(owasp) for dependency vulnerability check
4. Integrated Prometheus, node-exporter to collect metrics, grafana dashboard for visualisation

![image](https://github.com/user-attachments/assets/51acad10-385e-4b00-9f26-b12c8b7f084b)
![image](https://github.com/user-attachments/assets/49e927ac-bea0-42b8-bb75-345639a4a605)

5. Deployed the k8's application through EKS and argocd

![image](https://github.com/user-attachments/assets/4433086e-b21d-4c3d-9d9b-cb5b7bfaed44)

6. Netflix application is running on EKS cluster

![image](https://github.com/user-attachments/assets/db1b45ce-3f0f-4fd2-9604-a99318971e4b)






