---
layout: default
---

<script type = "text/javascript">

    function zeFunction() {
    
          var myArray = [
          "This is a quote, apparently. -KVS",
          "I hate sand. - Anakin Skywalker",
          "As the great Sun Tzu once said, the supreme art of war lies in defeating the enemy without facing him. -MudFlaps", 
          "He travels the fastest who travels alone.- Rudyard Kipling",
          "I think therefore I am. - René Descartes",
          "Knowledge is power. -Francis Bacon",
          "Not all those who wander are lost. - J.R.R. Tolkien",
          "Nothing is certain except for death and taxes. -Benjamin Franklin",
          "What doesn't kill us makes us stronger. - Friedrich Nietzsche",
          "United we stand, divided we fall. - Aesop",
          "Two roads diverged in a wood, and I, I took the one less travelled by, and that has made all the difference. -Robert Frost",
          "Violence is never the answer. It is a question, and the answer is YES! - KVS",
          "Speak softly and carry a big stick -Theodore Roosevelt",
          "That is one small step for a man, a giant leap for mankind. - Neil Armstrong",
          "I'm gonna make him an offer he can't refuse. -  Vito Corleone",
          "Fathers send their sons to college either because they went to college or because they didn't. - L.L. Henderson",
          "We hope that, when the insects take over the world, they will remember with gratitude how we took them along on all our picnics. - Bill Vaughan ",
          "There cannot be a crisis next week. My schedule is already full. - Henry Kissinger",
          "The great French Marshall Lyautey once asked his gardener to plant a tree. The gardener objected that the tree was slow growing and would not reach maturity for 100 years. The Marshall replied, 'In that case, there is no time to lose; plant it this afternoon!' -John F. Kennedy ",
          "Politics is the art of the possible. - Otto von Bismarck",
          "Literature is an occupation in which you have to keep proving your talent to people who have none. - Jules Renard",
          "War is an ugly thing, but not the ugliest of things. The decayed and degraded state of moral and patriotic feeling which thinks that nothing is worth war is much worse. The person who has nothing for which he is willing to fight, nothing which is more important than his own personal safety, is a miserable creature and has no chance of being free unless made and kept so by the exertions of better men than himself. - John Stuart Mill",
          "When everyone is somebody, then no one's anybody. - W.S. Gilbert",
          ""Children speak in the field what they hear in the house. - Scottish folk saying",
          "You can evade life, but you can not evade Death. - T.S. Elliot",
          " ",
          ];
  
          var randomIteem = myArray[Math.floor(Math.random()*myArray.length)];
          document.getElementById("randomIteem").innerHTML =randomIteem
         }
    
    </script>
<h1>Click the button in order to roll a random quote!</h1>

<button onclick="zeFunction()">Roll a quote!</button>
## And sayeth the oracle:
<span id = randomIteem>"---"</span>
