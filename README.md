# practice
test

## 2026-01-26 

今日の学習-Git Hubの練習


## 2026-01-27 

今日の学習-①GitHub　起動・記録　②単語調べ「push」＿ローカルPCで作成保存したコミットをリモート(GitHubのリポジトリ)に送ること


## 2026-01-28

今日の学習-①GitHub　Desktop 導入・アカウント連携

分からなかったこと-　ダウンロード手順　※英語読めない

明日の学習予定-　※続き

## 2026-01-29 

今日の学習-　practice リポジトリを GitHub Desktop で管理できる状態にする

⑴practiceリポジトリをclone　⑵VS CODEで編集可能

分からなかったこと-単語の意味 Fetch,Commit,push

明日の学習予定-「VS Code」、「GitHub　Desktop」を用いて勉強記録

## 今日1月29日(木)時点できること
GitHub Desktop をインストール・起動

GitHubにログイン

リポジトリをClone

VS Codeで編集

Commit

Fetch → Push

WebのGitHubで反映確認

## 2026-01-30

今日の学習-勉強記録継続　by　「VS Code」「GitHub　Desktop」

README（文章）&HTML（コード）をCommit・Push

## 2026-01-31

今日の学習

・新リポジトリ（HTML練習専用）の作成

・html・cssファイルの作成＆連携

・用語調べ

「Publish repository」ーパソコン上のローカルリポジトリをGitHub上のリモートリポジトリに新規作成＆アップすること

「Initial commit」ー最初のコミット。変更履歴の起点。

「Push origin」ーローカルリポジトリ上の変更（コミット）をリモートリポジトリ上に反映させること

## 2026-02-01

今日の学習

・GitHub Pagesで全世界に公開

・css変数（:root）

・：hover、transitionプロパティ

## 2026-02-02

今日の学習

・復習：：hover、transitionプロパティ　by「プロフボタン追加」

・js:「クリック反応」を実装

## 2026-02-03

今日の学習

・js:「クリック処理」を実装　※クリックされると必ず同じ処理
　id重複の不具合を修正

- addEventListener を使ってクリックイベントを実装
- 変数でクリック回数を管理
- id はページ内で一意にする（重複しない）必要があると理解した

・js:「クリック処理」※条件によって処理を変える

-if文による条件分岐で、回数に応じた表示切り替えを行った

## 2026-02-04

今日の学習

※忙しいため、GitHub起動と学習ログ更新のみ実施

## 2026-02-05

今日の学習

※時間が限られていたため、Pagesの表示確認と学習ログ更新のみ実施

## 2026-02-06

今日の学習

※時間が限られていたため、学習ログ更新のみ実施
by（衆院演説、読書、就活、将棋、日記、ニュース、GT操作）

## 2026-02-07

今日の学習

・【見た目】リセットボタン

・jsとcssの連携　
-classList.add
-クリックを10回クリックで「色が変わる」

## 2026-02-08

今日の学習

・【見た目】jsとcssの連携解除
- classList.remove
- リセットボタンをクリックで「色が戻る」

・【制御機能】10回クリック→その後クリック不可になる機能追加
-disabled = true 項目の使用不可ークリックボタンのクリック機能解除
-disabled = false 項目の使用OKーリセットボタンのクリック機能は維持

・クリック回数に応じた段階的な表示切り替えを実装
- if / else if を使って複数条件で表示を分岐

## 2026-02-09

今日の学習

※忙しいため、GitHub起動と学習ログ更新のみ実施
-　2週間前と比べて、PC起動や作業開始への抵抗が減っていると実感

## 2026-02-10

今日の学習

・関数化　for　再利用可、修正が楽。
-function 関数名(){処理}
-３つの関数で処理（見た目・ボタン・見た目＆ボタン）の分業

・復習問題：JavaScript　by　GT出題

・最初の表示を設定

## 2026-02-11

今日の学習

※忙しいため、GitHub起動と学習ログ更新のみ実施

## 2026-02-12

今日の学習

・【定数管理】数字：10　→　定数：GOAL　for　修正楽

・表示文　→　message定数

・! を使った条件反転に触れた

・達成時に一度だけ実行するフラグ制御を実装

## 2026-02-13

今日の学習

・命名分離

