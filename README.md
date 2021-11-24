# WP pivo countdown

Jednoduché JS odpočítávadlo na WP piva, stačí nastavit:

* `eventDate` - datum eventu ve formátu `November 24, 2021`
* `schedule` - seznam objektů s následujícími vlastnostmi:
    ```js
    {
        id: "schedule-1",
        author: "Karolína Vyskočilová",
        title: "Opening & WP News",
        time: "18:30"
    }
    ```

Odpočítávadlo a aktivní položka programu se zbarví automaticky, vždy je tam přechodových 5 minut na začátku, kdy se nezobrazuje odpočítávadlo.
