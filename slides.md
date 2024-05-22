---
theme: seriph
background: /cover.jpg
class: text-center
highlighter: shikiji
lineNumbers: false
info: |
  ## Zmień to, nie podoba mi się - czyli sztuka dawania feedbacku podczas code review
drawings:
  persist: false
transition: slide-up
title: Zmień to, nie podoba mi się - czyli sztuka dawania feedbacku podczas code review
mdc: true
---

<div style="position: absolute; left: 40px; top: 40px; text-align: left;">

# Zmień to, nie podoba mi się
## czyli sztuka dawania feedbacku podczas code review


</div>

---
layout: image-right
image: /Kacper_small.jpg
---

# Kacper Szewczyk

<v-clicks>

- JS developer w RST Software
- Next.js / React Native
- Ex-IT project manager

</v-clicks>

---
layout: image
image: /equality.jpeg
---

---
layout: image
image: /winni.jpeg
---

---
layout: full
---

<div style="margin: auto">
  <img src="/code-review-quality.png" style="height: 100%; object-fit: cover; margin: auto;">
</div>


---
layout: full
---

<Tweet id="1379451260638785536"/>

---
layout: full
---
<img src="/timeline.jpeg" style="width: 100%;  object-fit: cover;">


---
layout: statement
---

# Dlaczego kilka razy nanosimy poprawki po code review?

---
layout: image-right
image: /non-violent.jpeg
---

# Porozumienie bez przemocy (Non violent communication - NVC)

<v-clicks>

- metoda komunikacji opracowana przez amerykańskiego psychologa Marchalla Rosenberga
- skupia się na wyrażaniu uczuć i potrzeb
- pozwala na wyrażanie swoich emocji w sposób konstruktywny

</v-clicks>


---
layout: statement
---

# Dokumentacja jest słaba

<v-click>

## (Twoja) dokumentacja jest słaba

</v-click>


---
layout: statement
---

### W dokumentacji, którą prowadzimy w ramach wspólnego projektu, nie ma systematyki. Opisy nie są sklasyfikowane, a w dodatku umieszczone zostały w pięciu miejscach w Confluence. Ta sytuacja sprawia, że jestem poirytowany i mam poczucie zmarnowanego czasu, kiedy chcę znaleźć dokładną specyfikację. Boję się, że coś zrobię źle, bo nie mam pewności, czy korzystam z najnowszej wersji dokumentacji. Chciałbym, żeby w dokumentacji panował porządek i żeby poszczególne dokumenty łatwo można było znaleźć. Zależy mi też na tym, żeby posiadać wszystkie informacje do skończenia funkcjonalności, bez konieczności szukania ich w kilku miejscach. Proszę, żebyś wprowadził porządek w dokumentacji, nie tylko po to, żeby można było łatwo się w niej odnaleźć, lecz także po to, żeby zyskać pewność, że wszystkie dokumenty są na swoim miejscu.


---
layout: image
image: /too-long.gif
---

---
layout: two-cols
---

Dokumentacja jest słaba. Napraw to

::right::

W dokumentacji, którą prowadzimy w ramach wspólnego projektu, nie ma systematyki. Opisy nie są sklasyfikowane, a w dodatku umieszczone zostały w pięciu miejscach w Confluence. Ta sytuacja sprawia, że jestem poirytowany i mam poczucie zmarnowanego czasu, kiedy chcę znaleźć dokładną specyfikację. Boję się, że coś zrobię źle, bo nie mam pewności, czy korzystam z najnowszej wersji dokumentacji. Chciałbym, żeby w dokumentacji panował porządek i żeby poszczególne dokumenty łatwo można było znaleźć. Zależy mi też na tym, żeby posiadać wszystkie informacje do skończenia funkcjonalności, bez konieczności szukania ich w kilku miejscach. Proszę, żebyś wprowadził porządek w dokumentacji, nie tylko po to, żeby można było łatwo się w niej odnaleźć, lecz także po to, żeby zyskać pewność, że wszystkie dokumenty są na swoim miejscu.



--- 
layout: image-right
image: /fakty.jpeg
---

# 1 - Spostrzeżenie

<v-click>

W dokumentacji, którą prowadzimy w ramach wspólnego projektu, nie ma systematyki. Opisy nie są sklasyfikowane, a w dodatku umieszczone zostały w pięciu miejscach w Confluence.

</v-click>

<v-clicks>

* suche fakty
* brak subiektywnej oceny

</v-clicks>

<!-- Jest to rzeczowe stwierdzenie faktu czy zachowania, pozbawione jakiejkolwiek oceny.
-->
---
layout: image-right
image: /feelings.jpeg
---

# 2 - Uczucia

<v-click>

Ta sytuacja sprawia, że jestem poirytowany i mam poczucie zmarnowanego czasu, kiedy chcę znaleźć dokładną specyfikację. Boję się, że coś zrobię źle, bo nie mam pewności, czy korzystam z najnowszej wersji dokumentacji.

</v-click>

<!-- Odnoszą się do odczuć, jakie wywołuje w nas spostrzeżone zachowanie. Może to być smutek, radość, lęk, ekscytacja czy irytacja.
-->

---
layout: image-right
image: /needs.png
---

# 3 - Potrzeby

<v-click>

Chciałbym, żeby w dokumentacji panował porządek i żeby poszczególne dokumenty łatwo można było znaleźć. Zależy mi też na tym, żeby posiadać wszystkie informacje do skończenia funkcjonalności, bez konieczności szukania ich w kilku miejscach.

