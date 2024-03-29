# React-Forum
Black & Orange is a discussion platform with member functions. Visitors can browse posts by different authors at the same time, leave comments at the bottom of articles to participate in discussions, and view all articles of a specific author through links. Registered users can add and manage article status.

Black & Orange 是一個具備會員功能的討論平台。訪客可以同時瀏覽多個不同作者的發文，在文章下方留言參與討論，並透過連結檢視特定作者的所有文章。註冊用戶可以新增及管理文章狀態。

* [Demo](https://panoopan.github.io/React-Forum/#/)
![](https://github.com/panoopan/React-Forum/blob/main/Demo.gif)


## Features
* Display a list of all discussion articles
* Implement pagination with 5 articles per page, sorted from newest to oldest
* Click on an article title to display the content and comments on a single page
* Click on an author's name to display all articles written by that author
* Implement user registration/login with JWT authentication
* Allow registered users to publish new articles by clicking the "publish" button in the backend and entering a title and content
* Implement article management functionality in the backend for registered users to edit and delete their articles
* Allow logged-in users to add and delete comments on each article

* 顯示所有討論文章列表
* 分頁功能，排序從新到舊，以 5 筆為一頁
* 點擊文章標題，可顯示單頁文章內容及留言
* 點擊作者名稱，可顯示該作者之所有文章
* 註冊/登入功能，透過 JWT 實作驗證機制
* 發布文章功能，登入狀態下，進入後台點擊發布文章按鈕，輸入標題及內容即可新增文章
* 管理功能，登入狀態下，進入後台管理列表，可編輯及刪除文章
* 留言功能，登入狀態下，可於每篇文章下方新增留言，並能刪除自己的留言

<img width="1042" alt="截圖 2021-10-12 上午10 41 01" src="https://user-images.githubusercontent.com/52143262/136882239-d37a3225-564c-4ccb-bcd2-5ac3e4d38db2.png">
<img width="1042" alt="截圖 2021-10-12 上午10 41 10" src="https://user-images.githubusercontent.com/52143262/136882295-559b271c-7a25-45d2-b948-721be7bf36d9.png">
<img width="1042" alt="截圖 2021-10-12 上午10 41 14" src="https://user-images.githubusercontent.com/52143262/136882309-a9fa7daa-28f7-4cfe-9a42-89deb4f5f769.png">
<img width="1041" alt="截圖 2021-09-16 下午2 54 51" src="https://user-images.githubusercontent.com/52143262/133564513-f563c91a-fe49-417e-872a-cc8c1d7aa996.png">
<img width="1042" alt="截圖 2021-10-12 上午10 41 25" src="https://user-images.githubusercontent.com/52143262/136882314-f99681ab-e184-42a4-a3de-11796f857bb8.png">

## Technologies Used
* Using React and React Router
* Integrating with the Lidemy API
* Writing components using JSX syntax
* Supporting RWD, using styled-components and Sass for styling
* Implementing features with React Hooks
* Organizing the file structure of the React app
* Deploying to Github Pages.

* React 搭配 React Router 建立具備會員系統的討論平台
* 串接 Lidemy API
* 以 JSX 語法撰寫元件
* 支援 RWD，使用 styled-components 以 Sass 進行排版
* 使用 React Hooks 實作功能 
* 組織 React app 檔案結構
* Github Pages 部署

## Project Structure
* /src
  * /components
    * App.js
    * Navbar.js
    * Paginator.js
    * Post.js
    * PostForm.js 
    * LoginFrom.js
    * Comment.js
    * CommentForm.js
  * /customHooks
    * useAddPost.js
    * useComments.js
    * useGetPosts.js
    * useEditPost.js
    * usePaginate.js  
    * useLogin.js
    * useRegister.js
    * usePaginate.js
  * /images
  * /pages 
    * HomePage.js
    * LoginPage.js
    * RegisterPage.js
    * AboutPage.js
    * AdminPage.js
    * AuthorPage.js
    * PostPage.js
    * NewPostPage.js
    * EditPostPage.js
  * context.js
  * index.js
  * utils.js
  * WebAPI.js