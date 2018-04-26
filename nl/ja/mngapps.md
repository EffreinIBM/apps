---

copyright:
  years: 2015, 2017, 2018
lastupdated: "2018-03-16"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# アプリの状況の確認
{: #manageapps}

{{site.data.keyword.Bluemix}} コンソールのダッシュボードには、作成したアプリケーションの要約情報が表示されます。 この要約情報に含まれるのは、名前、アイコン、URL、ランタイム、実行状況、およびアプリにバインドされたサービス・インスタンスです。
{:shortdesc}

## アプリの状況の理解
{: #status}

ダッシュボードでは、各アプリケーションの状況を確認できます。 各アプリケーションの「状態」列で、アプリのインスタンスが実行されているかどうかを確認できます。

<dl>
<dt>
<strong>
停止または不明 (灰色)
</strong>
</dt>
<dd>
アプリは停止しているか状況が不明です。 灰色のアイコンは、アプリが停止しているか状況が不明であることを示しています。
</dd>
<dt>
<strong>
実行中 (緑色)
</strong>
</dt>
<dd>
アプリは稼働しています。 緑色のアイコンは、アプリが開始しており、すべてのインスタンスが稼働中であることを示しています。
</dd>
<dt>
<strong>
_Number_ 実行中 (黄色)
</strong>
</dt>
<dd>
アプリは開始していますが、稼動していないインスタンスがあります。 黄色のアイコンは、稼動しているインスタンスは 100% すべてではなく数が少ないことを示しています。 稼動中のインスタンスの数と失敗したインスタンスの数が表示されます。
</dd>
<dt>
<strong>
未実行 (赤色)
</strong>
</dt>
<dd>
アプリは稼働していません。 赤色のアイコンは、アプリは開始していても稼働中のインスタンスがないことを示しています。
</dd>
</dl>

## アプリ詳細ダッシュボードの表示
{: #viewingapps}

ダッシュボードでアプリの名前をクリックすることによって、アプリに関する詳細情報を表示できます。 その後、アプリの概要ページを表示できます。

アプリがデプロイされた後、アプリの概要ページで、開始、停止、再始動を行うことができ、Web アプリケーションの場合は、インスタンス数およびアプリによって使用されるメモリー量を変更できます。 Web アプリケーションの場合、{{site.data.keyword.Bluemix_notm}} は負荷に応じてアプリケーションを自動的に拡大することはしないため、それについてはユーザーが自分で管理する必要があります。

更新が行われた場合、アプリを再デプロイすることができます。アプリの更新には、アプリの最初のデプロイ時と同じメカニズムが使用されます。 {{site.data.keyword.Bluemix_notm}} は実行中のインスタンスをすべて停止し、それらを自動的に新しいインスタンスに置き換えます。