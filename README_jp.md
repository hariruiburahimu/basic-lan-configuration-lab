# 基本的なLAN構築ラボ

英語版はこちら → [README.md](README.md)

## 概要
Cisco Packet Tracerを使用して、レイヤー2の基本的なLANトポロジーを構築しました。

## ネットワーク構成
- PC 2台（PC0、PC1）
- Cisco 2960 スイッチ 1台
- ストレートケーブルによる接続

## IPアドレス設定
PC0: 192.168.1.10 /24  
PC1: 192.168.1.20 /24  

## 動作確認
ICMP（ping）による疎通確認を実施し、パケット損失 0% を確認しました。

## スクリーンショット

![LANトポロジーおよび疎通確認](lan-topology-and-ping-verification.png)

## 使用スキル
- 基本的なLAN設計
- 静的IPv4アドレス設定
- ネットワーク接続テスト
- パケットレベルでの疎通確認

## ライセンス
Apache License 2.0
