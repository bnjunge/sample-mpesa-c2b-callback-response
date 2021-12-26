# sample mpesa c2b callback response
Sample response received on M-PESA C2B Validate and confirmation URLs.

Since the C2B Register URL API is not that "stable", this is the response you can expect when
its working as expected. You can this manyally using a client like Postman and test your endpoints.

```javascript

{
"TransactionType": "Pay Bill",
"TransID": "PO23ERTG76U",
"TransTime": "20210605145023",
"TransAmount": "510",
"BusinessShortCode": "123456",
"BillRefNumber": "CUS-00014",
"InvoiceNumber": "",
"OrgAccountBalance": "350.00",
"ThirdPartyTransID": "",
"MSISDN": "254711123123",
"FirstName": "John",
"MiddleName": "J",
"LastName": "Doe"
}

```