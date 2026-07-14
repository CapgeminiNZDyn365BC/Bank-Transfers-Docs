This section includes topics for each of the pages within the app. If you have navigated to this page from within the app from a specific page, it means there is no context-sensitive help for the page you navigated from.

## Bank Account Card
Before you can post to a Bank Account, you must configure *Bank Acc. Posting Group*. You can find details on how to set up bank accounts in the standard online help for Business Central.

To use a bank account as a pay-from bank account for EFT payments, you must have a *Bank Branch No.* and *Bank Account No.* configured with values that indicate which file format is to be used. If you have an Australian bank account in a New Zealand company, you must specify the AUD currency code against the bank account as well as have a correctly formatted bank account. If you are using a New Zealand bank account in a New Zealand company, the currency code must be left blank (to indicate it is using the local currency). Similarly in an Australian company an Australian bank will have a blank currency and a New Zealand bank account will have an NZD currency code.

### Australian Bank

For an Australian banks account to be available for producing an Australian Banking Association (ABA) File Format export, it must have the following fields configured:

| Bank Account Field | Description |
| --- | --- |
| Bank Branch No. | Must match format AAB-CCC Where A = 2 digit bank code B = 1 digit state code C = 3 digit branch location code |
| Bank Account No. | Must match format DDDDDDDDD Where D = up to 9 digit bank account |
| AU EFT Bank Code | The three-character mnemonic code for the bank e.g. ANZ, WPA |
| AU EFT Security Name | Your account name |
| AU EFT Security No. | You user identification number |

![Australian Bank Setup Page](../images/page-help/Australian%20Bank%20Setup%20Page.jpg "Australian Bank Setup Page")

### New Zealand Bank

To use a New Zealand bank to produce EFT files, it must have the following fields configured:

| Bank Account Field | Description |
| --- | --- |
| Bank Branch No. | Must match format AA-BBBB Where A = 2 digit bank code (see list below) B = 4 digit branch code **Supported Bank Codes** ANZ - 01, 06, 11 ASB - 12 BNZ - 02 Westpac - 03 |
| Bank Account No. | Must match format CCCCCCC-DD or CCCCCCC-DDD Where CCCCCCC = 7 digit bank account number DD or DDD = 2 or 3 digit suffix |

![NZ Bank Account Westpac page](../images/page-help/NZ%20Bank%20Account%20Westpac%20page.jpg "NZ Bank Account Westpac page")

If you want to send remittances as an email attachment directly to your payees, you must configure the *Email Settings* on the *Capgemini Bank Transfers Setup* page.

## Capgemini Bank Transfers Setup

If you want to send remittances as an email attachment directly to your payees, you must configure the *Email Settings* on the *Capgemini Bank Transfers Setup* page.

The emailing of remittances will use your SMTP settings. The value you need to enter in the *Email From Address* must match the values of the *User ID* field on the *SMTP Mail Setup* page.

### Fields

| Field | Description |
| --- | --- |
| Email From Name | Name to appear as the sender name in the recipient's email. |
| Email From Address | Email address that the remittance will be sent from. |
| Remittance Shows Email Address | Specifies a description of the email body layout that is used. |
| Use Legacy Subscription Service | Specifies that the legacy subscription service should be used to check a valid license exists. |

## Purchase Invoice

### Creating a One-time Vendor Document

1. Create a new purchase order or purchase invoice using the vendor number as the one-time vendor you have setup previously. Below is an example for a purchase invoice.

![One time vendor purchase Invoice](../images/page-help/One%20time%20vendor%20purchase%20Invoice.jpg "One time vendor purchase Invoice")

Complete the new required fields (marked with an asterisk) for the one-time vendor:

* Vendor Name - used for the remittance advice.
* Bank Branch No. - should be completed in the correct format for the country i.e. for NZ 99-9999, or for AU 999-999.
* Bank Account No. - should be completed in the correct format for the country i.e. for NZ 9999999-999, or for AU 999999999.
* Email for Remittance – enter an email address. You can optionally enter address fields which will print in the address section on the remittance.

You can optionally also fill in the following:

* Email for Remittance Advice – this will be used to send the remittance advice to once the payment has been made.
* Our Account No./Reference – will be used for the Reference field on the payment.
* Address details – these will be used on the remittance advice.

![One time vendor purchase invoice fields completed](../images/page-help/One%20time%20vendor%20purchase%20invoice%20fields%20completed.jpg "One time vendor purchase invoice fields completed")

#### Post the Invoice

Post the invoice, then you can go to the payment journal and select these entries for payment.

## Purchase Order

### Creating a One-time Vendor Document

1. Create a new purchase order or purchase invoice using the vendor number as the one-time vendor you have setup previously. Below is an example for a purchase invoice.

![One time vendor purchase Invoice](../images/page-help/One%20time%20vendor%20purchase%20Invoice.jpg "One time vendor purchase Invoice")

Complete the new required fields (marked with an asterisk) for the one-time vendor:

* Vendor Name - used for the remittance advice.
* Bank Branch No. - should be completed in the correct format for the country i.e. for NZ 99-9999, or for AU 999-999.
* Bank Account No. - should be completed in the correct format for the country i.e. for NZ 9999999-999, or for AU 999999999.
* Email for Remittance – enter an email address. You can optionally enter address fields which will print in the address section on the remittance.

You can optionally also fill in the following:

* Email for Remittance Advice – this will be used to send the remittance advice to once the payment has been made.
* Our Account No./Reference – will be used for the Reference field on the payment.
* Address details – these will be used on the remittance advice.

![One time vendor purchase invoice fields completed](../images/page-help/One%20time%20vendor%20purchase%20invoice%20fields%20completed.jpg "One time vendor purchase invoice fields completed")

#### Post the Invoice

Post the invoice, then you can go to the payment journal and select these entries for payment.