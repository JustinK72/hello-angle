# heroku-sudoku (charles version)

[Herokuapp Link](https://knight-charlie-murphey.herokuapp.com/)

Angular - a framework that is asyncronous with the code. It would be in constant communication/saving with the client and server. When the user inputs data into the form it is automatically updated. 
``` js
app.get('/file', function(req, res) {

    fs.readFile('demofile1.html', function(err, data) {
        res.writeHead(200, { 'Content-Type': 'text/html' });
        res.write(data);
        return res.end();
    });

    fs.appendFile('demofile1.html', 'Hello Neighboor!', function(err) {
        if (err) throw err;
        console.log('Saved!');
    });
});
```
The code above will act as both read and write function. You create a html file and replace the *demofile1.html* with the name of your created html. To replace *hello neightbor* with whatever text you want so it will output to the file.
