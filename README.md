# モナオクシステム
モナオクで仕様されているシステムのソースです。
すべてのファイルをWebサーバーにアップロードした後、Websiteにアクセスして、ウィザードに従ってください。

## インストール・パーミッション設定
--------------------------------------------------------
uploaded - 755
includes/config.inc.php.new - 0777
language/EN/categories.inc.php - 0777
language/EN/categories_select_box.inc.php - 0777
cache - 0777

すべてのファイルをWebサーバーにアップロードした後、Websiteにアクセスして、ウィザードに従ってください。

## アップデート
--------------------------------------------------------
1. docsディレクトリ以外のすべてのファイルをアップロードする
2. http://yoursite/webid/install/update.php にアクセスし、ウィザードに従う。

ADDING A LANGUAGE
--------------------------------------------------------
1. Open the language directory and copy the entire EN folder, rename it to the abrviation of your language (e.g DL, NL, JP)
2. CHMOD the language/xx/categories.inc.php to 0777
3. CHMOD the language/xx/categories_select_box.inc.php to 0777
4. Translate every file in there.

MODS
--------------------------------------------------------
Well if you have made any fixes/mods for WeBid please feel free to share them at the link above