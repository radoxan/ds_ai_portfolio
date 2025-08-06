# InvoiceReader

Stworzona przeze mnie aplikacja do automatycznego odczytywania danych z faktur. Program przetwarza wszystkie pliki graficzne a następne zapisuje zbiorczo wszystkie informacje w pliku .csv

Przykładowa faktura
![InvoiceReader1](Faktura.jpg)

Zebrane dane
![InvoiceReader2](Data.jpg)

Wykorzystanie klasy instructor
![InvoiceReader3](Kod.jpg)


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
