# sample-jsp-servlet-thread
In the context of JSP and Servlets, the "thread description" refers to how the web container (like Apache Tomcat) manages concurrent requests to a servlet or JSP.
When a client sends an HTTP request to a servlet or a JSP (which is translated into a servlet at runtime), the web container typically handles this request by:
Creating a new thread:
For each incoming HTTP request, the servlet container spawns a new thread. This thread is dedicated to processing that specific request.
