# VRM4U
Runtime VRM loader for UnrealEngine4

詳細はこちら参照ください。
https://github.com/ruyo/VRM4U/wiki/VRM4U

なにかあれば @ruyo_h へどうぞ

### ソース
エンジンコードを継ぎ接ぎしています。アクセスにはUE4アカウントの紐づけが必要です。  
無残です。見たことを後悔するかもしれません…  
https://github.com/ruyo/UnrealEngine_VRM4UPlugin

gltf, VRMの読み込みだけ知りたい方はこちらへ  
https://github.com/ruyo/assimp


公開の体裁を含め 多くの方の情報を参考にさせて頂いています。  
ありがとうございます。

### リリース履歴
- 2018/10/18 骨数が256本を越えるとモデルが崩れるのを修正した。揺れ骨を暴れにくくした（InertiaTensorScaleを2にセットした）
- 2018/10/16 VRoidモデルのMorphTargetをまとめた。MorphのY座標がずれていたのを修正。
- 2018/10/11 MToonの半透明情報だけ反映した。
- 2018/10/10 VRoidモデルが白髪になってしまうのを修正。頂点法線が無効だったのを修正。
- 2018/10/08 ドラッグ&ドロップでのインポートに対応。
- 2018/10/07 公開
