# Methods
* [getOreData](#getoredata)
* [searchOreData](#searchoredata)
* [oreDataManager](#oredatamanager)
### getOreData
`getOreData(): oreData`
* **Return**
	* *oreData*
> ワールドに保存されたoreDataを取得します。
### searchOreData
`searchOreData(location): {time: number, ore: string}`
`searchOreData(): uuid.v4[]`
> oreDataの値を取得します。
* **Parameters**
	* `location?`: *mc.Location | null*
* **Returns**
	* *`{time: number, ore: string}`*
	* *mc.Location[]*
### oreDataManager
`oreDataManager(option, data): void`
> oreDataを管理します。
* **Parameters**
	* `option`: *oreDataManagerOptions*
	* `data`: *OreDataStack | mc.Location*
