# BIOCAD Тестовое задание

Этот проект представляет собой простое веб-приложение "Hello World", развернутое в контейнере Docker и управляемое с помощью Kubernetes в Minikube.

## Начало работы

Эти инструкции помогут вам получить копию проекта и запустить его на вашем локальном компьютере для разработки и тестирования.

### Предварительные условия

Для запуска этого проекта убедитесь, что у вас установлены:

- Docker
- Minikube
- kubectl

### Установка и Запуск

1. **Клонирование репозитория**:
   ```bash
   git clone https://github.com/Bagautdino/bc_test.git
   cd bc_test
   ```

2. **Запуск Minikube**:
   ```bash
   minikube start
   ```

3. **Развертывание в Kubernetes**:
   ```bash
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml
   ```

4. **Проверка запущенных сервисов**:
   ```bash
   minikube service list
   ```

