# practice

練習用環境  

・コンテナ内に入るとき  
docker exec -it containerID /bin/bash  
dockerのCLIでコマンド操作、ファイル実行  
  
・powershellでのheadとtail  
Get-Content "kyoto-univ-web-cf-2.0.xml"-Encoding UTF8 | Select-Object -first 100  
Get-Content "kyoto-univ-web-cf-2.0.xml"-Encoding UTF8 | Select-Object -last 100