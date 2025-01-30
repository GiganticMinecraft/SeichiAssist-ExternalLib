# SeichiAssist-ExternalLib
ギガンティック☆整地鯖のSeichiAssist外部の構成要素(外部プラグインなど)に関する情報を集約、issue管理する為のリポジトリです。

## 基本方針
- 外部に公開すると非常に困る情報(致命的な不具合, 非公開のIPアドレス, 認証情報, APIKey, 他運営チームがそのように判断した情報)は本リポジトリで公開/管理しない。
- 上記に当てはまらない情報で、特にオープン化された開発コミュニティの活動を行う上で必要となる情報(導入済み外部プラグインの名称, バージョン, SeichiAssistスコープ外の不具合, 課題, 新機能に関するissueなど)は、本リポジトリで公開/管理する。

## issueの方針
- SeichiAssistスコープ外(主に外部プラグイン)に起因する不具合、課題、新機能に関する話題をissuesで管理する。
- 複数の外部プラグイン等の情報を同一リポジトリで扱う為、Projects機能を用いた分類を活用する。

## 外部プラグインのドキュメント管理方針
- `/plugins/<PluginName>/README.md`に説明、バージョン情報、DLリンク、関連リンクなどを掲載
- 情報は可能な限り最新を維持する

### 設定ファイルについて
1.18.2 アップデート以降、プラグインの設定は [GiganticMinecraft/seichi_infra](https://github.com/GiganticMinecraft/seichi_infra) へ移動しているため、このプラグインでは管理しない。
