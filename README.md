# doma-gen-template

「[doma-gen](https://doma-gen.readthedocs.io)」を使用するためのテンプレートです。

## Description

「doma-gen」 + 「gradle」を使用して「Entity」、「Dao」などを作成するために使用するテンプレートリポジトリです。

## Requirement

* git
* 接続可能なRDBMS（※1）

※1：goma-genが対応しているRDBMSになります。詳細は、[こちら](https://doma-gen.readthedocs.io/ja/stable/gen/#id9)の「dialectName」を参照してください。

## Usage

```sh
$ git clone https://github.com/fumidzuki/doma-gen-template.git
$ cd doma-gen-template
$ sh gradlew gen
```

## Licence

This software is released under the MIT License.

## Author

[fumidzuki](https://fumidzuki.com)
