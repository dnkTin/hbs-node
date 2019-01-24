```
app.set('view engine', 'hbs');
app.use(express.static(__dirname + '/public'));
```
using this -> nodejs will find file in public folder to render file

app.use -> middle ware
