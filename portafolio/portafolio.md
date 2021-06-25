---
Layout: default
---

## Portafolio

Selección de trabajos del portafolio


<div class="w3-container">
  <h2>Portadas</h2>
  <p>Hacer clic en las imágenes para ampliarlas</p>

</div>
<div class="w3-row-padding">
  <div class="w3-container w3-third">
    <img src="portafolio_sbc_web.png" style="width:100%;cursor:pointer"
    onclick="onClick(this)" class="w3-hover-opacity">
  </div>
  <div class="w3-container w3-third">
    <img src="portafolio_sbc_web2.png" style="width:100%;cursor:pointer"
    onclick="onClick(this)" class="w3-hover-opacity">
  </div>
  <div class="w3-container w3-third">
    <img src="portafolio_sbc_web3.png" style="width:100%;cursor:pointer"
    onclick="onClick(this)" class="w3-hover-opacity">
  </div>
</div>

<div id="modal01" class="w3-modal" onclick="this.style.display='none'">
  <span class="w3-button w3-hover-red w3-xlarge w3-display-topright">&times;</span>
  <div class="w3-modal-content w3-animate-zoom">
    <img id="img01" style="width:100%">
  </div>
</div>

<script>
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
}
</script>



---


Descargar el cv y portafolio completo:

- [Alta resolución (40 MB)](link1)
- [Baja resolución (20 MB)](link2)


[(Regresar)](https://ovisnigra.github.io/cv_sbourguet/)
