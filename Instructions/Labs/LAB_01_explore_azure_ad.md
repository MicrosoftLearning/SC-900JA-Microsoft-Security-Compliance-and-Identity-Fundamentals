---
lab:
    title: 'Azure Active Directory の詳細を確認する'
    module: 'モジュール 2 レッスン 1: Microsoft ID およびアクセス管理ソリューションの機能について説明する: Azure AD のサービスと ID の種類について調べる'
---

# ラボ: Azure Active Directory の詳細を確認する

## ラボ シナリオ

このラボでは、Azure Active Directory にアクセスします。  さらに、ユーザーを作成し、ライセンスの追加を含む、さまざまな設定を構成します。  



**予想時間**: 10 ～ 15 分

#### タスク 1:  Microsoft 365 のサブスクライバーの方であれば、Azure AD を既にお使いです。  このタスクでは、Microsoft 365 管理者ポータルと Azure portal を通して、Azure AD にアクセスします。

1. Microsoft Edge を開きます。

2. アドレス バーに、「**admin.microsoft.com**」と入力して、Microsoft 365 管理センターにアクセスします。

3. 管理者の資格情報でサインインします。 
    1. 「サインイン」ウィンドウで、「**admin@WWLxZZZZZZ.onmicrosoft.com**」 (ZZZZZZ はラボ ホスティング プロバイダーにより提供される一意のテナント ID です) を入力してから、「**次へ**」を選択します。
    1. ラボ ホスティング プロバイダーから提供される管理者のパスワードを入力します。 「**サインイン**」 を選択します。
    1. サインインしたままにするかどうかを尋ねられたら、「**はい**」を選択します。

4. Microsoft 365 管理センターの左ナビゲーション ペインで、「**すべて表示**」 を選択します。

5. 管理センターの下で、「**Azure Active Directory**」を選択します (下にスクロールする必要があるかもしれません)。  Azure Active Directory 管理センターの「マイ ダッシュボード」ページを表示する新しいブラウザー ページが開きます。ダッシュボードの「メイン」ウィンドウには、組織の ID タイル (Contoso、テナント、Azure AD エディション)、ユーザーとグループのタイルなど、いくつかのタイルが表示されます。

6. 左ナビゲーション ペインで、「お気に入り」の下の「**Azure Active Directory**」を選択します。  「メイン」ウィンドウには、Azure AD で利用可能なすべてのサービスを一覧表示する別のナビゲーション パネルが表示されます。右側に、Contoso テナントに関する情報、作成できる ID の種類やおすすめのサービスに対するリンクが表示されます。  

7. 次に、新しいブラウザー ウィンドウを開いて、アドレス バーに、「**portal.azure.com**」 と入力します。  admin@WWLxZZZZZZ.onmicrosoft.com としてすでにサインインしているので、元々 Azure Pass を使用するのと同じ資格情報を使用していました。Azure portal にアクセスするときは、管理者としてログインする必要があります。  ページの右上隅のメールアドレスを確認し、ユーザー アイコンにマウスをホバリングして、これを確認できます。

8. Azure portal のランディング ページには、Azure Active Directory、VM、ストレージ アカウント、データベースなどの Azure サービスが表示されます。  「**Azure Active Directory**」を選択します。  

9. Microsoft 365 Contoso テナントの Azure Active Directory が表示されています。    Azure Active Directory サービスにアクセスするためにどのアプローチを使用する場合でも (Microsoft 365 管理者ポータルまたは Azure portal)、最終的には同じ場所 Contoso Azure Active Directory に移動します。ここで、すべての Azure AD サービスを管理できます。

10. 次のタスクのために、このブラウザー ページを開いたままにしておきます。


#### タスク 2:  このタスクでは、Azure Active Directory で新しいユーザーを作成する方法を学習し、ユーザー レベルで管理できるいくつかのサービスの詳細を確認します。

1. ブラウザーで開いている「Contoso – Microsoft Azure」タブに移動します。タブを以前に閉じた場合は、ブラウザー ページを開き、アドレス バーに「portal.azure.com」と入力して、「Azure Active Directory」を選択します。  Azure portal に管理者としてログインする必要があります。そうでない場合は、もう一度サインインしてください。

2. 左ナビゲーション ペインで、 「**ユーザー**」 を選択します。  ユーザーによりテナントがすでに構成されていることに注意してください。

3. ページ上部で、 「**+ 新しいユーザー**」 を選択します。

4. 「**ユーザーの作成**」 がすでに選択されているはずです。選択されていない場合は、このオプションを選択します。

5. 「**ID**」 フィールドに次のように入力します。

    1. ユーザー名: **sara**。

    2. 名前フィールド: **Sara Perez**。

    3. 名: **Sara**。

    4. 姓: **Perez**。

6. 「**パスワード**」 フィールドに次のように入力します。

    1. 「**自分でパスワードを作成する**」を選択します。

    1. 初期パスワード: **Naja8996**。Sara が初めてサインインすると、パスワードを変更するように求められます。

