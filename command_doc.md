# コマンド一覧

## 【オブジェクト】
KeyCode：
```
キーコード一覧が格納されたEnum。
詳細は一番後ろに
```
Dir：
```
方向が格納されたEnum
Up,Down,Right,Leftがある。
```

Pos：

```
座標情報を格納するオブジェクト。
new Pos(x座標,y座標)という風に生成できる。
Pos.X,Pos.Yで値を取得できる。
```

TileType：

```
Tileのタイプが格納押されたEnum
Tank,Rock,Hole,Emptyがある。
```


## 【メソッド】

Move：
	戦車を移動させることが出来る。

	型
	Move(Dir 方向,number 移動するマス数)

	例
	Move(Math.random() * 4, 1)
	(ランダムな方向に移動します。)

MoveDir：
	戦車の向きを変更することが出来る。

	型
	MoveDir(Dir 方向)

	例
	MoveDir(Dir.Up)
	(上方向に向きます)
	
ShotDir：
	射撃攻撃の方向を変更することが出来る。

	型
	ShotDir(number 角度)

	例
	ShotDir(Math.random() * 360)
	(ランダムな方向に射撃攻撃の方向を変更します。)

GetPosRad：
	現在の自分の位置から指定した座標の角度を取得します。

	型
	GetPosRad(Pos ターゲットのPos)

	例
	GetPosRad(new Pos(4,6))
	((4,6)のマスへ向けた角度を取得)
	
GetTileType：
	指定した座標の 'TileType' を取得します。

	例
	GetTileType(Pos TileTypeを取得したいマス)

	例
	GetTileType(new Pos(7,9))
	((7,9)マスのTileType取得)

Print：
	コンソールに値を出力します。

	型
	Print(any 表示する値)

	例
	Print(new Pos(5, 10))
	（Posの内容がコンソールに出力します。）

Wait：
	指定した時間(ms)、待ちます。

	型
	Wait(number ミリ秒)

	例
	Wait(2000)
	(2秒待つ)

GetKey：
	キーが入力されている場合、trueを返します。

	型
	GetKey(KeyCode キーコード)

	例
	if (GetKey(KeyCode.S))
	(Sキーが入力されていたらtrue)

GetKeyDown：
	キーが入力された時、trueを返します。

	型
	GetKeyDown(KeyCode キーコード)

	例
	if (GetKeyDown(KeyCode.S))
	(Sキーが押された時にtrue)

GetKeyUp：
	キーが離された時、trueを返します。

	型
	GetKeyUp(KeyCode キーコード)

	例
	if (GetKeyUp(KeyCode.S))
	(Sキーが離された時にtrue)

【KeyCode一覧】

| | | |
|---|---|---|
|Backspace|Delete|Tab|
|Clear|Return|Pause|
|Escape|Space|UpArrow|
|DownArrow|RightArrow|LeftArrow
|A|B|C|
|D|E|F|
|G|H|I|
|J|K|L|
|M|N|O|
|P|Q|R|
|S|T|U|
|V|W|X|
|Y|Z| |
