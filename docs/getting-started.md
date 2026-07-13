We've simplified the setup process but there are still a few things to prepare in your system before you make your first bank payment file export. You'll find everything you need to know in the Setup section, but here's a summary of the steps needed.

* The bank account you wish to pay from must have an account number for a supported bank.
* If you want to send remittances by email, you'll need to configure some settings and make sure your vendors and customers have an email address.
* You need to make sure that the vendors and customers you want to pay have a bank account in the correct format.
* You'll need to assign some new permission sets to your users so they can use the app.

## Supported File Formats

We currently support the following file formats:

* Australian Banking Association (ABA) File Format
* ANZ Bank Format
* BNZ Bank Format
* Westpac NZ Deskbank Format
* ASB Bank CSV Format
* ASB Bank MT9 Format
* Kiwibank Format

!!! info
    If your New Zealand bank isn't supported,
    [drop us a line](mailto:support.nz@capgemini.com?subject=Capgemini BC Add-on Bank Transfers: Request for new bank account format.)
    and we'll see if we can add it in a future release.

The file formats you will be able to select from are determined by the format of the bank account number you are paying from.

## New Zealand Bank Account

When you make a payment export, the system will only allow payment from a bank account with a *Bank Branch No.* and *Bank Account No.* in the correct format and with a bank code (the first two digits of the *Bank Branch No.*) from a supported bank.

| Bank Code | Bank Name |
| --- | --- |
| **01, 06 or 11** | ANZ |
| **02** | BNZ |
| **03** | Westpac |
| **12** | ASB |
| **38** | Kiwibank |

A New Zealand bank account must be in the format of either:

AA-BBBB-CCCCCCC-DD  
or  
AA-BBBB-CCCCCCC-DDD

Where:

AA = A two-digit bank code.  
BBBB = A four-digit branch number.  
CCCCCCC = A seven-digit account number.  
DD or DDD = A two- or three-digit suffix.

Only 0123456789- characters may be used.

You must separate the bank code, branch number, account number, and suffix with a hyphen (-), but it is up to you whether you enter the full account number in the *Bank Account No.* field or split the full bank account into a *Bank Branch No.* and *Bank Account No.*.

!!! info
    You can enter New Zealand bank account numbers in two fields (Bank Branch No. and Bank Account No.) or in a single field (Bank Account No.)

The following table shows how you can enter the bank account as either one or two fields.

| Entered As | Bank Branch No. | Bank Account No. | Bank |
| --- | --- | --- | --- |
| **Two fields** | 12-1234 | 1234567-00 | ASB |
| **One field** |  | 12-1234-1234567-00 | ASB |
| **Two fields** | 01-4321 | 7654321-00 | ANZ |
| **One field** |  | 01-4321-7654321-00 | ANZ |

!!! warning
    We don't validate your account number when it's entered into the Bank Account fields, but if you don't use the correct format your bank account will not be available for payments.

## Australian Bank Account

An Australian bank account must be in the following format:

AAB-CCC-DDDDDDDDD

Where:

AA = A two-digit bank code.  
B = A one-digit state code.  
CCC = A three-digit branch location code.  
DDDDDDDDD = An account number of up to nine-digits.

Only 0123456789- characters may be used.

If a bank account matches the required format it will be available for payments.
