# AccountingApi

All URIs are relative to *https://api.xero.com/api.xro/2.0*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**createAccount**](AccountingApi.md#createAccount) | **PUT** /Accounts | Creates a new chart of accounts |
| [**createAccountAttachmentByFileName**](AccountingApi.md#createAccountAttachmentByFileName) | **PUT** /Accounts/{AccountID}/Attachments/{FileName} | Creates an attachment on a specific account |
| [**createBankTransactionAttachmentByFileName**](AccountingApi.md#createBankTransactionAttachmentByFileName) | **PUT** /BankTransactions/{BankTransactionID}/Attachments/{FileName} | Creates an attachment for a specific bank transaction by filename |
| [**createBankTransactionHistoryRecord**](AccountingApi.md#createBankTransactionHistoryRecord) | **PUT** /BankTransactions/{BankTransactionID}/History | Creates a history record for a specific bank transactions |
| [**createBankTransactions**](AccountingApi.md#createBankTransactions) | **PUT** /BankTransactions | Creates one or more spent or received money transaction |
| [**createBankTransfer**](AccountingApi.md#createBankTransfer) | **PUT** /BankTransfers | Creates a bank transfer |
| [**createBankTransferAttachmentByFileName**](AccountingApi.md#createBankTransferAttachmentByFileName) | **PUT** /BankTransfers/{BankTransferID}/Attachments/{FileName} |  |
| [**createBankTransferHistoryRecord**](AccountingApi.md#createBankTransferHistoryRecord) | **PUT** /BankTransfers/{BankTransferID}/History | Creates a history record for a specific bank transfer |
| [**createBatchPayment**](AccountingApi.md#createBatchPayment) | **PUT** /BatchPayments | Creates one or many batch payments for invoices |
| [**createBatchPaymentHistoryRecord**](AccountingApi.md#createBatchPaymentHistoryRecord) | **PUT** /BatchPayments/{BatchPaymentID}/History | Creates a history record for a specific batch payment |
| [**createBrandingThemePaymentServices**](AccountingApi.md#createBrandingThemePaymentServices) | **POST** /BrandingThemes/{BrandingThemeID}/PaymentServices | Creates a new custom payment service for a specific branding theme |
| [**createContactAttachmentByFileName**](AccountingApi.md#createContactAttachmentByFileName) | **PUT** /Contacts/{ContactID}/Attachments/{FileName} |  |
| [**createContactGroup**](AccountingApi.md#createContactGroup) | **PUT** /ContactGroups | Creates a contact group |
| [**createContactGroupContacts**](AccountingApi.md#createContactGroupContacts) | **PUT** /ContactGroups/{ContactGroupID}/Contacts | Creates contacts to a specific contact group |
| [**createContactHistory**](AccountingApi.md#createContactHistory) | **PUT** /Contacts/{ContactID}/History | Creates a new history record for a specific contact |
| [**createContacts**](AccountingApi.md#createContacts) | **PUT** /Contacts | Creates multiple contacts (bulk) in a Xero organisation |
| [**createCreditNoteAllocation**](AccountingApi.md#createCreditNoteAllocation) | **PUT** /CreditNotes/{CreditNoteID}/Allocations | Creates allocation for a specific credit note |
| [**createCreditNoteAttachmentByFileName**](AccountingApi.md#createCreditNoteAttachmentByFileName) | **PUT** /CreditNotes/{CreditNoteID}/Attachments/{FileName} | Creates an attachment for a specific credit note |
| [**createCreditNoteHistory**](AccountingApi.md#createCreditNoteHistory) | **PUT** /CreditNotes/{CreditNoteID}/History | Retrieves history records of a specific credit note |
| [**createCreditNotes**](AccountingApi.md#createCreditNotes) | **PUT** /CreditNotes | Creates a new credit note |
| [**createCurrency**](AccountingApi.md#createCurrency) | **PUT** /Currencies | Create a new currency for a Xero organisation |
| [**createEmployees**](AccountingApi.md#createEmployees) | **PUT** /Employees | Creates new employees used in Xero payrun |
| [**createExpenseClaimHistory**](AccountingApi.md#createExpenseClaimHistory) | **PUT** /ExpenseClaims/{ExpenseClaimID}/History | Creates a history record for a specific expense claim |
| [**createExpenseClaims**](AccountingApi.md#createExpenseClaims) | **PUT** /ExpenseClaims | Creates expense claims |
| [**createInvoiceAttachmentByFileName**](AccountingApi.md#createInvoiceAttachmentByFileName) | **PUT** /Invoices/{InvoiceID}/Attachments/{FileName} | Creates an attachment for a specific invoice or purchase bill by filename |
| [**createInvoiceHistory**](AccountingApi.md#createInvoiceHistory) | **PUT** /Invoices/{InvoiceID}/History | Creates a history record for a specific invoice |
| [**createInvoices**](AccountingApi.md#createInvoices) | **PUT** /Invoices | Creates one or more sales invoices or purchase bills |
| [**createItemHistory**](AccountingApi.md#createItemHistory) | **PUT** /Items/{ItemID}/History | Creates a history record for a specific item |
| [**createItems**](AccountingApi.md#createItems) | **PUT** /Items | Creates one or more items |
| [**createLinkedTransaction**](AccountingApi.md#createLinkedTransaction) | **PUT** /LinkedTransactions | Creates linked transactions (billable expenses) |
| [**createManualJournalAttachmentByFileName**](AccountingApi.md#createManualJournalAttachmentByFileName) | **PUT** /ManualJournals/{ManualJournalID}/Attachments/{FileName} | Creates a specific attachment for a specific manual journal by file name |
| [**createManualJournalHistoryRecord**](AccountingApi.md#createManualJournalHistoryRecord) | **PUT** /ManualJournals/{ManualJournalID}/History | Creates a history record for a specific manual journal |
| [**createManualJournals**](AccountingApi.md#createManualJournals) | **PUT** /ManualJournals | Creates one or more manual journals |
| [**createOverpaymentAllocations**](AccountingApi.md#createOverpaymentAllocations) | **PUT** /Overpayments/{OverpaymentID}/Allocations | Creates a single allocation for a specific overpayment |
| [**createOverpaymentHistory**](AccountingApi.md#createOverpaymentHistory) | **PUT** /Overpayments/{OverpaymentID}/History | Creates a history record for a specific overpayment |
| [**createPayment**](AccountingApi.md#createPayment) | **POST** /Payments | Creates a single payment for invoice or credit notes |
| [**createPaymentHistory**](AccountingApi.md#createPaymentHistory) | **PUT** /Payments/{PaymentID}/History | Creates a history record for a specific payment |
| [**createPaymentService**](AccountingApi.md#createPaymentService) | **PUT** /PaymentServices | Creates a payment service |
| [**createPayments**](AccountingApi.md#createPayments) | **PUT** /Payments | Creates multiple payments for invoices or credit notes |
| [**createPrepaymentAllocations**](AccountingApi.md#createPrepaymentAllocations) | **PUT** /Prepayments/{PrepaymentID}/Allocations | Allows you to create an Allocation for prepayments |
| [**createPrepaymentHistory**](AccountingApi.md#createPrepaymentHistory) | **PUT** /Prepayments/{PrepaymentID}/History | Creates a history record for a specific prepayment |
| [**createPurchaseOrderAttachmentByFileName**](AccountingApi.md#createPurchaseOrderAttachmentByFileName) | **PUT** /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName} | Creates attachment for a specific purchase order |
| [**createPurchaseOrderHistory**](AccountingApi.md#createPurchaseOrderHistory) | **PUT** /PurchaseOrders/{PurchaseOrderID}/History | Creates a history record for a specific purchase orders |
| [**createPurchaseOrders**](AccountingApi.md#createPurchaseOrders) | **PUT** /PurchaseOrders | Creates one or more purchase orders |
| [**createQuoteAttachmentByFileName**](AccountingApi.md#createQuoteAttachmentByFileName) | **PUT** /Quotes/{QuoteID}/Attachments/{FileName} | Creates attachment for a specific quote |
| [**createQuoteHistory**](AccountingApi.md#createQuoteHistory) | **PUT** /Quotes/{QuoteID}/History | Creates a history record for a specific quote |
| [**createQuotes**](AccountingApi.md#createQuotes) | **PUT** /Quotes | Create one or more quotes |
| [**createReceipt**](AccountingApi.md#createReceipt) | **PUT** /Receipts | Creates draft expense claim receipts for any user |
| [**createReceiptAttachmentByFileName**](AccountingApi.md#createReceiptAttachmentByFileName) | **PUT** /Receipts/{ReceiptID}/Attachments/{FileName} | Creates an attachment on a specific expense claim receipts by file name |
| [**createReceiptHistory**](AccountingApi.md#createReceiptHistory) | **PUT** /Receipts/{ReceiptID}/History | Creates a history record for a specific receipt |
| [**createRepeatingInvoiceAttachmentByFileName**](AccountingApi.md#createRepeatingInvoiceAttachmentByFileName) | **PUT** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName} | Creates an attachment from a specific repeating invoices by file name |
| [**createRepeatingInvoiceHistory**](AccountingApi.md#createRepeatingInvoiceHistory) | **PUT** /RepeatingInvoices/{RepeatingInvoiceID}/History | Creates a  history record for a specific repeating invoice |
| [**createRepeatingInvoices**](AccountingApi.md#createRepeatingInvoices) | **PUT** /RepeatingInvoices | Creates one or more repeating invoice templates |
| [**createTaxRates**](AccountingApi.md#createTaxRates) | **PUT** /TaxRates | Creates one or more tax rates |
| [**createTrackingCategory**](AccountingApi.md#createTrackingCategory) | **PUT** /TrackingCategories | Create tracking categories |
| [**createTrackingOptions**](AccountingApi.md#createTrackingOptions) | **PUT** /TrackingCategories/{TrackingCategoryID}/Options | Creates options for a specific tracking category |
| [**deleteAccount**](AccountingApi.md#deleteAccount) | **DELETE** /Accounts/{AccountID} | Deletes a chart of accounts |
| [**deleteBatchPayment**](AccountingApi.md#deleteBatchPayment) | **POST** /BatchPayments | Updates a specific batch payment for invoices and credit notes |
| [**deleteBatchPaymentByUrlParam**](AccountingApi.md#deleteBatchPaymentByUrlParam) | **POST** /BatchPayments/{BatchPaymentID} | Updates a specific batch payment for invoices and credit notes |
| [**deleteContactGroupContact**](AccountingApi.md#deleteContactGroupContact) | **DELETE** /ContactGroups/{ContactGroupID}/Contacts/{ContactID} | Deletes a specific contact from a contact group using a unique contact Id |
| [**deleteContactGroupContacts**](AccountingApi.md#deleteContactGroupContacts) | **DELETE** /ContactGroups/{ContactGroupID}/Contacts | Deletes all contacts from a specific contact group |
| [**deleteCreditNoteAllocations**](AccountingApi.md#deleteCreditNoteAllocations) | **DELETE** /CreditNotes/{CreditNoteID}/Allocations/{AllocationID} | Deletes an Allocation from a Credit Note |
| [**deleteItem**](AccountingApi.md#deleteItem) | **DELETE** /Items/{ItemID} | Deletes a specific item |
| [**deleteLinkedTransaction**](AccountingApi.md#deleteLinkedTransaction) | **DELETE** /LinkedTransactions/{LinkedTransactionID} | Deletes a specific linked transactions (billable expenses) |
| [**deleteOverpaymentAllocations**](AccountingApi.md#deleteOverpaymentAllocations) | **DELETE** /Overpayments/{OverpaymentID}/Allocations/{AllocationID} | Deletes an Allocation from an overpayment |
| [**deletePayment**](AccountingApi.md#deletePayment) | **POST** /Payments/{PaymentID} | Updates a specific payment for invoices and credit notes |
| [**deletePrepaymentAllocations**](AccountingApi.md#deletePrepaymentAllocations) | **DELETE** /Prepayments/{PrepaymentID}/Allocations/{AllocationID} | Deletes an Allocation from a Prepayment |
| [**deleteTrackingCategory**](AccountingApi.md#deleteTrackingCategory) | **DELETE** /TrackingCategories/{TrackingCategoryID} | Deletes a specific tracking category |
| [**deleteTrackingOptions**](AccountingApi.md#deleteTrackingOptions) | **DELETE** /TrackingCategories/{TrackingCategoryID}/Options/{TrackingOptionID} | Deletes a specific option for a specific tracking category |
| [**emailInvoice**](AccountingApi.md#emailInvoice) | **POST** /Invoices/{InvoiceID}/Email | Sends a copy of a specific invoice to related contact via email |
| [**getAccount**](AccountingApi.md#getAccount) | **GET** /Accounts/{AccountID} | Retrieves a single chart of accounts by using a unique account Id |
| [**getAccountAttachmentByFileName**](AccountingApi.md#getAccountAttachmentByFileName) | **GET** /Accounts/{AccountID}/Attachments/{FileName} | Retrieves an attachment for a specific account by filename |
| [**getAccountAttachmentById**](AccountingApi.md#getAccountAttachmentById) | **GET** /Accounts/{AccountID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific account using a unique attachment Id |
| [**getAccountAttachments**](AccountingApi.md#getAccountAttachments) | **GET** /Accounts/{AccountID}/Attachments | Retrieves attachments for a specific accounts by using a unique account Id |
| [**getAccounts**](AccountingApi.md#getAccounts) | **GET** /Accounts | Retrieves the full chart of accounts |
| [**getBankTransaction**](AccountingApi.md#getBankTransaction) | **GET** /BankTransactions/{BankTransactionID} | Retrieves a single spent or received money transaction by using a unique bank transaction Id |
| [**getBankTransactionAttachmentByFileName**](AccountingApi.md#getBankTransactionAttachmentByFileName) | **GET** /BankTransactions/{BankTransactionID}/Attachments/{FileName} | Retrieves a specific attachment from a specific bank transaction by filename |
| [**getBankTransactionAttachmentById**](AccountingApi.md#getBankTransactionAttachmentById) | **GET** /BankTransactions/{BankTransactionID}/Attachments/{AttachmentID} | Retrieves specific attachments from a specific BankTransaction using a unique attachment Id |
| [**getBankTransactionAttachments**](AccountingApi.md#getBankTransactionAttachments) | **GET** /BankTransactions/{BankTransactionID}/Attachments | Retrieves any attachments from a specific bank transactions |
| [**getBankTransactions**](AccountingApi.md#getBankTransactions) | **GET** /BankTransactions | Retrieves any spent or received money transactions |
| [**getBankTransactionsHistory**](AccountingApi.md#getBankTransactionsHistory) | **GET** /BankTransactions/{BankTransactionID}/History | Retrieves history from a specific bank transaction using a unique bank transaction Id |
| [**getBankTransfer**](AccountingApi.md#getBankTransfer) | **GET** /BankTransfers/{BankTransferID} | Retrieves specific bank transfers by using a unique bank transfer Id |
| [**getBankTransferAttachmentByFileName**](AccountingApi.md#getBankTransferAttachmentByFileName) | **GET** /BankTransfers/{BankTransferID}/Attachments/{FileName} | Retrieves a specific attachment on a specific bank transfer by file name |
| [**getBankTransferAttachmentById**](AccountingApi.md#getBankTransferAttachmentById) | **GET** /BankTransfers/{BankTransferID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific bank transfer using a unique attachment ID |
| [**getBankTransferAttachments**](AccountingApi.md#getBankTransferAttachments) | **GET** /BankTransfers/{BankTransferID}/Attachments | Retrieves attachments from a specific bank transfer |
| [**getBankTransferHistory**](AccountingApi.md#getBankTransferHistory) | **GET** /BankTransfers/{BankTransferID}/History | Retrieves history from a specific bank transfer using a unique bank transfer Id |
| [**getBankTransfers**](AccountingApi.md#getBankTransfers) | **GET** /BankTransfers | Retrieves all bank transfers |
| [**getBatchPayment**](AccountingApi.md#getBatchPayment) | **GET** /BatchPayments/{BatchPaymentID} | Retrieves a specific batch payment using a unique batch payment Id |
| [**getBatchPaymentHistory**](AccountingApi.md#getBatchPaymentHistory) | **GET** /BatchPayments/{BatchPaymentID}/History | Retrieves history from a specific batch payment |
| [**getBatchPayments**](AccountingApi.md#getBatchPayments) | **GET** /BatchPayments | Retrieves either one or many batch payments for invoices |
| [**getBrandingTheme**](AccountingApi.md#getBrandingTheme) | **GET** /BrandingThemes/{BrandingThemeID} | Retrieves a specific branding theme using a unique branding theme Id |
| [**getBrandingThemePaymentServices**](AccountingApi.md#getBrandingThemePaymentServices) | **GET** /BrandingThemes/{BrandingThemeID}/PaymentServices | Retrieves the payment services for a specific branding theme |
| [**getBrandingThemes**](AccountingApi.md#getBrandingThemes) | **GET** /BrandingThemes | Retrieves all the branding themes |
| [**getBudget**](AccountingApi.md#getBudget) | **GET** /Budgets/{BudgetID} | Retrieves a specific budget, which includes budget lines |
| [**getBudgets**](AccountingApi.md#getBudgets) | **GET** /Budgets | Retrieve a list of budgets |
| [**getContact**](AccountingApi.md#getContact) | **GET** /Contacts/{ContactID} | Retrieves a specific contacts in a Xero organisation using a unique contact Id |
| [**getContactAttachmentByFileName**](AccountingApi.md#getContactAttachmentByFileName) | **GET** /Contacts/{ContactID}/Attachments/{FileName} | Retrieves a specific attachment from a specific contact by file name |
| [**getContactAttachmentById**](AccountingApi.md#getContactAttachmentById) | **GET** /Contacts/{ContactID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific contact using a unique attachment Id |
| [**getContactAttachments**](AccountingApi.md#getContactAttachments) | **GET** /Contacts/{ContactID}/Attachments | Retrieves attachments for a specific contact in a Xero organisation |
| [**getContactByContactNumber**](AccountingApi.md#getContactByContactNumber) | **GET** /Contacts/{ContactNumber} | Retrieves a specific contact by contact number in a Xero organisation |
| [**getContactCISSettings**](AccountingApi.md#getContactCISSettings) | **GET** /Contacts/{ContactID}/CISSettings | Retrieves CIS settings for a specific contact in a Xero organisation |
| [**getContactGroup**](AccountingApi.md#getContactGroup) | **GET** /ContactGroups/{ContactGroupID} | Retrieves a specific contact group by using a unique contact group Id |
| [**getContactGroups**](AccountingApi.md#getContactGroups) | **GET** /ContactGroups | Retrieves the contact Id and name of each contact group |
| [**getContactHistory**](AccountingApi.md#getContactHistory) | **GET** /Contacts/{ContactID}/History | Retrieves history records for a specific contact |
| [**getContacts**](AccountingApi.md#getContacts) | **GET** /Contacts | Retrieves all contacts in a Xero organisation |
| [**getCreditNote**](AccountingApi.md#getCreditNote) | **GET** /CreditNotes/{CreditNoteID} | Retrieves a specific credit note using a unique credit note Id |
| [**getCreditNoteAsPdf**](AccountingApi.md#getCreditNoteAsPdf) | **GET** /CreditNotes/{CreditNoteID}/pdf | Retrieves credit notes as PDF files |
| [**getCreditNoteAttachmentByFileName**](AccountingApi.md#getCreditNoteAttachmentByFileName) | **GET** /CreditNotes/{CreditNoteID}/Attachments/{FileName} | Retrieves a specific attachment on a specific credit note by file name |
| [**getCreditNoteAttachmentById**](AccountingApi.md#getCreditNoteAttachmentById) | **GET** /CreditNotes/{CreditNoteID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific credit note using a unique attachment Id |
| [**getCreditNoteAttachments**](AccountingApi.md#getCreditNoteAttachments) | **GET** /CreditNotes/{CreditNoteID}/Attachments | Retrieves attachments for a specific credit notes |
| [**getCreditNoteHistory**](AccountingApi.md#getCreditNoteHistory) | **GET** /CreditNotes/{CreditNoteID}/History | Retrieves history records of a specific credit note |
| [**getCreditNotes**](AccountingApi.md#getCreditNotes) | **GET** /CreditNotes | Retrieves any credit notes |
| [**getCurrencies**](AccountingApi.md#getCurrencies) | **GET** /Currencies | Retrieves currencies for your Xero organisation |
| [**getEmployee**](AccountingApi.md#getEmployee) | **GET** /Employees/{EmployeeID} | Retrieves a specific employee used in Xero payrun using a unique employee Id |
| [**getEmployees**](AccountingApi.md#getEmployees) | **GET** /Employees | Retrieves employees used in Xero payrun |
| [**getExpenseClaim**](AccountingApi.md#getExpenseClaim) | **GET** /ExpenseClaims/{ExpenseClaimID} | Retrieves a specific expense claim using a unique expense claim Id |
| [**getExpenseClaimHistory**](AccountingApi.md#getExpenseClaimHistory) | **GET** /ExpenseClaims/{ExpenseClaimID}/History | Retrieves history records of a specific expense claim |
| [**getExpenseClaims**](AccountingApi.md#getExpenseClaims) | **GET** /ExpenseClaims | Retrieves expense claims |
| [**getInvoice**](AccountingApi.md#getInvoice) | **GET** /Invoices/{InvoiceID} | Retrieves a specific sales invoice or purchase bill using a unique invoice Id |
| [**getInvoiceAsPdf**](AccountingApi.md#getInvoiceAsPdf) | **GET** /Invoices/{InvoiceID}/pdf | Retrieves invoices or purchase bills as PDF files |
| [**getInvoiceAttachmentByFileName**](AccountingApi.md#getInvoiceAttachmentByFileName) | **GET** /Invoices/{InvoiceID}/Attachments/{FileName} | Retrieves an attachment from a specific invoice or purchase bill by filename |
| [**getInvoiceAttachmentById**](AccountingApi.md#getInvoiceAttachmentById) | **GET** /Invoices/{InvoiceID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific invoices or purchase bills by using a unique attachment Id |
| [**getInvoiceAttachments**](AccountingApi.md#getInvoiceAttachments) | **GET** /Invoices/{InvoiceID}/Attachments | Retrieves attachments for a specific invoice or purchase bill |
| [**getInvoiceHistory**](AccountingApi.md#getInvoiceHistory) | **GET** /Invoices/{InvoiceID}/History | Retrieves history records for a specific invoice |
| [**getInvoiceReminders**](AccountingApi.md#getInvoiceReminders) | **GET** /InvoiceReminders/Settings | Retrieves invoice reminder settings |
| [**getInvoices**](AccountingApi.md#getInvoices) | **GET** /Invoices | Retrieves sales invoices or purchase bills |
| [**getItem**](AccountingApi.md#getItem) | **GET** /Items/{ItemID} | Retrieves a specific item using a unique item Id |
| [**getItemHistory**](AccountingApi.md#getItemHistory) | **GET** /Items/{ItemID}/History | Retrieves history for a specific item |
| [**getItems**](AccountingApi.md#getItems) | **GET** /Items | Retrieves items |
| [**getJournal**](AccountingApi.md#getJournal) | **GET** /Journals/{JournalID} | Retrieves a specific journal using a unique journal Id. |
| [**getJournalByNumber**](AccountingApi.md#getJournalByNumber) | **GET** /Journals/{JournalNumber} | Retrieves a specific journal using a unique journal number. |
| [**getJournals**](AccountingApi.md#getJournals) | **GET** /Journals | Retrieves journals |
| [**getLinkedTransaction**](AccountingApi.md#getLinkedTransaction) | **GET** /LinkedTransactions/{LinkedTransactionID} | Retrieves a specific linked transaction (billable expenses) using a unique linked transaction Id |
| [**getLinkedTransactions**](AccountingApi.md#getLinkedTransactions) | **GET** /LinkedTransactions | Retrieves linked transactions (billable expenses) |
| [**getManualJournal**](AccountingApi.md#getManualJournal) | **GET** /ManualJournals/{ManualJournalID} | Retrieves a specific manual journal |
| [**getManualJournalAttachmentByFileName**](AccountingApi.md#getManualJournalAttachmentByFileName) | **GET** /ManualJournals/{ManualJournalID}/Attachments/{FileName} | Retrieves a specific attachment from a specific manual journal by file name |
| [**getManualJournalAttachmentById**](AccountingApi.md#getManualJournalAttachmentById) | **GET** /ManualJournals/{ManualJournalID}/Attachments/{AttachmentID} | Allows you to retrieve a specific attachment from a specific manual journal using a unique attachment Id |
| [**getManualJournalAttachments**](AccountingApi.md#getManualJournalAttachments) | **GET** /ManualJournals/{ManualJournalID}/Attachments | Retrieves attachment for a specific manual journal |
| [**getManualJournals**](AccountingApi.md#getManualJournals) | **GET** /ManualJournals | Retrieves manual journals |
| [**getManualJournalsHistory**](AccountingApi.md#getManualJournalsHistory) | **GET** /ManualJournals/{ManualJournalID}/History | Retrieves history for a specific manual journal |
| [**getOnlineInvoice**](AccountingApi.md#getOnlineInvoice) | **GET** /Invoices/{InvoiceID}/OnlineInvoice | Retrieves a URL to an online invoice |
| [**getOrganisationActions**](AccountingApi.md#getOrganisationActions) | **GET** /Organisation/Actions | Retrieves a list of the key actions your app has permission to perform in the connected Xero organisation. |
| [**getOrganisationCISSettings**](AccountingApi.md#getOrganisationCISSettings) | **GET** /Organisation/{OrganisationID}/CISSettings | Retrieves the CIS settings for the Xero organistaion. |
| [**getOrganisations**](AccountingApi.md#getOrganisations) | **GET** /Organisation | Retrieves Xero organisation details |
| [**getOverpayment**](AccountingApi.md#getOverpayment) | **GET** /Overpayments/{OverpaymentID} | Retrieves a specific overpayment using a unique overpayment Id |
| [**getOverpaymentHistory**](AccountingApi.md#getOverpaymentHistory) | **GET** /Overpayments/{OverpaymentID}/History | Retrieves history records of a specific overpayment |
| [**getOverpayments**](AccountingApi.md#getOverpayments) | **GET** /Overpayments | Retrieves overpayments |
| [**getPayment**](AccountingApi.md#getPayment) | **GET** /Payments/{PaymentID} | Retrieves a specific payment for invoices and credit notes using a unique payment Id |
| [**getPaymentHistory**](AccountingApi.md#getPaymentHistory) | **GET** /Payments/{PaymentID}/History | Retrieves history records of a specific payment |
| [**getPaymentServices**](AccountingApi.md#getPaymentServices) | **GET** /PaymentServices | Retrieves payment services |
| [**getPayments**](AccountingApi.md#getPayments) | **GET** /Payments | Retrieves payments for invoices and credit notes |
| [**getPrepayment**](AccountingApi.md#getPrepayment) | **GET** /Prepayments/{PrepaymentID} | Allows you to retrieve a specified prepayments |
| [**getPrepaymentHistory**](AccountingApi.md#getPrepaymentHistory) | **GET** /Prepayments/{PrepaymentID}/History | Retrieves history record for a specific prepayment |
| [**getPrepayments**](AccountingApi.md#getPrepayments) | **GET** /Prepayments | Retrieves prepayments |
| [**getPurchaseOrder**](AccountingApi.md#getPurchaseOrder) | **GET** /PurchaseOrders/{PurchaseOrderID} | Retrieves a specific purchase order using a unique purchase order Id |
| [**getPurchaseOrderAsPdf**](AccountingApi.md#getPurchaseOrderAsPdf) | **GET** /PurchaseOrders/{PurchaseOrderID}/pdf | Retrieves specific purchase order as PDF files using a unique purchase order Id |
| [**getPurchaseOrderAttachmentByFileName**](AccountingApi.md#getPurchaseOrderAttachmentByFileName) | **GET** /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName} | Retrieves a specific attachment for a specific purchase order by filename |
| [**getPurchaseOrderAttachmentById**](AccountingApi.md#getPurchaseOrderAttachmentById) | **GET** /PurchaseOrders/{PurchaseOrderID}/Attachments/{AttachmentID} | Retrieves specific attachment for a specific purchase order using a unique attachment Id |
| [**getPurchaseOrderAttachments**](AccountingApi.md#getPurchaseOrderAttachments) | **GET** /PurchaseOrders/{PurchaseOrderID}/Attachments | Retrieves attachments for a specific purchase order |
| [**getPurchaseOrderByNumber**](AccountingApi.md#getPurchaseOrderByNumber) | **GET** /PurchaseOrders/{PurchaseOrderNumber} | Retrieves a specific purchase order using purchase order number |
| [**getPurchaseOrderHistory**](AccountingApi.md#getPurchaseOrderHistory) | **GET** /PurchaseOrders/{PurchaseOrderID}/History | Retrieves history for a specific purchase order |
| [**getPurchaseOrders**](AccountingApi.md#getPurchaseOrders) | **GET** /PurchaseOrders | Retrieves purchase orders |
| [**getQuote**](AccountingApi.md#getQuote) | **GET** /Quotes/{QuoteID} | Retrieves a specific quote using a unique quote Id |
| [**getQuoteAsPdf**](AccountingApi.md#getQuoteAsPdf) | **GET** /Quotes/{QuoteID}/pdf | Retrieves a specific quote as a PDF file using a unique quote Id |
| [**getQuoteAttachmentByFileName**](AccountingApi.md#getQuoteAttachmentByFileName) | **GET** /Quotes/{QuoteID}/Attachments/{FileName} | Retrieves a specific attachment from a specific quote by filename |
| [**getQuoteAttachmentById**](AccountingApi.md#getQuoteAttachmentById) | **GET** /Quotes/{QuoteID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific quote using a unique attachment Id |
| [**getQuoteAttachments**](AccountingApi.md#getQuoteAttachments) | **GET** /Quotes/{QuoteID}/Attachments | Retrieves attachments for a specific quote |
| [**getQuoteHistory**](AccountingApi.md#getQuoteHistory) | **GET** /Quotes/{QuoteID}/History | Retrieves history records of a specific quote |
| [**getQuotes**](AccountingApi.md#getQuotes) | **GET** /Quotes | Retrieves sales quotes |
| [**getReceipt**](AccountingApi.md#getReceipt) | **GET** /Receipts/{ReceiptID} | Retrieves a specific draft expense claim receipt by using a unique receipt Id |
| [**getReceiptAttachmentByFileName**](AccountingApi.md#getReceiptAttachmentByFileName) | **GET** /Receipts/{ReceiptID}/Attachments/{FileName} | Retrieves a specific attachment from a specific expense claim receipts by file name |
| [**getReceiptAttachmentById**](AccountingApi.md#getReceiptAttachmentById) | **GET** /Receipts/{ReceiptID}/Attachments/{AttachmentID} | Retrieves a specific attachments from a specific expense claim receipts by using a unique attachment Id |
| [**getReceiptAttachments**](AccountingApi.md#getReceiptAttachments) | **GET** /Receipts/{ReceiptID}/Attachments | Retrieves attachments for a specific expense claim receipt |
| [**getReceiptHistory**](AccountingApi.md#getReceiptHistory) | **GET** /Receipts/{ReceiptID}/History | Retrieves a history record for a specific receipt |
| [**getReceipts**](AccountingApi.md#getReceipts) | **GET** /Receipts | Retrieves draft expense claim receipts for any user |
| [**getRepeatingInvoice**](AccountingApi.md#getRepeatingInvoice) | **GET** /RepeatingInvoices/{RepeatingInvoiceID} | Retrieves a specific repeating invoice by using a unique repeating invoice Id |
| [**getRepeatingInvoiceAttachmentByFileName**](AccountingApi.md#getRepeatingInvoiceAttachmentByFileName) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName} | Retrieves a specific attachment from a specific repeating invoices by file name |
| [**getRepeatingInvoiceAttachmentById**](AccountingApi.md#getRepeatingInvoiceAttachmentById) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{AttachmentID} | Retrieves a specific attachment from a specific repeating invoice |
| [**getRepeatingInvoiceAttachments**](AccountingApi.md#getRepeatingInvoiceAttachments) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments | Retrieves attachments from a specific repeating invoice |
| [**getRepeatingInvoiceHistory**](AccountingApi.md#getRepeatingInvoiceHistory) | **GET** /RepeatingInvoices/{RepeatingInvoiceID}/History | Retrieves history record for a specific repeating invoice |
| [**getRepeatingInvoices**](AccountingApi.md#getRepeatingInvoices) | **GET** /RepeatingInvoices | Retrieves repeating invoices |
| [**getReportAgedPayablesByContact**](AccountingApi.md#getReportAgedPayablesByContact) | **GET** /Reports/AgedPayablesByContact | Retrieves report for aged payables by contact |
| [**getReportAgedReceivablesByContact**](AccountingApi.md#getReportAgedReceivablesByContact) | **GET** /Reports/AgedReceivablesByContact | Retrieves report for aged receivables by contact |
| [**getReportBalanceSheet**](AccountingApi.md#getReportBalanceSheet) | **GET** /Reports/BalanceSheet | Retrieves report for balancesheet |
| [**getReportBankSummary**](AccountingApi.md#getReportBankSummary) | **GET** /Reports/BankSummary | Retrieves report for bank summary |
| [**getReportBudgetSummary**](AccountingApi.md#getReportBudgetSummary) | **GET** /Reports/BudgetSummary | Retrieves report for budget summary |
| [**getReportExecutiveSummary**](AccountingApi.md#getReportExecutiveSummary) | **GET** /Reports/ExecutiveSummary | Retrieves report for executive summary |
| [**getReportFromId**](AccountingApi.md#getReportFromId) | **GET** /Reports/{ReportID} | Retrieves a specific report using a unique ReportID |
| [**getReportProfitAndLoss**](AccountingApi.md#getReportProfitAndLoss) | **GET** /Reports/ProfitAndLoss | Retrieves report for profit and loss |
| [**getReportTenNinetyNine**](AccountingApi.md#getReportTenNinetyNine) | **GET** /Reports/TenNinetyNine | Retrieve reports for 1099 |
| [**getReportTrialBalance**](AccountingApi.md#getReportTrialBalance) | **GET** /Reports/TrialBalance | Retrieves report for trial balance |
| [**getReportsList**](AccountingApi.md#getReportsList) | **GET** /Reports | Retrieves a list of the organistaions unique reports that require a uuid to fetch |
| [**getTaxRateByTaxType**](AccountingApi.md#getTaxRateByTaxType) | **GET** /TaxRates/{TaxType} | Retrieves a specific tax rate according to given TaxType code |
| [**getTaxRates**](AccountingApi.md#getTaxRates) | **GET** /TaxRates | Retrieves tax rates |
| [**getTrackingCategories**](AccountingApi.md#getTrackingCategories) | **GET** /TrackingCategories | Retrieves tracking categories and options |
| [**getTrackingCategory**](AccountingApi.md#getTrackingCategory) | **GET** /TrackingCategories/{TrackingCategoryID} | Retrieves specific tracking categories and options using a unique tracking category Id |
| [**getUser**](AccountingApi.md#getUser) | **GET** /Users/{UserID} | Retrieves a specific user |
| [**getUsers**](AccountingApi.md#getUsers) | **GET** /Users | Retrieves users |
| [**postSetup**](AccountingApi.md#postSetup) | **POST** /Setup | Sets the chart of accounts, the conversion date and conversion balances |
| [**updateAccount**](AccountingApi.md#updateAccount) | **POST** /Accounts/{AccountID} | Updates a chart of accounts |
| [**updateAccountAttachmentByFileName**](AccountingApi.md#updateAccountAttachmentByFileName) | **POST** /Accounts/{AccountID}/Attachments/{FileName} | Updates attachment on a specific account by filename |
| [**updateBankTransaction**](AccountingApi.md#updateBankTransaction) | **POST** /BankTransactions/{BankTransactionID} | Updates a single spent or received money transaction |
| [**updateBankTransactionAttachmentByFileName**](AccountingApi.md#updateBankTransactionAttachmentByFileName) | **POST** /BankTransactions/{BankTransactionID}/Attachments/{FileName} | Updates a specific attachment from a specific bank transaction by filename |
| [**updateBankTransferAttachmentByFileName**](AccountingApi.md#updateBankTransferAttachmentByFileName) | **POST** /BankTransfers/{BankTransferID}/Attachments/{FileName} |  |
| [**updateContact**](AccountingApi.md#updateContact) | **POST** /Contacts/{ContactID} | Updates a specific contact in a Xero organisation |
| [**updateContactAttachmentByFileName**](AccountingApi.md#updateContactAttachmentByFileName) | **POST** /Contacts/{ContactID}/Attachments/{FileName} |  |
| [**updateContactGroup**](AccountingApi.md#updateContactGroup) | **POST** /ContactGroups/{ContactGroupID} | Updates a specific contact group |
| [**updateCreditNote**](AccountingApi.md#updateCreditNote) | **POST** /CreditNotes/{CreditNoteID} | Updates a specific credit note |
| [**updateCreditNoteAttachmentByFileName**](AccountingApi.md#updateCreditNoteAttachmentByFileName) | **POST** /CreditNotes/{CreditNoteID}/Attachments/{FileName} | Updates attachments on a specific credit note by file name |
| [**updateExpenseClaim**](AccountingApi.md#updateExpenseClaim) | **POST** /ExpenseClaims/{ExpenseClaimID} | Updates a specific expense claims |
| [**updateInvoice**](AccountingApi.md#updateInvoice) | **POST** /Invoices/{InvoiceID} | Updates a specific sales invoices or purchase bills |
| [**updateInvoiceAttachmentByFileName**](AccountingApi.md#updateInvoiceAttachmentByFileName) | **POST** /Invoices/{InvoiceID}/Attachments/{FileName} | Updates an attachment from a specific invoices or purchase bill by filename |
| [**updateItem**](AccountingApi.md#updateItem) | **POST** /Items/{ItemID} | Updates a specific item |
| [**updateLinkedTransaction**](AccountingApi.md#updateLinkedTransaction) | **POST** /LinkedTransactions/{LinkedTransactionID} | Updates a specific linked transactions (billable expenses) |
| [**updateManualJournal**](AccountingApi.md#updateManualJournal) | **POST** /ManualJournals/{ManualJournalID} | Updates a specific manual journal |
| [**updateManualJournalAttachmentByFileName**](AccountingApi.md#updateManualJournalAttachmentByFileName) | **POST** /ManualJournals/{ManualJournalID}/Attachments/{FileName} | Updates a specific attachment from a specific manual journal by file name |
| [**updateOrCreateBankTransactions**](AccountingApi.md#updateOrCreateBankTransactions) | **POST** /BankTransactions | Updates or creates one or more spent or received money transaction |
| [**updateOrCreateContacts**](AccountingApi.md#updateOrCreateContacts) | **POST** /Contacts | Updates or creates one or more contacts in a Xero organisation |
| [**updateOrCreateCreditNotes**](AccountingApi.md#updateOrCreateCreditNotes) | **POST** /CreditNotes | Updates or creates one or more credit notes |
| [**updateOrCreateEmployees**](AccountingApi.md#updateOrCreateEmployees) | **POST** /Employees | Creates a single new employees used in Xero payrun |
| [**updateOrCreateInvoices**](AccountingApi.md#updateOrCreateInvoices) | **POST** /Invoices | Updates or creates one or more sales invoices or purchase bills |
| [**updateOrCreateItems**](AccountingApi.md#updateOrCreateItems) | **POST** /Items | Updates or creates one or more items |
| [**updateOrCreateManualJournals**](AccountingApi.md#updateOrCreateManualJournals) | **POST** /ManualJournals | Updates or creates a single manual journal |
| [**updateOrCreatePurchaseOrders**](AccountingApi.md#updateOrCreatePurchaseOrders) | **POST** /PurchaseOrders | Updates or creates one or more purchase orders |
| [**updateOrCreateQuotes**](AccountingApi.md#updateOrCreateQuotes) | **POST** /Quotes | Updates or creates one or more quotes |
| [**updateOrCreateRepeatingInvoices**](AccountingApi.md#updateOrCreateRepeatingInvoices) | **POST** /RepeatingInvoices | Creates or deletes one or more repeating invoice templates |
| [**updatePurchaseOrder**](AccountingApi.md#updatePurchaseOrder) | **POST** /PurchaseOrders/{PurchaseOrderID} | Updates a specific purchase order |
| [**updatePurchaseOrderAttachmentByFileName**](AccountingApi.md#updatePurchaseOrderAttachmentByFileName) | **POST** /PurchaseOrders/{PurchaseOrderID}/Attachments/{FileName} | Updates a specific attachment for a specific purchase order by filename |
| [**updateQuote**](AccountingApi.md#updateQuote) | **POST** /Quotes/{QuoteID} | Updates a specific quote |
| [**updateQuoteAttachmentByFileName**](AccountingApi.md#updateQuoteAttachmentByFileName) | **POST** /Quotes/{QuoteID}/Attachments/{FileName} | Updates a specific attachment from a specific quote by filename |
| [**updateReceipt**](AccountingApi.md#updateReceipt) | **POST** /Receipts/{ReceiptID} | Updates a specific draft expense claim receipts |
| [**updateReceiptAttachmentByFileName**](AccountingApi.md#updateReceiptAttachmentByFileName) | **POST** /Receipts/{ReceiptID}/Attachments/{FileName} | Updates a specific attachment on a specific expense claim receipts by file name |
| [**updateRepeatingInvoice**](AccountingApi.md#updateRepeatingInvoice) | **POST** /RepeatingInvoices/{RepeatingInvoiceID} | Deletes a specific repeating invoice template |
| [**updateRepeatingInvoiceAttachmentByFileName**](AccountingApi.md#updateRepeatingInvoiceAttachmentByFileName) | **POST** /RepeatingInvoices/{RepeatingInvoiceID}/Attachments/{FileName} | Updates a specific attachment from a specific repeating invoices by file name |
| [**updateTaxRate**](AccountingApi.md#updateTaxRate) | **POST** /TaxRates | Updates tax rates |
| [**updateTrackingCategory**](AccountingApi.md#updateTrackingCategory) | **POST** /TrackingCategories/{TrackingCategoryID} | Updates a specific tracking category |
| [**updateTrackingOptions**](AccountingApi.md#updateTrackingOptions) | **POST** /TrackingCategories/{TrackingCategoryID}/Options/{TrackingOptionID} | Updates a specific option for a specific tracking category |


<a name="createAccount"></a>
# **createAccount**
> Accounts createAccount(xero-tenant-id, Account, Idempotency-Key)

Creates a new chart of accounts

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Account** | [**Account**](../Models/Account.md)| Account object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Accounts**](../Models/Accounts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createAccountAttachmentByFileName"></a>
# **createAccountAttachmentByFileName**
> Attachments createAccountAttachmentByFileName(xero-tenant-id, AccountID, FileName, body, Idempotency-Key)

Creates an attachment on a specific account

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createBankTransactionAttachmentByFileName"></a>
# **createBankTransactionAttachmentByFileName**
> Attachments createBankTransactionAttachmentByFileName(xero-tenant-id, BankTransactionID, FileName, body, Idempotency-Key)

Creates an attachment for a specific bank transaction by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createBankTransactionHistoryRecord"></a>
# **createBankTransactionHistoryRecord**
> HistoryRecords createBankTransactionHistoryRecord(xero-tenant-id, BankTransactionID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific bank transactions

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createBankTransactions"></a>
# **createBankTransactions**
> BankTransactions createBankTransactions(xero-tenant-id, BankTransactions, summarizeErrors, unitdp, Idempotency-Key)

Creates one or more spent or received money transaction

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactions** | [**BankTransactions**](../Models/BankTransactions.md)| BankTransactions with an array of BankTransaction objects in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**BankTransactions**](../Models/BankTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createBankTransfer"></a>
# **createBankTransfer**
> BankTransfers createBankTransfer(xero-tenant-id, BankTransfers, Idempotency-Key)

Creates a bank transfer

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransfers** | [**BankTransfers**](../Models/BankTransfers.md)| BankTransfers with array of BankTransfer objects in request body | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**BankTransfers**](../Models/BankTransfers.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createBankTransferAttachmentByFileName"></a>
# **createBankTransferAttachmentByFileName**
> Attachments createBankTransferAttachmentByFileName(xero-tenant-id, BankTransferID, FileName, body, Idempotency-Key)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createBankTransferHistoryRecord"></a>
# **createBankTransferHistoryRecord**
> HistoryRecords createBankTransferHistoryRecord(xero-tenant-id, BankTransferID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific bank transfer

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createBatchPayment"></a>
# **createBatchPayment**
> BatchPayments createBatchPayment(xero-tenant-id, BatchPayments, summarizeErrors, Idempotency-Key)

Creates one or many batch payments for invoices

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BatchPayments** | [**BatchPayments**](../Models/BatchPayments.md)| BatchPayments with an array of Payments in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**BatchPayments**](../Models/BatchPayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createBatchPaymentHistoryRecord"></a>
# **createBatchPaymentHistoryRecord**
> HistoryRecords createBatchPaymentHistoryRecord(xero-tenant-id, BatchPaymentID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific batch payment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BatchPaymentID** | **UUID**| Unique identifier for BatchPayment | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createBrandingThemePaymentServices"></a>
# **createBrandingThemePaymentServices**
> PaymentServices createBrandingThemePaymentServices(xero-tenant-id, BrandingThemeID, PaymentServices, Idempotency-Key)

Creates a new custom payment service for a specific branding theme

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BrandingThemeID** | **UUID**| Unique identifier for a Branding Theme | [default to null] |
| **PaymentServices** | [**PaymentServices**](../Models/PaymentServices.md)| PaymentServices array with PaymentService object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**PaymentServices**](../Models/PaymentServices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createContactAttachmentByFileName"></a>
# **createContactAttachmentByFileName**
> Attachments createContactAttachmentByFileName(xero-tenant-id, ContactID, FileName, body, Idempotency-Key)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createContactGroup"></a>
# **createContactGroup**
> ContactGroups createContactGroup(xero-tenant-id, ContactGroups, Idempotency-Key)

Creates a contact group

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactGroups** | [**ContactGroups**](../Models/ContactGroups.md)| ContactGroups with an array of names in request body | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ContactGroups**](../Models/ContactGroups.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createContactGroupContacts"></a>
# **createContactGroupContacts**
> Contacts createContactGroupContacts(xero-tenant-id, ContactGroupID, Contacts, Idempotency-Key)

Creates contacts to a specific contact group

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactGroupID** | **UUID**| Unique identifier for a Contact Group | [default to null] |
| **Contacts** | [**Contacts**](../Models/Contacts.md)| Contacts with array of contacts specifying the ContactID to be added to ContactGroup in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Contacts**](../Models/Contacts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createContactHistory"></a>
# **createContactHistory**
> HistoryRecords createContactHistory(xero-tenant-id, ContactID, HistoryRecords, Idempotency-Key)

Creates a new history record for a specific contact

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createContacts"></a>
# **createContacts**
> Contacts createContacts(xero-tenant-id, Contacts, summarizeErrors, Idempotency-Key)

Creates multiple contacts (bulk) in a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Contacts** | [**Contacts**](../Models/Contacts.md)| Contacts with an array of Contact objects to create in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Contacts**](../Models/Contacts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createCreditNoteAllocation"></a>
# **createCreditNoteAllocation**
> Allocations createCreditNoteAllocation(xero-tenant-id, CreditNoteID, Allocations, summarizeErrors, Idempotency-Key)

Creates allocation for a specific credit note

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **Allocations** | [**Allocations**](../Models/Allocations.md)| Allocations with array of Allocation object in body of request. | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Allocations**](../Models/Allocations.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createCreditNoteAttachmentByFileName"></a>
# **createCreditNoteAttachmentByFileName**
> Attachments createCreditNoteAttachmentByFileName(xero-tenant-id, CreditNoteID, FileName, body, IncludeOnline, Idempotency-Key)

Creates an attachment for a specific credit note

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **IncludeOnline** | **Boolean**| Allows an attachment to be seen by the end customer within their online invoice | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createCreditNoteHistory"></a>
# **createCreditNoteHistory**
> HistoryRecords createCreditNoteHistory(xero-tenant-id, CreditNoteID, HistoryRecords, Idempotency-Key)

Retrieves history records of a specific credit note

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createCreditNotes"></a>
# **createCreditNotes**
> CreditNotes createCreditNotes(xero-tenant-id, CreditNotes, summarizeErrors, unitdp, Idempotency-Key)

Creates a new credit note

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNotes** | [**CreditNotes**](../Models/CreditNotes.md)| Credit Notes with array of CreditNote object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**CreditNotes**](../Models/CreditNotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createCurrency"></a>
# **createCurrency**
> Currencies createCurrency(xero-tenant-id, Currency, Idempotency-Key)

Create a new currency for a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Currency** | [**Currency**](../Models/Currency.md)| Currency object in the body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Currencies**](../Models/Currencies.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createEmployees"></a>
# **createEmployees**
> Employees createEmployees(xero-tenant-id, Employees, summarizeErrors, Idempotency-Key)

Creates new employees used in Xero payrun

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Employees** | [**Employees**](../Models/Employees.md)| Employees with array of Employee object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Employees**](../Models/Employees.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createExpenseClaimHistory"></a>
# **createExpenseClaimHistory**
> HistoryRecords createExpenseClaimHistory(xero-tenant-id, ExpenseClaimID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific expense claim

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ExpenseClaimID** | **UUID**| Unique identifier for a ExpenseClaim | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createExpenseClaims"></a>
# **createExpenseClaims**
> ExpenseClaims createExpenseClaims(xero-tenant-id, ExpenseClaims, Idempotency-Key)

Creates expense claims

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ExpenseClaims** | [**ExpenseClaims**](../Models/ExpenseClaims.md)| ExpenseClaims with array of ExpenseClaim object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ExpenseClaims**](../Models/ExpenseClaims.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createInvoiceAttachmentByFileName"></a>
# **createInvoiceAttachmentByFileName**
> Attachments createInvoiceAttachmentByFileName(xero-tenant-id, InvoiceID, FileName, body, IncludeOnline, Idempotency-Key)

Creates an attachment for a specific invoice or purchase bill by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **IncludeOnline** | **Boolean**| Allows an attachment to be seen by the end customer within their online invoice | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createInvoiceHistory"></a>
# **createInvoiceHistory**
> HistoryRecords createInvoiceHistory(xero-tenant-id, InvoiceID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific invoice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createInvoices"></a>
# **createInvoices**
> Invoices createInvoices(xero-tenant-id, Invoices, summarizeErrors, unitdp, Idempotency-Key)

Creates one or more sales invoices or purchase bills

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Invoices** | [**Invoices**](../Models/Invoices.md)| Invoices with an array of invoice objects in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Invoices**](../Models/Invoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createItemHistory"></a>
# **createItemHistory**
> HistoryRecords createItemHistory(xero-tenant-id, ItemID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific item

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ItemID** | **UUID**| Unique identifier for an Item | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createItems"></a>
# **createItems**
> Items createItems(xero-tenant-id, Items, summarizeErrors, unitdp, Idempotency-Key)

Creates one or more items

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Items** | [**Items**](../Models/Items.md)| Items with an array of Item objects in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Items**](../Models/Items.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createLinkedTransaction"></a>
# **createLinkedTransaction**
> LinkedTransactions createLinkedTransaction(xero-tenant-id, LinkedTransaction, Idempotency-Key)

Creates linked transactions (billable expenses)

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **LinkedTransaction** | [**LinkedTransaction**](../Models/LinkedTransaction.md)| LinkedTransaction object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**LinkedTransactions**](../Models/LinkedTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createManualJournalAttachmentByFileName"></a>
# **createManualJournalAttachmentByFileName**
> Attachments createManualJournalAttachmentByFileName(xero-tenant-id, ManualJournalID, FileName, body, Idempotency-Key)

Creates a specific attachment for a specific manual journal by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createManualJournalHistoryRecord"></a>
# **createManualJournalHistoryRecord**
> HistoryRecords createManualJournalHistoryRecord(xero-tenant-id, ManualJournalID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific manual journal

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createManualJournals"></a>
# **createManualJournals**
> ManualJournals createManualJournals(xero-tenant-id, ManualJournals, summarizeErrors, Idempotency-Key)

Creates one or more manual journals

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournals** | [**ManualJournals**](../Models/ManualJournals.md)| ManualJournals array with ManualJournal object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ManualJournals**](../Models/ManualJournals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createOverpaymentAllocations"></a>
# **createOverpaymentAllocations**
> Allocations createOverpaymentAllocations(xero-tenant-id, OverpaymentID, Allocations, summarizeErrors, Idempotency-Key)

Creates a single allocation for a specific overpayment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **OverpaymentID** | **UUID**| Unique identifier for a Overpayment | [default to null] |
| **Allocations** | [**Allocations**](../Models/Allocations.md)| Allocations array with Allocation object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Allocations**](../Models/Allocations.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createOverpaymentHistory"></a>
# **createOverpaymentHistory**
> HistoryRecords createOverpaymentHistory(xero-tenant-id, OverpaymentID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific overpayment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **OverpaymentID** | **UUID**| Unique identifier for a Overpayment | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPayment"></a>
# **createPayment**
> Payments createPayment(xero-tenant-id, Payment, Idempotency-Key)

Creates a single payment for invoice or credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Payment** | [**Payment**](../Models/Payment.md)| Request body with a single Payment object | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Payments**](../Models/Payments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPaymentHistory"></a>
# **createPaymentHistory**
> HistoryRecords createPaymentHistory(xero-tenant-id, PaymentID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific payment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PaymentID** | **UUID**| Unique identifier for a Payment | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPaymentService"></a>
# **createPaymentService**
> PaymentServices createPaymentService(xero-tenant-id, PaymentServices, Idempotency-Key)

Creates a payment service

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PaymentServices** | [**PaymentServices**](../Models/PaymentServices.md)| PaymentServices array with PaymentService object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**PaymentServices**](../Models/PaymentServices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPayments"></a>
# **createPayments**
> Payments createPayments(xero-tenant-id, Payments, summarizeErrors, Idempotency-Key)

Creates multiple payments for invoices or credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Payments** | [**Payments**](../Models/Payments.md)| Payments array with Payment object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Payments**](../Models/Payments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPrepaymentAllocations"></a>
# **createPrepaymentAllocations**
> Allocations createPrepaymentAllocations(xero-tenant-id, PrepaymentID, Allocations, summarizeErrors, Idempotency-Key)

Allows you to create an Allocation for prepayments

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PrepaymentID** | **UUID**| Unique identifier for a PrePayment | [default to null] |
| **Allocations** | [**Allocations**](../Models/Allocations.md)| Allocations with an array of Allocation object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Allocations**](../Models/Allocations.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPrepaymentHistory"></a>
# **createPrepaymentHistory**
> HistoryRecords createPrepaymentHistory(xero-tenant-id, PrepaymentID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific prepayment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PrepaymentID** | **UUID**| Unique identifier for a PrePayment | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPurchaseOrderAttachmentByFileName"></a>
# **createPurchaseOrderAttachmentByFileName**
> Attachments createPurchaseOrderAttachmentByFileName(xero-tenant-id, PurchaseOrderID, FileName, body, Idempotency-Key)

Creates attachment for a specific purchase order

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createPurchaseOrderHistory"></a>
# **createPurchaseOrderHistory**
> HistoryRecords createPurchaseOrderHistory(xero-tenant-id, PurchaseOrderID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific purchase orders

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createPurchaseOrders"></a>
# **createPurchaseOrders**
> PurchaseOrders createPurchaseOrders(xero-tenant-id, PurchaseOrders, summarizeErrors, Idempotency-Key)

Creates one or more purchase orders

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrders** | [**PurchaseOrders**](../Models/PurchaseOrders.md)| PurchaseOrders with an array of PurchaseOrder object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**PurchaseOrders**](../Models/PurchaseOrders.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createQuoteAttachmentByFileName"></a>
# **createQuoteAttachmentByFileName**
> Attachments createQuoteAttachmentByFileName(xero-tenant-id, QuoteID, FileName, body, Idempotency-Key)

Creates attachment for a specific quote

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createQuoteHistory"></a>
# **createQuoteHistory**
> HistoryRecords createQuoteHistory(xero-tenant-id, QuoteID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific quote

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createQuotes"></a>
# **createQuotes**
> Quotes createQuotes(xero-tenant-id, Quotes, summarizeErrors, Idempotency-Key)

Create one or more quotes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Quotes** | [**Quotes**](../Models/Quotes.md)| Quotes with an array of Quote object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Quotes**](../Models/Quotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createReceipt"></a>
# **createReceipt**
> Receipts createReceipt(xero-tenant-id, Receipts, unitdp, Idempotency-Key)

Creates draft expense claim receipts for any user

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Receipts** | [**Receipts**](../Models/Receipts.md)| Receipts with an array of Receipt object in body of request | |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Receipts**](../Models/Receipts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createReceiptAttachmentByFileName"></a>
# **createReceiptAttachmentByFileName**
> Attachments createReceiptAttachmentByFileName(xero-tenant-id, ReceiptID, FileName, body, Idempotency-Key)

Creates an attachment on a specific expense claim receipts by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createReceiptHistory"></a>
# **createReceiptHistory**
> HistoryRecords createReceiptHistory(xero-tenant-id, ReceiptID, HistoryRecords, Idempotency-Key)

Creates a history record for a specific receipt

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createRepeatingInvoiceAttachmentByFileName"></a>
# **createRepeatingInvoiceAttachmentByFileName**
> Attachments createRepeatingInvoiceAttachmentByFileName(xero-tenant-id, RepeatingInvoiceID, FileName, body, Idempotency-Key)

Creates an attachment from a specific repeating invoices by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="createRepeatingInvoiceHistory"></a>
# **createRepeatingInvoiceHistory**
> HistoryRecords createRepeatingInvoiceHistory(xero-tenant-id, RepeatingInvoiceID, HistoryRecords, Idempotency-Key)

Creates a  history record for a specific repeating invoice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |
| **HistoryRecords** | [**HistoryRecords**](../Models/HistoryRecords.md)| HistoryRecords containing an array of HistoryRecord objects in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createRepeatingInvoices"></a>
# **createRepeatingInvoices**
> RepeatingInvoices createRepeatingInvoices(xero-tenant-id, RepeatingInvoices, summarizeErrors, Idempotency-Key)

Creates one or more repeating invoice templates

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoices** | [**RepeatingInvoices**](../Models/RepeatingInvoices.md)| RepeatingInvoices with an array of repeating invoice objects in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**RepeatingInvoices**](../Models/RepeatingInvoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createTaxRates"></a>
# **createTaxRates**
> TaxRates createTaxRates(xero-tenant-id, TaxRates, Idempotency-Key)

Creates one or more tax rates

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TaxRates** | [**TaxRates**](../Models/TaxRates.md)| TaxRates array with TaxRate object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**TaxRates**](../Models/TaxRates.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createTrackingCategory"></a>
# **createTrackingCategory**
> TrackingCategories createTrackingCategory(xero-tenant-id, TrackingCategory, Idempotency-Key)

Create tracking categories

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TrackingCategory** | [**TrackingCategory**](../Models/TrackingCategory.md)| TrackingCategory object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**TrackingCategories**](../Models/TrackingCategories.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="createTrackingOptions"></a>
# **createTrackingOptions**
> TrackingOptions createTrackingOptions(xero-tenant-id, TrackingCategoryID, TrackingOption, Idempotency-Key)

Creates options for a specific tracking category

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TrackingCategoryID** | **UUID**| Unique identifier for a TrackingCategory | [default to null] |
| **TrackingOption** | [**TrackingOption**](../Models/TrackingOption.md)| TrackingOption object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**TrackingOptions**](../Models/TrackingOptions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deleteAccount"></a>
# **deleteAccount**
> Accounts deleteAccount(xero-tenant-id, AccountID)

Deletes a chart of accounts

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |

### Return type

[**Accounts**](../Models/Accounts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deleteBatchPayment"></a>
# **deleteBatchPayment**
> BatchPayments deleteBatchPayment(xero-tenant-id, BatchPaymentDelete, Idempotency-Key)

Updates a specific batch payment for invoices and credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BatchPaymentDelete** | [**BatchPaymentDelete**](../Models/BatchPaymentDelete.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**BatchPayments**](../Models/BatchPayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deleteBatchPaymentByUrlParam"></a>
# **deleteBatchPaymentByUrlParam**
> BatchPayments deleteBatchPaymentByUrlParam(xero-tenant-id, BatchPaymentID, BatchPaymentDeleteByUrlParam, Idempotency-Key)

Updates a specific batch payment for invoices and credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BatchPaymentID** | **UUID**| Unique identifier for BatchPayment | [default to null] |
| **BatchPaymentDeleteByUrlParam** | [**BatchPaymentDeleteByUrlParam**](../Models/BatchPaymentDeleteByUrlParam.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**BatchPayments**](../Models/BatchPayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deleteContactGroupContact"></a>
# **deleteContactGroupContact**
> deleteContactGroupContact(xero-tenant-id, ContactGroupID, ContactID)

Deletes a specific contact from a contact group using a unique contact Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactGroupID** | **UUID**| Unique identifier for a Contact Group | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |

### Return type

null (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deleteContactGroupContacts"></a>
# **deleteContactGroupContacts**
> deleteContactGroupContacts(xero-tenant-id, ContactGroupID)

Deletes all contacts from a specific contact group

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactGroupID** | **UUID**| Unique identifier for a Contact Group | [default to null] |

### Return type

null (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="deleteCreditNoteAllocations"></a>
# **deleteCreditNoteAllocations**
> Allocation deleteCreditNoteAllocations(xero-tenant-id, CreditNoteID, AllocationID)

Deletes an Allocation from a Credit Note

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **AllocationID** | **UUID**| Unique identifier for Allocation object | [default to null] |

### Return type

[**Allocation**](../Models/Allocation.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deleteItem"></a>
# **deleteItem**
> deleteItem(xero-tenant-id, ItemID)

Deletes a specific item

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ItemID** | **UUID**| Unique identifier for an Item | [default to null] |

### Return type

null (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deleteLinkedTransaction"></a>
# **deleteLinkedTransaction**
> deleteLinkedTransaction(xero-tenant-id, LinkedTransactionID)

Deletes a specific linked transactions (billable expenses)

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **LinkedTransactionID** | **UUID**| Unique identifier for a LinkedTransaction | [default to null] |

### Return type

null (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deleteOverpaymentAllocations"></a>
# **deleteOverpaymentAllocations**
> Allocation deleteOverpaymentAllocations(xero-tenant-id, OverpaymentID, AllocationID)

Deletes an Allocation from an overpayment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **OverpaymentID** | **UUID**| Unique identifier for a Overpayment | [default to null] |
| **AllocationID** | **UUID**| Unique identifier for Allocation object | [default to null] |

### Return type

[**Allocation**](../Models/Allocation.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deletePayment"></a>
# **deletePayment**
> Payments deletePayment(xero-tenant-id, PaymentID, PaymentDelete, Idempotency-Key)

Updates a specific payment for invoices and credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PaymentID** | **UUID**| Unique identifier for a Payment | [default to null] |
| **PaymentDelete** | [**PaymentDelete**](../Models/PaymentDelete.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Payments**](../Models/Payments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="deletePrepaymentAllocations"></a>
# **deletePrepaymentAllocations**
> Allocation deletePrepaymentAllocations(xero-tenant-id, PrepaymentID, AllocationID)

Deletes an Allocation from a Prepayment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PrepaymentID** | **UUID**| Unique identifier for a PrePayment | [default to null] |
| **AllocationID** | **UUID**| Unique identifier for Allocation object | [default to null] |

### Return type

[**Allocation**](../Models/Allocation.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deleteTrackingCategory"></a>
# **deleteTrackingCategory**
> TrackingCategories deleteTrackingCategory(xero-tenant-id, TrackingCategoryID)

Deletes a specific tracking category

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TrackingCategoryID** | **UUID**| Unique identifier for a TrackingCategory | [default to null] |

### Return type

[**TrackingCategories**](../Models/TrackingCategories.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="deleteTrackingOptions"></a>
# **deleteTrackingOptions**
> TrackingOptions deleteTrackingOptions(xero-tenant-id, TrackingCategoryID, TrackingOptionID)

Deletes a specific option for a specific tracking category

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TrackingCategoryID** | **UUID**| Unique identifier for a TrackingCategory | [default to null] |
| **TrackingOptionID** | **UUID**| Unique identifier for a Tracking Option | [default to null] |

### Return type

[**TrackingOptions**](../Models/TrackingOptions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="emailInvoice"></a>
# **emailInvoice**
> emailInvoice(xero-tenant-id, InvoiceID, RequestEmpty, Idempotency-Key)

Sends a copy of a specific invoice to related contact via email

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **RequestEmpty** | [**RequestEmpty**](../Models/RequestEmpty.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="getAccount"></a>
# **getAccount**
> Accounts getAccount(xero-tenant-id, AccountID)

Retrieves a single chart of accounts by using a unique account Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |

### Return type

[**Accounts**](../Models/Accounts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getAccountAttachmentByFileName"></a>
# **getAccountAttachmentByFileName**
> File getAccountAttachmentByFileName(xero-tenant-id, AccountID, FileName, contentType)

Retrieves an attachment for a specific account by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getAccountAttachmentById"></a>
# **getAccountAttachmentById**
> File getAccountAttachmentById(xero-tenant-id, AccountID, AttachmentID, contentType)

Retrieves a specific attachment from a specific account using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getAccountAttachments"></a>
# **getAccountAttachments**
> Attachments getAccountAttachments(xero-tenant-id, AccountID)

Retrieves attachments for a specific accounts by using a unique account Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getAccounts"></a>
# **getAccounts**
> Accounts getAccounts(xero-tenant-id, If-Modified-Since, where, order)

Retrieves the full chart of accounts

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**Accounts**](../Models/Accounts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransaction"></a>
# **getBankTransaction**
> BankTransactions getBankTransaction(xero-tenant-id, BankTransactionID, unitdp)

Retrieves a single spent or received money transaction by using a unique bank transaction Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |

### Return type

[**BankTransactions**](../Models/BankTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransactionAttachmentByFileName"></a>
# **getBankTransactionAttachmentByFileName**
> File getBankTransactionAttachmentByFileName(xero-tenant-id, BankTransactionID, FileName, contentType)

Retrieves a specific attachment from a specific bank transaction by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getBankTransactionAttachmentById"></a>
# **getBankTransactionAttachmentById**
> File getBankTransactionAttachmentById(xero-tenant-id, BankTransactionID, AttachmentID, contentType)

Retrieves specific attachments from a specific BankTransaction using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getBankTransactionAttachments"></a>
# **getBankTransactionAttachments**
> Attachments getBankTransactionAttachments(xero-tenant-id, BankTransactionID)

Retrieves any attachments from a specific bank transactions

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransactions"></a>
# **getBankTransactions**
> BankTransactions getBankTransactions(xero-tenant-id, If-Modified-Since, where, order, page, unitdp, pageSize)

Retrieves any spent or received money transactions

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **page** | **Integer**| Up to 100 bank transactions will be returned in a single API call with line items details | [optional] [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**BankTransactions**](../Models/BankTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransactionsHistory"></a>
# **getBankTransactionsHistory**
> HistoryRecords getBankTransactionsHistory(xero-tenant-id, BankTransactionID)

Retrieves history from a specific bank transaction using a unique bank transaction Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransfer"></a>
# **getBankTransfer**
> BankTransfers getBankTransfer(xero-tenant-id, BankTransferID)

Retrieves specific bank transfers by using a unique bank transfer Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |

### Return type

[**BankTransfers**](../Models/BankTransfers.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransferAttachmentByFileName"></a>
# **getBankTransferAttachmentByFileName**
> File getBankTransferAttachmentByFileName(xero-tenant-id, BankTransferID, FileName, contentType)

Retrieves a specific attachment on a specific bank transfer by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getBankTransferAttachmentById"></a>
# **getBankTransferAttachmentById**
> File getBankTransferAttachmentById(xero-tenant-id, BankTransferID, AttachmentID, contentType)

Retrieves a specific attachment from a specific bank transfer using a unique attachment ID

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getBankTransferAttachments"></a>
# **getBankTransferAttachments**
> Attachments getBankTransferAttachments(xero-tenant-id, BankTransferID)

Retrieves attachments from a specific bank transfer

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransferHistory"></a>
# **getBankTransferHistory**
> HistoryRecords getBankTransferHistory(xero-tenant-id, BankTransferID)

Retrieves history from a specific bank transfer using a unique bank transfer Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBankTransfers"></a>
# **getBankTransfers**
> BankTransfers getBankTransfers(xero-tenant-id, If-Modified-Since, where, order)

Retrieves all bank transfers

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**BankTransfers**](../Models/BankTransfers.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBatchPayment"></a>
# **getBatchPayment**
> BatchPayments getBatchPayment(xero-tenant-id, BatchPaymentID)

Retrieves a specific batch payment using a unique batch payment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BatchPaymentID** | **UUID**| Unique identifier for BatchPayment | [default to null] |

### Return type

[**BatchPayments**](../Models/BatchPayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBatchPaymentHistory"></a>
# **getBatchPaymentHistory**
> HistoryRecords getBatchPaymentHistory(xero-tenant-id, BatchPaymentID)

Retrieves history from a specific batch payment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BatchPaymentID** | **UUID**| Unique identifier for BatchPayment | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBatchPayments"></a>
# **getBatchPayments**
> BatchPayments getBatchPayments(xero-tenant-id, If-Modified-Since, where, order)

Retrieves either one or many batch payments for invoices

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**BatchPayments**](../Models/BatchPayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBrandingTheme"></a>
# **getBrandingTheme**
> BrandingThemes getBrandingTheme(xero-tenant-id, BrandingThemeID)

Retrieves a specific branding theme using a unique branding theme Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BrandingThemeID** | **UUID**| Unique identifier for a Branding Theme | [default to null] |

### Return type

[**BrandingThemes**](../Models/BrandingThemes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBrandingThemePaymentServices"></a>
# **getBrandingThemePaymentServices**
> PaymentServices getBrandingThemePaymentServices(xero-tenant-id, BrandingThemeID)

Retrieves the payment services for a specific branding theme

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BrandingThemeID** | **UUID**| Unique identifier for a Branding Theme | [default to null] |

### Return type

[**PaymentServices**](../Models/PaymentServices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBrandingThemes"></a>
# **getBrandingThemes**
> BrandingThemes getBrandingThemes(xero-tenant-id)

Retrieves all the branding themes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |

### Return type

[**BrandingThemes**](../Models/BrandingThemes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBudget"></a>
# **getBudget**
> Budgets getBudget(xero-tenant-id, BudgetID, DateTo, DateFrom)

Retrieves a specific budget, which includes budget lines

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BudgetID** | **UUID**| Unique identifier for Budgets | [default to null] |
| **DateTo** | **date**| Filter by start date | [optional] [default to null] |
| **DateFrom** | **date**| Filter by end date | [optional] [default to null] |

### Return type

[**Budgets**](../Models/Budgets.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getBudgets"></a>
# **getBudgets**
> Budgets getBudgets(xero-tenant-id, IDs, DateTo, DateFrom)

Retrieve a list of budgets

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **IDs** | [**List**](../Models/UUID.md)| Filter by BudgetID. Allows you to retrieve a specific individual budget. | [optional] [default to null] |
| **DateTo** | **date**| Filter by start date | [optional] [default to null] |
| **DateFrom** | **date**| Filter by end date | [optional] [default to null] |

### Return type

[**Budgets**](../Models/Budgets.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContact"></a>
# **getContact**
> Contacts getContact(xero-tenant-id, ContactID)

Retrieves a specific contacts in a Xero organisation using a unique contact Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |

### Return type

[**Contacts**](../Models/Contacts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContactAttachmentByFileName"></a>
# **getContactAttachmentByFileName**
> File getContactAttachmentByFileName(xero-tenant-id, ContactID, FileName, contentType)

Retrieves a specific attachment from a specific contact by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getContactAttachmentById"></a>
# **getContactAttachmentById**
> File getContactAttachmentById(xero-tenant-id, ContactID, AttachmentID, contentType)

Retrieves a specific attachment from a specific contact using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getContactAttachments"></a>
# **getContactAttachments**
> Attachments getContactAttachments(xero-tenant-id, ContactID)

Retrieves attachments for a specific contact in a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContactByContactNumber"></a>
# **getContactByContactNumber**
> Contacts getContactByContactNumber(xero-tenant-id, ContactNumber)

Retrieves a specific contact by contact number in a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactNumber** | **String**| This field is read only on the Xero contact screen, used to identify contacts in external systems (max length &#x3D; 50). | [default to null] |

### Return type

[**Contacts**](../Models/Contacts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContactCISSettings"></a>
# **getContactCISSettings**
> CISSettings getContactCISSettings(xero-tenant-id, ContactID)

Retrieves CIS settings for a specific contact in a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |

### Return type

[**CISSettings**](../Models/CISSettings.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContactGroup"></a>
# **getContactGroup**
> ContactGroups getContactGroup(xero-tenant-id, ContactGroupID)

Retrieves a specific contact group by using a unique contact group Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactGroupID** | **UUID**| Unique identifier for a Contact Group | [default to null] |

### Return type

[**ContactGroups**](../Models/ContactGroups.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContactGroups"></a>
# **getContactGroups**
> ContactGroups getContactGroups(xero-tenant-id, where, order)

Retrieves the contact Id and name of each contact group

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**ContactGroups**](../Models/ContactGroups.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContactHistory"></a>
# **getContactHistory**
> HistoryRecords getContactHistory(xero-tenant-id, ContactID)

Retrieves history records for a specific contact

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getContacts"></a>
# **getContacts**
> Contacts getContacts(xero-tenant-id, If-Modified-Since, where, order, IDs, page, includeArchived, summaryOnly, searchTerm, pageSize)

Retrieves all contacts in a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **IDs** | [**List**](../Models/UUID.md)| Filter by a comma separated list of ContactIDs. Allows you to retrieve a specific set of contacts in a single call. | [optional] [default to null] |
| **page** | **Integer**| e.g. page&#x3D;1 - Up to 100 contacts will be returned in a single API call. | [optional] [default to null] |
| **includeArchived** | **Boolean**| e.g. includeArchived&#x3D;true - Contacts with a status of ARCHIVED will be included in the response | [optional] [default to null] |
| **summaryOnly** | **Boolean**| Use summaryOnly&#x3D;true in GET Contacts and Invoices endpoint to retrieve a smaller version of the response object. This returns only lightweight fields, excluding computation-heavy fields from the response, making the API calls quick and efficient. | [optional] [default to false] |
| **searchTerm** | **String**| Search parameter that performs a case-insensitive text search across the Name, FirstName, LastName, ContactNumber and EmailAddress fields. | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**Contacts**](../Models/Contacts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getCreditNote"></a>
# **getCreditNote**
> CreditNotes getCreditNote(xero-tenant-id, CreditNoteID, unitdp)

Retrieves a specific credit note using a unique credit note Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |

### Return type

[**CreditNotes**](../Models/CreditNotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getCreditNoteAsPdf"></a>
# **getCreditNoteAsPdf**
> File getCreditNoteAsPdf(xero-tenant-id, CreditNoteID)

Retrieves credit notes as PDF files

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf

<a name="getCreditNoteAttachmentByFileName"></a>
# **getCreditNoteAttachmentByFileName**
> File getCreditNoteAttachmentByFileName(xero-tenant-id, CreditNoteID, FileName, contentType)

Retrieves a specific attachment on a specific credit note by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getCreditNoteAttachmentById"></a>
# **getCreditNoteAttachmentById**
> File getCreditNoteAttachmentById(xero-tenant-id, CreditNoteID, AttachmentID, contentType)

Retrieves a specific attachment from a specific credit note using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getCreditNoteAttachments"></a>
# **getCreditNoteAttachments**
> Attachments getCreditNoteAttachments(xero-tenant-id, CreditNoteID)

Retrieves attachments for a specific credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getCreditNoteHistory"></a>
# **getCreditNoteHistory**
> HistoryRecords getCreditNoteHistory(xero-tenant-id, CreditNoteID)

Retrieves history records of a specific credit note

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getCreditNotes"></a>
# **getCreditNotes**
> CreditNotes getCreditNotes(xero-tenant-id, If-Modified-Since, where, order, page, unitdp, pageSize)

Retrieves any credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **page** | **Integer**| e.g. page&#x3D;1 – Up to 100 credit notes will be returned in a single API call with line items shown for each credit note | [optional] [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**CreditNotes**](../Models/CreditNotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getCurrencies"></a>
# **getCurrencies**
> Currencies getCurrencies(xero-tenant-id, where, order)

Retrieves currencies for your Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**Currencies**](../Models/Currencies.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getEmployee"></a>
# **getEmployee**
> Employees getEmployee(xero-tenant-id, EmployeeID)

Retrieves a specific employee used in Xero payrun using a unique employee Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **EmployeeID** | **UUID**| Unique identifier for a Employee | [default to null] |

### Return type

[**Employees**](../Models/Employees.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getEmployees"></a>
# **getEmployees**
> Employees getEmployees(xero-tenant-id, If-Modified-Since, where, order)

Retrieves employees used in Xero payrun

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**Employees**](../Models/Employees.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getExpenseClaim"></a>
# **getExpenseClaim**
> ExpenseClaims getExpenseClaim(xero-tenant-id, ExpenseClaimID)

Retrieves a specific expense claim using a unique expense claim Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ExpenseClaimID** | **UUID**| Unique identifier for a ExpenseClaim | [default to null] |

### Return type

[**ExpenseClaims**](../Models/ExpenseClaims.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getExpenseClaimHistory"></a>
# **getExpenseClaimHistory**
> HistoryRecords getExpenseClaimHistory(xero-tenant-id, ExpenseClaimID)

Retrieves history records of a specific expense claim

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ExpenseClaimID** | **UUID**| Unique identifier for a ExpenseClaim | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getExpenseClaims"></a>
# **getExpenseClaims**
> ExpenseClaims getExpenseClaims(xero-tenant-id, If-Modified-Since, where, order)

Retrieves expense claims

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**ExpenseClaims**](../Models/ExpenseClaims.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getInvoice"></a>
# **getInvoice**
> Invoices getInvoice(xero-tenant-id, InvoiceID, unitdp)

Retrieves a specific sales invoice or purchase bill using a unique invoice Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |

### Return type

[**Invoices**](../Models/Invoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getInvoiceAsPdf"></a>
# **getInvoiceAsPdf**
> File getInvoiceAsPdf(xero-tenant-id, InvoiceID)

Retrieves invoices or purchase bills as PDF files

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf

<a name="getInvoiceAttachmentByFileName"></a>
# **getInvoiceAttachmentByFileName**
> File getInvoiceAttachmentByFileName(xero-tenant-id, InvoiceID, FileName, contentType)

Retrieves an attachment from a specific invoice or purchase bill by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getInvoiceAttachmentById"></a>
# **getInvoiceAttachmentById**
> File getInvoiceAttachmentById(xero-tenant-id, InvoiceID, AttachmentID, contentType)

Retrieves a specific attachment from a specific invoices or purchase bills by using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getInvoiceAttachments"></a>
# **getInvoiceAttachments**
> Attachments getInvoiceAttachments(xero-tenant-id, InvoiceID)

Retrieves attachments for a specific invoice or purchase bill

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getInvoiceHistory"></a>
# **getInvoiceHistory**
> HistoryRecords getInvoiceHistory(xero-tenant-id, InvoiceID)

Retrieves history records for a specific invoice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getInvoiceReminders"></a>
# **getInvoiceReminders**
> InvoiceReminders getInvoiceReminders(xero-tenant-id)

Retrieves invoice reminder settings

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |

### Return type

[**InvoiceReminders**](../Models/InvoiceReminders.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getInvoices"></a>
# **getInvoices**
> Invoices getInvoices(xero-tenant-id, If-Modified-Since, where, order, IDs, InvoiceNumbers, ContactIDs, Statuses, page, includeArchived, createdByMyApp, unitdp, summaryOnly, pageSize, searchTerm)

Retrieves sales invoices or purchase bills

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **IDs** | [**List**](../Models/UUID.md)| Filter by a comma-separated list of InvoicesIDs. | [optional] [default to null] |
| **InvoiceNumbers** | [**List**](../Models/String.md)| Filter by a comma-separated list of InvoiceNumbers. | [optional] [default to null] |
| **ContactIDs** | [**List**](../Models/UUID.md)| Filter by a comma-separated list of ContactIDs. | [optional] [default to null] |
| **Statuses** | [**List**](../Models/String.md)| Filter by a comma-separated list Statuses. For faster response times we recommend using these explicit parameters instead of passing OR conditions into the Where filter. | [optional] [default to null] |
| **page** | **Integer**| e.g. page&#x3D;1 – Up to 100 invoices will be returned in a single API call with line items shown for each invoice | [optional] [default to null] |
| **includeArchived** | **Boolean**| e.g. includeArchived&#x3D;true - Invoices with a status of ARCHIVED will be included in the response | [optional] [default to null] |
| **createdByMyApp** | **Boolean**| When set to true you&#39;ll only retrieve Invoices created by your app | [optional] [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **summaryOnly** | **Boolean**| Use summaryOnly&#x3D;true in GET Contacts and Invoices endpoint to retrieve a smaller version of the response object. This returns only lightweight fields, excluding computation-heavy fields from the response, making the API calls quick and efficient. | [optional] [default to false] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |
| **searchTerm** | **String**| Search parameter that performs a case-insensitive text search across the fields e.g. InvoiceNumber, Reference. | [optional] [default to null] |

### Return type

[**Invoices**](../Models/Invoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getItem"></a>
# **getItem**
> Items getItem(xero-tenant-id, ItemID, unitdp)

Retrieves a specific item using a unique item Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ItemID** | **UUID**| Unique identifier for an Item | [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |

### Return type

[**Items**](../Models/Items.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getItemHistory"></a>
# **getItemHistory**
> HistoryRecords getItemHistory(xero-tenant-id, ItemID)

Retrieves history for a specific item

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ItemID** | **UUID**| Unique identifier for an Item | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getItems"></a>
# **getItems**
> Items getItems(xero-tenant-id, If-Modified-Since, where, order, unitdp)

Retrieves items

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |

### Return type

[**Items**](../Models/Items.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getJournal"></a>
# **getJournal**
> Journals getJournal(xero-tenant-id, JournalID)

Retrieves a specific journal using a unique journal Id.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **JournalID** | **UUID**| Unique identifier for a Journal | [default to null] |

### Return type

[**Journals**](../Models/Journals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getJournalByNumber"></a>
# **getJournalByNumber**
> Journals getJournalByNumber(xero-tenant-id, JournalNumber)

Retrieves a specific journal using a unique journal number.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **JournalNumber** | **Integer**| Number of a Journal | [default to null] |

### Return type

[**Journals**](../Models/Journals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getJournals"></a>
# **getJournals**
> Journals getJournals(xero-tenant-id, If-Modified-Since, offset, paymentsOnly)

Retrieves journals

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **offset** | **Integer**| Offset by a specified journal number. e.g. journals with a JournalNumber greater than the offset will be returned | [optional] [default to null] |
| **paymentsOnly** | **Boolean**| Filter to retrieve journals on a cash basis. Journals are returned on an accrual basis by default. | [optional] [default to null] |

### Return type

[**Journals**](../Models/Journals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getLinkedTransaction"></a>
# **getLinkedTransaction**
> LinkedTransactions getLinkedTransaction(xero-tenant-id, LinkedTransactionID)

Retrieves a specific linked transaction (billable expenses) using a unique linked transaction Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **LinkedTransactionID** | **UUID**| Unique identifier for a LinkedTransaction | [default to null] |

### Return type

[**LinkedTransactions**](../Models/LinkedTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getLinkedTransactions"></a>
# **getLinkedTransactions**
> LinkedTransactions getLinkedTransactions(xero-tenant-id, page, LinkedTransactionID, SourceTransactionID, ContactID, Status, TargetTransactionID)

Retrieves linked transactions (billable expenses)

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **page** | **Integer**| Up to 100 linked transactions will be returned in a single API call. Use the page parameter to specify the page to be returned e.g. page&#x3D;1. | [optional] [default to null] |
| **LinkedTransactionID** | **UUID**| The Xero identifier for an Linked Transaction | [optional] [default to null] |
| **SourceTransactionID** | **UUID**| Filter by the SourceTransactionID. Get the linked transactions created from a particular ACCPAY invoice | [optional] [default to null] |
| **ContactID** | **UUID**| Filter by the ContactID. Get all the linked transactions that have been assigned to a particular customer. | [optional] [default to null] |
| **Status** | **String**| Filter by the combination of ContactID and Status. Get  the linked transactions associated to a  customer and with a status | [optional] [default to null] |
| **TargetTransactionID** | **UUID**| Filter by the TargetTransactionID. Get all the linked transactions allocated to a particular ACCREC invoice | [optional] [default to null] |

### Return type

[**LinkedTransactions**](../Models/LinkedTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getManualJournal"></a>
# **getManualJournal**
> ManualJournals getManualJournal(xero-tenant-id, ManualJournalID)

Retrieves a specific manual journal

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |

### Return type

[**ManualJournals**](../Models/ManualJournals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getManualJournalAttachmentByFileName"></a>
# **getManualJournalAttachmentByFileName**
> File getManualJournalAttachmentByFileName(xero-tenant-id, ManualJournalID, FileName, contentType)

Retrieves a specific attachment from a specific manual journal by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getManualJournalAttachmentById"></a>
# **getManualJournalAttachmentById**
> File getManualJournalAttachmentById(xero-tenant-id, ManualJournalID, AttachmentID, contentType)

Allows you to retrieve a specific attachment from a specific manual journal using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getManualJournalAttachments"></a>
# **getManualJournalAttachments**
> Attachments getManualJournalAttachments(xero-tenant-id, ManualJournalID)

Retrieves attachment for a specific manual journal

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getManualJournals"></a>
# **getManualJournals**
> ManualJournals getManualJournals(xero-tenant-id, If-Modified-Since, where, order, page, pageSize)

Retrieves manual journals

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **page** | **Integer**| e.g. page&#x3D;1 – Up to 100 manual journals will be returned in a single API call with line items shown for each overpayment | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**ManualJournals**](../Models/ManualJournals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getManualJournalsHistory"></a>
# **getManualJournalsHistory**
> HistoryRecords getManualJournalsHistory(xero-tenant-id, ManualJournalID)

Retrieves history for a specific manual journal

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getOnlineInvoice"></a>
# **getOnlineInvoice**
> OnlineInvoices getOnlineInvoice(xero-tenant-id, InvoiceID)

Retrieves a URL to an online invoice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |

### Return type

[**OnlineInvoices**](../Models/OnlineInvoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getOrganisationActions"></a>
# **getOrganisationActions**
> Actions getOrganisationActions(xero-tenant-id)

Retrieves a list of the key actions your app has permission to perform in the connected Xero organisation.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |

### Return type

[**Actions**](../Models/Actions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getOrganisationCISSettings"></a>
# **getOrganisationCISSettings**
> CISOrgSettings getOrganisationCISSettings(xero-tenant-id, OrganisationID)

Retrieves the CIS settings for the Xero organistaion.

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **OrganisationID** | **UUID**| The unique Xero identifier for an organisation | [default to null] |

### Return type

[**CISOrgSettings**](../Models/CISOrgSettings.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getOrganisations"></a>
# **getOrganisations**
> Organisations getOrganisations(xero-tenant-id)

Retrieves Xero organisation details

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |

### Return type

[**Organisations**](../Models/Organisations.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getOverpayment"></a>
# **getOverpayment**
> Overpayments getOverpayment(xero-tenant-id, OverpaymentID)

Retrieves a specific overpayment using a unique overpayment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **OverpaymentID** | **UUID**| Unique identifier for a Overpayment | [default to null] |

### Return type

[**Overpayments**](../Models/Overpayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getOverpaymentHistory"></a>
# **getOverpaymentHistory**
> HistoryRecords getOverpaymentHistory(xero-tenant-id, OverpaymentID)

Retrieves history records of a specific overpayment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **OverpaymentID** | **UUID**| Unique identifier for a Overpayment | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getOverpayments"></a>
# **getOverpayments**
> Overpayments getOverpayments(xero-tenant-id, If-Modified-Since, where, order, page, unitdp, pageSize)

Retrieves overpayments

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **page** | **Integer**| e.g. page&#x3D;1 – Up to 100 overpayments will be returned in a single API call with line items shown for each overpayment | [optional] [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**Overpayments**](../Models/Overpayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPayment"></a>
# **getPayment**
> Payments getPayment(xero-tenant-id, PaymentID)

Retrieves a specific payment for invoices and credit notes using a unique payment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PaymentID** | **UUID**| Unique identifier for a Payment | [default to null] |

### Return type

[**Payments**](../Models/Payments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPaymentHistory"></a>
# **getPaymentHistory**
> HistoryRecords getPaymentHistory(xero-tenant-id, PaymentID)

Retrieves history records of a specific payment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PaymentID** | **UUID**| Unique identifier for a Payment | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPaymentServices"></a>
# **getPaymentServices**
> PaymentServices getPaymentServices(xero-tenant-id)

Retrieves payment services

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |

### Return type

[**PaymentServices**](../Models/PaymentServices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPayments"></a>
# **getPayments**
> Payments getPayments(xero-tenant-id, If-Modified-Since, where, order, page, pageSize)

Retrieves payments for invoices and credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **page** | **Integer**| Up to 100 payments will be returned in a single API call | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**Payments**](../Models/Payments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPrepayment"></a>
# **getPrepayment**
> Prepayments getPrepayment(xero-tenant-id, PrepaymentID)

Allows you to retrieve a specified prepayments

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PrepaymentID** | **UUID**| Unique identifier for a PrePayment | [default to null] |

### Return type

[**Prepayments**](../Models/Prepayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPrepaymentHistory"></a>
# **getPrepaymentHistory**
> HistoryRecords getPrepaymentHistory(xero-tenant-id, PrepaymentID)

Retrieves history record for a specific prepayment

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PrepaymentID** | **UUID**| Unique identifier for a PrePayment | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPrepayments"></a>
# **getPrepayments**
> Prepayments getPrepayments(xero-tenant-id, If-Modified-Since, where, order, page, unitdp, pageSize)

Retrieves prepayments

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **page** | **Integer**| e.g. page&#x3D;1 – Up to 100 prepayments will be returned in a single API call with line items shown for each overpayment | [optional] [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**Prepayments**](../Models/Prepayments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPurchaseOrder"></a>
# **getPurchaseOrder**
> PurchaseOrders getPurchaseOrder(xero-tenant-id, PurchaseOrderID)

Retrieves a specific purchase order using a unique purchase order Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |

### Return type

[**PurchaseOrders**](../Models/PurchaseOrders.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPurchaseOrderAsPdf"></a>
# **getPurchaseOrderAsPdf**
> File getPurchaseOrderAsPdf(xero-tenant-id, PurchaseOrderID)

Retrieves specific purchase order as PDF files using a unique purchase order Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf

<a name="getPurchaseOrderAttachmentByFileName"></a>
# **getPurchaseOrderAttachmentByFileName**
> File getPurchaseOrderAttachmentByFileName(xero-tenant-id, PurchaseOrderID, FileName, contentType)

Retrieves a specific attachment for a specific purchase order by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getPurchaseOrderAttachmentById"></a>
# **getPurchaseOrderAttachmentById**
> File getPurchaseOrderAttachmentById(xero-tenant-id, PurchaseOrderID, AttachmentID, contentType)

Retrieves specific attachment for a specific purchase order using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getPurchaseOrderAttachments"></a>
# **getPurchaseOrderAttachments**
> Attachments getPurchaseOrderAttachments(xero-tenant-id, PurchaseOrderID)

Retrieves attachments for a specific purchase order

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPurchaseOrderByNumber"></a>
# **getPurchaseOrderByNumber**
> PurchaseOrders getPurchaseOrderByNumber(xero-tenant-id, PurchaseOrderNumber)

Retrieves a specific purchase order using purchase order number

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderNumber** | **String**| Unique identifier for a PurchaseOrder | [default to null] |

### Return type

[**PurchaseOrders**](../Models/PurchaseOrders.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPurchaseOrderHistory"></a>
# **getPurchaseOrderHistory**
> HistoryRecords getPurchaseOrderHistory(xero-tenant-id, PurchaseOrderID)

Retrieves history for a specific purchase order

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getPurchaseOrders"></a>
# **getPurchaseOrders**
> PurchaseOrders getPurchaseOrders(xero-tenant-id, If-Modified-Since, Status, DateFrom, DateTo, order, page, pageSize)

Retrieves purchase orders

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **Status** | **String**| Filter by purchase order status | [optional] [default to null] [enum: DRAFT, SUBMITTED, AUTHORISED, BILLED, DELETED] |
| **DateFrom** | **String**| Filter by purchase order date (e.g. GET https://.../PurchaseOrders?DateFrom&#x3D;2015-12-01&amp;DateTo&#x3D;2015-12-31 | [optional] [default to null] |
| **DateTo** | **String**| Filter by purchase order date (e.g. GET https://.../PurchaseOrders?DateFrom&#x3D;2015-12-01&amp;DateTo&#x3D;2015-12-31 | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **page** | **Integer**| To specify a page, append the page parameter to the URL e.g. ?page&#x3D;1. If there are 100 records in the response you will need to check if there is any more data by fetching the next page e.g ?page&#x3D;2 and continuing this process until no more results are returned. | [optional] [default to null] |
| **pageSize** | **Integer**| Number of records to retrieve per page | [optional] [default to null] |

### Return type

[**PurchaseOrders**](../Models/PurchaseOrders.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getQuote"></a>
# **getQuote**
> Quotes getQuote(xero-tenant-id, QuoteID)

Retrieves a specific quote using a unique quote Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |

### Return type

[**Quotes**](../Models/Quotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getQuoteAsPdf"></a>
# **getQuoteAsPdf**
> File getQuoteAsPdf(xero-tenant-id, QuoteID)

Retrieves a specific quote as a PDF file using a unique quote Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf

<a name="getQuoteAttachmentByFileName"></a>
# **getQuoteAttachmentByFileName**
> File getQuoteAttachmentByFileName(xero-tenant-id, QuoteID, FileName, contentType)

Retrieves a specific attachment from a specific quote by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getQuoteAttachmentById"></a>
# **getQuoteAttachmentById**
> File getQuoteAttachmentById(xero-tenant-id, QuoteID, AttachmentID, contentType)

Retrieves a specific attachment from a specific quote using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getQuoteAttachments"></a>
# **getQuoteAttachments**
> Attachments getQuoteAttachments(xero-tenant-id, QuoteID)

Retrieves attachments for a specific quote

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getQuoteHistory"></a>
# **getQuoteHistory**
> HistoryRecords getQuoteHistory(xero-tenant-id, QuoteID)

Retrieves history records of a specific quote

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getQuotes"></a>
# **getQuotes**
> Quotes getQuotes(xero-tenant-id, If-Modified-Since, DateFrom, DateTo, ExpiryDateFrom, ExpiryDateTo, ContactID, Status, page, order, QuoteNumber)

Retrieves sales quotes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **DateFrom** | **date**| Filter for quotes after a particular date | [optional] [default to null] |
| **DateTo** | **date**| Filter for quotes before a particular date | [optional] [default to null] |
| **ExpiryDateFrom** | **date**| Filter for quotes expiring after a particular date | [optional] [default to null] |
| **ExpiryDateTo** | **date**| Filter for quotes before a particular date | [optional] [default to null] |
| **ContactID** | **UUID**| Filter for quotes belonging to a particular contact | [optional] [default to null] |
| **Status** | **String**| Filter for quotes of a particular Status | [optional] [default to null] |
| **page** | **Integer**| e.g. page&#x3D;1 – Up to 100 Quotes will be returned in a single API call with line items shown for each quote | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **QuoteNumber** | **String**| Filter by quote number (e.g. GET https://.../Quotes?QuoteNumber&#x3D;QU-0001) | [optional] [default to null] |

### Return type

[**Quotes**](../Models/Quotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReceipt"></a>
# **getReceipt**
> Receipts getReceipt(xero-tenant-id, ReceiptID, unitdp)

Retrieves a specific draft expense claim receipt by using a unique receipt Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |

### Return type

[**Receipts**](../Models/Receipts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReceiptAttachmentByFileName"></a>
# **getReceiptAttachmentByFileName**
> File getReceiptAttachmentByFileName(xero-tenant-id, ReceiptID, FileName, contentType)

Retrieves a specific attachment from a specific expense claim receipts by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getReceiptAttachmentById"></a>
# **getReceiptAttachmentById**
> File getReceiptAttachmentById(xero-tenant-id, ReceiptID, AttachmentID, contentType)

Retrieves a specific attachments from a specific expense claim receipts by using a unique attachment Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getReceiptAttachments"></a>
# **getReceiptAttachments**
> Attachments getReceiptAttachments(xero-tenant-id, ReceiptID)

Retrieves attachments for a specific expense claim receipt

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReceiptHistory"></a>
# **getReceiptHistory**
> HistoryRecords getReceiptHistory(xero-tenant-id, ReceiptID)

Retrieves a history record for a specific receipt

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReceipts"></a>
# **getReceipts**
> Receipts getReceipts(xero-tenant-id, If-Modified-Since, where, order, unitdp)

Retrieves draft expense claim receipts for any user

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |

### Return type

[**Receipts**](../Models/Receipts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getRepeatingInvoice"></a>
# **getRepeatingInvoice**
> RepeatingInvoices getRepeatingInvoice(xero-tenant-id, RepeatingInvoiceID)

Retrieves a specific repeating invoice by using a unique repeating invoice Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |

### Return type

[**RepeatingInvoices**](../Models/RepeatingInvoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getRepeatingInvoiceAttachmentByFileName"></a>
# **getRepeatingInvoiceAttachmentByFileName**
> File getRepeatingInvoiceAttachmentByFileName(xero-tenant-id, RepeatingInvoiceID, FileName, contentType)

Retrieves a specific attachment from a specific repeating invoices by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getRepeatingInvoiceAttachmentById"></a>
# **getRepeatingInvoiceAttachmentById**
> File getRepeatingInvoiceAttachmentById(xero-tenant-id, RepeatingInvoiceID, AttachmentID, contentType)

Retrieves a specific attachment from a specific repeating invoice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |
| **AttachmentID** | **UUID**| Unique identifier for Attachment object | [default to null] |
| **contentType** | **String**| The mime type of the attachment file you are retrieving i.e image/jpg, application/pdf | [default to null] |

### Return type

**File**

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

<a name="getRepeatingInvoiceAttachments"></a>
# **getRepeatingInvoiceAttachments**
> Attachments getRepeatingInvoiceAttachments(xero-tenant-id, RepeatingInvoiceID)

Retrieves attachments from a specific repeating invoice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getRepeatingInvoiceHistory"></a>
# **getRepeatingInvoiceHistory**
> HistoryRecords getRepeatingInvoiceHistory(xero-tenant-id, RepeatingInvoiceID)

Retrieves history record for a specific repeating invoice

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |

### Return type

[**HistoryRecords**](../Models/HistoryRecords.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getRepeatingInvoices"></a>
# **getRepeatingInvoices**
> RepeatingInvoices getRepeatingInvoices(xero-tenant-id, where, order)

Retrieves repeating invoices

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**RepeatingInvoices**](../Models/RepeatingInvoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportAgedPayablesByContact"></a>
# **getReportAgedPayablesByContact**
> ReportWithRows getReportAgedPayablesByContact(xero-tenant-id, contactId, date, fromDate, toDate)

Retrieves report for aged payables by contact

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **contactId** | **UUID**| Unique identifier for a Contact | [default to null] |
| **date** | **date**| The date of the Aged Payables By Contact report | [optional] [default to null] |
| **fromDate** | **date**| filter by the from date of the report e.g. 2021-02-01 | [optional] [default to null] |
| **toDate** | **date**| filter by the to date of the report e.g. 2021-02-28 | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportAgedReceivablesByContact"></a>
# **getReportAgedReceivablesByContact**
> ReportWithRows getReportAgedReceivablesByContact(xero-tenant-id, contactId, date, fromDate, toDate)

Retrieves report for aged receivables by contact

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **contactId** | **UUID**| Unique identifier for a Contact | [default to null] |
| **date** | **date**| The date of the Aged Receivables By Contact report | [optional] [default to null] |
| **fromDate** | **date**| filter by the from date of the report e.g. 2021-02-01 | [optional] [default to null] |
| **toDate** | **date**| filter by the to date of the report e.g. 2021-02-28 | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportBalanceSheet"></a>
# **getReportBalanceSheet**
> ReportWithRows getReportBalanceSheet(xero-tenant-id, date, periods, timeframe, trackingOptionID1, trackingOptionID2, standardLayout, paymentsOnly)

Retrieves report for balancesheet

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **date** | **date**| The date of the Balance Sheet report | [optional] [default to null] |
| **periods** | **Integer**| The number of periods for the Balance Sheet report | [optional] [default to null] |
| **timeframe** | **String**| The period size to compare to (MONTH, QUARTER, YEAR) | [optional] [default to null] [enum: MONTH, QUARTER, YEAR] |
| **trackingOptionID1** | **String**| The tracking option 1 for the Balance Sheet report | [optional] [default to null] |
| **trackingOptionID2** | **String**| The tracking option 2 for the Balance Sheet report | [optional] [default to null] |
| **standardLayout** | **Boolean**| The standard layout boolean for the Balance Sheet report | [optional] [default to null] |
| **paymentsOnly** | **Boolean**| return a cash basis for the Balance Sheet report | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportBankSummary"></a>
# **getReportBankSummary**
> ReportWithRows getReportBankSummary(xero-tenant-id, fromDate, toDate)

Retrieves report for bank summary

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **fromDate** | **date**| filter by the from date of the report e.g. 2021-02-01 | [optional] [default to null] |
| **toDate** | **date**| filter by the to date of the report e.g. 2021-02-28 | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportBudgetSummary"></a>
# **getReportBudgetSummary**
> ReportWithRows getReportBudgetSummary(xero-tenant-id, date, periods, timeframe)

Retrieves report for budget summary

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **date** | **date**| The date for the Bank Summary report e.g. 2018-03-31 | [optional] [default to null] |
| **periods** | **Integer**| The number of periods to compare (integer between 1 and 12) | [optional] [default to null] |
| **timeframe** | **Integer**| The period size to compare to (1&#x3D;month, 3&#x3D;quarter, 12&#x3D;year) | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportExecutiveSummary"></a>
# **getReportExecutiveSummary**
> ReportWithRows getReportExecutiveSummary(xero-tenant-id, date)

Retrieves report for executive summary

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **date** | **date**| The date for the Bank Summary report e.g. 2018-03-31 | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportFromId"></a>
# **getReportFromId**
> ReportWithRows getReportFromId(xero-tenant-id, ReportID)

Retrieves a specific report using a unique ReportID

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReportID** | **String**| Unique identifier for a Report | [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportProfitAndLoss"></a>
# **getReportProfitAndLoss**
> ReportWithRows getReportProfitAndLoss(xero-tenant-id, fromDate, toDate, periods, timeframe, trackingCategoryID, trackingCategoryID2, trackingOptionID, trackingOptionID2, standardLayout, paymentsOnly)

Retrieves report for profit and loss

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **fromDate** | **date**| filter by the from date of the report e.g. 2021-02-01 | [optional] [default to null] |
| **toDate** | **date**| filter by the to date of the report e.g. 2021-02-28 | [optional] [default to null] |
| **periods** | **Integer**| The number of periods to compare (integer between 1 and 12) | [optional] [default to null] |
| **timeframe** | **String**| The period size to compare to (MONTH, QUARTER, YEAR) | [optional] [default to null] [enum: MONTH, QUARTER, YEAR] |
| **trackingCategoryID** | **String**| The trackingCategory 1 for the ProfitAndLoss report | [optional] [default to null] |
| **trackingCategoryID2** | **String**| The trackingCategory 2 for the ProfitAndLoss report | [optional] [default to null] |
| **trackingOptionID** | **String**| The tracking option 1 for the ProfitAndLoss report | [optional] [default to null] |
| **trackingOptionID2** | **String**| The tracking option 2 for the ProfitAndLoss report | [optional] [default to null] |
| **standardLayout** | **Boolean**| Return the standard layout for the ProfitAndLoss report | [optional] [default to null] |
| **paymentsOnly** | **Boolean**| Return cash only basis for the ProfitAndLoss report | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportTenNinetyNine"></a>
# **getReportTenNinetyNine**
> Reports getReportTenNinetyNine(xero-tenant-id, reportYear)

Retrieve reports for 1099

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **reportYear** | **String**| The year of the 1099 report | [optional] [default to null] |

### Return type

[**Reports**](../Models/Reports.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportTrialBalance"></a>
# **getReportTrialBalance**
> ReportWithRows getReportTrialBalance(xero-tenant-id, date, paymentsOnly)

Retrieves report for trial balance

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **date** | **date**| The date for the Trial Balance report e.g. 2018-03-31 | [optional] [default to null] |
| **paymentsOnly** | **Boolean**| Return cash only basis for the Trial Balance report | [optional] [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getReportsList"></a>
# **getReportsList**
> ReportWithRows getReportsList(xero-tenant-id)

Retrieves a list of the organistaions unique reports that require a uuid to fetch

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |

### Return type

[**ReportWithRows**](../Models/ReportWithRows.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getTaxRateByTaxType"></a>
# **getTaxRateByTaxType**
> TaxRates getTaxRateByTaxType(xero-tenant-id, TaxType)

Retrieves a specific tax rate according to given TaxType code

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TaxType** | **String**| A valid TaxType code | [default to null] |

### Return type

[**TaxRates**](../Models/TaxRates.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getTaxRates"></a>
# **getTaxRates**
> TaxRates getTaxRates(xero-tenant-id, where, order)

Retrieves tax rates

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**TaxRates**](../Models/TaxRates.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getTrackingCategories"></a>
# **getTrackingCategories**
> TrackingCategories getTrackingCategories(xero-tenant-id, where, order, includeArchived)

Retrieves tracking categories and options

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |
| **includeArchived** | **Boolean**| e.g. includeArchived&#x3D;true - Categories and options with a status of ARCHIVED will be included in the response | [optional] [default to null] |

### Return type

[**TrackingCategories**](../Models/TrackingCategories.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getTrackingCategory"></a>
# **getTrackingCategory**
> TrackingCategories getTrackingCategory(xero-tenant-id, TrackingCategoryID)

Retrieves specific tracking categories and options using a unique tracking category Id

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TrackingCategoryID** | **UUID**| Unique identifier for a TrackingCategory | [default to null] |

### Return type

[**TrackingCategories**](../Models/TrackingCategories.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getUser"></a>
# **getUser**
> Users getUser(xero-tenant-id, UserID)

Retrieves a specific user

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **UserID** | **UUID**| Unique identifier for a User | [default to null] |

### Return type

[**Users**](../Models/Users.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="getUsers"></a>
# **getUsers**
> Users getUsers(xero-tenant-id, If-Modified-Since, where, order)

Retrieves users

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **If-Modified-Since** | **Date**| Only records created or modified since this timestamp will be returned | [optional] [default to null] |
| **where** | **String**| Filter by an any element | [optional] [default to null] |
| **order** | **String**| Order by an any element | [optional] [default to null] |

### Return type

[**Users**](../Models/Users.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

<a name="postSetup"></a>
# **postSetup**
> ImportSummaryObject postSetup(xero-tenant-id, Setup, Idempotency-Key)

Sets the chart of accounts, the conversion date and conversion balances

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Setup** | [**Setup**](../Models/Setup.md)| Object including an accounts array, a conversion balances array and a conversion date object in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ImportSummaryObject**](../Models/ImportSummaryObject.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateAccount"></a>
# **updateAccount**
> Accounts updateAccount(xero-tenant-id, AccountID, Accounts, Idempotency-Key)

Updates a chart of accounts

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |
| **Accounts** | [**Accounts**](../Models/Accounts.md)| Request of type Accounts array with one Account | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Accounts**](../Models/Accounts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateAccountAttachmentByFileName"></a>
# **updateAccountAttachmentByFileName**
> Attachments updateAccountAttachmentByFileName(xero-tenant-id, AccountID, FileName, body, Idempotency-Key)

Updates attachment on a specific account by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **AccountID** | **UUID**| Unique identifier for Account object | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateBankTransaction"></a>
# **updateBankTransaction**
> BankTransactions updateBankTransaction(xero-tenant-id, BankTransactionID, BankTransactions, unitdp, Idempotency-Key)

Updates a single spent or received money transaction

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |
| **BankTransactions** | [**BankTransactions**](../Models/BankTransactions.md)|  | |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**BankTransactions**](../Models/BankTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateBankTransactionAttachmentByFileName"></a>
# **updateBankTransactionAttachmentByFileName**
> Attachments updateBankTransactionAttachmentByFileName(xero-tenant-id, BankTransactionID, FileName, body, Idempotency-Key)

Updates a specific attachment from a specific bank transaction by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactionID** | **UUID**| Xero generated unique identifier for a bank transaction | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateBankTransferAttachmentByFileName"></a>
# **updateBankTransferAttachmentByFileName**
> Attachments updateBankTransferAttachmentByFileName(xero-tenant-id, BankTransferID, FileName, body, Idempotency-Key)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransferID** | **UUID**| Xero generated unique identifier for a bank transfer | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateContact"></a>
# **updateContact**
> Contacts updateContact(xero-tenant-id, ContactID, Contacts, Idempotency-Key)

Updates a specific contact in a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |
| **Contacts** | [**Contacts**](../Models/Contacts.md)| an array of Contacts containing single Contact object with properties to update | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Contacts**](../Models/Contacts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateContactAttachmentByFileName"></a>
# **updateContactAttachmentByFileName**
> Attachments updateContactAttachmentByFileName(xero-tenant-id, ContactID, FileName, body, Idempotency-Key)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactID** | **UUID**| Unique identifier for a Contact | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateContactGroup"></a>
# **updateContactGroup**
> ContactGroups updateContactGroup(xero-tenant-id, ContactGroupID, ContactGroups, Idempotency-Key)

Updates a specific contact group

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ContactGroupID** | **UUID**| Unique identifier for a Contact Group | [default to null] |
| **ContactGroups** | [**ContactGroups**](../Models/ContactGroups.md)| an array of Contact groups with Name of specific group to update | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ContactGroups**](../Models/ContactGroups.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateCreditNote"></a>
# **updateCreditNote**
> CreditNotes updateCreditNote(xero-tenant-id, CreditNoteID, CreditNotes, unitdp, Idempotency-Key)

Updates a specific credit note

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **CreditNotes** | [**CreditNotes**](../Models/CreditNotes.md)| an array of Credit Notes containing credit note details to update | |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**CreditNotes**](../Models/CreditNotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateCreditNoteAttachmentByFileName"></a>
# **updateCreditNoteAttachmentByFileName**
> Attachments updateCreditNoteAttachmentByFileName(xero-tenant-id, CreditNoteID, FileName, body, Idempotency-Key)

Updates attachments on a specific credit note by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNoteID** | **UUID**| Unique identifier for a Credit Note | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateExpenseClaim"></a>
# **updateExpenseClaim**
> ExpenseClaims updateExpenseClaim(xero-tenant-id, ExpenseClaimID, ExpenseClaims, Idempotency-Key)

Updates a specific expense claims

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ExpenseClaimID** | **UUID**| Unique identifier for a ExpenseClaim | [default to null] |
| **ExpenseClaims** | [**ExpenseClaims**](../Models/ExpenseClaims.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ExpenseClaims**](../Models/ExpenseClaims.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateInvoice"></a>
# **updateInvoice**
> Invoices updateInvoice(xero-tenant-id, InvoiceID, Invoices, unitdp, Idempotency-Key)

Updates a specific sales invoices or purchase bills

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **Invoices** | [**Invoices**](../Models/Invoices.md)|  | |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Invoices**](../Models/Invoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateInvoiceAttachmentByFileName"></a>
# **updateInvoiceAttachmentByFileName**
> Attachments updateInvoiceAttachmentByFileName(xero-tenant-id, InvoiceID, FileName, body, Idempotency-Key)

Updates an attachment from a specific invoices or purchase bill by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **InvoiceID** | **UUID**| Unique identifier for an Invoice | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateItem"></a>
# **updateItem**
> Items updateItem(xero-tenant-id, ItemID, Items, unitdp, Idempotency-Key)

Updates a specific item

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ItemID** | **UUID**| Unique identifier for an Item | [default to null] |
| **Items** | [**Items**](../Models/Items.md)|  | |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Items**](../Models/Items.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateLinkedTransaction"></a>
# **updateLinkedTransaction**
> LinkedTransactions updateLinkedTransaction(xero-tenant-id, LinkedTransactionID, LinkedTransactions, Idempotency-Key)

Updates a specific linked transactions (billable expenses)

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **LinkedTransactionID** | **UUID**| Unique identifier for a LinkedTransaction | [default to null] |
| **LinkedTransactions** | [**LinkedTransactions**](../Models/LinkedTransactions.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**LinkedTransactions**](../Models/LinkedTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateManualJournal"></a>
# **updateManualJournal**
> ManualJournals updateManualJournal(xero-tenant-id, ManualJournalID, ManualJournals, Idempotency-Key)

Updates a specific manual journal

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |
| **ManualJournals** | [**ManualJournals**](../Models/ManualJournals.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ManualJournals**](../Models/ManualJournals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateManualJournalAttachmentByFileName"></a>
# **updateManualJournalAttachmentByFileName**
> Attachments updateManualJournalAttachmentByFileName(xero-tenant-id, ManualJournalID, FileName, body, Idempotency-Key)

Updates a specific attachment from a specific manual journal by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournalID** | **UUID**| Unique identifier for a ManualJournal | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateOrCreateBankTransactions"></a>
# **updateOrCreateBankTransactions**
> BankTransactions updateOrCreateBankTransactions(xero-tenant-id, BankTransactions, summarizeErrors, unitdp, Idempotency-Key)

Updates or creates one or more spent or received money transaction

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **BankTransactions** | [**BankTransactions**](../Models/BankTransactions.md)|  | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**BankTransactions**](../Models/BankTransactions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateContacts"></a>
# **updateOrCreateContacts**
> Contacts updateOrCreateContacts(xero-tenant-id, Contacts, summarizeErrors, Idempotency-Key)

Updates or creates one or more contacts in a Xero organisation

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Contacts** | [**Contacts**](../Models/Contacts.md)|  | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Contacts**](../Models/Contacts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateCreditNotes"></a>
# **updateOrCreateCreditNotes**
> CreditNotes updateOrCreateCreditNotes(xero-tenant-id, CreditNotes, summarizeErrors, unitdp, Idempotency-Key)

Updates or creates one or more credit notes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **CreditNotes** | [**CreditNotes**](../Models/CreditNotes.md)| an array of Credit Notes with a single CreditNote object. | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**CreditNotes**](../Models/CreditNotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateEmployees"></a>
# **updateOrCreateEmployees**
> Employees updateOrCreateEmployees(xero-tenant-id, Employees, summarizeErrors, Idempotency-Key)

Creates a single new employees used in Xero payrun

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Employees** | [**Employees**](../Models/Employees.md)| Employees with array of Employee object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Employees**](../Models/Employees.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateInvoices"></a>
# **updateOrCreateInvoices**
> Invoices updateOrCreateInvoices(xero-tenant-id, Invoices, summarizeErrors, unitdp, Idempotency-Key)

Updates or creates one or more sales invoices or purchase bills

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Invoices** | [**Invoices**](../Models/Invoices.md)|  | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Invoices**](../Models/Invoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateItems"></a>
# **updateOrCreateItems**
> Items updateOrCreateItems(xero-tenant-id, Items, summarizeErrors, unitdp, Idempotency-Key)

Updates or creates one or more items

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Items** | [**Items**](../Models/Items.md)|  | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Items**](../Models/Items.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateManualJournals"></a>
# **updateOrCreateManualJournals**
> ManualJournals updateOrCreateManualJournals(xero-tenant-id, ManualJournals, summarizeErrors, Idempotency-Key)

Updates or creates a single manual journal

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ManualJournals** | [**ManualJournals**](../Models/ManualJournals.md)| ManualJournals array with ManualJournal object in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**ManualJournals**](../Models/ManualJournals.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreatePurchaseOrders"></a>
# **updateOrCreatePurchaseOrders**
> PurchaseOrders updateOrCreatePurchaseOrders(xero-tenant-id, PurchaseOrders, summarizeErrors, Idempotency-Key)

Updates or creates one or more purchase orders

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrders** | [**PurchaseOrders**](../Models/PurchaseOrders.md)|  | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**PurchaseOrders**](../Models/PurchaseOrders.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateQuotes"></a>
# **updateOrCreateQuotes**
> Quotes updateOrCreateQuotes(xero-tenant-id, Quotes, summarizeErrors, Idempotency-Key)

Updates or creates one or more quotes

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **Quotes** | [**Quotes**](../Models/Quotes.md)|  | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Quotes**](../Models/Quotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateOrCreateRepeatingInvoices"></a>
# **updateOrCreateRepeatingInvoices**
> RepeatingInvoices updateOrCreateRepeatingInvoices(xero-tenant-id, RepeatingInvoices, summarizeErrors, Idempotency-Key)

Creates or deletes one or more repeating invoice templates

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoices** | [**RepeatingInvoices**](../Models/RepeatingInvoices.md)| RepeatingInvoices with an array of repeating invoice objects in body of request | |
| **summarizeErrors** | **Boolean**| If false return 200 OK and mix of successfully created objects and any with validation errors | [optional] [default to false] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**RepeatingInvoices**](../Models/RepeatingInvoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updatePurchaseOrder"></a>
# **updatePurchaseOrder**
> PurchaseOrders updatePurchaseOrder(xero-tenant-id, PurchaseOrderID, PurchaseOrders, Idempotency-Key)

Updates a specific purchase order

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |
| **PurchaseOrders** | [**PurchaseOrders**](../Models/PurchaseOrders.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**PurchaseOrders**](../Models/PurchaseOrders.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updatePurchaseOrderAttachmentByFileName"></a>
# **updatePurchaseOrderAttachmentByFileName**
> Attachments updatePurchaseOrderAttachmentByFileName(xero-tenant-id, PurchaseOrderID, FileName, body, Idempotency-Key)

Updates a specific attachment for a specific purchase order by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **PurchaseOrderID** | **UUID**| Unique identifier for an Purchase Order | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateQuote"></a>
# **updateQuote**
> Quotes updateQuote(xero-tenant-id, QuoteID, Quotes, Idempotency-Key)

Updates a specific quote

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |
| **Quotes** | [**Quotes**](../Models/Quotes.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Quotes**](../Models/Quotes.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateQuoteAttachmentByFileName"></a>
# **updateQuoteAttachmentByFileName**
> Attachments updateQuoteAttachmentByFileName(xero-tenant-id, QuoteID, FileName, body, Idempotency-Key)

Updates a specific attachment from a specific quote by filename

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **QuoteID** | **UUID**| Unique identifier for an Quote | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateReceipt"></a>
# **updateReceipt**
> Receipts updateReceipt(xero-tenant-id, ReceiptID, Receipts, unitdp, Idempotency-Key)

Updates a specific draft expense claim receipts

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |
| **Receipts** | [**Receipts**](../Models/Receipts.md)|  | |
| **unitdp** | **Integer**| e.g. unitdp&#x3D;4 – (Unit Decimal Places) You can opt in to use four decimal places for unit amounts | [optional] [default to null] |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Receipts**](../Models/Receipts.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateReceiptAttachmentByFileName"></a>
# **updateReceiptAttachmentByFileName**
> Attachments updateReceiptAttachmentByFileName(xero-tenant-id, ReceiptID, FileName, body, Idempotency-Key)

Updates a specific attachment on a specific expense claim receipts by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **ReceiptID** | **UUID**| Unique identifier for a Receipt | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateRepeatingInvoice"></a>
# **updateRepeatingInvoice**
> RepeatingInvoices updateRepeatingInvoice(xero-tenant-id, RepeatingInvoiceID, RepeatingInvoices, Idempotency-Key)

Deletes a specific repeating invoice template

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |
| **RepeatingInvoices** | [**RepeatingInvoices**](../Models/RepeatingInvoices.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**RepeatingInvoices**](../Models/RepeatingInvoices.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateRepeatingInvoiceAttachmentByFileName"></a>
# **updateRepeatingInvoiceAttachmentByFileName**
> Attachments updateRepeatingInvoiceAttachmentByFileName(xero-tenant-id, RepeatingInvoiceID, FileName, body, Idempotency-Key)

Updates a specific attachment from a specific repeating invoices by file name

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **RepeatingInvoiceID** | **UUID**| Unique identifier for a Repeating Invoice | [default to null] |
| **FileName** | **String**| Name of the attachment | [default to null] |
| **body** | **byte[]**| Byte array of file in body of request | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**Attachments**](../Models/Attachments.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: application/json

<a name="updateTaxRate"></a>
# **updateTaxRate**
> TaxRates updateTaxRate(xero-tenant-id, TaxRates, Idempotency-Key)

Updates tax rates

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TaxRates** | [**TaxRates**](../Models/TaxRates.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**TaxRates**](../Models/TaxRates.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateTrackingCategory"></a>
# **updateTrackingCategory**
> TrackingCategories updateTrackingCategory(xero-tenant-id, TrackingCategoryID, TrackingCategory, Idempotency-Key)

Updates a specific tracking category

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TrackingCategoryID** | **UUID**| Unique identifier for a TrackingCategory | [default to null] |
| **TrackingCategory** | [**TrackingCategory**](../Models/TrackingCategory.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**TrackingCategories**](../Models/TrackingCategories.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

<a name="updateTrackingOptions"></a>
# **updateTrackingOptions**
> TrackingOptions updateTrackingOptions(xero-tenant-id, TrackingCategoryID, TrackingOptionID, TrackingOption, Idempotency-Key)

Updates a specific option for a specific tracking category

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **xero-tenant-id** | **String**| Xero identifier for Tenant | [default to null] |
| **TrackingCategoryID** | **UUID**| Unique identifier for a TrackingCategory | [default to null] |
| **TrackingOptionID** | **UUID**| Unique identifier for a Tracking Option | [default to null] |
| **TrackingOption** | [**TrackingOption**](../Models/TrackingOption.md)|  | |
| **Idempotency-Key** | **String**| This allows you to safely retry requests without the risk of duplicate processing. 128 character max. | [optional] [default to null] |

### Return type

[**TrackingOptions**](../Models/TrackingOptions.md)

### Authorization

[OAuth2](../README.md#OAuth2)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

