# NodeCMS / BZBeelder BE
NodeJS / MongoDB based blogging platform API

## Prepare to work
You will need MongoDB database. 

Configuration sample:
```
module.exports = {
  theme: 'fedojo/',
  mongo: '<MONGO_URL>',
  secret: '<YOUR_SECRET>',
  publicPath: 'public/'
};
```

## Purposes / main ideas
1. NodeCMS platform for blogging 
2. PUG based templating

## FrontEnd
https://github.com/fedojo/bzbeelder-fe

## Links
http://fedojo.com


## Testing
1. Testing :
```
npm run test
```

2. Coverage:
```
npm run coverage
```

3. Testing with code coverage:
```
npm run testfull
```
