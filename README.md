# Radix Workshop - Example 1 (WWW & Echo)

Purpose - a simple two module app. The public front-end (www) will respond to requests, request data from the non-public echo module - and echo the data back to the requestor. All magic!
 
## Content

- ```echo``` contains the echo module
- ```www``` contains the www front-end
- ```docs``` contains the workshop script ([link](./docs/workshop.md))

## A conceptual overview of the application.

![Conseptual diagram](./docs/smalldiagram.png)


## Notater av Marita under kurset
- måtte fjerne proxy settingene i docker (authproxy.statoil.net:8080 tror jeg det var.....må verifisers)
- for å kjøre echo og www appene sammen i hver sin container, så må du på katalog over også kjøre 
- > docker-compose build
- deretter > docker-compose up

- Når du starter på radix ....
- Endre navnet i toppen av meadata -> name i  radixconfig.yaml
