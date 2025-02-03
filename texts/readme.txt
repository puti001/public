我來說明如何建立和設定公開的 Github repository:

A.建立新的 Repository:
1. 登入 Github 帳號
2. 點擊右上角的 "+" 按鈕,選擇 "New repository"
3. 填寫 Repository 名稱
4. 在 "Description" 可以加入簡短描述
5. 選擇 "Public"(公開)
6. 勾選 "Add a README file"
7. 點擊 "Create repository"

B. 建立文字檔資料夾:
1. 在 repository 頁面點擊 "Add file" > "Create new file"
2. 在檔名欄位輸入 "texts/" (這會自動建立資料夾)
3. 在資料夾下建立第一個文字檔,例如: "texts/example1.txt"
4. 輸入文字內容
5. 在頁面底部填寫 commit 訊息
6. 點擊 "Commit new file"

C.上傳更多文字檔:
1. 進入 "texts" 資料夾
2. 點擊 "Add file" > "Upload files"
3. 拖曳或選擇要上傳的 .txt 檔案
4. 填寫 commit 訊息
5. 點擊 "Commit changes"

D.修改程式碼中的設定:
this.githubRepo = {
  owner: '您的Github用戶名', // 例如: 'huang-teacher'
  repo: '您的Repository名稱',  // 例如: 'quiz-texts'
  path: 'texts'  // 文字檔所在的資料夾
};

E.取得文字檔的網址:
每個文字檔都會有一個原始檔案網址,格式為:
https://raw.githubusercontent.com/[用戶名]/[Repository名稱]/main/texts/[檔名].txt
