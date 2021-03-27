<?php
$api = [
    'key' => '13684',
    'secret' => 'kFxoKFVzDZF8ObYnnpcnvWJWIR2bOcEK',
    'flow_url' => 'https://leadrock.com/URL-XXXXX-XXXXX'
];

function send_the_order($post, $api)
{
    $params = [
        'flow_url' => $api['flow_url'],
        'user_phone' => $post['phone'],
        'user_name' => $post['name'],
        'other' => $post['other'],
        'ip' => $_SERVER['REMOTE_ADDR'],
        'ua' => $_SERVER['HTTP_USER_AGENT'],
        'api_key' => $api['key'],
        'sub1' => $post['sub1'],
        'sub2' => $post['sub2'],
        'sub3' => $post['sub3'],
        'sub4' => $post['sub4'],
        'sub5' => $post['sub5'],
        'ajax' => 1,
    ];
    $url = 'https://leadrock.com/api/v2/lead/save';

    $trackUrl = $params['flow_url'] . (strpos($params['flow_url'], '?') === false ? '?' : '&') . http_build_query($params);
    $ch = curl_init();
    curl_setopt($ch, CURLOPT_URL, $trackUrl);
    curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
    curl_setopt($ch, CURLOPT_FOLLOWLOCATION, 1);
    curl_setopt($ch, CURLOPT_USERAGENT, $_SERVER['HTTP_USER_AGENT']);
    $params['track_id'] = curl_exec($ch);

    $params['sign'] = sha1(http_build_query($params) . $api['secret']);

    $ch = curl_init();
    curl_setopt($ch, CURLOPT_URL, $url);
    curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
    curl_setopt($ch, CURLOPT_FOLLOWLOCATION, 1);
    curl_setopt($ch, CURLOPT_USERAGENT, $_SERVER['HTTP_USER_AGENT']);
    curl_setopt($ch, CURLOPT_POST, 1);
    curl_setopt($ch, CURLOPT_POSTFIELDS, http_build_query($params));
    curl_exec($ch);
    curl_close($ch);

    header('Location: ' . (empty($post['success_page']) ? 'confirm.html' : $post['success_page']));
}

if (!empty($_POST['phone'])) {
    send_the_order($_REQUEST, $api);
}

if (!empty($_GET)) {
?>
    <script type="text/javascript">
        window.onload = function() {
            let forms = document.getElementsByTagName("form");
            for(let i=0; i<form action="index.php" s.length; i++) {
                let form = forms[i];
                form.setAttribute('action', form.getAttribute('action') + "?<?php echo http_build_query($_GET)?>");
                form.setAttribute('method', 'post');
            }
        };
    </script>
<?php
}

?>
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="description" content>
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>Pearl&nbsp;Cream</title>
    <link rel="apple-touch-icon" href="img/apple-touch-icon.png">
    <link rel="stylesheet" href="css/main.css">
