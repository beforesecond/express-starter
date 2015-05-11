# Express Starter

- use express 4.*
- use jade
- use mongoose
- use config.json
- use session
- use bluebird for promise/A+ 
- use mocha for test
- add startmongodb.sh && start.sh
- add pm2 for deploy
- use supervisor for live reload


## pm2 tips


启动项目

    sudo pm2 start app.js -i max --name 'express-starter'


查看状态

    sudo pm2 status


停止所有

    sudo pm2 stop all
    
    