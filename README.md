# Movie Picture Pipeline

## Project Overview
This project demonstrates a full CI/CD pipeline for a **Movie Frontend** and **Backend** application using:

- **GitHub Actions** for Continuous Integration (CI) and Continuous Deployment (CD)
- **Docker** for containerization
- **Amazon ECR** for Docker image hosting
- **Amazon EKS** for Kubernetes deployment

The project automatically lints, tests, builds, and deploys the applications on every merge to the `main` branch.

---

## GitHub Actions Workflows

### Frontend
- **Continuous Integration:** `.github/workflows/frontend-ci.yaml`
- **Continuous Deployment:** `.github/workflows/frontend-cd.yaml`

### Backend
- **Continuous Integration:** `.github/workflows/backend-ci.yaml`
- **Continuous Deployment:** `.github/workflows/backend-cd.yaml`

All workflows are passing successfully with no errors.

---

## Running Applications

### Backend API
- **Endpoint URL:** [Backend API](http://aefe888f25371482e9641174c1062121-1960966480.us-east-1.elb.amazonaws.com/movies)
- Returns a JSON list of movies:

### Frontend Application

- **URL:** [Frontend Application](http://a2364be79ff3848c985c4fc5fb42d17d-610079682.us-east-1.elb.amazonaws.com)  
- **Description:** Displays a list of movies fetched from the backend API and allows user interaction.  
 

