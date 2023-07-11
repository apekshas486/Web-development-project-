# Web-development-project
[7/11, 8:41 AM] Apeksha: <!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
        <link rel="stylesheet" href="APEKSHA.CSS">
    </head>
    <body>
      <header>
        <div class="nav_bar">
            <div  class="nav_logo border">
                <div class="logo"></div>

            </div>
            <div class="nav_Address border">
                <p class="address_first">Deliver to</p>
            <div class="address_icon">
                <i class="fa-solid fa-location-dot"></i>
                <p class="adress_second">India</p>
            </div>
        </div>
        <div class="nav_search border">
            <select class="nav_select">
                <option> All</option>
            </select>
            <input placeholder="Search Amazon" type="text"  class="search_input">
            <div class="search_icon">
                <i class="fa-solid fa-magnifying-glass"></i>
            
        </div>
        </div>
        <div class="nav_signin border">
            <p><span>Hello,Sign in</span></p>
            <p class="nav_account"> Account & Lists</p>
        </div>
        <div class="nav_return border">
            <p><span>Returns</span></p>
            <p class="nav_account">& order</p>
        </div>
        <div class="cart border">
            <i class="fa-solid fa-cart-shopping"></i>
            Cart
        </div>
        </div>
        <div class="panel">
            <div class="panel_all">
                <i class="fa-solid fa-bars"></i>
                All
            </div>
            <div class="panel_option">
                <p>Today's Deals</p>
                <p>Customer Servies</p>
                <p>Registry</p>
                <p>Gify Cards</p>
                <p>Sell</p>
            </div>
            <div class="deals">Deals for Electronics </div>
         </div>
      </header>
      <div class="hero_section">
        <div class="hero_message">
            <p>You are on Amazon Now .You can also shop on Amazon India for million of product <a>click here to go in</a></p>
        </div>
      </div>
     
      <div class="shop">
        <div class="box1 box">
            <div class="box_content">
                <h2>Health & Personal Care</h2>
                <div class="box_img" style="background-image: url('GW_CONS_AUS_HPC_HPCEssentials_CatCard_Desktop1x._SY304_CB627424361_.jpg');"></div>
               <p>See more</p>
            </div>
        </div>
        <div class="box2 box">
            <div class="box_content">
                <h2>Beauty pics</h2>
                <div class="box_img" style="background-image: url('Fuji_Dash_Beauty_1x._SY304_CB432774351_.jpg');"></div>
               <p>See more</p>
            </div>
        </div>
        <div class="box3 box">
            <div class="box_content">
                <h2>Fashion</h2>
                <div class="box_img" style="background-image: url('DQC_APR_TBYB_W_BOTTOMS_1x._SY116_CB624172947_.jpg');"></div>
               <p>See more</p>
            </div></div>
        <div class="box4 box">
            <div class="box_content">
                <h2>Electronics</h2>
                <div class="box_img" style="background-image: url('Fuji_Dash_Electronics_1x._SY304_CB432774322_.jpg');"></div>
               <p>See more</p>
            </div>
        </div>
        <div class="box1 box">
            <div class="box_content">
                <h2>Health & Personal Care</h2>
                <div class="box_img" style="background-image: url('GW_CONS_AUS_HPC_HPCEssentials_CatCard_Desktop1x._SY304_CB627424361_.jpg');"></div>
               <p>See more</p>
            </div>
        </div>
        <div class="box2 box">
            <div class="box_content">
                <h2>Beauty pics</h2>
                <div class="box_img" style="background-image: url('Fuji_Dash_Beauty_1x._SY304_CB432774351_.jpg');"></div>
               <p>See more</p>
            </div>
        </div>
        <div class="box3 box">
            <div class="box_content">
                <h2>Fashion</h2>
                <div class="box_img" style="background-image: url('DQC_APR_TBYB_W_BOTTOMS_1x._SY116_CB624172947_.jpg');"></div>
               <p>See more</p>
            </div></div>
        <div class="box4 box">
            <div class="box_content">
                <h2>Electronics</h2>
                <div class="box_img" style="background-image: url('Fuji_Dash_Electronics_1x._SY304_CB432774322_.jpg');"></div>
               <p>See more</p>
            </div>
        </div>
      </div>
      <footer>
        <div class="foot_panel1">back  to top</div>
        <div class="foot_panel2">
            <ul>
              <p>Get to Know us</p>
              <a >Careers</a>
              <a>Blogs</a>
              <a>About Amazon</a>
              <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Get to Know us</p>
                <a >Careers</a>
                <a>Blogs</a>
                <a>About Amazon</a>
                <a>Amazon Science</a>
              </ul> <ul>
                <p>Get to Know us</p>
                <a >Careers</a>
                <a>Blogs</a>
                <a>About Amazon</a>
                <a>Amazon Science</a>
              </ul> <ul>
                <p>Get to Know us</p>
                <a >Careers</a>
                <a>Blogs</a>
                <a>About Amazon</a>
                <a>Amazon Science</a>
              </ul>
        </div>
      </footer>
    </body>
