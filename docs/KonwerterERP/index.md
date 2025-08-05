# ArtGalleryGenerator

Aplikacja wykonana przeze mnie dla firmy Temared. Konwertuje ona zablokowany do edycji magazynowy raport ERP do formatu .xlsx o wymaganym układzie danych co pozwala na automatycznie zaczytywanie informacji do szybkiego generowania wykresów u osób kierujących magazynem i analizę danych w czasie rzeczywistym.

<a href="https://radoxan-konwertowanie-danych-z-erp-karolkonwerter-nixntw.streamlit.app/" target="_blank" rel="noopener noreferrer">Odwiedź stronę KonwerterERP</a>

![Generator obrazów](KERP1.jpg)

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
