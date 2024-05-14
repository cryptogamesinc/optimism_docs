# Optimism Docs日本語
2024.04.14時点でのドキュメントを日本語化
- 主にChatGPTによる自動翻訳
	- 「一般的な語彙でない場合には英語のままその単語を残してください。」とスクリプトに加えると変な日本語訳されなくなるのでおすすめ
- 作業開始前にISSUEにどのファイルで作業するか明記のこと
- メモを追加するときは二重カッコで残す。（ドキュメント本文ではないことを明示するため）
	- 例: ((これはメモです))
- 分からなかったところはTODOで残す
	- 例: TODO: ⚪︎︎︎⚪︎︎︎ってどういう意味だろう？

ChatGPTへの指示参考
「
以下のmdxファイルを日本語に翻訳してください。なお、以下のルールを適用してください。
- 一般に日本語にない語彙は英語のまま残す
- 翻訳した結果はコードブロックに入れる
- 本文のコードブロックの始点と終点はエスケープする（```は\```とする）
」


#  Optimism Docs

This repo houses the Optimism Docs located at [docs.optimism.io](https://docs.optimism.io/). All documentation-related updates and new content will be tracked and maintained in this repo. 

## Local Development

How to [install pnpm](https://pnpm.io/installation)

First, run `pnpm i` to install the dependencies.

Then, run `pnpm dev` to start the development server and visit localhost:3000.

## Contributions

Please see the [CONTRIBUTING.md](CONTRIBUTING.md) page for specifics on how to write PRs, use the linter, run spellcheck, add dictionary terms, etc. You should also review the [Optimism Documentation Style Guide](/pages/connect/contribute/style-guide.mdx) for additional guidelines, especially if you are writing entirely brand new pages to the developer docs, as opposed to smaller edits and/or revisions.

## Project Board

You can track documentation [issues](https://github.com/ethereum-optimism/docs/issues) or submit documentation [requests](https://github.com/ethereum-optimism/docs/issues/new/choose) directly from this repo.

## License

This project is licensed under the MIT License.

