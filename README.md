Fake News(Express Api with React Client)

Install Dependencies on Server and Client

The project is configured to run with yarn if you don't have it installed on your system run:

```
npm install -g yarn
if(you don't want to install yarn go to the package.json file and change the yarn command's for npm)
```

```
server: npm install or yarn install
client: yarn install:client or npm run install:client
```

Start Server

```
- Server will start on port: 5000
yarn start or npm start (**The server will start using nodemon)
```

Start Server and Client

```
yarn dev or npm run dev
```

Endpoints

HTTP METHOD GET:

```
- localhost:5000/api/fakesites = will return array of fakeNEWS websites.
- localhost:5000/api/fakesites/articles/:id = will return articles from the corresponding news site.
- localhost:5000/api/fakesites/category/:category = will return array of sites according to the url parameter category:

Errors
if(!id )return error message and 400 status code.
if(!category )return error message and 400 status code.


```

Fake Sites JSON Template is from [aligajani/fake-news-detector](https://github.com/aligajani/fake-news-detector)
