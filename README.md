cakephp_mypackage_composer_json
===============================

CakePHPでWEBサービスを作る時に使うもの一括インストールするcomposer.json

インストールされるものは以下の４つ。
  "require" : {
    "php": ">=5.3",
    "cakephp/cakephp" : "2.4.*",        /* CakePHP本体 */
    "cakephp/debug_kit": "2.2.*@dev",   /* DebugKit - デバッグする時に便利なやつ */
    "uzyn/cakephp-opauth": "*",         /* Oauth - 色んなサービスのOauthログインを簡単に実装 */
    "slywalker/boost_cake": "*"         /* BoostCake - TwitterBootstrapを適応 */
  }
