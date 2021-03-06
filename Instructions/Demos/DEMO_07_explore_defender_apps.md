---
Demo:
    title: 'Microsoft Defender for Cloud Apps'
    module: 'モジュール 3 レッスン 4: Microsoft セキュリティ ソリューションの機能を説明する: Microsoft 365 Defender を使用した脅威に対する保護について説明する'
---


# デモ: Microsoft Defender for Cloud Apps

### デモ シナリオ
このデモでは、Microsoft Defender for Cloud Apps の機能について説明します。  Cloud Discovery ダッシュボードで使用可能な情報、および検出事項を調査し、ポリシーを通して組織に対する影響を制御するために利用可能な機能について、学習者に詳しく説明します。  注:  組織には、ユーザーベースのサブスクリプション サービスである Microsoft Defender for Cloud Apps を使用するライセンスが必要です。  

#### デモ パート 1: Cloud Discovery の詳細を確認します。

1. Microsoft Edge を開きます。アドレス バーに、「**admin.microsoft.com**」と入力します。  すでに管理者としてサインインしている必要があります。  そうでない場合は、、管理者の資格情報でサインインします。

1. Microsoft 365 管理センターの左ナビゲーション ペインで、「**すべて表示**」を選択します。  ここからさまざまな Microsoft 365 管理センターにアクセスできるという点を説明してください。

1. 「管理センター」の下で、「**セキュリティ**」を選択します。  Microsoft 365 Defender ポータルの「ようこそ」ページを表示する新しいブラウザー ページが開きます。  

1. Microsoft 365 Defender ポータルに初めてアクセスする場合は、ポップアップ ウィンドウが表示されてクイック ツアーに参加できる場合があります。  これを閉じます。

1. 「Microsoft 365 Defender」ページの左ナビゲーション パネルの下部で、「**その他のリソース**」を選択します。

1. **Microsoft Defender for Cloud Apps** カードで、**「開く」** を選択します。  Cloud App Security Dashboard を表示する新しいブラウザー ページが開きます。  利用可能な情報カードに注意してください。  これはアクティブに使用されていない事前に構成されたラボ テナント環境であるため、カードに情報が表示されない可能性があります。  

1. 左ナビゲーション パネルで、「**検出**」を選択してから、ドロップダウンで、「**Cloud Discovery ダッシュボード**」を選択します。  ダッシュボードには、検出されたアプリの概要、アプリのカテゴリ、リスク レベルなどが表示されます。  

    1. 「Cloud Discovery」ページの上部で、「**検出されたアプリ**」タブを選択します。  「検出されたアプリ」ウィンドウには、リスク スコア、トラフィック、ユーザー数などのより詳細なビューが表示されます。

        1. 一覧の任意の項目で、テーブルの「アクション」列の**省略記号**を選択します。  アプリを承認されたまたは承認されていないとしてタグ付けする機能を含む、さまざまなオプションが利用可能であることに注意してください。  もう一度省略記号を選択して、「アクション」ボックスを閉じます。

        1. 特定のライン項目を選択して、特定のアプリの詳細ページを開きます。  一覧から項目を選択します。  選択した項目について、詳細ページの上部の各タブ  (**使用状況**、**情報**、**IP アドレス**、**ユーザー**、**アラート**) を確認します。「詳細」ページの確認を完了したら、左ナビゲーション パ根スで、「**検出されたアプリ**」を選択して、検出されたアプリに戻ります。

    1. ページの上部で、「**IP アドレス**」タブを選択します (これは、左ナビゲーション パネルで、「IP アドレス」を選択することと同等です)。  ここで、IP アドレス別のトランザクションの数、トラフィックの量、アップロードの量を含むデータを確認します。  特定の IP アドレスによるフィルター処理、詳細分析のためのデータのエクスポートを実施できることに注意してください。

    1. ページ (または左ナビゲーション ペイン) の上部で、「**ユーザー**」を選択します。  これは、「IP アドレス」を選択したときに表示される情報を同じ種類ですが、個別のユーザーに対して一覧表示されます。  ここで繰り返しになりますが、特定のユーザー別にフィルター処理を行い、詳細分析のためにデータをエクスポートします、

