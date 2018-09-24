## Hub Embeds

Simple components for embedding unique content in Hub pages.

To use, build the URL for the component you want, then use a Page iFrame card.

## Tables

Embed Base URL: `http://esridc.github.io/hub-embed/hub-embed-table.html`



**Option parameters**:

Parameters can be added to the Base URL with either query `?` or anchor `#`

- `url` - Feature Layer URL (include the layer index, e.g. `/0`)
- `outFields` - Feature fields (attributes) to include in table
- `hiddenFields` - Fields that end-user can show, but is hidden on startup


[Example from Johns Creek, GA](http://esridc.github.io/hub-embed/hub-embed-table.html#url=https://services1.arcgis.com/bqfNVPUK3HOnCFmA/arcgis/rest/services/Financial_Expenditures/FeatureServer/0/&outFields=FiscalYear,FiscalYearPeriod,ServiceCode,FundName,DepartmentCode,Department,ProgramCode,Program,SequenceCode,FunctionDesc,ExpenseCategory,FundType,Vendor,VendorID,VendorZip,PaymentID,PaymentMethod,PaymentDate,PaymentStatus,InvoiceID,InvoiceDate,DraftAmount,CreditAmount,Amount,Description,ExpenseType,PaymentMonth,PaymentMonthYear&hiddenFields=FID,C_Seq,Street,OBJECTID)

[Example from Washington, DC](http://esridc.github.io/hub-embed/hub-embed-table.html#url=https://maps2.dcgis.dc.gov/dcgis/rest/services/FEEDS/MPD/MapServer/0&outFields=*&hiddenFields=OBJECTID,CCN)



Thanks to [Johns Creek](http://datahub.johnscreekga.gov/) for the code.
