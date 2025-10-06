# Ex.06 Book Front Cover Page Design
## Date:06-10-2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
book.html

<html>
<head>
  <title>Book Cover Page</title>
  <link rel="stylesheet" href="book1.css">
</head>
<body>
  <div class="cover">
    <div class="top">
      <h4>SEC Insights</h4>
    </div>
  <div class="line"></div>
    </div>
    <div class="title">
      <h1>AUGMENTED REALITY <br>&<br> VIRTUAL REALITY</h1>
      <p>The Future of Immersive Technology From Virtual Worlds to Augmented Experiences</p>
     </div>

    <div class="bottom">
      <div class="left">
        <p><b>SPECIAL EDITION</b></p>
        <p>Sivasakthi S</p>
      </div>
      <div class="right">
        <img src="photo.png" alt="Author">
        <p>SEC</p>
      </div>
    </div>
  </div>
</body>
</html>

book1.css

body {
  margin: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cover {
  width: 600px;
  height: 700px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 15px;
  box-sizing: border-box;
  background-image: url('image.png'); 
  background-clip: border-box;           
  background-position: center;    
  background-size: cover;     
  background-repeat: no-repeat;
  color: white;
}

.top {
  font-size: 25px;
  font-weight: bold;
  text-align: left;
}
.line{
  line-height: 1;
  margin-top: 0px;
}

.title {
  text-align: center;
  margin-bottom: 210px;

}

.title h1 {
  font-size: 40px;
  line-height: 1;
  margin: 0;
  font-weight: bold;
}

.line {
  width: 25%;
  height: 2px;               
  background-color: white;  
}
.bottom {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.left {
  font-size: 13px;
}

.left b {
  display: block;
  margin-bottom: 30px;
}

.right {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.right img {
  width: 80px;
  height: 80px;
  object-fit: cover;
  border: 2px solid white;
  margin-bottom: 5px;
}
```


## OUTPUT:
![alt text](book-1.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
