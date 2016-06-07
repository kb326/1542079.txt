# 1542079.txt

問1<br>
htmlとcssの作成は省略し、3.から行う。<br>
準備：<br>
SorceTreeを開き、【新規/クローンの作成】から新たなリポジトリの作成を行う。<br>
そして、保存先のパスをhtmlとcssデータのあるファイルを選択し、作成する。<br>
作業ツリーのhtmlとcssデータのチェックをつけ、indexにステージする。<br>
3.4:<br>
htmlとcssのデータをメモ帳上で編集し保存。SourceTreeに戻ってくると、作業ツリーに編集後のデータが記録されている。<br>
5：<br>
データを更新し、その更新データをコミットする。<br>
手順は、作業ツリーにある更新されたデータを選択し、上にある【コミット】を押し、メモに更新の内容を簡単に記録し、コミットするだけである。<br>
この更新を行う前に戻るには、ログを開きコミットの記録を右クリックし【このコミットまでリセット】を行うことで前のデータに戻すことが出来る。<br>

問2<br>
1.ア）hello.htmlを作成し、GitHub上に登録する。<br>
2.ボ）GitHub上でhello.htmlを更新する。<br>
3.ア）SorceTree上でhello.htmlを更新しコミット。更新データをGitHubにプッシュするが、既にGitHub上に別の更新データが存在している。<br>
4.ア）そこでプルを行い、最新のデータをSorceTreeに落とし、その上で更新データを再度コミットする。<br>
5.ア）再度プッシュを行う。<br>
6.ボ）GitHub上のデータがアリスの更新が最新版に変更されている。<br>

問4<br>
コマンドプロンプトを開き、pythonと入力すると起動できる。<br>

問5<br>
シェルのようなキーボードで操作するインタフェースを、(CUI)と呼ぶ。

問6<br>
乗算は**（アスタリスクが2つ）

問7<br>
／は正確な計算での結果が出るが、／／は整数部のみの表示しか行わない。小数点は切り捨てられる。

問8<br>
シングルクオートを使うとそのままの表示になる。<br>
‘あいうえお’　＝　あいうえお

問9<br>
import random #モジュールの読み込み<br>
data = ['goo','choki','pa'] #リストの作成<br>
data_choice = random.choice(data) #ランダム選択<br>
print(data_choice) #結果の表示 <br>

問10<br>
このプログラムはジャンケンを行うプログラムである。<br>

問11<br>
コンソールで起動するには、pythonを起動した上で上記のプログラムを入力する。

問12<br>
pythonのスクリプトの拡張子は（.py）にするのが一般的。

問13<br>
データには型がある。１は（整数）型、‘abc’は（文字）型

問14<br>
【apple = 100, orange = 60】<br>
apple*3 + orange*2 の結果を調べる。<br>
apple * 3 + orange * 2<br>
＝420<br>
また、orange = 120　となったらどうなるか。<br>
orange = 120  //普通に定義しなおせばいい<br>
apple * 3 + orange * 2<br>
＝540

問15<br>
コマンドプロンプトのプロパティを開き、簡易編集をチェックをすると、選択してエンターでコピー、右クリックでペーストが使えるようになる。<br>

問16<br>
0.1 + 0.1 + 0.1<br>
＝0.30000000000000004<br>
浮動小数点の丸め誤差による結果<br>
速さのために精確さを捨てている。

問17<br>
1/10 + 1/10 + 1/10<br>
【Wolfram/Alpha】<br>
＝3/10　or　0.3<br>
こちらはpythonよりも数字が精確で丸め誤差が起こらない。<br>
ちなみにエクセルでも丸め誤差は起きるため、切り上げなどの処理をしないと最終的な計算にズレが生じる。<br>

問18<br>
5 % 2 //割算を行った整数部以下の余りを表示する<br>
＝1<br>
5 ** 2 //乗算を行う<br>
＝25

問19<br>
3 + 7 * 4<br>
＝31<br>
(3 + 7) * 4<br> 
＝40

問20<br>
1 > 0.4 //1は0.4よりも大きい<br>
True<br>
1 < 0.4 //1は0.4よりも小さい<br>
False

問21<br>
1 <= 1 //1は1以下か<br>
1 >= 1 //1は1以上か<br>
True

問22<br>
1 == 1 //1と1は等しいか<br>
True<br>
2 != 2　//2と2は等しくないか<br>
False<br>

