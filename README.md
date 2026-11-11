# Giulio MoneyLAB — demo pubblica di navigazione

Anteprima **statica** del menu MoneyLAB con 5 sezioni e 22 sottomenu.
Nessun collegamento a OpenClaw, Telegram Bot API, portafoglio, prezzi, ordini, backend o API a pagamento.
Non contiene token, password o segreti.

## Pubblicazione gratuita con GitHub Pages

1. Crea un repository GitHub **pubblico** separato, ad esempio `moneylab-miniapp-preview`.
2. Metti `index.html`, `.nojekyll` e `README.md` nella root di `main`.
3. Vai in **Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save**.
4. Apri l'indirizzo HTTPS indicato dalla pagina Settings > Pages.

Per aprire la demo da Telegram, condividi l'URL HTTPS in una chat; per configurare il pulsante del bot, valuta BotFather `/setmenubutton` solo dopo aver confermato che si tratta di una demo pubblica.

## Sicurezza e limiti

- Questo è un sito pubblico: **non** aggiungere token BotFather, chiavi API, dati clienti, dati personali o del portafoglio.
- L'interfaccia non autentica gli utenti e non offre accesso alle funzioni operative.
- Gli utenti potranno soltanto navigare tra i menu.
- Non pubblicare il vecchio pacchetto completo offline con la configurazione OpenClaw e i moduli backend.
- Per l'uso reale serve un backend protetto separato, con verifica `initData` Telegram sul server, controllo costi, sessioni isolate, audit, e una verifica di sicurezza prima del collegamento a OpenClaw.
- Questo repository non serve per monetizzazione; il futuro dominio Hostinger può essere dedicato a un servizio diverso.