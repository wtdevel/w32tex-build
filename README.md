# w32tex-build

This repository contains binary files of win32 TeX distribution.
Current binaries are mostly based on

- w32tex-src.tar.xz (as of 2016-05-13 10:17)

and some sources are updated along with TeX Live svn

- ktx/texk/kpathsea (r41795)
- ktx/texk/web2c/ptexdir (r42040)
- ktx/texk/web2c/eptexdir (r42041)
- ktx/texk/tex4htk (r42110)
- xtx/texk/kpathsea (r41795)
- xtx/texk/web2c/xetexdir (r42142)
- ktx/texk/mendexk (r42167)
- xtx/texk/upmendex (r41572)

Only a small subset of binaries are available, since these are the ones
which I managed to build by myself using Visual Studio 2013. The even
better and stable binaries are also included in W32TeX by Akira Kakuto,
so there is no reason to choose ones in this repository.
No warranty.

----

これは、私が Visual Studio 2013 環境でどうにかビルドに成功した win32 の
TeX 関連バイナリを置いておくための場所です。成功したものしか置いていま
せんので、角藤先生の W32TeX に比べてファイルが欠けています。
ただの練習目的ですので、常用しないほうがよいと思います。当然無保証です。

もし使ってみたい場合は、W32TeX や TeX Live (win32) の元々の同名ファイル
をリネームして保管しておき、代わりにこのリポジトリから取得したファイルを
置いてください。それ以上の説明はあえて控えます。

Hironobu Yamashita
