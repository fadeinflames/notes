---
share: true
---
  
---  
### **1. Базовые концепции SRE (1–2 недели)**  
- **Что изучать:**  
  - Основы SRE: SLA, SLO, SLI, Error Budget, Toil, Postmortem.  
  - Культура blameless postmortems и инцидент-менеджмент.  
  - Принципы надежности и баланс между фичами и стабильностью.  
- **Что почитать:**  
  - Книга:**"Site Reliability Engineering"** (O’Reilly, Google).  
  - Воркбук:**"The Site Reliability Workbook"** (Google).  
- **Ресурсы:** [Google SRE Resources](https://sre.google/).  
#### [SRE Theory check-list](./SRE%20Theory%20check-list.md)  
  
---  
  
### **2. Углубление в инфраструктуру и сети (1–2 месяца)**  
- **Технологии:**  
  - **Linux/Unix:** Управление процессами, сети, файловые системы, Bash/Python-скрипты.  
  - **Сети:** TCP/IP, DNS, HTTP, Load Balancing, Firewalls, CDN.  
  - **Базы данных:** Основы SQL/NoSQL, репликация, шардинг.  
- **Чем можно попрактиковаться:**  
  - Настройка серверов на Ubuntu/CentOS.  
  - Работа с сетевыми утилитами:` netstat, tcpdump, curl, iptables.`  
  - Работа с логами, процессами, правами.  
- **Курсы, которые можно посмотреть:**  
  - **"Linux Foundation: Introduction to Linux"** (edX).  
  - **"Computer Networking"** (Coursera, от Stanford).  
  
---  
  
### **3. Инструменты автоматизации и IaC (2–3 месяца)**  
- **Технологии:**  
  - **Terraform** (Infrastructure as Code).  
  - **Ansible** (еще IaC).  
  - **CI/CD:** Jenkins, GitLab CI, GitHub Actions. Teamcity and etc.  
- **Чем можно попрактиковаться:**  
  - Развертывание инфраструктуры в облаке (AWS/GCP, YC) через Terraform.  
  - Автоматизация деплоя приложения с Ansible + CI/CD.  
- **Курсы и книги, которые можно посмотреть/почитать:**  
  - **"HashiCorp Certified: Terraform Associate"** (Udemy).  
  - **"Ansible for DevOps"** (книга + практика).  
  
---  
  
### **4. Контейнеры и оркестрация (2–3 месяца)**  
- **Технологии:**  
  - **Docker:** Сборки dockerfile, создание образов, сети, volumes.  
  - **Kubernetes:** Pods, Deployments, Services, Helm, Operators.  
  - **Service Mesh:** Istio, Linkerd (крайне опционально).  
- **Чем можно попрактиковаться:**  
  - Развертывание кластера k8s (minikube, kind, k3s, EKS/GKE (рекомендую kind)).  
  - Миграция с монолита на микросервисы в k8s.  
- **Курсы и книги, которые можно посмотреть/почитать:**  
  - **"Docker Mastery"** (Udemy, Bret Fisher).  
  - **"Certified Kubernetes Administrator (CKA)"** (KodeKloud).  
  
---  
  
### **5. Мониторинг и observability (1–2 месяца)**  
- **Технологии:**  
  - **Метрики:** Prometheus, Grafana, VictoriaMetrics and etc.  
  - **Логи:** ELK Stack (Elasticsearch, Logstash, Kibana), Loki.  
  - **Трейсинг:** Jaeger, OpenTelemetry, Tempo.  
  - **Инструменты:** Datadog, New Relic, Sentry (крайне опционально).  
- **Чем попрактиковаться:**  
  - Настройка мониторинга для приложения в k8s.  
  - Создание алертов на основе SLO.  
  
---  
  
### **6. Облачные платформы (1–2 месяца)**  
- **Технологии:**  
  - **AWS:** EC2, S3, RDS, Lambda, CloudFormation.  
  - **GCP:** Compute Engine, Cloud Storage, GKE.  
  - **Azure:** VM, AKS, Functions.  
  - **YC**: Compote, Storage, K8S  
- **Чем попрактиковаться:**  
  - Развертывание высокодоступного приложения в облаке.  
  - Настройка auto-scaling и disaster recovery.  
- **Курсы, которые можно посмотреть:**  
  - **"AWS Certified DevOps Engineer"** (A Cloud Guru).  
  - **"Google Cloud Associate Cloud Engineer"** (Coursera).  
  
---  
  
### **7. Углубленные темы (2–3 месяца)**  
- **Направления:**  
  - **Надежность:** Chaos Engineering (Chaos Monkey, Gremlin).  
  - **Безопасность:** DevSecOps, Vault, RBAC в k8s (крайне опционально).  
  - **Оптимизация:** Performance tuning, cost optimization.  
- **Что почитать:**  
  - **"Chaos Engineering"** (Casey Rosenthal).  
  - **"Building Secure and Reliable Systems"** (Google).  
  
---  
  
### **8. Практика и проекты**  
- **Проекты:**  
  - Свой кластер k8s с мониторингом и CI/CD.  
  - Chaos-тесты для приложения.  
- **Тестовые задания:**  
  - Автоматизировать развертывание приложения с нуля (от кода до прода).  
  - Реши задачи из **"Google SRE Interview Questions".**  
  
---  
  
### **9. Подготовка к собеседованиям (1 месяц)**  
- **Что учить:**  
  - Системный дизайн для SRE (надежность, масштабирование (крайне обязательно)).  
  - Алгоритмы и структуры данных (базово, на Go, но тебе это точно не надо))).  
  - Вопросы по Linux, сетям, k8s.  
- **Что почитать и посмотреть:**  
  - **"Site Reliability Engineering Interview"** (YouTube).  
  - **LeetCode** (easy/medium задачи).  
  
---  
