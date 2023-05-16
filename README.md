# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11


# CMPE 172 - Lab #10 DevOps CI/CD 
<h2>Part1: CI Workflow</h2>
- Building and testing Java with Gradle<br>
<img width="1512" alt="Screenshot 2023-05-15 at 10 35 59 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/f5022d49-b1d1-4bde-8ac9-a4fd49ae8554">
<img width="1512" alt="Screenshot 2023-05-15 at 10 28 40 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/d38de3d4-3bda-4cf8-9be4-ec99753bb556">

- github/workflows/gradle.yml
<img width="1512" alt="Screenshot 2023-05-15 at 10 36 22 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/d1ee3c11-7a7d-4c1a-9c29-a674ce7d9974">

- github/workflows/google.yml
<img width="1512" alt="Screenshot 2023-05-15 at 10 36 15 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/508a1f0c-f179-4b6d-b064-8b9d2b7ca110">

<br><br>
- Set up your workflow to trigger on push and pr on main branch and optionally upload build artifact (i.e. jar file).
<img width="1512" alt="Screenshot 2023-05-15 at 10 28 31 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/9be0ecd8-2a3e-47f8-b6b9-bed235ef87f4">



<h2>Part2: CD Workflow</h2>
<img width="1512" alt="Screenshot 2023-05-15 at 11 01 31 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/32919f03-8f79-4133-ae1a-cf7b92489de0">
<img width="1512" alt="Screenshot 2023-05-15 at 11 01 35 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/41f25e64-dff3-4936-9e3c-d391902bde2f">
<img width="1512" alt="Screenshot 2023-05-15 at 11 02 03 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/0e8b7221-c0c5-4d67-96f8-0de0b1446db2">
<img width="1512" alt="Screenshot 2023-05-15 at 11 04 07 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/275a3e98-179b-4362-b5a7-9a926b8c692c">
<img width="1512" alt="Screenshot 2023-05-15 at 11 08 29 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/e66664b0-d9da-4060-9270-af3056070918">
<img width="1512" alt="Screenshot 2023-05-15 at 11 08 53 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/eb1c97fd-0b52-468f-bfaa-e675e98f1770">

<br><br>
- In github secret, add repo
<img width="1512" alt="Screenshot 2023-05-15 at 11 12 08 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/e8ef78c6-8d50-4ad3-8a15-d6a3a760e487">
<img width="1512" alt="Screenshot 2023-05-15 at 11 12 35 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/e8b5e3d5-38dd-40a0-999c-ddcd797f2fee">
<img width="1512" alt="Screenshot 2023-05-15 at 11 12 35 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/a79b0f4c-aaa3-4fde-8d5d-320d0cfc67cb">

<img width="1512" alt="Screenshot 2023-05-15 at 11 19 08 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/e50d691f-c380-422e-98c4-711365bb473e">
<img width="1512" alt="Screenshot 2023-05-15 at 11 20 38 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/75ad8c35-593c-453d-9851-ab995cda5926">
<img width="1512" alt="Screenshot 2023-05-15 at 11 20 59 PM" src="https://github.com/jj904/spring-gumball/assets/57935131/835e5007-e6ff-47e6-b0e8-d83e19b8c221">


