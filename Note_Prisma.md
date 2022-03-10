# [Prisma](https://www.prisma.io/)

> Next-generation Node.js and TypeScript ORM

\*\*[ORM(Object Relational Mapping)](https://ko.wikipedia.org/wiki/%EA%B0%9D%EC%B2%B4_%EA%B4%80%EA%B3%84_%EB%A7%A4%ED%95%91)

1. Node.js and Typescript ORM(Object Relational Mapping)
   => JS or TS 와 데이터베이스 사이에 다리를 놓아줌 (기본적으로 번역기 또는 연결해주는 다리 역할)

2. Prisma를 사용하기 위해서는 먼저 Prisma에게 DB가 어떻게 생겼는지, 데이터의 모양을 설명해줘야 한다. => schema.prisma

3. Prisma가 이런 타입에 관한 정보를 알고 있으면 client를 생성해줄 수 있음. client를 이용하면 TS로 DB와 직접 상호작용 가능, 자동완성 제공.

4. Prisma Studio : Visual Database Browser, DB를 위한 관리자 패널같은 것.

## Start

[Doc](https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres)

- yarn add prisma -D
- yarn add @prisma/client
- yarn prisma init  
  create the prisma folder with schema.prisma file and create .env file.
  - basically .env file is pre-setting the DB url so have to change the url according to your project DB. and Also you have to modify the provider in schema.prisma file
  -

## Extension

- [Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma)
