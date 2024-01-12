# NestJS Monorepo
## Create new monorepo project
```shell
nest new .

# Monorepo
nest generate app cron
nest generate app api
nest generate app callback
nest generate app auth

# Shared modules
nest generate library shared
nest generate module config --project shared
nest generate module database --project shared
```


## Run this project
```shell
git clone https://github.com/KhitrovMaksim/nest-monorepo-starter-kit.git
cd nest-monorepo-starter-kit
nest start
```