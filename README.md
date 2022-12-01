# spring-boot-github-login

Starter Reactive Spring Boot project for OAuth login with GitHub

Simple starter for a Spring Boot Webflux application with GitHub OAuth support.

Steps:
1. Create a GitHub App and get the Client ID and Client Secret values.
2. Add those values in application.yml
3. Run the Spring Boot App. You should be able to login with GitHub

This is a super minimal app. Post login, you will be redirected back to the login page, but you can validate the authorized principal is created by accessing the /user API.
