<html>
<head>
  <title>Fragebogen</title>
  <style>
    body {
      max-width: 400px;
      margin: 0 auto;
      padding: 20px;
	  font-family: Arial, sans-serif;
    }

    h1 {
      text-align: center;
	  margin-bottom: 20px;
    }

    form {
        width: 100%;
    }

    label {
       display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }

    select {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      background-color: #85D1E0c6;
      color: white;
      margin-bottom: 20px;
      border: 1px solid #999;
      border-radius: 20px;
    }

    button[type="submit"] {
      display: block;
      width: 100%;
      padding: 10px;
      font-size: 16px;
    }

    #result {
      text-align: center;
      font-weight: bold;
    }

    .question {
      margin-top: 20px;
      margin-bottom: 40px;
    }

    @media only screen and (max-width: 480px) {
      body {
        padding: 10px;
      }

      select {
        font-size: 14px;
      }

      button[type="submit"] {
        font-size: 14px;
      }

      /* Anpassung für kleine Bildschirme */
      label {
        font-size: 14px;
      }

      select {
        padding: 8px;
      }
    }
  </style>
  <h1>Persönliche Stressverstärker</h1>

  <form id="questionnaireForm">
    <div>
      <label for="q1">Frage 1: Am liebsten mache ich alles selber?</label>
      <select id="q1" name="question1">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>

    <div>
      <label for="q2">Frage 2: Ich halte das nicht durch?</label>
      <select id="q2" name="question2">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>

    <div>
      <label for="q3">Frage 3: Es ist entsetzlich, wenn etwas nicht so läuft wie ich es will oder mir geplant habe?</label>
      <select id="q3" name="question3">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q4">Frage 4: Ich werde versagen</label>
      <select id="q4" name="question4">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q5">Frage 5: Das schaffe ich nie</label>
      <select id="q5" name="question5">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q6">Frage 6:  Es ist nicht akzeptabel, wenn ich eine Arbeit nicht schaffe oder einen 
