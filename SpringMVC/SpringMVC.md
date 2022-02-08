# Spring MVC 

## Spring MVC Architecture 
- A Java framework used to build web applications. 
- Follows Model-View-Controller (MVC) design pattern. 
- Implements basic features of a core spring framework such as Inversion Control and Dependency Injection.

## Spring Web MVC 
- Model - Contains the data of the aplplication. Can be a single object or collection of objects. 
- Controller - Contains the business logic of an application. @Controller annotation used to mark the class as the controller.
- View - Represents provided information in a particular format. JSP+JSTL used to create a view page. Spring also supports Apache Velocity, Thymeleaf and FreeMarker. 
- Front Controller - The DispatcherServlet class works as the front controller. Responsible to manage the flow of the Spring MVC application.

## Flow of Spring Web MVC
1. All incoming requests is intercepted by the DispatcherServlet (works as the front controller).
2. DispatcherServlet gets an entry of handler mapping from the XML file. Forwars the request to the controller.
3. Controller returns an object of ModelAndView.
4. DispatcherServlet checks the entry of view resolver in the XML file and invokes the specified view component.

## Advantages 
- Separate Roles - Spring MVC separates each role. So model object, controller, view resolver, command object, DispatcherServlet etc. can be fulfilled by a specialised object.
- Light-weight - Uses light-weight servlet container to develop and deploy your application. 
- Easy to test - Generally, Javabeans classes enable the injection of test data using the setter methods. 
- Flexible Mapping - Provides the specific annotation that easily redirect the page. 
- Reusable business code - Rather than creating new objects, it allows us to use the existing business objects.
- Rapid development - Spring MVC facilitates fast and parallel development.

## Inversion of Control and Dependency Injection 
- 

## Spring MVC Beans
- 

# Links 
- https://www.javatpoint.com/spring-mvc-tutorial#:~:text=A%20Spring%20MVC%20is%20a,Inversion%20of%20Control%2C%20Dependency%20Injection.
