﻿---
Demo:
    title: 'Microsoft 365 の機密ラベル'
    module: 'モジュール 4 レッスン 2: Microsoft コンプライアンス ソリューションの機能について説明する: Microsoft 365 の情報保護とガバナンスの機能について説明する'
---


# デモ: Microsoft 365 の機密ラベル

### デモ シナリオ
このデモでは、機密ラベルの機能について説明します。  作成された既存の機密ラベルの設定と、ラベルを公開するための対応するポリシーの設定を行います。   次に、ユーザーの観点から、ラベルを適用する方法とそのラベルの影響を確認します。


#### デモ パート 1: このデモでは、既存の機密ラベルの設定と、ラベルを公開するための対応するポリシーについて説明します。

1. Microsoft Edge を開きます。アドレス バーに、「**admin.microsoft.com**」と入力します。

1. 管理者の資格情報でサインインします。
    1. 「サインイン」ウィンドウで、「**admin@WWLxZZZZZZ.onmicrosoft.com**」 (ZZZZZZ はラボ ホスティング プロバイダーにより提供される一意のテナント ID です) を入力してから、「**次へ**」を選択します。
    1. ラボ ホスティング プロバイダーから提供される管理者のパスワードを入力します。「**サインイン**」を選択します。
    1. サインインしたままにするかどうかを尋ねられたら、「**はい**」を選択します。これにより、「Microsoft 365 管理センター」ページにリダイレクトされます。

1. Microsoft 365 管理センターの左ナビゲーション ペインで、「**すべて表示**」を選択します。

1. 「管理センター」の下で、「**コンプライアンス**」を選択します。  Microsoft 365 コンプライアンス センターの「ようこそ」ページを表示する新しいブラウザー ページが開きます。  

1. Microsoft 365 コンプライアンス センターの左ナビゲーション パネルで、「**すべて表示**」を選択します。

1. 左ナビゲーション パネルで、「ソリューション」の下の「**情報保護**」を選択します。

1. 黄色の情報ボックスは、暗号化された機密ラベルが適用され、OneDrive と SharePoint に保存されている Office オンライン ファイルのコンテンツを処理する機能が組織で有効になっていないことを示します。  「今すぐ有効にする」を選択します。  これを行うと、設定がシステム全体に伝播するのに遅延が生じる可能性があります。

1. ページ上部の「**ラベル**」タブが選択されている (下線が引かれている) ことを確認します。

1. ページの中央で、3 つのラベルがすでに作成されていることに注意してください。  「**機密 - 財務**」を選択します。  このラベルに関する情報を表示するウィンドウが開きます。  このラベルが暗号化とコンテンツ マーキングの両方をサポートするように設定されていることに注意してください。  ページ上部の「**ラベルの編集**」を選択して、基本的な構成設定の一部を表示します。

    1. 構成は、ラベルの名前と説明を提供することから始まります。  何も変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. このラベルのスコープに注意してください。  スコープは「ファイルと電子メール」に設定されており、ラベル付きの電子メールと Office ファイルを保護するために暗号化とコンテンツ マーキングの設定を構成できます。  何も変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. 選択したスコープ、「ファイルと電子メール」について、コンテンツを暗号化および/またはマークするように構成できます。  ファイルと電子メールの保護設定が、暗号化とファイルの内容のマーキングの両方にどのように設定されているかに注意してください。  それぞれの定義を確認します。  何も変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. 「暗号化」ウィンドウには、暗号化設定の構成が表示されます。  何も変更しないでください。  「暗号化設定の構成」の下の情報ボックスを確認し、構成済みの設定を確認します。コンテンツへのユーザーアクセスが無期限に設定されていることに注意してください。  特定のユーザーとグループにアクセス許可を割り当てて、このラベルが適用されているコンテンツを操作できるのはそのユーザーだけにすることもできます。  ユーザーとグループの下で、テナントが定義されているため、テナント内のすべてのユーザーがこのラベルの付いたコンテンツを表示できます。  財務チームも一覧表示されており、共同作成者のアクセス許可があります。  設定を変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. 「コンテンツ マーキング」ページで、ページ上部の情報ボックスに注意してください。  コンテンツ マーキングはドキュメントに適用されますが、ヘッダーとフッターのみが電子メール メッセージに適用されます。つまり、透かしは電子メールには適用されません。  このラベルに関連付けられているコンテンツ マーキングは透かしです。  設定を変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. これで、「ファイルと電子メールの自動ラベル付け」ウィンドウが表示されます。  ページ上部の自動ラベル付けの説明とその下の情報ボックスをお読みください。  また、このラベルは特定の条件の自動ラベル付け用に設定されていることに注意してください。設定を変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. この次のウィンドウでは、このラベルが適用されているチーム、グループ、サイトの保護設定を定義します。これが有効になっていない場合は、ページの下部にある「**次へ**」を選択します。 

    1. この次のウィンドウは、選択した機密情報の種類を含む Azure データベース列 (SQL、Synapse など) にこのラベルを自動的に適用するプレビュー機能です。  この機能は有効化されていません。ページの下部にある「**キャンセル**」を選択して、「ラベル構成」ウィザードを終了し、「情報保護」ページに戻ります。 

1. 「情報保護」ページの上部で、「**ラベル ポリシー**」を選択します。  機密ラベルを公開できるのは、ラベル ポリシーを通じてです。  

