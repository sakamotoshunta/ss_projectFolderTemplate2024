基本ルール

文字列はキャメルケースで記述する

ムービー制作で.ai以外のファイルを扱う場合は、それ用のフォルダーを作る。ex._MOV,_PHOTO,_SOUND,_C4D、AllCapsで記述する。

c4dなど、各プロジェクトのフォルダが必要なものは、_C4Dフォルダの中にc4d_projectNameのようにフォルダを作る。

_C4Dないでプロジェクトを跨いで使うものは、_C4Dフォルダの中に作る。ex._C4D/_C4D_IN, _C4D/_C4D_OUT

各フォルダには_ARCHIVESを必要であれば作り、そこに古いファイルを移動する。このtemplateでは、ルートにしか_ARCHIVESは作っていないが、必要であれば各フォルダに作ること。

ファイル名は
[prefix]_[projecteName]_[date(yymmdd)]_[version].[dataType]

子フォルダー名は
[date(yymmdd)]_[projecteName]_[version]