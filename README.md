chapter1:

el表达式会失效
需要在jap页面添加:
```
<%@ page contentType="text/html;charset=UTF-8" language="java" isELIgnored="false" %>
```