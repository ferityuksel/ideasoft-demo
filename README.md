IDEASOFT DEMO APP
Azure DevOps CI/CD Pipeline
Azure DevOps platformu üzerinden CI/CD süreçleri aşağıdaki adımları izler:

1.	Install Dependencies: Symfony bağımlılıkları yüklenir.

2.	Run Unit Tests: PHPUnit testleri çalıştırılır.

3.	SonarQube Analysis: Kod kalitesi analizi yapılır.

4.	Build and Push Docker Image: Docker image oluşturulur ve Docker Hub’a gönderilir.

5.	Deploy to Kubernetes: Helm kullanılarak Kubernetes'e dağıtım yapılır.

Demo uygulamasının imajına aşağıdaki komut ile ulaşabilirsiniz.
docker push ferityuksel/demoideasoft:52
