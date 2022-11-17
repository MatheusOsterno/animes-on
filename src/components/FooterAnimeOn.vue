<template lang="">
<footer class="footer">
    <div class="page-up">
        <a href="#" id="scrollToTopButton"><i class="fa-solid fa-up-long"></i></a>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-lg-3">
                <div class="footer__logo">
                    <a href="./index.html"><img src="@/assets/logo.png" alt=""></a>
                </div>
            </div>
            <div class="col-lg-6">
                <div class="footer__nav">
                    <ul>
                        <li class="active"><a href="./index.html">Homepage</a></li>
                        <li><a href="./categories.html">Categories</a></li>
                        <li><a href="./blog.html">Our Blog</a></li>
                        <li><a href="#">Contacts</a></li>
                    </ul>
                </div>
            </div>
            <div class="col-lg-3">
                <p>
                Copyright &copy; All rights reserved | Seu anime sempre ON <i class="fa fa-heart" aria-hidden="true"></i> by <a href="" target="_blank">Matheus Osterno</a>
                </p>
              </div>
          </div>
      </div>
  </footer>

</template>
<script>
export default {
    
}
</script>
<style scoped>
img {
	height: 50px;
	text-align: center;
	cursor: pointer;
}

/*---------------------
  Footer
-----------------------*/

.footer {
	background:#dbdbdb;
	padding-top: 60px;
	padding-bottom: 40px;
	position: relative;
}

.page-up {
	position: absolute;
	left: 50%;
	top: -25px;
	margin-left: -25px;
}

.page-up a {
	display: inline-block;
	font-size: 36px;
	color: #ffffff;
	height: 50px;
	width: 50px;
	background: rgb(236, 2, 2);
	line-height: 53px;
	text-align: center;
	border-radius: 50%;
}

.page-up a span {
	position: relative;
	top: 2px;
	left: -1px;
}

.footer__nav {
	text-align: center;
}

.footer__nav ul li {
	list-style: none;
	display: inline-block;
	position: relative;
	margin-right: 40px;
}

.footer__nav ul li:last-child {
	margin-right: 0;
}

.footer__nav ul li a {
	font-size: 15px;
	color: #000000;
	display: block;
	font-weight: 700;
}

.footer__copyright__text {
	color: #000000;
	margin-bottom: 0;
	text-align: right;
}

.footer__copyright__text a {
	color: red;
}

</style>