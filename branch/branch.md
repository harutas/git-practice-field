# ブランチとは
- Git におけるブランチとは、単にこれら三つのコミットを指す軽量なポインタに過ぎません。Git のデフォルトのブランチ名は master です。最初にコミットした時点で、直近のコミットを指す master ブランチが作られます。その後コミットを繰り返すたびに、このポインタは自動的に進んでいきます。

![alt text](https://git-scm.com/book/en/v2/images/branch-and-history.png)


## 新しいブランチの作成

```
git branch testing
```
これで、新しいポインタが作られます。 現時点ではふたつのポインタは同じ位置を指しています。
![alt text](https://git-scm.com/book/en/v2/images/two-branches.png)


## HEADの概念
- 今どのブランチで作業しているのかを指すのがHEAD
- Gitでは、HEADはあなたが作業しているローカルブランチへのポインタとなります。

![alt text](https://git-scm.com/book/en/v2/images/head-to-master.png)