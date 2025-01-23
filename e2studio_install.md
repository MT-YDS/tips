#### **目次**

1. PC Requirements
2. Download
3. Install
4. Launch
5. Install RZV FSP Pack
6. 動作確認
   Kakipで動作確認はまだできないのでFPB-RA2E1で確認

7. 参考
   Kakip + J-Link EDU mini

#### **PC Requirements**

- Windows 10 with Intel i5 or i7, or AMD A10-7850K or FX
- Memory: 8-GB DDR3 or DDR4 DRAM (16-GB DDR4/2400-MHz RAM is preferred)
- Minimum 250-GB hard disk

#### **Download**

1. 下記サイトからWindows用インストーラをダウンロード。

​	https://www.renesas.com/ja/software-tool/e2studio-information-rz-family

​	統合開発環境 e² studio 2024-10 Windows用インストーラ
​	e2studio_installer-2024-10_windows_host.zip

2. 解凍して実行ファイルを得る。

​	e2studio_installer-2024-10_windows_host.exe

#### **Install**

e² studio インストーラをダブルクリック。

| All Usersを選択                                              | Custom Installを選択<br/>Next >                              | **Next >**                                                   |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| <img src="C:\mygithub\tips\images\1.jpg" alt="1" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\2.jpg" alt="2" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\3.jpg" alt="3" style="zoom:33%;" /> |
| **RZを選択**<br />**Next >**                                 | **日本語環境を選択**<br />**Next >**                         | **Next >**                                                   |
| <img src="C:\mygithub\tips\images\4.jpg" alt="4" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\5.jpg" alt="5" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\6.jpg" alt="6" style="zoom:33%;" /> |
| **Next >**                                                   | **契約条件に同意後**<br />**Next >**                         | **Next >**                                                   |
| <img src="C:\mygithub\tips\images\7.jpg" alt="7" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\8.jpg" alt="8" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\9.jpg" alt="9" style="zoom:33%;" /> |
| **インストール**                                             |                                                              | **Launch..を選択し**<br />**OK**                             |
| <img src="C:\mygithub\tips\images\10.jpg" alt="10" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\11.jpg" alt="11" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\12.jpg" alt="12" style="zoom:33%;" /> |

インストールの途中でArm GNU Toolchainのインストールが開始される。
バージョン違いで3、4回繰り返す。

| **OK**                                                       | **次へ(N)>**                                                 | **同意する(A)**                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| <img src="C:\mygithub\tips\images\13.jpg" alt="13" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\14.jpg" alt="14" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\15.jpg" alt="15" style="zoom:33%;" /> |
|                                                              | **Add path…のみ✓し**<br />**他は✓を外す**                    | **完了(F)**                                                  |
| <img src="C:\mygithub\tips\images\16.jpg" alt="16" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\17.jpg" alt="17" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\18.jpg" alt="18" style="zoom:33%;" /> |

#### Launch

| **ワークスペースを指定し**<br />**起動(L)**                  | **いずれかを選択し**<br />**続行(P)**                        | **OK**                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| <img src="C:\mygithub\tips\images\19.jpg" alt="19" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\20.jpg" alt="20" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\21.jpg" alt="21" style="zoom:33%;" /> |
| **OK**                                                       | **起動**                                                     |                                                              |
| <img src="C:\mygithub\tips\images\22.jpg" alt="22" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\23.jpg" alt="23" style="zoom:33%;" /> |                                                              |

#### Install RZV FSP Pack

1. 一旦、e2studioの終了する。

2. 下記から最新のFSPをダウンロードする。

    https://github.com/renesas/rzv-fsp/releases/
    RZV_FSP_Packs_v3.0.0.exe

3. 実行ファイルをダブルクリック。

| **Next >**                                                   | **License termに同意**<br />**I Agree**                      | **E2studioのインストール先を指定<br />** **Install**         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| <img src="C:\mygithub\tips\images\24.jpg" alt="24" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\25.jpg" alt="25" style="zoom:33%;" /> | <img src="C:\mygithub\tips\images\26.jpg" alt="26" style="zoom:33%;" /> |
| **Finish**                                                   |                                                              |                                                              |
| <img src="C:\mygithub\tips\images\27.jpg" alt="27" style="zoom:33%;" /> |                                                              |                                                              |

