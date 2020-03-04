# Tron-commandline-tool

## TRON-Family commandline tool

## Download
https://www.tron-family.de

# Commands:

### Wallet
-account <walletaddress>
-trx <amount> <destinationaddress> <privatekey>
-trc10 <amount> <destinationaddress> <privatekey> <tokenid> <precision>
-trc20 <amount> <destinationaddress> <privatekey> <contractaddress> <precision>
-vote <amount> <witnessaddress> <privatekey>
-claim <privatekey>
-freeze <amount> <resource> <privatekey>
-unfreeze <resource> <privatekey>

### Trading
-polonidexpairs
-polonidexorderbook <pairid>
-polonidexopenorder <walletaddress> optional:<pairid>
-polonidexbuy <pairid> <amount> <price> <privatekey>
-polonidexsell <pairid> <amount> <price> <privatekey>
-polonidexcancel <orderid> <privatekey>

### Convert

-abiaddressencode <address>
-abiaddressdecode <hex>
-abivalueencode <value>
-abivaluedecode <hex>
-toHexAddress <walletaddress>
-toBase58Address <hexaddress>

### Batchsend

-batch <importfile.csv> <privatekey> optional: /v (verify)
-createimportfile <filename>
