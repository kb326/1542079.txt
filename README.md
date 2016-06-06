# 1542079.txt

問1
htmlとcssの作成は省略し、3.から行う。
準備：
SorceTreeを開き、【新規/クローンの作成】から新たなリポジトリの作成を行う。
そして、保存先のパスをhtmlとcssデータのあるファイルを選択し、作成する。
作業ツリーのhtmlとcssデータのチェックをつけ、indexにステージする。
3.4:
htmlとcssのデータをメモ帳上で編集し保存。SourceTreeに戻ってくると、作業ツリーに編集後のデータが記録されている。
5：
データを更新し、その更新データをコミットする。
手順は、作業ツリーにある更新されたデータを選択し、上にある【コミット】を押し、メモに更新の内容を簡単に記録し、コミットするだけである。
この更新を行う前に戻るには、ログを開きコミットの記録を右クリックし【このコミットまでリセット】を行うことで前のデータに戻すことが出来る。

問2
1.ア）hello.htmlを作成し、GitHub上に登録する。
2.ボ）GitHub上でhello.htmlを更新する。
3.ア）SorceTree上でhello.htmlを更新しコミット。更新データをGitHubにプッシュするが、既にGitHub上に別の更新データが存在している。
4.ア）そこでプルを行い、最新のデータをSorceTreeに落とし、その上で更新データを再度コミットする。
5.ア）再度プッシュを行う。
6.ボ）GitHub上のデータがアリスの更新が最新版に変更されている。

問4
コマンドプロンプトを開き、pythonと入力すると起動できる。

問5
シェルのようなキーボードで操作するインタフェースを、(CUI)と呼ぶ。

問6
乗算は**（アスタリスクが2つ）

問7
／は正確な計算での結果が出るが、／／は整数部のみの表示しか行わない。小数点は切り捨てられる。

問8
シングルクオートを使うとそのままの表示になる。
‘あいうえお’＝あいうえお

問9
import random #モジュールの読み込み
data = ['goo','choki','pa'] #リストの作成
data_choice = random.choice(data) #ランダム選択
print(data_choice) #結果の表示 

問10
このプログラムはジャンケンを行うプログラムである。

問11
コンソールで起動するには、pythonを起動した上で上記のプログラムを入力する。

問12
pythonのスクリプトの拡張子は（.py）にするのが一般的。

問13
データには型がある。１は（整数）型、‘abc’は（文字）型

問14
【apple = 100, orange = 60】
apple*3 + orange*2 の結果を調べる。

apple * 3 + orange * 2
＝420

また、orange = 120　となったらどうなるか。

orange = 120  //普通に定義しなおせばいい
apple * 3 + orange * 2
＝540

問15
コマンドプロンプトのプロパティを開き、簡易編集をチェックをすると、選択してエンターでコピー、右クリックでペーストが使えるようになる。

問16
0.1 + 0.1 + 0.1
＝0.30000000000000004
浮動小数点の丸め誤差による結果
速さのために精確さを捨てている。

問17
1/10 + 1/10 + 1/10
【Wolfram/Alpha】
＝3/10　or　0.3
こちらはpythonよりも数字が精確で丸め誤差が起こらない。
ちなみにエクセルでも丸め誤差は起きるため、切り上げなどの処理をしないと最終的な計算にズレが生じる。

問18
5 % 2 //割算を行った整数部以下の余りを表示する
＝1
5 ** 2 //乗算を行う
＝25

問19
3 + 7 * 4
＝31
(3 + 7) * 4 
＝40

問20
1 > 0.4 //1は0.4よりも大きい
True
1 < 0.4 //1は0.4よりも小さい
False

問21
1 <= 1 //1は1以下か
1 >= 1 //1は1以上か
True

問22
1 == 1 //1と1は等しいか
True
2 != 2　//2と2は等しくないか
False

問23
i = 3
i += 2 //iに2を足した後、答えをiに代入
i ＝ 5
i -= 2 //iから2を引いた後代入
i ＝ 1
i *= 2 //iと2を掛けた後代入
i ＝ 6
i /= 2 //iを2で割った後代入
i ＝ 1.5
i %= 2　//iを2で割った後整数部以下の余りを代入
i ＝ 1
i **= 2 //iを2乗した後代入
i ＝ 9

問24
len(‛tomorrow’)という関数の呼び出しでは、文字列’tomorrow’は関数lenの（引数）と呼ばれ、結果として得られる整数の８は（戻り値・返り値）と呼ばれる。

問25
len('abcde')
＝5
len(list)
＝3

問26
'abc' + 'xyz'
＝'abcxyz' //文字列の足し算

問27
'python 3.5' //数字と文字の足し算
'python' +　' '　+ str(3.5) //strで数字を文字列に変換できる

問28
list(range(10)) //10個の数字からなるリストの作成
＝[0,1,2,3,4,5,6,7,8,9]
list(range(1,11)) //1から表示し、11個の数字からなるリストの作成
[1,2,3,4,5,6,7,8,9,10]　//0は表示しないだけでカウントされる

問29
list(range(2,22)) //0から数えるので、文字数は実際に表示したい最大数＋1

問30
あるデータ型だけが独自に持っている関数のことを、(メソッド)と呼ぶ。

問31
address = 'Tkyo,Japan'
address.split(',') //''で囲まれた文字　,の位置で分割する
['Tkyo','Japan']

問32
tanuki = 'kaerutanotakotahatakaeru'
tanuki.split('ta')
＝['kaeru', 'no', 'ko', 'ha', 'kaeru']

問33
adress = [A ~ Z]
address.index('T')
＝20
address.index('P')
＝16

.index('文字')
何個目に'文字'が出てくるか検索する関数

問34
upper()
全てを大文字に変換する関数

問35
center()
中央に寄せた文字列にする
count()
始めと終わりを定義し、その間の重複せず出現する回数を表示する
など

問36
lower()
全てを小文字に変換する関数

問37-40
オプショナル

問41