1. これらのタブに表示される情報は、ファイアウォールやプロキシから手動でアップロードしたトラフィック ログからのスナップショット レポート、または Cloud App Security を使用するネットワークから転送されるすべてのログを分析する継続的レポートのいずれかに基づきます。  この設定をどこで行うかを確認するには、ページの右上隅で、**省略記号**を選択します。

    1. 最初のオプション「**Cloud Discovery スナップショット レポートの作成**」を選択します。ここで、要求の詳細を入力し、トラフィック ログをアップロードして、レポートを生成およびアップロードします。  「**キャンセル**」を選択します。  ラボ テナントに表示されるデータは、スナップショット レポートからのデータであり、この情報は画面の右上隅に表示されます。

    1. 継続的レポートのオプションを表示するには、ページの右上隅にある**省略記号**を選択し、ドロップダウンで、「**自動アップロードの構成**」を選択します。  接続されているデータ ソースはありませんが、ここにデータ ソースを追加します。「**アプライアンスの選択**」ドロップダウン矢印を選択して、データ ソースとして接続できるアプライアンスの種類を確認します。  「**キャンセル**」を選択して終了します。

1. もう 1 つの注意点は、クラウド アプリの可視性と制御を向上させるアプリ コネクタを設定し、アプリに直接接続できることです。画面の左上隅で、**「設定」歯車アイコン**を選択し、ドロップダウン リストで、「**アプリ コネクタ**」を選択します。  

    1. 「接続済みアプリ」ページで、一覧に接続済み状態であり Office 365 が表示されます。  Office 365 に接続エラーが表示されている場合は、監査がオンになっていない可能性があります。

    1. 「**+ アプリを接続**」を選択し、ドロップダウン リストで、「**Microsoft Azure**」を選択します。  「Microsoft Azure」ポップアップ ウィンドウで、「**Microsoft Azureの接続**」を選択します。  ユーザー、データ、アクティビティのスキャンに関する接続の状態と情報が表示されます。  **「閉じる」ボタン**を選択します。

1. 次のタスクで使用するため、このページを開いたままにしておきます。

#### デモ パート 2: 記録されたアクティビティを調査する方法の詳細を確認します。

1. 左ナビゲーション パネルで、「**調査**」の下の「**アクティビティ ログ**」を選択します。  ここでは、接続されたアプリからすべてのアクティビティ可視化できます。   すでに Offic e365 コネクタが接続されているので、いくつかのデータを表示できるはずです。App コネクタを使用して Cloud App Security をアプリに接続すると、Cloud App Security は発生したすべてのアクティビティをスキャンします (遡及スキャン期間はアプリごとに異なります)。その後、新しいアクティビティで常に更新されます。  

1. 項目を選択すると、より詳細な情報が表示されます。ページ上部に、検索から新しいポリシーを追加するオプション、または詳細に分析するためにデータをエクスポートするオプションがあることに注意してください。  **検索から「+ 新しいポリシー」** を選択します。  テンプレートに基づいてポリシーを作成し、ポリシーの重大度とカテゴリを選択し、ポリシーのフィルターを作成し、アラートを作成し、さらにアラートを Power Automate に送信する方法に注意してください。  「**キャンセル**」を選択して、「ポリシー作成」ウィンドウを終了します。

1. 左ナビゲーション ペインで、「**ファイル**」オプションを選択および確認し、データのフィルター処理、ファイル ポリシーの作成、データのエクスポートのオプションを確認します。  「**ユーザーとアカウント**」のオプションを選択および確認します。  データをフィルター処理して、データをエクスポートするオプションに注意してください。

1. 左ナビゲーション パネルで、「セキュリティの構成」を選択します。このページでは、Azure、Amazon Web Services (AWS)、および Google Cloud Platform (GCP) アカウントのセキュリティ構成評価を行います。

1. 次のタスクで使用するため、このページを開いたままにしておきます。


#### デモ パート 3: このタスクでは、Microsoft Defender for Cloud Apps のポリシー ページとアラート ページを説明します。

1. 左ナビゲーション パネルで、「制御」の下の「**ポリシー**」を選択します。  一覧表示されたポリシーには、ポリシーによって生成されたアラートの数、重大度などに関する情報が表示されます。任意のライン項目を選択すると、ポリシーに関するより詳細な情報が表示されます。一覧から項目、つまり、「**危険なサインイン**」を選択します。  

1. 左ナビゲーション パネルで、「**アラート**」を選択します。  アラートが一覧表示されている場合は、アラート一覧から項目を選択します。表示された情報を確認します。  ウィンドウの右上で、「**アラートを閉じる**」を選択して、アラートを閉じるためのオプションを表示します。  

1. ブラウザー ウィンドウを閉じます。

#### 確認
このデモでは、Microsoft Defender for Cloud Apps の機能について説明しました。  Cloud Discovery ダッシュボードで使用可能な情報、および検出事項を調査し、ポリシーを通して組織に対する影響を制御するために利用可能な機能について説明しました。
