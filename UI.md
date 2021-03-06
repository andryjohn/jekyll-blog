---
layout: default_UI
title: RJ's UI kit
tags: design
permalink: /design/
mathjax: true
---

>"99% du design d'une application web est contistué des mêmes composants, j'ai décidé d'en coder quelques uns et de vous les partagés!"

Ce sont des *"Composants Web"* que l'on trouve de manière *récurrents*.

 je vais en intégrer les plus connus, tels que les avatars, les boutons, les bannières,... afin de vous les partagés  et cela me permettra d'avoir ma propre librairie.

Pour chaques éléments, les codes sont visible sur [codepen.io](https://codepen.io/dashboard/).

## *"UI kit"* :
> *La majorité des composants utilisent [Bootstrap (4.3)](https://getbootstrap.com/) & [Fontawesome (5.7)](https://fontawesome.com/), si vous décidez d'en utiliser un ou plusieurs , incorporez ces librairies à vos projets!*

## Avatar:

Ce composant simple, néamoins indispensable sur les profils de nos réseaux sociaux.


![avatar](/images/avatar.png)
##### HTML

```html
  <div class="container">
    <h2>Avatar design</h2>
          <img src="./ladies.jpeg" alt="" class="avatar">
           <img src="./ladies.jpeg" alt="" class="avatar-small">
     </div>
```
##### CSS

```css
.avatar {
  border-radius: 50%;
  width: 70px;
}

.avatar-small {
  border-radius: 50%;
  width: 50px;
}
```
## Buttons:
<!--rendering button-->

<div class="container-card">
  <a href="#" class="btn-medium">Write a stories</a>
  <a href="#" class="btn-treehouse">Free Trial</a>
  </div>
  <style>
    .btn-medium {
  color: #999999;
  border: 1px solid #999999;
  padding: 10px 15px;
  margin: 10px;
  border-radius: 50px;
  font-weight: lighter;
  opacity: 0.6;
}
.btn-medium:hover {
  text-decoration: none;
  color: #999999;
  opacity: 1;
}

.btn-treehouse {
  border: 2px solid #4AB66A;
  padding: 10px 15px;
  color: #4AB66A;
  font-weight: bold;
  border-radius: 4px;
  opacity: 0.7;
}
.btn-treehouse:hover {
  text-decoration: none;
  color: #4AB66A;
  opacity: 1;
}
 </style>
<!-- end rendering button-->
##### HTML

```html
<div class="container-card">
  <a href="#" class="btn-medium">Write a stories</a>
  <a href="#" class="btn-treehouse">Free Trial</a>
  </div>
```
##### CSS

```css
  .btn-medium {
  color: #999999;
  border: 1px solid #999999;
  padding: 10px 15px;
  margin: 10px;
  border-radius: 50px;
  font-weight: lighter;
  opacity: 0.6;
}
.btn-medium:hover {
  text-decoration: none;
  color: #999999;
  opacity: 1;
}

.btn-treehouse {
  border: 2px solid #4AB66A;
  padding: 10px 15px;
  color: #4AB66A;
  font-weight: bold;
  border-radius: 4px;
  opacity: 0.7;
}
.btn-treehouse:hover {
  text-decoration: none;
  color: #4AB66A;
  opacity: 1;
}

```
## Nav Bar:

<!--rendering Navbar-->
<div class="container">
  <ul>
    <li class="default"><a href="#"><i class="fa fa-home"></i></a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Blog</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</div>



<style>

.container {
  display: flex;
  text-align: center;
  font-size: 1.35em;
  }

.container ul {
  width: 100%;
  padding: 0px;
  border-radius: .25em;
  background: whitesmoke;
  list-style:none;
  text-align: center;
  }

.container li {
  position:relative;
  display:inline-block;
  border-bottom: none;
  border-radius: .25em .25em 0 0;
  }

.container li:hover { box-shadow: 0 -5px 0 #f47321; }

.container a {
  color:#f47321;
  display:block;
  padding: .5em;
  text-decoration:none;
  }

.container a:hover {
  border-radius: 0 0 .25em .25em;
  background: #f47321;
  box-shadow: 0 5px 0 #dc6519;
  color:white;
  text-shadow: 0 -1px 0 rgba(0,0,0,0.3);
  }
.default { box-shadow: 0 -5px 0 #f47321; }

.default a {
  background: #f47321;
  box-shadow: 0 5px 0 #dc6519;
  color:white;
  border-radius: 0 0 .25em .25em;
  text-shadow: 0 -1px 0 rgba(0,0,0,0.3);
  }
</style>
<!-- end rendering Navbar-->

#### HTML

```html
<div class="container">
  <ul>
    <li class="default"><a href="#"><i class="fa fa-home"></i></a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Blog</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</div>
```
#### CSS
```css
.container {
  display: flex;
  text-align: center;
  font-size: 1.35em;
  }

.container ul {
  width: 100%;
  padding: 0px;
  border-radius: .25em;
  background: whitesmoke;
  list-style:none;
  text-align: center;
  }

.container li {
  position:relative;
  display:inline-block;
  border-bottom: none;
  border-radius: .25em .25em 0 0;
  }

.container li:hover { box-shadow: 0 -5px 0 #f47321; }

.container a {
  color:#f47321;
  display:block;
  padding: .5em;
  text-decoration:none;
  }

.container a:hover {
  border-radius: 0 0 .25em .25em;
  background: #f47321;
  box-shadow: 0 5px 0 #dc6519;
  color:white;
  text-shadow: 0 -1px 0 rgba(0,0,0,0.3);
  }
.default { box-shadow: 0 -5px 0 #f47321; }

.default a {
  background: #f47321;
  box-shadow: 0 5px 0 #dc6519;
  color:white;
  border-radius: 0 0 .25em .25em;
  text-shadow: 0 -1px 0 rgba(0,0,0,0.3);
  }
```
## Alerts!
<!--rendering Alert-->
<div class="flash flash-success alert alert-dismissible fade show" role="alert">
  <span><strong>Yay!</strong> 🎉 you successfully signed in to our service.</span>
</div>

<div class="flash flash-warning alert alert-dismissible fade show" role="alert">
  <span><strong>Mmh</strong> 🤔 seems like you don't have <a href="#">profile picture</a> yet.</span>
</div>

<div class="flash flash-danger alert alert-dismissible fade show" role="alert">
  <span><strong>Oops!</strong> 😱 a problem has occurred while processing your booking.</span>
</div>


<style>
.flash {
  padding: 16px 24px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: whitesmoke;
  box-shadow: 0 0 8px rgba(0,0,0,0.2);
  border-radius: 4px;
  margin: 8px;
}

.flash-success {
  border: 2px solid #1EDD88;
}

.flash-warning {
  border: 2px solid #FFC65A;
}

.flash-danger {
  border: 2px solid #FD1015;
}
.flash:hover {
  webkit-transform: scale(1.2);
  -moz-transform: scale(1.2);
  -ms-transform: scale(1.2);
  -o-transform: scale(1.2);
  transform: scale(1.2);
  transition: 0.9s;

}
</style>
<!--rendering Alert-->
#### HTML

```html
<div class="flash flash-success alert alert-dismissible fade show" role="alert">
  <span><strong>Yay!</strong> 🎉 you successfully signed in to our service.</span>
</div>

<div class="flash flash-warning alert alert-dismissible fade show" role="alert">
  <span><strong>Mmh</strong> 🤔 seems like you don't have <a href="#">profile picture</a> yet.</span>
</div>

<div class="flash flash-danger alert alert-dismissible fade show" role="alert">
  <span><strong>Oops!</strong> 😱 a problem has occurred while processing your booking.</span>
</div>

```
#### CSS
```css
.flash {
  padding: 16px 24px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: whitesmoke;
  box-shadow: 0 0 8px rgba(0,0,0,0.2);
  border-radius: 4px;
  margin: 8px;
}

.flash-success {
  border: 2px solid #1EDD88;
}

.flash-warning {
  border: 2px solid #FFC65A;
}

.flash-danger {
  border: 2px solid #FD1015;
}
.flash:hover {
  webkit-transform: scale(1.2);
  -moz-transform: scale(1.2);
  -ms-transform: scale(1.2);
  -o-transform: scale(1.2);
  transform: scale(1.2);
  transition: 0.9s;

}

```
## Landing page:

[*Voir le code*](https://codepen.io/andryjohn/pen/EzVoWQ)

![Card](/images/landing-page.png)

## Cards grid :

<!--rendering Card grid-->

  <div class="row">
    <div class="col-xs-12 col-sm-4">
    <div class="card" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('https://source.unsplash.com/6ZWhi3YhDY8');">
  <div class="card-category">Popular</div>
  <div class="card-description">
    <h2>Breakfast</h2>
    <p>Awesome</p>
  </div>
  <img class="card-user" src="https://source.unsplash.com/OjvZ_2vSruk">
  <a class="card-link" href="#" ></a>
</div>
    </div>
    <div class="col-xs-12 col-sm-4">
  <div class="card" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('https://source.unsplash.com/osblobZQL8c');">
  <div class="card-category">Popular</div>
  <div class="card-description">
    <h2>Brunch</h2>
    <p>Lovely place, "the best place"</p>
  </div>
  <img class="card-user" src="https://source.unsplash.com/OjvZ_2vSruk">
  <a class="card-link" href="#" ></a>
</div>
    </div>
    <div class="col-xs-12 col-sm-4">
      <!-- insert <div class="card"> --><div class="card" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('https://source.unsplash.com//JnFGgVaFpmE');">
  <div class="card-category">Popular</div>
  <div class="card-description">
    <h2>Asian Foods</h2>
    <p>Awesome place,we Love it!</p>
  </div>
  <img class="card-user" src="https://source.unsplash.com/OjvZ_2vSruk">
  <a class="card-link" href="#" ></a>
</div>
    </div>
  </div>

<style>

.card {
  width: 18em;
  height: 10em;
  text-shadow: 0 1px 3px rgba(0,0,0,0.6);
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  background-size: cover !important;
  background-position: center;
  color: whitesmoke;
  position: relative;
  border-radius: 7px;
  margin: 10px;
}
.card-user {
  position: absolute;
  right: 10px;
  top: 10px;
  width: 60px;
  border-radius: 50%;
  height: 55px;
}
.card-category {
  position: absolute;
  font-family: 'Roboto', sans-serif;
  top: 10px;
  left: 10px;
  font-size: 25px;
  text-transform: uppercase;
}
.card-description {
  position: absolute;
  bottom: 10px;
  left: 10px;
}
.card-description h2 {

  font-size: 15px;
  font-weight: bold;
}
.card-description p {
  font-size: 12px;
  opacity: 0.7;
  font-weight: lighter;
  color: #ffff;
}
.card-link {
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  z-index: 2;
  background: black;
  opacity: 0;
}
.card:hover {
   margin: 10px;
   webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  -ms-transform: scale(1.1);
  -o-transform: scale(1.1);
  transform: scale(1.1);
  transition: 0.9s;
}
</style>

<!--rendering Card grid-->
#### HTML

```html
<div class="row">
    <div class="col-xs-12 col-sm-4">
    <div class="card" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('https://source.unsplash.com/hrlvr2ZlUNk');">
  <div class="card-category">Popular</div>
  <div class="card-description">
    <h2>Breakfast</h2>
    <p>Awesome</p>
  </div>
  <img class="card-user" src="https://source.unsplash.com/OjvZ_2vSruk">
  <a class="card-link" href="#" ></a>
</div>
    </div>
    <div class="col-xs-12 col-sm-4">
  <div class="card" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('https://source.unsplash.com/Pt_YmiYm7a4');">
  <div class="card-category">Popular</div>
  <div class="card-description">
    <h2>Brunch</h2>
    <p>Lovely place, "the best place"</p>
  </div>
  <img class="card-user" src="https://source.unsplash.com/OjvZ_2vSruk">
  <a class="card-link" href="#" ></a>
</div>
    </div>
    <div class="col-xs-12 col-sm-4">
      <!-- insert <div class="card"> --><div class="card" style="background-image: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('https://source.unsplash.com//D-vDQMTfAAU');">
  <div class="card-category">Popular</div>
  <div class="card-description">
    <h2>Asian Foods</h2>
    <p>Awesome place,we Love it!</p>
  </div>
  <img class="card-user" src="https://source.unsplash.com/OjvZ_2vSruk">
  <a class="card-link" href="#" ></a>
</div>
    </div>
  </div>

```
#### CSS


```css
.card {
  width: 15em;
  height: 8em;
  text-shadow: 0 1px 3px rgba(0,0,0,0.6);
  background-size: cover !important;
  background-position: center;
  color: whitesmoke;
  position: relative;
  border-radius: 7px;
  margin: 10px;
}
.card-user {
  position: absolute;
  right: 10px;
  top: 10px;
  width: 60px;
  border-radius: 50%;
  height: 55px;
}
.card-category {
  position: absolute;
  top: 10px;
  left: 10px;
  font-size: 15px;
  text-transform: uppercase;
}
.card-description {
  position: absolute;
  bottom: 10px;
  left: 10px;
}
.card-description h2 {

  font-size: 24px;
}
.card-description p {
  font-size: 14px;
  opacity: 0.7;
  font-weight: lighter;
  color: #ffff;
}
.card-link {
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  z-index: 2;
  background: black;
  opacity: 0;
}
.card:hover {
   margin: 10px;
   webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  -ms-transform: scale(1.1);
  -o-transform: scale(1.1);
  transform: scale(1.1);
  transition: 0.9s;
}


```

## Product Hunt list:


<div class="wrap">
  <ul class="list-unstyled">
        <li class="product">
 <div class="product-upvote text-center">
            <i class="fa fa-caret-up"></i>
            <p>685</p>
       </div>
<img src="http://unsplash.it/200/120/?random" alt="" class="product-image img-rounded">
<div class="product-description">
            <h3>Slack</h3>
            <p>The best chat tool.</p>
          </div>
<ul class="list-inline product-controls">
            <li><a href=""><i class="fa fa-heart"></i></a></li>
            <li><a href=""><i class="fa fa-share"></i></a></li>
            <li><a href=""><i class="fa fa-star"></i></a></li>
          </ul>
        </li>
        <li class="product">
<div class="product-upvote text-center">
            <i class="fa fa-caret-up"></i>
            <p>1250</p>
          </div>
<img src="http://unsplash.it/200/120/?random" alt="" class="product-image img-rounded">
<div class="product-description">
            <h3>Stripe</h3>
            <p>The best payment API.</p>
    </div>
<ul class="list-inline product-controls">
            <li><a href=""><i class="fa fa-heart"></i></a></li>
            <li><a href=""><i class="fa fa-share"></i></a></li>
            <li><a href=""><i class="fa fa-star"></i></a></li>
          </ul>
        </li>
        <li class="product">
 <div class="product-upvote text-center">
            <i class="fa fa-caret-up"></i>
            <p>542</p>
          </div>
 <img src="http://unsplash.it/200/120/?random" alt="" class="product-image img-rounded">
<div class="product-description">
            <h3>Intercom</h3>
            <p>The best CRM tool.</p>
          </div>
<ul class="list-inline product-controls">
            <li><a href=""><i class="fa fa-heart"></i></a></li>
            <li><a href=""><i class="fa fa-share"></i></a></li>
            <li><a href=""><i class="fa fa-star"></i></a></li>
          </ul>
        </li>
      </ul>
</div>

<style>

.product {
  margin: 0px;
  background-color: whitesmoke;
  box-shadow: 0 0 3px rgba(0,0,0,0.2);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
  transition: all 0.3s ease;
  border-radius: 3px;
}

.product:hover {
  background: #cccc;
}

.product:hover .product-upvote {
  font-size: 25px;
}

.product-upvote {
  font-size: 20px;
  padding: 20px;
  transition: all 0.3s ease;
}

.product-description {
  flex: 1 0 auto;
  padding: 20px;
}
.product-controls a {
  font-size: 15px;
  color: #CCCCCC;
}
</style>

#### HTML

```html
<div class="wrap">
  <ul class="list-unstyled">
        <li class="product">
 <div class="product-upvote text-center">
            <i class="fa fa-caret-up"></i>
            <p>685</p>
       </div>
<img src="http://unsplash.it/200/120/?random" alt="" class="product-image img-rounded">
<div class="product-description">
            <h3>Slack</h3>
            <p>The best chat tool.</p>
          </div>
<ul class="list-inline product-controls">
            <li><a href=""><i class="fa fa-heart"></i></a></li>
            <li><a href=""><i class="fa fa-share"></i></a></li>
            <li><a href=""><i class="fa fa-star"></i></a></li>
          </ul>
        </li>
        <li class="product">
<div class="product-upvote text-center">
            <i class="fa fa-caret-up"></i>
            <p>1250</p>
          </div>
<img src="http://unsplash.it/200/120/?random" alt="" class="product-image img-rounded">
<div class="product-description">
            <h3>Stripe</h3>
            <p>The best payment API.</p>
    </div>
<ul class="list-inline product-controls">
            <li><a href=""><i class="fa fa-heart"></i></a></li>
            <li><a href=""><i class="fa fa-share"></i></a></li>
            <li><a href=""><i class="fa fa-star"></i></a></li>
          </ul>
        </li>
        <li class="product">
 <div class="product-upvote text-center">
            <i class="fa fa-caret-up"></i>
            <p>542</p>
          </div>
 <img src="http://unsplash.it/200/120/?random" alt="" class="product-image img-rounded">
<div class="product-description">
            <h3>Intercom</h3>
            <p>The best CRM tool.</p>
          </div>
<ul class="list-inline product-controls">
            <li><a href=""><i class="fa fa-heart"></i></a></li>
            <li><a href=""><i class="fa fa-share"></i></a></li>
            <li><a href=""><i class="fa fa-star"></i></a></li>
          </ul>
        </li>
      </ul>
</div>

```


#### CSS

```css
.card {
  width: 25em;
  height: 12em;
  text-shadow: 0 1px 3px rgba(0,0,0,0.6);
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  background-size: cover !important;
  background-position: center;
  color: whitesmoke;
  position: relative;
  border-radius: 7px;
  margin: 10px;
}
.card-user {
  position: absolute;
  right: 10px;
  top: 10px;
  width: 60px;
  border-radius: 50%;
  height: 55px;
}
.card-category {
  position: absolute;
  top: 10px;
  left: 10px;
  font-size: 35px;
  text-transform: uppercase;
}
.card-description {
  position: absolute;
  bottom: 10px;
  left: 10px;
}
.card-description h2 {

  font-size: 25px;
  font-weight: bold;
}
.card-description p {
  font-size: 20px;
  opacity: 0.7;
  font-weight: lighter;
  color: #ffff;
}
.card-link {
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  width: 100%;
  z-index: 2;
  background: black;
  opacity: 0;
}
.card:hover {
   margin: 10px;
   webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  -ms-transform: scale(1.1);
  -o-transform: scale(1.1);
  transform: scale(1.1);
  transition: 0.9s;
}



```
## Card product :

[*Voir le code*](https://codepen.io/andryjohn/pen/XwmYqw)

<div class="card-product">
  <img src="https://images.unsplash.com/photo-1517336714731-489689fd1ca8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=926&q=80">
  <div class="card-product-infos">
    <h2>Macbook Pro</h2>
    <p>Product description with <strong>relevant info</strong> only.</p>
   </div>
</div>
<style>


.card-product {
  margin: 35px;
  overflow: hidden;
  height: 120px;
  background: white;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  display: flex;
  align-items: center;
  cursor: pointer;
}

.card-product img {
  height: 100%;
  width: 120px;
  object-fit: cover;
  border-radius: none!important;
}

.card-product h2 {
  font-size: 16px;
  font-weight: bold;
  margin: 0;
}

.card-product p {
  font-size: 12px;
  line-height: 1.4;
  opacity: .7;
  margin-bottom: 0;
  margin-top: 8px;
}

.card-product .card-product-infos {
  padding: 16px;
}

.card-product:hover {
  webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  -ms-transform: scale(1.1);
  -o-transform: scale(1.1);
  transform: scale(1.1);
  transition: 0.8s;
}
</style>

#### HTML

```html
<div class="card-product">
  <img src="https://images.unsplash.com/photo-1517336714731-489689fd1ca8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=926&q=80">
  <div class="card-product-infos">
    <h2>Macbook Pro</h2>
    <p>Product description with <strong>relevant info</strong> only.</p>
   </div>
</div>
```
#### css

```css
.card-product {
  margin: 35px;
  overflow: hidden;
  height: 120px;
  background: white;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  display: flex;
  align-items: center;
  cursor: pointer;
}

.card-product img {
  height: 100%;
  width: 120px;
  object-fit: cover;
}

.card-product h2 {
  font-size: 16px;
  font-weight: bold;
  margin: 0;
}

.card-product p {
  font-size: 12px;
  line-height: 1.4;
  opacity: .7;
  margin-bottom: 0;
  margin-top: 8px;
}

.card-product .card-product-infos {
  padding: 16px;
}

.card-product:hover {
  webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  -ms-transform: scale(1.1);
  -o-transform: scale(1.1);
  transform: scale(1.1);
  transition: 0.8s;
}
```

## Card trip:

<div class="card-trip">
  <img src="https://source.unsplash.com/vO0hUESehtc">
  <div class="card-trip-infos">
    <div>
      <h2>Italia </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/MTZTGvDsHFY' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/DpPutJwgyW8">
  <div class="card-trip-infos">
    <div>
      <h2>Kyoto </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/ZHvM3XIOHoE' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/oqFHLfLFtmc">
  <div class="card-trip-infos">
    <div>
      <h2>Japan </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/ZHvM3XIOHoE' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/9sz0RKcPAQw">
  <div class="card-trip-infos">
    <div>
      <h2>Tokyo </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/ZHvM3XIOHoE' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/QAwciFlS1g4">
  <div class="card-trip-infos">
    <div>
      <h2>Paris </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/MTZTGvDsHFY' class="card-trip-user avatar-bordered"/>
  </div>
</div>

  <style>
.card-trip {
  margin: 35px;
  overflow: hidden;
  background: whitesmoke;
  box-shadow: 0 0 15px rgba(0,0,0,0.5);
}

.card-trip > img {
  height: 200px;
  width: 100%;
  object-fit: cover;
}

.card-trip h2 {
  font-size: 17px;
  font-weight: bold;
  margin: 0;
}

.card-trip p {
  font-size: 12px;
  opacity: 0.7;
  margin: 0;
}


.card-trip .card-trip-infos {
  padding: 16px;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  position: relative;
}

.card-trip-infos .card-trip-user {
  position: absolute;
  right: 16px;
  top: -20px;
  width: 45px;
  border-radius: 50%;
}
.card-trip:hover {
   webkit-transform: scale(1.05);
  -moz-transform: scale(1.05);
  -ms-transform: scale(1.05);
  -o-transform: scale(1.05);
  transform: scale(1.05);
  transition: 0.9s;
}
  </style>

#### HTML

```html
<div class="card-trip">
  <img src="https://source.unsplash.com/vO0hUESehtc">
  <div class="card-trip-infos">
    <div>
      <h2>Italia </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/MTZTGvDsHFY' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/DpPutJwgyW8">
  <div class="card-trip-infos">
    <div>
      <h2>Kyoto </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/ZHvM3XIOHoE' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/oqFHLfLFtmc">
  <div class="card-trip-infos">
    <div>
      <h2>Japan </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/ZHvM3XIOHoE' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/9sz0RKcPAQw">
  <div class="card-trip-infos">
    <div>
      <h2>Tokyo </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/ZHvM3XIOHoE' class="card-trip-user avatar-bordered"/>
  </div>
</div>
  <div class="card-trip">
  <img src="https://source.unsplash.com/QAwciFlS1g4">
  <div class="card-trip-infos">
    <div>
      <h2>Paris </h2>
      <p>Come to my hometown, wine and pasta an awesome place!</p>
    </div>
    <h2 class="card-trip-pricing">£199.99</h2>
    <img src='https://source.unsplash.com/MTZTGvDsHFY' class="card-trip-user avatar-bordered"/>
  </div>
</div>
```
#### CSS

```css
.card-trip {
  margin: 35px;
  overflow: hidden;
  background: whitesmoke;
  box-shadow: 0 0 15px rgba(0,0,0,0.5);
}

.card-trip > img {
  height: 200px;
  width: 100%;
  object-fit: cover;
}

.card-trip h2 {
  font-size: 17px;
  font-weight: bold;
  margin: 0;
}

.card-trip p {
  font-size: 12px;
  opacity: 0.7;
  margin: 0;
}


.card-trip .card-trip-infos {
  padding: 16px;
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  position: relative;
}

.card-trip-infos .card-trip-user {
  position: absolute;
  right: 16px;
  top: -20px;
  width: 45px;
  border-radius: 50%;
}
.card-trip:hover {
   webkit-transform: scale(1.05);
  -moz-transform: scale(1.05);
  -ms-transform: scale(1.05);
  -o-transform: scale(1.05);
  transform: scale(1.05);
  transition: 0.9s;
}

```

## Card category:

<div class="pizza">
  <div class="pizza__herro">
      <img src="https://images.unsplash.com/photo-1474600056930-615c3d706456?ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80" alt="pizza" class="pizza__img">
  </div>
    <div class="pizza__content">
        <div class="pizza__title">
            <h1 class="pizza__heading">Pizza Végétarienne 👌</h1>
              <div class="pizza__tag pizza__tag--1">#vegetarian</div>
               <div class="pizza__tag pizza__tag--2">#italian</div>
                 </div>
                  <p class="pizza__description">Une délicieuse pizza veggie composé d'une sauce tomate maison, mozzarella, champignons, oignons rouges, olives & origan </p>
                    <div class="pizza__details">
                      <p class="pizza__detail"><span class="emoji">🍕</span>850 kcal</p>
                        <p class="pizza__detail"><span class="emoji">⏱</span>30 min</p>
                          <p class="pizza__detail"><span class="emoji">⭐</span>4.7 / 5</p>
                            </div>
                        </div>
                       <div class="pizza__price">$11.99</div>
                    </div>
<style>
.pizza {
  max-width: 800px;
  border-radius: 4px;
  overflow: hidden;
  box-shadow: 0 30px 80px 10px rgba(0, 0, 0, 0.2);
  display: flex;
  height: 250px;
}
.pizza__herro {
  flex: 0 0 45%;
}
.pizza__img {
  width: 100%;
  height: 100%;
}
.pizza__content {
  flex: 1;
  background-color: white;
  padding: 10px 45px;
  display: flex;
  flex-direction: column;
}
.pizza__price {
  flex: 0 0 50px;
  background: linear-gradient(to bottom, #67b26f, #4ca2cd);
  color: white;
  writing-mode: vertical-rl;
  display: flex;
  align-items: center;
  justify-content: center;
}
.pizza__title {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}
.pizza__heading {
  font-size: 20px;
  margin-right: auto;
}
.pizza__tag {
  font-size: 10px;
  text-transform: uppercase;
  padding: 2px 7px;
  margin-left: 7px;
  border-radius: 100px;
}
.pizza__tag--1 { background-color: #67b26f; }
.pizza__tag--2 { background-color: #4ca2cd; }
.pizza__description {
  font-size: 14px;
}
.pizza__details {
  display: flex;
  margin: -12px;
}
.pizza__detail {
  font-size: 15px;
  text-transform: uppercase;
  margin-right: 20px;
  font-weight: 700;
  display: flex;
  align-items: center;
}
.emoji {
  font-size: 18px;
  margin-right: 3px;
}
.pizza:hover {
 webkit-transform: scale(1.025);
  -moz-transform: scale(1.025);
  -ms-transform: scale(1.025);
  -o-transform: scale(1.025);
  transform: scale(1.025);
  transition: 0.6s;

}
</style>

#### HTML

```html
<div class="pizza">
  <div class="pizza__herro">
      <img src="https://images.unsplash.com/photo-1474600056930-615c3d706456?ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80" alt="pizza"   class="pizza__img">
         </div>
    <div class="pizza__content">
        <div class="pizza__title">
            <h1 class="pizza__heading">Pizza Végétarienne 👌</h1>
               <div class="pizza__tag pizza__tag--1">#vegetarian</div>
                  <div class="pizza__tag pizza__tag--2">#italian</div>
                     </div>
                        <p class="pizza__description">Une délicieuse pizza veggie composé d'une sauce tomate maison, mozzarella, champignons, oignons rouges, olives & origan </p>
                          <div class="pizza__details">
                            <p class="pizza__detail"><span class="emoji">🍕</span>850 kcal</p>
                              <p class="pizza__detail"><span class="emoji">⏱</span>30 min</p>
                                 <p class="pizza__detail"><span class="emoji">⭐</span>4.7 / 5</p>
                            </div>
                        </div>
                      <div class="pizza__price">$11.99</div>
                   </div>
```
#### CSS

```css
.pizza {
  max-width: 800px;
  border-radius: 4px;
  overflow: hidden;
  box-shadow: 0 30px 80px 10px rgba(0, 0, 0, 0.2);
  display: flex;
  height: 250px;
}
.pizza__herro {
  flex: 0 0 45%;
}
.pizza__img {
  width: 100%;
  height: 100%;
}
.pizza__content {
  flex: 1;
  background-color: white;
  padding: 10px 45px;
  display: flex;
  flex-direction: column;
}
.pizza__price {
  flex: 0 0 50px;
  background: linear-gradient(to bottom, #67b26f, #4ca2cd);
  color: white;
  writing-mode: vertical-rl;
  display: flex;
  align-items: center;
  justify-content: center;
}
.pizza__title {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}
.pizza__heading {
  font-size: 20px;
  margin-right: auto;
}
.pizza__tag {
  font-size: 10px;
  text-transform: uppercase;
  padding: 2px 7px;
  margin-left: 7px;
  border-radius: 100px;
}
.pizza__tag--1 { background-color: #67b26f; }
.pizza__tag--2 { background-color: #4ca2cd; }
.pizza__description {
  font-size: 14px;
}
.pizza__details {
  display: flex;
  margin-top: auto;
}
.pizza__detail {
  font-size: 15px;
  text-transform: uppercase;
  margin-right: 20px;
  font-weight: 700;
  display: flex;
  align-items: center;
}
.emoji {
  font-size: 18px;
  margin-right: 3px;
}
.pizza:hover {
 webkit-transform: scale(1.025);
  -moz-transform: scale(1.025);
  -ms-transform: scale(1.025);
  -o-transform: scale(1.025);
  transform: scale(1.025);
  transition: 0.6s;

}

```
## Messages:

[*Voir le code*](https://codepen.io/andryjohn/pen/RmrrLd)

![Message](/images/messsage.png)



## Notification:

[*Voir le code*](https://codepen.io/andryjohn/pen/PvPVRj)

![Card](/images/notification.png)



## Footer:


[*Voir le code*](https://codepen.io/andryjohn/pen/PvPVRj)

![footer](/images/Footer.png)


D'autres liens sur RJ'blog:
*  [Mise en page avec flexbox et CSS grind!](https://rajohnson-andry.tk/developper/skills/2019/05/09/Top-site/)

 <footer><cite title="Workshop">Credit: Made by ©Andry Rajohnson, inspired by le wagon UI kit </cite></footer>

<style>
  .highlight {
  background-color: #252525;
  box-shadow: 0 0 20px rgba(0,0,0,0.2);
  border-radius: 5px;
}

</style>
