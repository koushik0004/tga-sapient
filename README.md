# Sapient TGA

## Required details for development
` CODE COMMIT REPO : https://del.tools.publicis.sapient.com/bitbucket/projects/XTTRAIN/repos/142937-koushik-sadhukhan/browse`

## TGA session repo by Rajesh
` https://gitlab.com/sapient-tga-training-july-2019 `
` https://gitlab.com/sapient-tga-training-july-2019/training-content/tree/master/session10 `

## Required bogs
` https://www.lucidchart.com/documents/view/703f6119-4838-4bbb-bc7e-be2fb75e89e5/dTP8IH8l1hxc `
` Vinci - https://medium.com/@areai51/architect-vs-a-town-planner-87be3525de16 `
` Docker is very simple - https://www.youtube.com/watch?v=_dfLOzuIg2o&t=259s `
` Docker and container - https://www.youtube.com/watch?v=JSLpG_spOBM `

## Useful git Repo
` Microfrontend - https://github.com/xt/nitro2`

## Useful Tools
` Online practice - https://www.katacoda.com/courses/docker `
` https://www.katacoda.com/courses/container-runtimes `
` Docker Play Ground - https://labs.play-with-docker.com/ `

## Build using Docker
` docker build -t xt/nitro2 .`

` docker run -p 3000:3000 xt/nitro2` 

## Node PM2

`
pm2 commands:
1. sudo npm install -g pm2
2. sudo npm install -g pm2-server-monit
3. sudo npm i -g loadtest
4. pm2 start simple-session.js -i max
5. pm2 logs
6. pm2 logs --lines 200
7. pm2 logs simple-session
8. loadtest -c 20 -n 5000 http://localhost:3000/info
9. pm2 reload all
10. pm2 kill
11. pm2 link y0b1fxg8sbsm7u4 kodpahu0p7pkenq WKMIN0896083

`

## steps to Build Locally & run

`yarn`

`yarn install:apps`

`yarn build:apps`

`yarn start`

on the browser `http://localhost:3000/home`

## Contributors