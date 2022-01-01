# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Jue adventure</title>
    <link rel="stylesheet" href="./css/layout.css" />  
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />    
  </head>

  <body>
    <div class="container">
      <div class="banner">Jue adventure</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
      ss="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="C:/Users/ishwarya/Downloads/juelogo.png">
          <div class="contenttext">
            An adventure game is a video game in which the player assumes the role of a protagonist
            in an interactive story driven by exploration and/or puzzle-solving. The genre's focus on 
            story allows it to draw heavily from other narrative-based media, literature and film,
            encompassing a wide variety of literary genres. Many adventure games are designed for
            single player, since this emphasis on story and character makes multiplayer design difficult.
            <br></br>
            Adventure games continue to be popular in the form of visual novels, which
            make up nearly 70% of PC games released in Japan.Asian countries have also found
            markets for adventure games for portable and mobile gaming devices. Japanese 
            adventure-games tend to be distinct from Western adventure  games and have 
            their own separate development history.
            
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Jue adventure Private Limited, Developed by Ishwarya.v
      </div>
    </div>
  </body>
</html>
~~~

### Product Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Jue adventure</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Jue adventure</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Oddmar</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Criminal case</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Dead target</div>
                  <div class="itemprice">Price: Rs.100.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mini militia</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
              </div>
              <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:\Users\ishwarya\Desktop\webpage\game5.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Shadow fight</div>
                    <div class="itemprice">Price: Rs.100.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                    <img src="C:\Users\ishwarya\Desktop\webpage\game6.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Asphalt8</div>
                    <div class="itemprice">Price: Rs.300.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game7.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Zombie survival</div>
                  <div class="itemprice">Price: Rs.550.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game8.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Clash of clans</div>
                  <div class="itemprice">Price: Rs.350.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game9.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Haunted hunt</div>
                  <div class="itemprice">Price: Rs.370.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game10.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Hill climb race</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game11.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Escape game</div>
                  <div class="itemprice">Price: Rs.100.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\ishwarya\Desktop\webpage\game12.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Among us</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
                </div>
               
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2020 Jue adventure Private Limited, Developed by Ishwarya.V
      </div>
    </div>
  </body>
</html>
~~~

### People Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Jue adventure</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner">Jue adv</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.cheatsheet.com/wp-content/uploads/2020/11/Marvel-star-Robert-Downey-Jr.jpg" alt="product image">
                </div>
                <div class="itemname">Shriram</div>
                <div class="itemprice">Founder</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="	https://m.media-amazon.com/images/M/MV5BMjA1MjE2MTQ2MV5BMl5BanBnXkFtZTcwMjE5MDY0Nw@@._V1_.jpg "  alt="product image">
                </div>
                <div class="itemname">Aakash</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://m.media-amazon.com/images/M/MV5BMTM0ODU5Nzk2OV5BMl5BanBnXkFtZTcwMzI2ODgyNQ@@._V1_.jpg"  alt="product image">
              </div>
              <div class="itemname">Jeeva</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://cdn.britannica.com/38/188638-050-08A5704E/Tom-Hardy-British-2014.jpg"  alt="product image">
              </div>
              <div class="itemname">Rajesh</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://www.emmys.com/sites/default/files/Tom-Hiddleston-bio-450x600.jpg"  alt="product image">
            </div>
            <div class="itemname">Prethivee</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="https://i.pinimg.com/originals/fa/a3/e0/faa3e06e51c2f32bde8939b2654992c7.jpg"  alt="product image">
          </div>
          <div class="itemname">Krishna</div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Jue adventure Private Limited, Developed by Ishwarya.V
    </div>
  </div>
</body>
</html>
~~~

### Contact Us Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Jue adventure</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Jue adventure</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            90/W Jue adventure Private Limited , kolathur,Chennai-600253.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Ms.Kaushika(MARKETING MANAGER):8220156869<br><br>
              Ms.Swathika(OPERATION MANAGER):9865432145<br><br>
              Ms.Shrruthilaya(OFFICE MANAGER):6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:Jueadventureprivatelimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Jue adventure Limited, Developed by Ishwarya.v
      </div>
    </div>
  </body>
</html>
~~~

### Layout CSS Page:
~~~

~~~

## OUTPUT:

### Home Page:

![output](home.png)

### Product Page:
![outtput1](product.png)

### People Page:
![output2](people.png) 

### Contact Us:
![output3](contact.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
