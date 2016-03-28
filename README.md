# Installation: 

npm install
npm install -g phantomjs@1.9.8


# Run tests: 

1. Start a local web server that servers the index.html file (try using something like Serve - http://get-serve.com/) 
2. Make sure that the url on line 3 of tests/visual/index.spec.js is correct
3. Start the SASS watcher from a command line propmt: 	**sass --watch scss:css**
4. Run this command from a command line prompt:  **casperjs test tests/visual/index.spec.js**

