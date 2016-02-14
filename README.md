TweetBlog: A web application
By
Aakash M Takale
Akhil A Choudhari
Dhaval V Shah
Course: CPSC 476
Due: October 6th

Table of Contents
1. Requirements............................................................................... 3
2. A Public Page.............................................................................. 4
3. Login Page................................................................................. 6
4. A Signup Page..............................................................................7
5. A Home Page...............................................................................8


1. Requirements
Build an Enterprise Java web application to allow users to maintain a group blog (Perhaps we’ll call ours as TweetBlog). Our application supports following features:
1. A public “front page” showing recent posts to the blog in reverse chronological order, along with the author of each post and the date it was posted.
2. A “login” page where users can create an account with a username and password.
3. A “home page” for each user showing that user’s posts and allowing that user, if logged in, to create a new post.
Additional Requirements
1. Use the “Model 2” architecture combining servlets and JSP.
2. Use sessions to maintain state.
3. As in Customer-Support-v3, store users, posts, and other data using in-memory data structures such as HashMap.
4. Limit blog posts to 140 characters.
We have stored User’s session and passwords in HashMap. Other details like Comments in an ArrayList.
 3
2. A Public Page
This is a public “front page” showing recent posts to the blog in reverse chronological order, along with the author of each post and the date it was posted. When there are no posts in the “Recent Post” tab will not show any posts as shown in screenshot below.
  4
After user post their individual post, this public page will have posts of each user, as shown in screenshot below.
  5
3. Login Page
If user has an account then user will enter his/her credentials to get logged in to post his blog. Without logging in user will not be able to post his/her blog.
  6
4. A Signup Page
If user doesn’t have an account, he/she need’s to sign up first to post his/her blog.
  7
5. A Home Page
This page will allow the Logged in user to post his/her blog and also allows to view his/her all the blogs he posted.
Below screenshot shows that user “Akhil” has logged in and now he can post his blog. As this user haven’t posted any blogs yet, this page doesn’t show any blogs below recent posts.
  8
When user “Akhil” post his blog, this page will get updated and shows the blogs that he has posted with the date and time in a reverse chronological order.
  9
