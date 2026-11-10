# Plan de implementare și organizare

## 1. Alegerea și justificarea tehnologiilor

- **HTML și CSS** — Pentru structura și aspectul paginilor aplicației.
- **SvelteKit** — Pentru organizarea paginilor, navigarea între acestea și reutilizarea componentelor interfeței.
- **JavaScript** — Pentru interacțiunea cu utilizatorul și comunicarea cu backendul.
- **Java și Spring Boot** — Pentru autentificare, gestionarea exercițiilor, calcularea punctajelor și salvarea datelor.
- **PostgreSQL găzduit pe Supabase** — Pentru stocarea datelor în tabele și gestionarea relațiilor dintre utilizatori, quiz-uri, rezultate și planuri de studiu.

## 2. Strategia de versionare

Codul aplicației îl vom avea într-un repository pe GitHub. Vom utiliza Git, astfel încât fiecare dintre noi să își salveze contribuțiile prin commit-uri cu mesaje clare. Înainte de a încărca modificările, vom verifica dacă funcționează corect.

## 3. Prioritizarea activităților

Funcționalitățile obligatorii, cu prioritate ridicată, sunt autentificarea, rezolvarea exercițiilor și a quiz-urilor, afișarea rezultatelor și a feedbackului, organizarea planurilor de studiu, urmărirea progresului și administrarea conținutului și a utilizatorilor.

Funcționalitățile opționale, cu prioritate scăzută, sunt exportul rezultatelor și oferirea de recomandări de recapitulare în funcție de rezultatele elevului. Acestea vor fi implementate după finalizarea funcționalităților obligatorii, în funcție de timpul disponibil.

## 4. Planul de implementare și repartizarea responsabilităților

| Etapă | Ce vom realiza | Responsabilă | Termen |
|---|---|---|---|
| 1 | Crearea bazei de date | Dragoș Ioana | Săptămâna 8 |
| 2 | Pagina de autentificare și înregistrare | Cinăzan Maria | Săptămâna 8 |
| 3 | Pagina principală cu capitolele de informatică | Corjuc Maria | Săptămâna 8 |
| 4 | Conectarea backendului la baza de date | Corjuc Maria | Săptămâna 9 |
| 5 | Pagina „Plan de studiu”, cu activități și termene | Dragoș Ioana | Săptămâna 9 |
| 6 | Pagina „Progres”, cu rezultatele obținute | Cinăzan Maria | Săptămâna 9 |
| 7 | Pagina de administrare a exercițiilor, quiz-urilor și utilizatorilor | Cinăzan Maria | Săptămâna 11 |
| 8 | Pagina de rezolvare a exercițiilor și quiz-urilor | Dragoș Ioana | Săptămâna 11 |
| 9 | Calcularea punctajului și pagina de afișare a rezultatului și feedbackului | Corjuc Maria | Săptămâna 11 |
| 10 | Pregătirea quiz-urilor pentru clasa a IX-a | Cinăzan Maria | Săptămâna 13 |
| 11 | Pregătirea quiz-urilor pentru clasa a X-a | Dragoș Ioana | Săptămâna 13 |
| 12 | Pregătirea quiz-urilor pentru clasa a XI-a | Corjuc Maria | Săptămâna 13 |
| 13 | Testarea aplicației și corectarea erorilor | Toate | Săptămâna 14 |
