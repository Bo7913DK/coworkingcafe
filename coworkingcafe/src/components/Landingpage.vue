<script setup>
</script>

<template>
  <div class="full-page">
    <section class="hero-banner">
      <img src="@/img/herobanner.png" alt="Hero-banner af Coworking Café" class="hero-image">
      <div class="hero-content">
        <img src="@/img/cwchvidlogotekst.svg" alt="Coworking Cafe Logo" class="hero-logo">
        <button class="booknu-button">BOOK NU</button>
      </div>
    </section>
    
    <section class="info-box">
      <div class="info-item">
        <img src="@/img/prisikon.png" alt="Pris Ikon" class="info-icon">
        <div class="info-text">Priser fra 4500 kr</div>
      </div>
      <div class="info-item">
        <img src="@/img/lokationikon.png" alt="Lokations Ikon" class="info-icon">
        <div class="info-text">Central beliggenhed, uden naboer</div>
      </div>
      <div class="info-item">
        <img src="@/img/gaesterikon.png" alt="Antal Gæster Ikon" class="info-icon">
        <div class="info-text">80 Siddepladser</div>
      </div>
    </section>
    <section class="hvad-er-cwc">
      <div class="showcase-flex-reverse">
          <img src="@/img/hvadercwc.webp" class="venuephoto-one" alt="Billede af Coworking Cafés bordpynt med gæster">
          <div class="showcase-text-wrap">
            <h1 class="hvad-er-h1">Hvad er Coworking Cafe?</h1>
            <p class="showcase_text_left">Coworking Café er et <b>alsidigt selskabslokale</b>, der egner sig perfekt til private fester, firmaarrangementer og møder. Med vores moderne faciliteter tilbyder vi en fleksibel og inspirerende ramme for enhver begivenhed. Uanset om det er en sammenkomst, en professionel workshop eller en festlig fejring, skaber vores café den ideelle atmosfære for dit arrangement.
            <br><br>Coworking Café ligger <b>centralt</b> - kun 10 minutter fra Odense Banegård. Og så er det i et industriområde <b>uden naboer</b>, hvilket betyder at festen kan fortsætte med <b>højt musik</b> til sent ud på natten. <br><br>Lokalet er på <b>134 m2</b>, med plads til <b>80 siddende gæster</b>, så du kan invitere alle vennerne, kollegaerne og familien med.
          </p>
          </div>
      </div>
    </section>

    <section class="priser-section">
  <h2 class="priser-h2">Priser</h2>
  <div class="price-wrap">
    <div class="price-box">
      <p class="dag-p">Halv dag (4 timer)</p>
      <p class="price">4500 kr.</p>
    </div>
    <div class="price-box">
      <p class="dag-p">Hel dag</p>
      <p class="price">7500 kr.</p>
    </div>
  </div>
  <button class="semere-button">SE MERE</button>
    </section>

  <section class="review-section">
  <h3 class="review-h3">Se hvad vores kunder synes</h3>
  <div class="review-wrap">
    <button class="review-button"><</button>
    <div class="review-box">
      <p class="review-text">“Jeg holdt min 40-års fødselsdag i Coworking Café, og det var en fantastisk oplevelse. Central beliggenhed og ingen naboer betød, at vi kunne feste hele natten uden problemer. Kan varmt anbefales!"</p>
      <p class="reviewer-author">- Jens R.</p>
    </div>
    <div class="review-box">
      <p class="review-text">"Coworking Café er den perfekte ramme for både professionelle møder og sociale events. Lokalet har en moderne og indbydende atmosfære, og faciliteterne lever fuldt op til forventningerne. Personalet er hjælpsomme og professionelle, hvilket gjorde vores arrangement til en succes. Jeg kan varmt anbefale dette sted til enhver, der søger et fleksibelt og inspirerende lokale."</p>
      <p class="reviewer-author">- Jan L.</p>
    </div>
    <div class="review-box">
      <p class="review-text">“Vi holdt et firmamøde på Coworking Café, og det var helt perfekt! Lokalet var professionelt og komfortabelt, og faciliteterne var ideelle til vores præsentationer. Vi følte os virkelig velkomne. Absolut et sted, vi vil bruge igen! Vi valgte forplejning og det var bare i top!”</p>
      <p class="reviewer-author">- Jon P.</p>
    </div>
    <button class="review-button">></button>
  </div>
    </section>

    <section class="eventtype-section">
  <h4 class="eventtype-h4">Coworking Café passer perfekt til</h4>
  <div class="eventtype-wrap">
    <div class="eventtype-box">
      <p class="eventtype-headline">Privatarrangementer</p>
      <p class="eventtype-text">Vores selskabslokale er det perfekte sted at holde det næste firma arrangement - hvad end det er julefrokost eller et større event. Der er nemlig plads til alle medarbejderne, og AV-udstyr kan tilkøbes så præsentationer kan ses på lærreder.</p>
      <div class="eventtype-image-container">
      <img src="@/img/privatarrangementlandingpage.webp" class="eventtype-image" alt="Billede af Coworking Cafés tomme lokale">
      <div class="eventtype-mereinfo">Læs mere</div>
      </div>
    </div>
    <div class="eventtype-box">
      <p class="eventtype-headline">Firmafester</p>
      <p class="eventtype-text">Om det er fødselsdag, konfirmation, eller noget helt tredje, tilbyder vi et rummeligt selskabslokale med plads til 80 mennesker lige i hjertet af Odense. Med muligheden for tilkøb af forplejning gør vi det nemt for dig så du kun skal tænke på at hygge dig. </p>
      <div class="eventtype-image-container">
      <img src="@/img/firmafestlandingpage.webp" class="eventtype-image" alt="Billede af Coworking Cafés oppyntet lokale med gæster og tag-selv bord">
      <div class="eventtype-mereinfo">Læs mere</div>
    </div>
    </div>
    <div class="eventtype-box">
      <p class="eventtype-headline">Kurser og møder</p>
      <p class="eventtype-text">Skal du holde et kursus eller et mindre møde, kan vi tilbyde lokaler med Wi-Fi og TV-skærm, så alle kan følge med i dagsordenen. <br><br>Det er også muligt at tilkøbe forplejning.</p>
      <div class="eventtype-image-container">
        <img src="@/img/kurserlandingpage.webp" class="eventtype-image" alt="Billede af Coworking Cafés store mødelokale med deltagere">
        <div class="eventtype-mereinfo">Læs mere</div>
        </div>
    </div>
  </div>
    </section>

    <section class="hvorfor-cwc">
      <div class="showcase-flex-reverse">
          <img src="@/img/coworkingcafeinterior.webp" class="interiormap" alt="Billede af Coworking Cafés bordpynt med gæster">
          <div class="showcase-text-wrap-hvorfor">
            <p class="hvorfor-minioverskrift">Hvor, hvor mange og hvorfor?</p>
            <h5 class="hvorfor-h5">Hvad er Coworking Cafe?</h5>
            <div class="showcase-text-left-hvorfor">
            <ul>
              <li class="hvorfor-liste">Ligger centralt i Odense - kun 10 minutter fra Banegården.</li>
              <li class="hvorfor-liste">Der er ingen naboer, så festen kan fortsætte i lang tid uden klager.</li>
              <li class="hvorfor-liste">Plads til 80 siddende og 120 stående gæster i vores 134m2 store lokale.</li>
              <li class="hvorfor-liste">Mulighed for tilkøb af forplejning, så du ikke skal tænke på servicen.</li>
              <li class="hvorfor-liste">Mulighed for at tilkøbe AV-udstyr, så deltagerne får det hele med.</li>
              <li class="hvorfor-liste">Lokalet egner sig både til privatarrangementer, firmafester og kurser.</li>
              <li class="hvorfor-liste">Priser fra 4500 kr.-</li>
              </ul>
            </div>
          </div>
      </div>
    </section>
  </div>

</template>