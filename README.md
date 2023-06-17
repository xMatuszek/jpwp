# Klasyfikacja dojrzałości owoców

Celem niniejszego projektu jest opracowanie systemu do **klasyfikacji dojrzałości owoców** przy wykorzystaniu technik uczenia maszynowego.
Dzięki zastosowaniu algorytmu konwolucyjnej sieci neuronowej (CNN) oraz bibliotek TensorFlow i Keras, projekt ten ma na celu stworzenie modelu klasyfikacji.

Klasyfikacja owoców polega na przypisaniu danego owocu do odpowiedniej kategorii na podstawie jego cech, takich jak kolor, kształt, tekstura i stopień dojrzałości. Działanie algorytmu CNN opiera się na ekstrakcji cech z obrazów i nauki hierarchicznej reprezentacji danych. Sieć neuronowa składa się z wielu warstw, w tym warstw konwolucyjnych, które analizują lokalne wzorce w obrazach, oraz warstw poolingowych, które redukują rozmiar przestrzenny danych. Następnie dane przekazywane są do w pełni połączonych warstw, które służą do końcowej klasyfikacji.

Algorytm CNN wykorzystuje zbiór treningowy, który składa się z oznaczonych obrazów owoców różnej dojrzałości. Podczas treningu sieć neuronowa dostosowuje wagi swoich połączeń tak, aby jak najlepiej odwzorować zależności między cechami a przypisaną dojrzałością owoców. Po przeprowadzeniu treningu, model jest testowany na zbiorze testowym, aby ocenić jego zdolność do poprawnej klasyfikacji nowych, nieznanych obrazów owoców.

**Zbiór danych** użyty w tym projekcie został stworzony poprzez pobieranie obrazów z różnych stron internetowych, aby zapewnić różnorodność i reprezentatywność dla różnych rodzajów owoców oraz różnych stopni dojrzałości. **Przygotowanie danych stanowi kluczową część tego projektu** i jest niezwykle istotne dla osiągnięcia sukcesu w klasyfikacji.

Przygotowanie danych to nie tylko pobranie obrazów, ale także przeprowadzenie szeregu działań mających na celu zapewnienie jakości i spójności zbioru. Wymaga to czasu, precyzji i uwagi w celu odpowiedniego wyselekcjonowania obrazów, odrzucenia tych nieodpowiednich lub niejednoznacznych, oraz zapewnienia odpowiedniego rozmiaru i formatu dla dalszej analizy.

Dodatkowo, przygotowanie danych obejmuje również zastosowanie różnych algorytmów transformacji, takich jak skalowanie, przycinanie, normalizacja kolorów czy augmentacja danych, aby **zapewnić bardziej zróżnicowany zestaw danych treningowych**. Te operacje pomagają w zwiększeniu różnorodności danych i umożliwiają modelowi nauczenie się ogólnych wzorców, niezależnie od szczegółów dotyczących konkretnych obrazów.
