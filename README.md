# Vaja1-ADC-singe-conversion-STM32F0
<h4> Glede na vašo razvojno ploščico in razširitveno vezje s tipkami ter potenciometri, izberite usretzni analogni vhod. Kateri pin je to? </h4>
<p> PC0. </h4>
<h4> V Pinout zavihku ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? </h4>
<p> 1. </p>
<h4> Izbrani ADC pretvornik ima oznako s trikotnikom. Kaj to pomeni? </h4>
<p> To pomeni, da je PIN zaseden. </p>
<h4> Kaj morate storiti, da razrešite to omejitev? Opišite in jo odpravite. </h4>
<p> Pin, ki je zaseden postavimo na reset state, na zavihku ADC pa obkljukamo IN10. Sedaj imamo pin PC0 uporabljen kot ADC pretvornik. </p>
<h4> Razširite razdelek ADC. Koliko je vseh vhodnih kanalov? </h4>
<p> Vseh vhodnih kanalov je 16. </p>
<h4> Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? </h4>
<p> Poleg pina se izpiše ADC_IN10. </p>
<h4> V Configuration kliknemo ADC gumb. V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti? </h4>
<p> a. 12-bitno, od 0 do 4095. </p>
<p> b. 10-bitno, od 0 do 1023. </p>
<p> c. 6-bitno, od 0 do 63. </p>
<h4> Komentar: </h4>
<p> Naloga je delovala po navodilih. </p>
