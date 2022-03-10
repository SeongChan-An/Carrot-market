# 학습내용

## DataBase Setup

> [Prisma](./Note_Prisma.md)

> [PlanetScale](./Note_PlanetScale.md)

### 주의사항 ?

PlanetScale은 [vitess](https://vitess.io/)를 사용하는 MySQL과 호환되는 DB 플랫폼으로 MySQL의 기능에서 지원하지 않는 것이 있다.

- example
  - Foreign Key Constraints (외래키 제약)
    - vitess 는 외래키가 없더라도 에러가 발생하지 않음
    - [referentialIntegrity](https://www.prisma.io/docs/concepts/components/prisma-schema/relations/referential-integrity)를 이용하여 보완

### Step

- Install Prisma
- define schema
- install PlanetScale
- connect project "pscale connect project" for using secure tunnel (change URL in .env)
- push "yarn prisma db push"

### Util

- yarn prisma studio  
  admin page : you can add record
