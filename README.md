# springboot-primeng-datatable-lazyload

### Description
This project demonstrate how to use PrimeNG Datatable lazy load functionality with spring jdbctemplate.
Project comes with inmemory H2 db. You can find the scripts in "backend/src/main/resources/sql" folder.
This project demonstrate how to use server side, sorting, filtering and pagination using spring jdbcTemplate
and PrimeNG Dataload


### Instruction
1. Run ```npm install ``` inside frontend folder
2. Run ``` ng serve ``` inside frontend folder
3. Deploy backend war in tomcat or anyother servlet container. Frontend is expecting backend available on port 9999.
   If you have different port for backend then please update frontend service to use correct url to get data from abckend.
   
Note : If you get error "No Error" when you run ng serve then please run the following command inside "frontend" folder and then run "ng server"
and that should resolve the issue.

```npm install extract-text-webpack-plugin@2.0.0-rc.0 --save-dev```

To access embedded db console, use following url

```http://localhost:8082/```

Tested on tomcat 8.5.16 ( it is a war file based app )\

From: https://github.com/pritspatel
