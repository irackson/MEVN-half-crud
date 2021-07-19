# Microposts

> Example of a fullstack app using Vue.js, Express and MongoDB. You will need to edit the MongoDB connection string in server/routes/api/posts.js to your own.

## Quick Start

```bash
# Install dependencies
npm install
cd client && npm install && cd ..

# environmental variables
rename template.env to .env
add your mongo uri to .env

# Start Express Server: http://localhost:5000
npm start

# Start Vue DevServer: http://localhost:8080
cd client
npm run serve

# Build for production (Will build into server/public, ready for deployment)
cd client
npm run build
```

## App Info

### Code originally forked from Brad Traversy

[microposts_fullstack_vue](https://github.com/bradtraversy/microposts_fullstack_vue/tree/c1209c58b46635275fc89c3a2a9ae42bc85db139)

### Version

1.0.0

### License

This project is licensed under the MIT License
