# Git Large File Storage (LFS)

## インストール

### Mac

`brew install git-lfs`

### Windows

https://git-lfs.github.com/

## 使い方

### 特定のファイル

`git lfs track "*.dat"`

### 特定のディレクトリ

`git lfs track "ディレクトリ/**"`

## おまけ

### 大きなダミーファイルの作り方

1GB

`fsutil file createnew 1gb.dat 1073741824`
