Github link files: https://github.com/githubde1017/MacOSX-Sorted-script/blob/main/sort_images_by_date.sh

假設要將下載資料夾中的所有圖片檔，依照日期分類歸檔並建立各個日期的資料夾。

請按照以下步驟執行：
假設都是在下載資料夾目錄下。
cd ~/Downloads

Step1
保存並執行腳本：
將上述改進後的腳本內容複製並粘貼到文本編輯器中，並將文件命名為sort_images_by_date.sh。

Step2
保存文件後，在終端中執行以下命令，給腳本添加執行權限：

複製程式碼
chmod +x sort_images_by_date.sh

Step3
然後運行腳本：
sh 
複製程式碼
./sort_images_by_date.sh

這個改進的腳本增加了調試信息，例如當前正在處理的文件類型、找到的文件以及創建的目標目錄和移動文件的操作。這些信息可以幫助你確定腳本是否正確地找到了圖片文件並進行了分類。

＊＊＊＊＊
你可以依照個人需求，針對腳本中要分類的屬性（副檔名）進行修改。
