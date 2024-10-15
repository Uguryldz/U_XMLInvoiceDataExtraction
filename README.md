# U_XMLInvoiceDataExtraction
XML format invoices are processed and converted into a system-compatible format. With this process, invoices can be easily exported and edited.

## Arguments

- **InvoiceXMLPath**: Full file path of the invoice in XML format.  
  Example: `C:\Faturalar\UFatura001.xml`

- **ExcelOutputFolder**: Path to the folder where converted Excel files will be saved.  
  This argument is only functional when `ExcelSave` is enabled.  
  Example: `C:\Faturalar\`

- **ExcelSave**: When set to **Enabled**, the invoice data will be saved as an Excel file in the specified folder, with the original XML file's name and a `.xlsx` extension. The default value is **Disabled**.

- **InvoiceDetailsDT**: A DataTable that contains the details of each product or service on the invoice (e.g., product name, quantity, unit price).

- **InvoiceFooterDT**: A DataTable that holds the total invoice information, such as total amount, VAT, discounts, and other additional details.

- **InvoiceHeaderDT**: A DataTable that contains the general information related to the invoice (e.g., invoice number, date, customer details).



![SaveU Image](https://github.com/Uguryldz/U_XMLInvoiceDataExtraction/blob/main/image/SaveU.png)
