# graphql-ex
GraphQL Sample Project

# 개발환경
- node.js v12
- yarn v1.21
- MongoDB v4.2.2

## Optional
- Docker v19.03.5

# 실행방법
1. 저장소 Clone
2. 저장소 안에서 의존성 설치
   ```bash
   $ yarn

   # or you can use npm
   $ npm i
   ```
3. MongoDB 설치
   - [MongoDB Community Edition Page](https://docs.mongodb.com/manual/administration/install-community/)
   - or Use Docker
      ```bash
      docker container run -itd --name gql_mongo -p 27017:27017 mongo:4.2.2
      ```

3. 실행
   ```bash
   $ yarn serve

   # or you can use npm
   $ npm run serve
   ```


##### 
study doc link
https://docs.google.com/presentation/d/1hnEzv-Me8ynmA8vIHcwpgOK6D9UGWwfgH3S-ZRVAxkk/edit?fbclid=IwAR27UajLHAUt-isCut4_aGzGRpuhHTOt5L7DumEo0egzqUU5Jqg38mJsnaA
