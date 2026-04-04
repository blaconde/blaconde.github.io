## Walidacja danych adresowych (SQL + Python)

Projekt pokazujący podejście do pracy z danymi historycznymi i ich walidacji.

### Zakres:
- wybór aktywnych umów z danych historycznych (date_from / date_to)
- obsługa duplikatów i braków w danych
- wyznaczenie aktualnego klienta
- przygotowanie danych do walidacji adresu (NUTS)

### Podejście:
- funkcje analityczne (ROW_NUMBER, MAX OVER)
- logika biznesowa zamiast flag systemowych
- filtrowanie aktywności względem aktualnej daty

### Kod:
 [Zobacz SQL / Python](https://github.com/blaconde/data-analysis-snippets)

 👉 [Powrót do strony głównej](/)
