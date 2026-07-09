# 📅 Schema Vecka 10: Next.js

Vi bygger vidare på vår app och hämtar data från API.

---

## 📅 Måndag: Dynamic routes & 404

Vi bygger sidor för varje enskilt kort med dynamic routes och params samt skapar en not found-sida


### 🎯 Mål för dagen

* Förstå vad dynamic routes är och hur de fungerar
* Kunna använda params i komponenter
* Async i komponenter
* Använda notFound()

### 📚 Material

#### 📃 Läsning
* [Dynamiska routes](https://nextjs.org/docs/app/getting-started/layouts-and-pages#creating-a-dynamic-segment)
* [Params](https://nextjs.org/docs/app/api-reference/file-conventions/page#params-optional)
* [notFound()](https://nextjs.org/docs/app/api-reference/functions/not-found)
* [notFound.tsx](https://nextjs.org/docs/app/api-reference/file-conventions/not-found)

#### 🛠️ Övningar
* Skapa länkar från korten till en dynamisk route med info
* Skapa en not-found-sida
* Lägg till en koll på info-sidan som vidarebefodrar användaren till not-found om sidan inte finns (gör ev en custom not found till bara info-delen)

---

## 📅 Tisdag: APIer

Vad är ett API och hur kan vi använda det inom front-end?

### 🎯 Mål för dagen

* Förstå skillnaden och teorin bakom olika web API-typer (REST vs GraphQL)
* Förstå hur data flödar från en extern källa till vårt gränssnitt

### 📚 Material

#### 📃 Läsning
* [Futurama API](https://futuramaapi.com/)
* [Om REST (översiktligt)](https://aws.amazon.com/what-is/restful-api/)
* [Om GraphQL (översiktligt)](https://graphql.org/learn/)
* [Swap (REST)](https://swapi.info/)
* [Swapi (GraphQl)](https://graphql.org/swapi-graphql/)
* [PokéAPI (REST)](https://pokeapi.co/)
* [PokéAPI (GraphQL)](https://beta.pokeapi.co/graphql/console)
* [Hoppscotch](https://hoppscotch.io/)
* [Swagger](https://api.escuelajs.co/docs#/products/ProductsController_getProduct)
* [Exempel på olika API:er](https://developer.mozilla.org/en-US/docs/Web/API)

---

## 📅 Onsdag: Fetch API

Vi byter källa för våra karaktärer från json till API-data

### 🎯 Mål för dagen

* Server Fetch: Hämta data med fetch
* Om vi hinner: Dynamisk metadata (t.ex. att sidans titel är kopplat till aktuell data) och/eller streaming med suspense
* Ev lite om felhantering (try/catch och state)

### 📚 Material

#### 📃 Läsning
* [**Viktigt** - Data Fetching fundamentals](https://nextjs.org/docs/app/getting-started/fetching-data)
* [Generating Metadata](https://nextjs.org/docs/app/api-reference/functions/generate-metadata)

#### 🛠️ Övningar
* Hämta in data från ett API med hjälp av en funktion som kör fetch

---

## 📅 Torsdag: URL State Management med searchParams 

Vi lär oss styra sidans innehåll via URL:en med hjälp av `searchParams` och bygger ev en enkel sök.


### 🎯 Mål för dagen

* Förstå URL State Management: Varför vi vill ha filter och sökningar i URL:en
* Kunna använda `searchParams` i server components (page props)
* Göra en ny `fetch` baserat på vad som står i `searchParams`

### 📚 Material

#### 📃 Läsning
* [`searchParams` prop](https://nextjs.org/docs/app/api-reference/file-conventions/page#searchparams)
* [URL Search Params (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams)

---

## 📅 Fredag: Kodsnack

Vi snyggar till koden och kollar på varandras lösningar från veckans koncept.

TBA


---
