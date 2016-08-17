---
layout: page
permalink: /contato/
---
<div id="wrapper">
                <!--=============== Conten holder  ===============-->
                <div class="content-holder elem scale-bg2 transition3">
                    <!--  Page title    -->
                    <div class="fixed-title"><span>Contato</span></div>
                    <!--  Page title end   -->
                    <!--  Page navigation   -->
                    <div class="scroll-page-nav cdc" style="margin-top: -30px;">
                        <ul>
                            <li><a href="#sec1" class="act-link"></a></li>
                            <li><a href="#sec2"></a></li>
                            <li><a href="#sec3"></a></li>
                        </ul>
                    </div>
                    <!--  Page navigation  end -->                
                    <div class="content full-height">
                        <!--  Page title section   -->
                        <section class="parallax-section">
                            <div class="overlay"></div>
                            <div class="bg skrollable skrollable-between" style="transform: translateY(-69.8039px); background-image: url(&quot;/assets/images/bg/59.jpg&quot;);" data-top-bottom="transform: translateY(200px);" data-bottom-top="transform: translateY(-200px);"></div>
                            <div class="container">
                                <h2>Contato</h2>
                                <div class="separator"></div>
                            </div>
                            <a class="custom-scroll-link sect-scroll" href="#sec1"><i class="fa fa-angle-double-down"></i></a>
                        </section>
                        <!--  Page title section end  -->
                        <!--  Section contact info   --> 
                        <section class="section-columns" id="sec1">
                            <div class="section-columns-img">
                                <div class="bg" style="background-image:url(/assets/images/bg/22.jpg)"></div>
                            </div>
                            <div class="section-columns-text">
                                <div class="custom-inner">
                                    <div class="container">
                                        <h2>Entre em contato</h2>
                                        <div class="separator"></div>
                                        <div class="clearfix"></div>
                                        <h3 class="subtitle">PERGUNTAR O QUE COLOCAR.....</h3>
                                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                                        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                                        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                                        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                                        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                                        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
                                        <ul class="contact-list no-dec">
                                            <li><span>Endereço : </span><a>Rua Tirana n° 45 </a></li>
                                            <li><span>Telefone : </span><a>+11 2116-4223</a></li>
                                            <li><span>Celular : </span><a>+11 99243-4409</a></li>
                                            <li><span>E-mail : </span><a href="mailto:rerproducoes@hotmail.com">rerproducoes@hotmail.com</a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </section>
                        <!--  Section contact info end   -->
                        <!--  Section social   -->
                        <!-- social end  -->
                        <!--  Section map   --> 
                        <section class="no-padding" id="sec2">
                            <div class="map-box">
                                <div class="map-holder skrollable skrollable-before" data-top-bottom="transform: translateY(300px);" data-bottom-top="transform: translateY(-300px);" style="transform: translateY(-300px);">
                                  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3657.0771479507466!2d-46.54863948539666!3d-23.565668684680748!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5dcfe78378e3%3A0xc51ba394217707eb!2sR.+Tirana%2C+45+-+Vila+Formosa%2C+S%C3%A3o+Paulo+-+SP%2C+03359-110!5e0!3m2!1spt-BR!2sbr!4v1465859915057" width="100%" height="100%" frameborder="0" style="border:0" allowfullscreen></iframe>
                                </div>
                            </div>
                        </section>
                        <!--  Section map end  --> 
                        <!--  Section contact form  -->
                        <section class="flat-form" id="sec3">
                            <div class="container">
                                <h2>Contato</h2>
                                <div class="separator-image"><img src="/assets/images/separator2.png" alt=""></div>
                                <div id="contact-form">
                                    <div id="message"></div>
                                    <form method="post" action="php/contact.php" name="contactform" id="contactform">
                                        <input name="name" type="text" id="name" class="inputForm2" onclick="this.select()" value="Nome">
                                        <input name="email" type="text" id="email" onclick="this.select()" value="E-mail">  
                                        <input name="telefone" type="text" id="telefone" onclick="this.select()" value="Telefone" min="1" max="11">            
                                        <textarea name="comments" id="comments" onclick="this.select()">Menssagem</textarea>            										           											
                                        <input type="submit" class="send_message transition" id="submit" value="Enviar">
                                    </form>
                                </div>
                            </div>
                        </section>
                        <!--  Section contact form end  -->
                    </div>
                    <!-- Content end  -->  
                    <!-- Share container  -->    
                <div class="share-container  isShare" data-share="['facebook','googleplus','twitter','linkedin']"></div></div>
                <!-- content holder end -->
            </div>
            <!-- wrapper end -->
            <div class="left-decor"></div>
            <div class="right-decor"></div>

<script type="text/javascript">
  $('#map *').bind('mousewheel', function(){
    return false;
});
</script>