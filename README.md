# cloud_native_hw2
2025 spring - cloud native - assignment 2

Repo link: https://github.com/sheepycat/cloud_native_hw2.git

### Part 1. Repo 操作
---
<img src="readme_img/image.png" alt="alt text" width="700"/>

* 創建新 Repo，設定 repo name、權限 (public)、新增 README.md

<img src="readme_img/image-1.png" alt="alt text" width="400"/>

* 創建 hw-f, hw-p 兩個 branch

### Part 2. Issue
---
<img src="readme_img/image-2.png" alt="alt text" width="700"/>

* 從 Repo settings 的 Features 新增 issue template

<img src="readme_img/image-3.png" alt="alt text" width="700"/>
<img src="readme_img/image-4.png" alt="alt text" width="700"/>

### Part 3&4 Pull Request & GitHub Action
---
* hw-p, hw-f 的 pull request 和 comment:

<img src="readme_img/image-5.png" alt="alt text" width="700"/>
<img src="readme_img/image-6.png" alt="alt text" width="700"/>


* Github action: 使用 template: simple workflow，再額外加入兩個步驟: 使用 requirements.txt install dependencies、 run test.py

<img src="readme_img/image-7.png" alt="alt text" width="400"/>


* hw-p, hw-f PR 的 Github Action 運行結果。其中 hw-f 的 test.py 有 bug，使 Github Action 運行失敗

<img src="readme_img/image-8.png" alt="alt text" width="700"/>
<img src="readme_img/image-9.png" alt="alt text" width="700"/>