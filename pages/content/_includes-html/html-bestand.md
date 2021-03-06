Het HTML-bestand
----------------

Een **statische webpagina** bestaat uit een tekstbestand dat meestal de **bestandsextensie** `.html` heeft. Door deze extensie herkennen zowel de browser als de teksteditor het bestand als een HTML-document.

{% highlight html linenos %}
<!DOCTYPE html>
<html lang="nl">
    <head>
        <meta charset="UTF-8">
        <title>Hallo</title>
    </head>
    <body>
        <h1>Hallo GDM!</h1>
        <p>Mijn naam is Voornaam Naam.</p>
    </body>
</html>
{% endhighlight %}{:data-file="index.html"}

Als de webbrowser geen specifiek bestand opvraagt aan een webserver, dan zullen de meeste webservers ervan uitgaan dat het gevraagde bestand `index.html` is. Dit hangt af van de serverinstellingen die door de serverbeheerder ingesteld zijn.

> Opmerking
> ---
> De **startpagina** *(Eng.: home page)* van een website noem je best `index.html`.
{:.card.card-remark}