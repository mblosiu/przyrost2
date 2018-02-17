Jak uruchomić:
1. Uruchomić w intellij.
2. Zapytania wprowadzać poprzez Postmana (np. GET	http://localhost:8080/api/positions/save/json/4)



Model danych znajduje się w klasach:
Address
Contact
Employee
Position

Zapytania znajdują się w klasach:
AddressController
ContactController
EmployeeController
PositionController

ZonedDateTime znajduje się w klasie Task, która ostatecznie nie została użyta w projekcie.


"Docelowy projekt powinien czytać i zapisywać zamodelowane dane z i do plików typu XML i JSON (obu typów!) i zapisywać/odczytywać je z bazy danych."
Serializacja znajduje się w klasach zapytań (AddressController, ContactController, EmployeeController, PositionController).
