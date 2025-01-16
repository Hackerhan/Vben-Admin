Vben-Admin has a hard-coded vulnerability
Vue Vben Admin is a free and open source mid-end and back-end template. Developed using the latest mainstream technologies such as vue3, vite, and TypeScript, the out-of-the-box mid-end and front-end solutions are also available for learning reference. Vue Vben has a hard-coded vulnerability
fofa
icon_hash="-317536629"
poc
Login page, right-click to view source code, search for index, and enter the js page

The page hard-codes the login account and password

Log in to the system using the account and password

System case
1.http://47.106.143.205/#/login,
View the source code to find the js file of index

Find the account and password written in js and log in successfully

2. https://8.138.99.143/#/login,
View the source code to find the js file of index

Find the account and password written in js and log in successfully

3.http://129.211.8.84:8081/,
View the source code to find the js file of index

Find the account and password written in js and log in successfully

The following are other cases, or batch verification through fofa syntax icon_hash="-317536629"

http://110.4 0.156.247:8002/#/login http://1.116.143.20:9003/#/login, http://8.149.134.55:5858/, http://159.75.230.122:8083/, http://1.94.99.40:8080/#/login, https://182.132.20.172:9443/, https://121.41.178.204:80/
