# 0.6.1-beta.1 (2018/09/02)
- **Fix**
  - Fix WatchingStream if we have many watching repositories ([#65](https://github.com/jasperapp/jasper/pull/65) Thanks [@pocke](https://github.com/pocke))
  - Fix not open outdated comment ([@a86f0f9](https://github.com/jasperapp/jasper/commit/a86f0f99433433176808a3dd7f694d3b5475fd03))
  - Fix display description diff ([@2cb49e6](https://github.com/jasperapp/jasper/commit/2cb49e6400ca381b2cc6dc4181a4fe295ed67846))
  - Fix copy/cut/paste text in browser ([@4e7388e](https://github.com/jasperapp/jasper/commit/4e7388e9e35c065183a806608eb33508a97c3cdd))
- **Internal**
  - Update Electron ([#67](https://github.com/jasperapp/jasper/pull/67) Thanks [Watson1978](https://github.com/Watson1978))
  - Update packages ([@78159f7](https://github.com/jasperapp/jasper/commit/78159f783736bf4a64556272e6f0ee58e6dc431c))

# 0.6.0 (2018/07/14)
- **Feat**
  - Jasper is now free
- **Fix**
  - Fix that stream stopped at unexpected timing
  - Change initial loading issue count (1000 to 100)
- **Internal**
  - Update Electron to v1.8.7
  - Use BrowserView instead of WebView

# 0.5.0 (2018/01/27)
- **Fix**
  - A version number in user-agent
  - A default path prefix of GitHub API
  - Toggle buttons clickable region [#48](https://github.com/jasperapp/jasper/issues/48)
- **Internal**
  - Update Electron to v1.7.11 from v1.6.11(includes security fix [CVE-2018-1000006](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-1000006))

# 0.4.0 (2017/08/20)
- **Feat**
  - Support multi account
  - Support multi query at a stream
  - Display a difference of issue body
  - Preference for always open external URL in external browser
  - Save and load streams
  - Support custom UI themes with CSS
  - Improve a performance of displaying un-read count
- **Fix**
  - Using GitHub Enterprise with HTTP
  - Accented letter input
- **Internal**
  - Update Electron to v1.6.11

# 0.3.1 (2017/05/08)
- **Fix**
  - Notify review comment of pull-requests on GHE

# 0.3.0 (2017/04/22)
- **Feature**
  - Create filter for any streams (like as a view of SQL)
  - Filter text in body, repo, author, etc
- **Fix**
  - Broken streams list when right click it ([#14](https://github.com/jasperapp/jasper/issues/14))
  - Suppress notification of self updating
  - Search word in issue on Linux ([#36](https://github.com/jasperapp/jasper/issues/36))

# 0.2.5 (2017/03/13)
- **Fix**
  - Fix a input delaying when post a comment
  - Suppress notification from self posting.
  - Broken J/K moving ([#28](https://github.com/jasperapp/jasper/issues/28))
- **Internal**
  - Update Electron to v1.6.1

# 0.2.4 (2017/01/28)
- **Feat**
  - Support some keyboard shortcuts.
  - Support to read filtered all issues.
  - \[experimental\] Notify review comment of pull-requests.
  - Show a issue number.
- **Fix**
  - Broken handling uppercase/lowercase of label, assignee and milestone. ([#25](https://github.com/jasperapp/jasper/issues/25))
  - Can restart all streams that is workaround of stopping streams. ([#21](https://github.com/jasperapp/jasper/issues/21))
  - Broken zoom
  - Limited width of page when watching split-diff.
- **Internal**
  - Update Electron to v1.4.13

# 0.2.3 (2016/11/21)
- **Fix**
  - Can not load the issue via clicking notification

# 0.2.2 (2016/11/19)
- **Feat**
  - Immediately respond to clicking a issue
- **Fix**
  - Crash when read old issues that does not have multi assignee
  - Display `generate token` link at setup view
  - Handle 404 if we click issues without signed-in
  - Crash when clear all data on Windows
  - Crash when open selecting dialog
- **Internal**
  - Update Electron to v1.4.6

# 0.2.1 (2016/11/13)
- **Feat**
  - Support open external browser with cmd + click
  - Display labels, milestone and comment counts in issues pane ([#5](https://github.com/h13i32maru/jasper/issues/5))
  - Filter issues when click attributes of a issue
    - Clickable attributes are label, milestone, org, repo, author, assignee, opened/closed, and comment
  - Add clear-filter-button
  - Support exclusion filter ([#6](https://github.com/h13i32maru/jasper/issues/6))
  - Support preferences of always open outdated comments
  - Support new review style comment
- **Fix**
  - Broken stream labels when sort those ([#14](https://github.com/jasperapp/jasper/issues/14))
  - Reset the filter when click a stream
  - A stream including `is:open` does not update closed issues

# 0.2.0 (2016/10/22)

🙏 Important notice for paid users (English)

The Jasper requires a license key. The users need to migrate to new app from old app.

- A) Paid at Gumroad
  - 1. Confirm received email from h13i32maru@gmail.com that reference to the license.
  - 2. Please gets license key with written the way in the email.
  - 3. Download new Jasper and register the license key.
- B) Paid at Mac App Store
  - 1. Please send the screen-shot of Mac App Store Purchased tab(including Jasper icon) to [h13i32maru+jasper_license@gmail.com](mailto:h13i32maru+jasper_license@gmail.com)
  - 2. Please gets license key with written the way on reply.
  - 3. Download new Jasper and register the license key.

If you have any questions, please contact h13i32maru@gmail.com.  
Thanks using Jasper.


🙏 購入済みユーザ様への重要なお知らせ(日本語)

Jasperを使用するためにはライセンスキーが必要となりました。 古いアプリを購入済みのユーザ様は新しいアプリへの移行が必要となります。

- A) Gumroadで購入した場合
  - 1. ライセンスに関するメールがh13i32maru@gmail.comから届いていることをご確認ください
  - 2. そのメールに書かれた手順でライセンスキーの取得を行ってください
  - 3. 新しいJasperをダウンロードし、ライセンスキーをJasperに登録してください
- B) Mac App Storeで購入した場合
  - 1. Mac App Storeの購入済みタブのスクリーンショット(Jasperのアイコンを含む)を[h13i32maru+jasper_license@gmail.com](mailto:h13i32maru+jasper_license@gmail.com)まで送信してください
  - 2. 返信されたメールに書かれた手順でライセンスキーの取得を行ってください
  - 3. 新しいJasperをダウンロードし、ライセンスキーを登録してください

ご不明な点がればh13i32maru@gmail.comまでご連絡ください。  
Jasperをご利用いただきありがとうございます。

- **Feat**
  - Support Linux
  - Support screen zoom +/- ([#8](https://github.com/jasperapp/jasper/issues/8))
  - Create a PR stream when initialize
- **Fix**
  - Can not immediately quit
  - Freeze when selecting item link clicked ([#19](https://github.com/jasperapp/jasper/issues/19))
  - Crash if you try to open a file ([#17](https://github.com/jasperapp/jasper/issues/17))
  - Broken style of built-in browser
- **Internal**
  - Update Electron to v1.4.2

# 0.1.2 (2016/06/19)
- **Feat**
  - Support HTTP for GitHub Enterprise
  - Display unread count in Dock's badge (Mac only) ([#6](https://github.com/jasperapp/jasper/issues/6))
- **Fix**
  - Text input is little frozen at issue text area
  - Prevent loading external web page ([#4](https://github.com/jasperapp/jasper/issues/4))
  - Disable notification of archived issues
- **Internal**
  - Update Electron to v1.2.2

# 0.1.1 (2016/06/07)
First Release!
