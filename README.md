# Run #  
```
docker-compose -f "docker-compose.yml" up -d --build  
```  

## curl --location --request GET 'http://localhost:8800/c25_flushLogLevel1_BTREE.jpg' ##  
![C10](screens/request_1.jpg "first request")
![C10](screens/request_2.jpg "second request")
![C10](screens/request_3.jpg "third request")  

## curl --location --request PURGE 'http://localhost:8800/c25_flushLogLevel1_BTREE.jpg' ##  
![C10](screens/request_purge.jpg "purge cache")  

## curl --location --request GET 'http://localhost:8800/c25_flushLogLevel1_BTREE.jpg' ##  
![C10](screens/request_after_purge.jpg "after purge")  
