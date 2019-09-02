# コマンド一覧

##  【オブジェクト】
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


【メソッド】
Move：
	戦車を移動させることが出来る。

	例
	Move(方向, 移動するマス数)

	応用例
	Move(Math.random() * 4, 1)
	
MoveDir：
	戦車の向きを変更する出来る。

	例
	

ShotDir：

GetPosRad：

GetTileType：

Print：

Wait：

GetKey：

GetKeyDown：

GetKeyUp：

【KeyCode一覧】

Backspace
Delete
Tab
Clear
Return
Pause
Escape
Space
UpArrow
DownArrow
RightArrow
LeftArrow
A
B
C
D
E
F
G
H
I
J
K
L
M
N
O
P
Q
R
S
T
U
V
W
X
Y
Z
