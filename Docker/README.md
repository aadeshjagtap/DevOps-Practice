# 🐳 Docker Practicals

This repository contains my hands-on practice with Docker.
I am learning how to build, run, and manage containers using real examples.

---

## 📌 About

This section includes basic to intermediate Docker concepts with practical implementation.

---

## 🛠️ Technologies Used

* Docker
* Linux
* Nginx (for demo)

---

## 📁 Practicals Covered

1. Basic Docker commands (run, ps, images)
2. Running Nginx container
3. Creating Dockerfile
4. Building custom image
5. Port mapping
6. Volume mounting
7. Environment variables
8. Docker logs & exec
9. Docker networking basics

---

## ⚙️ How to Run (Example)

### Pull nginx image

```bash id="yqbtvy"
docker pull nginx
```

### Run container

```bash id="jjocdr"
docker run -d -p 8080:80 nginx
```

Open browser:
http://localhost:8080

---

## 📊 Features

* Container creation
* Image building
* Port exposure
* Volume usage

---

## 🧠 What I Learned

* Difference between image and container
* How Docker works internally
* How to run applications inside containers

---

## 👨‍💻 Author

Adesh Jagtap
