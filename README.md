# best-repo-ever
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;   
 }

body{
  background: radial-gradient(circle,#aaa,#baf);
  padding: 15px;
 }

.grid-container{
  margin: 10px;
  background-color:#444;
  display: grid;
  grid-template-areas: 
  "header header header"
  "aside main main"
  "aside main main"
  "footer footer footer";
  grid-template-rows: repeat(auto-fill, 1fr);
  border: 4px solid #000;
  height: 92vh;
} 

ul li{
  display: inline-block;
}
.grid_item{
  padding: 25px;
  margin: 5px;
}

.grid-header{
  background:#f96;
  grid-area:header;
}
.grid-main{
  background:#96f;
  grid-area: main;
}
.grid-aside{
  background: #08d;
  grid-area: aside;
}
.grid-footer{
  background:#d80;
  grid-area: footer;
}
