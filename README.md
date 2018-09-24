## Hub Embeds

Simple components for embedding unique content in Hub pages.

To use, build the URL for the component you want, then use a Page iFrame card.

These components are currently _in development_ and [feedback](https://github.com/esridc/hub-embed/issues) is very welcome.

## Tables

Embed Base URL: `http://esridc.github.io/hub-embed/hub-embed-table.html`



**Option parameters**:

Parameters can be added to the Base URL with either query `?` or anchor `#`

- `url` - Feature Layer URL (include the layer index, e.g. `/0`)
- `outFields` - Feature fields (attributes) to include in table
- `hiddenFields` - Fields that end-user can show, but is hidden on startup


[Example from Johns Creek, GA](http://esridc.github.io/hub-embed/hub-embed-table.html#url=https://services1.arcgis.com/bqfNVPUK3HOnCFmA/arcgis/rest/services/Financial_Expenditures/FeatureServer/0/&outFields=FiscalYear,FiscalYearPeriod,ServiceCode,FundName,DepartmentCode,Department,ProgramCode,Program,SequenceCode,FunctionDesc,ExpenseCategory,FundType,Vendor,VendorID,VendorZip,PaymentID,PaymentMethod,PaymentDate,PaymentStatus,InvoiceID,InvoiceDate,DraftAmount,CreditAmount,Amount,Description,ExpenseType,PaymentMonth,PaymentMonthYear&hiddenFields=FID,C_Seq,Street,OBJECTID)

[Example from Washington, DC](http://esridc.github.io/hub-embed/hub-embed-table.html#url=https://maps2.dcgis.dc.gov/dcgis/rest/services/FEEDS/MPD/MapServer/0&outFields=*&hiddenFields=OBJECTID,CCN)


Thanks to [Johns Creek](http://datahub.johnscreekga.gov/) for the example.

### License

Copyright &copy; 2018 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

> http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [LICENSE](./LICENSE) file.