問23<br>
i = 3<br>
i += 2 //iに2を足した後、答えをiに代入<br>
i ＝ 5<br>
i -= 2 //iから2を引いた後代入<br>
i ＝ 1<br>
i *= 2 //iと2を掛けた後代入<br>
i ＝ 6<br>
i /= 2 //iを2で割った後代入<br>
i ＝ 1.5<br>
i %= 2　//iを2で割った後整数部以下の余りを代入<br>
i ＝ 1<br>
i **= 2 //iを2乗した後代入<br>
i ＝ 9<br>

問24<br>
len(‛tomorrow’)という関数の呼び出しでは、文字列’tomorrow’は関数lenの（引数）と呼ばれ、結果として得られる整数の８は（戻り値・返り値）と呼ばれる。<br>

問25<br>
len('abcde')<br>
＝5<br>
len(list)<br>
＝3

問26<br>
'abc' + 'xyz'<br>
＝'abcxyz' //文字列の足し算

問27<br>
'python 3.5' //数字と文字の足し算<br>
'python' +　' '　+ str(3.5) //strで数字を文字列に変換できる

問28<br>
list(range(10)) //10個の数字からなるリストの作成<br>
＝[0,1,2,3,4,5,6,7,8,9]<br>
list(range(1,11)) //1から表示し、11個の数字からなるリストの作成<br>
[1,2,3,4,5,6,7,8,9,10]　//0は表示しないだけでカウントされる

問29<br>
list(range(2,22)) //0から数えるので、文字数は実際に表示したい最大数＋1

問30<br>
あるデータ型だけが独自に持っている関数のことを、(メソッド)と呼ぶ。

問31<br>
address = 'Tkyo,Japan'<br>
address.split(',') //''で囲まれた文字　,の位置で分割する<br>
['Tkyo','Japan']

問32<br>
tanuki = 'kaerutanotakotahatakaeru'<br>
tanuki.split('ta')<br>
＝['kaeru', 'no', 'ko', 'ha', 'kaeru']

問33<br>
adress = [A ~ Z]<br>
address.index('T')<br>
＝20<br>
address.index('P')<br>
＝16

.index('文字')<br>
何個目に'文字'が出てくるか検索する関数

問34<br>
upper()<br>
全てを大文字に変換する関数

問35<br>
center()<br>
中央に寄せた文字列にする<br>
count()<br>
始めと終わりを定義し、その間の重複せず出現する回数を表示する。など

問36<br>
lower()<br>
全てを小文字に変換する関数

問37-40<br>
オプショナル

問41<br>
date_a = date(2008,1,1)<br>
date_b = date(2009,1,1)<br>
result = date_b - date_a<br>
print(result) <br>
＝366 day,0:00:00

問42<br>
date_a.year<br>
＝2008<br>
date_a.month<br>
＝1<br>
date_a.day<br>
＝1

問43<br>
today = date.today()<br>
born = date(1997,1,17)<br>
kei = today - born<br>
print(kei)<br>
＝7081 day

問44<br>
date.weekday(date.today())<br>
＝1 //火曜日 <br>
date.weekday(2008,1,1)<br>
＝1 //火曜日

問45
書きました。

問46-48<br>
オプショナル

問49<br>
from datetime import *<br>
datetime(2016,6,7)<br>
＝datetime.datetime(2016,6,7,0,0)

問50<br>
date.today()<br>
＝datetime.date(2016,6,7)

問51<dr>
from datetime import *<br>
today = date.today()<br>
birthday = date(1997, 1, 17)<br>
life = today - birthday<br>
print(life.days)<br>
＝7081　day

問52<br>
モジュールはpythonの定義で、データ型はデータの種類のこと。<br>
この二つの関係性を例えるならば、モジュールは本の分類（娯楽誌、教材、図鑑など）で、データ型はジャンル。

問53<br>
list_int = [0,1,2,3]<br>
list_mix = [2,1.732,'test']<br>
list_int + list_mix<br>
＝[0,1,2,3,2,1.732,'test']

問54<br>
list_mix[1]<br>
＝1.732

問55<br>
len(list_int)<br>
＝4

問56<br>
list_int[-1]<br>
＝3　//-は後ろから何番目、というもの

問57<br>
list_int[0] = -1<br>
＝[-1,1,2,3]　//データは上書きされる

