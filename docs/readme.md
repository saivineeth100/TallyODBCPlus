# Tally ODBC Plus
This TDL adds extra tables on top of Default ODBC tables

| Table Name | Description |
| ------------- | ------------- |
| AC_CompanyCollection | List of companies opened in Tally (Excludes Group companies) |
| AC_Groups | List of groups in all opened companies |
| AC_Ledgers | List of Ledgers in all opened companies |
| AC_VchTypes | List of VoucherTypes in all opened companies |
| AC_Vouchers | List of Vouchers in all opened companies |
| AC_VoucherAllLedgerEntries | List of LedgerEntries in all opened companies |
| AC_VoucherLedgerBillAllocations | List of BillAllocations in all opened companies |
| AC_VoucherAllInventoryEntries | List of InventoryEntries in all opened companies |

> [!NOTE]
> Will be adding more tables soon ..

## Features
- Supports Multiple Companies
- Extract Custom period that can different from selected period in Tally
- Added Foreign keys
- Add child tables like LedgerEntries, BillAllocations, InventoryEntries, BatchAllocations etc..,

> [!TIP]
> If you like or using this TDL dont forget to star and sponser

## Tired of These Tally ODBC Limitations?
- Only selected company data is availiable
- Only First level of data is availaible as tables
- Data will be availaible based on selected period in UI, means if selected period is 1st April 2024 to  30 April 2024, ODBC data covers only data related to April 2024 only , we cannot acess before or after data

Tally ODBC Plus solves these problems!

## Tutorials
We will be creating tutorials on how to create reports, dashboards based on Tally ODBC plus in this [channel](https://www.youtube.com/@accountingcompanion) , specifically these playlists 

- [Tally to Excel](https://www.youtube.com/playlist?list=PLXk2wj8z1UsW6xDwXcV_426aQJ4k6uvNu)
- [Tally to PowerBI](https://www.youtube.com/playlist?list=PLXk2wj8z1UsVnLpOXKGZ4DIMxnMwzzNjz)

> [!NOTE]
> Subscribe to channel and enable notification to get notified when videos are uploaded

## Need Custom Reports?
If you want me to create custom reports for you then contact us contact@accountingcompanion.com
> [!NOTE]
> This TDL or Default ODBC is ideal for companies that has low volume of data say less than 5,000 vouchers per year , numbers may depend on system config also, but you got the point, if your data is huge then ODBC is not good choice


## Huge Data Case
If you have huge data I dont receommend using this ODBC approach as this may hang tally.

Use XML approach with your favorite language to sync data in chunks to some database and use that DB to create reports.

I already curated [XMLS that are useful for Tally Integration](https://documenter.getpostman.com/view/13855108/TzeRpAMt)

If you are using C# then you can use [TallyConnector nugget](https://www.nuget.org/packages/TallyConnector/), It is also  [opensource](https://github.com/Accounting-Companion/TallyConnector)

We also developed a [Sync Tool(not open source)](https://github.com/Accounting-Companion/TallyPowerBI.Docs) that can sync data from Tally to various databases like SQLServer,MYSQL etc..,

If you want custom tool to be build for you with source code access then contact us at contact@accountingcompanion.com, 
you can refer pricing here for [custom solution](https://www.upwork.com/services/product/development-it-a-fantastic-app-that-integrates-tally-tally-prime-with-any-application-1376166703485251584?ref=fl_profile)

