# ローカルのソースコードをコピーしてbuild成功したときのDockerfile
FROM python:3.9

# 作業ディレクトリの設定
WORKDIR /workspace

COPY ./requirements.txt /workspace/

# 依存関係のインストール
RUN pip install --no-cache-dir -r requirements.txt

# # 環境変数の設定
# ENV FLASK_APP=app

# # pipをアップグレードし、依存関係をインストール
# RUN pip install --upgrade pip 
# RUN pip install flask
# # RUN pip install -r requirements.txt 

# # ポート5000を公開
# EXPOSE 5000

# # Flaskアプリの実行。Docker Composeファイルで上書きされます。
# CMD ["flask", "run", "--host=0.0.0.0"]