-　resetBtn.addEventListener("click",()=>
    【処理】　});
    ↓
    resetBtn.addEventListener("click", handleResetClick);

    ※関数handleResetClickにて【処理】を設定済み

・localStorageでクリック回数を保存

-ページ更新（リロード）しても回数保持。リセット時に消える。

【用語解説】
localStorage = 保存できる場所

set = 書く  
get = 読む  
remove = 消す

## 2026-02-14

今日の学習

※忙しいため、GitHub起動と学習ログ更新のみ実施

## 2026-02-15

今日の学習

・consoleに「保存回数」を表示

・「保存回数」を画面に表示

・アプリに「初期化処理」追加
-init関数ー①

【コード修正】　by　savedCountを定義するより上の行で実行したため

【コード理解】
loadStorage.getItem(STORAGE_KEY);
「ブラウザ中のメモ帳　タイトルSTORAGE_KEY　から保存データをください」
＝「clickCountという名前で保存されているデータをください」

const STORAGE_KEY = "clickCount";
目的：定数STORAGE_KEYを設定することで文字列clickCountの名称変更が楽

## 2026-02-16

今日の学習【関数名を処理内容が伝わる形へ改善】

・「保存処理分離」
-保存処理をsaveCount関数にまとめる（分離する）。→コードを見やすくする

・【確認】関数名から役割を確認
-handleCountclick「カウントをクリック時の処理」
-isAchieved「達成していますか？」

・「増加処理分離」
-値の変更をする関数作成　for 将来の修正箇所を減らす
-incrementCount関数

・「変更入口統一」
-count変更後の処理をまとめ
-onCountChanged関数

・「reset分離」
-resetCount関数ーcount = 0 ;

## 2026-02-17

今日の学習

・「状態判定分離」
-getAppState関数に「状態を判断させる」
-updateText関数「表示変更」と責任を分けることで
将来の変更(文言変更・多言語対応など)が楽

・「目標判定関数」
-isGoalReached関数
-count >= GOAL　と比べ　役割が一目で分かる

・「中間目標定数化」
-マジックナンバー（コードに記述された意図不明の数）を排除＆定数で管理

## 2026-02-18

今日の学習

・保存通知を１秒後自動で消す
※コード不十分のため明日続き

## 2026-02-19

今日の学習

・「自動保存しました」を１秒後に消す仕組み

-setTimeout(処理,1000)　ー「1000ミリ秒後（１秒後）に処理を実行」

-clearTimeout（タイマー）ー「そのタイマーをキャンセルする」

※「タイマー処理」学習が難しいため一時中断。明日再開予定

## 2026-02-20

今日の学習

※時間なしのため昨日のログ「タイマー処理の図解」を確認＆GitHub更新のみ

## 2026-02-21

今日の学習

・タイマー処理の実装＆理解

・「イベントループ」理解
-js:一度にできる処理は一つだけ（シングルスレッド）
【イメージ】
setTimeout(処理,時間)
＝①Web　APIに処理を渡す　②Web　APIが時間計測　③タスクキュー
（あとでやる仕事）に処理を追加　④コールスタック（今やる仕事）が空いたら
処理を追加＆実行

・【同期処理・非同期処理・マイクロタスク・async/await】
-同期処理：すぐ実行
-非同期処理（タスク）
：Web　APIに処理を渡しタスクキューに登録。
今やる仕事が空いていれば実行
-マイクロタスク：優先度高いタスク。タスクより先に実行。
処理を全部実行してからタスクに進むため、状態の安定化がやりやすい。
-async/await：※マイクロタスクPrpmiseを書きやすくしたもの。

## 2026-02-22

今日の学習

・Promise(マイクロタスク)の組込み

【復習・確認】
・localStorage.setItem(STORAGE_KEY, String(count));
-「ブラウザのメモ帳に『STORAGE_KEY』という名前で『String(count)』を保存

