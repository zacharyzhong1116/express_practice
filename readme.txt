express framework for node.js practice based on youtube tutorial
youtube link : https://www.youtube.com/watch?v=k_0ZzvHbNBQ&index=1&list=PLillGF-RfqbYRpji8t4SxUkMxfowG4Kqp


A:the difference between let var const:
    https://www.zhihu.com/question/52662013
1. create  app folder: express_practice and walk in

2. npm init
    ---->  creating a package.json file

    2.1 under the script:
        http://www.ruanyifeng.com/blog/2016/10/npm_scripts.html
        when you run : npm start
        it will run the command defined with start
        you can also create command as you want

3. npm install --save express
    ----> create the node_modules(see the changes in package.json)

4. npm install --save pug
    ----> use pug (see the changes in package.json)
    tutorial :https://www.cnblogs.com/xiaohuochai/p/7222227.html

5. sudp npm install -g nodemon
    -----> to debug the nodejs
    nodemon  ----->start nodemon

6. use mongodb
    6.1 in terminal:
        6.1.1 mongod   ---->start the mongodb
        6.1.2 in new terminal window
            mongo      ----> to use mongodb

        6.1.3   use nodedb    ---->create a datebase names nodedb
           and insert the data you want

    6.2 npm install --save mongoose
7. npm install --save body-parser
    ---->use body-parser to parse the content in post-form
    https://github.com/expressjs/body-parser
    before express body-parser is included.
8. npm install -g bower
    ---->use bower in install bootstrap

    8.1 bower install bootstrap
        to make the looks more better







