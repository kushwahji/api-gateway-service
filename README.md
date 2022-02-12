# api-gateway-service
api-gateway-service with route redirection and JWT authorization
Api-gateway-service - redirect all microservice service -
  http://www.localhost:2000/Your-Service_Url
  example - localhost:2000/product/?productId=2
Auth-api-gateway-service
  http://www.localhost:1111/Your-Service_Url  
          Header authorization token
  localhost:2000/product/?productId=2
