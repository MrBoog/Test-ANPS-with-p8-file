# Test-APNS-with-p8-file

First we need to initiate a new Node.js project and apn package for npm.

```
npm install apn --save  
```

Then copy the `.p8` file to your current folder, rename it as `apns.p8`.

Modify the `app.js` file, fill in `apnProvider & deviceToken & notification` etc.

After this, just use `node app.js` to run this script.


