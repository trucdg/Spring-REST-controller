# 🍖 Spring REST Controller
There are mainly 2 controllers are used in the Spring: controller (`@controller`) and RestController (`@restcontroller`).
- The main difference between the `@restcontroller` and the `@controller` is that the `@restcontroller` = `@controller` + `@ResponseBody`

>**RestController**: Rest Controller is used for making restful web services with the help of @RestController annotation. This annotation is used at the class level and allows the class to handle the requests made by the client. The RestController allows to handle all REST APIs such as GET, POST, PUT and DELETE requests.

## Step by Step Implementation
1. Go to [Spring Initializr](https://start.spring.io/) and download the starter file
2. Go to src > main > java > com.luv2code.Spring.boot.app
