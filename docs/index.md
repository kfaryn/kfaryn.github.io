# Witam na oficjalnej stronie Parcour Autistic Assistas Group

Jest to strona poświęcona wyjściom, spotkaniom i wypadom sportowym.
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Strona z wyskakującym obrazem</title>
</head>
<body>

  <!-- Modal -->
  <div id="myModal" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal()">&times;</span>
      <img src="https://kfaryn.github.io/strona/img/add.JPG" alt="add" onclick="closeModal()">
    </div>
  </div>

  <!-- Skrypt JavaScript -->
  <script>
    // Funkcja otwierająca modal
    function openModal() {
      document.getElementById('myModal').style.display = 'block';
    }

    // Funkcja zamykająca modal
    function closeModal() {
      document.getElementById('myModal').style.display = 'none';
      
      // Zapisujemy informację o zamknięciu modala w localStorage
      localStorage.setItem('modalClosed', 'true');
    }

    // Funkcja sprawdzająca przewinięcie strony
    window.onscroll = function() {
      // Sprawdzamy, czy modal był już zamknięty wcześniej
      var isModalClosed = localStorage.getItem('modalClosed');
      
      // Jeżeli użytkownik przewinął stronę o 300 pikseli i modal nie był wcześniej zamknięty, to otwórz modal
      if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
        if (!isModalClosed) {
          openModal();
        }
      }
    };
  </script>

</body>
</html>

## Cel strony

Początkowo strona miała charakter humorystyczny z nastawieniem na rozwijanie umiejętności budowania strony.
Obecnie jest w fazie reorganizacji na przedstawianie wyników miniprojektów analitycznych związanych z moimi zainteresowaniami.
Więcej treści wkrótce ;)

```markdown
Poniżej prezentowane są sekcje, gdzie każdy może kliknąć i zobaczyć czy nie
szykuje się coś nowego. Dodatkowo jest dedykowana zakładka dla Najlepszego.
Zapraszam do klikania!
```

## Wyprawy oraz wyjścia sportowe

[Wyprawy piesze](https://kfaryn.github.io/strona/)

[Koszykówka/Siatkówka/Piłka nożna](https://kfaryn.github.io/strona/pilka/)

## Kręgle/Bilard

[Kręgle/ Bilard]()


## Planszówki

[Planowane planszówki](https://kfaryn.github.io/strona/planszowki/)

## Informacja dla Najlepszego

[Only Najlepszy can push this button](https://kfaryn.github.io/strona/img/najlepszy.jpg)

### Kontakt

Wszelkie skargi proszę pisać na messengerze. Ostatnio coraz częściej rzucam telefon po przyjściu
i przypominam sobie o nim po kilku godzinach, co doliczając czas szukania może oznaczać dłuższą
chwilę na uzykanie odpowiedzi. Proszę się nie poddawać! 
#### PS: Ty Tobiasz możesz dzwonić na komórkę :)

