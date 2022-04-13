Documentation for Swiss NextGen Banking API-Framework
=============================

Documentation for API Endpoints
########################################

All URIs are relative to *https://api.dev.openbankingproject.ch*



AccountInformationServiceAISApi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. csv-table::
   :header:  "Operation", "HTTP request", "Description"
   :widths: 500, 500, 500

    "**POST**","/v1/consents","Create consent"
    "**DELETE**","/v1/consents/{consentId}","Delete Consent"
    "**GET**","/v1/accounts","Read Account List"
    "**GET**","/v1/accounts/{account-id}/balances","Read Balance"
    "**GET**","/v1/consents/{consentId}/authorisations","Get Consent Authorisation Sub-Resources Request"
    "**GET**","/v1/consents/{consentId}","Get Consent Request"
    "**GET**","/v1/consents/{consentId}/authorisations/{authorisationId}","Read the SCA status of the consent authorisation."
    "**GET**","/v1/consents/{consentId}/status","Consent status request"
    "**GET**","/v1/accounts/{account-id}/transactions/{transactionId}","Read Transaction Details"
    "**GET**","/v1/accounts/{account-id}/transactions","Read transaction list of an account"
    "**GET**","/v1/accounts/{account-id}","Read Account Details"
    "**POST**","/v1/consents/{consentId}/authorisations","Start the authorisation process for a consent"
    "**PUT**","/v1/consents/{consentId}/authorisations/{authorisationId}","Update PSU Data for consents"


CommonServicesApi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. csv-table::
   :header:  "Operation", "HTTP request", "Description"
   :widths: 500, 500, 500

    "**DELETE**","/v1/signing-baskets/{basketId}","Delete the signing basket"
    "**GET**","/v1/consents/{consentId}/authorisations/{authorisationId}","Read the SCA status of the consent authorisation."
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId}","Read the SCA status of the payment cancellation's authorisation."
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations","Get Payment Initiation Authorisation Sub-Resources Request"
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId}","Read the SCA Status of the payment authorisation"
    "**GET**","/v1/signing-baskets/{basketId}/authorisations","Get Signing Basket Authorisation Sub-Resources Request"
    "**GET**","/v1/signing-baskets/{basketId}/authorisations/{authorisationId}","Read the SCA status of the signing basket authorisation"
    "**GET**","/v1/signing-baskets/{basketId}/status","Read the status of the signing basket"
    "**POST**","/v1/consents/{consentId}/authorisations","Start the authorisation process for a consent"
    "**POST**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations","Start the authorisation process for a payment initiation"
    "**POST**","/v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations","Start the authorisation process for the cancellation of the addressed payment"
    "**POST**","/v1/signing-baskets/{basketId}/authorisations","Start the authorisation process for a signing basket"
    "**PUT**","/v1/consents/{consentId}/authorisations/{authorisationId}","Update PSU Data for consents"
    "**PUT**","/v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId}","Update PSU Data for payment initiation cancellation"
    "**PUT**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId}","Update PSU data for payment initiation"
    "**PUT**","/v1/signing-baskets/{basketId}/authorisations/{authorisationId}","Update PSU Data for signing basket"


ConfirmationOfFundsServicePIISApi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. csv-table::
   :header:  "Operation", "HTTP request", "Description"
   :widths: 500, 500, 500

    "**POST**","/v1/funds-confirmations","Confirmation of Funds Request"


PaymentInitiationServicePISApi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. csv-table::
   :header:  "Operation", "HTTP request", "Description"
   :widths: 500, 500, 500

    "**DELETE**","/v1/{payment-service}/{payment-product}/{paymentId}","Payment Cancellation Request"
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId}","Read the SCA status of the payment cancellation's authorisation."
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}","Get Payment Information"
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations","Get Payment Initiation Authorisation Sub-Resources Request"
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations","Will deliver an array of resource identifications to all generated cancellation authorisation sub-resources."
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId}","Read the SCA Status of the payment authorisation"
    "**GET**","/v1/{payment-service}/{payment-product}/{paymentId}/status","Payment initiation status request"
    "**POST**","/v1/{payment-service}/{payment-product}","Payment initiation request"
    "**POST**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations","Start the authorisation process for a payment initiation"
    "**POST**","/v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations","Start the authorisation process for the cancellation of the addressed payment"
    "**PUT**","/v1/{payment-service}/{payment-product}/{paymentId}/cancellation-authorisations/{cancellationId}","Update PSU Data for payment initiation cancellation"
    "**PUT**","/v1/{payment-service}/{payment-product}/{paymentId}/authorisations/{authorisationId}","Update PSU data for payment initiation"


