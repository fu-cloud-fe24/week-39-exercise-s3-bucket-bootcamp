# Övningar S3 Bucket Bootcamp

## Övning 1: Skapa och driftsätt en enkel HTML-sida
1. Skriv en grundläggande HTML-fil som innehåller en rubrik och lite text.
2. Logga in på AWS och skapa en ny S3-bucket. Kom ihåg att namnet på din bucket måste vara unikt globalt.
3. Ladda upp din HTML-fil till S3-bucketen.
4. Konfigurera bucketens inställningar så att den är offentlig och kan nås via en webbläsare, samt att den har korrekta permissions.
5. Öppna webbadressen till din S3-bucket för att se din HTML-sida live.

## Övning 2: Driftsätt en React-applikation
1. Välj ett React projekt som du gjort tidigare.
2. Kör `npm run build` för att generera en produktionsversion av din applikation.
3. Skapa en ny S3-bucket och ladda upp alla filer från dist-mappen.
4. Aktivera statisk webbhosting för din bucket och ställ in indexdokumentet till index.html.
5. Öppna webbadressen till din S3-bucket för att se din React-applikation live.

## Övning 3
1. Bygg en frontend i React till ditt Todo API där du använder API:et i din applikation.
2. Deploya din frontend till AWS S3.
