# 7DaysToDie No Trader Mod Pack

*a21(b324)で少し動かしてみた感じでは、特に問題なく動くと思います。*

*Maybe compatible a21(b324)*

### これは何

[7DaysToDie](https://7daystodie.com)というサバイバルゾンビホードクラフトゲームのModパックです。

以下のModが入っています:

- ~~DisableTraderTypeA~~ : トレーダー縛りMod（建物ごと消去）*1 *2 ***5 (important)**
- DisableTraderTypeB : トレーダー縛りMod（トレーダーNPCだけ消去 : トレーダーの敷地に入ると赤字エラーが出るうえワープします）*1
- DisableTraderTypeC : トレーダー縛りMod（トレーダー24時間閉店 : トレーダーの敷地に入るとワープします）*1
- CraftSolarCellBank : ソーラーセルとソーラーバンクのレシピ追加 : 電気技師（ワイヤリング101の本）Lv75が必要です
- CraftWaterFilter : ウォーターフィルターのレシピ追加 : 作業場（フォージアヘッドの本）Lv2が必要です
- FixJpTranslate : 公式日本語を少し修正 *3
- ~~CraftFirstAidBandageFromBandage : 普通の包帯とアロエクリームで救急包帯を作るレシピの追加~~ *4

*1 全部入れたままだとDisableTraderTypeAが優先されますが、どれか一つだけで残りは消しても問題ないです。  
*2 恐らくトレーダーの建物が初期スポーンの起点になっているため、初期スポーン地点が全マップ中からランダムになります。荒れ地とか雪山とか湖の中とかにスポーンする可能性があります。  
*3 他の日本語化MODが入っている場合、削除して問題ありません。  
*4 公式でこのレシピになったので削除しました。  
***5 今のところ DisableTraderTypeA は a21-b324 で動いていません。XMLの記述を変える必要がありそうなんですが、正しい記述をまだ見つけられていません。**

### What's this

This is Mod Pack for [7DaysToDie](https://7daystodie.com) survival zombie horde craft game.

Includes Mods:

- ~~DisableTraderTypeA~~ : Remove trader with trader Building *1 *2 ***5 (important)**
- DisableTraderTypeB : Remove trader npc : show console error and you will warp, when approaching the trader area *1
- DisableTraderTypeC : Trader is closed 24 hours all time : you will warp, when approaching the trader area *1
- CraftSolarCellBank : Add recipe to SolarCell and SolarBank : Require to Electrician (book of Wiring 101) level 75
- CraftWaterFilter : Add recipe to WaterFilter : Require to Workstations (bool of Forge Ahead) Lv2
- FixJpTranslate : Japanese correction a little *3
- ~~CraftFirstAidBandageFromBandage : Require Physician perk (vanilla default) and normal bandage with aloe cream~~ *4

*1 If you leave all of them in, DisableTraderTypeA will be given priority, but you can erase the rest with just one of them.  
*2 You have random initial player spawn because maybe trader building is starting point for initial spawn. wasteland, snow mountains, lake inside, etc...  
*3 If installed other Japanese translate mod, you can remove it.  
*4 Removed this mod because official recipe changes to same.  
***5 CAN'T DISABLE trader spawn at DisableTraderTypeA in a21-b324. I haven't found right wrote yet, probably i need to change write the XML.**

### 使い方

1. mkgaskDisableTraderModPack.zipを[リリースページ](https://github.com/mkgask/mkgask7dtdNoTraderMod/releases)からダウンロードし、展開してください。
1. 展開して出てきた各フォルダーを、お好みに応じて7DaysToDie.exeと同じフォルダーにあるModsフォルダー内にコピーしたりしなかったりしてください。
  もしModsフォルダーが無かった場合は作成してください。
1. 7DaysToDieを起動し、新規にランダムマップを作成して遊んでください。

### Usage

1. Download "mkgaskDisableTraderModPack.zip" from [Releases](https://github.com/mkgask/mkgask7dtdNoTraderMod/releases) and extract.
1. You can copy or not copy each extracted folder to "Mods" folder in "7DaysToDie.exe" same folder.  
  if not exists "Mods" folder, create "Mods" folder.
1.  Start 7DaysToDie, create new random map and enjoy play.

### 注意事項

- TypeAをインストールした場合は、プレイヤーの初期スポーン地点がランダムになります。  
  荒れ地や雪山、湖の中などにスポーンする場合があります。
- 本Modlet導入後、ランダムマップを新規に作成してプレイしてください。  
  既存のマップで遊べるかは未確認です。

### Warning

- Player initial spawn will be randomized if install DisableTraderTypeA Mod.
  It may spawn in wastelands, snowy mountains, lakes, etc.
- You can create new random map when enable this Modlet.  
  Not confirmed to play in exist maps.

### ちなみに

オススメ設定はトレーダーなし、エアドロップなし、ルート品再補充なしです。  
敵がゾンビから飲食物になり、サバイバルがより楽しめます。  
お好みでルート品入手率を下げるのも面白いです。

### As a side note

Recommended settings are NO trader and NO air drop and, NO loot respawn.  
Enemies become food and drink from zombies, and you can enjoy survival more.  
I think you can more enjoy for rate down loot getting parameter.

### バージョン情報

2023/07/01
CraftWaterFilter : 0.1.1 : 追加

2023/06/17  
DisableTraderTypeA : 0.2.1 : トレーダー削除できなくなっていたので修正  
その他のMOD : 0.1.1 : Modinfo.xmlを新しいフォーマットに対応

### Versions

07/01/2023
CraftWaterFilter : 0.1.1 : added

06/17/2023  
DisableTraderTypeA : 0.2.1 : Fixed to don't disable trader building.  
Other mods : 0.1.1 : Replaced new Modinfo.xml Format.
