# Week 9

## Monday

### Happy Hour ideas

- VR
  - Downtown Disney
  - Twobit Circus
- BARcade 🍺 👾
  - 82
- Laser tag/paintball
  - Hollywood Sports Park
- Escape room
- Paint Wine
- Color Me Mine
- Gokarting
- Picnic
  - Dockweiler
- Water sports/beach day
- Six Flags
- Karoke Bar
- KBBQ

### GTOD

- redo specific questions from the video?
- Codeview link?

### Interview questions

## Tuesday

### MongoDB

![mongoDB logo](https://webassets.mongodb.com/_com_assets/cms/MongoDB-Logo-5c3a7405a85675366beb3a5ec4c032348c390b3f142f5e6dddf1d78e2df5cb5c.png)

- **Open source**
- **Document-oriented**: fields can vary from document to document and data structure can be changed over time
- **NoSQL** database
- **JSON**-like documents with schemata

There are a few tools JavaScript developers like to use with MongoDB:

- **MongoDB**: the actual database software
- **Atlas**: cloud database (managed hardware with managed software installed)
- **Compass**: GUI for interacting with db
- **Mongoose**: object modeling for node.js (npm package)

#### Mongoose

> Mongoose provides a straight-forward, schema-based solution to model your application data.
> It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.

Some terms to understand:

- Schema: the blueprint for your data objects
  > Each schema maps to a MongoDB collection and defines the shape of the documents within that collection
- Model: compiled Schema used to actually interact with the DB
  > Models are responsible for creating and reading documents from the underlying MongoDB database
- Queries: requests to read and modify the DB (**Careful!** They look/act a lot like Promises but they're not quite)

1. register for mongoDB Atlas
   1. create cluster
   2. add new user: root qD3Q5rLgP0SszhsS
   3. whitelist your ip
2. download compass
3. Let's go work in server of express-codealong
4. `npm i mongoose`
5. make url (put sensitive info in `.env`)
6. `mongoose.connect`
7. make Comment model
   1. Schema (like the blueprint for your data) and Schema types
   2. model
   3. export
8. use model in router
9. Comment.find to get all
   1. filter with `where` and `regex` with [chaining](https://mongoosejs.com/docs/api.html#Query)
10. create a document with `save`
