# Grupa: Wyzwania w przetwarzaniu danych obrazowych MRI mózgu

## Prowadzący
Bartosz Kochański

## Ogólna koncepcja
-	uczestnicy będą replikowali wyniki jednego z dwóch otwartych wyzwań: BraTS Challenge (segmentacja glejaków) lub OpenBHB Challenge (predykcja wieku biologicznego mózgów osób zdrowych)
-	Zajęcia rozpoczną się od wprowadzenia do charakteru danych, sposobów przetwarzania wstępnego i modelowania (4 zajęcia). Po zajęciach warsztatowych wysyłane będą proste prace domowe żeby upewnić się, że uczestnicy przyswoili praktycznie materiał.
-	Kolejne zajęcia (10) będą się składać z omawiania trudności zgłaszanych na bieżąco przez uczestników we wdrażaniu projektu lub zajęć hands-on nt. szczegółów obsługi konkretnych toolboxów. Uczestnicy mają opcjonalnie możliwość zaprezentować samodzielnie obsługę jednego z narzędzi i podzielić się swoimi doświadczeniami z obsługi – za dodatkowe punkty. Jeśli wszystkie zespoły zgłoszą się do hands-on (max. 5 bloków zajęciowych) – pozostaje min. 5 wolnych bloków na konsultacje problemów.
-	Ostatnie zajęcia poświęcone są na prezentacje wyników każdego z zespołów.

## Tematyka zajęć:

### Warsztaty 1: Wprowadzenie do MRI mózgu.
-	Przeglądanie danych wolumetrycznych przy pomocy przeglądarki MRIcroGL.
-	Przedstawienie obrazu zdrowego mózgu w reprezentacji podstawowych sekwencji klinicznych: T1, T1c, T2, FLAIR. Omówienie podłoża różnic poziomów jasności między sekwencjami.
-	Przykłady patologii i zmian zachodzących z wiekiem (uczestnicy przeglądają samodzielnie obrazy, najpierw sami wskazują regiony zainteresowania przy pomocy współrzędnych, potem omówienie)

Dwa zadania: ocena starzenia struktury mózgu na przykładzie sekwencji T1. Obraz glejaków w sekwencjach T1, T1c, T2, FLAIR. Przykład zmian widocznych tylko na wybranych sekwencjach.

Praca domowa: wysłać współrzędne guza mózgu w wysłanym przez prowadzącego 	wolumenie mózgu. Załączyć zrzut ekranu z przeglądarki.

### Warsztaty 2: Dane i preprocessing

-	otwarte źródła danych MRI: BraTS Challenge, OpenBHB. Jakie obrazy i metadane są dostępne. Sposoby dostępu do danych.
-	formaty plików NIfTI i DICOM. Omówienie struktury, narzędzi I/O i uzupełnienie informacji dot. przeglądarek.
-	przygotowanie danych surowych do modelowania przy pomocy otwartych pipeline'ów: BraTS Toolkit.
-	Ekstraktory cech: segmentacja istoty szarej przy pomocy toolboxa CAT12 z pakietu SPM. Generacja tabelarycznych cech wolumetrycznych przy pomocy narzędzi FreeSurfer/FastSurfer.

Praca domowa 1: Wyślij wartość z komórki o zadanych współrzędnych z tablicy wewnątrz 	wysłanego pliku NifTI.

Praca domowa 2: Wyślij zawartość zadanego pola metadanych z wysłanego pliku DICOM.

###	Wasztaty 3: Modelowanie

-	Sieci neuronowe operujące na danych 3D
-	do segmentacji wolumetrycznej
-	do predykcji wieku

Praca domowa: wysłać predykcję wieku lub segmentację guza dla wysłanego przez 	prowadzącego badania.

### Warsztaty 4: Wstęp do projektu

-	Omówienie wyzwań BraTS i OpenBHB. Wskazanie istotnych stron internetowych, repozytoriów, kodu baseline’owego do ulepszania itd.

Praca domowa: założenie repozytorium git projektu grupowego i udostępnienie zawartości prowadzącemu!


