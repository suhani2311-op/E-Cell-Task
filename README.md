# E-Cell-Task
The task is to Make a Blog Page.
#project in HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E CELL (WEB TEAM) TASK</title>
    <---I hve attempted the third task--->
</head>



<prep>
  
  
  <big> <b>              BLOG PAGE DESIGN            </b></big>
    <body>
        <style>
    body {
      font-family: Calliforian FB, sans-serif;
      background: #f7f7f7;
      margin: 1;
      padding: 1;
    }

  header {
      background: #333;
      color: #fafafad8;
      text-align: center;
    }

  .container {
      width: 70%;
      max-width: 1100px;
          }

   .posts {
      display: -moz-inline-box;
      -moz-inline-box-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      ;
    }

   .card {
      background: #ffffff36;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0.1);
      display: legacy;
      flex-direction: column;
    }

  .card img {
      width: 100%;
      height: 180px;
      object-fit: fill;
    }
    .card h3 {
      margin-top: 0;
    }

  .card p {
      color: #555555f6;
    }

  .actions {
      display: legacy;
      justify-content: space-between;
      padding: 0.5rem 1rem 1rem;
    }
    .actions button {
      background: none;
      cursor: pointer;
      color: #33333342;
      font-size: 0.75rem;
    }

  .actions button:hover {
      color: #0077cc;
    }
    .comments {
      margin-top: 1rem;
      background: #fafafa;
      border-radius: 8px;
    }

   .comment {
      border-bottom: 1px solid #ddd;
          }

   .comment:last-child
     {
      border-bottom: none;
    }

   .like.active {
      color: red;
          }
  </style>
</head>
<body>
  <header>
    <h1><b><u>My Blog</u></b></h1>
  </header>

  <div class="container">
    <!-- Blog Posts Grid -->
    <section class="posts">
      <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="Post image">
        <div class="card-content">
          <h3>Post One</h3>
          <p>The first post will be here. The details can be entered in here.</p>
        </div>
        <div class="actions">
          <button class="like">♥ Like</button>
          <button>💬 Comment</button>
          <button>✎ Edit</button>
          <button>🗑 Delete</button>
          <button><:share</button>
        </div>
      </div>

   <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="Post image">
        <div class="card-content">
          <h3>Post Two</h3>
          <p>The second post will be here. The details can be entered in here.</p>
          <a href="#">Read More</a>
        </div>
        <div class="actions">
          <button class="like">♥ Like</button>
          <button>💬 Comment</button>
          <button>✎ Edit</button>
          <button>🗑 Delete</button>
          <button><:share</button>
        </div>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x200" alt="Post image">
        <div class="card-content">
          <h3>Post Three</h3>
          <p>The third post will be here. The details can be entered in here.</p>
        </div>
        <div class="actions">
          <button class="like">♥ Like</button>
          <button>💬 Comment</button>
          <button>✎ Edit</button>
          <button>🗑 Delete</button>
          <button><:share</button>
        </div>
      </div>
    </section>
        <section class="form-container">
      <h2>Create New Post</h2>
      <form>
        <input type="text" placeholder="Post Title" required>
        <textarea rows="6" placeholder="Post Content"></textarea>
        <input type="file" accept="image/*">
        <button type="submit">Create Post</button>
      </form>
    </section>
        <div class="comments">
        <h4>Comments:</h4>
        <div class="comment"><b>Xavier:</b>The post looks nice. </div>
        <div class="comment"><b>Uncle Fester:</b>Is this story for real?.</div>
        <div class="comment"><b>Wednesday:</b>Can't you post some deadly horrifying stuff?</div>
      </div>
    </section>
  </div>
 </body>
</html>

    

</style>
</body>
  </prep>  
</body>
</html>
