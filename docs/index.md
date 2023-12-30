# Witam na oficjalnej stronie Parcour Autistic Assistas Group

Jest to strona poświęcona wyjściom, spotkaniom i wypadom sportowym.

![Open Modal](https://kfaryn.github.io/strona/img/add.JPG){: .modal-trigger }

<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal()">&times;</span>
    <img src="https://kfaryn.github.io/strona/img/add.JPG" alt="Modal Image" style="max-width: 100%; max-height: 100%; display: block; margin: 0 auto;">
  </div>
</div>

<script>
  // Funkcja otwierająca modal
  function openModal() {
    document.getElementById('myModal').style.display = 'block';
  }

  // Funkcja zamykająca modal
  function closeModal() {
    document.getElementById('myModal').style.display = 'none';
  }

  // Funkcja sprawdzająca przewinięcie strony
  window.onscroll = function() {
    var modalTrigger = document.querySelector('.modal-trigger');
    var modalPosition = modalTrigger.offsetTop;
    
    // Jeżeli użytkownik przewinął stronę w dół, a modal nie jest otwarty, to otwórz modal
    if (window.scrollY > modalPosition && document.getElementById('myModal').style.display !== 'block') {
      openModal();
    }
  };
</script>


## Cel strony

Celem tej strony jest sprawdzenie jak trudno tworzy się takie rzeczy, oraz jest to jeden z celów edukacyjnych przedmiotu na uczelni.

```markdown
Poniżej prezentowane są sekcje, gdzie każdy może kliknąć i zobaczyć czy nie
szykuje się coś nowego. Dodatkowo jest dedykowana zakładka dla najlepszego.
Jak to mówią "Tyrtum pyrtum"!
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

