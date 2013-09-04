cakephp_mypackage_composer_json
===============================

CakePHPでWEBサービスを作る時に使うもの一括インストールするcomposer.json  
WEBサービスを作るのに参考にしたい書籍  
* CakePHP2-実践入門 : <http://www.amazon.co.jp/dp/4774153249>  
* PHPエンジニア養成読本 : <http://www.amazon.co.jp/dp/4774159719>  

インストールされるものは以下の４つ。
````
"require" : {
    "php": ">=5.3",
    "cakephp/cakephp" : "2.4.*",        /* CakePHP本体 */
    "cakephp/debug_kit": "2.2.*@dev",   /* DebugKit - デバッグする時に便利なやつ */
    "uzyn/cakephp-opauth": "*",         /* Oauth - 色んなサービスのOauthログインを簡単に実装 */
    "slywalker/boost_cake": "*"         /* BoostCake - TwitterBootstrapを適応 */
}
````

#使い方  
1. プロジェクトディレクトリにcomposer.jsonを保存  
2. 1のディレクトリで`$ curl -sS https://getcomposer.org/installer | php`を実行  
3. 1のディレクトリで`$ php composer.phar install`を実行  
以上。  

追加でプラグイン等を入れたい時はcomposer.jsonを編集して、1のディレクトリで`$ php composer.phar update`を実行する。
