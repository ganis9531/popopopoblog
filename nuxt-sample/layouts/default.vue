<template>
  <div>
  <body>
    <header>
     <h1 class="title">ぽぽたんBLOG</h1>
    </header>
    <div class="main">
      
         <Nuxt />


      <div class="end">
        <h3>ぽんちゃんラヴ</h3>
      </div>

    </div>

    <div class="sub">
      <i class="sample"></i><nuxt-link class="btn" to="/main"> Top </nuxt-link>
        <div class="project">
          <ol>
            <li><nuxt-link class="btn" to="/7-4">   7/4   </nuxt-link></li>
            <li><nuxt-link class="btn" to="/7-11">   7/11   </nuxt-link>  </li>
            <li><nuxt-link class="btn" to="/7-18">  7/18   </nuxt-link></li>
            <li><nuxt-link class="btn" to="/7-2325">  7/23-25  </nuxt-link></li>
            <li><nuxt-link class="btn" to="/8-2">  8/2   </nuxt-link></li>
            <li><nuxt-link class="btn" to="/8-23">  8/23  </nuxt-link></li>
            <li><nuxt-link class="btn" to="/9-26">  9/26  </nuxt-link></li>
          </ol>
        </div>  
    </div>

  </body>
    
  </div>
</template>

<style>

body{
  background-image: url("~assets/ishigaki.jpg");
  background-size:cover;
  background-attachment: fixed;
  height:1000px;
}

header{
  background-image:url("~assets/maikura.png");
  color:#fff;
  width:100%;
  height:100px;
  background-size:cover;
  margin-bottom:15px;
}

.title{
  padding-left: 50px;
  opacity: 0.8;
  margin-bottom:20px;
}

.main{
  background-color: rgba(0,0,0, 0.5);
  color:#fff;
  width:76%;
  float:right;
  margin-right:3px;
  padding:10px;
  margin-bottom:100px;
}
.end{
  display:flex;
  justify-content:flex-end;
  margin-top:1000px;
  font-size:10px;
}
.sub{
  background-color: rgba(0,0,0, 0.5);
  color:#fff;
  width:16%;
  float:left;
  margin-right:3px;
  padding:10px;
}
.sub a{
  color:rgb(255,230,230);
}
.btn:hover{
  opacity:0.7;
}
li{
  list-style:none;
}
</style>