1. 「**機密 - 財務ポリシー**」を選択します。  このポリシーに関する情報を表示するウィンドウが開きます。  このポリシーは、「機密 - 財務ポリシー」ラベルを公開し、Contoso の財務データを含むデータを保護するのに役立ちます。  また、このポリシーがすべての人にどのように公開されているかに注意してください。  

1. ウィンドウの上部で、「ポリシーの**編集**」を選択します。

    1. “公開する機密ラベルの選択” の説明をお読みください。  一覧表示されているラベルに注意してください。  設定を変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. “ユーザーとグループに公開する” の説明をお読みください。  このラベルはすべてのユーザーが利用できることに注意してください。  設定を変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. ポリシー設定を確認します。  設定を変更しないでください。  ページの下部にある「**次へ**」を選択します。

    1. 最後の構成オプションは、ポリシーに名前を付けることです。  設定を変更しないでください。  ページの下部にある「**キャンセル**」を選択して、ポリシー構成を終了し、「情報保護」ページに戻ります。

1. 「情報保護」ページで、「自動ラベル付け」を選択します。  自動ラベル付けポリシーが構成されていないことに注意してください。  設定を変更しないでください。  ラベル構成がファイルと電子メールの自動ラベル付けに設定されているため、ここにポリシーがない理由がわからない場合は、ラベル構成設定を確認した手順に戻り、ファイルと電子メールの自動ラベル付けに関連する説明と情報ボックスを確認します。  ヒント:  機密ラボの自動ラベル付けタブには、次のように書かれています。  "(SharePoint および OneDrive に) 既に保存されているファイルまたは Exchange によって既に処理されている電子メールにこのラベルを自動的に適用するには、自動ラベル付けポリシーを作成する必要があります。"

1. 左ナビゲーション パネルで、「ホーム」を選択して、Microsoft 365 コンプライアンス センターに戻ります。

1. 次のタスクで使用するため、このページを開いたままにしておきます。


#### デモ パート 2:  この手順では、ユーザー (この場合はユーザーが管理者) の観点からラベルを適用し、ラベルによって生成されたコンテンツ マーキングを表示するプロセスについて説明します。

1. Microsoft 365 コンプライアンス センターの「ホーム」ページで、Contoso Electronics と表示されている場所の隣の **「アプリ ランチャー」アイコン** を選択し、**「Word」アイコンを右クリックして**、「**新しいタブで開く**」を選択します。

1. 「**+ 新しい空白のドキュメント**」を選択し、ページにテキストを入力します。  ページ上部の青色のバーで、「DocumentXX - Saved」と表示されている場所の隣の下向き矢印を選択し、「ファイル名」ボックスに「**Test-label**」と入力します。

1. 上部のメニュー バーで、「**機密度**」を選択します。このオプションがすぐに表示されない場合は、ページを更新してください。ドロップダウンで、「**機密 - 財務**」を選択します。 

1. 上部のメニュー バーで、「**ビュー**」選択してから、「**読み取りビュー**」を選択します。

1. ドキュメントに透かしが含まれていることに注意してください。  

1. ブラウザーで開いている「Microsoft Word」タブを閉じて、Word を終了します。

#### デモ パート 3 (オプション): コンテンツ マーキングに加えて、暗号化のためにラベル保護設定が設定されました。このラベルで構成されたアクセス許可に従って、財務グループのメンバーはこのラベルが適用されたドキュメントを共同作成でき、Contoso テナントのユーザーは (またはラベルが適用された任意のドキュメント/電子メール) を表示できます。  こセクションでは、アクセス権のあるメール アドレス (つまり、個人のメール アドレスまたは Microsoft のメール アドレス) にこのドキュメントを送信します。これは WWLxZZZZ.OnMicrosoft.com ドメインの一部ではなく、添付ファイルを開こうとするとどうなるかを確認するためです。  

1. Microsoft 365 コンプライアンス センターの「ホーム」ページで、Contoso Electronics と表示されている場所の隣の **「アプリ ランチャー」アイコン** を選択し、**「Outlook」アイコンを右クリックして**、「**新しいタブで開く**」を選択します。

1. 画面の左上隅で、「**新しいメッセージ**」 を選択します。  アクセス権があり、WWLxZZZZ.OnMicrosoft.com ドメインの一部ではないメール アドレスを入力し、件名に「**テスト**」と入力します。

1. 「**接続**」 を選択します。

1. 「**クラウドの場所を参照**」 を選択します。

1. 表示される一覧で、作成し、ラベル 「**Test-label**」 を適用したドキュメントを選択します。 「**次へ**」 を選択し、 「**コピーとして添付**」 を選択します。  「**送信**」を押します。

1. ドキュメントの送信先のメール アドレスを確認します。  メールは迷惑メール フォルダーに送信される場合があることに注意してください。  添付の Word ファイルを開こうとすると、ドキュメントを開く権限がないという通知が表示されます。

1. 開いているブラウザー タブを閉じます。


#### レビュー
このデモでは、機密ラベルについて説明しました。  すでに作成されている既存の機密ラベルの設定と、ラベルを公開するための対応するポリシーの設定について説明しました。次に、ユーザーの観点から、ラベルを適用する方法とそのラベルの影響について説明しました。