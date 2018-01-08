layout: simple
extends: default.liquid
title: 'Startseite'
---

<div class="bg-primary">
  <div class="container">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img class="d-block w-100" src="/assets/images/kampagnen/preisschild.jpg" alt="Ein Mann zückt ein Umschlag aus der Innentasche seines Anzugs.">
            <div class="carousel-caption d-none p-3 mb-5 bg-dark text-light d-md-block text-left" style="right: 55%;">
              <h4 class="mb-3">Neue Kampagne: Demokratie darf kein Preisschild haben</h4>
              <p>Die Macht der Konzerne wird immer größer. Das BMDT startet deshalb die Kampagne “Demokratie darf kein Preisschild haben”. Wir machen uns stark für neue Formen der Mitbestimmung. Denn Demokratie ist für alle da, unabhängig vom Geldbeutel.</p>
              <p class="text-right"><a class="btn btn-outline-light" href="">mehr</a></p>
            </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="/assets/images/kampagnen/kinder-im-feld.jpg" alt="Ein Schwarz-weiß Photo, das zeigt wie Kinder auf einem Feld davon laufen.">
            <div class="carousel-caption d-none p-3 mb-5 bg-light text-dark d-md-block text-left" style="bottom: auto; top: 40px;">
              <h4 class="mb-3">Fluchtursachen - was kann Deutschland tun?</h4>
              <h5>Jetzt anmelden zum Bürgerkonvent!</h5>
              <p>Weltweit sind Millionen Menschen auf der Flucht vor Krieg und Verfolgung, Hunger, Dürre und Armut. Doch was kann Deutschland tun? Melden Sie sich jetzt an zum 1. Bürgerkonvent der Bundesrepublik Deutschland und diskutieren Sie mit.</p>
            </div>
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="/assets/images/kampagnen/resist.jpg" alt="Ein Photo aus der Vogelperspektive auf dem Menschen auf einem Strand das Wort 'Resist' formen.">
            <div class="carousel-caption d-none p-3 mb-5 bg-light text-dark d-md-block text-left" style="left: 55%;">
              <h4 class="mb-3">Das BMDT fördert Deine Demokratie-Initiative mit 5000€!</h4>
              <p>Deutschlandweit engagieren sich Tausende ehrenamtlich in Initiativen für mehr Demokratie und Transparenz. Doch oftmals fehlt das Geld. Das BMDT fördert deshalb Deine Demokratie-Initiative mit 5000€ ! Egal, ob Du Lobbyskandale aufdeckst oder Dich für kommunale Mitbestimmung einsetzt.</p>
              <p class="text-center"><a href="#" class="btn btn-outline-primary">Bewirb Dich jetzt!</a></p>
            </div>
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    </div>
</div>

<div class="container">
  <div class="media">
    <div class="align-self-center media-body">
      <blockquote class="blockquote text-center"><p style="font-size: 1.35em; font-style: italic;">Das Vertrauen in unsere Demokratie ist unbezahlbar. Wir brauchen mehr Mitbestimmung und Transparenz.
      </p>
        <footer class="blockquote-footer text-right"><a href="/ministerium/ministerin/">Katarina Barley, Bundesministerin</a></footer>
    </blockquote>
    </div>
      <img class="m-5 align-self-center w-25 rounded-circle" src="/assets/images/barley.jpg" alt="Photo zeigt Katarina Barley." />
  </div>
</div>

<div class="bg-light my-5 py-5">
  <div class="container">
    <h3 class="mb-4 row">Termine und Veranstaltungen</h3>
    <div class="row">
      <div class="col">
          <div class="card border-light mb-3" style="max-width: 18rem;">
            <div class="card-header">21. Jan</div>
            <div class="card-body">
              <h5 class="card-title">Neujahrsempfang</h5>
              <p class="card-text">Das Bundesministerium für Demokratie und Transparenz lädt ein zum Neujahrsempfang mit Vertreter*innen aus Zivilgesellschaft und Politik.</p>
            </div>
          </div>
      </div>
      <div class="col">
          <div class="card border-light mb-3" style="max-width: 18rem;">
            <div class="card-header">23.-26. Jan</div>
            <div class="card-body">
              <h5 class="card-title">World Democracy Summit</h5>
              <p class="card-text">Diskutieren Sie in Davos über politische Bildung, Mitbestimmung im Alltag und Lobbyismus.</p>
            </div>
          </div>
      </div>
      <div class="col">
          <div class="card border-light mb-3" style="max-width: 18rem;">
            <div class="card-header">15. Sept</div>
            <div class="card-body">
              <h5 class="card-title">Demokratiefestival vor dem Brandenburger Tor</h5>
              <p class="card-text">Wir feiern die Demokratie! Mit einem großen Straßenfest vor dem Brandenburger Tor am internationalen Tag der Demokratie. </p>
            </div>
          </div>
      </div>
    </div>
    <p class="text-right">
        <a href="/service/veranstaltungen/" class="btn btn-outline-primary">Mehr Veranstaltungen</a>
    </p>
  </div>
</div>
<div class="container">
  <h3>Themen</h3>
  {% include themen-nav.html %}
</div>