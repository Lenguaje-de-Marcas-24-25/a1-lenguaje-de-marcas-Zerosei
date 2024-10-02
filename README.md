# README.md

## ¿Qué es un lenguaje de marcas?

Un lenguaje de marcas es un lenguaje que usa etiquetas para organizar y describir datos.

## Características generales de los lenguajes de marcas

- Usan etiquetas para organizar la información.
- Son fáciles de leer por personas y ordenadores.
- Se usan en diferentes áreas como la web o los calendarios.

## Clasificación de los lenguajes de marcas

1. **Generales**: Como HTML, XML.
2. **Específicos**: Como iCalendar, vCard, KML, RSS.

### Lenguajes más importantes

- **HTML**: Para páginas web.
- **XML**: Base para otros lenguajes.
- **iCalendar**: Para eventos de calendario.
- **vCard**: Para contactos.
- **KML**: Para mapas.
- **RSS**: Para noticias.

## Ámbitos de aplicación

- **Web**: HTML y XML.
- **Calendarios**: iCalendar.
- **Mapas**: KML.
- **Noticias**: RSS.
- **Contactos**: vCard.

## Ejemplos de lenguajes de marcas

### HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Ejemplo</title>
</head>
<body>
    <h1>Hola Mundo</h1>
</body>
</html>
```
HTML se usa para crear páginas web. Los navegadores lo leen.
### iCalendar
```
BEGIN:VCALENDAR
VERSION:2.0
BEGIN:VEVENT
SUMMARY:Reunión
DTSTART:20231003T140000Z
DTEND:20231003T150000Z
END:VEVENT
END:VCALENDAR
```
iCalendar se usa para eventos de calendario. Lo leen apps como Google Calendar.
### VCARD
```
BEGIN:VCARD
VERSION:3.0
FN:Antonio Rios
TEL:696 01 72 44
EMAIL:Antonio@ejemplo.com
END:VCARD
```
vCard se usa para contactos. Lo leen apps como Outlook.
### KML
```
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Placemark>
    <name>Lugar</name>
    <Point>
      <coordinates></coordinates>
    </Point>
  </Placemark>
</kml>
```
KML se usa para mapas. Lo leen apps como Google Earth.
### RSS
```

<rss version="2.0">
  <channel>
    <title>Mi Blog</title>
    <link>http://ejemplo.com</link>
    <item>
      <title>Post 1</title>
      <link>http://ejemplo.com/post1</link>
    </item>
  </channel>
</rss>

```
RSS se usa para distribuir noticias. Lo leen lectores de RSS.
