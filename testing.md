# Testing phase

Testing ensures software reliability, stability, and maintainability.


## Components of software testing. 

- People: to ensure that there is adequate education and awareness;

- Process: to ensure that there are adequate policies and standards and that people know how to follow these policies;

- Technology: to ensure that the process has been effective in its implementation.



## Best Practices for Testing & Debugging

✔ Write test cases early in development.

✔ Use version control (Git) to track changes.

✔ Log errors effectively for easy debugging.

✔ Automate repetitive tests to save time.


## Types of testing 

## 1. Manual Testing

### Unit testing

Testing individual components i.e functions/classes.

Tools 
- Jest
- Vitest 
- Chai
- TestNG
- JUnit (Java)
- PyTest (Python)
- Mocha (JavaScript).

  
### Intergration testing

  verify that different modules of an application work together correctly.

  Tools 
- Supertest
- Jest
- Cucumber
- Spring Test 

- System testing 

### End-to-End (E2E) Testing/Acceptance testing.

Simulate real user interactions to ensure complete functionality.

 Tools
- Cypress and Playwright 

### API Testing
API testing helps validate RESTful and GraphQL APIs.

  Tools
- Postman  
- Newman 

### Test-Driven Development (TDD)
Writing tests before code improves reliability and ensures code correctness



## 2. Automated testing 

### Regression testing

Ensures new code does not break existing features.

Automation – Selenium, Cypress, Puppeteer.


### Performance testing 
Checking speed, Scalability and stability of software.

   Tools
- JMeter
- k6 
- LoadRunner.


### Security testing
Finding vulnerabilities in code using penetration methods

Tools
- OWASP ZAP
- Burp Suite.
 
Types of security testing 
- Vulnerability scanning 
- Software penetration testing 
- Risk assessment 
- Security Auditing 
- Source code review





---------------------------------------------------------------



# Continuous Intergration/Continuous Deployment (CI/CD)

CI/CD is a DevOps practice that automates software development, testing, and deployment, ensuring rapid and reliable code delivery.




  Best Practices for CI/CD
  
✔ Automate everything – Builds, tests, deployments.

✔ Use Infrastructure as Code (IaC) – Terraform, Ansible, Docker.

✔ Implement Security (DevSecOps) – Static code analysis, security testing.

✔ Monitor & Log – Prometheus, Grafana, ELK Stack.

✔ Use Feature Flags – Deploy safely without impacting users.

✔ Integrate AI debugging tools with CI/CD pipelines for automated bug fixing.


## 1. Continuous Integration (CI)

CI automates the process of merging code changes into a shared repository, testing them early to catch bugs.


### Popular CI Tools:

- Jenkins: Open-source, highly customizable.
- GitHub Actions: Built-in for GitHub repositories.
- GitLab CI/CD: Fully integrated with GitLab.
- CircleCI: Cloud-based with fast parallel builds.
- Travis CI: Simple YAML-based setup.
- Teamcity

      $git bisect - pinpoint when a bug was introduced.


## 2. Continuous Deployment (CD)

CD automates deploying code to production after passing all tests.

### Popular CD Tools:

- ArgoCD – GitOps-based CD for Kubernetes.
- Spinnaker – Multi-cloud deployment automation.
- FluxCD – Kubernetes-native CD.



----------------------------------------------

# Minimum Viable Product(MVP).

- An MVP is a version of a new product that includes only the essential features necessary to meet the needs of early adopters. 

- It allows teams to test their ideas in the market with minimal resources and gather feedback for further development. 

- Using an MVP approach helps in validating concepts and reducing the risk of developing a product that does not meet market demands. 

- It allows teams to test their ideas in the market with minimal resources and gather feedback for further development.





-------------------------------------------

# Debugging.

Debugging is the process of finding and fixing bugs.

### Best Debugging practices

✔ Combine AI with traditional debugging techniques for better accuracy.

✔ Train AI models with project-specific data to improve bug detection.

✔ Use AI-driven logging tools to catch issues in real time.




### Debugging Techniques

Print Statements – Logging values to track issues.

Breakpoints – Using IDEs (like VS Code, IntelliJ) to pause execution.

Code Reviews – Collaborating with team members to find mistakes.

Static Code Analysis – Tools like SonarQube, ESLint, Pylint to detect issues.


Common Debugging Tools:

GDB – For C/C++ debugging.

Chrome DevTools – For debugging JavaScript and web apps.



AI-driven debugging 
Is the future of software testing, leveraging AI to detect, analyze, and fix bugs efficiently.
This reduces manual debugging time and improves software reliability.

How AI-Driven Debugging Works

1. Automated Bug Detection
2. Anomaly Detection
3. Code Suggestion & Auto-Fixing
4. Predictive Analysis
5. Natural Language Debugging



Popular AI Debugging Tools.

1. AI Code Review & Static Analysis

- DeepCode (Snyk).
- Codacy.
- SonarQube.


2. AI-Powered Debugging Assistants

- Copilot (GitHub).
- Tabnine.
- CodeWhisperer (AWS).


3. AI for Runtime Debugging & Log Analysis

- Datadog AI Logs
- Splunk AI
- TensorFlow Debugger.


4. AI-Powered Automated Testing & Debugging

- https://testim.io
- Applitools.
- Diffblue Cover 


----------------------------------------------

# Resources

Books

Videos







