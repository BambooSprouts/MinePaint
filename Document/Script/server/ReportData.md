# Methods
* [getReportData](#getreportdata)
* [searchReportData](#searchreportdata)
* [reportDataManager](#reportdatamanager)
### getReportData
`getReportData(): reportData`
* **Return**
	* *reportData*
> ワールドに保存されたreportDataを取得します。
### searchReportData
`searchReportData(uuid): {player: mc.Player, reportType: reportOptions, reason: string}`
`searchReportData(): uuid.v4[]`
> reportDataの値を取得します。
* **Parameters**
	* `uuid?`: *uuid.v4 | null*
* **Returns**
	* *`{player: mc.Player, reportType: reportOptions, reason: string}`*
	* *uuid.v4*
### reportDataManager
`reportDataManager(option, data): void`
> reportDataを管理します。
* **Parameters**
	* `option`: *reportDataManagerOptions*
	* `data`: *ReportDataStack | uuid.v4*
