# making-premiere-directory-script

Adobe Premiere Pro のディレクトリ作成を一括で行うスクリプト

## ディレクトリ構成
- root - 作成する動画のフォルダ（名前は任意で変更可能）  
- 01_footage - 動画データ  
- 02_asset   - 動画以外の素材  
  - img       - 画像素材  
  - se        - 効果音素材  
  - bgm       - BGM素材  
- 03_proj    - Premiereデータ  
- 04_out     - 動画書き出し用  

```
.  
⎿＿ root  
　　　├─ 01_footage  
　　　├─ 02_asset  
　　　│　├─  img  
　　　│　├─  se  
　　　│　└─  bgm  
　　　├─ 03_proj  
　　　└─ 04_out
```

## プログラム  
main.py - 最終的に実行を行うプログラム  
input_name.py - rootの名前を指定するプログラム  
make_script.py - スクリプトを作成するプログラム  