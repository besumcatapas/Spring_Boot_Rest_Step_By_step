# Spring_Boot_Rest_Step_By_step
This is the Spring Boot Rest API step by Step for Beginners as well as for Experienced professionals

# Step 1  /*execute first REST API*/
  added in HelloWorldController_1 controller class
  method name :helloWorld
  this is a HTTP get request
  url = http://localhost:2107/helloworld

# Step 2 /*execute REST API with return type as Bean*/
  added in HelloWorldController_1 controller class
  method name :helloWorldBean
  this is a HTTP get request
  url =http://localhost:2107/helloworld-bean
  
# Step 3 /*execute REST API with return type as Bean and take input as path variable */
  added in HelloWorldController_1 controller class
  method name : helloWorldBeanPathVariable
  this is a HTTP get request
  url =http://localhost:2107/helloworld-bean/path-variable/Tapas Pal

# Step 4 /*execute REST API with return type as Bean retrieve all users */
  added in UserResourceController_2 controller class
  new class created: 1. UserResourceController_2, 2.UserBean_2 3. UserDaoService_1 
  method name : retrieveAllUsers
  this is a HTTP get request
  url =http://localhost:2107/users

# Step 5 /*execute REST API with return type as Bean and take input as path variable and return a particular user*/
  added in UserResourceController_2 controller class
  method name : retrieveOneUser
  this is a HTTP get request
  url =http://localhost:2107/user/1

# Step 6 /*execute REST API with HTTP POST request accepting input as USER BEAN*/
  added in UserResourceController_2 controller class
  method name : createUser
  this is a HTTP POST request
  url =http://localhost:2107/users
  body: {
  "name": "Tapas 2",
  "dob": "1987-07-17T07:48:24.725+00:00"
}
------------------------------------------------------------------------------------------------------------------------
  
