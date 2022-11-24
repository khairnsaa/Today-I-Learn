# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

last day of week 6!

i just finished my personal task and mini test. to checkout what have i done for my personal task, you can visit this link http://46.137.235.255:3000/api/post/

by the way for the personal task i have succeed to deploy my project to aws ec2. here's a little documentation to access the api that i made

**GET** `http://46.137.235.255:3000/api/post/` get all of the post

**POST** `http://46.137.235.255:3000/api/post/` Create new post (requiring `name` and `post` in request body)

**PUT** `http://46.137.235.255:3000/api/post/:postId` edit post (requiring `name` and `post` in request body)

**DELETE** `http://46.137.235.255:3000/api/post/:postId` delete post

**GET** `http://46.137.235.255:3000/api/comments/:postId` get all of the comments in specific post

**POST** `http://46.137.235.255:3000/api/comments/:postId` Create new comment for specific post (requiring `name` and `comment` in request body)

**PUT** `http://46.137.235.255:3000/api/comments/:commentId` edit comment (requiring `name` and `comment` in request body)

**DELETE** `http://46.137.235.255:3000/api/comments/:commentId` delete comment

![image](https://user-images.githubusercontent.com/53510222/203827050-bc602f6f-deb3-48f1-a3b4-b31735f1fe22.png)
