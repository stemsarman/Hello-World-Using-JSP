# Hello_World_Using_JSP

**prerequisite**
*You need to download and install the Apache tomcat web server*

1. To run your first JSP project you need to first install EclipseEE IDE.
2. After installation, create a *Dynamic web project*
3. Give appropriate name for your project (a directory structure will be created)
4. *Navigate to `src->main->webapp`*
5. Right click on the webapp folder and create a new JSP file, named `index.jsp`
6. Copy and Paste the below code in the `index.jsp` file.

``` <%@ page language="java" contentType="text/html; charset=ISO-8859-1"
    pageEncoding="ISO-8859-1"%>
<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>My First Web-App</title>
</head>
<body>
<h1>Hello JSP World!</h1>
</body>
</html>
```

7. Right click the project on the left hand side in the project explorer window and go to **run as** option.
8. Select the **run of server** option and click **finish**
(Your JSP project will start running in a new browser window)
