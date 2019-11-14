# Vaja2_ADC_continuos_conversion_STM32F0

<h3>Odgovori</h3>



<h3>Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? </h3>
<p>PC0</p>
<h3>Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?</h3
 <p>ADC_IN10</p>
 <h3>V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. Kaj opazite?</h3>
 <p>Druge vrednosti se spremenijo na enako vrednost kot je APB1</p>
 <h3>Clock Prescaler nastavimo z deliteljem 4. Kolikšna je sedaj preskalirana frekvenca takta</h3>
 <pFrekvenca sedaj znaša 4 MHz</p>
 <h3>Sampling time (čas vzorčenja tvz_ciklih) spremenite na 239.5 ciklov. Pravi čas vzorčenja se nato poveča še za 12 ciklov. Koliko znaša pravi čas vzorčenja tvz v mikro sekundah?</h3>
 <p>59,875ms.</p>
 <h3>Komentar</h3>
 <p>ADC bere v realnem času spremembo na pinu PC0 in izpiše v programu STM Studio v okrivru 8-bitov, torej 0-255.</p>
