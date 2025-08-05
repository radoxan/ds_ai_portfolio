# FindFriends

Stworzona przeze mnie aplikacja do wyszukiwania osób o wspólnych zainteresowaniach. Do jej stworzenia wykorzystałem model LLM do klastrowania.

![Generator obrazów](FF1.jpg)

<a href="https://project71.streamlit.app/" target="_blank" rel="noopener noreferrer">Odwiedź stronę FindFriend</a>

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
