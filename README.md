# O projekcie

Ten projekt zawiera kod prostej aplikacji do korekcji perspektywy służącej jako demo wykorzystania Pythona do cyfrowego przetwarzania obrazów.

Działanie aplikacji omawiam na minikursie InterTech Academy dostępnym pod tym linkiem: https://www.udemy.com/user/maciej-kraszewski-3/


## Jak zainstalować i uruchomić kod?

### Instalacja:
1. Sklonuj repozytorium z serwisu GitHub: git clone https://github.com/mackrasz/minicourse_python_imgproc
2. Utwórz wirtualne środowisko Pythona: python -m venv venv
3. Aktywuj wirtualne środowisko: venv\Scripts\activate
4. Zainstaluj pakiety NumPy i Opencv: pip install numpy opencv-python

Zamiast kroków 2 - 4 możesz też uruchomić skrypt install.bat, który zawiera wszystkie powyższe komendy.

### Uruchomienie:
python input_file_name output_file_name

Po uruchomieniu programu zaznacz cztery narożniki fragmentu obrazu, którego perspektywę chcesz skorygować zgodnie z ruchem wskazówek zegara.