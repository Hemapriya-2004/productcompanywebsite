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
    <title>Hema Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Hema Info Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Hema Info Private Limited, Developed by Hema Priya.
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
    <title>Hema Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Hema Info Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/61odhriZovL._SL1306_.jpg" alt="product image">
                  </div>
                  <div class="itemname">Fresh Desk Customer Software</div>
                  <div class="itemprice">Price: Rs.500 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/61tUB2uBVtS._SL1132_.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Vyaapar Billing Software</div>
                  <div class="itemprice">Price: Rs.200 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://m.media-amazon.com/images/I/41HIgGTcI5L.jpg"  alt="product image">
                </div>
                <div class="itemname">Linux installation drive</div>
                <div class="itemprice">Price: Rs.400</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://m.media-amazon.com/images/I/71yVflZyOYL._SL1500_.jpg"  alt="product image">
              </div>
              <div class="itemname">Windows 10</div>
              <div class="itemprice">Price: Rs.10,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://m.media-amazon.com/images/I/61tAfyBWIrS._SL1500_.jpg"  alt="product image">
            </div>
            <div class="itemname">Microsoft office 365</div>
            <div class="itemprice">Price: Rs.5,510</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/71HpEfZSgkL._SL1500_.jpg"  alt="product image">
          </div>
          <div class="itemname">Office 365 personal</div>
          <div class="itemprice">Price: Rs.3,365 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://m.media-amazon.com/images/I/61jaIhpn07L._SL1500_.jpg"  alt="product image">
        </div>
        <div class="itemname">Windows 10 proffessional</div>
        <div class="itemprice">Price: Rs.11,550</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="https://m.media-amazon.com/images/I/41-XPb2+0qL.jpg"  alt="product image">
      </div>
      <div class="itemname">Ubuntu Installation Drive</div>
      <div class="itemprice">Price: Rs.400</div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="https://images-eu.ssl-images-amazon.com/images/I/41UHOGZVjcL._SY264_BO1,204,203,200_QL40_FMwebp_.jpg"  alt="product image">
    </div>
    <div class="itemname">Accounting software</div>
    <div class="itemprice">Price: Rs.4,356</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/71uDYRKaXKS._SL1500_.jpg"  alt="product image">
  </div>
  <div class="itemname">Kali linux</div>
  <div class="itemprice">Price: Rs.500</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/31Zm+quTpiL.jpg"  alt="product image">
  </div>
  <div class="itemname">Bulk Messager</div>
  <div class="itemprice">Price: Rs.3,500</div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/61ZL4eixRpL._SL1072_.jpg"  alt="product image">
  </div>
  <div class="itemname">MacFee AntiVirus</div>
  <div class="itemprice">Price: Rs.1500</div>
</div>
</div>
</div>        
</div>
<div class="footer">
        Copyright &#169; 2021 Hema Info Private Limited, Developed by Hema Priya.
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
    <title>Hema Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Hema Info Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Crew</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://static.toiimg.com/thumb/msid-73204368,width-400,resizemode-4/73204368.jpg" alt="product image">
                  </div>
                  <div class="itemname">Sundar Pichai</div>
                  <div class="itemprice">CEO</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage"> 
                  <img src="https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F60cbfa276389f09f98133343%2FFacebook-CEO-Mark-Zuckerberg-Testifies-At-Joint-Senate-Commerce-Judiciary-Hearing%2F960x0.jpg%3Ffit%3Dscale"  alt="product image">
                  </div>
                  <div class="itemname">Mr. Mark</div>
                  <div class="itemprice">Branch Manager </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.theladders.com/wp-content/uploads/jeff-bezos-ceo-profile.jpg"  alt="product image">
                </div>
                <div class="itemname">Mr. Jeff</div>
                <div class="itemprice">Capital Manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://4a7efb2d53317100f611-1d7064c4f7b6de25658a4199efb34975.ssl.cf1.rackcdn.com/marissa-mayer-bids-adieu-to-yahoo-showcase_image-8-p-2497.jpg"  alt="product image">
              </div>
              <div class="itemname">Marissa</div>
              <div class="itemprice">Technical Lead</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://static.dezeen.com/uploads/2021/06/elon-musk-architect_dezeen_1704_col_1.jpg"  alt="product image">
            </div>
            <div class="itemname">Mr. Elon Musk</div>
            <div class="itemprice">Team Lead</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://www.deccanherald.com/sites/dh/files/styles/article_detail/public/articleimages/2021/11/30/parags-1055950-1638246491-1056177-1638272241.jpg?itok=Z2RopzRG"  alt="product image">
          </div>
          <div class="itemname">Mr. Parag</div>
          <div class="itemprice">Senior Engineer </div>
      </div>

</div>
</div>
</div>        
</div>
<div class="footer">
        Copyright &#169; 2021 Hema Info Private Limited, Developed by Hema Priya.
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
    <title>Hema Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Hema Info Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
       
          <div class="contenttext">
           Mail us at  hemainfopvtltd@gmail.com
           <br>
           Contact us at 2233445566
           <br>
           Our main office is at 4-199 opposite to clock tower,chaurastha building 5th floor.
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Hema Private Limited, Developed by Hema Priya.
      </div>
    </div>
  </body>
</html>
~~~

### CSS:
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
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
  background-image: url("data:image/jpeg;base64,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");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: darkblue;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: grey;
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
  background-image: url("data:image/jpeg;base64,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");
  background-repeat: no-repeat;
  background-size: cover;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
  color: black
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
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
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
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
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color:grey;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
~~~

## OUTPUT:

### Home Page:

![output](./homepage.png)

### Product Page:

![output](./productpage1.png)

![output](./productpage2.png)

### People Page:

![output](./peoplepage.png)

### Contact Us Page:

![output](./contactuspage.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
