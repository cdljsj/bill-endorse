## 一个简单的票据应用

用来展示 **__fabric-client__** & **__fabric-ca-client__** Node.js SDK APIs

运行步骤：
```
cd bill-endorse 
npm install
npm install -g bower

cd bill-endorse/public/ng
bower install

cd bill-endorse 
./setupFabricNetwork.sh
./createChannelAndInstallChaincode.sh
```

access http://localhost:4000/ng/src/
