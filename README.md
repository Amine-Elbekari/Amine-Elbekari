# Hi, I'm Amine El bekari

Full Stack Engineer studying at 1337 Coding School, part of the 42 Network.

I enjoy building web applications, backend systems and tools that solve real problems.

Most of my learning comes from building projects and understanding what happens behind the abstraction, especially around APIs, databases, distributed systems, cloud infrastructure and AI integration.

## What I work with

### Frontend

React, Next.js, TypeScript, JavaScript

### Backend

Python, FastAPI, Django, Node.js, NestJS

### AI

RAG, Sentence Transformers, ChromaDB, Ollama, Qwen

### Databases

PostgreSQL, Redis, SQL

### Cloud and DevOps

Docker, Kubernetes, K3s, AWS, Ansible, Linux, Nginx, Git

### Security

eJPT Certified

## Selected Projects

### Booking Platform

A booking system I built to understand how real reservation platforms handle availability, concurrency and data consistency.

One of the main problems I wanted to solve was double booking.

If two users try to reserve the same property at the same time, the system needs to make sure that only one reservation succeeds.

I used Redis locks together with PostgreSQL row locking to handle concurrent booking requests safely.

The project also includes a frontend built with React and TypeScript, with FastAPI handling the backend services.

Tech

FastAPI, PostgreSQL, Redis, React, TypeScript, Docker, Nginx

Repository

https://github.com/Amine-Elbekari/Booking-Platform

#### RAG Assistant

I later added an assistant inside the same booking platform.

Users can ask questions about their bookings or uploaded rental documents.

Documents are split into smaller sections, converted into embeddings and stored in ChromaDB.

For booking related questions, the system retrieves information directly from PostgreSQL.

The backend decides which data can be accessed based on the authenticated user.

Tech

FastAPI, Sentence Transformers, ChromaDB, Ollama, Qwen, PostgreSQL

Same repository

https://github.com/Amine-Elbekari/Booking-Platform

### Inception of Things

A Kubernetes project built at 1337 to understand container orchestration and application deployment.

I mainly worked on Part 1 and Part 2.

I configured a K3s cluster with server and worker nodes, then deployed multiple applications using Kubernetes Services and Ingress.

The project also introduced me to infrastructure automation using Vagrant and Ansible.

Tech

Kubernetes, K3s, Vagrant, Ansible, Docker, Linux

Repository

https://github.com/Amine-Elbekari/Inception_of_things

### Cloud 1

A cloud infrastructure project focused on moving an application from a local environment to AWS.

I automated the deployment process with Ansible, including EC2 provisioning, Docker installation, application deployment, TLS configuration and server lifecycle management.

Tech

AWS EC2, Ansible, Docker, Linux, TLS

Repository

https://github.com/Amine-Elbekari/Cloud-1

### Piscine Django

A collection of backend projects built while learning Django and Python.

I worked with Django ORM, raw SQL, authentication, permissions, testing, WebSockets and PostgreSQL.

Tech

Python, Django, PostgreSQL, SQL, WebSockets

Repository

https://github.com/Amine-Elbekari/Piscine-Django

## 1337 Coding School

I study at 1337 Coding School, part of the 42 Network.

The program is project based and focuses heavily on learning by solving problems and building systems.

It has taken me through C, C++, Unix, networking, web development, security, Docker, cloud infrastructure and Kubernetes.

<!-- Put your 42 badge here if you want to keep it -->

## Portfolio

https://amineelbekari.tech

## Contact

LinkedIn

https://linkedin.com/in/amine-el-bekari

Email

amineelbekari8@gmail.com
