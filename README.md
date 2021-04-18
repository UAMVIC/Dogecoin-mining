@echo off
 
setlocal enableDelayedExpansion
 
Rem #################################
Rem ## Begin of user-editable part ##
Rem #################################
 
set "POOL=ethash.unmineable.com:3333"
set "WALLET=DOGE:钱包地址.lolMinerWorker"										
 
Rem #################################
Rem ##  End of user-editable part  ##
Rem #################################
 
lolMiner.exe --algo ETHASH --pool ethash.unmineable.com:3333 --user DOGE:钱包地址.矿工名字#h99v-k3cl --4g-alloc-size 4024 --keepfree 8 
timeout 10
