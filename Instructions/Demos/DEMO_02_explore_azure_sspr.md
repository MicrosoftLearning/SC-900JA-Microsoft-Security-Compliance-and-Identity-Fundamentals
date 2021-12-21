﻿---
Demo:
    title: 'Azure Active Directory のセルフサービス パスワード リセット'
    module: 'モジュール 2 レッスン 2: Microsoft ID およびアクセス管理ソリューションの機能について説明する: Azure AD のさまざまな認証方法について説明する'
---

# デモ: Azure Active Directory のセルフサービス パスワード リセット (SSPR)

### デモ シナリオ

このデモでは、セルフサービス パスワード リセットの有効化に関連するさまざまな設定について詳しく説明します。

1. ブラウザーで開いている「Contoso – Microsoft Azure」タブに移動します。タブを以前に閉じた場合は、ブラウザー ページを開き、アドレス バーに「portal.azure.com」と入力して、「Azure Active Directory」を選択します。Azure portal に管理者としてログインする必要があります。そうでない場合は、もう一度サインインしてください。

1. 左ナビゲーション ペインで、「パスワードのリセット」を選択します。

1. 「プロパティ」タブが強調表示されます。  「プロパティ」ウィンドウで、SSPR を「なし」、「選択」、または「すべて」で有効にできることに注意してください。
    1. 「セルフサービスのパスワードリセットが有効になっています」と表示されている場所の隣の「情報」アイコンにカーソルを置き、「選択済み」を選択して、パスワードのリセットを限られたユーザー グループに制限するか、「なし」または「すべて」を選択できることを思い出してください。
    1. 「グループの選択」の表示の隣の「情報」アイコンにカーソルを合わせます。ここで、自分のパスワードをリセットできるユーザーのグループを特定することを思い出してください。   ユーザーをこのグループに含めてください。そうしないと、個別にユーザーを選択できなくなります。  また、グループを変更する場合は、選択するグループが、現在一覧表示されているグループを置き換えます。  また、ユーザーをSSPRグループに追加することを推奨します。
    1. 水色の情報ボックスに注意して、学習者にこれらの設定は、組織内のエンド ユーザーにのみ適用されることを思い出させます。管理者はセルフサービス パスワード リセットが常に有効になっており、自分のパスワードをリセットするには 2 つの認証方法を使用する必要があります。

1. 「パスワードのリセット」の左ナビゲーション パネルで、「認証方法」を選択します。
    1. 「リセットに必要なメソッドの数」と表示されている場所の隣の情報アイコンにカーソルを置きます。  これにより、このディレクトリ内のユーザーがパスワードをリセットする必要がある代替の識別方法の数が設定されることに注意してください。   設定を変更しないでください。
    1. SSPR がセキュリティの質問をサポートする点を含め、さまざまな「ユーザーが利用できる方法」に注意してください。「セキュリティの質問」を選択して、セキュリティの質問を使用するためのオプションを表示します。オプションについて説明し終えたら、戻って[セキュリティの質問]を選択し、チェックマークを外します。

1. 「パスワードのリセット」の左ナビゲーション パネルで、「登録」を選択します。
    1. 「サインイン時にユーザーに登録を要求する」と表示されている場所の隣の「情報」アイコンにマウスを合わせます。   これをユーザーに思い出させてください。  
    1. 「ユーザーが認証情報の再確認を求められるまでの日数」と表示されている場所の隣の「情報」アイコンにマウスを合わせます。   これをユーザーに思い出させてください。  

1. 「パスワードのリセット」の左ナビゲーション パネルで、「通知」を選択します。  2 つの設定に注意して、説明の「情報」アイコンの上にマウスを置きます。

1. 「パスワードのリセット」ナビゲーション ペインに監査ログと利用状況と洞察を表示するオプションも含まれることに注意してください。

1. ページの右上隅にある「X」を選択します。これにより、Contoso テナントの「メイン」ページに戻ります。

1. 次のデモのために、このブラウザー ページを開いたままにしておきます。

#### レビュー

このデモでは、セルフサービス パスワード リセットに関連する設定を表示しました。 