</html>


css code
[7/11, 8:42 AM] Apeksha: *{
    margin: 0%;
    font-family: 'Times New Roman', Times, serif;
    border:border-box;
}
.nav_bar{
   height: 60px;
   background-color: black;
   color: white;
   display: flex;
   align-items: center;
   justify-content: space-evenly;

}
.nav_logo{
    height: 50px;
    width: 100px;
}
.logo{
    background-image: url("images.png");
    height: 50px;
    width: 100%;
    background-size: cover;


}
.border{
    border: 1.5px solid transparent;
}
.border:hover{
    border:1.5px solid white;
}
.address_first{
    margin-left: 15px;
    color: #cccccc;
    font-size: .8rem;

}
.address.second{
    font-size: 1rem;
}
.address_icon{
    display: flex;
    margin-left: 10px;
    align-items: center;
}
.nav_search{
    display: flex;
    background-color: pink;
    width: 575px;
    height: 40px;
    border-radius: 4px;
    
}
.nav_select{
    border-top-left-radius:0.5rem ;
    border-bottom-left-radius: 0.5rem;
    background-color: #f3f3f3;
    width:45px;
    text-align: center;


}
.search_input{
    width: 100%;
    font-size: 1rem;
     border:none;


}
.nav_search:hover{
    border:1px solid darkorange;
}
.search_icon{
    width: 45px;
    display:flex;
    justify-content: center;
    align-items: center;
    font-size: 1rem;
    background-color: orange;
    border-top-right-radius:0.5rem ;
    border-bottom-right-radius: 0.5rem;
    color:#0f1111;
}
span{
    font-size: 0.7rem;
}
.nav_account{
    font: 0.9rem;
    font-weight: 700;
}
.cart i{
    font-size: 2rem;
}
.cart{
    font-weight: 700;
}
.panel{
    display: flex;
    height: 40px;
    background-color: #222f3d;
    color: white;
    justify-content: space-evenly;
    align-items: center;

}

.panel p{
    display: inline;
    margin-left: 16px;
}
.panel_option{
    width: 70%;
    font-size: 0.7;
    
}
.deals{
    font-size: 1rem;
    font-weight: 700;
}
.hero_section{
    background-image: url("appu.jpg");
    height: 350px;
    background-size: cover;
    display: flex;
    justify-content:center;
    align-items: flex-end;

}
.hero_message{
    background-color: white;
    color:black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content:center;
    font-size: 0.85rem;
    width: 80%;
    margin-bottom: 25px;



}
.hero_message a{
    color:#007185;
    font-size: 0.9rem;
}
.shop{
    display:flex;
    flex-wrap: wrap;

    justify-content: space-evenly;
    background-color: pink;
}
.box{
    width: 23%;
    height: 200px;
    padding: 20px 0px 15px;
    background-color: white;
    margin-top: 10px;
}


.box_content{
    margin-left: 10px;
    margin-right: 10px;

}
.box_img{
    margin-top: 1rem;
    margin-bottom:1rem ;
    background-image:contain;
    height: 150px;
}
footer{
    margin-top: 45px;
}
.foot_panel1{
    background-color: #374758;
    color: white;
    height: 50px;
    justify-content: center;
    align-items: center;
    font-size: 0.9rem;
    text-align: center;
    
}
.foot_panel2 {
    background-color: #222f3d;
    color:white;
    height: 500px;;
    display: flex;
    justify-content: space-evenly;
}
ul{
    margin-top: 20px;
}
ul a{
    display: block;
    color: #dddddd;

}
