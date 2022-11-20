<template lang="">
    <!-- Login Section Begin -->
    <section class="login spad">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <div class="login__form">
                        <h3>Login</h3>
                        <form action="#">
                            <div class="input__item">
                                <input type="text" placeholder="Email address">
                                <span class="icon_mail"></span>
                            </div>
                            <div class="input__item">
                                <input type="text" placeholder="Password">
                                <span class="icon_lock"></span>
                            </div>
                            <button type="submit" class="site-btn">Login Now</button>
                            <a href="#" class="forget_pass">Esqueceu sua senha?</a>
                        </form>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="login__register">
                        <h3>Voce não tem conta?</h3>
                        <a href="#" class="primary-btn"> Registrar agora</a>
                    </div>
                </div>
            </div>
            <div class="login__social">
                <div class="row d-flex justify-content-center">
                    <div class="col-lg-6">
                        <div class="login__social__links">
                            <span>ou</span>
                            <ul>
                                <li><a href="#" class="facebook"><i class="fa-brands fa-facebook"></i> Login pelo
                                Facebook</a></li>
                                <li><a href="#" class="google"><i class="fa-brands fa-google"></i> Login pelo Google</a></li>
                                <li><a href="#" class="twitter"><i class="fa-brands fa-twitter"></i> Login pelo Twitter</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>
a {
   text-decoration: none; 
   color: white;
}
.site-btn{
    color: white;
    background-color: red;
}

.forget_pass{
    margin-top: 40px;
    display: flex;
    align-items: center;
    text-align: center;
    justify-content: center;
    justify-items: center;
}

.site-btn {
    display: flex;
    align-items: center;
    text-align: center;
    justify-content: center;
    justify-items: center;
}


</style>