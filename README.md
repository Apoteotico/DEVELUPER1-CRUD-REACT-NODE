npm init -y
 "type": "module",
  "scripts": {
    "start": "node src/index.js",
    "dev": "nodemon src/index.js"
  },
npm i express morgan sequelize pg pg-hstore
npm i nodemon -D
crear:
carpeta src
index.js {
  import app from "./app.js";

  async function main() {
    await sequelize.sync({force: false});
    app.listen(4000);
    console.log("Server on port 4000");
  }

  main();

  }

app.js {

 }



