# GitHub アカウントの作成

## ステップ 1: [GitHub](https://github.com) アカウントを作成しよう！
GitHub アカウントをすでに作っている場合はこのステップは飛ばしてください。

GitHub のアカウントを持っていない人は [GitHub](https://github.com/join) にアクセスしてアカウントを作りましょう。

## ステップ 2: [account.json](./account.json) を編集しよう！

アカウントを作成したら[account.json](./account.json)の `github_username` の値に GitHub のユーザー名を記入して保存してください。

```json
{
  "github_username": "<Write your GitHub username here>"
}
```

## ステップ 3: テストを実行しよう！
テストを実行して、エラーなく終了できる事を確認しましょう！  
[specifications](./specifications) フォルダの中にある `.spec.js` で終わるファイルからテストの内容が確認できます。

### GitHub へ Fork して受験している場合
GitHub へ Fork してローカル受験をしている場合は、先に Node.js のモジュールをインストールしてから実行する必要があります。次の2つのコマンドをターミナル上で実行することでテストが可能です。

```bash
$ npm install                      # モジュールのインストール
$ $(npm bin)/mocha specifications  # テストの実行
```

次のような出力が確認できれば成功です。

```
Verify GitHub Account
  ✓ should get right user (863ms)


1 passing (871ms)
```

### Web Editor から受験している場合
`RUN` ボタンを押す事でテストが実行されます。

テストが問題なく通過した場合は次のような出力が出ているはずです。

```
1..1
ok 1 Verify GitHub Account should get right user
# tests 1
# pass 1
# fail 0
```

## 提出しよう
問題なくテストを通過することができたら、チャレンジの詳細画面から「提出」をして、別の問題に進んでみましょう。  
作成したGitHubアカウントをcodecheckに認証すれば、あなたのGitHubを活用して、チャレンジの回答をすることが出来ます。
