# Summary   
指定した文字列を評価後に連結して、現在のシェルに実行させる(https://www.atmarkit.co.jp/ait/articles/1712/22/news019.html)

## Ex(https://github.com/riywo/ndenv)   
```   
echo 'eval "$(ndenv init -)"' >> ~/.bash_profile    
```   
$(ndenv init -)の実行結果を~/.bash_profileに書き込む。    
