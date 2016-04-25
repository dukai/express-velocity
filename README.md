# express velocity engine
A velocity template engine wrapper for express
```` javascript
var engines = require('express-velocity-engine');

app.set('views', 'src/vm');
app.set('view engine', 'vm');
app.engine('vm', engines.vm);
````
