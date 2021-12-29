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
Home:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="./home.html">Home</a></div>
        <div class="menuitem"><a href="./products.html">Products</a></div>
        <div class="menuitem"><a href="./people.html">People</a></div>
        <div class="menuitem"><a href="./contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
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
        Copyright &#169; 2021 EduSoft Private Limited, Developed by yashaswi mitta .
      </div>
    </div>
  </body>
</html>
~~~
Products:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="./home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="./products.html">Products</a>
        </div>
        <div class="menuitem"><a href="./people.html">People</a></div>
        <div class="menuitem"><a href="./contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
         <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://4.imimg.com/data4/IF/QK/MY-68172/tally-erp-9-250x250.jpg" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.55,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="http://5.imimg.com/data5/MQ/BJ/MY-46980500/tally-erp9-silver-gst-ready-500x500.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.17,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcSHHnytqRmDRU0TNix4rw5Js0024P6yZU1KyVuTWfW9ivVPhveB1B7Cf_VEFZnFFbulGJif1u-Clkp5uZOjAy3DekGpSHPksO1bHUv9m6I&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">TallyPrime GST Ready (Single User - Perpetual).</div>
                <div class="itemprice">Price: Rs.19,800.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcTfzTVx61vjJk72krfwD88Weg5ECq8hlamE-3FVUxueY6zXE7bFYrrunhiCKJdF1cyYJPh405QX7USqBnbcIlDmuR1S4U3Ve7LCjYMBantG&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Tally Prime Single User Latest Version</div>
                <div class="itemprice">Price: Rs.17,900.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn2.gstatic.com/shopping?q=tbn:ANd9GcSOBM2AfbrkDjvVICXifKQKg7w-GVPoUTa7EBZXdTGysfdN_1JpFBBwzRHovptEEPUjC92RouT7pFC9qeBown7GalvKR6AAc_ui_w2q78E&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">E-Invoicing Implementation In Tally Prime</div>
                <div class="itemprice">Price: Rs.11,800.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcTszaqS8qTSOPe4JHKsoL-pZSbbEk7wzBs5hoWHPXp_enPfncOKzc8UpifitAjd143XKSlGOPGubxsQ-_rGUNut5GZdYlu0ldNoRqZgaM8&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Tally.ERP 9 Silver Single user Edition Accounting Software</div>
                <div class="itemprice">Price: Rs.20,300.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcTDxso5uXwbuMEsEP-B1pSEWKXWh6K5tSOwbqKrb9krINqiySXIbOpM53pdeuM4-KQARHewrey4G4P2E0pl0NzZ_tBEQvMdMVzHmkseeJp-JgGPhmw3m5ry&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Tally's Corner: A Study of Negro Streetcorner Men [Book]</div>
                <div class="itemprice">Price: Rs.14,100.28 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcTszNhr1CqKt-8oaF_RTV-uK-c3rxUfFAtFOQbQmn7hQpQIZT0k5hxrsNU88JAUKJsdXcl8-0uPh32EAqnU23FfnVMRR2dfj2zfVfMJo9hJ8JKz71A6GPtHtw&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Upgrade To Tally 9 Multi User To Tally ERP 9 Multi User</div>
                <div class="itemprice">Price: Rs.12,744.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcTXAj5i5KuCt1gFeGHH0Zbncb_SACZcXAwI2PhZ292pfHTzFWWgplEhNZIxAYqvsoPPizZDhsjRYyXSWzArqJ-EYxvNvv4gFw&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Tally Prime Gold Accounting Software single user Unlimited multi-user</div>
                <div class="itemprice">Price: Rs.57,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcRmodWTSbHEXDFYxqjxfEjZG1jqRnbFwvgcR2k-gpaAK42pbWFfQrFA_IhR1S3WTpthACC9165wteZT7vwlYVh47BAt2NRe&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Excel to Tally Software</div>
                <div class="itemprice">Price: Rs.14,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcT3NKcDcwQmnBp9jWPot0OWykxa7oo4NEuKx7cwnqUOVbDNuITmYas7rI9v2vf5VPQ5Ko9MWfjNs537-aSn6MJQydBpKEMY2Q&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Tally Prime Silver Accounting Software single user</div>
                <div class="itemprice">Price: Rs.18,500.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcTEK97JqraxKN5bfgkpQZ1Vf8ucZoeiRAoq60_LUG1ovz19j_U8BONxQb4cnADIFHpMUEPCGptbl3_IlxjyCCAPAOkLaELfAdJR7Bjzoa5NY50_q5JeKXi8XQ&usqp=CAE" alt="product image">
                </div>
                <div class="itemname">Tally ERP9 Gold(Multi User)</div>
                <div class="itemprice">Price: Rs.48,898.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Anandh Sasisharan.
      </div>
    </div>
  </body>
</html>
~~~
People:
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>People</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    </head>
    <body>
        <div class="container">
            <div class="banner">EduSoft Private Limited.</div>
            <div class="menu">
              <div class="menuitem"><a href="./home.html">Home</a></div>
              <div class="menuitem"><a href="./products.html">Products</a></div>
              <div class="menuitemselected"><a href="./people.html">People</a></div>
              <div class="menuitem"><a href="./contact.html">Contact Us</a></div>
            </div>
            <div class="content">
              <div class="productcontent">
                <div class="people1">
                    <img src="data:image/jpeg;base64,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" alt="people1">
                    <h3>CEO of TESLA,SpaceX</h3>
                </div>
                <div class="people2">
                    <img src="data:image/jpeg;base64,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" alt="people2">
                    <h3>Founder and CEO of Facebook,Whatsapp and Instagram</h3>
                </div>
                <div class="people3">
                    <img src="data:image/jpeg;base64,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" alt="people3">
                    <h3>CEO of Google</h3>
                </div>
                <div class="people4">
                    <img src="data:image/jpeg;base64,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" alt="people4">
                    <h3>CEO of Microsoft</h3>
                </div>
                <div class="people5">
                    <img src="data:image/jpeg;base64,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" alt="people5">
                    <h3>CEO of Amazon</h3>
                </div>
                <div class="people6">
                    <img src="data:image/jpeg;base64,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" alt="people6">
                    <h3>Owner of Microsoft</h3>
                </div>
              </div>
            </div>
            <div class="footer">
              Copyright &#169; 2021 EduSoft Private Limited, Developed by yashaswi mitta.
            </div>
          </div>
    </body>
</html>
~~~
Contact:
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Contact</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    </head>
    <body>
        <div class="container">
            <div class="banner">EduSoft Private Limited.</div>
            <div class="menu">
              <div class="menuitem"><a href="./home.html">Home</a></div>
              <div class="menuitem"><a href="./products.html">Products</a></div>
              <div class="menuitem"><a href="./people.html">People</a></div>
              <div class="menuitemselected"><a href="./contact.html">Contact Us</a></div>
            </div>
            <div class="content">
              <div class="homecontent">
                <img src="./img/building.png" alt="Building" />
                <div class="contactus">
                    <h1>Contact Us</h1>
                    <br>
                    <br>
                    <h2>Address : 1-120 nellore,Andhra Pradesh,517500</h2>
                    <br>
                    <h2>Phone No : 8106463420</h2>
                    <br>
                    <h2>Email us on : yashaswi mitta@gmail.com</h2>
                </div>
              </div>
            </div>
            <div class="footer">
              Copyright &#169; 2021 EduSoft Private Limited, Developed by yashaswi mitta.
            </div>
          </div>
    </body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](1.png)

### products Page:
![output](2.png)

### people Page:
![output](3.png)

### contact Page:
![output](4.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
