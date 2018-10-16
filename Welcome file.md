＃歡迎來到StackEdit！

嗨！我對你們的第一次降價文件** StackEdit **。如果你想了解StackEdit，你可以讀我。如果你想玩Markdown，可以編輯我。完成後，您可以通過打開導航欄左側的*                                                          *文件瀏覽器**來創建新文件。


＃文件

StackEdit存儲您的文件在您的瀏覽器，這意味著您的所有文件會自動保存到本地，都可以訪問**下線！**

## 創建文件和文件夾

可以使用導航欄左下角的按鈕訪問文件資源管理器。您可以通過單擊文件資源管理器中的**新文件**按鈕來創建新文件。您還可以通過單擊**新文件夾**按鈕來創建文件夾。

## 切換到另一個文件

您的所有文件都列在文件資源管理器中，您可以通過單擊列表中的文件從一個切換到另一個。

## 重命名文件

您可以通過單擊導航欄中的文件名或單擊文件資源管理器中的**重命名**按鈕來重命名當前文件。

## 刪除文件

您可以通過單擊文件資源管理器中的**刪除**按鈕來刪除當前文件。該文件將被移動到** Trash **文件夾中，並在7天不活動後自動刪除。

## 導出文件

您可以通過單擊菜單中的**導出到磁盤**來導出當前文件。您可以選擇將文件導出為純Markdown，使用Handlebars模板或PDF作為HTML導出。


＃同步

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

發布後，StackEdit會將您的文件鏈接到該出版物，以便您輕鬆重新發布。修改文件並想要更新出版物後，單擊導航欄中的**立即發布**按鈕。

> **注意：**如果您的文件尚未發布，則**現在**發布**按鈕被禁用。 

## 管理文件發布

由於一個文件可以被發布到多個位置，你可以列出和管理通過點擊發布位置**文件發布**的**發布**子菜單。這允許您列出和刪除鏈接到您的文件的發布位置。


＃降價擴展

StackEdit通過添加額外的** Markdown擴展**擴展了標準Markdown語法，為您提供了一些不錯的功能。

> ** ProTip：**您可以在**文件屬性**對話框中禁用任何** Markdown擴展**。 


## SmartyPants

聰明的傢伙將ASCII標點符號轉換為“智能”排版標點符號HTML實體例如：。

| | ASCII | HTML | | ---------------- | ------------------------------- | ----------------------------- | | 單反手| “？這不是很有趣嗎” ` | “這不好玩嗎？”| | 行情| ` “這不是好玩的？” ` | “這不好玩嗎？”| | 破折號| ` - 是短破折號，---是破折號`|  - 是短劃線，---是em-dash |                

            
            



## KaTeX

您可以使用[KaTeX]（https://khan.github.io/KaTeX/ ）渲染LaTeX數學表達式：

在*伽瑪功能*滿足$ \伽瑪（ñ）=（N-1）！\ quad \ forall n \ in \ mathbb N $是通過Euler積分

$$                                                                          \ Gamma（z）= \ int _0 ^ \ infty t ^ { z-1 } e ^ { -t } dt \ ,. $$



> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```美人魚
序列
圖表愛麗絲 -  >>鮑勃：你好鮑勃，你好嗎？
鮑勃 -  >>約翰：約翰，你呢？
鮑勃 -  x愛麗絲：我很感謝！
Bob-x John：我很感謝！
注意約翰的權利：鮑勃認為很長很長一段時間，因為文本不適合連續。鮑勃 - >愛麗絲：和約翰一起檢查......愛麗絲 - > 約翰：是的......約翰，你好嗎？```





這將產生一個流程圖：

```美人魚
圖LR 
A [方形矩形]  - 鏈接文字 - > B（（圓圈））
A  - > C（圓形矩形）
B  - > D {菱形} 
C  - > D```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NzIyNjI1OTMsLTE1NTU1MTIyM119
-->