# ArtGalleryGenerator

Stworzona przeze mnie aplikcaji streamit umożliwiająca genrowanie obrazów w wybranym stylu malarskim przy pomocy modeli sztucznej inteligencji Dalle-2 lub Dalle-3. Utworzone obrazy automatycznie wysyłane są do bazy danych Cloudinary

![Generator obrazów](AGG1.jpg)

Aplikacja pozwala również na przeglądanie wszystkich wygenerowanych obrazów

![Generator obrazów](AGG2.jpg)


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
