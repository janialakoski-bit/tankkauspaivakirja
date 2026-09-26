# Tankkauspäiväkirja – pilviversio

Tämä versio käyttää Supabasea kirjautumiseen ja pilvitallennukseen.

## Vaihe 9
Aja `SUPABASE_VAIHE_9.sql` Supabasen SQL Editorissa ennen sovelluksen testaamista.

Muutos lisää tankkauksille kirjaajan (`user_id`). Tavallinen käyttäjä voi muokata ja poistaa omia tankkauksiaan. Admin voi käsitellä kaikkia tankkauksia.

Lisäksi hyväksytty sähköpostiosoite tarkistetaan ennen uuden käyttäjätunnuksen luontia, ja uuden käyttäjän Auth-tunnus yhdistetään automaattisesti `allowed_users`- ja `user_roles`-tauluihin.

Sovellus käyttää Supabase Project URLia ja Publishable keytä `index.html`-tiedostossa.
