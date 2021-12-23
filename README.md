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
layout.css
```
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
  background-image: url("/static/img/img1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: black;
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
  color: white;
}

.content {
  display: block;
  width: 100%;
  background-color: #D3D3D3;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  font-size: larger;
  
}
.homecontent h1 {
  text-align: left;
  font-size: larger;
}
.homecontent h2 {
  text-align: left;
  font-size: medium;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  font-size: larger;
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
  background-color: #000000;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: white;
}

```
Home Page
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>The Gun Shop</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us:</h1>
          <img src="./img/img2.png" alt="Building" />
          <div class="contenttext">
            The Gun shop has made shopping for firearms more convenient by offering a
            selection of guns available for purchase online. Select the firearm you 
            want and we will ship it to your nearest our retail store for pickup. 
            <br />
            
            No matter what you're shooting, be it handguns, centerfire rifles, rimfire rifles or shotguns,
            We have a gun to suit your needs. We offer legendary firearm brands such as SIG Sauer,
            Browning, CZ-USA, Beretta, Smith & Wesson, Benelli, Ruger and many others. Browse the selection of
            new firearms available for online purchase and have it delivered to your nearest our retail store.
            <ul>
              <li>While only applicablefor new firearms, buying a gun online is simple.</li>
              <li>sell the latest firearm models for hunters and shooters .</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 The Gun Shop Corporation, Developed by RAJESHKANNAN.M.
      </div>
    </div>
  </body>
</html>

```
Products Page
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>The Gun Shop</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Taurus G2C Pistol.jfif" alt="product image">
                  </div>
                  <div class="itemname">Taurus G2C Pistol</div>
                  <div class="itemprice">Price: $236.04 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Ruger-57 Pistol.jfif"  alt="product image">
                  </div>
                  <div class="itemname">Ruger-57 Pistol</div>
                  <div class="itemprice">Price: $599.97</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Ruger PC Carbine Semi-Auto Rifle.jfif" alt="product image">
                </div>
                <div class="itemname">Ruger PC Carbine Semi-Auto Rifle</div>
                <div class="itemprice">Price: $658.774 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/Hornady FTX Bullets.png" alt="product image">
              </div>
              <div class="itemname">Hornady FTX Bullets</div>
              <div class="itemprice">Price: $37.04-$44.90</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/Christensen Arms Ridgeline Bolt-Action Rifle.jfif" alt="product image">
            </div>
            <div class="itemname">Christensen Arms Ridgeline Bolt-Action Rifle</div>
            <div class="itemprice">Price: $2180.09 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/CZ 612 Home Defense Pump-Action Shotgun.jfif" alt="product image">
          </div>
          <div class="itemname">CZ 612 Home Defense Pump-Action Shotgun</div>
          <div class="itemprice">Price: $300.87 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/TriStar Viper G2 Synthetic Semi-Auto Shotgun.jfif" alt="product image">
            </div>
            <div class="itemname">TriStar Viper G2 Synthetic Semi-Auto Shotgun</div>
            <div class="itemprice">Price: $7100.89 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/Tipton Carbon Fiber Cleaning Rod.jfif" alt="product image">
              </div>
              <div class="itemname">Tipton Carbon Fiber Cleaning Rod</div>
              <div class="itemprice">Price: $40.89 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/Ramrodz Cotton Gun Cleaning Swabs.jfif" alt="product image">
            </div>
            <div class="itemname">Ramrodz Cotton Gun Cleaning Swabs</div>
            <div class="itemprice">Price: $10.99 </div>
            </div>    
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/RangeMaxx Rifle Bore Mop.jfif" alt="product image">
              </div>
              <div class="itemname">RangeMaxx Rifle Bore Mop</div>
              <div class="itemprice">Price: $15.25</div>
              </div>    
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Hoppe's BoreSnake CLP Gun Oil.jfif" alt="product image">
                </div>
                <div class="itemname">Hoppe's BoreSnake CLP Gun Oil</div>
                <div class="itemprice">Price: $19.25</div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Hammerli TAC R1 M-LOK Semi-Auto Rifle.jfif" alt="product image">
                  </div>
                  <div class="itemname">Hammerli TAC R1 M-LOK Semi-Auto Rifle</div>
                  <div class="itemprice">Price: $1958.52</div>
                  </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 The Gun Shop Corporation, Developed by RAJESHKANNAN.M.
      </div>
    </div>
  </body>
</html>

```
People Page
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>The Gun Shop</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company promoters:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/1.png" alt="product image">
                </div>
                <div class="itemname"> Justin Kriishswa </div><br><br><br>
                <div class="itemprice">   CEO  </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/2.png"  alt="product image">
                </div>
                <div class="itemname"> John kawshru </div><br><br><br>
                <div class="itemprice">CHAIRMAN</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/3.png"  alt="product image">
              </div>
              <div class="itemname">Williams jejepriaa</div><br><br><br>
              <div class="itemprice">CHAIRMAN</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/4.png"  alt="product image">
              </div>
              <div class="itemname">Martin srikisven</div><br><br><br>
              <div class="itemprice">CHAIRMAN</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/5.png"  alt="product image">
            </div>
            <div class="itemname">Ronald frndfakes</div><br><br><br>
            <div class="itemprice">CHAIRMAN </div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/6.png"  alt="product image">
          </div>
          <div class="itemname">Steven saashdiba </div><br><br><br>
          <div class="itemprice">  CFO  </div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 The Gun Shop Corporation, Developed by RAJESHKANNAN.M.
    </div>
  </div>
</body>
</html>
```
Contact Us Page
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>The Gun Shop</title>
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
          <h1>Contact Us:</h1><br>
          <h2>Address:</h2>
          <div class="contenttext">
           Hesperides,
           <br>Lake Wales,
           <br>Florida.
          </div><br>
          <h2>Phone:</h2>
          <div class="contenttext">
            1-800-237-4444
          </div><br>
          <h2>E-Mail:</h2>
          <div class="contenttext">
           customer.service@thegunshop.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  The Gun Shop corporation, Developed by RAJESHKANNAN.M.
      </div>
    </div>
  </body>
</html>
```
## OUTPUT:

### Home Page:

![output 1](./images/SSS2.png)

### Product Page:
![output 2](./images/SSS1.png)

### People Page:
![output 3](./images/SSS3.png)

### Contact Us Page:
![output 4](./images/SSS4.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
