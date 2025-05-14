
# Ejecutando Static

```bash
# Clone this repository
git clone https://github.com/rsalgadoc/introduction-to-nodejs-lfw111x.git
```

```bash
npm install
```
 If you have issues, To address all issues, run:
```bash
npm audit fix
```


```bash
# El parametro static se refiere a una carpeta, en este caso a static
npx serve -p 5050 static
```
OR

```bash
# Esta es otra forma de iniciar el servidor, 
npm run static
```

Serving! : 
Local:    http://localhost:5050 


# Ejecutando mock-srv

```bash
cd mock-srv
```

```bash
npm install
```

 If you have issues, To address all issues, run:
```bash
npm audit fix
```

```bash
npm start
```

El output sera lo siguiente:

> mock-srv@1.0.0 start
> fastify start -l info app.js

{"level":30,"time":1747193833021,"pid":10992,"hostname":"DESKTOP-HJHLDQ3","msg":"Server listening at http://[::1]:3000"}
{"level":30,"time":1747193833026,"pid":10992,"hostname":"DESKTOP-HJHLDQ3","msg":"Server listening at http://127.0.0.1:3000"}

# Command Line Tool my-cli


```bash
cd my-cli
```

```bash
npm install
```

```bash
npm link
```

```bash
my-cli
```

Usage: my-cli [options] [command]

Back office for My App

Options:
  -V, --version                                            output the version number
  -i, --interactive                                        Run App in interactive mode
  -h, --help                                               display help for command

Commands:
  update [options] [ID] [AMOUNT]                           Update an order
  add [options] [CATEGORY] [ID] [NAME] [AMOUNT] [INFO...]  Add Product by ID to a Category
  list [options] [CATEGORY]                                List categories


  Otros ejemplos:

```bash
my-cli -i
```

```bash
my-cli list all
```