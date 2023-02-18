#                                                         Spring cloud Microservices and Angular front-end
![logoreadme](https://user-images.githubusercontent.com/55364638/206926865-496024be-f97d-44d8-af78-c3fa4c4d2e9f.png)
# I. Backend :
  * [1. use case](#1-use-case)
  * [2 Inventory service - get all products](#2-inventory-service---get-all-products)
  * [3 Inventory service - get product by ID](#3-inventory-service---get-product-by-id)
  * [4 Customer Service - get All Customers](#4-customer-service---get-all-customers)
  * [5 Customer Service - get Customer by ID](#5-customer-service---get-customer-by-id)
  * [6 Bill Service - get bills](#6-bill-service---get-bills)
  * [7 Bill Service - get bill by id](#7-bill-service---get-bill-by-id)
  * [8 Eureka Service](#8-eureka-service)
# II. Frontend Angular Client :
  * [Login screen](#login-screen)
  ## Products
  * [1 Show all products](#1-show-all-products)
  * [2 Edit products](#2-edit-products)
  * [3 Delete products](#3-delete-products)
  * [4 Search for a product](#4-search-for-a-product)
  * [5 New Product](#5-new-product)
  ## Customers
  * [1 Show all customer](#1-show-all-customer)
  * [2 Edit Customer](#2-edit-customer)
  * [3 Delete Customer](#3-delete-customer)
  * [4 Search Customer](#4-search-customer)
  * [5 New Customer](#5-new-customer)
  ## Bills
  * [Show Bills](#show-bills)
# III. KEYCLOAK
  * [1 Realm](#1-realm)
  * [2 Client](#2-client)
  * [3 Utilisateurs](#3-users)
  * [4 Rôles](#4-roles)
  * [5 Tokens](#4-tokens)
  * [6 Service sécurisé](#5-Service-sécurisé)
# IV. KAFKA :
  * [1 Supplier](#1-supplier)
  * [2 Consumer](#2-Consumer)
  * [3 Kafka streams ](#3-Kafka-streams )


# V. DOCKER :
# I. Backend :
## 1. use case

![image](https://user-images.githubusercontent.com/62290643/206123723-0f5d7345-b23d-4ecb-84cb-83346104a73d.png)

## 2 Inventory service - get all products
```http
GET /localhost:8888/PRODUCT-SERVICE/products
```

![image](https://user-images.githubusercontent.com/55364638/206927699-da2bd3b9-7d1c-4ca3-837e-c9564a826ede.png)



## 3 Inventory service - get product by ID 
```http
GET /localhost:8888/PRODUCT-SERVICE/products/{id}
```

![image](https://user-images.githubusercontent.com/101510983/206922542-ff3bc375-78ba-4956-92f4-0cc57ac762b8.png)



## 4 Customer Service - get All Customers
```http
GET /localhost:8888/CUSTOMER-SERVICE/customers
```

![image](https://user-images.githubusercontent.com/101510983/206921889-6f2333f5-b2ac-4d27-839b-c0989720c140.png)


## 5 Customer Service - get Customer by ID
```http
GET /localhost:8888/CUSTOMER-SERVICE/customers/{id}
```

![image](https://user-images.githubusercontent.com/101510983/206922673-eb757211-bc70-4d62-a1c2-8248050f3133.png)


## 6 Bill Service - get bills
```http
GET /localhost:8888/BILLING-SERVICE/fullbills
```

![image](https://user-images.githubusercontent.com/101510983/206922042-3f83dfcb-cb8e-4227-ae03-b5013cbf62f5.png)


## 7 Bill Service - get bill by id
```http
GET /localhost:8888/BILLING-SERVICE/fullbills/{id}
```

![image](https://user-images.githubusercontent.com/101510983/206922866-21e9873d-ca97-4434-8cf6-57dfcaadc571.png)


## 8 Eureka Service 
```http
GET /localhost:8761/
```

![image](https://user-images.githubusercontent.com/101510983/206922145-5a50d39f-704c-4ca9-a1cc-ed65cbd20569.png)

# II. Frontend Angular Client :
## Login screen 

![image](https://user-images.githubusercontent.com/101510983/206923607-8e842b94-d208-4dc6-8cbe-fb68db9037ec.png)

## Products
## 1 Show all products 

![image](https://user-images.githubusercontent.com/55364638/206925608-0b8e8b90-f8cf-45af-987a-550ffeb810e3.png)

## 2 Edit products 

![image](https://user-images.githubusercontent.com/101510983/206923795-26a19423-e941-4acd-878e-8a0ce1e3df11.png)

## 3 Delete products 

![image](https://user-images.githubusercontent.com/55364638/206925748-42a715d1-4713-45a3-889a-ccb3ca042ca5.png)

![image](https://user-images.githubusercontent.com/55364638/206925764-23a250e5-8a39-4293-b96c-575a22dfe68b.png)


## 4 Search for a product

![image](https://user-images.githubusercontent.com/55364638/206925802-0b184999-ccb0-4a54-9fc9-dcf419205f83.png)


## 5 New Product

![image](https://user-images.githubusercontent.com/55364638/206925875-db2771c4-e4b0-4970-8f5d-e7c699a9b4ee.png)

![image](https://user-images.githubusercontent.com/55364638/206925899-ebcd1e02-dfbe-43f0-b0ca-e52d264c84a9.png)

## Products
## 1 Show all customer

![image](https://user-images.githubusercontent.com/55364638/206925644-39d57c48-dd68-4d57-a563-a76e20dabe65.png)



## 2 Edit Customer

![image](https://user-images.githubusercontent.com/101510983/206924228-151e1ed2-e1d6-406d-8849-34da1dc34937.png)


## 3 Delete Customer 

![image](https://user-images.githubusercontent.com/55364638/206926221-6b3c8033-4f51-420a-89eb-9634b8322d2b.png)



## 4 Search Customer 

![image](https://user-images.githubusercontent.com/55364638/206926003-7e101bb2-764a-4083-8270-739fa6e95709.png)



## 5 New Customer 

![image](https://user-images.githubusercontent.com/55364638/206925953-153464e1-a35e-470b-ad44-9cf09874aa25.png)


![image](https://user-images.githubusercontent.com/55364638/206925982-3003c687-4601-4ee2-b88c-f0b2b58dcf3e.png)


## Bills
## Show Bills  

![image](https://user-images.githubusercontent.com/55364638/206925572-719bdaa5-0195-46e8-b4e2-7a190a300df9.png)

# III. KEYCLOAK :
```To start Keycloak
> ...\bin\standalone.bat
```

## 1. REALM

![image](https://user-images.githubusercontent.com/73041687/219620750-5378152e-a955-45e1-9bd2-699374405d80.png)

## 2. CLIENT

![image](https://user-images.githubusercontent.com/73041687/219620904-dd7f3c62-636a-41c8-b327-106fa3cf47cc.png)

## 3. USERS

![image](https://user-images.githubusercontent.com/73041687/219620974-3fa8bea4-4be1-43c3-9b89-44841369e2f7.png)

## 4. ROLES
![image](https://user-images.githubusercontent.com/73041687/219621061-6890af29-2d3e-44c1-890a-02e970ca78b8.png)

![image](https://user-images.githubusercontent.com/73041687/219621157-94bd7359-07d2-48e6-91b5-661348334d60.png)

## 5. TOKENS

![Capture d’écran 2023-02-09 173815](https://user-images.githubusercontent.com/73041687/219621277-d957395c-559d-402a-a06a-232e1109cccf.jpg)

![Capture d’écran 2023-02-09 173750](https://user-images.githubusercontent.com/73041687/219621287-ef639e50-0db2-4a9c-a805-6510b070b746.jpg)

## 6. Service sécurisé

![image](https://user-images.githubusercontent.com/73041687/219621563-7e6a5211-68be-44be-b764-45867cf51713.png)


# IV. KAFKA :
## 1. SUPPLIER

![image](https://user-images.githubusercontent.com/73041687/219654966-8ed99356-f63b-449b-b782-480121de32f6.png)

![image](https://user-images.githubusercontent.com/73041687/219687628-a8c20cbe-a87a-4375-9636-b932406c01ac.png)


## 2. CONSUMER

![image](https://user-images.githubusercontent.com/73041687/219677290-25fc52df-3a92-4a65-8e3e-dbf559b2f1de.png)

## 3. KAFKA STREAMS 

![image](https://user-images.githubusercontent.com/73041687/219668084-72ac27e1-849e-4fe5-bec0-9eb63685b965.png)



# V. DOCKER :

## BILLING-SERVICE 
![image](https://user-images.githubusercontent.com/73041687/219697077-feed41f4-1a89-45e8-9206-19451d6dc80a.png)
## INVENTORY-SERVICE
![image](https://user-images.githubusercontent.com/73041687/219698461-5131e970-68b0-4978-a159-a0c628cdb856.png)

![image](https://user-images.githubusercontent.com/73041687/219706814-b5b679ad-30b0-4848-a57c-743ddd0b2798.png)
## CUSTOMER-SERVICE
![1](https://user-images.githubusercontent.com/84048380/219879470-280f20b5-64ba-40ef-b1d1-efbcf85222ba.png)
## GATEWAY-SERVICE
![2](https://user-images.githubusercontent.com/84048380/219879477-5aabf372-83ce-425f-91ce-1b7229f4e183.png)
## EUREKA-DISCOVERY
![3](https://user-images.githubusercontent.com/84048380/219879489-cf5be4ef-21dd-4591-a6fe-729d264c99bc.png)
## FRONTEND
![4](https://user-images.githubusercontent.com/84048380/219879497-61682b3a-19cc-4aba-b753-9088da73a10e.png)

