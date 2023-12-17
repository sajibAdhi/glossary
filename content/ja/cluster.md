---
title: クラスター
status: Completed
category: コンセプト
tags: ["インフラストラクチャー", "基礎", ""]
---

クラスターは、共通の目的に向けて連携して働くコンピューターやアプリケーションのグループです。
クラウドネイティブコンピューティングの文脈では、この用語は通常[Kubernetes](/ja/kubernetes/)に適用されます。
Kubernetesクラスターは、通常異なるマシン上でそれぞれのコンテナ内で実行される一連のサービス（あるいはワークロード）です。
これらすべての[コンテナ化](/ja/containerization/)されたサービスの集合がネットワーク上で接続され、クラスターを形成しています。

## 解決すべき問題はなんですか

単一のコンピューター上で動作するソフトウェアには、単一障害点があります。
もしそのコンピューターがクラッシュしたり、誰かが誤って電源ケーブルを抜いたりした場合、
ビジネス上重要なシステムが利用できなくなる可能性があります。
そのため、モダンなソフトウェアは一般的に[分散アプリケーション](/ja/distributed-apps/)として構築され、クラスターとしてまとめられます。

## どのように役に立つのでしょうか

クラスター化された分散アプリケーションは複数のマシン上で実行され、単一障害点がなくなります。
しかし、分散システムを構築することは非常に難しいです。
実際、分散システムはコンピューターサイエンスの中で一つの分野として扱われています。
グローバルなシステムの必要性と長い年月をかけた試行錯誤が、[クラウドネイティブ技術](/ja/cloud-native-tech/)と呼ばれる新たなタイプの技術スタックの開発につながりました。
これらの新しい技術は、分散システムの運用と作成を容易にするための構成要素となります。