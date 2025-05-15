# TicTacToe - README - demickk

To prosty skrypt w JavaScript, który umożliwia grę w kółko-krzyżyk dla dwóch osób na planszy 3x3.

## Jak korzystać ze skryptu?

Po uruchomieniu skryptu pojawi się plansza o wymiarach 3x3 (9 pól). Gracze na zmianę umieszczają swoje znaki (X lub O), a po zakończeniu gry, jeśli jeden z graczy wygra, skrypt wyświetli komunikat z informacją o zwycięzcy oraz oznaczy zwycięskie pola czerwoną linią.

## Jakie *funkcje* zawiera skrypt?

* **createBoard()** – Tworzy planszę 3x3 do gry.
* **handleCellClick(event)** – Obsługuje kliknięcie na pole, umieszczając odpowiedni znak gracza (w zależności od tury). Sprawdza również, czy doszło do wygranej, remisu, lub zmiany gracza.
* **checkWin()** – Sprawdza, czy któryś z graczy spełnił warunki wygranej, porównując możliwe kombinacje wygranych.
* **drawWinningLine()** – Rysuje linię na planszy, wskazując pola, które doprowadziły do wygranej.
* **resetGame()** – Resetuje grę, czyszcząc planszę i przygotowując ją na nową rozgrywkę.

## Jakie *zmienne globalne* są używane w skrypcie?

* ***board*** – Element HTML zawierający planszę.
* ***messageTur*** – Element HTML, w którym wyświetlane są informacje o turze.
* ***resertBtn*** – Element HTML zawierający przycisk do resetowania gry.
* ***currentPlayer*** – Zmienna wskazująca na aktualnego gracza.
* ***gameBoard*** – Tablica przechowująca stan planszy.
* ***winningCombo*** – Tablica zawierająca wszystkie możliwe zwycięskie kombinacje.
* ***gameOver*** – Zmienna wskazująca, kiedy gra się kończy.
