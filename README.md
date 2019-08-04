 # Seapay

 ## Description
 
Seapay is a fintech app consists of 4 different services
  - API gateway
    - API gateway service routes all requests to other services
  - User account
    - User account service takes care of user management: user creation, get user data, etc
  - Wallet
    - Wallet service handles all wallet functionalities: update balance, get balance, create wallet, etc
  - Transaction
    - Transaction service manage all transaction data

The project itself has 4 modules
 - seapay-api
   - a module that abstracts interface for all services
 - seapay-common
   - a module that groups all common functionalities used by all services
 - seapay-domain
   - the bussiness logic for all services goes here
 - seapay-monolith
   - an entry point of our monolithic app, including all handlers
  
  ## Installation

  ### Prerequisites
  #### Java >v8
  [Install](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
  #### PostgreSQL v10
  [Install](https://www.postgresql.org/download/)
  
  Install postgres in Ubuntu
  ```
  sudo apt-get install postgresql postgresql-contrib
  ```

  ### How to build from scratch
  ```
  make all
  ```

  ### How to run
  ```
  make run
  ```

  ### How to build
  ```
  make build
  ```

  



