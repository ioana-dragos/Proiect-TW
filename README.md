# Învățare și evaluare educațională

## 1. Descrierea proiectului

Proiectul constă în realizarea unei aplicații web prin care elevii pot învăța și exersa informatica. Aceștia vor putea rezolva exerciții și quiz-uri pe diferite capitole, își vor putea crea planuri de studiu și își vor putea urmări progresul.

## 2. Problema abordată

Elevii au nevoie de o metodă simplă și organizată pentru a învăța informatica și pentru a-și verifica cunoștințele. Aplicația îi va ajuta să exerseze, să vadă ce au înțeles și ce mai trebuie să învețe. De asemenea, vor primi punctaje și explicații pentru răspunsurile greșite.

## 3. Obiectivele proiectului

- Ajutarea elevilor să învețe și să exerseze informatica.
- Organizarea exercițiilor și quiz-urilor pe capitole.
- Afișarea punctajelor și a explicațiilor pentru răspunsurile greșite.
- Ajutarea elevilor să își organizeze timpul prin planuri de studiu.
- Urmărirea progresului și a rezultatelor obținute.
- Permiterea administratorului să gestioneze exercițiile, quiz-urile și utilizatorii.

## 4. Utilizatorii vizați

Aplicația este destinată elevilor care doresc să învețe informatică și să își verifice cunoștințele.

Vor exista două tipuri de utilizatori:

- **Elev:** poate rezolva exerciții și quiz-uri, poate vedea rezultatele, poate primi explicații, își poate crea un plan de studiu și își poate urmări progresul.
- **Administrator:** poate adăuga, modifica și șterge exerciții și întrebări pentru quiz-uri. De asemenea, poate gestiona conturile utilizatorilor.

## 5. Membrii echipei și responsabilitățile

Echipa proiectului este formată din:

- **Corjuc Maria** – se ocupă de pagina principală cu capitolele de informatică, conectarea backendului la baza de date, calcularea punctajelor și afișarea rezultatelor. De asemenea, pregătește quiz-urile pentru clasa a XI-a.
- **Cinăzan Maria** – se ocupă de paginile de autentificare și înregistrare, pagina de progres și pagina de administrare. De asemenea, pregătește quiz-urile pentru clasa a IX-a.
- **Dragoș Ioana** – se ocupă de crearea bazei de date, pagina planului de studiu și pagina unde se rezolvă exercițiile și quiz-urile. De asemenea, pregătește quiz-urile pentru clasa a X-a.

Toți membrii echipei vor participa la testarea aplicației și la rezolvarea eventualelor probleme.

## 6. Funcționalitățile propuse

### Funcționalități pentru elev

- Crearea unui cont și autentificarea în aplicație.
- Vizualizarea capitolelor de informatică.
- Accesarea exercițiilor și quiz-urilor.
- Rezolvarea exercițiilor și quiz-urilor.
- Afișarea punctajului după terminarea unui quiz.
- Afișarea explicațiilor pentru răspunsurile greșite.
- Crearea unui plan de studiu, în care poate adăuga activități și termene-limită.
- Marcarea activităților ca fiind finalizate.
- Vizualizarea quiz-urilor rezolvate, împreună cu data și punctajul obținut.

### Funcționalități pentru administrator

- Adăugarea, modificarea și ștergerea exercițiilor.
- Adăugarea și modificarea întrebărilor pentru quiz-uri.
- Gestionarea răspunsurilor corecte și a explicațiilor.
- Vizualizarea listei cu utilizatorii înregistrați.
- Gestionarea conturilor utilizatorilor.

### Funcționalități opționale

- Descărcarea rezultatelor elevilor.
- Recomandarea capitolelor care ar trebui recapitulate, în funcție de rezultate.

## 7. Tehnologiile alese

- **HTML și CSS** – pentru realizarea structurii și aspectului paginilor.
- **SvelteKit** – pentru organizarea paginilor și navigarea în aplicație.
- **JavaScript** – pentru funcțiile interactive și comunicarea cu backendul.
- **Java și Spring Boot** – pentru autentificare, gestionarea exercițiilor, calcularea punctajelor și salvarea datelor.
- **PostgreSQL și Supabase** – pentru crearea și gestionarea bazei de date, unde vor fi păstrate conturile utilizatorilor, quiz-urile, rezultatele și planurile de studiu.
