# Klasyfikacja dojrzałości owoców

Celem niniejszego projektu jest opracowanie systemu do **klasyfikacji dojrzałości owoców** przy wykorzystaniu technik uczenia maszynowego.
Dzięki zastosowaniu algorytmu konwolucyjnej sieci neuronowej (CNN) oraz bibliotek TensorFlow i Keras, projekt ten ma na celu stworzenie modelu klasyfikacji.

Klasyfikacja owoców polega na przypisaniu danego owocu do odpowiedniej kategorii na podstawie jego cech, takich jak kolor, kształt, tekstura i stopień dojrzałości. Działanie algorytmu CNN opiera się na ekstrakcji cech z obrazów i nauki hierarchicznej reprezentacji danych. Sieć neuronowa składa się z wielu warstw, w tym warstw konwolucyjnych, które analizują lokalne wzorce w obrazach, oraz warstw poolingowych, które redukują rozmiar przestrzenny danych. Następnie dane przekazywane są do w pełni połączonych warstw, które służą do końcowej klasyfikacji.

Algorytm CNN wykorzystuje zbiór treningowy, który składa się z oznaczonych obrazów owoców różnej dojrzałości. Podczas treningu sieć neuronowa dostosowuje wagi swoich połączeń tak, aby jak najlepiej odwzorować zależności między cechami a przypisaną dojrzałością owoców. Po przeprowadzeniu treningu, model jest testowany na zbiorze testowym, aby ocenić jego zdolność do poprawnej klasyfikacji nowych, nieznanych obrazów owoców.
