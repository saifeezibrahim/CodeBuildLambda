# 🚀 AWS CodeBuild + Lambda Integration Lab

> **A hands-on playground to learn how AWS CodeBuild and Lambda work together for automated CI/CD on AWS!**

---

## 🌟 What is This Project?

This repository is a step-by-step learning guide for building a continuous deployment pipeline using:
- **AWS CodeBuild**: Automate building and packaging your code
- **AWS Lambda**: Run serverless functions to orchestrate or trigger deployments
- **CloudFormation (template.yml)**: Infrastructure-as-Code to provision everything automatically

Whether you're a DevOps beginner or prepping for AWS certifications, this is your practical sandbox!

---

## 🛠️ What You'll Practice

- Writing a Lambda function (`lambda_function.py`) to trigger or react to build events
- Defining build steps in `buildspec.yml` for AWS CodeBuild
- Deploying everything with a single `template.yml` using AWS CloudFormation
- Building an end-to-end CI/CD workflow for serverless apps

---

## 📦 Repository Structure

```plaintext
README.md            # This file! (Learning guide)
lambda_function.py   # Example AWS Lambda function code (Python)
buildspec.yml        # AWS CodeBuild build instructions
template.yml         # CloudFormation template for provisioning resources
```
👉 [See all files and explore in GitHub](https://github.com/saifeezibrahim/CodeBuildLambda/tree/master)

---

## 🚦 Quick Start

### 1. **Clone the repository**
```bash
git clone https://github.com/saifeezibrahim/CodeBuildLambda.git
cd CodeBuildLambda
```

### 2. **Review & Edit the Code**
- Edit `lambda_function.py` to customize your Lambda actions
- Update `buildspec.yml` for your build needs

### 3. **Deploy with CloudFormation**
- Use the AWS Console or CLI to deploy the stack:
    ```bash
    aws cloudformation deploy --template-file template.yml --stack-name codebuild-lambda-demo
    ```

### 4. **Trigger CodeBuild and Lambda**
- Push code changes to trigger CodeBuild
- Observe Lambda execution as defined in your templates

---

## 🎓 Who Is This For?

- DevOps learners exploring AWS automation
- Students prepping for AWS DevOps Engineer or Developer exams
- Anyone curious about end-to-end serverless CI/CD pipelines

---

## 💡 Learning Tips

- Read and tweak each YAML and Python file—break things and fix them!
- Consult [AWS Docs](https://docs.aws.amazon.com/) for deeper dives on each service
- Experiment with adding notifications, S3 triggers, or extra build steps

---

## 🙋‍♂️ Maintained by Saifee Zibrahim

If you found this helpful, give a ⭐ or connect on GitHub!  
Fork, learn, and contribute—this project is built for experimentation.

---

## 📄 License

MIT — Free to use for personal and educational purposes.

---

> **Keep automating real DevOps skills come from building and breaking things!**
