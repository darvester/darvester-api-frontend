# darvester-api-frontend
<p align="center">
A frontend web application that ties with the darvester-api application to provide easy access to your Darvester database
</p>

### Notice:
Requires the [darvester-api](https://github.com/V3ntus/darvester-api) package.

## Install:
### 1. Clone the repository
```
git clone https://github.com/V3ntus/darvester-api-frontend; cd darvester-api-frontend
```
### 2. Run npm commands
First:
```
nano src/config.js # set your HOST and PORT for the darvester-api
npm i
```
then to deploy:
```
npm run build
npm install -g serve
serve -s build
# listening on :3000
```
or
```
npm start
```

## Demo:
View a demo at [darvester.gladiusso.com](http://darvester.gladiusso.com)
