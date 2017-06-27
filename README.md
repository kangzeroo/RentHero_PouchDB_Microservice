### PouchDB ###

# To start process (option A - recommended) <br />
$ pouchdb-server --port 5984 --dir ./db & <br />

# To start process (option B) <br />
$ npm run dev

# To kill process <br />
$ sudo lsof -PiTCP -sTCP:LISTEN <br />
$ kill < PID > <br />