7. **グループとロール**を構成します。

    1. 「グループ」の隣の「**0 個のグループが選択されました**」 を選択します。  これにより、利用可能なグループが表示されます。  利用可能なグループの一覧に注意してください。

    2. 「**操作**」を選択してから (下にスクロールする必要があるかもしれません)、「**選択**」 を押します。グループの隣のテキストが 1 つのグループが選択されたことを反映するためにどのように更新されるかに注意してください。  

    3. 「ロール」の隣の「**ユーザー**」を選択します。ディレクション ロールの一覧が表示されます。  下にスクロールして、さまざまな組み込みのロールを確認します。さまざまなロールを確認しますが、ユーザー ロールを変更しないでください。  ページの右上隅の「**X**」を選択して、このウィンドウを閉じます。

8. **設定**を構成する

    1. サインインのブロック:  **いいえ** (既定のままにします。設定のままにします)。

    1. 利用場所: **米国** (ドロップダウンを選択してから、下にスクロールして、このオプションを見つけます)。  ライセンスを割り当てるために、利用場所を構成することが必要です。

9. ページの下部で、「**作成**」 ボタンを選択します。

10. ユーザー一覧にユーザーが表示されることを確認します (名前はアルファベット順に一覧表示されます)。

11. ユーザー一覧から、作成したユーザー「**Sara Perez**」 を選択ます。  「プロファイル」ページが開きます。

12. 左ナビゲーション パネルにユーザーに構成できるさまざまなオプションが表示されます。  「**グループ**」 を選択します。  ここで、グループに関する追加情報を表示できます。  操作グループが一覧表示されることを確認します (グループ割り当てを表示するのに数分かかる場合があります)。  注:  ユーザーを作成するとき、1 つのグループのみを割り当てているため、Contoso グループも表示されます。  これは、事前構成されたポリシーの結果です。テナントでは、新しいユーザーは Contoso グループに自動的に割り当てられます。

13. 左ナビゲーション パネルで、「**ライセンス**」を選択します。  このユーザーにライセンスが割り当てられていないことに注意してください。  

14. ライセンスを追加するには、メイン ウィンドウの上部で、「**+ 割り当て**」 を選択します。

15. 「ライセンスの選択」の下で、「**Office 365 E3**」と「**Windows 10 Enterprise E3**」を」選択してから、画面の下部の「**保存**」ボタンを選択します。画面の右上隅の通知には、ライセンス割り当てが成功したことが表示されるはずです。

16. 画面右上の 「**X**」 を選択して、「ライセンス割り当て」ウィンドウを閉じます。

17. パージの上部の **「更新」アイコン** を選択して、ライセンス割り当てを確認します。

18. 「Contoso Overview Azure Active ディレクトリ」ページに戻り、画面 (階層リンク) の左上の「**Contoso**」を選択します。上部に「Sara Perez | のライセンス」と表示されます。

19. Azure Active Directory でのユーザーの作成および構成に成功しました。

20.	画面の右上隅のメールアドレスの隣の「ユーザー」アイコンをクリックして、すべての「ブラウザー」タブからサインアウトします。次に、すべてのブラウザー ウィンドウを閉じます。

#### タスク 3:  このタスクでは、初めて「Sara Perez」としてサインインします。

1. Microsoft Edge を開きます。

2. アドレス バーに、「**login.microsoft.com**」 と入力します。

3. **sara@WWLxZZZZZ.onmicrosoft.com** としてサインインします (ここで、ZZZZZZ はラボ ホスティング プロバイダーから提供された一意のテナント ID です)。

4. 一時パスワード「**Naja8996**」を入力します。

5. パスワードを更新するように求められます。「現在のパスワード」フィールドに、 「**Naja8996**」 と入力します。

6. 「新しいパスワード」フィールドに、 「**SC900-Lab**」 と入力します。  「パスワードの確認」フィールドに「SC900-Lab」と入力してから、「サインイン」を選択します。
注: ベスト プラクティスとして、より安全なパスワードを使用する必要があります。このパスワードは便宜上、このラボの目的のためにのみ選択されています。

7. Microsoft 365 へのサインインに成功しました。

8. 画面の右上隅のメールアドレスの隣の「ユーザー」アイコンをクリックして、すべての「ブラウザー」タブから**サインアウト**します。次に、すべてのブラウザー ウィンドウを閉じます。



#### レビュー
このラボでは、Azure AD の初期探索を開始しました。Microsoft 365 へのサブスクライバーは、自動的に Azure AD を使用するため、Microsoft 365 管理者ポータルまたは Azure portal を通して、Azure AD の機能やサービスにアクセスしました。  どのアプローチをとっても、同じ場所に移動します。  また、新しいユーザーの作成プロセスを確認し、ユーザーを割り当てることができるグループ、ロールの可用性、ユーザー ライセンスの割り当てなど、構成できるさまざまな設定について確認しました。


