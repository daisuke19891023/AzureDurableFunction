# AzureDurableFunction
local test for azure Durable

## 
### envirnmnent
Windows 10 home edition 64bit

### for develop
visual studio code
extention azure function
create project

### for test
microsoft sql server
azure cosmos db emulator

## installation
install azure-functions-core-tools
``` 
npm install azure-functions-core-tools --save 
npm install jest --save 
npm install eslint --save
npm install durable-functions --save
```

F5 debug

http://localhost:7071/api/orchestrators/{functionName}

http://localhost:7071/api/orchestrators/DurableFunctionsOrchestratorJS