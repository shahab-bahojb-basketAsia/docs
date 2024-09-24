# Documentation for Xero Accounting API

<a name="documentation-for-api-endpoints"></a>
## Documentation for API Endpoints

All URIs are relative to *https://api.xero.com/api.xro/2.0*

| Class | Method | HTTP request | Description |
|------------ | ------------- | ------------- | -------------|
| *AccountingApi* | [**createAccount**](Apis/AccountingApi.md#createaccount) | **PUT** /Accounts | Creates a new chart of accounts |
*AccountingApi* | [**createAccountAttachmentByFileName**](Apis/AccountingApi.md#createaccountattachmentbyfilename) | **PUT** /Accounts/{AccountID}/Attachments/{FileName} | Creates an attachment on a specific account |
*AccountingApi* | [**createBankTransactionAttachmentByFileName**](Apis/AccountingApi.md#createbanktransactionattachmentbyfilename) | **PUT** /BankTransactions/{BankTransactionID}/Attachments/{FileName} | Creates an attachment for a specific bank transaction by filename |
*AccountingApi* | [**createBankTransactionHistoryRecord**](Apis/AccountingApi.md#createbanktransactionhistoryrecord) | **PUT** /BankTransactions/{BankTransactionID}/History | Creates a history record for a specific bank transactions |
*AccountingApi* | [**createBankTransactions**](Apis/AccountingApi.md#createbanktransactions) | **PUT** /BankTransactions | Creates one or more spent or received money transaction |
*AccountingApi* | [**createBankTransfer**](Apis/AccountingApi.md#createbanktransfer) | **PUT** /BankTransfers | Creates a bank transfer |
*AccountingApi* | [**createBankTransferAttachmentByFileName**](Apis/AccountingApi.md#createbanktransferattachmentbyfilename) | **PUT** /BankTransfers/{BankTransferID}/Attachments/{FileName} |  |
*AccountingApi* | [**createBankTransferHistoryRecord**](Apis/AccountingApi.md#createbanktransferhistoryrecord) | **PUT** /BankTransfers/{BankTransferID}/History | Creates a history record for a specific bank transfer |
*AccountingApi* | [**createBatchPayment**](Apis/AccountingApi.md#createbatchpayment) | **PUT** /BatchPayments | Creates one or many batch payments for invoices |
*AccountingApi* | [**createBatchPaymentHistoryRecord**](Apis/AccountingApi.md#createbatchpaymenthistoryrecord) | **PUT** /BatchPayments/{BatchPaymentID}/History | Creates a history record for a specific batch payment |
*AccountingApi* | [**createBrandingThemePaymentServices**](Apis/AccountingApi.md#createbrandingthemepaymentservices) | **POST** /BrandingThemes/{BrandingThemeID}/PaymentServices | Creates a new custom payment service for a specific branding theme |
*AccountingApi* | [**createContactAttachmentByFileName**](Apis/AccountingApi.md#createcontactattachmentbyfilename) | **PUT** /Contacts/{ContactID}/Attachments/{FileName} |  |
*AccountingApi* | [**createContactGroup**](Apis/AccountingApi.md#createcontactgroup) | **PUT** /ContactGroups | Creates a contact group |
*AccountingApi* | [**createContactGroupContacts**](Apis/AccountingApi.md#createcontactgroupcontacts) | **PUT** /ContactGroups/{ContactGroupID}/Contacts | Creates contacts to a specific contact group |
*AccountingApi* | [**createContactHistory**](Apis/AccountingApi.md#createcontacthistory) | **PUT** /Contacts/{ContactID}/History | Creates a new history record for a specific contact |
*AccountingApi* | [**createContacts**](Apis/AccountingApi.md#createcontacts) | **PUT** /Contacts | Creates multiple contacts (bulk) in a Xero organisation |
*AccountingApi* | [**createCreditNoteAllocation**](Apis/AccountingApi.md#createcreditnoteallocation) | **PUT** /CreditNotes/{CreditNoteID}/Allocations | Creates allocation for a specific credit note |
*AccountingApi* | [**createCreditNoteAttachmentByFileName**](Apis/AccountingApi.md#createcreditnoteattachmentbyfilename) | **PUT** /CreditNotes/{CreditNoteID}/Attachments/{FileName} | Creates an attachment for a specific credit note |
*AccountingApi* | [**createCreditNoteHistory**](Apis/AccountingApi.md#createcreditnotehistory) | **PUT** /CreditNotes/{CreditNoteID}/History | Retrieves history records of a specific credit note |
*AccountingApi* | [**createCreditNotes**](Apis/AccountingApi.md#createcreditnotes) | **PUT** /CreditNotes | Creates a new credit note |
*AccountingApi* | [**createCurrency**](Apis/AccountingApi.md#createcurrency) | **PUT** /Currencies | Create a new currency for a Xero organisation |
*AccountingApi* | [**createEmployees**](Apis/AccountingApi.md#createemployees) | **PUT** /Employees | Creates new employees used in Xero payrun |
*AccountingApi* | [**createExpenseClaimHistory**](Apis/AccountingApi.md#createexpenseclaimhistory) | **PUT** /ExpenseClaims/{ExpenseClaimID}/History | Creates a history record for a specific expense claim |
*AccountingApi* | [**createExpenseClaims**](Apis/AccountingApi.md#createexpenseclaims) | **PUT** /ExpenseClaims | Creates expense claims |
*AccountingApi* | [**createInvoiceAttachmentByFileName**](Apis/AccountingApi.md#createinvoiceattachmentbyfilename) | **PUT** /Invoices/{InvoiceID}/Attachments/{FileName} | Creates an attachment for a specific invoice or purchase bill by filename |
*AccountingApi* | [**createInvoiceHistory**](Apis/AccountingApi.md#createinvoicehistory) | **PUT** /Invoices/{InvoiceID}/History | Creates a history record for a specific invoice |
*AccountingApi* | [**createInvoices**](Apis/AccountingApi.md#createinvoices) | **PUT** /Invoices | Creates one or more sales invoices or purchase bills |
*AccountingApi* | [**createItemHistory**](Apis/AccountingApi.md#createitemhistory) | **PUT** /Items/{ItemID}/History | Creates a history record for a specific item |
*AccountingApi* | [**createItems**](Apis/AccountingApi.md#createitems) | **PUT** /Items | Creates one or more items |
*AccountingApi* | [**createLinkedTransaction**](Apis/AccountingApi.md#createlinkedtransaction) | **PUT** /LinkedTransactions | Creates linked transactions (billable expenses) |
*AccountingApi* | [**createManualJournalAttachmentByFileName**](Apis/AccountingApi.md#createmanualjournalattachmentbyfilename) | **PUT** /ManualJournals/{ManualJournalID}/Attachments/{FileName} | Creates a specific attachment for a specific manual journal by file name |
*AccountingApi* | [**createManualJournalHistoryRecord**](Apis/AccountingApi.md#createmanualjournalhistoryrecord) | **PUT** /ManualJournals/{ManualJournalID}/History | Creates a history record for a specific manual journal |
*AccountingApi* | [**createManualJournals**](Apis/AccountingApi.md#createmanualjournals) | **PUT** /ManualJournals | Creates one or more manual journals |
*AccountingApi* | [**createOverpaymentAllocations**](Apis/AccountingApi.md#createoverpaymentallocations) | **PUT** /Overpayments/{OverpaymentID}/Allocations | Creates a single allocation for a specific overpayment |
*AccountingApi* | [**createOverpaymentHistory**](Apis/AccountingApi.md#createoverpaymenthistory) | **PUT** /Overpayments/{OverpaymentID}/History | Creates a history record for a specific overpayment |
*AccountingApi* | [**createPayment**](Apis/AccountingApi.md#createpayment) | **POST** /Payments | Creates a single payment for invoice or credit notes |
*AccountingApi* | [**createPaymentHistory**](Apis/AccountingApi.md#createpaymenthistory) | **PUT** /Payments/{PaymentID}/History | Creates a history record for a specific payment |
*AccountingApi* | [**createPaymentService**](Apis/AccountingApi.md#createpaymentservice) | **PUT** /PaymentServices | Creates a payment service |
*AccountingApi* | [**createPayments**](Apis/AccountingApi.md#createpayments) | **PUT** /Payments | Creates multiple payments for invoices or credit notes |
*AccountingApi* | [**createPrepaymentAllocations**](Apis/AccountingApi.md#createprepaymentallocations) | **PUT** /Prepayments/{PrepaymentID}/Allocations | Allows you to create an Allocation for prepayments |
*AccountingApi* | [**createPrepaymentHistory**](Apis/AccountingApi.md#createprepaymenthistory) | **PUT** /Prepayments/{PrepaymentID}/History | Creates a history record for a specific prepayment |
*AccountingApi* | [**createPurchaseOrderAttachmentByFileName**](Apis/AccountingApi.md#createpurchaseorderattachmentbyfilename) | **PUT** /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName} | Creates attachment for a specific purchase order |
*AccountingApi* | [**createPurchaseOrderHistory**](Apis/AccountingApi.md#createpurchaseorderhistory) | **PUT** /PurchaseOrders/{PurchaseOrderID}/History | Creates a history record for a specific purchase orders |
*AccountingApi* | [**createPurchaseOrders**](Apis/AccountingApi.md#createpurchaseorders) | **PUT** /PurchaseOrders | Creates one or more purchase orders |
*AccountingApi* | [**createQuoteAttachmentByFileName**](Apis/AccountingApi.md#createquoteattachmentbyfilename) | **PUT** /Quotes/{QuoteID}/Attachments/{FileName} | Creates attachment for a specific quote |
*AccountingApi* | [**createQuoteHistory**](Apis/AccountingApi.md#createquotehistory) | **PUT** /Quotes/{QuoteID}/History | Creates a history record for a specific quote |
*AccountingApi* | [**createQuotes**](Apis/AccountingApi.md#createquotes) | **PUT** /Quotes | Create one or more quotes |
*AccountingApi* | [**createReceipt**](Apis/AccountingApi.md#createreceipt) | **PUT** /Receipts | Creates draft expense claim receipts for any user |
*AccountingApi* | [**createReceiptAttachmentByFileName**](Apis/AccountingApi.md#createreceiptattachmentbyfilename) | **PUT** /Receipts/{ReceiptID}/Attachments/{FileName} | Creates an attachment on a specific expense claim receipts by file name |
*AccountingApi* | [**createReceiptHistory**](Apis/AccountingApi.md#createreceipthistory) | **PUT** /Receipts/{ReceiptID}/History | Creates a history record for a specific receipt |
*AccountingApi* | [**createRepeatingInvoiceAttachmentByFileName**](Apis/AccountingApi.md#createrepeatinginvoiceattachmentbyfilename) | **PUT** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName} | Creates an attachment from a specific repeating invoices by file name |
*AccountingApi* | [**createRepeatingInvoiceHistory**](Apis/AccountingApi.md#createrepeatinginvoicehistory) | **PUT** /RepeatingInvoices/{RepeatingInvoiceID}/History | Creates a  history record for a specific repeating invoice |
*AccountingApi* | [**createRepeatingInvoices**](Apis/AccountingApi.md#createrepeatinginvoices) | **PUT** /RepeatingInvoices | Creates one or more repeating invoice templates |
*AccountingApi* | [**createTaxRates**](Apis/AccountingApi.md#createtaxrates) | **PUT** /TaxRates | Creates one or more tax rates |
*AccountingApi* | [**createTrackingCategory**](Apis/AccountingApi.md#createtrackingcategory) | **PUT** /TrackingCategories | Create tracking categories |
*AccountingApi* | [**createTrackingOptions**](Apis/AccountingApi.md#createtrackingoptions) | **PUT** /TrackingCategories/{TrackingCategoryID}/Options | Creates options for a specific tracking category |
*AccountingApi* | [**deleteAccount**](Apis/AccountingApi.md#deleteaccount) | **DELETE** /Accounts/{AccountID} | Deletes a chart of accounts |
*AccountingApi* | [**deleteBatchPayment**](Apis/AccountingApi.md#deletebatchpayment) | **POST** /BatchPayments | Updates a specific batch payment for invoices and credit notes |
*AccountingApi* | [**deleteBatchPaymentByUrlParam**](Apis/AccountingApi.md#deletebatchpaymentbyurlparam) | **POST** /BatchPayments/{BatchPaymentID} | Updates a specific batch payment for invoices and credit notes |
*AccountingApi* | [**deleteContactGroupContact**](Apis/AccountingApi.md#deletecontactgroupcontact) | **DELETE** /ContactGroups/{ContactGroupID}/Contacts/{ContactID} | Deletes a specific contact from a contact group using a unique contact Id |
*AccountingApi* | [**deleteContactGroupContacts**](Apis/AccountingApi.md#deletecontactgroupcontacts) | **DELETE** /ContactGroups/{ContactGroupID}/Contacts | Deletes all contacts from a specific contact group |
*AccountingApi* | [**deleteCreditNoteAllocations**](Apis/AccountingApi.md#deletecreditnoteallocations) | **DELETE** /CreditNotes/{CreditNoteID}/Allocations/{AllocationID} | Deletes an Allocation from a Credit Note |
*AccountingApi* | [**deleteItem**](Apis/AccountingApi.md#deleteitem) | **DELETE** /Items/{ItemID} | Deletes a specific item |
*AccountingApi* | [**deleteLinkedTransaction**](Apis/AccountingApi.md#deletelinkedtransaction) | **DELETE** /LinkedTransactions/{LinkedTransactionID} | Deletes a specific linked transactions (billable expenses) |
*AccountingApi* | [**deleteOverpaymentAllocations**](Apis/AccountingApi.md#deleteoverpaymentallocations) | **DELETE** /Overpayments/{OverpaymentID}/Allocations/{AllocationID} | Deletes an Allocation from an overpayment |
*AccountingApi* | [**deletePayment**](Apis/AccountingApi.md#deletepayment) | **POST** /Payments/{PaymentID} | Updates a specific payment for invoices and credit notes |
*AccountingApi* | [**deletePrepaymentAllocations**](Apis/AccountingApi.md#deleteprepaymentallocations) | **DELETE** /Prepayments/{PrepaymentID}/Allocations/{AllocationID} | Deletes an Allocation from a Prepayment |
*AccountingApi* | [**deleteTrackingCategory**](Apis/AccountingApi.md#deletetrackingcategory) | **DELETE** /TrackingCategories/{TrackingCategoryID} | Deletes a specific tracking category |
*AccountingApi* | [**deleteTrackingOptions**](Apis/AccountingApi.md#deletetrackingoptions) | **DELETE** /TrackingCategories/{TrackingCategoryID}/Options/{TrackingOptionID} | Deletes a specific option for a specific tracking category |
*AccountingApi* | [**emailInvoice**](Apis/AccountingApi.md#emailinvoice) | **POST** /Invoices/{InvoiceID}/Email | Sends a copy of a specific invoice to related contact via email |
*AccountingApi* | [**getAccount**](Apis/AccountingApi.md#getaccount) | **GET** /Accounts/{AccountID} | Retrieves a single chart of accounts by using a unique account Id |
*AccountingApi* | [**getAccountAttachmentByFileName**](Apis/AccountingApi.md#getaccountattachmentbyfilename) | **GET** /Accounts/{AccountID}/Attachments/{FileName} | Retrieves an attachment for a specific account by filename |
*AccountingApi* | [**getAccountAttachmentById**](Apis/AccountingApi.md#getaccountattachmentbyid) | **GET** /Accounts/{AccountID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific account using a unique attachment Id |
*AccountingApi* | [**getAccountAttachments**](Apis/AccountingApi.md#getaccountattachments) | **GET** /Accounts/{AccountID}/Attachments | Retrieves attachments for a specific accounts by using a unique account Id |
*AccountingApi* | [**getAccounts**](Apis/AccountingApi.md#getaccounts) | **GET** /Accounts | Retrieves the full chart of accounts |
*AccountingApi* | [**getBankTransaction**](Apis/AccountingApi.md#getbanktransaction) | **GET** /BankTransactions/{BankTransactionID} | Retrieves a single spent or received money transaction by using a unique bank transaction Id |
*AccountingApi* | [**getBankTransactionAttachmentByFileName**](Apis/AccountingApi.md#getbanktransactionattachmentbyfilename) | **GET** /BankTransactions/{BankTransactionID}/Attachments/{FileName} | Retrieves a specific attachment from a specific bank transaction by filename |
*AccountingApi* | [**getBankTransactionAttachmentById**](Apis/AccountingApi.md#getbanktransactionattachmentbyid) | **GET** /BankTransactions/{BankTransactionID}/Attachments/{AttachmentID} | Retrieves specific attachments from a specific BankTransaction using a unique attachment Id |
*AccountingApi* | [**getBankTransactionAttachments**](Apis/AccountingApi.md#getbanktransactionattachments) | **GET** /BankTransactions/{BankTransactionID}/Attachments | Retrieves any attachments from a specific bank transactions |
*AccountingApi* | [**getBankTransactions**](Apis/AccountingApi.md#getbanktransactions) | **GET** /BankTransactions | Retrieves any spent or received money transactions |
*AccountingApi* | [**getBankTransactionsHistory**](Apis/AccountingApi.md#getbanktransactionshistory) | **GET** /BankTransactions/{BankTransactionID}/History | Retrieves history from a specific bank transaction using a unique bank transaction Id |
*AccountingApi* | [**getBankTransfer**](Apis/AccountingApi.md#getbanktransfer) | **GET** /BankTransfers/{BankTransferID} | Retrieves specific bank transfers by using a unique bank transfer Id |
*AccountingApi* | [**getBankTransferAttachmentByFileName**](Apis/AccountingApi.md#getbanktransferattachmentbyfilename) | **GET** /BankTransfers/{BankTransferID}/Attachments/{FileName} | Retrieves a specific attachment on a specific bank transfer by file name |
*AccountingApi* | [**getBankTransferAttachmentById**](Apis/AccountingApi.md#getbanktransferattachmentbyid) | **GET** /BankTransfers/{BankTransferID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific bank transfer using a unique attachment ID |
*AccountingApi* | [**getBankTransferAttachments**](Apis/AccountingApi.md#getbanktransferattachments) | **GET** /BankTransfers/{BankTransferID}/Attachments | Retrieves attachments from a specific bank transfer |
*AccountingApi* | [**getBankTransferHistory**](Apis/AccountingApi.md#getbanktransferhistory) | **GET** /BankTransfers/{BankTransferID}/History | Retrieves history from a specific bank transfer using a unique bank transfer Id |
*AccountingApi* | [**getBankTransfers**](Apis/AccountingApi.md#getbanktransfers) | **GET** /BankTransfers | Retrieves all bank transfers |
*AccountingApi* | [**getBatchPayment**](Apis/AccountingApi.md#getbatchpayment) | **GET** /BatchPayments/{BatchPaymentID} | Retrieves a specific batch payment using a unique batch payment Id |
*AccountingApi* | [**getBatchPaymentHistory**](Apis/AccountingApi.md#getbatchpaymenthistory) | **GET** /BatchPayments/{BatchPaymentID}/History | Retrieves history from a specific batch payment |
*AccountingApi* | [**getBatchPayments**](Apis/AccountingApi.md#getbatchpayments) | **GET** /BatchPayments | Retrieves either one or many batch payments for invoices |
*AccountingApi* | [**getBrandingTheme**](Apis/AccountingApi.md#getbrandingtheme) | **GET** /BrandingThemes/{BrandingThemeID} | Retrieves a specific branding theme using a unique branding theme Id |
*AccountingApi* | [**getBrandingThemePaymentServices**](Apis/AccountingApi.md#getbrandingthemepaymentservices) | **GET** /BrandingThemes/{BrandingThemeID}/PaymentServices | Retrieves the payment services for a specific branding theme |
*AccountingApi* | [**getBrandingThemes**](Apis/AccountingApi.md#getbrandingthemes) | **GET** /BrandingThemes | Retrieves all the branding themes |
*AccountingApi* | [**getBudget**](Apis/AccountingApi.md#getbudget) | **GET** /Budgets/{BudgetID} | Retrieves a specific budget, which includes budget lines |
*AccountingApi* | [**getBudgets**](Apis/AccountingApi.md#getbudgets) | **GET** /Budgets | Retrieve a list of budgets |
*AccountingApi* | [**getContact**](Apis/AccountingApi.md#getcontact) | **GET** /Contacts/{ContactID} | Retrieves a specific contacts in a Xero organisation using a unique contact Id |
*AccountingApi* | [**getContactAttachmentByFileName**](Apis/AccountingApi.md#getcontactattachmentbyfilename) | **GET** /Contacts/{ContactID}/Attachments/{FileName} | Retrieves a specific attachment from a specific contact by file name |
*AccountingApi* | [**getContactAttachmentById**](Apis/AccountingApi.md#getcontactattachmentbyid) | **GET** /Contacts/{ContactID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific contact using a unique attachment Id |
*AccountingApi* | [**getContactAttachments**](Apis/AccountingApi.md#getcontactattachments) | **GET** /Contacts/{ContactID}/Attachments | Retrieves attachments for a specific contact in a Xero organisation |
*AccountingApi* | [**getContactByContactNumber**](Apis/AccountingApi.md#getcontactbycontactnumber) | **GET** /Contacts/{ContactNumber} | Retrieves a specific contact by contact number in a Xero organisation |
*AccountingApi* | [**getContactCISSettings**](Apis/AccountingApi.md#getcontactcissettings) | **GET** /Contacts/{ContactID}/CISSettings | Retrieves CIS settings for a specific contact in a Xero organisation |
*AccountingApi* | [**getContactGroup**](Apis/AccountingApi.md#getcontactgroup) | **GET** /ContactGroups/{ContactGroupID} | Retrieves a specific contact group by using a unique contact group Id |
*AccountingApi* | [**getContactGroups**](Apis/AccountingApi.md#getcontactgroups) | **GET** /ContactGroups | Retrieves the contact Id and name of each contact group |
*AccountingApi* | [**getContactHistory**](Apis/AccountingApi.md#getcontacthistory) | **GET** /Contacts/{ContactID}/History | Retrieves history records for a specific contact |
*AccountingApi* | [**getContacts**](Apis/AccountingApi.md#getcontacts) | **GET** /Contacts | Retrieves all contacts in a Xero organisation |
*AccountingApi* | [**getCreditNote**](Apis/AccountingApi.md#getcreditnote) | **GET** /CreditNotes/{CreditNoteID} | Retrieves a specific credit note using a unique credit note Id |
*AccountingApi* | [**getCreditNoteAsPdf**](Apis/AccountingApi.md#getcreditnoteaspdf) | **GET** /CreditNotes/{CreditNoteID}/pdf | Retrieves credit notes as PDF files |
*AccountingApi* | [**getCreditNoteAttachmentByFileName**](Apis/AccountingApi.md#getcreditnoteattachmentbyfilename) | **GET** /CreditNotes/{CreditNoteID}/Attachments/{FileName} | Retrieves a specific attachment on a specific credit note by file name |
*AccountingApi* | [**getCreditNoteAttachmentById**](Apis/AccountingApi.md#getcreditnoteattachmentbyid) | **GET** /CreditNotes/{CreditNoteID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific credit note using a unique attachment Id |
*AccountingApi* | [**getCreditNoteAttachments**](Apis/AccountingApi.md#getcreditnoteattachments) | **GET** /CreditNotes/{CreditNoteID}/Attachments | Retrieves attachments for a specific credit notes |
*AccountingApi* | [**getCreditNoteHistory**](Apis/AccountingApi.md#getcreditnotehistory) | **GET** /CreditNotes/{CreditNoteID}/History | Retrieves history records of a specific credit note |
*AccountingApi* | [**getCreditNotes**](Apis/AccountingApi.md#getcreditnotes) | **GET** /CreditNotes | Retrieves any credit notes |
*AccountingApi* | [**getCurrencies**](Apis/AccountingApi.md#getcurrencies) | **GET** /Currencies | Retrieves currencies for your Xero organisation |
*AccountingApi* | [**getEmployee**](Apis/AccountingApi.md#getemployee) | **GET** /Employees/{EmployeeID} | Retrieves a specific employee used in Xero payrun using a unique employee Id |
*AccountingApi* | [**getEmployees**](Apis/AccountingApi.md#getemployees) | **GET** /Employees | Retrieves employees used in Xero payrun |
*AccountingApi* | [**getExpenseClaim**](Apis/AccountingApi.md#getexpenseclaim) | **GET** /ExpenseClaims/{ExpenseClaimID} | Retrieves a specific expense claim using a unique expense claim Id |
*AccountingApi* | [**getExpenseClaimHistory**](Apis/AccountingApi.md#getexpenseclaimhistory) | **GET** /ExpenseClaims/{ExpenseClaimID}/History | Retrieves history records of a specific expense claim |
*AccountingApi* | [**getExpenseClaims**](Apis/AccountingApi.md#getexpenseclaims) | **GET** /ExpenseClaims | Retrieves expense claims |
*AccountingApi* | [**getInvoice**](Apis/AccountingApi.md#getinvoice) | **GET** /Invoices/{InvoiceID} | Retrieves a specific sales invoice or purchase bill using a unique invoice Id |
*AccountingApi* | [**getInvoiceAsPdf**](Apis/AccountingApi.md#getinvoiceaspdf) | **GET** /Invoices/{InvoiceID}/pdf | Retrieves invoices or purchase bills as PDF files |
*AccountingApi* | [**getInvoiceAttachmentByFileName**](Apis/AccountingApi.md#getinvoiceattachmentbyfilename) | **GET** /Invoices/{InvoiceID}/Attachments/{FileName} | Retrieves an attachment from a specific invoice or purchase bill by filename |
*AccountingApi* | [**getInvoiceAttachmentById**](Apis/AccountingApi.md#getinvoiceattachmentbyid) | **GET** /Invoices/{InvoiceID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific invoices or purchase bills by using a unique attachment Id |
*AccountingApi* | [**getInvoiceAttachments**](Apis/AccountingApi.md#getinvoiceattachments) | **GET** /Invoices/{InvoiceID}/Attachments | Retrieves attachments for a specific invoice or purchase bill |
*AccountingApi* | [**getInvoiceHistory**](Apis/AccountingApi.md#getinvoicehistory) | **GET** /Invoices/{InvoiceID}/History | Retrieves history records for a specific invoice |
*AccountingApi* | [**getInvoiceReminders**](Apis/AccountingApi.md#getinvoicereminders) | **GET** /InvoiceReminders/Settings | Retrieves invoice reminder settings |
*AccountingApi* | [**getInvoices**](Apis/AccountingApi.md#getinvoices) | **GET** /Invoices | Retrieves sales invoices or purchase bills |
*AccountingApi* | [**getItem**](Apis/AccountingApi.md#getitem) | **GET** /Items/{ItemID} | Retrieves a specific item using a unique item Id |
*AccountingApi* | [**getItemHistory**](Apis/AccountingApi.md#getitemhistory) | **GET** /Items/{ItemID}/History | Retrieves history for a specific item |
*AccountingApi* | [**getItems**](Apis/AccountingApi.md#getitems) | **GET** /Items | Retrieves items |
*AccountingApi* | [**getJournal**](Apis/AccountingApi.md#getjournal) | **GET** /Journals/{JournalID} | Retrieves a specific journal using a unique journal Id. |
*AccountingApi* | [**getJournalByNumber**](Apis/AccountingApi.md#getjournalbynumber) | **GET** /Journals/{JournalNumber} | Retrieves a specific journal using a unique journal number. |
*AccountingApi* | [**getJournals**](Apis/AccountingApi.md#getjournals) | **GET** /Journals | Retrieves journals |
*AccountingApi* | [**getLinkedTransaction**](Apis/AccountingApi.md#getlinkedtransaction) | **GET** /LinkedTransactions/{LinkedTransactionID} | Retrieves a specific linked transaction (billable expenses) using a unique linked transaction Id |
*AccountingApi* | [**getLinkedTransactions**](Apis/AccountingApi.md#getlinkedtransactions) | **GET** /LinkedTransactions | Retrieves linked transactions (billable expenses) |
*AccountingApi* | [**getManualJournal**](Apis/AccountingApi.md#getmanualjournal) | **GET** /ManualJournals/{ManualJournalID} | Retrieves a specific manual journal |
*AccountingApi* | [**getManualJournalAttachmentByFileName**](Apis/AccountingApi.md#getmanualjournalattachmentbyfilename) | **GET** /ManualJournals/{ManualJournalID}/Attachments/{FileName} | Retrieves a specific attachment from a specific manual journal by file name |
*AccountingApi* | [**getManualJournalAttachmentById**](Apis/AccountingApi.md#getmanualjournalattachmentbyid) | **GET** /ManualJournals/{ManualJournalID}/Attachments/{AttachmentID} | Allows you to retrieve a specific attachment from a specific manual journal using a unique attachment Id |
*AccountingApi* | [**getManualJournalAttachments**](Apis/AccountingApi.md#getmanualjournalattachments) | **GET** /ManualJournals/{ManualJournalID}/Attachments | Retrieves attachment for a specific manual journal |
*AccountingApi* | [**getManualJournals**](Apis/AccountingApi.md#getmanualjournals) | **GET** /ManualJournals | Retrieves manual journals |
*AccountingApi* | [**getManualJournalsHistory**](Apis/AccountingApi.md#getmanualjournalshistory) | **GET** /ManualJournals/{ManualJournalID}/History | Retrieves history for a specific manual journal |
*AccountingApi* | [**getOnlineInvoice**](Apis/AccountingApi.md#getonlineinvoice) | **GET** /Invoices/{InvoiceID}/OnlineInvoice | Retrieves a URL to an online invoice |
*AccountingApi* | [**getOrganisationActions**](Apis/AccountingApi.md#getorganisationactions) | **GET** /Organisation/Actions | Retrieves a list of the key actions your app has permission to perform in the connected Xero organisation. |
*AccountingApi* | [**getOrganisationCISSettings**](Apis/AccountingApi.md#getorganisationcissettings) | **GET** /Organisation/{OrganisationID}/CISSettings | Retrieves the CIS settings for the Xero organistaion. |
*AccountingApi* | [**getOrganisations**](Apis/AccountingApi.md#getorganisations) | **GET** /Organisation | Retrieves Xero organisation details |
*AccountingApi* | [**getOverpayment**](Apis/AccountingApi.md#getoverpayment) | **GET** /Overpayments/{OverpaymentID} | Retrieves a specific overpayment using a unique overpayment Id |
*AccountingApi* | [**getOverpaymentHistory**](Apis/AccountingApi.md#getoverpaymenthistory) | **GET** /Overpayments/{OverpaymentID}/History | Retrieves history records of a specific overpayment |
*AccountingApi* | [**getOverpayments**](Apis/AccountingApi.md#getoverpayments) | **GET** /Overpayments | Retrieves overpayments |
*AccountingApi* | [**getPayment**](Apis/AccountingApi.md#getpayment) | **GET** /Payments/{PaymentID} | Retrieves a specific payment for invoices and credit notes using a unique payment Id |
*AccountingApi* | [**getPaymentHistory**](Apis/AccountingApi.md#getpaymenthistory) | **GET** /Payments/{PaymentID}/History | Retrieves history records of a specific payment |
*AccountingApi* | [**getPaymentServices**](Apis/AccountingApi.md#getpaymentservices) | **GET** /PaymentServices | Retrieves payment services |
*AccountingApi* | [**getPayments**](Apis/AccountingApi.md#getpayments) | **GET** /Payments | Retrieves payments for invoices and credit notes |
*AccountingApi* | [**getPrepayment**](Apis/AccountingApi.md#getprepayment) | **GET** /Prepayments/{PrepaymentID} | Allows you to retrieve a specified prepayments |
*AccountingApi* | [**getPrepaymentHistory**](Apis/AccountingApi.md#getprepaymenthistory) | **GET** /Prepayments/{PrepaymentID}/History | Retrieves history record for a specific prepayment |
*AccountingApi* | [**getPrepayments**](Apis/AccountingApi.md#getprepayments) | **GET** /Prepayments | Retrieves prepayments |
*AccountingApi* | [**getPurchaseOrder**](Apis/AccountingApi.md#getpurchaseorder) | **GET** /PurchaseOrders/{PurchaseOrderID} | Retrieves a specific purchase order using a unique purchase order Id |
*AccountingApi* | [**getPurchaseOrderAsPdf**](Apis/AccountingApi.md#getpurchaseorderaspdf) | **GET** /PurchaseOrders/{PurchaseOrderID}/pdf | Retrieves specific purchase order as PDF files using a unique purchase order Id |
*AccountingApi* | [**getPurchaseOrderAttachmentByFileName**](Apis/AccountingApi.md#getpurchaseorderattachmentbyfilename) | **GET** /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName} | Retrieves a specific attachment for a specific purchase order by filename |
*AccountingApi* | [**getPurchaseOrderAttachmentById**](Apis/AccountingApi.md#getpurchaseorderattachmentbyid) | **GET** /PurchaseOrders/{PurchaseOrderID}/Attachments/{AttachmentID} | Retrieves specific attachment for a specific purchase order using a unique attachment Id |
*AccountingApi* | [**getPurchaseOrderAttachments**](Apis/AccountingApi.md#getpurchaseorderattachments) | **GET** /PurchaseOrders/{PurchaseOrderID}/Attachments | Retrieves attachments for a specific purchase order |
*AccountingApi* | [**getPurchaseOrderByNumber**](Apis/AccountingApi.md#getpurchaseorderbynumber) | **GET** /PurchaseOrders/{PurchaseOrderNumber} | Retrieves a specific purchase order using purchase order number |
*AccountingApi* | [**getPurchaseOrderHistory**](Apis/AccountingApi.md#getpurchaseorderhistory) | **GET** /PurchaseOrders/{PurchaseOrderID}/History | Retrieves history for a specific purchase order |
*AccountingApi* | [**getPurchaseOrders**](Apis/AccountingApi.md#getpurchaseorders) | **GET** /PurchaseOrders | Retrieves purchase orders |
*AccountingApi* | [**getQuote**](Apis/AccountingApi.md#getquote) | **GET** /Quotes/{QuoteID} | Retrieves a specific quote using a unique quote Id |
*AccountingApi* | [**getQuoteAsPdf**](Apis/AccountingApi.md#getquoteaspdf) | **GET** /Quotes/{QuoteID}/pdf | Retrieves a specific quote as a PDF file using a unique quote Id |
*AccountingApi* | [**getQuoteAttachmentByFileName**](Apis/AccountingApi.md#getquoteattachmentbyfilename) | **GET** /Quotes/{QuoteID}/Attachments/{FileName} | Retrieves a specific attachment from a specific quote by filename |
*AccountingApi* | [**getQuoteAttachmentById**](Apis/AccountingApi.md#getquoteattachmentbyid) | **GET** /Quotes/{QuoteID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific quote using a unique attachment Id |
*AccountingApi* | [**getQuoteAttachments**](Apis/AccountingApi.md#getquoteattachments) | **GET** /Quotes/{QuoteID}/Attachments | Retrieves attachments for a specific quote |
*AccountingApi* | [**getQuoteHistory**](Apis/AccountingApi.md#getquotehistory) | **GET** /Quotes/{QuoteID}/History | Retrieves history records of a specific quote |
*AccountingApi* | [**getQuotes**](Apis/AccountingApi.md#getquotes) | **GET** /Quotes | Retrieves sales quotes |
*AccountingApi* | [**getReceipt**](Apis/AccountingApi.md#getreceipt) | **GET** /Receipts/{ReceiptID} | Retrieves a specific draft expense claim receipt by using a unique receipt Id |
*AccountingApi* | [**getReceiptAttachmentByFileName**](Apis/AccountingApi.md#getreceiptattachmentbyfilename) | **GET** /Receipts/{ReceiptID}/Attachments/{FileName} | Retrieves a specific attachment from a specific expense claim receipts by file name |
*AccountingApi* | [**getReceiptAttachmentById**](Apis/AccountingApi.md#getreceiptattachmentbyid) | **GET** /Receipts/{ReceiptID}/Attachments/{AttachmentID} | Retrieves a specific attachments from a specific expense claim receipts by using a unique attachment Id |
*AccountingApi* | [**getReceiptAttachments**](Apis/AccountingApi.md#getreceiptattachments) | **GET** /Receipts/{ReceiptID}/Attachments | Retrieves attachments for a specific expense claim receipt |
*AccountingApi* | [**getReceiptHistory**](Apis/AccountingApi.md#getreceipthistory) | **GET** /Receipts/{ReceiptID}/History | Retrieves a history record for a specific receipt |
*AccountingApi* | [**getReceipts**](Apis/AccountingApi.md#getreceipts) | **GET** /Receipts | Retrieves draft expense claim receipts for any user |
*AccountingApi* | [**getRepeatingInvoice**](Apis/AccountingApi.md#getrepeatinginvoice) | **GET** /RepeatingInvoices/{RepeatingInvoiceID} | Retrieves a specific repeating invoice by using a unique repeating invoice Id |
*AccountingApi* | [**getRepeatingInvoiceAttachmentByFileName**](Apis/AccountingApi.md#getrepeatinginvoiceattachmentbyfilename) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName} | Retrieves a specific attachment from a specific repeating invoices by file name |
*AccountingApi* | [**getRepeatingInvoiceAttachmentById**](Apis/AccountingApi.md#getrepeatinginvoiceattachmentbyid) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific repeating invoice |
*AccountingApi* | [**getRepeatingInvoiceAttachments**](Apis/AccountingApi.md#getrepeatinginvoiceattachments) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments | Retrieves attachments from a specific repeating invoice |
*AccountingApi* | [**getRepeatingInvoiceHistory**](Apis/AccountingApi.md#getrepeatinginvoicehistory) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/History | Retrieves history record for a specific repeating invoice |
*AccountingApi* | [**getRepeatingInvoices**](Apis/AccountingApi.md#getrepeatinginvoices) | **GET** /RepeatingInvoices | Retrieves repeating invoices |
*AccountingApi* | [**getReportAgedPayablesByContact**](Apis/AccountingApi.md#getreportagedpayablesbycontact) | **GET** /Reports/AgedPayablesByContact | Retrieves report for aged payables by contact |
*AccountingApi* | [**getReportAgedReceivablesByContact**](Apis/AccountingApi.md#getreportagedreceivablesbycontact) | **GET** /Reports/AgedReceivablesByContact | Retrieves report for aged receivables by contact |
*AccountingApi* | [**getReportBalanceSheet**](Apis/AccountingApi.md#getreportbalancesheet) | **GET** /Reports/BalanceSheet | Retrieves report for balancesheet |
*AccountingApi* | [**getReportBankSummary**](Apis/AccountingApi.md#getreportbanksummary) | **GET** /Reports/BankSummary | Retrieves report for bank summary |
*AccountingApi* | [**getReportBudgetSummary**](Apis/AccountingApi.md#getreportbudgetsummary) | **GET** /Reports/BudgetSummary | Retrieves report for budget summary |
*AccountingApi* | [**getReportExecutiveSummary**](Apis/AccountingApi.md#getreportexecutivesummary) | **GET** /Reports/ExecutiveSummary | Retrieves report for executive summary |
*AccountingApi* | [**getReportFromId**](Apis/AccountingApi.md#getreportfromid) | **GET** /Reports/{ReportID} | Retrieves a specific report using a unique ReportID |
*AccountingApi* | [**getReportProfitAndLoss**](Apis/AccountingApi.md#getreportprofitandloss) | **GET** /Reports/ProfitAndLoss | Retrieves report for profit and loss |
*AccountingApi* | [**getReportTenNinetyNine**](Apis/AccountingApi.md#getreporttenninetynine) | **GET** /Reports/TenNinetyNine | Retrieve reports for 1099 |
*AccountingApi* | [**getReportTrialBalance**](Apis/AccountingApi.md#getreporttrialbalance) | **GET** /Reports/TrialBalance | Retrieves report for trial balance |
*AccountingApi* | [**getReportsList**](Apis/AccountingApi.md#getreportslist) | **GET** /Reports | Retrieves a list of the organistaions unique reports that require a uuid to fetch |
*AccountingApi* | [**getTaxRateByTaxType**](Apis/AccountingApi.md#gettaxratebytaxtype) | **GET** /TaxRates/{TaxType} | Retrieves a specific tax rate according to given TaxType code |
*AccountingApi* | [**getTaxRates**](Apis/AccountingApi.md#gettaxrates) | **GET** /TaxRates | Retrieves tax rates |
*AccountingApi* | [**getTrackingCategories**](Apis/AccountingApi.md#gettrackingcategories) | **GET** /TrackingCategories | Retrieves tracking categories and options |
*AccountingApi* | [**getTrackingCategory**](Apis/AccountingApi.md#gettrackingcategory) | **GET** /TrackingCategories/{TrackingCategoryID} | Retrieves specific tracking categories and options using a unique tracking category Id |
*AccountingApi* | [**getUser**](Apis/AccountingApi.md#getuser) | **GET** /Users/{UserID} | Retrieves a specific user |
*AccountingApi* | [**getUsers**](Apis/AccountingApi.md#getusers) | **GET** /Users | Retrieves users |
*AccountingApi* | [**postSetup**](Apis/AccountingApi.md#postsetup) | **POST** /Setup | Sets the chart of accounts, the conversion date and conversion balances |
*AccountingApi* | [**updateAccount**](Apis/AccountingApi.md#updateaccount) | **POST** /Accounts/{AccountID} | Updates a chart of accounts |
*AccountingApi* | [**updateAccountAttachmentByFileName**](Apis/AccountingApi.md#updateaccountattachmentbyfilename) | **POST** /Accounts/{AccountID}/Attachments/{FileName} | Updates attachment on a specific account by filename |
*AccountingApi* | [**updateBankTransaction**](Apis/AccountingApi.md#updatebanktransaction) | **POST** /BankTransactions/{BankTransactionID} | Updates a single spent or received money transaction |
*AccountingApi* | [**updateBankTransactionAttachmentByFileName**](Apis/AccountingApi.md#updatebanktransactionattachmentbyfilename) | **POST** /BankTransactions/{BankTransactionID}/Attachments/{FileName} | Updates a specific attachment from a specific bank transaction by filename |
*AccountingApi* | [**updateBankTransferAttachmentByFileName**](Apis/AccountingApi.md#updatebanktransferattachmentbyfilename) | **POST** /BankTransfers/{BankTransferID}/Attachments/{FileName} |  |
*AccountingApi* | [**updateContact**](Apis/AccountingApi.md#updatecontact) | **POST** /Contacts/{ContactID} | Updates a specific contact in a Xero organisation |
*AccountingApi* | [**updateContactAttachmentByFileName**](Apis/AccountingApi.md#updatecontactattachmentbyfilename) | **POST** /Contacts/{ContactID}/Attachments/{FileName} |  |
*AccountingApi* | [**updateContactGroup**](Apis/AccountingApi.md#updatecontactgroup) | **POST** /ContactGroups/{ContactGroupID} | Updates a specific contact group |
*AccountingApi* | [**updateCreditNote**](Apis/AccountingApi.md#updatecreditnote) | **POST** /CreditNotes/{CreditNoteID} | Updates a specific credit note |
*AccountingApi* | [**updateCreditNoteAttachmentByFileName**](Apis/AccountingApi.md#updatecreditnoteattachmentbyfilename) | **POST** /CreditNotes/{CreditNoteID}/Attachments/{FileName} | Updates attachments on a specific credit note by file name |
*AccountingApi* | [**updateExpenseClaim**](Apis/AccountingApi.md#updateexpenseclaim) | **POST** /ExpenseClaims/{ExpenseClaimID} | Updates a specific expense claims |
*AccountingApi* | [**updateInvoice**](Apis/AccountingApi.md#updateinvoice) | **POST** /Invoices/{InvoiceID} | Updates a specific sales invoices or purchase bills |
*AccountingApi* | [**updateInvoiceAttachmentByFileName**](Apis/AccountingApi.md#updateinvoiceattachmentbyfilename) | **POST** /Invoices/{InvoiceID}/Attachments/{FileName} | Updates an attachment from a specific invoices or purchase bill by filename |
*AccountingApi* | [**updateItem**](Apis/AccountingApi.md#updateitem) | **POST** /Items/{ItemID} | Updates a specific item |
*AccountingApi* | [**updateLinkedTransaction**](Apis/AccountingApi.md#updatelinkedtransaction) | **POST** /LinkedTransactions/{LinkedTransactionID} | Updates a specific linked transactions (billable expenses) |
*AccountingApi* | [**updateManualJournal**](Apis/AccountingApi.md#updatemanualjournal) | **POST** /ManualJournals/{ManualJournalID} | Updates a specific manual journal |
*AccountingApi* | [**updateManualJournalAttachmentByFileName**](Apis/AccountingApi.md#updatemanualjournalattachmentbyfilename) | **POST** /ManualJournals/{ManualJournalID}/Attachments/{FileName} | Updates a specific attachment from a specific manual journal by file name |
*AccountingApi* | [**updateOrCreateBankTransactions**](Apis/AccountingApi.md#updateorcreatebanktransactions) | **POST** /BankTransactions | Updates or creates one or more spent or received money transaction |
*AccountingApi* | [**updateOrCreateContacts**](Apis/AccountingApi.md#updateorcreatecontacts) | **POST** /Contacts | Updates or creates one or more contacts in a Xero organisation |
*AccountingApi* | [**updateOrCreateCreditNotes**](Apis/AccountingApi.md#updateorcreatecreditnotes) | **POST** /CreditNotes | Updates or creates one or more credit notes |
*AccountingApi* | [**updateOrCreateEmployees**](Apis/AccountingApi.md#updateorcreateemployees) | **POST** /Employees | Creates a single new employees used in Xero payrun |
*AccountingApi* | [**updateOrCreateInvoices**](Apis/AccountingApi.md#updateorcreateinvoices) | **POST** /Invoices | Updates or creates one or more sales invoices or purchase bills |
*AccountingApi* | [**updateOrCreateItems**](Apis/AccountingApi.md#updateorcreateitems) | **POST** /Items | Updates or creates one or more items |
*AccountingApi* | [**updateOrCreateManualJournals**](Apis/AccountingApi.md#updateorcreatemanualjournals) | **POST** /ManualJournals | Updates or creates a single manual journal |
*AccountingApi* | [**updateOrCreatePurchaseOrders**](Apis/AccountingApi.md#updateorcreatepurchaseorders) | **POST** /PurchaseOrders | Updates or creates one or more purchase orders |
*AccountingApi* | [**updateOrCreateQuotes**](Apis/AccountingApi.md#updateorcreatequotes) | **POST** /Quotes | Updates or creates one or more quotes |
*AccountingApi* | [**updateOrCreateRepeatingInvoices**](Apis/AccountingApi.md#updateorcreaterepeatinginvoices) | **POST** /RepeatingInvoices | Creates or deletes one or more repeating invoice templates |
*AccountingApi* | [**updatePurchaseOrder**](Apis/AccountingApi.md#updatepurchaseorder) | **POST** /PurchaseOrders/{PurchaseOrderID} | Updates a specific purchase order |
*AccountingApi* | [**updatePurchaseOrderAttachmentByFileName**](Apis/AccountingApi.md#updatepurchaseorderattachmentbyfilename) | **POST** /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName} | Updates a specific attachment for a specific purchase order by filename |
*AccountingApi* | [**updateQuote**](Apis/AccountingApi.md#updatequote) | **POST** /Quotes/{QuoteID} | Updates a specific quote |
*AccountingApi* | [**updateQuoteAttachmentByFileName**](Apis/AccountingApi.md#updatequoteattachmentbyfilename) | **POST** /Quotes/{QuoteID}/Attachments/{FileName} | Updates a specific attachment from a specific quote by filename |
*AccountingApi* | [**updateReceipt**](Apis/AccountingApi.md#updatereceipt) | **POST** /Receipts/{ReceiptID} | Updates a specific draft expense claim receipts |
*AccountingApi* | [**updateReceiptAttachmentByFileName**](Apis/AccountingApi.md#updatereceiptattachmentbyfilename) | **POST** /Receipts/{ReceiptID}/Attachments/{FileName} | Updates a specific attachment on a specific expense claim receipts by file name |
*AccountingApi* | [**updateRepeatingInvoice**](Apis/AccountingApi.md#updaterepeatinginvoice) | **POST** /RepeatingInvoices/{RepeatingInvoiceID} | Deletes a specific repeating invoice template |
*AccountingApi* | [**updateRepeatingInvoiceAttachmentByFileName**](Apis/AccountingApi.md#updaterepeatinginvoiceattachmentbyfilename) | **POST** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName} | Updates a specific attachment from a specific repeating invoices by file name |
*AccountingApi* | [**updateTaxRate**](Apis/AccountingApi.md#updatetaxrate) | **POST** /TaxRates | Updates tax rates |
*AccountingApi* | [**updateTrackingCategory**](Apis/AccountingApi.md#updatetrackingcategory) | **POST** /TrackingCategories/{TrackingCategoryID} | Updates a specific tracking category |
*AccountingApi* | [**updateTrackingOptions**](Apis/AccountingApi.md#updatetrackingoptions) | **POST** /TrackingCategories/{TrackingCategoryID}/Options/{TrackingOptionID} | Updates a specific option for a specific tracking category |


<a name="documentation-for-models"></a>
## Documentation for Models

 - [Account](./Models/Account.md)
 - [AccountType](./Models/AccountType.md)
 - [Accounts](./Models/Accounts.md)
 - [AccountsPayable](./Models/AccountsPayable.md)
 - [AccountsReceivable](./Models/AccountsReceivable.md)
 - [Action](./Models/Action.md)
 - [Actions](./Models/Actions.md)
 - [Address](./Models/Address.md)
 - [AddressForOrganisation](./Models/AddressForOrganisation.md)
 - [Allocation](./Models/Allocation.md)
 - [Allocations](./Models/Allocations.md)
 - [Attachment](./Models/Attachment.md)
 - [Attachments](./Models/Attachments.md)
 - [BalanceDetails](./Models/BalanceDetails.md)
 - [Balances](./Models/Balances.md)
 - [BankTransaction](./Models/BankTransaction.md)
 - [BankTransactions](./Models/BankTransactions.md)
 - [BankTransfer](./Models/BankTransfer.md)
 - [BankTransfers](./Models/BankTransfers.md)
 - [BatchPayment](./Models/BatchPayment.md)
 - [BatchPaymentDelete](./Models/BatchPaymentDelete.md)
 - [BatchPaymentDeleteByUrlParam](./Models/BatchPaymentDeleteByUrlParam.md)
 - [BatchPaymentDetails](./Models/BatchPaymentDetails.md)
 - [BatchPayments](./Models/BatchPayments.md)
 - [Bill](./Models/Bill.md)
 - [BrandingTheme](./Models/BrandingTheme.md)
 - [BrandingThemes](./Models/BrandingThemes.md)
 - [Budget](./Models/Budget.md)
 - [BudgetBalance](./Models/BudgetBalance.md)
 - [BudgetLine](./Models/BudgetLine.md)
 - [Budgets](./Models/Budgets.md)
 - [CISOrgSetting](./Models/CISOrgSetting.md)
 - [CISOrgSettings](./Models/CISOrgSettings.md)
 - [CISSetting](./Models/CISSetting.md)
 - [CISSettings](./Models/CISSettings.md)
 - [Contact](./Models/Contact.md)
 - [ContactGroup](./Models/ContactGroup.md)
 - [ContactGroups](./Models/ContactGroups.md)
 - [ContactPerson](./Models/ContactPerson.md)
 - [Contacts](./Models/Contacts.md)
 - [ConversionBalances](./Models/ConversionBalances.md)
 - [ConversionDate](./Models/ConversionDate.md)
 - [CountryCode](./Models/CountryCode.md)
 - [CreditNote](./Models/CreditNote.md)
 - [CreditNotes](./Models/CreditNotes.md)
 - [Currencies](./Models/Currencies.md)
 - [Currency](./Models/Currency.md)
 - [CurrencyCode](./Models/CurrencyCode.md)
 - [Element](./Models/Element.md)
 - [Employee](./Models/Employee.md)
 - [Employees](./Models/Employees.md)
 - [Error](./Models/Error.md)
 - [ExpenseClaim](./Models/ExpenseClaim.md)
 - [ExpenseClaims](./Models/ExpenseClaims.md)
 - [ExternalLink](./Models/ExternalLink.md)
 - [HistoryRecord](./Models/HistoryRecord.md)
 - [HistoryRecords](./Models/HistoryRecords.md)
 - [ImportSummary](./Models/ImportSummary.md)
 - [ImportSummaryAccounts](./Models/ImportSummaryAccounts.md)
 - [ImportSummaryObject](./Models/ImportSummaryObject.md)
 - [ImportSummaryOrganisation](./Models/ImportSummaryOrganisation.md)
 - [Invoice](./Models/Invoice.md)
 - [InvoiceReminder](./Models/InvoiceReminder.md)
 - [InvoiceReminders](./Models/InvoiceReminders.md)
 - [Invoices](./Models/Invoices.md)
 - [Item](./Models/Item.md)
 - [Items](./Models/Items.md)
 - [Journal](./Models/Journal.md)
 - [JournalLine](./Models/JournalLine.md)
 - [Journals](./Models/Journals.md)
 - [LineAmountTypes](./Models/LineAmountTypes.md)
 - [LineItem](./Models/LineItem.md)
 - [LineItemItem](./Models/LineItemItem.md)
 - [LineItemTracking](./Models/LineItemTracking.md)
 - [LinkedTransaction](./Models/LinkedTransaction.md)
 - [LinkedTransactions](./Models/LinkedTransactions.md)
 - [ManualJournal](./Models/ManualJournal.md)
 - [ManualJournalLine](./Models/ManualJournalLine.md)
 - [ManualJournals](./Models/ManualJournals.md)
 - [OnlineInvoice](./Models/OnlineInvoice.md)
 - [OnlineInvoices](./Models/OnlineInvoices.md)
 - [Organisation](./Models/Organisation.md)
 - [Organisations](./Models/Organisations.md)
 - [Overpayment](./Models/Overpayment.md)
 - [Overpayments](./Models/Overpayments.md)
 - [Pagination](./Models/Pagination.md)
 - [Payment](./Models/Payment.md)
 - [PaymentDelete](./Models/PaymentDelete.md)
 - [PaymentService](./Models/PaymentService.md)
 - [PaymentServices](./Models/PaymentServices.md)
 - [PaymentTerm](./Models/PaymentTerm.md)
 - [PaymentTermType](./Models/PaymentTermType.md)
 - [Payments](./Models/Payments.md)
 - [Phone](./Models/Phone.md)
 - [Prepayment](./Models/Prepayment.md)
 - [Prepayments](./Models/Prepayments.md)
 - [Purchase](./Models/Purchase.md)
 - [PurchaseOrder](./Models/PurchaseOrder.md)
 - [PurchaseOrders](./Models/PurchaseOrders.md)
 - [Quote](./Models/Quote.md)
 - [QuoteLineAmountTypes](./Models/QuoteLineAmountTypes.md)
 - [QuoteStatusCodes](./Models/QuoteStatusCodes.md)
 - [Quotes](./Models/Quotes.md)
 - [Receipt](./Models/Receipt.md)
 - [Receipts](./Models/Receipts.md)
 - [RepeatingInvoice](./Models/RepeatingInvoice.md)
 - [RepeatingInvoices](./Models/RepeatingInvoices.md)
 - [Report](./Models/Report.md)
 - [ReportAttribute](./Models/ReportAttribute.md)
 - [ReportCell](./Models/ReportCell.md)
 - [ReportFields](./Models/ReportFields.md)
 - [ReportRow](./Models/ReportRow.md)
 - [ReportRows](./Models/ReportRows.md)
 - [ReportWithRow](./Models/ReportWithRow.md)
 - [ReportWithRows](./Models/ReportWithRows.md)
 - [Reports](./Models/Reports.md)
 - [RequestEmpty](./Models/RequestEmpty.md)
 - [RowType](./Models/RowType.md)
 - [SalesTrackingCategory](./Models/SalesTrackingCategory.md)
 - [Schedule](./Models/Schedule.md)
 - [Setup](./Models/Setup.md)
 - [TaxComponent](./Models/TaxComponent.md)
 - [TaxRate](./Models/TaxRate.md)
 - [TaxRates](./Models/TaxRates.md)
 - [TaxType](./Models/TaxType.md)
 - [TenNinetyNineContact](./Models/TenNinetyNineContact.md)
 - [TimeZone](./Models/TimeZone.md)
 - [TrackingCategories](./Models/TrackingCategories.md)
 - [TrackingCategory](./Models/TrackingCategory.md)
 - [TrackingOption](./Models/TrackingOption.md)
 - [TrackingOptions](./Models/TrackingOptions.md)
 - [User](./Models/User.md)
 - [Users](./Models/Users.md)
 - [ValidationError](./Models/ValidationError.md)


<a name="documentation-for-authorization"></a>
## Documentation for Authorization

<a name="OAuth2"></a>
### OAuth2

- **Type**: OAuth
- **Flow**: accessCode
- **Authorization URL**: https://login.xero.com/identity/connect/authorize
- **Scopes**: 
  - email: Grant read-only access to your email
  - openid: Grant read-only access to your open id
  - profile: your profile information
  - accounting.attachments: Grant read-write access to attachments
  - accounting.attachments.read: Grant read-only access to attachments
  - accounting.contacts: Grant read-write access to contacts and contact groups
  - accounting.contacts.read: Grant read-only access to contacts and contact groups
  - accounting.journals.read: Grant read-only access to journals
  - accounting.reports.read: Grant read-only access to accounting reports
  - accounting.reports.tenninetynine.read: Grant read-only access to 1099 reports
  - accounting.settings: Grant read-write access to organisation and account settings
  - accounting.settings.read: Grant read-only access to organisation and account settings
  - accounting.transactions: Grant read-write access to bank transactions, credit notes, invoices, repeating invoices
  - accounting.transactions.read: Grant read-only access to invoices
  - paymentservices: Grant read-write access to payment services

