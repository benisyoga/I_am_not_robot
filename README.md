# I_am_not_robot

プロジェクトファイルはGoogleDriveから  
リンク：https://drive.google.com/drive/folders/1q2dz76Qmbmc5p8W_yr3WhSZn38Vws906?usp=sharing  

使用ゲームエディタ：Unity  
使用言語：#c  
開発体制：個人開発  

Gitから実行ファイルをダウンロードした場合はMy project_Dataのzipファイルを解凍してください。  

操作方法：  
・タイトル画面、リザルト画面  
ボタンをクリック...ボタンを押すことで、対応するシーンへの切り替えやチュートリアルウィンドウを開くことができます。  

・ゲーム画面  
画像をクリック...画像を押すことでそれぞれの画像を選択/解除することができます。  
「次へ」をクリック...選択された解答が正しいかチェックします。  
丸矢印をクリック...問題をパスして次の問題に切り替えます。  
(i)をクリック...チュートリアルウィンドウを表示します。  

テンキーの１～９...各キーの位置に対応する画像を選択/解除することができます。  
テンキーの０...「丸矢印をクリック」と同様  
スペースキー...「『次へ』をクリック」と同様  

ルール：  
・画面左に表示されているゲージが空になったらゲームオーバーです。  
・連続して正解し続けるとゲージが回復します。  
・間違った回答をするとゲージが減少します。  
・丸矢印によって問題が切り替わるたびにゲージの減少速度が上がります。  

※ゲーム内にチュートリアルウィンドウを用意していますのでそちらも参照してください。  

開発目的：  
Unityの基本的な操作やc#の書き方を覚えるため。また、csvファイルを用いたデータ呼び出しの方法を学ぶため。  

こだわったところ：  
・ゲームロゴ、キャラクター、背景、ボタンを全て自作した。  
・実在するセキュリティシステムであるreCAPTCHAをモチーフにしたため、ゲームシーンの背景やUIを実際のWebブラウザに似ているようにデザインをした。  
・問題文や解答をcsvファイルで管理しているため、問題の拡張が容易に行うことができるようにした。  
・キャラクターの表情をゲームの状況に応じて変化するようにし、感情を豊かにした。  