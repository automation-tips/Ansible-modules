# Vagrantを使用したAnsible勉強用環境の構築

## 実行環境
・MAC または Windows  

## Vagrant と VirtualBox のインストール

Vagrantダウンロードサイト↓  
https://www.vagrantup.com  

VirtualBoxダウンロードサイト↓（VirtualBox 6.0.0 platform packagesをダウンロード）  
https://www.virtualbox.org/wiki/Downloads  


## サーバーの構築

```
# Ansibleサーバー構築
$ cd VMs/provisioning/
$ vagrant up

# Sandboxサーバー構築
$ cd VMs/sandbox/
$ vagrant up
```

# Sandboxサーバー(Amazon Linux2)構築
$ cd VMs/ec2-sandbox/
$ vagrant up
```

## サーバーへのログイン

```
# Ansibleサーバーへのログイン
$ cd VMs/provisioning/
$ vagrant ssh

# Sandboxサーバーへのログイン
$ cd VMs/sandbox/
$ vagrant ssh
```

# Sandboxサーバー(Amazon Linux2)へのログイン
$ cd VMs/ec2-sandbox/
$ vagrant ssh
```

## AnsibleサーバーからSandboxサーバーへのログイン

```
$ ssh l4a-sandbox.localdomain
```
