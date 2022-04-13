Documentation for Swiss NextGen Banking API-Framework
=============================

Documentation for API Endpoints
########################################

All URIs are relative to *https://api.dev.openbankingproject.ch*

+--------------------------------------+-------------------------------+-------------------------------------------------------------------------------------+-----------------------------+--------------------------------------------------+
|                Class                 |            Method             |                                    HTTP request                                     |         Description         |                                                  |
+======================================+===============================+=====================================================================================+=============================+==================================================+
|                Class                 |            Method             |                                    HTTP request                                     |         Description         |                                                  |
+--------------------------------------+-------------------------------+-------------------------------------------------------------------------------------+-----------------------------+--------------------------------------------------+


| *AccountInformationServiceAISApi* | [**createConsent**](Apis/AccountInformationServiceAISApi.md#createconsent) | **POST** /v1/consents | Create consent || *AccountInformationServiceAISApi* | [**deleteConsent**](Apis/AccountInformationServiceAISApi.md#deleteconsent) | **DELETE** /v1/consents/{consentId} | Delete Consent || *AccountInformationServiceAISApi* | [**getAccountList**](Apis/AccountInformationServiceAISApi.md#getaccountlist) | **GET** /v1/accounts | Read Account List || *AccountInformationServiceAISApi* | [**getBalances**](Apis/AccountInformationServiceAISApi.md#getbalances) | **GET** /v1/accounts/{account-id}/balances | Read Balance || *AccountInformationServiceAISApi* | [**getConsentAuthorisation**](Apis/AccountInformationServiceAISApi.md#getconsentauthorisation) | **GET** /v1/consents/{consentId}/authorisations | Get Consent Authorisation Sub-Resources Request || *AccountInformationServiceAISApi* | [**getConsentInformation**](Apis/AccountInformationServiceAISApi.md#getconsentinformation) | **GET** /v1/consents/{consentId} | Get Consent Request || *AccountInformationServiceAISApi* | [**getConsentScaStatus**](Apis/AccountInformationServiceAISApi.md#getconsentscastatus) | **GET** /v1/consents/{consentId}/authorisations/{authorisationId} | Read the SCA status of the consent authorisation. || *AccountInformationServiceAISApi* | [**getConsentStatus**](Apis/AccountInformationServiceAISApi.md#getconsentstatus) | **GET** /v1/consents/{consentId}/status | Consent status request || *AccountInformationServiceAISApi* | [**getTransactionDetails**](Apis/AccountInformationServiceAISApi.md#gettransactiondetails) | **GET** /v1/accounts/{account-id}/transactions/{transactionId} | Read Transaction Details || *AccountInformationServiceAISApi* | [**getTransactionList**](Apis/AccountInformationServiceAISApi.md#gettransactionlist) | **GET** /v1/accounts/{account-id}/transactions | Read transaction list of an account || *AccountInformationServiceAISApi* | [**readAccountDetails**](Apis/AccountInformationServiceAISApi.md#readaccountdetails) | **GET** /v1/accounts/{account-id} | Read Account Details || *AccountInformationServiceAISApi* | [**startConsentAuthorisation**](Apis/AccountInformationServiceAISApi.md#startconsentauthorisation) | **POST** /v1/consents/{consentId}/authorisations | Start the authorisation process for a consent || *AccountInformationServiceAISApi* | [**updateConsentsPsuData**](Apis/AccountInformationServiceAISApi.md#updateconsentspsudata) | **PUT** /v1/consents/{consentId}/authorisations/{authorisationId} | Update PSU Data for consents || *CommonServicesApi* | [**deleteSigningBasket**](Apis/CommonServicesApi.md#deletesigningbasket) | **DELETE** /v1/signing-baskets/{basketId} | Delete the signing basket || *CommonServicesApi* | [**getConsentScaStatus**](Apis/CommonServicesApi.md#getconsentscastatus) | **GET** /v1/consents/{consentId}/authorisations/{authorisationId} | Read the SCA status of the consent authorisation. || *CommonServicesApi* | [**getPaymentCancellationScaStatus**](Apis/CommonServicesApi.md#getpaymentcancellationscastatus) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId} | Read the SCA status of the payment cancellation's authorisation. || *CommonServicesApi* | [**getPaymentInitiationAuthorisation**](Apis/CommonServicesApi.md#getpaymentinitiationauthorisation) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations | Get Payment Initiation Authorisation Sub-Resources Request || *CommonServicesApi* | [**getPaymentInitiationScaStatus**](Apis/CommonServicesApi.md#getpaymentinitiationscastatus) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId} | Read the SCA Status of the payment authorisation || *CommonServicesApi* | [**getSigningBasketAuthorisation**](Apis/CommonServicesApi.md#getsigningbasketauthorisation) | **GET** /v1/signing-baskets/{basketId}/authorisations | Get Signing Basket Authorisation Sub-Resources Request || *CommonServicesApi* | [**getSigningBasketScaStatus**](Apis/CommonServicesApi.md#getsigningbasketscastatus) | **GET** /v1/signing-baskets/{basketId}/authorisations/{authorisationId} | Read the SCA status of the signing basket authorisation || *CommonServicesApi* | [**getSigningBasketStatus**](Apis/CommonServicesApi.md#getsigningbasketstatus) | **GET** /v1/signing-baskets/{basketId}/status | Read the status of the signing basket || *CommonServicesApi* | [**startConsentAuthorisation**](Apis/CommonServicesApi.md#startconsentauthorisation) | **POST** /v1/consents/{consentId}/authorisations | Start the authorisation process for a consent || *CommonServicesApi* | [**startPaymentAuthorisation**](Apis/CommonServicesApi.md#startpaymentauthorisation) | **POST** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations | Start the authorisation process for a payment initiation || *CommonServicesApi* | [**startPaymentInitiationCancellationAuthorisation**](Apis/CommonServicesApi.md#startpaymentinitiationcancellationauthorisation) | **POST** /v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations | Start the authorisation process for the cancellation of the addressed payment || *CommonServicesApi* | [**startSigningBasketAuthorisation**](Apis/CommonServicesApi.md#startsigningbasketauthorisation) | **POST** /v1/signing-baskets/{basketId}/authorisations | Start the authorisation process for a signing basket || *CommonServicesApi* | [**updateConsentsPsuData**](Apis/CommonServicesApi.md#updateconsentspsudata) | **PUT** /v1/consents/{consentId}/authorisations/{authorisationId} | Update PSU Data for consents || *CommonServicesApi* | [**updatePaymentCancellationPsuData**](Apis/CommonServicesApi.md#updatepaymentcancellationpsudata) | **PUT** /v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId} | Update PSU Data for payment initiation cancellation || *CommonServicesApi* | [**updatePaymentPsuData**](Apis/CommonServicesApi.md#updatepaymentpsudata) | **PUT** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId} | Update PSU data for payment initiation || *CommonServicesApi* | [**updateSigningBasketPsuData**](Apis/CommonServicesApi.md#updatesigningbasketpsudata) | **PUT** /v1/signing-baskets/{basketId}/authorisations/{authorisationId} | Update PSU Data for signing basket || *ConfirmationOfFundsServicePIISApi* | [**checkAvailabilityOfFunds**](Apis/ConfirmationOfFundsServicePIISApi.md#checkavailabilityoffunds) | **POST** /v1/funds-confirmations | Confirmation of Funds Request || *PaymentInitiationServicePISApi* | [**cancelPayment**](Apis/PaymentInitiationServicePISApi.md#cancelpayment) | **DELETE** /v1/{payment-service}/{payment-product}/{paymentId} | Payment Cancellation Request || *PaymentInitiationServicePISApi* | [**getPaymentCancellationScaStatus**](Apis/PaymentInitiationServicePISApi.md#getpaymentcancellationscastatus) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId} | Read the SCA status of the payment cancellation's authorisation. || *PaymentInitiationServicePISApi* | [**getPaymentInformation**](Apis/PaymentInitiationServicePISApi.md#getpaymentinformation) | **GET** /v1/{payment-service}/{payment-product}/{paymentId} | Get Payment Information || *PaymentInitiationServicePISApi* | [**getPaymentInitiationAuthorisation**](Apis/PaymentInitiationServicePISApi.md#getpaymentinitiationauthorisation) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations | Get Payment Initiation Authorisation Sub-Resources Request || *PaymentInitiationServicePISApi* | [**getPaymentInitiationCancellationAuthorisationInformation**](Apis/PaymentInitiationServicePISApi.md#getpaymentinitiationcancellationauthorisationinformation) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations | Will deliver an array of resource identifications to all generated cancellation authorisation sub-resources. || *PaymentInitiationServicePISApi* | [**getPaymentInitiationScaStatus**](Apis/PaymentInitiationServicePISApi.md#getpaymentinitiationscastatus) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId} | Read the SCA Status of the payment authorisation || *PaymentInitiationServicePISApi* | [**getPaymentInitiationStatus**](Apis/PaymentInitiationServicePISApi.md#getpaymentinitiationstatus) | **GET** /v1/{payment-service}/{payment-product}/{paymentId}/status | Payment initiation status request || *PaymentInitiationServicePISApi* | [**initiatePayment**](Apis/PaymentInitiationServicePISApi.md#initiatepayment) | **POST** /v1/{payment-service}/{payment-product} | Payment initiation request || *PaymentInitiationServicePISApi* | [**startPaymentAuthorisation**](Apis/PaymentInitiationServicePISApi.md#startpaymentauthorisation) | **POST** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations | Start the authorisation process for a payment initiation || *PaymentInitiationServicePISApi* | [**startPaymentInitiationCancellationAuthorisation**](Apis/PaymentInitiationServicePISApi.md#startpaymentinitiationcancellationauthorisation) | **POST** /v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations | Start the authorisation process for the cancellation of the addressed payment || *PaymentInitiationServicePISApi* | [**updatePaymentCancellationPsuData**](Apis/PaymentInitiationServicePISApi.md#updatepaymentcancellationpsudata) | **PUT** /v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId} | Update PSU Data for payment initiation cancellation || *PaymentInitiationServicePISApi* | [**updatePaymentPsuData**](Apis/PaymentInitiationServicePISApi.md#updatepaymentpsudata) | **PUT** /v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId} | Update PSU data for payment initiation || *SigningBasketsServiceSBSApi* | [**createSigningBasket**](Apis/SigningBasketsServiceSBSApi.md#createsigningbasket) | **POST** /v1/signing-baskets | Create a signing basket resource || *SigningBasketsServiceSBSApi* | [**deleteSigningBasket**](Apis/SigningBasketsServiceSBSApi.md#deletesigningbasket) | **DELETE** /v1/signing-baskets/{basketId} | Delete the signing basket || *SigningBasketsServiceSBSApi* | [**getSigningBasket**](Apis/SigningBasketsServiceSBSApi.md#getsigningbasket) | **GET** /v1/signing-baskets/{basketId} | Returns the content of an signing basket object. || *SigningBasketsServiceSBSApi* | [**getSigningBasketAuthorisation**](Apis/SigningBasketsServiceSBSApi.md#getsigningbasketauthorisation) | **GET** /v1/signing-baskets/{basketId}/authorisations | Get Signing Basket Authorisation Sub-Resources Request || *SigningBasketsServiceSBSApi* | [**getSigningBasketScaStatus**](Apis/SigningBasketsServiceSBSApi.md#getsigningbasketscastatus) | **GET** /v1/signing-baskets/{basketId}/authorisations/{authorisationId} | Read the SCA status of the signing basket authorisation || *SigningBasketsServiceSBSApi* | [**getSigningBasketStatus**](Apis/SigningBasketsServiceSBSApi.md#getsigningbasketstatus) | **GET** /v1/signing-baskets/{basketId}/status | Read the status of the signing basket || *SigningBasketsServiceSBSApi* | [**startSigningBasketAuthorisation**](Apis/SigningBasketsServiceSBSApi.md#startsigningbasketauthorisation) | **POST** /v1/signing-baskets/{basketId}/authorisations | Start the authorisation process for a signing basket || *SigningBasketsServiceSBSApi* | [**updateSigningBasketPsuData**](Apis/SigningBasketsServiceSBSApi.md#updatesigningbasketpsudata) | **PUT** /v1/signing-baskets/{basketId}/authorisations/{authorisationId} | Update PSU Data for signing basket |
+--------------------------------------+-------------------------------+-------------------------------------------------------------------------------------+-----------------------------+--------------------------------------------------+

 ## Documentation for Models

  - `Error400_AIS`_
 - `Error400_AIS_additionalErrors`_
 - `Error400_NG_AIS`_
 - `Error400_NG_PIIS`_
 - `Error400_NG_PIS`_
 - `Error400_NG_SBS`_
 - `Error400_PIIS`_
 - `Error400_PIIS_additionalErrors`_
 - `Error400_PIS`_
 - `Error400_PIS_additionalErrors`_
 - `Error400_SBS`_
 - `Error400_SBS_additionalErrors`_
 - `Error401_AIS`_
 - `Error401_AIS_additionalErrors`_
 - `Error401_NG_AIS`_
 - `Error401_NG_PIIS`_
 - `Error401_NG_PIS`_
 - `Error401_NG_SBS`_
 - `Error401_PIIS`_
 - `Error401_PIIS_additionalErrors`_
 - `Error401_PIS`_
 - `Error401_PIS_additionalErrors`_
 - `Error401_SBS`_
 - `Error401_SBS_additionalErrors`_
 - `Error403_AIS`_
 - `Error403_AIS_additionalErrors`_
 - `Error403_NG_AIS`_
 - `Error403_NG_PIIS`_
 - `Error403_NG_PIS`_
 - `Error403_NG_SBS`_
 - `Error403_PIIS`_
 - `Error403_PIIS_additionalErrors`_
 - `Error403_PIS`_
 - `Error403_PIS_additionalErrors`_
 - `Error403_SBS`_
 - `Error403_SBS_additionalErrors`_
 - `Error404_AIS`_
 - `Error404_AIS_additionalErrors`_
 - `Error404_NG_AIS`_
 - `Error404_NG_PIIS`_
 - `Error404_NG_PIS`_
 - `Error404_NG_SBS`_
 - `Error404_PIIS`_
 - `Error404_PIIS_additionalErrors`_
 - `Error404_PIS`_
 - `Error404_PIS_additionalErrors`_
 - `Error404_SBS`_
 - `Error404_SBS_additionalErrors`_
 - `Error405_AIS`_
 - `Error405_AIS_additionalErrors`_
 - `Error405_NG_AIS`_
 - `Error405_NG_PIIS`_
 - `Error405_NG_PIS`_
 - `Error405_NG_PIS_CANC`_
 - `Error405_NG_SBS`_
 - `Error405_PIIS`_
 - `Error405_PIIS_additionalErrors`_
 - `Error405_PIS`_
 - `Error405_PIS_CANC`_
 - `Error405_PIS_CANC_additionalErrors`_
 - `Error405_PIS_additionalErrors`_
 - `Error405_SBS`_
 - `Error405_SBS_additionalErrors`_
 - `Error406_AIS`_
 - `Error406_AIS_additionalErrors`_
 - `Error406_NG_AIS`_
 - `Error409_AIS`_
 - `Error409_AIS_additionalErrors`_
 - `Error409_NG_AIS`_
 - `Error409_NG_PIIS`_
 - `Error409_NG_PIS`_
 - `Error409_NG_SBS`_
 - `Error409_PIIS`_
 - `Error409_PIIS_additionalErrors`_
 - `Error409_PIS`_
 - `Error409_PIS_additionalErrors`_
 - `Error409_SBS`_
 - `Error409_SBS_additionalErrors`_
 - `Error429_AIS`_
 - `Error429_AIS_additionalErrors`_
 - `Error429_NG_AIS`_
 - `MessageCode2XX`_
 - `MessageCode400_AIS`_
 - `MessageCode400_PIIS`_
 - `MessageCode400_PIS`_
 - `MessageCode400_SBS`_
 - `MessageCode401_AIS`_
 - `MessageCode401_PIIS`_
 - `MessageCode401_PIS`_
 - `MessageCode401_SBS`_
 - `MessageCode403_AIS`_
 - `MessageCode403_PIIS`_
 - `MessageCode403_PIS`_
 - `MessageCode403_SBS`_
 - `MessageCode404_AIS`_
 - `MessageCode404_PIIS`_
 - `MessageCode404_PIS`_
 - `MessageCode404_SBS`_
 - `MessageCode405_AIS`_
 - `MessageCode405_PIIS`_
 - `MessageCode405_PIS`_
 - `MessageCode405_PIS_CANC`_
 - `MessageCode405_SBS`_
 - `MessageCode406_AIS`_
 - `MessageCode409_AIS`_
 - `MessageCode409_PIIS`_
 - `MessageCode409_PIS`_
 - `MessageCode409_SBS`_
 - `MessageCode429_AIS`_
 - `_linksAccountDetails`_
 - `_linksAccountReport`_
 - `_linksAll`_
 - `_linksCardAccountReport`_
 - `_linksConsents`_
 - `_linksDownload`_
 - `_linksGetConsent`_
 - `_linksPaymentInitiation`_
 - `_linksPaymentInitiationCancel`_
 - `_linksSelectPsuAuthenticationMethod`_
 - `_linksSigningBasket`_
 - `_linksStartScaProcess`_
 - `_linksTransactionDetails`_
 - `_linksUpdatePsuAuthentication`_
 - `_linksUpdatePsuIdentification`_
 - `accountAccess`_
 - `accountDetails`_
 - `accountList`_
 - `accountReference16-CH`_
 - `accountReport`_
 - `accountStatus`_
 - `address`_
 - `amount`_
 - `authenticationObject`_
 - `authenticationType`_
 - `authorisations`_
 - `balance`_
 - `balanceType`_
 - `bulkPaymentInitiationWithStatusResponse`_
 - `bulkPaymentInitiation_json`_
 - `cardAccountDetails`_
 - `cardAccountList`_
 - `cardAccountReport`_
 - `cardAccountsTransactionsResponse200`_
 - `cardTransaction`_
 - `challengeData`_
 - `chargeBearer`_
 - `confirmationOfFunds`_
 - `consentInformationResponse-200_json`_
 - `consentStatus`_
 - `consentStatusResponse-200`_
 - `consents`_
 - `consentsResponse-201`_
 - `creditorAgent7-CH`_
 - `dayOfExecution`_
 - `deptorAgent7-CH`_
 - `exchangeRateInformation1`_
 - `executionRule`_
 - `externalServiceLevel1Code`_
 - `frequencyCode`_
 - `hrefType`_
 - `inline_response_200`_
 - `institutionalIdentification2`_
 - `paymentInitationRequestResponse-201`_
 - `paymentInitiationBulkElement_json`_
 - `paymentInitiationCancelResponse-202`_
 - `paymentInitiationStatusResponse-200_json`_
 - `paymentInitiationWithStatusResponse`_
 - `paymentInitiation_json`_
 - `periodicPaymentInitiationWithStatusResponse`_
 - `periodicPaymentInitiation_json`_
 - `postalAddress6-CH`_
 - `psuData`_
 - `purposeCode`_
 - `readAccountBalanceResponse-200`_
 - `readCardAccountBalanceResponse-200`_
 - `remittanceInformationStructured`_
 - `reportExchangeRate`_
 - `scaStatus`_
 - `scaStatusResponse`_
 - `selectPsuAuthenticationMethod`_
 - `selectPsuAuthenticationMethodResponse`_
 - `signingBasket`_
 - `signingBasketResponse-200`_
 - `signingBasketResponse-201`_
 - `signingBasketStatusResponse-200`_
 - `startScaprocessResponse`_
 - `tppMessage2XX`_
 - `tppMessage400_AIS`_
 - `tppMessage400_PIIS`_
 - `tppMessage400_PIS`_
 - `tppMessage400_SBS`_
 - `tppMessage401_AIS`_
 - `tppMessage401_PIIS`_
 - `tppMessage401_PIS`_
 - `tppMessage401_SBS`_
 - `tppMessage403_AIS`_
 - `tppMessage403_PIIS`_
 - `tppMessage403_PIS`_
 - `tppMessage403_SBS`_
 - `tppMessage404_AIS`_
 - `tppMessage404_PIIS`_
 - `tppMessage404_PIS`_
 - `tppMessage404_SBS`_
 - `tppMessage405_AIS`_
 - `tppMessage405_PIIS`_
 - `tppMessage405_PIS`_
 - `tppMessage405_PIS_CANC`_
 - `tppMessage405_SBS`_
 - `tppMessage406_AIS`_
 - `tppMessage409_AIS`_
 - `tppMessage409_PIIS`_
 - `tppMessage409_PIS`_
 - `tppMessage409_SBS`_
 - `tppMessage429_AIS`_
 - `tppMessageCategory`_
 - `transactionAuthorisation`_
 - `transactionDetails`_
 - `transactionStatus`_
 - `transactionStatus_SBS`_
 - `transactionsResponse-200_json`_
 - `updatePsuAuthentication`_
 - `updatePsuAuthenticationResponse`_
 - `updatePsuIdenticationResponse`_
   

 ## Documentation
for Authorization

     ###
BearerAuthOAuth

 - **Type**: HTTP basic authentication
 


.. _: Apis/%7B%7BapiDocPath%7D%7D%7B%7Bclassname%7D%7D.md#%7B%7BoperationIdLowerCase%7D%7D
.. _: ./%7B%7B%7BmodelPackage%7D%7D%7D/%7B%7BmodelDocPath%7D%7D%7B%7B%7BclassFilename%7D%7D%7D.md
