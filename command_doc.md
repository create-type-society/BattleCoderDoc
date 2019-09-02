# コマンド一覧

## 【オブジェクト】
KeyCode：
キーコード一覧が格納されたEnum。
詳細は一番後ろに

Dir：
方向が格納されたEnum
Up,Down,Right,Leftがある。

Pos：
	座標情報を格納するオブジェクト。
	new Pos(x座標,y座標)という風に生成できる。
	Pos.X,Pos.Yで値を取得できる。

TileType：
	Tileのタイプが格納押されたEnum
	Tank,Rock,Hole,Emptyがある。


## 【メソッド】

Move：
	戦車を移動させることが出来る。

	例
	Move(方向, 移動するマス数)

	応用例
	Move(Math.random() * 4, 1)
	（ランダムな方向に移動します。）

MoveDir：
	戦車の向きを変更することが出来る。

	例
	MoveDir(方向)
	
ShotDir：
	射撃攻撃の方向を変更することが出来る。

	例
	ShotDir(角度)

	応用例
	ShotDir(Math.random() * 360)
	（ランダムな方向に射撃攻撃の方向を変更します。）

GetPosRad：
	現在の座標から指定した座標の角度を取得します。

	例
	GetPosRad(new Pos(x座標,y座標))
	
GetTileType：
	指定した座標の 'TileType' を取得します。

	例
	GetTileType(new Pos(x座標,y座標))

Print：
	コンソールに値を出力します。

	例
	Print(値)

	応用例
	Print(new Pos(5, 10))
	（Posの内容がコンソールに出力します。）

Wait：
	指定した時間(ms)、待ちます。

	例
	Wait(ミリ秒)

GetKey：
	キーが入力されている場合、trueを返します。

	例
	GetKey(キーコード)

	応用例
	if (GetKey(KeyCode.S))

GetKeyDown：
	キーが入力された時、trueを返します。

	例
	GetKey(キーコード)

	応用例
	if (GetKey(KeyCode.S))

GetKeyUp：
	キーが離された時、trueを返します。

	例
	GetKey(キーコード)

	応用例
	if (GetKey(KeyCode.S))

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
