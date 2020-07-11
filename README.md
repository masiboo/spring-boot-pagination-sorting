# spring-boot-pagination-sorting

In this demo, default page number is 0, page size is 10 and default sort column is ‘id’.

Now invoke these URLs one by one and observe the outputs.

http://localhost:8080/employees?pageSize=5  
http://localhost:8080/employees?pageSize=5&pageNo=1  
http://localhost:8080/employees?pageSize=5&pageNo=2  
http://localhost:8080/employees?pageSize=5&pageNo=1&sortBy=email  
http://localhost:8080/employees?pageSize=5&pageNo=1&sortBy=firstName  

Read more in this blog:-

https://howtodoinjava.com/spring-boot2/pagination-sorting-example/  
