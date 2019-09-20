# vue

1. 打包

env="test prod"

常见的错误 Error: EACCES: permission denied, mkdir '/data/workspace/html/aibuduo_app_h5/node_modules/node-sass/vendor

解决办法

npm install --unsafe-perm=true --allow-root   

npm run build:$env
