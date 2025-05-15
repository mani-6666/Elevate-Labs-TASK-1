
# Node.js CI/CD Pipeline using GitHub Actions

This repository contains a simple Node.js web application that demonstrates a fully automated CI/CD pipeline using **GitHub Actions** and **Docker**.

## 🚀 Objective

To automate the process of building, testing, and deploying a Node.js application using GitHub Actions CI/CD pipeline and Docker.

---

## 🛠️ Tools & Technologies Used

- **GitHub** – Source code hosting and version control
- **GitHub Actions** – CI/CD automation
- **Node.js** – Runtime environment for JavaScript
- **Docker** – Containerization of the application
- **DockerHub** – Container registry for Docker images

---

## 📁 Project Structure

```
├── index.js
├── package.json
├── Dockerfile
└── .github
    └── workflows
        └── main.yml
```

---

## ⚙️ GitHub Actions Workflow

The CI/CD pipeline is defined in `.github/workflows/main.yml` and is triggered on every push to the `main` branch. Here's what it does:

1. **Checkout Code** – Pulls the latest code from the repository
2. **Set Up Node.js** – Installs Node.js environment
3. **Install Dependencies** – Runs `npm install`
4. **Run Tests** – Placeholder step for testing (`npm test`)
5. **Build Docker Image** – Builds the application Docker image
6. **Push Docker Image** – Pushes the Docker image to DockerHub

---

## 🔄 CI/CD Pipeline Steps

- **Trigger:** On push to `main` branch
- **Build:** Installs dependencies and builds the Docker image
- **Test:** Placeholder test command (`npm test`)
- **Deploy:** Docker image is pushed to DockerHub

---

## 🔧 How to Use

1. Fork or clone the repository
2. Set your **DockerHub credentials** as GitHub Repository Secrets:
   - `DOCKER_USERNAME`
   - `DOCKER_PASSWORD`
3. Push code to `main` branch
4. Watch the pipeline execute in GitHub Actions tab

---

## ✅ Result

Every time code is pushed to `main`, the application is automatically built, tested, containerized, and the Docker image is pushed to DockerHub – **No manual steps required!**

---

## 📸 Screenshots

*Refer to the screenshots in the repository for detailed results of each pipeline step.*

---

## 🙌 Acknowledgments

Thanks to the mentors and community support that guided the completion of this task.
