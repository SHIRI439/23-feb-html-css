<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width, initial-scale=1.0">
    <title>Simple Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="box"></div>
    <button>Click Me</button>
    <div class="gallery">
        <img src="https://www.flipkart.com/aryan-sofia-pink-dolls-soft-toy-cute-kids-girls-40-cm/p/itm4424e8be5ef5c?pid=STFGZX4XWST9MQKM&lid=LSTSTFGZX4XWST9MQKM9LWSRS&marketplace=FLIPKART&store=tng%2Fclb&srno=b_1_5&otracker=browse&fm=organic&iid=a8d7bf93-c9f3-43f8-8813-1bfb16efb740.STFGZX4XWST9MQKM.SEARCH&ppt=browse&ppn=browse" alt="Image 1">
        <img src="https://www.flipkart.com/hezalwood-beautiful-motu-patlu-soft-toy-kids-multicolour-33-cm/p/itmc31df49ed5e59?pid=STFFSXY3NS7GH4FF&lid=LSTSTFFSXY3NS7GH4FFC1XTTW&marketplace=FLIPKART&store=tng%2Fclb&srno=b_1_7&otracker=browse&fm=organic&iid=a8d7bf93-c9f3-43f8-8813-1bfb16efb740.STFFSXY3NS7GH4FF.SEARCH&ppt=browse&ppn=browse" alt="Image 2">
        <img src="https://www.flipkart.com/osjs-long-standing-cute-soft-teddy-bear-gift-birthday-party-other-90-4-cm/p/itm5722f7487f6cf?pid=STFG8FBHYTHGFYZF&lid=LSTSTFG8FBHYTHGFYZFHVRNCS&marketplace=FLIPKART&store=tng%2Fclb&spotlightTagId=FkPickId_mgl%2F1zt&srno=b_1_9&otracker=browse&fm=organic&iid=a8d7bf93-c9f3-43f8-8813-1bfb16efb740.STFG8FBHYTHGFYZF.SEARCH&ppt=browse&ppn=browse" alt="Image 3">
        <img src="https://www.flipkart.com/dogee-teddy-bear-3-feet-panda-soft-toy-birthday-gift-girls-wife-90-cm/p/itmfb8cc37ad693f?pid=STFGA6YUGGZNYKNN&lid=LSTSTFGA6YUGGZNYKNNCIXV3H&marketplace=FLIPKART&store=tng%2Fclb&srno=b_1_10&otracker=browse&fm=organic&iid=a8d7bf93-c9f3-43f8-8813-1bfb16efb740.STFGA6YUGGZNYKNN.SEARCH&ppt=browse&ppn=browse" alt="Image 4">
      </div>
   <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
      </nav>
    <h1>Welcome to My Simple Webpage</h1>
  <p>This is a simple webpage with a title and a paragraph of text. The paragraph is styled with a larger font size and proper line spacing for better readability. The title also has a cool text shadow effect!</p>
  <div class="card">
    <p>This is a simple card with a border, padding, and margin.</p>
  </div>
</body>
</html>

<ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
    <li><a href="#">Link 3</a></li>
    <li><a href="#">Link 4</a></li>
    <li><a href="#">Link 5</a></li>
  </ul>
  <style>
a {
  color: blue;
  text-decoration: none; 
}
a:hover {
  color: red;
}
a:active {
  color: green;
}
h1 {
  font-family: Arial, sans-serif; 
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); 
}

p {
  font-size: 1.2rem; 
  line-height: 1.6; 
  text-align: justify; 
}

.card {
  border: 1px solid gray; 
  padding: 20px;           
  margin: 10px;        
  max-width: 300px;       
}


/* Basic reset */
body, html {
  margin: 0;
  padding: 0;
  height: 100%;
}
nav {
  display: flex; 
  justify-content: center; 
  align-items: center; 
  height: 100vh; 
  background-color: #333; 
}


nav a {
  color: white; 
  text-decoration: none;
  margin: 0 15px; 
  font-size: 18px; 
}

nav a:hover {
  color: #f0f0f0; 
}

.gallery {
  display: grid; 
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 10px; 
  margin: 20px;
}
.gallery img {
  width: 100%; 
  height: auto; 
  border-radius: 8px; 
}
@media (max-width: 600px) {
  .gallery {
    grid-template-columns: 1fr; 
  }
}
button {
  background-color: blue; 
  color: white;           
  border: none;           
  padding: 10px 20px;      
  font-size: 16px;         
  cursor: pointer;        
  border-radius: 5px;      
  transition: background-color 0.3s ease; 
}

button:hover {
  background-color: darkblue;
}
</style>
