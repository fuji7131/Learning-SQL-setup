# Learning-SQL-setup

Learning SQL（邦題：初めてのSQL）の学習環境をdocker-composeで立ち上げるためのリポジトリです。

## Setup
```
$ cd Learning-SQL-setup
$ docker-compose up -d
$ sh init-mysql.sh
```

## Usage
```
$ docker-compose exec db bash
$$ mysql -u lrngsql -p bank # enter 'password'
```

## Licence
[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## References
[docker-compose でMySQL環境簡単構築 - Qiita](https://qiita.com/A-Kira/items/f401aea261693c395966)

[examples / Learning SQL · GitLab](https://resources.oreilly.com/examples/9780596007270/)
