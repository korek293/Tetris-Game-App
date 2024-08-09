# Deploy-Tetris-Game-to-Azure-App-Service-using-Azure-Pipelines
This project demonstrates the creation of a fully automated CI/CD pipeline using Jenkins, Azure, and Docker. The pipeline is designed to build and deploy a Dockerized application to Azure App Services upon any code changes in a GitHub repository.




![image](https://github.com/user-attachments/assets/097c63fa-48e2-492f-9016-6cd003a68218)


Key features include:

Automated CI Process: Jenkins pulls the latest code, builds a Docker image, and pushes it to Azure Container Registry (ACR) upon each commit.
Automated CD Process: The Docker image is then automatically deployed to Azure App Services, ensuring the latest version of the application is always live.
Azure Integration: Seamless integration with Azure through service principals, enabling secure and efficient deployments.
Scalability: This setup can be easily adapted for different applications or environments, providing a robust foundation for cloud-native CI/CD pipelines.
This project is ideal for developers looking to streamline their deployment processes and integrate continuous delivery practices into their workflow.



Video ---- https://youtu.be/wxsYA_NB8os
