Documentation for Swiss NextGen Banking API-Framework
=============================

Documentation for API Endpoints
########################################

All URIs are relative to *https://api.dev.openbankingproject.ch*

.. csv-table:: a title
   :header: "name", "firstname", "age"
   :widths: 20, 20, 10

   "Smith", "John", 40
   "Smith", "John, Junior", 20


Documentation for Swiss NextGen Banking API-Framework
=================================================================

Documentation for API Endpoints
########################################

All URIs are relative to *https://api.dev.openbankingproject.ch*

.. csv-table:: AccountInformationServiceAISApi
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


.. csv-table:: CommonServicesApi
   :header:  "Operation", "HTTP request", "Description"
   :widths: 500, 500, 500, 500

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

