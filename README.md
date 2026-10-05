# Declara-o_Paula_Mayron
Site hospedado da minha declaração para Paula Massetti.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Paula — de Mayron</title>
<style>
       /* Todo o CSS do site fica aqui */
</style>
</head>
<body>
<!-- CAPA -->
<section class="hero">
<div class="hero-inner">
<div>
<div class="kicker">
                   Uma pequena declaração para você
</div>
<h1>
                   Paula<br>
<span>&amp;</span> Mayron
</h1>
<h2>
                   Entre tantos caminhos, encontros e momentos,
                   a melhor parte da minha história é poder viver
                   tudo isso ao seu lado.
</h2>
<div class="signature">
                   Com amor, Mayron ♡
</div>
</div>
<div class="hero-photo">
<img src="SUA_FOTO_AQUI">
</div>
</div>
</section>

<!-- GALERIA DE MOMENTOS -->
<section class="section">
<div class="container center">
<div class="eyebrow">
               Nossa história
</div>
<h2>
               Alguns dos meus momentos favoritos com você.
</h2>
<p class="lead">
               Cada fotografia guarda uma pequena parte da nossa história.
</p>
<div class="heart-line">
               ♥
</div>
</div>

<div class="container gallery">
<div class="memory">
<div class="photo-wrap">
<img src="FOTO_1">
</div>
<div class="memory-copy">
<div class="number">01</div>
<h3>Você e eu.</h3>
<p>
                       Mais um daqueles momentos simples
                       que se tornam especiais porque são
                       vividos ao seu lado.
</p>
</div>
</div>

<div class="memory">
<div class="photo-wrap">
<img src="FOTO_2">
</div>
<div class="memory-copy">
<div class="number">02</div>
<h3>
                       Nosso lugar favorito.
</h3>
<p>
                       Porque no fim das contas,
                       o melhor lugar continua sendo
                       onde estamos juntos.
</p>
</div>
</div>

<!-- Continue adicionando as outras fotos -->
</div>
</section>

<!-- HOMENAGEM À MÃE DA PAULA -->
<section class="tribute">
<div class="tribute-inner">
<div class="tribute-photo">
<img src="FOTO_DA_PAULA_COM_A_MAE">
</div>

<div class="tribute-copy">
<div class="eyebrow">
                   Uma lembrança que merece
                   um lugar especial
</div>
<h2>
                   Para você e para ela.
</h2>
<p>
                   Paula, entre todas as lembranças que
                   guardamos, existe uma que tem um
                   significado diferente. Essa foi a única
                   foto que consegui tirar com a sua mãe
                   em vida.
</p>
<p>
                   Eu sei que nenhuma fotografia é capaz
                   de substituir a presença de alguém tão
                   importante. Mas, de alguma forma,
                   gosto de pensar que essa imagem guarda
                   um pedacinho daquele momento, da família
                   reunida e de uma pessoa que fez parte
                   da sua história — e, por isso, também
                   passou a fazer parte da minha.
</p>
<p>
                   Tenho carinho e respeito por essa
                   lembrança. E quero que você saiba que,
                   sempre que eu olhar para essa foto,
                   vou lembrar não apenas da saudade,
                   mas também da importância que ela teve
                   e sempre terá na sua vida.
</p>
<p class="tribute-sign">
                   Que essa lembrança permaneça para sempre. ❤️
</p>
</div>
</div>
</section>

<!-- CARTA -->
<section class="letter">
<div class="letter-card">
<div class="eyebrow">
               Depois de tudo isso,
               ainda tenho uma coisa para te dizer
</div>
<h2 class="big">
               Paula, eu escolheria você de novo.
</h2>
<p>
               Eu poderia tentar escrever um texto perfeito,
               mas talvez o mais bonito seja simplesmente
               dizer a verdade.
</p>
<p>
               Eu amo o jeito como você faz os dias comuns
               parecerem especiais.
</p>
<p>
               Amo nossas risadas, nossos passeios,
               nossas viagens, nossas conversas e até
               aquelas pequenas coisas que provavelmente
               ninguém mais entenderia.
</p>
<p>
               Gosto de olhar para trás e perceber quantas
               lembranças já construímos juntos.
               E gosto ainda mais de olhar para frente
               e imaginar todas as outras que ainda estão
               esperando por nós.
</p>
<p>
               Obrigado por ser você.
               Por dividir sua vida comigo e por me permitir
               conhecer seus sonhos, suas manias, seus
               sorrisos e cada uma das suas versões.
</p>
<p>
               Se algum dia eu esquecer de dizer,
               espero que essas fotos lembrem por mim:
<strong>
                   você é muito especial para mim.
</strong>
</p>
<p style="text-align:right">
               Com todo meu amor,<br>
<strong>Mayron</strong> ❤️
</p>
</div>
</section>

<!-- FINAL -->
<section class="ending">
<div>
<div class="final-heart">
               ♥
</div>
<div class="eyebrow">
               E essa história continua...
</div>
<h2>
               Eu &amp; você.
</h2>
<p>
               Que a gente continue colecionando lugares,
               viagens, abraços, fotos e motivos para
               sorrir juntos.
</p>
<p>
               Paula, eu te amo.
</p>
</div>
</section>

<footer>
       Feito por Mayron, para Paula — com amor.
</footer>

<script>
       const obs = new IntersectionObserver((entries) => {
           entries.forEach(e => {
               if (e.isIntersecting) {
                   e.target.classList.add('show');
                   obs.unobserve(e.target);
               }
           });
       }, {
           threshold: .12
       });

       document
           .querySelectorAll('.reveal')
           .forEach(el => obs.observe(el));
</script>
</body>
</html>
