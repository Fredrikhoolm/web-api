Setting up react application

1. 'npm init'
2. 'npm install -D parcel@1.12.3 (1.12.4 has a bug)'
3. Add script start '"parcel": "parcel src/client/index.html"'
4. Add index.html
5. 'npm start' => http://localhost.1234
6. Add index.jsx and refrence from indec.html
7. 'npm install -P react react-dom'
8. Restart 'npm start'
9. Add 'ReactDOM.render(<h1>Hello World</h1>, document.getElementById("root")'

## Troubleshooting

* Check parcel version
* Restart parcel (npm start)
* Delete .cache directory
* Run 'npm install' - perhaps also delete 'node_modules' directory

