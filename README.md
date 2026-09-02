Varför passar Flexbox för dina aktivitetskort — och ge ett konkret exempel från din egen kod?

Det passar in bra pga att korten annars hamnar på hög och det dels ser sämre ut samt även tar betydligt mer plats för samma info som användare ser

Grid är till för när det finns mycket innehåll/ mer komplexa lösningar.


<section>
  <div style="display: flex;">
    <div class="card" style="display: flex">Workshop</div>
    <div class="card">Fika</div>
    <div class="card">Brädspel</div>
  </div>
</section>

.card {
  margin: 20px;
}

Byt ut div för mer specifik tagg
gör unika class-kort (om det inte ska se exakt lika ut såklart)
.card saknar allt visuelt, värt att lägga till det