# Moja Analiza Danych EDA Pasażerów okrętu Titanic: Eksploracja Domenowa

Zapraszam do zapoznania się z wykonaną przeze mnie analizą danych pasażerów pamiętnego rejsu okrętu Titanic. Okręt podczas swojego pierwszego rejsu doświadczył fatalnego w skutkach uderzenia w górę lodową co doprowadziło do jego zatonięcia i śmierci wielu pasażerów.

<a href="Titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="Titanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