問58<br>
list_int.insert(1,5)<br>
＝[-1,5,1,2,3]

問59<br>
list_int.pop(1)<br>
＝[-1,1,2,3]

問60<br>
list_mix.remove('test')<br>
＝[2,1.732]

問61<br>
list2 = list_int + list_mix<br>
元のデータが消えずに新しいデータが作れる

問62<>br>
list_int.extend(list_mix)<br>
データにデータを直接入れる方法。

問63<br>
list_f = [0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55]<br>
list_f[:3]<br>
＝[0,1,1,]

問64<br>
list_a = list_f[1：]<br>
＝[1, 1, 2, 3, 5, 8, 13, 21, 34, 55]<br>

問65<br>
list_b = list_f[:4]<br>
＝[0,1,1,]

問66<br>
list_test = [4, 9, 3, -1, 0]<br>
list_test.reverse( )<br>
＝[0,-1,3,9,4]

問67<br>
list_test.sorted( ) //ソートしたデータが別データとして保存される<br>
＝[-1,0,3,4,9]

問68<br>
list.test = [4, 9, 3, -1, 0]<br>
list_test.sort( )　//ソートしたデータが上書きされる<br>
＝[-1,0,3,4,9]

問69<br>
list_test.sorted( )<br>
list_test.reverse( )<br>
＝[9,4,3,0,-1]

問70<br>
list_os = ['windows','mac','linux','BeOS']<br>
list_os.sort()<br>
＝['BeOS', 'linux', 'mac', 'windows']

list_os = ['Windows',Mmac','linux','BeOS']<br>
list_os.sort()<br>
＝['BeOS', 'Mac', 'Windows', 'linux']

問71<br>
オプショナル

問72<br>
test = [ ]　//空のリスト<br>
test.append(1000)<br>
test.append(500)<br>
test.append(100)<br>
＝[1000,500,100]

問73<br>
リストにも，いろいろなメソッドがある。<br>
要素を追加するときは（insert）が使われ、要素を昇順に並べ替えるには（sort）を使う。<br>
（reverse）を使うと，リストの並びが逆順になる。

問74<br>
list = []<br>
list.append('Ninja')<br>
list.append('samurai')<br>
list.append('katana')<br>
list.append('tonosama')<br>
＝['ninja','samurai','katana','tonosama']

問75<br>
最初に見つけた方が消える。

問76<br>
country_code = {1:'america',39:'Italia',86:'china'}

問77<br>
81 in country_code<br>
False<br>
39 in country_code<br>
True

問78<br>
{1: 'america',86: 'china', 39: 'Italia'}<br>
country_code[81] = 'Japan'<br>
＝{1: 'america', 81: 'Japan', 86: 'china', 39: 'Italia'}

問79<br>
country_code[81] = 'Nippon'<br>
＝{1: 'america', 81: 'Nippon', 86: 'china', 39: 'Italia'}

問80<br>
country_code[1] = 'Nippon'<br>
＝{1: 'Nippon', 81: 'Nippon', 86: 'china', 39: 'Italia'}

問81<br>
{1: 'Nippon', 81: 'Nippon', 86: 'china', 39: 'Italia'}<br>
country_code.pop(1)<br>
＝{81: 'Nippon', 86: 'china', 39: 'Italia'}

問82<br>
aaa = {}<br>
aaa[140] = 'orange'<br>
aaa[100] = 'apple'<br>
＝{'orange': 140,'apple': 100}

問83<br>
fruit = {}<br>
fruit[3] = 'orange'<br>
fruit[11] = 'apple'<br>
fruit[45] = 'meron'<br>
fruit[67] = 'banana'<br>
＝{3:'orange',11:'apple',45:'meron',67:'banana'}

問84<br>
date_a = (1, 2, 3, '100 yen')<br>
[ ]：新しい要素の追加、削除が出来る<br>
( )：数の変化がない。追加、削除が出来ない<br>
しかし、list( )で名前を付けると[ ]と同じように使える

問85<br>
list(date_a)<br>
＝[1, 2, 3, '100 yen']

問86<br>
set.add(1,2,3)<br>
＝(1,2,3)

問87<br>
1 in set<br>
True<br>
10 in set<br>
False

問88<br>
list_a = list(set)

問89<br>
list_a + list_b <br>
list_a.extend(list_b)<br>
list_a.insert(list_b)<br>
list_a.append(list_b)



