
# BendTime

Aplikacja wykonana dla firmy Temared pozwalająca oszacować czas oraz koszt produkcji elementów podczas wykonywania operacji gięcia na prasach krawędziowych.
Do jej wykonania wykoszystałem algorytmy uczenia maszynowego PyCaret wytrenowanego na historycznych danych. Interfejs został wykonany Streamlit. Aplikacja została wdrożona na platformie DigitalOcean. 

<a href="https://bendtime-jrnlq.ondigitalocean.app/" target="_blank" rel="noopener noreferrer">Odwiedź stronę BendTime</a>

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
