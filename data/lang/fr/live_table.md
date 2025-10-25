---


---

<h1 id="live-visu">Live Visu</h1>
<p>Ce tableau affiche une ligne pour chaque nœud connecté au réseau maillé.<br>
Un click sur une ligne ouvre un graphique détaillant le nœud.</p>
<h2 id="colonnes-">Colonnes :</h2>
<ul>
<li><strong>Name</strong> : Emplacement physique du nœud. Correspond au paramètre <strong>NI</strong> (Node Identifier)</li>
<li><strong>T-int</strong> : Température intérieure</li>
<li><strong>H-int</strong> : Humidité intérieure</li>
<li><strong>T-ext</strong> : Température extérieure (si capteur connecté)</li>
<li><strong>V-bat</strong> : Tension électrique de la batterie, en Volts. Uniquement si le nœud est en <strong>mode dormant</strong></li>
<li><strong>Power</strong> : Identique à V-bat</li>
<li><strong>State</strong> : Indique si le nœud est <strong>en ligne</strong> (vert) ou <strong>hors ligne</strong> (rouge). Se base sur le paramètre <code>frq</code> configuré et correspondant à la fréquence d’envoi (ou de réveil) du nœud. Passera rouge si le nœud n’a pas envoyé ces données dans les temps.</li>
<li><strong>Last</strong> : Dernières données reçues du nœud</li>
</ul>
<p>Le tableau est rafraichi entièrement à chaque fois qu’un nouveau paquet est reçu.</p>

