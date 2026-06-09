# Spring MVC JSP Demo

A simple Spring MVC web application built using Java, Spring MVC, Maven, and JSP.

## Features

- Spring MVC Controller
- Request Mapping
- JSP View Rendering
- Model Attribute Binding
- Server-Side Rendering (SSR)
- Maven Project Structure

## Technologies Used

- Java
- Spring MVC
- JSP
- Maven
- Apache Tomcat

## Project Structure

```text
src/main
├── java
│   └── com/rudra/demo/controller
├── resources
├── webapp
│       └── views
│           └── home.jsp
```

## How It Works

1. User enters a URL in the browser.
2. Spring MVC Controller receives the request.
3. Controller processes the request and sends data to the view.
4. JSP renders the dynamic content.
5. HTML is returned to the browser.

## Example

```java
@Controller
public class AlienController {

    @RequestMapping("/home")
    public String home() {
        return "home";
    }
}
