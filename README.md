## Description
Docker for Windowsが使えないWindows向けにDockerを使用可能な状態としたVMを立ち上げるVagrantfileを提供するリポジトリです。
boxはbentoのCentOS7.4を使用。

また、Elasticsearch + KibanaをDocker起動するdocker-composeを同梱しているため、Elastic Stackを気軽に立ち上げたい方も利用できます。

## Requirements
** Virtual Box 5.2.8 r 121009 (Qt5.6.2)
** Vagrant 2.0.3

## Usage
```bash
$ git clone https://github.com/j-yama/vagrant-for-my-windows-home
$ cd vagrant-for-my-windows-home/
$ vagrant up
$ vagrant ssh
$ sudo su -
$ cd /vagrant/data/
$ docker-compose up
```
