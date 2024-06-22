# phish

# Macでの実行
### 作業のディレクトリに移動(好きな)
cd ~/projects/myproject

ここにurl.txt と user_info_post.py を置いておく

### 仮想環境を作成
python3 -m venv venv

### 仮想環境をアクティベート
source venv/bin/activate

### 必要なモジュールをインストール(自分の時はこれでした)
pip install nodriver

### コード実行→ブラウザすごい立ち上がるので最初は5件くらいで試すのがよさそうです。
python user_info_post.py

### 送るユーザの変更
user_info_post.py にある<br>
num_users = 10000　←　この数字を1 にすると1ユーザのみ登録します。
