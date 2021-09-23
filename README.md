# オブジェクトのシェーダ
物体に適応するシェーダを変更します。
オブジェクトの入力データである法線ベクトルを使った効果を実装します。

![image](https://user-images.githubusercontent.com/55951546/134488728-af8af311-6d70-4fef-8f0a-84b89d56f4db.png)
![image](https://user-images.githubusercontent.com/55951546/134488837-932696cf-2faf-4d5d-972a-0f49beecc0bc.png)
![image](https://user-images.githubusercontent.com/55951546/134489045-c1f8615e-de90-422a-aa96-f3f817008b75.png)

# 自分なりに変更した点
-リムライトを消したり光らせたりした
-
-

# 進め方

- 本リポジトリをフォークしてください
- フォークしたリポジトリをcloneします
- Unityのプロジェクトを更新して実装してください。
  - リムライトを実装してください
  - [ノード一覧](https://docs.unity3d.com/ja/Packages/com.unity.shadergraph@10.0/manual/Node-Library.html)を10分以上見て、自分なりにロジックを変更しよう
    - 案1: リムライトの色を時間で変える
    - 案2: リムライトの色を場所に応じて変える
    - 案3: 光源の情報を使ったライティングを行う
- このテキストファイルに変更点を記載してください
- result.pngを自分の結果を保存して差し替えてください
- node_graph.pngを自分のシェーダグラフの結果に差し替えてください
- プルリクエストを出して提出してください
