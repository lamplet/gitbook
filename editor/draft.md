## 草稿編輯流程（Draft Workflow）

儲存檔案，修改目錄指引或是名詞、索引檔案，都會驅動後台自動進行製書程序。

但有時你還在進行編輯與校對，每次修改都立即製作書籍不符合你的需求，這時就可以啟用「草稿編輯模式」（事實上，這是 Git 開分支的功能），可以讓你完成所有編輯、校對、審閱流程之後，才進行一次製書程序，產生一個新的書籍版本。


1. 從編輯器右上方的「分支選單」，建立一個新分支（branch）
    1. 替分支取個名稱，例如： "firstdraft"
    2. 選擇 "master" 為參考基準（origin branch）
2. 剛剛新建的分支，現在應該會是你工作區內的啟用分支
3. 編輯與修改內容（這時的任何儲存都不會再驅動製書程序了）
4. 當你完成編輯之後，打開分支選單，點選「合併（Merge Branches）」
5. 把在草稿中的所有修改都合併回原來的主分支（master branch）
6. 合併成功之後，你就可以刪除掉草稿分支了
7. 完成！

