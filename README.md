# psk_act

PC-8801エミュレータ、M88はLinuxのwineでも動きます。  
アクションゲームの.d88イメージファイル(Psk_act.d88,IT.d88)。  

M88.exeと、( M88　改+ rel 2.21 18/10/04　バージョンが良い)  
ROMファイル等は、別途手に入れて下さい。キーボードの「１」「２」「３」、  
「↓」「←」「→」「↑」がテンキーの「１」「２」「３」、「２」「４」「６」「８」に対応します。  
M88.exeにはデフォルトでは、リセット時にカラーパレットが初期化されないバグがあるので、  
N88-V1(S)modeで動かして下さい。M88改＋で、快適にゲームをするには、  
「Control」→「Config...」から、「CPU」タブで、CPUクロックを２MHｚ位にして、  
「音」タブの「高精度合成」にチェックを入れ、「画面」タブの、  
「画面の偶数ラインを表示する」にチェックを入れて下さい。  

Pack'n Boy,Galack,StarStruck,Internal Troubleは、  
フルキーボードのテンキーを使うので、テンキーが付いてないノートパソコンでは、  
キーマップを一時的に変更する必要があります。  
それ用の実行スクリプト（m88k)と、キーマップファイル(xmodemap0,xmodemap1)  
を置いておきます。

Internal Troubleにはバグがあります。緑色の「顔」を打ち倒した時、そこが、次の  
ステージでの、見えない敵になります。
