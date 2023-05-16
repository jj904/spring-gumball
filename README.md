# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11


# CMPE 172 - Lab #10 DevOps CI/CD 
<h2>Part1 CI Workflow</h2>
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



