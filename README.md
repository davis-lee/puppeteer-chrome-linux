# docker
```
docker pull ohko/puppeteer-chrome-linux
docker rm -fv puppeteer
docker run -d --name=puppeteer --restart=always -p 127.0.0.1:5400:8080 ohko/puppeteer-chrome-linux
```

# install
```
yarn install
```

# test cli
```
npm run test
# or
node test.js
```

# run server
```
npm run start
# or
node server.js
```

# run chromium
```
./node_modules/puppeteer/.local-chromium/mac-674921/chrome-mac/Chromium.app/Contents/MacOS/Chromium --remote-debugging-port=9222 --proxy-server=socks5://127.0.0.1:1080 --user-data-dir=/tmp/user1
```

# run chrome
```
/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --remote-debugging-port=9222 --user-data-dir=/tmp/user-a
```