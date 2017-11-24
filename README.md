# README #

API Automation Test with Newman & Node.js

# How to install

* Mac
  Go to nodejs.org, click ‘install’, and run through the install process.

* Ubuntu
  Run the following on your command line to install the source for nodejs

   ```curl -sL https://deb.nodesource.com/setup | sudo -E bash -```

   ```sudo apt-get install -y nodejs```

* Windows 
  installer from the [**Node.js**](https://nodejs.org) web site.
  
* Install Newman using NPM.

    ```
    $ npm install newman --global
    ```
	
# Example run

```
$ newman run  collection.json -e environment.json --exitCode 1 -r cli,html --reporter-html-export report.html
```
