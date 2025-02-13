---
layout: default
title: Exam Results
permalink: /exam-results/
---


    <h2>Verifica Risultati Appello</h2>
    
    <label>Insegnamento:</label>
    <select  id="insegnamento"  >
        <option value="algoritmi">Algoritmi e Strutture Dati (LP)</option>
        <option value="finf">Fondamenti di informatica</option>
    </select>
    <br><br>
    
    <label>Data Appello:</label>
    <input type="date" id="dataAppello" value="2025-02-11"><br><br>
    
    <label>Matricola:</label>
    <input type="text" id="matricola" value="1080685"><br><br>
    
    <button onclick="cercaRisultati()">Cerca</button>

    <h3>Risultati:</h3>
    <p id="output"></p>

    <table border="1" id="resultTable" style="display: none;">
        <thead>
            <tr id="tableHeader"></tr>
        </thead>
        <tbody>
            <tr id="tableRow"></tr>
        </tbody>
    </table>

    <script>
        function cercaRisultati() {
            var insegnamento = document.getElementById("insegnamento").value;
            var dataAppello = document.getElementById("dataAppello").value;
            var matricola = document.getElementById("matricola").value;

            var url = "https://script.google.com/macros/s/AKfycbxIhbePxyHruJJmxNYmKsed2nOzitbtvCkYH5KOnxPT7p0FRJpOMaQGOq6Kkyct0_4b/exec" + 
                      "?insegnamento=" + encodeURIComponent(insegnamento) + 
                      "&dataAppello=" + encodeURIComponent(dataAppello) + 
                      "&matricola=" + encodeURIComponent(matricola) + 
                      "&callback=handleResponse";
            console.log(url);

            
            fetch(url, { redirect: 'follow' })
                .then(response => response.json())
                .then(data => {
                    console.log(data);
                    if (data.status == "error") {
                        document.getElementById("output").innerText = "Errore: " + data.data.error;
                    } else {
                        //document.getElementById("output").innerText = "Risultati trovati: " + data.data.risultati.join(", ");
                        visualizzaTabella(data.data.risultati);
                    }
                })
                .catch(error => {
                    document.getElementById("output").innerText = "Errore nel recupero dei dati: " + error;
                });
            /*
            var script = document.createElement("script");
            script.src = url;
            document.body.appendChild(script);
            */
        }

        function visualizzaTabella(dati) {
            var headers = dati[0];  // Prima riga: intestazioni
            var values = dati[1];   // Seconda riga: valori

            var tableHeader = document.getElementById("tableHeader");
            var tableRow = document.getElementById("tableRow");

            // Svuota la tabella prima di riempirla
            tableHeader.innerHTML = "";
            tableRow.innerHTML = "";

            // Popola gli header della tabella
            headers.forEach(header => {
                var th = document.createElement("th");
                th.innerText = header;
                tableHeader.appendChild(th);
            });

            // Popola i valori della tabella
            values.forEach(value => {
                var td = document.createElement("td");
                td.innerText = value;
                tableRow.appendChild(td);
            });

            // Mostra la tabella
            document.getElementById("resultTable").style.display = "table";
        }        

        function handleResponse(data) {
            if (data.error) {
                document.getElementById("output").innerText = "Errore: " + data.data.error;
            } else {
                document.getElementById("output").innerText = "Risultati: " + JSON.stringify(data.data.risultati);
            }
        }
    </script>