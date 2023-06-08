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
### Home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitem"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/books.jpg" alt="Building" />
          <div class="contenttext">
            India has been pioneering quality publishing for teachers and institutions. The passion to transform lives is at the centre of our ideology. Royalreader textbooks, developed by leading academicians and practicing teachers are research-based, learner-centric and are the first choice of over 15,000 institutes pan India. Our resources lead the teaching-learning through new methodologies, and sound teaching practices that inspire learners to achieve more through engaging digital and print content.
            <br>
            <br>
            pringer Nature Group, a global and progressive business that opens doors to discovery. Our 500 passionate team members are spread over 26 offices in India. Over 15 million learners use our learning resources, which include 200 new titles every year. Over 50,000 teachers receive professional development inputs from us.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2022 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>

```
### Products.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitemselected">
          <a href="/static/products.html"><b>Products</b></a>
        </div>
        <div class="menuitem"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/bennett.jpg" alt="product image">
                  </div>
                  <div class="itemname">The Vanishing Half</div>
                  <div class="itemprice">Price: Rs.4799.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/divergent.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Divergent</div>
                  <div class="itemprice">Price: Rs.5299.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/code.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The da vinci code</div>
                  <div class="itemprice">Price: Rs.5000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/gaiman.jpg"  alt="product image">
                  </div>
                  <div class="itemname">American Gods</div>
                  <div class="itemprice">Price: Rs.5899.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/hater.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Hate You Give</div>
                  <div class="itemprice">Price: Rs.6299.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/hoover.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Verity</div>
                  <div class="itemprice">Price: Rs.5699.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/kazuo.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Klara and the Sun</div>
                  <div class="itemprice">Price: Rs.5199.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mexican.jpg"  alt="product image">
                  </a>
                  </div>
                  <div class="itemname">Mexican Gothic</div>
                  <div class="itemprice">Price: Rs.5499.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ocean.jpg"  alt="product image">
                  </div>
                  <div class="itemname">On Earth We're Briefly Gorgeous</div>
                  <div class="itemprice">Price: Rs.6399.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/roses.jpg"  alt="product image">
                  </div>
                  <div class="itemname">A Court Of Thorns And Roses</div>
                  <div class="itemprice">Price: Rs.7199.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/seven.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Seven Husbands Of Evenly Hugo</div>
                  <div class="itemprice">Price: Rs.7499.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/stephen.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Shining</div>
                  <div class="itemprice">Price: Rs.6999.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Six-of-Crows.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Six Of Crows</div>
                  <div class="itemprice">Price: Rs.7999.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/turtles.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Turtles All The Way Down</div>
                  <div class="itemprice">Price: Rs.7499.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/whitehead.jpg"  alt="product image">
                  </div>
                  <div class="itemname">The Underground Railground</div>
                  <div class="itemprice">Price: Rs.7799.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2022 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>
```
### People.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitemselected"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitem"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/chairman.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Lee Yung (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/head1.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  John Nickson (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/head2.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Albert Rio (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/manager1.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Maddy Nelson (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/manager2.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Remi Juliet (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/deputy.jpeg" height="500" width="500"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Max Mysterio (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>
```
### Contact.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Royalreader Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>ROYALREADER PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><b>Home</b></a></div>
        <div class="menuitem"><a href="/static/products.html"><b>Products</b></a></div>
        <div class="menuitem"><a href="/static/people.html"><b>People</b></a></div>
        <div class="menuitemselected"><a href="/static/contact.html"><b>Contact Us</b></a></div>
      </div>
      <body>
          <div class="content">
          <h1>&ensp;Contact Information</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:98, king street, Flyer Town, Texas, United States
                    </p>
                    <ul>
                        <br>
                        <li><b>&emsp;Phone:</b>&emsp;2387459648</li>
                        <br>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586456745</li>
                        <br>
                        <li><b>&emsp;Shop Manager Number:</b> 8975455185</li>
                        <br>
                        <li><b>&emsp;Email Id:</b>&emsp;royalreader74@gmail.com</li>
                        <br>
                        <li><b>&emsp;Alternate Email Id:</b>&emsp;royalreader89@gmail.com</li>
                        <br>
                    </ul>
                </div>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Royalreader Private Limited, Developed by Surendhar K.
      </div>
    </div>
  </body>
</html>

```
## OUTPUT:
![Screenshot 2023-06-08 105645](https://github.com/surrey-78/productcompanywebsite/assets/119559366/d3aebd1e-171b-41ee-b3c9-022c329ad001)
![Screenshot 2023-06-08 105703](https://github.com/surrey-78/productcompanywebsite/assets/119559366/b83046e7-9388-4749-b295-25a2df13bc33)
![Screenshot 2023-06-08 105719](https://github.com/surrey-78/productcompanywebsite/assets/119559366/71cea18e-8765-469b-ae62-843b7a6bf637)
![Screenshot 2023-06-08 105739](https://github.com/surrey-78/productcompanywebsite/assets/119559366/32c7aa78-f41a-4e05-9833-80fca737edd5)
![Screenshot 2023-06-08 105757](https://github.com/surrey-78/productcompanywebsite/assets/119559366/38d44ac0-060a-459b-af5d-8335bc2f7729)
![Screenshot 2023-06-08 105834](https://github.com/surrey-78/productcompanywebsite/assets/119559366/4181c99e-0bae-407b-90f8-9643412ca917)
![Screenshot 2023-06-08 105854](https://github.com/surrey-78/productcompanywebsite/assets/119559366/cfc78794-f67b-40e1-b709-eda959f50a28)
![Screenshot 2023-06-08 105913](https://github.com/surrey-78/productcompanywebsite/assets/119559366/b8eced9b-3736-45ea-91dd-f48b312ce6fa)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
