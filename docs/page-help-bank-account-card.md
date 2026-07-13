Before you can post to a Bank Account, you must configure *Bank Acc. Posting Group*. You can find details on how to set up bank accounts in the standard online help for Business Central.

To use a bank account as a pay-from bank account for EFT payments, you must have a *Bank Branch No.* and *Bank Account No.* configured with values that indicate which file format is to be used. If you have an Australian bank account in a New Zealand company, you must specify the AUD currency code against the bank account as well as have a correctly formatted bank account. If you are using a New Zealand bank account in a New Zealand company, the currency code must be left blank (to indicate it is using the local currency). Similarly in an Australian company an Australian bank will have a blank currency and a New Zealand bank account will have an NZD currency code.

## Australian Bank

For an Australian banks account to be available for producing an Australian Banking Association (ABA) File Format export, it must have the following fields configured:

| Bank Account Field | Description |
| --- | --- |
| Bank Branch No. | Must match format AAB-CCC Where A = 2 digit bank code B = 1 digit state code C = 3 digit branch location code |
| Bank Account No. | Must match format DDDDDDDDD Where D = up to 9 digit bank account |
| AU EFT Bank Code | The three-character mnemonic code for the bank e.g. ANZ, WPA |
| AU EFT Security Name | Your account name |
| AU EFT Security No. | You user identification number |

![Australian Bank Setup Page](../images/Australian%20Bank%20Setup%20Page.jpg "Australian Bank Setup Page")

## New Zealand Bank

To use a New Zealand bank to produce EFT files, it must have the following fields configured:

| Bank Account Field | Description |
| --- | --- |
| Bank Branch No. | Must match format AA-BBBB Where A = 2 digit bank code (see list below) B = 4 digit branch code **Supported Bank Codes** ANZ - 01, 06, 11 ASB - 12 BNZ - 02 Westpac - 03 |
| Bank Account No. | Must match format CCCCCCC-DD or CCCCCCC-DDD Where CCCCCCC = 7 digit bank account number DD or DDD = 2 or 3 digit suffix |

![NZ Bank Account Westpac page](../images/NZ%20Bank%20Account%20Westpac%20page.jpg "NZ Bank Account Westpac page")

If you want to send remittances as an email attachment directly to your payees, you must configure the *Email Settings* on the *Intergen Bank Transfers Setup* page.