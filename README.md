# Analityk-Rynku-nieruchomosci

Dominik Kuraś
Nikolas Kida
Kamil Kopczyk

AI2
ISI
PI

wersja 3.0.5
instalacja wsl z PS
wsl --install

wersja 4.99
Pobranie dockera z https://docs.docker.com/desktop/setup/install/windows-install/

uruchomienie
docker compose up -d

zamykanie / wylaczenie
docker compose down

logi
docker logs analityk_python / laravel

instalacja laravela

docker compose run --rm --no-deps laravel bash -c "composer create-project laravel/laravel:^13.0 temp_app && shopt -s dotglob && mv temp_app/\* . && rm -rf temp_app"
