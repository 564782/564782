- 👋 Hi, I’m @564782
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
564782/564782 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
header nav ul {
    display: inline-block;
    
}
header nav ul li {
    display: inline-block;
    margin: 10px 10px; 
    border-right: 1px solid rgb(255, 255, 255);
    padding-right: 15px;
    font-size: 13px
}
header nav ul li a {
    text-decoration: none;
    color: white;
    font-family: sans-serif;
    text-transform: uppercase
}
header nav {
    background-image: linear-gradient(to bottom, rgba(10, 34, 245, 0.432) , rgba(122,5,117,0.5));
    border: 1px solid grey;
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 10px
}
.logo img {
    width: 50px
}
.top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 5px;
}
.right {
    display: inline-block
}
.body {
    display: flex;
/*    justify-content: space-between*/
}
.body-right-top {
    width: 1000px;
    height: 300px;
    background-position: center center;
    position: relative;
    background-image: url('https://i.picsum.photos/id/869/1000/300.jpg?hmac=FbZIYdomDxRhbWFFfqExoNbuI_XbhjeXJt9FK8Dtvj0');
    background-repeat: no-repeat;
    background-size: cover
}
.bottom {
    width: 100%;
    height: 40px;
    background-color: rgb(78, 63, 163);
    position: absolute;
    bottom: 0
}
.bottom span {

    width: 20px;
    height: 20px;
    z-index: 1000
}
.bottom:nth-child(2) {
    background-color: aqua
}
.card {
    width: 250px;
    height: 200px;
    background-image: url('https://i.picsum.photos/id/691/250/200.jpg?hmac=XU4UelNOiSZlF2xJZFBdGH71JcnWbVoIueoW85ZJV7c');
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    margin-right:100px
    display: inline-block;
    margin: 10px 10px; 
    border-right: 1px solid rgb(255, 255, 255);
    padding-right: 15px;
    font-size: 35px;
    font-style: italic;
    color: white
}
.products {
/*    display: inline-block;*/
/*    justify-content: space-between*/
}
.category {
    background-color: rgba(16, 78, 136, 0.137);
    border: 1px solid rgb(78,63,163);
    margin: 10px
}
.category span {
    border-radius: 10px;
    width: 100%
}
.text {
    color: white;
    font-size: 32px;
}
