# TBBonamd64x86x64
UbuntuへのTBB(Intel Threading Building Blocks)導入用debパッケージ保管庫
Deb package warehouse for introducing TBB (Intel Threading Building Blocks) to Ubuntu
　

## [Japanese] TBB (Intel Threading Building Blocks)の導入

1. TBB(2018 U2)インストール用debファイルのダウンロード

```
$ cd ~
$ wget https://github.com/PINTO0309/TBBonamd64x86x64/blob/master/libtbb-dev_2018U2_amd64.deb
```

2. 下記のコマンドを実行してインストール

```
$ sudo dpkg -i ~/libtbb-dev_2018U2_amd64.deb
$ sudo ldconfig
$ rm libtbb-dev_2018U2_amd64.deb
```

　
## [English] Introduction of TBB (Intel Threading Building Blocks)

1. TBB (2018 U2) Download deb file for installation

```
$ cd ~
$ wget https://github.com/PINTO0309/TBBonamd64x86x64/blob/master/libtbb-dev_2018U2_amd64.deb
```

2. Execute the following command to install

```
$ sudo dpkg -i ~/libtbb-dev_2018U2_amd64.deb
$ sudo ldconfig
$ rm libtbb-dev_2018U2_amd64.deb
```