</v-click>

<!-- To potrzeby, które wynikają z uczuć, jakie dane zachowanie w nas budzi. --->


---
layout: image-right
image: /puss-in-boots.gif

---

# 4 - Prośba


<v-click>

Proszę, żebyś wprowadził porządek w dokumentacji, nie tylko po to, żeby można było łatwo się w niej odnaleźć, lecz także po to, żeby zyskać pewność, że wszystkie dokumenty są na swoim miejscu.

</v-click>

<!-- Wyraża prośbę o konkretne działanie drugiej osoby, które ma zaspokoić nasze potrzeby. --->
---
layout: image-right
image: /non-violent.jpeg
---

# NVC

<v-clicks>

1. Spostrzeżenie -> Fakty
2. Uczucia -> Co to powoduje dla Ciebie/zespołu/projektu?
3. Potrzeby -> Oczekiwania co do zmiany
4. Prośba -> Jakie działanie chcesz, żeby zostało podjęte?

</v-clicks>

---
layout: statement
---

## Kiedy każda ze stron słyszy krytykę, diagnozę albo interpretację swojego zachowania, wówczas zużywa energię na samoobronę i oskarżenia, zamiast kierować się ku rozwiązaniom, które zaspokajają potrzeby.

~ Marshall B. Rosenberg

---
layout: full
---

# Code review #1

<img src="/statement.png" style="width: 100%; margin-top: 16px; object-fit: cover;">

<v-click>

NVC: Jest to komponent, używany w wielu miejscach wdrożony zgodnie z design systemem. Boję się, że ekrany, które go używają przestaną się dobrze wyświetlać. Chciałbym, zeby po zmianach komponent działał tak samo jak wcześniej. Ustaw proszę, żeby komponent domyślnie  miał takie same propsy jak wcześniej.

</v-click>

<v-click>

Krótka wersja: Jest to komponent, używany w wielu miejscach. Akualnie został zmieniony domyślny props z 1 na 2. Zmień proszę domyślną wartość z powrotem na 1, bo inaczej ekrany, które go używają przestaną się dobrze wyświetlać.

</v-click>


---
layout: full
---

# Code review #2

<img src="/feeling.png" style="width: 100%; margin-top: 16px; object-fit: cover;">

<v-click>

NVC: Wartości propsa variant nie są zgodne z design systemem. Chciałbym, zebyśmy mieli spójność miedzy designem, a kodem, ponieważ łatwiej będzie nam monitorować zmiany. Zmień proszę nazwy wariantów na te, które są zgodne z design systemem: primary i secondary.

</v-click>

---
layout: image-right
image: /long-code-review.webp
---

# Code review #3

<v-click>
 
To powinien być pair programming

</v-click>

---
layout: full
---

# Code review #4

<img src="/abandoned.png" style="width: 100%; margin-top: 16px; object-fit: cover;">


---
layout: full
---

# Code review #5

<img src="/change-it.webp" style="width: 100%; margin-top: 16px; object-fit: cover;">

<v-click>

Aktualnie mamy jeden ekran z nawigacją i nawigatory między ekranami. Będzie to się mylić jak dojdzie nam więcej komponentów od nawigacji i więcej navigatorów. Chciałbym, aby nazwy jasno wskazywały odpowiedzialność i moduł z aplikacji. Zmieńmy proszę nazwę tego Navigatora na MapScreenNavigation.
</v-click>


---
layout: full
---

# Code review #6

<img src="/technical.webp" style="width: 100%; margin-top: 16px; object-fit: cover;">


---
layout: full
---

<video controls autoplay>
  <source src="/project.mp4" type="video/mp4">
</video>

---
layout: statement
---

# Kiedy to nie działa?

---
layout: image-right
image: /glaskologia.webp
---

# Głaskologia

<v-clicks>

- Głaski -> pochwały, komplementy
- Kiedy, jak dawać?
- Czemu technika "kanapki" nie działa?

</v-clicks>

---
layout: image-right
image: /chocolade.jpg
---

# Gorąca czekolada

<!-- Kazdy pozytywny feedback, i to co pozytywnego Ci się przydarzy napełnia kubek z gorącą czekoladą. 
Kazdy feedback, który dajesz to nalewasz ze swojej czekolady. Tak samo jak dostajesz negatywny feedback to "pijesz" swoją czekolade, zeby sie pozbierać -->

---
layout: image-right
image: /empty-cup.jpeg
---

# Gorąca czekolada

<!-- Kiedy wylejesz całość to juz nie ma z czego nalewac, wiec wtedy nie mamy siły zeby się podniesc. -->


---
layout: image-right
image: /chocolade.jpg
---

# Gorąca czekolada

<!-- Dlatego potrzebujemy czegos co pozwoli nam znow choc trochę dolac sobie tej goracej czekolady. -->

---
layout: full
---

# Key takeways

<v-clicks>

- Dobry feedback z code review powinien zawierać:
  - Fakty, dlatego trzeba to zmienić
  - Co to powoduje dla Ciebie/zespołu/projektu?
  - Oczekiwania co do zmiany
  - Jakie dokładne działanie chcesz, żeby zostało podjęte? 
- Stosuj pair programming dla szybszego feedbacku
- Pamiętaj o "głaskach", zeby feedback nie został zinterpretowany jako atak

</v-clicks>

---
layout: full
---

# Źródła
- "Porozumienie bez przemocy" Marshall B. Rosenberg
- "Głaskologia" - Miłosz Brzeziński

---
layout: statement
---

# Q&A