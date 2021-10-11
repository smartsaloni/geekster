# geekster
<!DOCTYPE html>
<html>
    <head>
      <title>Anchor</title>
      <style>
          a {
              margin: 10px;
              text-decoration: none;
          }
      </style>
    </head>

    <body>
       <a href="https://www.facebook.com/" target="_blank">Facebook</a>
       <a href="https://www.amazon.in/" target="_blank">Amazon</a>
       <a href="https://www.flipkart.com/" target="_blank">Flipkart</a>
       <a href="https://geekster.in/" target="_blank">Geekster</a>

    </body>
</html> 
 78  Concept_Oct_04/HTML/Food_world/index.css 
@@ -0,0 +1,78 @@
* {
    margin: 0;
    text-align: center;

}
body {
    background: linear-gradient(45deg,limegreen,coral);

}
table {
    width: 100%;
    margin-top: 30px;
}
img {
    border-radius: 10px;
    box-shadow: 0 0 10px black;
}


#header {
    background-color: black;
    height: 70px;
}
h1 {
    color: cornsilk
}
#brand {
  width: 40%;
  float: left;
  line-height: 70px;
  height: 70px;
  text-align: center;
}

#menu {
  width: 60%;
  float: right;
  line-height: 70px;
  height: 70px;
  text-align: center;
}

a {
    color: cornsilk;
    margin-right: 30px;
    text-decoration: none;

}

#title {
    margin-top: 35px;
}
#pizza {
    margin-top: 20px;
}
#DP {
  background: linear-gradient(45deg,darkred,black);
  color: white;
  width: 500px;
  padding: 15px;
  border-radius: 50%;
  margin:20px auto

}
#TB {
    background: linear-gradient(45deg,darkred,black);
  color: white;
  width: 500px;
  padding: 15px;
  border-radius: 50%;
  margin:20px auto
}
#footer {
    background: black;
    padding: 50px;
    color: cornsilk;
    margin-top: 50px;
} 
 150  Concept_Oct_04/HTML/Food_world/index.html 
@@ -0,0 +1,150 @@
<!DOCTYPE html>

<html>
  <head>
    <title>Food World</title>
    <link href="index.css" rel="stylesheet" />
  </head>

  <body>
    <div id="header">
      <div id="brand">
        <h1>Geekster's Food World</h1>
      </div>

      <div id="menu">
        <a href="">Home</a>
        <a href="">Pizza</a>
        <a href="">Burger</a>
        <a href="">Drinks</a>
      </div>
    </div>

    <div id="main">
      <div id="title">
        <h1>
          <span style="color: yellow">Yummy</span>
          <span style="color: cornsilk">Foods</span>
        </h1>
      </div>

      <div id="pizza">
        <div id="DP">
          <h2>Delicious Pizza</h2>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Consequuntur
          sit placeat id alias ad molestiae ullam eius sint quisquam dolores
          tenetur, odit eum consequatur adipisci nulla eaque atque! Placeat
          nihil ex, corrupti porro iure quo necessitatibus provident veritatis
          omnis deleniti.
        </p>
        <table>
          <tr>
            <td>
              <img
                src="https://images.pexels.com/photos/803290/pexels-photo-803290.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                width="500px"
                height="300px"
              />
            </td>
            <td>
              <img
                src="https://images.pexels.com/photos/365459/pexels-photo-365459.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                width="500px"
                height="300px"
              />
            </td>
          </tr>
          <tr>
            <td>Pizza1</td>
            <td>Pizza2</td>
          </tr>
        </table>

        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus
          fugiat impedit itaque neque veniam dolor, soluta dolorem dicta
          suscipit reiciendis quaerat placeat quod. Consequuntur, officia.
          Inventore autem nesciunt quaerat, nemo odit nostrum eius reiciendis
          harum incidunt explicabo maiores accusamus quis.
        </p>
      </div>

      <div id="burger">
        <div id="TB">
          <h2>Tasty Burger</h2>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum
          quisquam sequi odio et, eveniet dolor voluptas obcaecati voluptate a
          adipisci!
        </p>
        <table>
          <tr>
            <td>
              <img
                src="https://images.pexels.com/photos/3630141/pexels-photo-3630141.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                width="300"
                height="200"
              />
            </td>
            <td>
              <img
                src="https://images.pexels.com/photos/4109132/pexels-photo-4109132.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                width="300"
                height="200"
              />
            </td>
            <td>
              <img
                src="https://images.pexels.com/photos/4253703/pexels-photo-4253703.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                width="300"
                height="200"
              />
            </td>
            <td>
              <img
                src="https://images.pexels.com/photos/2545312/pexels-photo-2545312.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500"
                width="300"
                height="200"
              />
            </td>
          </tr>
          <tr>
            <td>Burger 1</td>
            <td>Burger 2</td>
            <td>Burger 3</td>
            <td>Burger 4</td>
          </tr>
        </table>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Est aliquam
          dicta, a consequatur magni similique laborum ab odio commodi quia
          nesciunt rem harum officia explicabo maiores enim esse nisi quaerat
          autem officiis, eaque, ratione obcaecati? Asperiores expedita itaque
          numquam est vitae, dolore ullam dignissimos commodi dolorum fuga quasi
          praesentium odit, voluptatibus quas neque sapiente ratione. Ducimus
          vitae, voluptate rem obcaecati molestias at recusandae officia. Iusto
          a ratione nesciunt culpa eos.
        </p>
      </div>

      <div id="drinks"></div>
    </div>

    <div id="footer">
     <div></div>

     <div>
         <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt, illo odit modi, quos velit dignissimos expedita molestiae perspiciatis soluta similique sit dicta voluptas veritatis mollitia impedit. Inventore, suscipit magni. Consectetur sapiente vel iste et cupiditate iusto temporibus voluptas aliquid? Sequi corporis eos quo quia perspiciatis voluptas ipsa, magni rem voluptatibus nam cum cupiditate ipsum dicta eligendi, neque impedit illo dolorum illum. Quia molestias minus, itaque nemo natus saepe dolores explicabo?</p>
     </div>

     <div style="margin-top: 20px;">
         <h3>All Copyrights &copy; are Reserved By Kabir-Sagiii</h3>
     </div>


    </div>
  </body>
</html>
 43  Concept_Oct_04/HTML/Table.html 
@@ -0,0 +1,43 @@
<!DOCTYPE html>
<html>
    <head>
        <title>Table element</title>
        <style>
            table {
                width: 100%;
            }
            td {
                text-align: center;
            }
        </style>
    </head>

    <body>

           <div>
               <table border="1">
                   <tr>
                        <th>ID</th>
                        <th>NAME</th>
                        <th>CITY</th>
                   </tr>
                   <tr>
                       <td>1</td>
                       <td>s1</td>
                       <td>Hyd</td>
                   </tr>
                   <tr>
                    <td>2</td>
                    <td>s2</td>
                    <td>Gurugram</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>s3</td>
                    <td>Delhi</td>
                </tr>

               </table>
           </div>
    </body>
</html>