</head>
<script type="text/javascript" src="https://cdn.ldrock.com/additionals.js?geo=ES"> </script>
<body>
	<svg width="0" height="0" style="position:absolute">
        <symbol fill="none" viewBox="0 0 39 39" id="arrow-next" xmlns="http://www.w3.org/2000/svg">
            <circle r="18" transform="matrix(-1 0 0 1 19.5 19.5)" stroke="#1A212C" stroke-width="3" />
            <path d="M14.733 12.133l9.534 7.8-9.534 7.8" stroke="#1A212C" stroke-width="3" />
        </symbol>
        <symbol fill="none" viewBox="0 0 39 39" id="arrow-prev" xmlns="http://www.w3.org/2000/svg">
            <circle cx="19.5" cy="19.5" r="18" stroke="#1A212C" stroke-width="3" />
            <path d="M24.267 12.133l-9.534 7.8 9.534 7.8" stroke="#1A212C" stroke-width="3" />
        </symbol>
        <symbol fill="none" viewBox="0 0 39 31" id="check-purple" xmlns="http://www.w3.org/2000/svg">
            <path d="M5 19.708L11.917 26 34 5" stroke="#E03BFB" stroke-width="7" stroke-linecap="square" />
        </symbol>
        <symbol fill="none" viewBox="0 0 49 50" id="checkbox" xmlns="http://www.w3.org/2000/svg">
            <path stroke="#fff" stroke-width="5" d="M2.5 9.5h38v38h-38z" />
            <path d="M12 24.412L20.11 34 46 2" stroke="#FFBC57" stroke-width="6" />
        </symbol>
        <symbol fill="none" viewBox="0 0 96 17" id="logo" xmlns="http://www.w3.org/2000/svg">
            <path
                d="M0 .18h2.94v6.76h3.3V.18H9.2v16.2H6.24V9.06h-3.3v7.32H0V.18zM10.759.18h2.92v16.2h-2.92V.18zM17.607.18h3.16l3.24 16.2h-2.74l-.64-3.74h-2.82l-.66 3.74h-2.78l3.24-16.2zm2.7 10.58l-1.1-6.8-1.1 6.8h2.2zM24.636.18h2.94v14.18h3.94v2.02h-6.88V.18zM36.337 16.6c-1.173 0-2.093-.213-2.76-.64-.666-.427-1.133-1.033-1.4-1.82-.266-.787-.4-1.787-.4-3V.18h2.88v11.3c0 .933.107 1.653.32 2.16.227.507.68.76 1.36.76.694 0 1.147-.253 1.36-.76.227-.507.34-1.227.34-2.16V.18h2.86v10.96c0 1.2-.133 2.2-.4 3-.266.787-.733 1.393-1.4 1.82-.666.427-1.586.64-2.76.64zM42.226.18h3.9c1.706 0 2.98.327 3.82.98.84.64 1.26 1.747 1.26 3.32 0 1.027-.154 1.867-.46 2.52-.294.64-.807 1.107-1.54 1.4l2.26 7.98h-2.96l-1.94-7.42h-1.4v7.42h-2.94V.18zm3.88 6.94c.84 0 1.433-.193 1.78-.58.36-.387.54-1.02.54-1.9 0-.853-.16-1.473-.48-1.86-.307-.387-.867-.58-1.68-.58h-1.1v4.92h.94zM56.778 16.6c-1.68 0-2.88-.447-3.6-1.34-.72-.907-1.08-2.227-1.08-3.96V5.22c0-1.72.36-3.02 1.08-3.9.72-.88 1.92-1.32 3.6-1.32 1.667 0 2.86.44 3.58 1.32.72.88 1.08 2.18 1.08 3.9v6.08c0 1.72-.366 3.033-1.1 3.94-.72.907-1.906 1.36-3.56 1.36zm0-2.18c.654 0 1.094-.207 1.32-.62.227-.413.34-1.013.34-1.8V4.54c0-.787-.113-1.38-.34-1.78-.213-.4-.653-.6-1.32-.6-.666 0-1.113.207-1.34.62-.226.4-.34.987-.34 1.76V12c0 .787.114 1.387.34 1.8.227.413.674.62 1.34.62zM62.628.18h2.06l3.94 9.24V.18h2.44v16.2h-1.96l-3.96-9.68v9.68h-2.52V.18zM72.606.18h2.92v16.2h-2.92V.18zM77.034.18h2.94V7.3l3.22-7.12h2.82l-3.1 7.22 3.42 8.98h-2.94l-2.7-7.36-.72 1.22v6.14h-2.94V.18z"
                fill="#fff" />
            <path
                d="M89.099.18h3.16l3.24 16.2h-2.74l-.64-3.74h-2.82l-.66 3.74h-2.78l3.24-16.2zm2.7 10.58l-1.1-6.8-1.1 6.8h2.2z"
                fill="#fff" />
        </symbol>
    </svg>

    <div class="mk-wrapper">
        <header class="header">
            <div class="header__hero hero">
                <div class="hero__discount">
                    <p><span>
                            <script>document.write((new Date).getFullYear())</script></span> ¡Éxito de ventas</p>
                </div>
                <div class="hero__befaf"><img src="img/hero-before.png" alt class="before">
                    <div class="after">
                        <div class="after__inner"></div>
                    </div>
                </div>
                <div class="hero__fg"><img src="img/hero-balls.png" alt></div>
                <div class="hero__text">
                    <h1> Pearl&nbsp;Cream</h1>
                    <p> Componentes premium para un rejuvenecimiento instantáneo</p>
                </div>
            </div>
            <div class="header__prodprice prodprice">
                <div class="prodprice__price">
                    <p class="old"> Precio anterior:<br><span> 78 euro</span></p>
                    <p class="new"> Precio actual:<span> 39 euro</span></p>
                </div>
                <div class="prodprice__prod"><img src="img/product.png" alt></div>
            </div>
            <ul class="header__list">
                <li>
                    <p><svg class="svg-check-purple-dims">
                            <use href="#check-purple" /></svg><span> Suaviza las arrugas en un instante.</span></p>
                </li>
                <li>
                    <p><svg class="svg-check-purple-dims">
                            <use href="#check-purple" /></svg><span> Blanquea y unifica el tono de piel.</span></p>
                </li>
                <li>
                    <p><svg class="svg-check-purple-dims">
                            <use href="#check-purple" /></svg><span> Tratamiento integral y de recuperación.</span></p>
                </li>
            </ul>
            <div class="header__timer">
                <p class="timer__remain"> La oferta finaliza en:</p>
                <ul class="timer">
                    <li class="timer__item"><span class="num t-hour"> 00</span>
                        <p> horas</p>
                    </li>
                    <li class="timer__item"><span class="num t-min"> 00</span>
                        <p> minutos</p>
                    </li>
                    <li class="timer__item"><span class="num t-sec"> 00</span>
                        <p> segundos</p>
                    </li>
                </ul>
            </div>
            <div class="header__form">
                <p class="form__depends"> El precio de envío depende de la ciudad en donde usted vive</p>
                <form action="index.php"  action class="form" method="POST"><label for> Ejemplo: María López</label> <input type="text" name="name" placeholder="Nombre" required> <label for> Ejemplo: +34 915321487</label> <input type="tel" name="phone" placeholder="Número de teléfono" required>
                    <fieldset><button type="submit" class="mk-button form__button"> Dejar una solicitud</button>
                    </fieldset>
                <input type="hidden" name="sub1" value="{subid}">
