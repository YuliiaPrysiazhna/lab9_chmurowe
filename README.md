# Laboratorium 9

## Wykonała: Yuliia Prysiazhna

##Grupa: TI6.2

### Podczas laboratorium zostały stworzone 4 kontenera:
- jeden kontener dla Nginx,
- jeden kontener dla PHP,
- jeden kontener dla MySQL,
- jeden kontener dla phpMyAdmin.

### Żeby uróchomić kontenery trzeba wykorzystać polecenie:

`docker compose up -d`

Potem możemy sprawdzić jakie kontenery są uruchomione za pomocą polecenia: 

`docker compose ps`

Mamy utworzone oraz uruchomione 4 kontenery:

![image](https://user-images.githubusercontent.com/103123474/168905271-755c1a1b-880f-4f3a-92c8-0f3827a48909.png)


Przy otworzeniu localhoost:8080 możemy wejść do PhpMyAdmin:

-login: root

-hasło: root

![image](https://user-images.githubusercontent.com/103123474/168905128-de362dff-a6fb-4802-82aa-8dea86b68549.png)

Możemy zatrzymać nasze kontenery za pomocą polecenia: 

`docker compose stop`

Zrestartować kontenery za pomocą polecenia:

`docker compose restart`

Możemy zatrzymać i/lub zniszcz pojemniki i ich objętość za pomocą polecenia:

`docker compose down -v`
