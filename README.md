## これはなに
なでしこでJSONを綺麗に表示するための関数をまとめたものです。  
自分が必要だったのでついでに公開しました。  

## どうやって使うの
ライブラリ的にそのまま取り込んで使えるようにはしてないので、適宜コピーして使ってください。  
なでしこに触ること自体久しぶりすぎて名前空間の扱いとか忘れたので、生の関数で置かれています。  
都合に合わせて名前を変えるなどしてください。  

## サンプル
PrettyJson.nakoを実行するとそのままサンプルが実行されます。  

### PrettyPrint(object)
objectはハッシュ、配列、文字列、NIL、それ以外に分類されます。  
JSONを出力するにあたってなでしこの型に変換された構造が必要になるので、通常はJSON文字列を`JSONデコード`を使って型付きの構造に戻します。  

