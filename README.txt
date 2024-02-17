基本ルール

文字列はキャメルケースで記述する

ムービー制作で.ai以外のファイルを扱う場合は、それ用のフォルダーを作る。ex._MOV,_PHOTO,_SOUND,_C4D、AllCapsで記述する。

c4dなど、各プロジェクトのフォルダが必要なものは、_C4Dフォルダの中にc4d_projectNameのようにフォルダを作る。

_C4Dないでプロジェクトを跨いで使うものは、_C4Dフォルダの中に作る。ex._C4D/_C4D_IN, _C4D/_C4D_OUT

各フォルダには_ARCHIVESを必要であれば作り、そこに古いファイルを移動する。このtemplateでは、ルートにしか_ARCHIVESは作っていないが、必要であれば各フォルダに作ること。

ファイル名, _C4D直下のプロジェクトフォルダ名は、以下のようにする。
[prefix]_[projecteName]_[option]_[date(yymmdd)]_[version].[dataType]

ex.projectFolderTemplate2024_240217_1.ai // .aiはprefixなし
ex.c4d_projectFolderTemplate2024_logoMotion_240217_1.c4d //ai以外のデータ
ex.c4d_projectFolderTemplate2024_logoMotion_240217_1


子フォルダー名は
[date(yymmdd)]_[projecteName]_[version]
ex.240217_svg_1