・JSの値の種類
-number型ー(例)5「数値」
-string型ー(例）"5"「文字」
-boolean型（ブーリアン型）ー(例）true
-null型ー(例）null
-undefined型ー(例）undefined

・「＝＝」と「＝＝＝」の違い
＝＝　　　値が同じならOK
＝＝＝　　値と型が同じならOK

・「truthy / falsy」 と 「!!」
-JSでは全ての値はtrue/falseに変換できる(＝Boolean変換)
-「！」はtrue/falseを反転
-「！！」Valueを強制的にtrue/falseに変換
(例)!!o　→　false　,　!!"hello" 　→　true
-truthy「trueになる値」、falsy「falseになる値」

## 2026-02-23

今日の学習

【基礎知識】
-NaN＝Not　a Number「数では無いnumber型」
⭐️例題：Number.isNaN("abc")　　→　　false
"abc"は文字列なので「数では無いがstring型」のため
❌"abc"は「数ではない」のでtrueは誤り

-「Number.isNan(pursed)」
→「値：pursedはNaNですか？」

-「isNan(pursed)」
→「pursedは数値変換したらNaNですか？」

-Object.is(値１,値２)
→「値１と値２は本当に同じ値ですか？」※NaN同士は同じ値とみなす

-infinity「無限大（number型）」

## 2026-02-24

今日の学習

・クリックカウンター仕上げ
-README

・UI整形
-ボタンスタイル統一、hover演出の最適化、アクセシビリティ配慮（:focus-visible、　prefers-reduced-motion）、レイアウト調整

・面接質問対策「:focus-visible、　prefers-reduced-motion」説明

## 2026-02-25

今日の学習

※時間なしのためGitHub更新のみ

## 2026-02-26

今日の学習

・クリックカウンター仕上げ
-動作確認（PC、スマホ）

・ポートフォリオ完成度UP
-スクリーンショット追加
-リポジトリリンク追加
-README：本名・アプリ上：名前のみ。それぞれ分けて記述
-クリック練習を上部に配置

【学び】
-CSS警告ルール（空のCSSは消去推奨）
-コミットメッセージ英語統一　for　多くの人が読める言語
-VS上の「M」＝未コミット

## 2026-02-27

今日の学習

・面接対策「質問TOP５」
①アプリの概要「クリック回数記録アプリ」　
②作成目的「JSのイベント処理・状態管理の学習」
③工夫点「状態判定を関数に分けた」
④苦労点「条件分岐と状態管理」
⑤学び「修正しやすいコード設計」

## 2026-02-28

今日の学習

・クリックカウンター説明対策

【復習】
・localStorage
①.setItem　   「データを保存」
②.getItem　   「保存データを取得」
③.removeItem　「データの更新」

・NaN対策「数値でなければ０にする」
-if(Number.isNaN(value)){count = 0;}

・ポートフォリオ２作目「Simple　ToDo　Manager」　設計開始

## 2026-03-01

今日の学習

・開発方針確認「Version方式」
V1：完成（実装予定：タスク追加・削除・完了チェック・localStorage保存・残タスク表示）
V2:余裕有（締切機能）　　V3:発展（締切日ごとにUI変更）

・フィールド設定
-id:タスク番号,title:タスク名,completed:完了チェック,createdAt:作成日,dueAt:締切

## 2026-03-02

今日の学習

・HTML、JSコード入力＆修正

-headタグの入力
-スペルミスの修正

## 2026-03-03

今日の学習

・「Simple ToDo Manager」をGitHub Pagesで公開

・削除機能の記述

## 2026-03-04

今日の学習

・render関数の理解
-各処理説明をコードに記述

【JS知識】
-innerHTML　「HTML要素の取得・変更」
-createElement　「HTML要素の生成」
-addEventListener("click",関数)　「クリックされたら’関数’を実行」
-appendChild　「子要素の追加」

## 2026-03-05

今日の学習

・配列の基本操作
-配列の設定
const todos = [{id:1,title:"勉強"},{id:2,title:"筋トレ"}]
-push:配列に追加
todos.push = {id:Date.now(),title:input.value}
-配列を１つずつ取り出し
for (const todo of todos)
-配列の絞り込み
todos.filter (todo => todo.id !== id)


【JS知識】
JSON .stringly　「JSオブジェ　→　JSON文字列」
JSON .parse　　　「JSオブジェ　←　JSON文字列」

deleteTodo(3)       <すぐ実行>
()=> deleteTodo (3) <後で実行>

## 2026-03-06

今日の学習

・deleteTodo関数の理解
-配列todos＆その一要素todo

## 2026-03-07

今日の学習

・render()の役割
-todos(データ)→HTML(画面)に変換
※データ変更の際（追加・削除・完了）に画面を書き直す必要があるため

【知識】
-配列.length　「配列の要素数」

【疑問】
①const todo = {}における{}内の構造？
②配列todos =loadTodos();　の構造？
③関数deleteTOdo　の構造？

## 2026-03-08

今日の学習

・「completed切り替え」の実装　※途中まで
-inputタグ　「入力欄の追加」
-checkbox作成

## 2026-03-09

今日の学習

・「completed切り替え」の実装
-checkbox作成
-changeイベント
-取り消し線

・「タイトル」表示コード
-titleSpan　「タイトル部分のみ操作（斜線を引く）するため」
-textContent　「spanに文字を入れるため」
-appendChild　「親子関係(親li-子span)作成のため」

## 2026-03-10

今日の学習

・「completed切り替え」の完成
※親liー子checkboxの親子関係を作る

・css見た目の改善
-flex:1;=  アイテムを伸ばす　※下記３つの融合
「flex-grow: 1;」=空きスペース分伸ばす、
「flex-shrink: 1;」＝はみ出した分縮める、
「flex-basis: 0;」＝基準サイズを指定

## 2026-03-11

今日の学習

・「フィルタ機能」　※少し
-filter-条件：未完了タスクのみ取り出す

## 2026-03-12

今日の学習

・「フィルタ機能ボタン」コード実装
-for　表示タスクを選別するため

## 2026-03-13

今日の学習

・「フィルタ機能ボタン」理解
-All「全タスク」
-Active「実行中タスク」
-Completed「完了済タスク」

【知識】
配列.forEach ( () => {処理});
「配列内の要素を1個ずつ処理」

## 2026-03-14

今日の学習

【復習】
-querySelectorAll 「セレクタ要素の取得」
-NodeList　「配列のような集合　※querySelectorAllによる取得可」
-配列.forEach　「配列内の一要素を一つずつ取得」

## 2026-03-15

今日の学習

【学習】

-<html>data-⚪︎⚪︎　「属性。自由に情報保存できる」
(例)<button data-filter="all">All</button>
-<js>dataset.⚪︎⚪︎　「上記情報の取得できる」
(例)btn.dataset.filter

forEach
-配列.forEach( (要素) => {処理})
-要素は空欄でもOK
-ただし、要素を使う処理の場合は要記述
例：
document.querySelectorAll("#filters button).forEach((btn)=>){
    btn.addEventListener("click,　※以下略)
}

## 2026-03-16

今日の学習

【復習】
-.forEach
-dataset.⚪︎⚪︎
-.filter
-let　「変数定義　※再代入可能」
-classList.remove("値")　「値の排除」

・「フィルタボタンの選択状態表示機能」※実装のみ・未理解
-①classList

## 2026-03-17

今日の学習

・「フィルタボタンの選択状態表示機能」
-② 状態(currentFilter)変更　→　（状態を元に）UIの変更 
-③ renderは一覧表示だけでなくUI全体を更新

【ポイント】
-render　「(状態を元に)UI全体を更新する」
-currentFilter「表示モードを表す状態」
-Q.ボタンクリック時に直接UIを変更しない理由？
A.状態を変えてrenderによって一元管理するため

⚪︎状態変更　→　UI（画面）変更

## 2026-03-18

今日の学習

・コード写経

document.querySelectorAll("[data-filter]").forEach(button => {
    button.addEventListener("click", ()=> {
        currentFilter = button.dataset.filter;
        render();
    });
});

⚪︎状態に従ってUIは更新される

・render関数の役割分け for 修正が楽、バグを見つけやすい、短い文章
-renderList(); 「一覧機能」
-renderCount(); 「件数機能」
-renderFilter(); 「フィルタ機能」

## 2026-03-19

今日の学習

・バグ修正
-forEachにてtodo設定した場合、todoの使用はforEach内で行うこと
-変数deleteButton、関数deleteTodo　の書き間違い
- ] の書き漏れ

・作成：チェックボックス、タイトル、削除ボタン

## 2026-03-20

今日の学習

・動作確認
-タスク追加、チェック線、削除機能、フィルタ機能、更新時データ保持

・UI改善
-opacity 「透明化」→完了タスク判別のため
-if (filterTodos.length === 0) 「フィルタ０時の表示」