# papanda925

VBA、PowerShell、AI/API、ネットワークを中心に、**実際に動かして処理を追跡できる学習用サンプル**を公開しています。

完成したコードだけを示すのではなく、日本語コメント、処理トレース、導入手順、制限事項、テスト観点を含め、初学者・学生・社内研修でも読み進められる構成を目指しています。

- 技術ブログ: [papanda925.com](https://papanda925.com/)
- ポートフォリオ: [papanda925.github.io](https://papanda925.github.io/)
- 公開リポジトリ: [Repositories](https://github.com/papanda925?tab=repositories)

## VBAネットワーク学習シリーズ

Windows版Excel VBAから、外部コマンドに頼らずWindows APIを直接呼び出す教材です。クライアント側だけでなく、可能なものはローカル簡易サーバーまたは応答側も用意し、通信の両側をトレースできるようにしています。

| 推奨順 | リポジトリ | 学べる内容 |
| ---: | --- | --- |
| 1 | [VBA_WinsockAPI_TCP_Sample](https://github.com/papanda925/VBA_WinsockAPI_TCP_Sample) | IPv4 TCPの接続、送信、受信、切断 |
| 2 | [VBA_WinsockAPI_UDP_Sample](https://github.com/papanda925/VBA_WinsockAPI_UDP_Sample) | IPv4 UDPのデータグラム送受信 |
| 3 | [VBA_Async_HTTP_API_Sample](https://github.com/papanda925/VBA_Async_HTTP_API_Sample) | 非同期HTTPクライアントとローカル簡易HTTPサーバー |
| 4 | [VBA_DnsAPI_Query_Sample](https://github.com/papanda925/VBA_DnsAPI_Query_Sample) | DNS APIによるA、AAAA、CNAME、PTR、MX、TXT問い合わせ |
| 5 | [VBA_IcmpAPI_Ping_Sample](https://github.com/papanda925/VBA_IcmpAPI_Ping_Sample) | IPv4/IPv6 PingとICMP応答の観察 |
| 6 | [VBA_IcmpAPI_Traceroute_Sample](https://github.com/papanda925/VBA_IcmpAPI_Traceroute_Sample) | TTLを変化させるTracerouteの仕組み |
| 7 | [VBA_WinsockAPI_TCP_IPv6_Sample](https://github.com/papanda925/VBA_WinsockAPI_TCP_IPv6_Sample) | IPv6 TCPクライアント・サーバー通信 |
| 8 | [VBA_WinsockAPI_UDP_IPv6_Sample](https://github.com/papanda925/VBA_WinsockAPI_UDP_IPv6_Sample) | IPv6 UDP送受信、タイムアウト、送信元確認 |

新しい6教材はMIT Licenseで公開しています。著作権表示とライセンス文を残すことで、学習、授業、社内研修、改変、再配布に利用できます。

## PowerShell・Windows GUI

| リポジトリ | 内容 |
| --- | --- |
| [PowerShell_WPF_XAML_GUI_SampleCodes](https://github.com/papanda925/PowerShell_WPF_XAML_GUI_SampleCodes) | PowerShellとWPF/XAMLによるGUI実装サンプル集 |
| [PowerShell_HiDPI_GUI_Sample](https://github.com/papanda925/PowerShell_HiDPI_GUI_Sample) | 高DPI環境を考慮したPowerShell GUIサンプル |
| [PowerShellXamlEditTool](https://github.com/papanda925/PowerShellXamlEditTool) | PowerShell/XAMLで作成した編集ツール |

## AI・API、ローカルツール

| リポジトリ | 内容 |
| --- | --- |
| [OrcaRouter-Samples](https://github.com/papanda925/OrcaRouter-Samples) | Web、PowerShell、VBAからOpenAI互換APIを学ぶサンプル集 |
| [MarkdownLocalWiki](https://github.com/papanda925/MarkdownLocalWiki) | Windows上で利用できるMarkdown対応ローカルWiki |
| [MarkDownPSLocalServerWiki](https://github.com/papanda925/MarkDownPSLocalServerWiki) | PowerShellローカルサーバーを利用するMarkdown Wiki |

## このGitHubで重視していること

- 日本語コメントで「何をしているか」「なぜ必要か」を説明
- 成功時だけでなく、処理段階とエラーをトレース
- 32ビット版・64ビット版Officeの違いを考慮
- 初学者が再現できる導入手順とテスト手順
- 教材としての制限事項、セキュリティ上の注意、実機未確認事項を明記
- 公式ドキュメントを参照し、学習をさらに進められる構成

## ご利用にあたって

各リポジトリのREADME、`SECURITY.md`、`LICENSE`をご確認ください。学習用サンプルは業務用システムや公開サーバーをそのまま置き換えるものではありません。利用環境でのテストと、安全性の確認を行ってください。

不具合や改善案は、該当リポジトリのIssuesからお知らせください。
