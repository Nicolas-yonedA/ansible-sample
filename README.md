# Ansible基本のキ
「Ansible基本のキ」で説明に利用したコード
「Ansible基本のキ」については、以下のリンクからスライドを参照
[Ansible 基本のキ - SlideShare](https://www.slideshare.net/secret/43PGEChjrRzVmh)

## 必須
Ansible
Vagrant

## デモ

```bash
$ cd playbook-nginx
$ ansible-playbook -i inventory sanmple_nginx.yml
```

## 各ファイル・ディレクトリ
### Vagrantfile
Vagrantでリモートホストを作成する際に利用
### ansible
ansibleコマンドでping等、アドホックなコマンドを試す際に利用
### playbook-nginx
基本的なansible-playbookコマンドを試用する際に利用
### playbook-lnmp
実践的な内容。Linux-Nginx-MySql-PHPの環境構築が可能
### aws
AWSに接続し、動的なインベントリを取得する際に利用



