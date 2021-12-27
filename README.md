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
    <title>Ice Flow</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"> </div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="https://i.insider.com/58f634d4c75d4a62008b51c8?width=1000&format=jpeg&auto=webp" alt="Building" />
          <div class="contenttext">
            In one very important way all ice creams are the same as they are all gorgeous and are guaranteed to bring a smile to your face, but just think about it for a second, there are many, many different types of products all called ice cream but look, feel and taste very different to one another.
            <br />
            Ice cream is a sweetened frozen food typically eaten as a snack or dessert. It may be made from milk or cream and is flavoured with a sweetener, either sugar or an alternative, and a spice, such as cocoa or vanilla, or with fruit such as strawberries or peaches. ... Ice cream and gelato, based on cream and milk.
            
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Ishwarya.v.
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
    <title>Ice Flow</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
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
                  <img src="https://i.ytimg.com/vi/-5VJ0eJ05Cw/maxresdefault.jpg" alt="product image">
                  </div>
                  <div class="itemname">Sizziling Brownie</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://i.pinimg.com/originals/dc/cf/77/dccf776bebd0ce105c3412cb1edfec6b.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Oreo Mud</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ296VtMAxaNVcsy4viSrorhFLDr0ltcMxPgw&usqp=CAU"  alt="product image">
                  </div>
                  <div class="itemname">Butterscotch ice cream</div>
                  <div class="itemprice">Price: Rs.100.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://www.gimmesomeoven.com/wp-content/uploads/2014/04/Strawberry-Banana-Smoothie-4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Strawberry Banana Smoothie</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
              </div>
              <div class="productitem"> 
                    <div class="itemimage">
                    <img src="https://www.eatingbirdfood.com/wp-content/uploads/2021/06/blueberry-smoothie-straight-on.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Blueberry Smoothie</div>
                    <div class="itemprice">Price: Rs.100.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                    <img src="	https://www.whattheforkfoodblog.com/wp-content/uploads/2021/01/Hot-Chocolate-Bombs-5-web.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Hot Choco Ball</div>
                    <div class="itemprice">Price: Rs.300.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://i.pinimg.com/564x/72/29/d5/7229d5fdeeb781190537efa4ea3fd790.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Brownie Pizza</div>
                  <div class="itemprice">Price: Rs.550.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://simplysohealthy.com/wp-content/uploads/2016/12/fhc-2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Hot Chocolate Fudge </div>
                  <div class="itemprice">Price: Rs.350.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://images.media-allrecipes.com/userphotos/2900185.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Double Chocolate Waffles</div>
                  <div class="itemprice">Price: Rs.370.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://theforkedspoon.com/wp-content/uploads/2020/05/Cherry-Cocktails-16-500x500.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Frozen Borbon</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://upload.wikimedia.org/wikipedia/commons/3/30/Caf%C3%A9_li%C3%A9geois.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Belgium coffee</div>
                  <div class="itemprice">Price: Rs.100.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://aromaticessence.co/wp-content/uploads/2021/05/fruit_cream_featured.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Fruit Salad</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
                </div>
               
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2020 D Organica Private Limited, Developed by Ishwarya.V
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
    <title>Ice Flowd</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
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
                <div class="itemname">AAKASH</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://m.media-amazon.com/images/M/MV5BMTM0ODU5Nzk2OV5BMl5BanBnXkFtZTcwMzI2ODgyNQ@@._V1_.jpg"  alt="product image">
              </div>
              <div class="itemname">JEEVA</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://cdn.britannica.com/38/188638-050-08A5704E/Tom-Hardy-British-2014.jpg"  alt="product image">
              </div>
              <div class="itemname">RAJESH</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://www.emmys.com/sites/default/files/Tom-Hiddleston-bio-450x600.jpg"  alt="product image">
            </div>
            <div class="itemname">HARISH</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="https://i.pinimg.com/originals/fa/a3/e0/faa3e06e51c2f32bde8939b2654992c7.jpg"  alt="product image">
          </div>
          <div class="itemname">SIDDHU</div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Bonanza Private Limited, Developed by Ishwarya.V
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
    <title>Ice Flow</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
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
            90/W Ice Flow Private Limited , kolathur,Chennai-600253.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              MRs.Kaushiya(MARKETING MANAGER):8220156869<br><br>
              MRs.Swathika(OPERATION MANAGER):9865432145<br><br>
              MRs.Shrruthilaya(OFFICE MANAGER):6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:iceflowprivatelimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  Bonanza Private Limited, Developed by Ishwarya.S.
      </div>
    </div>
  </body>
</html>
~~~

### Layout CSS Page:
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: black;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("https://s3.amazonaws.com/zaubatrademarks/6af8b102-3ffe-4006-a6ad-82157c21904c.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #018317;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: rgb(5, 201, 37);
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-image: url("https://images-gmi-pmc.edge-generalmills.com/34c0ac81-656b-45f1-b0b9-6eff351f2dc9.jpg");
  min-height: 500px;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: black;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: black;
  display: inline;
}
.homecontent h1 {
  color: black;
  display: inline;
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color: black;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  display: inline;
  color: rgb(253, 251, 251);
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: inline-block;
}
.productitem .itemimage {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: rgb(253, 249, 249);
  font-family: block;
}
.productitem .itemprice {
  display: block;
  color: rgb(255, 255, 255);
  font-family: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(5, 201, 37);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

.productitem1 .itemimage1 {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  height: 40px;
  margin-bottom: 5px;
}

.productitem1 .itemprice1 {
  display: block;
  color: rgb(255, 255, 255);
  font-family: block;
}
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
