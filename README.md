# Pconsole-js

Mini lightweight console color logger.

## Installation
```
npm i pconsole-js --save

```

## Usuage
```javascript
const con=new Pconsole

con.colorRed="color:red;"
con.log(`$<colorRed>Hello World`)

con.colorBlue="color:blue;"
con.log(`$<colorBlue>My color is blue`)

con.myStyleCss="background:yellow;color:green;"
con.log(`$<myStyleCss>you can put all valid css styles`)

const myLog=con.getlog(`$<colorRed>you can get the log and view it later`)
console.log(...myLog)

```
## License
