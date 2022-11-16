<template lang="">
    <!-- Page Preloder -->
    <div id="preloder">
        <div class="loader"></div>
    </div>
</template>

<script>
export default {
    
}
</script>
<style>
#preloder {
	position: fixed;
	width: 100%;
	height: 100%;
	top: 0;
	left: 0;
	z-index: 999999;
	background: #000;
}

.loader {
	width: 40px;
	height: 40px;
	position: absolute;
	top: 50%;
	left: 50%;
	margin-top: -13px;
	margin-left: -13px;
	border-radius: 60px;
	animation: loader 0.8s linear infinite;
	-webkit-animation: loader 0.8s linear infinite;
}

@keyframes loader {
	0% {
		-webkit-transform: rotate(0deg);
		transform: rotate(0deg);
		border: 4px solid #f44336;
		border-left-color: transparent;
	}
	50% {
		-webkit-transform: rotate(180deg);
		transform: rotate(180deg);
		border: 4px solid #673ab7;
		border-left-color: transparent;
	}
	100% {
		-webkit-transform: rotate(360deg);
		transform: rotate(360deg);
		border: 4px solid #f44336;
		border-left-color: transparent;
	}
}

@-webkit-keyframes loader {
	0% {
		-webkit-transform: rotate(0deg);
		border: 4px solid #f44336;
		border-left-color: transparent;
	}
	50% {
		-webkit-transform: rotate(180deg);
		border: 4px solid #673ab7;
		border-left-color: transparent;
	}
	100% {
		-webkit-transform: rotate(360deg);
		border: 4px solid #f44336;
		border-left-color: transparent;
	}
}

.spacial-controls {
	position: fixed;
	width: 111px;
	height: 91px;
	top: 0;
	right: 0;
	z-index: 999;
}

.spacial-controls .search-switch {
	display: block;
	height: 100%;
	padding-top: 30px;
	background: #323232;
	text-align: center;
	cursor: pointer;
}

.search-model {
	display: none;
	position: fixed;
	width: 100%;
	height: 100%;
	left: 0;
	top: 0;
	background: #000;
	z-index: 99999;
}

.search-model-form {
	padding: 0 15px;
}

.search-model-form input {
	width: 500px;
	font-size: 40px;
	border: none;
	border-bottom: 2px solid #333;
	background: 0 0;
	color: #999;
}

.search-close-switch {
	position: absolute;
	width: 50px;
	height: 50px;
	background: #333;
	color: #fff;
	text-align: center;
	border-radius: 50%;
	font-size: 28px;
	line-height: 28px;
	top: 30px;
	cursor: pointer;
	display: -webkit-box;
	display: -ms-flexbox;
	display: flex;
	-webkit-box-align: center;
	-ms-flex-align: center;
	align-items: center;
	-webkit-box-pack: center;
	-ms-flex-pack: center;
	justify-content: center;
}
</style>