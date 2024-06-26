# Morpheus 保護基金提案

## 簡介

Morpheus ホワイトペーパーによれば、すべての MOR の発行量の4%を「保護基金」として確保し、必要な場合にはコードプロバイダにリソースサポートを委託します。
操作タイプ：

- 攻撃を回避するための脆弱性報奨金の支払い。
- 新しいスマートコントラクトのデプロイ前の監査料の支払い。
- 攻撃が継続している間、スマートコントラクトを一時停止する。
- 攻撃後のシグナルと支払いのメカニズム。
- 重大な損失イベント（ハードフォークのシナリオ）の計画。

## ファンドからトリガーされる小額の支払いのケース

イーサリアムネットワーク上でスマートコントラクトがリアルタイムになる前に、MORまたはstETHの支払い条件が保護基金に定義されています。

## 支払いタイプ：

1. Morpheus キャピタル、コード、計算、コミュニティ、または保護基金スマートコントラクトの開発者に対して、発見した脆弱性を報告します。
2. Morpheus ネットワークに新しいスマートコントラクトをデプロイする前に監査料を支払います。
3. Morpheus スマートコントラクトが不正使用された場合、ユーザーがMORまたはstETHを失います。
4. Morpheus スマートコントラクトの失敗の場合、発行が受け取られなかったプロバイダーを完全に補償します。

保護基金からの支払いは、脆弱性、損失、または発行のエラーに比例する必要があります。

## スマートコントラクトの一時停止条件

損失の支払いを確認する前に、攻撃が継続している場合にはスマートコントラクトを一時停止する条件が必要です。

## シグナルと支払いのメカニズム

コードプロバイダは、支払いがトリガーされた際にシグナルに参加します。まず、イベントは詳細に説明され、影響を受けるスマートコントラクトのGitHubリポジトリに公開されます。影響を受けるアドレスとMORと/またはstETHの金額のリストが含まれます。

コードプロバイダの大多数（MORトークンの量で測定）がシグナルサイクル（最長7日間）内に参加した場合、報告はTRUEとして確認され、支払いがトリガーされます。

支払いがトリガーされた後、ソフトウェアは開発者にメッセージを送信し、影響を受けるアドレスに指定された金額を支払うことを承認します。

## 重大な損失イベントシナリオの計画

重大な損失イベントは、保護基金の総リソースを超えるMORの損失が発生した場合に定義されます。この場合、コードプロバイダは新しいスマートコントラクトをデプロイし、MORの残高を手動で調整することにより、MORの支払いではなくMORの供給を行います。これにより、コード/MORの残高がハードフォークによって生じ、すべてのプロバイダ、トークン保有者、およびその他のインフラプロバイダは新しいスマートコントラクトにコードを更新する必要があります。

重大な損失イベントの場合、stETHに損失が発生した場合、保護基金は各人の損失金額に比例して支払われるべきです。

## 結論

ソフトウェアの脆弱性とエラーは、ビットコインの二度の意図しないハードフォークとイーサリアムの初期のDAOのような過去の事件を示しています。したがって、さまざまなシナリオやケースに備え、それらを処理する方法を事前に計画することは、賢明なリスク管理とリスク軽減の方法です。幸いにも、保護基金にリソースを事前に確保し、AMMでLP報奨金を受け取るための保護基金の一部を確保し、ユーザーの保護のためにリソースを提供することは、時間とともに成長する必要があります。

## 翻译 private_upload\default_user\2024-04-15-16-06-32\Protection Fund Details Chinese.md.part-1.md

# 損失支払を確定する前に、攻撃が続く場合はスマートコントラクトを一時停止するための条件が必要です。

## シグナルと支払メカニズム

開発者はシグナルがトリガーされたときに支払いに参加します。最初に、イベントは詳細に説明され、関連するスマートコントラクトのGitHubリポジトリに公開されます。影響を受けるアドレスと、影響を受けるMORおよび/またはstETHの金額リストが含まれます。

ほとんどのコードプロバイダ（MORトークン量に基づいて）が信号サイクル（最長7日間）内で参加する場合、報告はTRUEと確認され、支払いがトリガーされます。

支払いがトリガーされた後、ソフトウェアは開発者に対してメッセージを送信し、指定された金額を影響を受けるアドレスに支払うことを承認します。

## 重大な損失イベントシナリオの計画

重大な損失イベントは、保護基金の総資源を超えるMORの損失が発生するイベントと定義されます。この場合、コードプロバイダは新しいスマートコントラクトを展開し、MORの支払い代わりにMOR残高を手動で調整する必要があります。これにより、コード/MORの残高は実際にはハードフォークが発生し、すべてのプロバイダ、トークン保有者、および他のインフラプロバイダは新しいスマートコントラクトにコードを更新する必要があります。

重大な損失イベントでは、stETHの損失が発生した場合、保護基金は各人の損失金額に比例して支払われるべきです。

## 結論

ソフトウェアのバグやエラーは、ビットコインの2回の予期しないハードフォークとイーサリアムの早期のDAOの歴史を示しています。したがって、さまざまな状況とケースに対して準備をし、それらを処理する方法を事前に計画することは、賢明なリスク管理とリスク軽減策です。幸いなことに、保護基金に予めリソースを確保し、AMMでLP報酬を得るための一部の保護基金を提供し、ユーザーの保護にリソースを提供することは、時間の経過とともに増えるべきです。

