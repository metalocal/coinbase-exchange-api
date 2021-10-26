### Coinbase Exchange API


#### Reference

https://docs.cloud.coinbase.com/exchange/reference


#### Resources with Functions

Accounts

getaccounts
getaccount
getaccountholds
getaccountledger
getaccounttransfers

Coinbase Accounts

getcoinbaseaccounts
generatecryptoaddress

Conversions

postconversion
getconversion

Currencies

getcurrencies
getcurrency

Transfers

postdepositcoinbaseaccount
postdepositpaymentmethod
getpaymentmethods.json
gettransfers.json
gettransfer.json
postwithdrawcoinbaseaccount
postwithdrawcrypto
getwithdrawfeeestimate.json
postwithdrawpaymentmethod

Fees

getfees

Orders

getfills
getorders
deleteorders
postorders
getorder
deleteorder

Coinbase price oracle

getcoinbasepriceoracle

Products

getproducts
getproduct
getproductbook
getproductcandles
getproductstats
getproductticker
getproducttrades

Profiles

getprofiles
postprofile
postprofiletransfer
getprofile
putprofile
putprofiledeactivate

Reports

getreports
postreports
getreport

Users

getuserexchangelimits


#### Generate Docs

```shell
cat api.json | jq '.oasDefinition' > api.oas3.json
```
