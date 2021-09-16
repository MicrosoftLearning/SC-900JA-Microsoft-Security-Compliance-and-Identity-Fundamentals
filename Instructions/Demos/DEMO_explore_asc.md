---
Demo:
    title: 'Azure Security Center'
    module: 'モジュール 3 レッスン 2: Microsoft セキュリティ ソリューションの機能を説明する: Azure のセキュリティ管理機能について説明する'
---

# デモ: Azure Security Center

### デモ シナリオ

このデモでは、Azure Security Center を詳しく説明し、Azure Secure Score を使用して、組織のセキュリティ体勢を改善する方法について説明します。

1. ブラウザー タブ「**ホーム - Microsoft Azure**」を開きます。  タブを以前に閉じた場合は、ブラウザー ページを開き、アドレス バーに「portal.azure.com」と入力して、再度サインインします。

1. 検索ボックスのページ上部にある「Microsoft Azure」と表示されている場所の隣の青色バーに、「**セキュリティ センター**」と入力し、検索結果で、「**セキュリティ センター**」を選択します。

1. サブスクリプションを使用してセキュリティ センターに初めてアクセスする場合は、「使用の開始」ページが表示され、アップグレードを求められる場合があります。  ページの下部までスクロールし、「**スキップ**」を選択します。

1. 「セキュリティ センターの概要」ページで利用可能な情報に注意してください。  注: ページの上部に青色の情報ボックスが表示される場合があります。これは、限定情報が表示されていることを示しています。  選択しないでください (処理には最大 15 分かかる場合があり、このデモでは違いはありません)。

1. ページの上部の情報には、Azure サブスクリプションの数、評価されたリソースの数、アクティブな推奨事項の数、セキュリティ アラートが含まれます。  ページの本文には、セキュア スコア、規制コンプライアンス、洞察、Azure Defender などを表すカードがあります。  

1. ページの上部で、「**評価されたリソース**」を選択します。  (これは、セキュリティ センターの「ホーム」ページの左ナビゲーション パネルで、「インベントリ」を選択した場合と同じであることに注意してください)。
    1. これにより、Azure Pass サブスクリプションを表示する 「**インベントリ**」 ページにリダイレクトされます。  「**Azure Pass – スポンサーシップ**」 を選択します。
    1. 「リソース正常性」ページには、推奨事項の一覧が表示されます。  利用可能な一覧で、「**複数の所有者がサブスクリプションに割り当てられている必要があります**」 を選択します。
    1. 修復手順の隣にあるドロップダウン矢印を選択します。詳細な修復手順が措置を講じるためのオプションに沿ってどのように提供されるかについて注意してください。  
    1. 画面の左上隅で、「**セキュリティ センター**」 を選択し、「セキュリティ センターの概要」ページに戻ります。

1. ページの上部で、「**アクティブな推奨事項**」を選択します。  (これは、セキュリティ センターの「ホーム」ページの左ナビゲーション パネルで、「推奨事項」を選択した場合と同じであることに注意してください)。
    1. 「推奨事項」ページには、セキュア スコア ダッシュボードが表示されます。 
    1. セキュア スコア ダッシュボードの下には、制御の一覧があります。各セキュリティ制御は、軽減する必要のあるセキュリティ リスクを表し、その制御に関連付けられている最大スコア、現在のスコア、潜在的なスコアの増加、およびリソースの状態に関する情報も含まれています。  
    1. 「**MFA を有効にする**」 などの制御の 1 つを選択します。  「**サブスクリプションの所有者権限を持つアカウントで MFA を有効にする必要がある**」 など、サブ項目の 1 つを選択します。  開いたページに、説明、修復手順、および影響を受けるリソースが表示されます。画面の右上隅の「**X**」を選択して、このページを終了します。
    1. 画面の右上隅の 「**X**」 を選択して、「推奨事項」ページを終了し、「概要」ページに戻ります。

1. セキュリティ センターの「概要」ページに戻ります。  「メイン」ページで、「セキュア スコア」を選択します (これは、左ナビゲーション パネルで、「セキュア スコア」を選択するのと同じです)。
    1. これにより、セキュア スコア ダッシュボードが表示されます。  さらに、利用可能な管理グループとサブスクリプションが一覧表示されます。  「Azure サブスクリプション – Azure Pass – スポンサーシップ」を選択します。
    1. これにより、前に示した「推奨事項」ページが表示されます。
    1. 画面の右上隅の「**X**」を選択して、「推奨事項」ページを終了します。
    1. 画面の右上隅の「**X**」を選択して、「セキュア スコア」ページを終了し、「概要」ページに戻ります。

1. セキュリティ センターの「概要」ページに戻ります。  「メイン」ページで、「**規制コンプライアンス**」を選択します。(これは、セキュリティ センターの「ホーム」ページの左ナビゲーション パネルで、「推奨事項」を選択した場合と同じであることに注意してください)。
    1. 「規制コンプライアンス」ページには、コンプライアンス制御の一覧が表示されます。  各制御の下に、Azure でクラウド ソリューションをセキュリティで保護する方法に関する推奨事項を提供する Azure セキュリティ ベンチマークに基づく一連の評価が表示されます。
    1. 「**IM.ID 管理**」を選択してから、「**IM.4 すべての Azure Active Directory ベースのアクセスに強力な認証制御を使用する**」を選択します。  一覧には、コンプライアンス体制を改善するために講じることができる顧客責任アクションが表示されます。
    1. 画面に右上隅で、 「**X**」 を選択して、ページを閉じて、「規制コンプライアンス」ページに戻ります。
    1. 画面の右上隅の 「**X**」 を選択して、「概要」ページに戻ります。

1. ページの左上隅にある「ホーム」を選択して、Azure portal の 「**ホーム**」 ページに戻ります。  後のデモで戻るので、このブラウザー タブを利用できるようにしておいてください。

## レビュー

このデモでは、Azure Security Center を詳しく説明し、Azure Secure Score を使用して、組織のセキュリティ体勢を改善する方法について説明しました。