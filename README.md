# mern_product_manager_part_one_practice

- [ ] Create your MERN stack folder structure

```bash
touch server.js .env 
npm init -y
mkdir server
```

```bash
npm i cors dotenv express nodemon mongoose
```
```bash
npx create-react-app client
```

- [ ] Create your server, model, controller, routes, and config files for your server
- 
```bash
mkdir server/config server/controllers server/models server/routes
```

```bash
touch server/config/mongoose.config.js
touch server/controllers/product.controller.js
touch server/models/product.model.js
touch server/routes/product.routes.js

```

- [ ] On the client end ==> Create a form component so that your Product can have a title, price and description

- [ ] Check in your database that your products are being added