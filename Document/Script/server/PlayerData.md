# Methods
* [getPlayerData](#getplayerdata)
* [searchPlayerData](#searchplayerdata)
* [setPlayerData](#setplayerdata)
### getPlayerData
`getPlayerData(): playerData`
> ワールドに保存されたplayerDataを取得します。
* **Returns**
	* *Object.playerData*
### searchPlayerData
`searchPlayerData(type, player): string[]`  
`searchPlayerData(type): mc.Player.nameTag[]`
> playerDataの値を取得します。
* **Parameters**
	* `type`: *playerDataTypeOptions*
	* `player?`: *mc.Player | null*
* **Returns**
	* *string[]*
	* *mc.Player.nameTag[]*
### setPlayerData
`setPlayerData(data): void`
> playerDataを操作します。
* **Parameters**
	* `data`: *PlayerDataStack*
