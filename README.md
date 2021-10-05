# practice

練習用環境  

Dockerfile更新してイメージを更新するとき  
docker-compose up --build  

・コンテナ稼働状況確認
docker ps -a

・コンテナ内に入るとき  
docker exec -it containerID /bin/bash  
dockerのCLIでコマンド操作、ファイル実行  
  
・powershellでのheadとtail  
Get-Content "kyoto-univ-web-cf-2.0.xml"-Encoding UTF8 | Select-Object -first 100  
Get-Content "kyoto-univ-web-cf-2.0.xml"-Encoding UTF8 | Select-Object -last 100  

・grep的なpowershellコマンド
Select-String "美味しい/おいしい" kyoto-univ-web-cf-2.0.xml -Encoding UTF8  