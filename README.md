# CI/CD Experiment-20

## Steps to Run

1. Build Docker Image:
   docker build -t my-backend-app .

2. Run Container:
   docker run -d -p 3000:3000 my-backend-app

3. Push to GitHub:
   git add .
   git commit -m "CI/CD setup"
   git push origin main

4. Check GitHub Actions tab for workflow execution.
