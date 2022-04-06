#Integration continue testing with APIPLATFORM

### 1st step  
Creation of symfony environment with maker bundle and api 
Activation of sqlite with .env then creation of database with command
Creation of 2 entities User and Department
Migration migrate the database
(tips : be careful with php.ini, be sure required extensions are activated)  

### 2nd step  
Settings of entity files by adding dependence injection for ApiRessource. See files  
Checks if functionnal by running server  

### 3rd step  
Installation of JWT bundle  
https://github.com/lexik/LexikJWTAuthenticationBundle/blob/2.x/Resources/doc/index.md#getting-started  


