<!DOCTYPE html>
<html lang="km">
<head>
  <meta charset="UTF-8">
  <title>My Video Site</title>
  <style>
    body { text-align: center; font-family: Arial, sans-serif; margin: 20px; }
    .video-box { margin-bottom: 30px; }
  </style>
</head>
<body>
  <h1>ស្វាគមន៍មកកាន់វេបសាយវីដេអូរបស់ខ្ញុំ</h1>

  <div class="video-box">
    <!-- Embed YouTube Video -->
    <iframe width="560" height="315"
      src="https://www.youtube.com/embed/VIDEO_ID"
      frameborder="0"
      allowfullscreen>
    </iframe>
  </div>

  <div class="video-box">
    <!-- ឬប្រសិនបើអ្នកមានវីដេអូ mp4 upload នៅក្នុង repo -->
    <video width="560" height="315" controls>
      <source src="videos/myvideo.mp4" type="video/mp4">
      កញ្ញាជួយ Browser របស់អ្នកមិនគាំទ្របន្ទាត់នេះទេ។
    </video>
  </div>
</body>
</html>