SigningBasketsServiceSBSApi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. csv-table::
   :header:  "Operation", "HTTP request", "Description"
   :widths: 500, 500, 500

    "**POST**","/v1/signing-baskets","Create a signing basket resource"
    "**DELETE**","/v1/signing-baskets/{basketId}","Delete the signing basket"
    "**GET**","/v1/signing-baskets/{basketId}","Returns the content of an signing basket object."
    "**GET**","/v1/signing-baskets/{basketId}/authorisations","Get Signing Basket Authorisation Sub-Resources Request"
    "**GET**","/v1/signing-baskets/{basketId}/authorisations/{authorisationId}","Read the SCA status of the signing basket authorisation"
    "**GET**","/v1/signing-baskets/{basketId}/status","Read the status of the signing basket"
    "**POST**","/v1/signing-baskets/{basketId}/authorisations","Start the authorisation process for a signing basket"
    "**PUT**","/v1/signing-baskets/{basketId}/authorisations/{authorisationId}","Update PSU Data for signing basket"



Documentation for Models
########################################

 - Error400_AIS_
 - Error400_AIS_additionalErrors_
 - Error400_NG_AIS_
 - Error400_NG_PIIS_
 - Error400_NG_PIS_
 - Error400_NG_SBS_
 - Error400_PIIS_
 - Error400_PIIS_additionalErrors_
 - Error400_PIS_
 - Error400_PIS_additionalErrors_
 - Error400_SBS_
 - Error400_SBS_additionalErrors_
 - Error401_AIS_
 - Error401_AIS_additionalErrors_
 - Error401_NG_AIS_
 - Error401_NG_PIIS_
 - Error401_NG_PIS_
 - Error401_NG_SBS_
 - Error401_PIIS_
 - Error401_PIIS_additionalErrors_
 - Error401_PIS_
 - Error401_PIS_additionalErrors_
 - Error401_SBS_
 - Error401_SBS_additionalErrors_
 - Error403_AIS_
 - Error403_AIS_additionalErrors_
 - Error403_NG_AIS_
 - Error403_NG_PIIS_
 - Error403_NG_PIS_
 - Error403_NG_SBS_
 - Error403_PIIS_
 - Error403_PIIS_additionalErrors_
 - Error403_PIS_
 - Error403_PIS_additionalErrors_
 - Error403_SBS_
 - Error403_SBS_additionalErrors_
 - Error404_AIS_
 - Error404_AIS_additionalErrors_
 - Error404_NG_AIS_
 - Error404_NG_PIIS_
 - Error404_NG_PIS_
 - Error404_NG_SBS_
 - Error404_PIIS_
 - Error404_PIIS_additionalErrors_
 - Error404_PIS_
 - Error404_PIS_additionalErrors_
 - Error404_SBS_
 - Error404_SBS_additionalErrors_
 - Error405_AIS_
 - Error405_AIS_additionalErrors_
 - Error405_NG_AIS_
 - Error405_NG_PIIS_
 - Error405_NG_PIS_
 - Error405_NG_PIS_CANC_
 - Error405_NG_SBS_
 - Error405_PIIS_
 - Error405_PIIS_additionalErrors_
 - Error405_PIS_
 - Error405_PIS_CANC_
 - Error405_PIS_CANC_additionalErrors_
 - Error405_PIS_additionalErrors_
 - Error405_SBS_
 - Error405_SBS_additionalErrors_
 - Error406_AIS_
 - Error406_AIS_additionalErrors_
 - Error406_NG_AIS_
 - Error409_AIS_
 - Error409_AIS_additionalErrors_
 - Error409_NG_AIS_
 - Error409_NG_PIIS_
 - Error409_NG_PIS_
 - Error409_NG_SBS_
 - Error409_PIIS_
 - Error409_PIIS_additionalErrors_
 - Error409_PIS_
 - Error409_PIS_additionalErrors_
 - Error409_SBS_
 - Error409_SBS_additionalErrors_
 - Error429_AIS_
 - Error429_AIS_additionalErrors_
 - Error429_NG_AIS_
 - MessageCode2XX_
 - MessageCode400_AIS_
 - MessageCode400_PIIS_
 - MessageCode400_PIS_
 - MessageCode400_SBS_
 - MessageCode401_AIS_
 - MessageCode401_PIIS_
 - MessageCode401_PIS_
 - MessageCode401_SBS_
 - MessageCode403_AIS_
 - MessageCode403_PIIS_
 - MessageCode403_PIS_
 - MessageCode403_SBS_
 - MessageCode404_AIS_
 - MessageCode404_PIIS_
 - MessageCode404_PIS_
 - MessageCode404_SBS_
 - MessageCode405_AIS_
 - MessageCode405_PIIS_
 - MessageCode405_PIS_
 - MessageCode405_PIS_CANC_
 - MessageCode405_SBS_
 - MessageCode406_AIS_
 - MessageCode409_AIS_
 - MessageCode409_PIIS_
 - MessageCode409_PIS_
 - MessageCode409_SBS_
 - MessageCode429_AIS_
 - _linksAccountDetails_
 - _linksAccountReport_
 - _linksAll_
 - _linksCardAccountReport_
 - _linksConsents_
 - _linksDownload_
 - _linksGetConsent_
 - _linksPaymentInitiation_
 - _linksPaymentInitiationCancel_
 - _linksSelectPsuAuthenticationMethod_
 - _linksSigningBasket_
 - _linksStartScaProcess_
 - _linksTransactionDetails_
 - _linksUpdatePsuAuthentication_
 - _linksUpdatePsuIdentification_
 - accountAccess_
 - accountDetails_
 - accountList_
 - accountReference16-CH_
 - accountReport_
 - accountStatus_
 - address_
 - amount_
 - authenticationObject_
 - authenticationType_
 - authorisations_
 - balance_
 - balanceType_
 - bulkPaymentInitiationWithStatusResponse_
 - bulkPaymentInitiation_json_
 - cardAccountDetails_
 - cardAccountList_
 - cardAccountReport_
 - cardAccountsTransactionsResponse200_
 - cardTransaction_
 - challengeData_
 - chargeBearer_
 - confirmationOfFunds_
 - consentInformationResponse-200_json_
 - consentStatus_
 - consentStatusResponse-200_
 - consents_
 - consentsResponse-201_
 - creditorAgent7-CH_
 - dayOfExecution_
 - deptorAgent7-CH_
 - exchangeRateInformation1_
 - executionRule_
 - externalServiceLevel1Code_
 - frequencyCode_
 - hrefType_
 - inline_response_200_
 - institutionalIdentification2_
 - paymentInitationRequestResponse-201_
 - paymentInitiationBulkElement_json_
 - paymentInitiationCancelResponse-202_
 - paymentInitiationStatusResponse-200_json_
 - paymentInitiationWithStatusResponse_
 - paymentInitiation_json_
 - periodicPaymentInitiationWithStatusResponse_
 - periodicPaymentInitiation_json_
 - postalAddress6-CH_
 - psuData_
 - purposeCode_
 - readAccountBalanceResponse-200_
 - readCardAccountBalanceResponse-200_
 - remittanceInformationStructured_
 - reportExchangeRate_
 - scaStatus_
 - scaStatusResponse_
 - selectPsuAuthenticationMethod_
 - selectPsuAuthenticationMethodResponse_
 - signingBasket_
 - signingBasketResponse-200_
 - signingBasketResponse-201_
 - signingBasketStatusResponse-200_
 - startScaprocessResponse_
 - tppMessage2XX_
 - tppMessage400_AIS_
 - tppMessage400_PIIS_
 - tppMessage400_PIS_
 - tppMessage400_SBS_
 - tppMessage401_AIS_
 - tppMessage401_PIIS_
 - tppMessage401_PIS_
 - tppMessage401_SBS_
 - tppMessage403_AIS_
 - tppMessage403_PIIS_
 - tppMessage403_PIS_
 - tppMessage403_SBS_
 - tppMessage404_AIS_
 - tppMessage404_PIIS_
 - tppMessage404_PIS_
 - tppMessage404_SBS_
 - tppMessage405_AIS_
 - tppMessage405_PIIS_
 - tppMessage405_PIS_
 - tppMessage405_PIS_CANC_
 - tppMessage405_SBS_
 - tppMessage406_AIS_
 - tppMessage409_AIS_
 - tppMessage409_PIIS_
 - tppMessage409_PIS_
 - tppMessage409_SBS_
 - tppMessage429_AIS_
 - tppMessageCategory_
 - transactionAuthorisation_
 - transactionDetails_
 - transactionStatus_
 - transactionStatus_SBS_
 - transactionsResponse-200_json_
 - updatePsuAuthentication_
 - updatePsuAuthenticationResponse_
 - updatePsuIdenticationResponse_
   

Documentation for Authorization
########################################

    
BearerAuthOAuth
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 - **Type**: HTTP basic authentication
 


.. _: Apis/%7B%7BapiDocPath%7D%7D%7B%7Bclassname%7D%7D.md#%7B%7BoperationIdLowerCase%7D%7D
.. _: ./%7B%7B%7BmodelPackage%7D%7D%7D/%7B%7BmodelDocPath%7D%7D%7B%7B%7BclassFilename%7D%7D%7D.md