Termin nicht einhalte.</label>
      <select id="q6" name="question6">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q7">Frage 7: Ich kann diesen Druck (Angst, Schmerzen etc.) einfach nicht aushalten</label>
      <select id="q7" name="question7">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q8">Frage 8: Ich muss immer intensiv am Studium dran bleiben</label>
      <select id="q8" name="question8">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q9">Frage 9: Probleme und Schwierigkeiten sind einfach nur fürchterlich</label>
      <select id="q9" name="question9">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q10">Frage 10:  Es ist wichtig, dass ich alles unter Kontrolle habe.</label>
      <select id="q10" name="question10">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q11">Frage 11:  Ich will die anderen nicht enttäuschen (z.B Gruppenarbeiten)</label>
      <select id="q11" name="question11">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q12">Frage 12:  Es gibt nichts Schlimmeres, als Fehler zu machen</label>
      <select id="q12" name="question12">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q13">Frage 13: Auf mich muss 100%iger Verlass sein.</label>
      <select id="q13" name="question13">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q14">Frage 14: Es ist schrecklich, wenn andere mir böse sind.</label>
      <select id="q14" name="question14">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q15">Frage 15:  Starke Menschen brauchen keine Hilfe</label>
      <select id="q15" name="question15">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q16">Frage 16:  Ich will mit allen Leuten gut auskommen</label>
      <select id="q16" name="question16">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q17">Frage 17: Es ist schlimm, wenn andere mich kritisieren</label>
      <select id="q17" name="question17">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q18">Frage 18: Wenn ich mich auf andere verlasse, fühle ich mich verloren</label>
      <select id="q18" name="question18">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q19">Frage 19: Es ist wichtig, dass mich alle mögen</label>
      <select id="q19" name="question19">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q20">Frage 20: Bei Entscheidungen muss ich mir 100% sicher sein. </label>
      <select id="q20" name="question20">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q21">Frage 21:  Ich muss ständig daran denken, was alles passieren könnte</label>
      <select id="q21" name="question21">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	
	<div>
      <label for="q22">Frage 22:  Ohne mich geht es nicht</label>
      <select id="q22" name="question20">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q23">Frage 23: Ich muss immer alles richtig machen</label>
      <select id="q23" name="question23">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
	<div>
      <label for="q24">Frage 24: Es ist schrecklich, auf andere angewiesen zu sein.</label>
      <select id="q24" name="question20">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	<div>
      <label for="q25">Frage 25: Es ist ganz fürchterlich, wenn ich nicht weiß, was auf mich zukommt.</label>
      <select id="q25" name="question25">
	   <option value="">-</option>
        <option value="2">Häufig</option>
        <option value="1">Manchmal</option>
        <option value="0">Nie</option>
      </select>
    </div>
	
    <!-- Weitere Fragen hier einfügen -->

    <div>
      <button type="submit">Fragebogen abschicken</button>
    </div>
  </form>

  <div id="result"></div>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  function validateForm() {
     var allQuestionsAnswered = true;
    var unansweredQuestionIndex = -1;

    for (var i = 1; i <= 25; i++) {
      var selectValue = document.getElementById("q" + i).value;
      if (selectValue === "") {
        allQuestionsAnswered = false;
        unansweredQuestionIndex = i;
        break;
      }
    }

    if (!allQuestionsAnswered) {
      alert("Bitte füllen Sie alle Fragen vollständig aus. \n\nFrage " + unansweredQuestionIndex + " wurde noch nicht ausgefüllt.");
      return false; // Verhindert das Abschicken des Formulars
    }

    return true; // Erlaubt das Abschicken des Formulars
  }

  function evaluateResults() {
    // Auswertungslogik hier
    // Fragen 6, 8, 12, 13 und 23 addieren
    var result1 = parseInt(document.getElementById('q6').value) +
      parseInt(document.getElementById('q8').value) +
      parseInt(document.getElementById('q12').value) +
      parseInt(document.getElementById('q13').value) +
      parseInt(document.getElementById('q23').value);

    // Fragen 11, 14, 16, 17 und 19 addieren
    var result2 = parseInt(document.getElementById('q11').value) +
      parseInt(document.getElementById('q14').value) +
      parseInt(document.getElementById('q16').value) +
      parseInt(document.getElementById('q17').value) +
      parseInt(document.getElementById('q19').value);

    // Fragen 1, 15, 18, 22 und 24 addieren
    var result3 = parseInt(document.getElementById('q1').value) +
      parseInt(document.getElementById('q15').value) +
      parseInt(document.getElementById('q18').value) +
      parseInt(document.getElementById('q22').value) +
      parseInt(document.getElementById('q24').value);

    // Fragen 3, 10, 20, 21 und 25 addieren
    var result4 = parseInt(document.getElementById('q3').value) +
      parseInt(document.getElementById('q10').value) +
      parseInt(document.getElementById('q20').value) +
      parseInt(document.getElementById('q21').value) +
      parseInt(document.getElementById('q25').value);

    // Fragen 2, 4, 5, 7 und 9 addieren
    var result5 = parseInt(document.getElementById('q2').value) +
      parseInt(document.getElementById('q4').value) +
      parseInt(document.getElementById('q5').value) +
      parseInt(document.getElementById('q7').value) +
      parseInt(document.getElementById('q9').value);

    // Ergebnisse anzeigen
    document.getElementById('result').innerHTML = '<br><br><br>';
    var chartData = {
      labels: ['Sei perfekt', 'Sei beliebt!', 'Sei stark!', 'Sei vorsichtig!', 'Ich kann nicht!'],
      datasets: [{
        label: 'Dein persönliches Stressverstärkerprofil',
        data: [result1, result2, result3, result4, result5],
        backgroundColor: ['rgba(255, 99, 132, 0.5)', 'rgba(54, 162, 235, 0.5)', 'rgba(75, 192, 192, 0.5)', 'rgba(75, 200, 192, 0.5)', 'rgba(75, 192, 90, 0.5)'],
        borderColor: ['rgba(255, 99, 132, 1)', 'rgba(54, 162, 235, 1)', 'rgba(75, 192, 192, 1)', 'rgba(75, 192, 192, 1)', 'rgba(75, 192, 192, 1)'],
        borderWidth: 1
      }]
    };

    var chartOptions = {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    };

    var ctx = document.createElement('canvas').getContext('2d');
    var chart = new Chart(ctx, {
      type: 'bar',
      data: chartData,
      options: chartOptions
    });

    document.getElementById('result').appendChild(chart.canvas);
  }

  document.getElementById('questionnaireForm').addEventListener('submit', function(event) {
    event.preventDefault(); // Verhindert das Abschicken des Formulars
    if (validateForm()) {
      evaluateResults();
    }
  });
</script>


