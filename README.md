# ソフトウェアテスト技法練習帳の回答メモ

[ソフトウェアテスト技法練習帳 ～知識を経験に変える40問～：書籍案内｜技術評論社](https://gihyo.jp/book/2020/978-4-297-11061-1) の回答メモ用のリポジトリです。

![cover](https://gihyo.jp/assets/images/cover/2020/thumb/TH320_9784297110611.jpg)

## 4. 組み合わせテスト

因子水準表を作り、以下ツールを利用して回答しています。
書籍では PictMaster を使用しますが、 macOS 環境のため以下の代替ツールを使用します。

- PICT
- GIHOZ
- ChatGPT

# ツールの補足

## PICT

[PICT (Pairwise Independent Combinatorial Tool)](https://github.com/microsoft/pict) は、Microsoft社が開発したペアワイズ法による組合せテストケース生成ツールです。

### インストールと実行

```bash
$ brew install pict

$ pict 4.1.pict.txt
```

## GIHOZ

[GIHOZ（ギホーズ）](https://www.veriserve.co.jp/helloqualityworld/service/gihoz/) は、ベリサーブ社が開発した各種テスト技法を手軽に利用できるクラウド型ツールです。

作成したテストは [GIHOZ : oikwsat/repositories/WorkbookTestingTechniques](https://gihoz.com/users/oikwsat/repositories/WorkbookTestingTechniques/folders/root_folder) に公開しています。