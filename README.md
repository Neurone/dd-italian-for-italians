# Miglioramenti alla traduzione italiana di Darkest Dungeon

Revisioni e correzioni per la traduzione italiana di Darkest Dungeon.

Nella traduzione originale ad esempio "party" veniva tradotto con "partito", "build number" veniva tradotto con "costruiamo", ecc. :)

In aggiunta alle correzioni di traduzione, il mod contiene un elenco di poco più di 9.000 di nomi italiani che si vanno ad aggiungere ai 500 nomi standard, così che gli avventurieri abbiano dei nomi più familiari e pronunciabili per il popolo italico.

NOTA: Poiché i mod installati via Steam vengono applicati solamente dopo che si è scelta una campagna (con i relativi mod attivati) le modifiche alla traduzione per le voci del menu principale non vengono applicate (es. in alto a sinistra si vede ancora la voce "Costruzione" invece che "Versione").

## Come creare delle modifiche

Modificare i file all'interno della cartella 'mod'

## Come effettuo l'upload del mod su Steam

Se volete creare il vostro mod, potete utilizzare la guida ufficiale [Darkest Dungeon - Modding Guide [Official]](https://steamcommunity.com/sharedfiles/filedetails/?id=819597757)

Di seguito invece i passi che effettuo come proprietario del mod per aggiornarlo.

Dalla cartella `D:\Giochi\Steam\SteamApps\common\DarkestDungeon\_windows` eseguo il comando:

`steam_workshop_upload.exe "d:\Sviluppo\dd-italian-for-italians\mod\project.xml"`

Il programma di upload creerà da solo i file .loc necessari.

### Note varie
- Inserisco dentro "mod" tutto il progetto altrimenti Steam carica anche la cartella git nel repo.
- Le modifiche alla descrizione del mod è più comodo farle da Steam direttamente, per questo il tag <ItemDescription> dentro il file project.xml è vuoto