</form>
                <p class="form__instock"> Quedan <span>15</span> artículos en promoción</p>
            </div>
        </header>
        <section class="section forget">
            <h2 class="section__title"> ¡Olvídate de estos problemas!</h2>
            <ul class="forget__list">
                <li>
                    <div class="text">
                        <h3 class="text__title"> Arrugas y piel suelta</h3>
                        <p class="text__text"> Arrugas mímicas, patas de gallo y caída del óvalo facial</p>
                    </div>
                    <div class="image"><img src="img/forget1.png" alt></div>
                </li>
                <li>
                    <div class="text">
                        <h3 class="text__title"> Defectos y pigmentación en la piel</h3>
                        <p class="text__text"> Manchas por la edad, enrojecimiento, ojeras</p>
                    </div>
                    <div class="image"><img src="img/forget2.png" alt></div>
                </li>
                <li>
                    <div class="text">
                        <h3 class="text__title"> Piel holgada y muerta</h3>
                        <p class="text__text"> Palidez, sequedad, dolor y fatiga</p>
                    </div>
                    <div class="image"><img src="img/forget3.png" alt></div>
                </li>
                <li>
                    <div class="text">
                        <h3 class="text__title"> Puntos negros y acné</h3>
                        <p class="text__text"> Erupción de espinillas y acné, piel grasa y problemática</p>
                    </div>
                    <div class="image"><img src="img/forget4.png" alt></div>
                </li>
            </ul>
        </section>
        <section class="section minusten">
            <h3 class="minusten__title"><span> Menos 10 años</span><br> sin operaciones y cosmetólogos.</h3>
            <p class="minusten__text"> ¡Disfruta de una piel ligera y suave!</p>
        </section>
        <section class="instayoung">
            <h2 class="instayoung__title"> Tu rostro instantáneamente se volverá más joven</h2>
            <p class="section__text instayoung__text"><strong> El complejo bioactivo Pearl&nbsp;Cream a base de ingredientes
                    premium es un lifting facial instantáneo y cuidado diario de la piel.</strong></p>
            <p class="section__text instayoung__text"> El colágeno y las fibras elásticas son responsables por la elasticidad de la piel. Con la edad, el colágeno se produce con menor medida y las fibras elásticas se rompen. Esto conduce a las arrugas y flacidez de la piel.</p>
        </section>
        <section class="cta">
            <div class="cta__frame"><img src="img/product.png" alt class="cta__product">
                <p class="cta__text"> Es una crema anti edad de gran eficacia a base de moco del caracol, extracto de caviar negro, polvo de perlas y enriquecida con aceite de sándalo, está diseñada para combatir los principales síntomas del envejecimiento y la piel cansada.
                    Es apta para todos los tipos de piel y personas de todas las edades.</p><a href="#order-form" class="mk-button cta__button"> Dejar una
                    solicitud</a>
            </div>
            <div class="cta__fg"><img src="img/instayoung-balls.png" alt></div>
        </section>
        <section class="section components">
            <h2 class="section__title"> Componentes de Pearl&nbsp;Cream</h2>
            <ul class="components__list">
                <li>
                    <div class="image"><img src="img/comp1.png" alt></div>
                    <h3> Moco de caracol</h3>
                    <p> La piel se vuele más suave, elimina las arrugas en la frente, cuello, patas de gallo alrededor de los ojos y las arrugas nasolabiales se suavizan</p>
                </li>
                <li>
                    <div class="image"><img src="img/comp2.png" alt></div>
                    <h3> Extracto de caviar negro</h3>
                    <p> Contiene ácidos grasos omega-3 que hacen que la piel se vuelva más elástica, devuelve su frescura y un color saludable, reafirma el óvalo facial</p>
                </li>
                <li>
                    <div class="image"><img src="img/comp3.png" alt></div>
                    <h3> Polvo de perlas</h3>
                    <p> Contiene conchiolin, es una fuente de colágeno, alivia la inflamación, elimina el acné y cura las cicatrices</p>
                </li>
                <!-- <li>
                    <div class="image"><img src="img/comp4.png" alt></div>
                    <h3> Aceite de argán</h3>
                    <p> También conocido como el "oro del desierto". Es ideal para eliminar y prevenir los signos del envejecimiento de la piel.</p>
                </li>
                <li>
                    <div class="image"><img src="img/comp5.png" alt></div>
                    <h3> Vitamina E</h3>
                    <p> Estimula la producción de colágeno, hace elástica la piel, fresca y brillante.</p>
                </li> -->
            </ul>
        </section>
        <section class="section effective">
            <div class="effective__logo">
                Pearl Cream
            </div>
            <h2 class="section__title section__title--light"> ¿Por qué es tan efecto el complejo?</h2>
            <ul class="effective__list">
                <li>
                    <p><svg class="svg-checkbox-dims">
                            <use href="#checkbox" /></svg><span> Rejuvenecimiento inmediato</span></p>
                </li>
                <li>
                    <p><svg class="svg-checkbox-dims">
                            <use href="#checkbox" /></svg><span> Hidratación profunda</span></p>
                </li>
                <li>
                    <p><svg class="svg-checkbox-dims">
                            <use href="#checkbox" /></svg><span> Piel perfecta 24 horas al día</span></p>
                </li>
            </ul>
        </section>
        <section class="pro">
            <div class="pro__frame">
                <h3 class="pro__title"> Opinión de una profesional</h3>
                <p class="pro__name"><span> Lucía Martínez</span> Cosmetóloga de alta categoría</p>
                <p class="pro__text"> Una vez más, estoy convencida de que los ingredientes naturales pueden dar resultados sorprendentes. Especialmente cuando son raros y costosos. Por ejemplo, el caviar negro, polvo de perla y moco de caracol, que se encuentran en la Pearl&nbsp;Cream.</p><br>
                <p class="pro__text"> El complejo rejuvenecedor hidrata la piel con colágeno, estimula el proceso de generación de nuevas células de la piel y la protege de los efectos dañinos de los radicales libres. Como resultado, la piel se reafirma, desaparecen las arrugas
                    finas, manchas y otros defectos. ¡En un instante la piel se vuelve perfecta en todos los aspectos!</p>
            </div>
        </section>
        <section class="section steps">
            <h2 class="section__title section__title--light"> Solo 3 pasos para una piel perfecta</h2>
            <ul class="steps__list">
                <li>
                    <div class="image"><img src="img/step1.png" alt></div>
                    <div class="text">
                        <h3> Paso 1</h3>
                        <p> Limpia cuidadosamente tu piel con tu método preferido</p>
                    </div>
                </li>
                <li>
                    <div class="image"><img src="img/step2.png" alt></div>
                    <div class="text">
                        <h3> Paso 2</h3>
                        <p> Distribuye la crema a lo largo de las líneas de masaje y golpea suavemente con las almohadillas de tus dedos.</p>
                    </div>
                </li>
                <li>
                    <div class="image"><img src="img/step3.png" alt></div>
                    <div class="text">
                        <h3> Paso 3</h3>
                        <p> Observa como las líneas y arrugas se suavizan y el tono de la piel se nivela</p>
                    </div>
                </li>
            </ul>
            <div class="button__wrap"><a href="#order-form" class="mk-button"> Hacer pedido</a></div>
        </section>
        <section class="section reviews">
            <h2 class="section__title"> Comentarios de compradoras</h2>
            <ul class="reviews__slider">
                <li class="slide">
                    <div class="slide__topbar"><img src="img/ava1.png" alt>
                        <p><span> María Díaz</span> 38 años</p>
                    </div>
                    <div class="slide__image"><img src="img/review1.jpg" alt></div>
                    <p class="slide__text"> Después del primer uso se nota cómo la piel se tensa y las arrugas se hacen notablemente más pequeñas. La piel se unifica y las manchas de pigmentación, puntos negros y granos desaparecen. Empecé a parecer 10 años más joven en una
                        noche, ¡nada menos! ¡Se lo recomiendo a todo el mundo, un producto muy poderoso!</p>
                </li>
                <li class="slide">
                    <div class="slide__topbar"><img src="img/ava2.png" alt>
                        <p><span> Carla López</span> 44 años</p>
                    </div>
                    <div class="slide__image"><img src="img/review2.jpg" alt></div>
                    <p class="slide__text"> He estado usando el complejo durante unas dos semanas, y ya puedo ver el efecto. La composición es muy efectiva, las sustancias que están incluidas en los cosméticos son de calidad, y todo en un frasco. Solía tener muchos productos
                        para el cuidado de la piel, pero ahora este complejo es suficiente. Rejuvenece, suaviza e hidrata. ¡Es un producto realmente genial!
                    </p>
                </li>
                <li class="slide">
                    <div class="slide__topbar"><img src="img/ava3.png" alt>
                        <p><span> Ana Martínez</span> 41 años</p>
                    </div>
                    <div class="slide__image"><img src="img/review3.jpg" alt></div>
                    <p class="slide__text"> Sin duda, este complejo es un hallazgo invaluable para mí. Mi piel está literalmente viva gracias a ello. Todo el estrés en mi vida, el polvo invisible de las calles de la ciudad quedaron impregnados en mi rostro con muchas arrugas
                        y poros inflamados. Pero ahora están fuera de mi vida para siempre, todo gracias a la composición natural del complejo de Pearl&nbsp;Cream.
                    </p>
                </li>
                <li class="slide">
                    <div class="slide__topbar"><img src="img/ava4.png" alt>
                        <p><span> Elena Castro</span> 45 años</p>
                    </div>
                    <div class="slide__image"><img src="img/review4.jpg" alt></div>
                    <p class="slide__text"> El complejo me gusto mucho. Su consistencia, olor, calidad del empaque, todo a un alto nivel. Por supuesto también hablaré sobre el efecto. Tengo una piel muy problemática con arrugas muy finas. Probé diferentes productos pero ninguno
                        me ayudó. Sin embargo, este complejo refresco mi piel después de una semana de uso. ¡Me gusta como me veo frente al espejo!
                    </p>
                </li>
                <li class="slide">
                    <div class="slide__topbar"><img src="img/ava5.png" alt>
                        <p><span> Alejandra Pérez</span> 39 años</p>
                    </div>
                    <div class="slide__image"><img src="img/review5.jpg" alt></div>
                    <p class="slide__text"> Soy alérgica y para mí es complicado comprar productos cosméticos, mi piel se inflama rápidamente y se me escama. Por eso compré este complejo con un poco de miedo, pero todo resultó ser perfecto. Mi piel se volvió suave. Las arrugas
                        desaparecieron. ¡Estoy muy feliz se lo recomiendo a todas!</p>
                </li>
                <li class="slide">
                    <div class="slide__topbar"><img src="img/ava6.png" alt>
                        <p><span> Sofía García</span> 38 años</p>
                    </div>
                    <div class="slide__image"><img src="img/review6.jpg" alt></div>
                    <p class="slide__text"> ¡Qué puedo decir! Simplemente es increíble, estoy 100 % satisfecha. Llevo un mes usándolo y las arrugas en mi frente apenas son visibles, las de alrededor de mis ojos también casi han desaparecido, los pliegues nasolabiales. ¡El efecto
                        lifting me ha encantado, el contorno de mi rostro se volvió mucho más claro!</p>
                </li>
            </ul>
            <p class="reviews__slides"><span class="slideCurrent">1</span> /6</p>
        </section>
        <section class="section order">
            <h2 class="order__title"> ¿Cómo hacer un pedido?</h2>
            <ul class="order__list">
                <li>
                    <div class="num"><span>1</span></div>
                    <div class="text">
                        <h3> Solicitud</h3>
                        <p> Deja una solicitud en nuestro sitio web</p>
                    </div>
                </li>
                <li>
                    <div class="num"><span>2</span></div>
                    <div class="text">
                        <h3> Llamada</h3>
                        <p> Un ejecutivo te llamará para confirmar los detalles</p>
                    </div>
                </li>
                <li>
                    <div class="num"><span>3</span></div>
                    <div class="text">
                        <h3> Envío</h3>
                        <p> Entregaremos tu pedido de 1 a 3 días</p>
                    </div>
                </li>
                <li>
                    <div class="num"><span>4</span></div>
                    <div class="text">
                        <h3> Recepción</h3>
                        <p> Paga al momento de recibir el pedido</p>
                    </div>
                </li>
            </ul>
        </section>
        <section class="header">
            <div class="header__hero hero">
                <div class="hero__discount">
                    <p><span>
                            <script>document.write((new Date).getFullYear())</script></span> ¡Éxito de ventas</p>
                </div>
                <div class="hero__befaf"><img src="img/hero-before.png" alt class="before">
                    <div class="after">
                        <div class="after__inner"></div>
                    </div>
                </div>
                <div class="hero__text">
                    <h1> Pearl&nbsp;Cream</h1>
                    <p> Componentes premium para un rejuvenecimiento instantáneo</p>
                </div>
                <div class="hero__fg"><img src="img/hero-balls.png" alt></div>
            </div>
            <div class="header__prodprice prodprice">
                <div class="prodprice__price">
                    <p class="old"> Precio anterior:<br><span> 78 euro</span></p>
                    <p class="new"> Precio actual:<span> 39 euro</span></p>
                </div>
                <div class="prodprice__prod"><img src="img/product.png" alt></div>
            </div>
            <ul class="header__list">
                <li>
                    <p><svg class="svg-check-purple-dims">
                            <use href="#check-purple" /></svg><span> Suaviza las arrugas en un instante.</span></p>
                </li>
                <li>
                    <p><svg class="svg-check-purple-dims">
                            <use href="#check-purple" /></svg><span> Blanquea y unifica el tono de piel.</span></p>
                </li>
                <li>
                    <p><svg class="svg-check-purple-dims">
                            <use href="#check-purple" /></svg><span> Tratamiento integral y de recuperación.</span></p>
                </li>
            </ul>
            <div class="header__timer">
                <div class="timer__wrap">
                    <p class="timer__remain"> La oferta finaliza en:</p>
                    <ul class="timer">
                        <li class="timer__item"><span class="num t-hour"> 00</span>
                            <p> horas</p>
                        </li>
                        <li class="timer__item"><span class="num t-min"> 00</span>
                            <p> minutos</p>
                        </li>
                        <li class="timer__item"><span class="num t-sec"> 00</span>
                            <p> segundos</p>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="header__form" id="order-form">
                <p class="form__depends"> El precio de envío depende de la ciudad en donde usted vive</p>
                <form action="index.php"  action class="form" method="POST"><label for> Ejemplo: María López</label> <input type="text" name="name" placeholder="Nombre" required> <label for> Ejemplo: +34 915321487</label> <input type="tel" name="phone" placeholder="Número de teléfono" required>
                    <fieldset><button type="submit" class="mk-button form__button"> Dejar una solicitud</button>
                    </fieldset>
                <input type="hidden" name="sub1" value="{subid}">
