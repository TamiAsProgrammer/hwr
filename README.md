
tips
----

### .md file
> .md file --> for 'markdown.syntax'

#### table

column1 | column2 
---|---
c1 | c2
c3 | c4

#### list
- list1
- list2
    - list2.1
    - list 2.2
        - list 2.2.1
        - list 2.2.2

This is a *italic*.  
This is a **Bold**.  
This is a baidu.com   
This is a [baidu](baidu.com)


Hack with React.js   
==================
C1.
----
1. create an empty project
~~~sh
cd Desktop
mkdir hwr
cd hwr
npm init -y
~~~

~~~sh
echo "# hwr" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/TamiAsProgrammer/hwr.git
git push -u origin master
~~~

~~~sh
npm install --save-dev webpack webpack-dev-server react-hot-loader
npm install --save-dev babel-core babel-loader
npm install --save-dev babel-preset-es2015 babel-preset-react
npm install --save react react-dom history react-router
~~~

webpack-dev-server
./node_modules/.bin/webpack