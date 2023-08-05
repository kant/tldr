# say

> Convierte texto a voz.
> Más información: <https://ss64.com/osx/say.html>.

- Di una frase en voz alta:

`say "{{Me gusta montar en bicicleta.}}"`

- Lee un archivo en voz alta:

`say -archivo-de-entrada={{nombre-de-archivo.txt}}`

- Di una frase con una voz y un ritmo de voz personalizados:

`say --voice={{voice}} --rate={{words_per_minute}} "{{Lo siento David, no puedo dejarte hacer eso.}}"`

- Lista las voces disponibles (cada voz habla en un idioma distinto):

`say --voice="?"`

- Di algo en polaco:

`say --voice={{Zosia}} "{{Litwo, ojczyzno moja!}}"`

- Crea un archivo de audio con el texto hablado:

`say --output-file={nombre-de-fichero.aiff}} "{{Aquí están los locos.}}"`