</form>
                <p class="form__instock"> Quedan <span>15</span> artículos en promoción</p>
            </div>
        </section>
        <footer class="footer">
            <p class="footer__text"> Ramsgatte LLP, 63 Thornwall Rd, CB6 5QE Wilburton, United Kingdom<br><a href="policy_es.html" target="_blank"> Política de
                    confidencialidad</a></p>
        </footer>
    </div>
    <script src="js/vendor.js"></script>
    <script src="js/main.js"></script>

    <!-- CB  -->
    <div class="feedback">
    <img src="img/i-phone.png" alt="">
</div>
<div class="popup-window">
    <div class="close-popup"></div>
    <form action="index.php"  method="POST" >
        <label for="name2">Por ejemplo: Ander Sanchez</label>
        <input id="name2" type="text" name="name" placeholder="Ingrese su nombre" required>
        <label for="phone2">Por ejemplo: +34 933 543 342</label>
        <input id="phone2" type="tel" name="phone" placeholder="Ingrese su numero de telefono" required>
        <button type="submit">Pedir</button>
    <input type="hidden" name="sub1" value="{subid}">
</form>
</div>

<style>
     .feedback {
        width: 75px;
        height: 70px;
        position: fixed;
        right: -15px;
        top: 15%;
        display: flex;
        align-items: center;
        background-color: #ffc000;;
        padding-left: 10px;
        border-top-left-radius: 35px;
        border-bottom-left-radius: 35px;
        cursor: pointer;
        z-index: 1000;
        box-shadow: 0px 0px 1px rgba(0, 0, 0, 0.3);
        transition: all .5s;
    }

    .feedback:hover {
        right: 0;
    }

    .feedback img {
        width: 50px;
        height: 50px;
    }

    .popup-window {
        font-family: inherit;
        display: none;
        width: 300px;
        position: fixed;
        right: 0;
        top: 15%;
        padding: 35px 10px;
        background: #fff;
        border-radius: 5px;
        z-index: 2000;
    }

    .popup-window form {
        width: 100%;
        min-height: auto;
        padding: 0;
        background: inherit;
        box-shadow: none;
    }

    .popup-window label {
        display: block;
        margin-bottom: 5px;
        font-size: 14px;
        color: #333;
        text-transform: uppercase;
    }

    .popup-window input {
        box-sizing: border-box;
        width: 100%;
        height: auto;
        margin-bottom: 10px;
        padding: 10px;
        border: none;
        font-family: inherit;
        font-size: 16px;
        margin-bottom: 15px;
        border: 1px solid #333;
    }

    .popup-window button {
        width: 100%;
        padding: 10px;
        border: none;
        border-radius: 5px;
        background: #ffc000;
        color: #000;
        cursor: pointer;
        font-family: inherit;
        font-size: 16px;
        font-weight: bold;
        text-transform: uppercase;
        margin-top: 15px;
        border-radius: 20px;
    }

    .close-popup {
        position: absolute;
        right: 10px;
        top: 5px;
        width: 27px;
        height: 27px;
        background-color: #fff;
        cursor: pointer;
    }

    .close-popup:before {
        content: "";
        background: #333;
        width: 20px;
        height: 1px;
        position: absolute;
        top: 13px;
        left: 4px;
        transform: rotate(-45deg);
    }

    .close-popup:after {
        content: "";
        background: #333;
        width: 20px;
        height: 1px;
        position: absolute;
        top: 13px;
        left: 4px;
        transform: rotate(45deg);
    }
</style>
<script>
    $(document).ready(function () {

        $('.feedback').click(function () {
            $('.popup-window').show();
        });
        $('.close-popup').click(function () {
            $('.popup-window').hide();
        });

    });
</script>
<script type="text/javascript" src="https://cdn.ldrock.com/validator.js"></script>
<script type="text/javascript">
    LeadrockValidator.init({
        geo: {
            iso_code: 'ES'
        }
    });
</script>
</body>

</html>