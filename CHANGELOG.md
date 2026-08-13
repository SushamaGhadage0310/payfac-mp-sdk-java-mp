CHANGELOG
---------
## 16.0.0
* **Feature** Merchant Category Code No Longer Optional on 'LegalEntityCreate' Request
* **Feature** New complex element 'valueAddedServices' is added in 'subMerchantCreateRequest','subMerchantUpdateRequest'
* **Feature** New element 'valueAddedServices' is of type 'valueAddedServices' which contains 'code' of type 'valueAddedServiceProductCode' and 'enabled' is of type 'boolean'
* **Feature** To support element 'code' new Enum is added 'valueAddedServiceProductCode' with value 'DISPUTE_DEFENDER'

## 15.0.1
* **Feature** Support for Merchant Category Code - Payfac MP API version 15.0.1

## 15.0.0
* **Feature** Support for Payfac MP API version 15.0


## 14.0.0
* **Feature** Support for Payfac MP API version 14.0
* **Change** Package structure is changed from 'com.mp.sdk' to 'io.github.vantiv.mp.sdk' to support Sonatype repository for publishing artifacts.

## 13.1.0
* **Feature** Support for Payfac MP API version 13.1

## 13.0.1
* **BugFix** original Legal Entity camel casing is corrected

## 13.0.0
* **Feature** Support for PayFac MP API version 13.0

