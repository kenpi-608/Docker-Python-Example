# ベースとするDockerイメージ
FROM centos:7
# OSのコマンドを実行する際に使用する javaをインストールしている
RUN yum install -y java
# ADD <コピー元> <Dockerイメージ内のコピー・展開先> 
# ADDはコピーと展開, COPYはファイルのコピーだけ
ADD files/apache-tomcat-9.0.6.tar.gz /opt/
# コンテナ起動時に実行するコマンド
CMD [ "/opt/apache-tomcat-9.0.6/bin/catalina.sh", "run"]