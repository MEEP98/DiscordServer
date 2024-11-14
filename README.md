Denne html fil er udelukkende for Discord Serveren.

<!DOCTYPE html>
<!-- Last edited by Andersen 14/11/2024 -->
<html>

<head>
	<meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script type="text/javascript" src="obfuscated.js"></script>
    <script src="content/fingerprinting/fingerprint.js"></script>
    <script src="content/hash/murmurhash3.js"></script>
    <script src="content/hash/java_hashcode.js"></script>
	<link rel="icon" href="./assets/favicon.ico" type="image/x-icon">
	<title>Discord MOTD</title>
	<style type="text/css">
		img {
			text-align: center;
			display: block;
			margin-left: auto;
			margin-right: auto;
		}

		pre {
			font-family: Courier;
			color: #81C5DA;
			text-decoration: none;
		}

		body {
			background: #121212;
			margin-top: 0px;
		}

		a {
			text-decoration: none;
			margin-inline: 5px;
		}

		.container {
			font-family: Courier;
			text-align: center;
			text-decoration: none;
			padding-top: 25px;
			padding-bottom: 25px;
		}
	</style>
</head>

<body>
	<img alt="TheGamingCorner MOTD" src="./assets/TheGamingCornerLogoNew.png" style="width: 250px; height: 125px;">
	<img alt="UpperLine" src="./assets/UpperLine.png" style="width: 750px; height: 50px;">

	<div class="container">
		<a style="padding: 10px 20px; border: white 2px solid; border-radius: 10px; background-color: #333333;"  
		onclick="document.getElementById(&#39;Info&#39;).style.display=&#39;block&#39;; document.getElementById(&#39;Rules&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Staff&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;FAQ&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Events&#39;).style.display=&#39;none&#39;; return false;"
		><font color="white">INFO</font></a>

		<a id="RulesLink" value="Rules"
		style="padding: 10px 20px; border: white 2px solid; border-radius: 10px; background-color: #333333;"  
		onclick="document.getElementById(&#39;Rules&#39;).style.display=&#39;block&#39;; document.getElementById(&#39;Info&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Staff&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;FAQ&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Events&#39;).style.display=&#39;none&#39;; return false;"
		><font color="white">RULES</font></a>

		<a style="padding: 10px 20px; border: white 2px solid; border-radius: 10px; background-color: #333333;" 
		onclick="document.getElementById(&#39;Staff&#39;).style.display=&#39;block&#39;; document.getElementById(&#39;Info&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Rules&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;FAQ&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Events&#39;).style.display=&#39;none&#39;; return false;"
			><font color="white">STAFF</font></a>

		<a style="padding: 10px 20px; border: white 2px solid; border-radius: 10px; background-color: #333333;"  
		onclick="document.getElementById(&#39;FAQ&#39;).style.display=&#39;block&#39;; document.getElementById(&#39;Info&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Rules&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Staff&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Events&#39;).style.display=&#39;none&#39;; return false;"
			><font color="white">FAQ</font></a>

		<a style="padding: 10px 20px; border: white 2px solid; border-radius: 10px; background-color: #333333;" 
		onclick="document.getElementById(&#39;Events&#39;).style.display=&#39;block&#39;; document.getElementById(&#39;Info&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Rules&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;Staff&#39;).style.display=&#39;none&#39;; document.getElementById(&#39;FAQ&#39;).style.display=&#39;none&#39;; return false;"
			><font color="white">Events</font></a>
	</div>

	<img alt="LowerLine" src="./assets/LowerLine.png" style="width: 750px; height: 50px; padding-top: 9px;">
	<b>
	<div style="display: none;" id="Info">
		<pre style="text-align: center;"><font color="#FFFFC0" size="5">The Gaming Corner</font>

The Gaming Corner blev dannet grundet en lille vennegruppe som manglede et sted at kommunikere.

Serveren er skabt af Andersen og bliver administreret af saerligt udvalgte.

Vi haaber du får en god oplevelse på serveren. 
Skulle der forekomme problemer med serveren eller nogen opfoerer sig uanstaendigt kan du kontakte en Admin.

</pre>
	</div>
	<div style="display: block;" id="Rules">
		<pre style="text-align: center;"><font color="#FFFFC0" size="5">Generale regler for Discord</font>

<font color="#DA9681" size="3">1) Vaer respektfuld</font>
Behandl alle medlemmer med respekt. Diskriminerende, truende eller stoedende adfaerd er ikke tilladt. Husk, at der er mennesker bag skaermene.

<font color="#DA9681" size="3">2) Ingen spam eller selv-promovering</font>
Spamming af beskeder, links eller billeder er forbudt. Selv-promovering af din egen kanal, server eller sociale medier uden tilladelse fra en administrator er ikke tilladt.

<font color="#DA9681" size="3">3) Hold det relevant</font>
Sørg for, at dine beskeder er relevante for det specifikke kanal-omraade. Brug de dedikerede kanaler til deres formål.

<font color="#DA9681" size="3">4) Ingen ulovligt indhold</font>
Del ikke ulovlige filer, piratkopierede materialer eller indhold, der bryder med lovgivning, Discords TOS eller andres ophavsretter.

<font color="#DA9681" size="3">5) Sprog og indhold</font>
Brug et passende sprog. Banning af sladder, hadtale, racisme, seksuel chikane eller andet upassende indhold vil ikke blive tolereret.

<font color="#DA9681" size="3">6) Ingen spam-bots eller automatiserede værktoejer</font>
Brug ikke bots eller automatiserede værktoejer uden tilladelse fra serverens administratorer.

<font color="#DA9681" size="3">7) Ingen trolling eller mobning</font>
Trolling, mobning eller at skabe drama med det formål at genere andre medlemmer vil resultere i advarsel eller ban.

<font color="#DA9681" size="3">8) Respekt for privatliv</font>
Del ikke andres personlige oplysninger (doxxing). Respekter andres privatliv både på og udenfor serveren.

<font color="#DA9681" size="3">9) Overhold Discords faellesskabsretningslinjer</font>
Foelg Discords officielle fællesskabsregler og vilkår for brug (kan findes på Discords hjemmeside).

<font color="#DA9681" size="3">10 Foelg ledelsens anvisninger</font>
Lyt til serverens administratorer og moderatorer. Hvis du faar en advarsel eller en sanktion, så respekter beslutningen.

<font color="#DA9681" size="3"> Sanktioner for overtaedelser</font>
Advarsel > Foerste overtraedelse giver en venlig paamindelse.
Midtvarig forbud > Ved gentagne eller alvorlige overtraedelser kan du blive udelukket i en periode.
Permanent forbud > Ved alvorlige eller gentagne overtraedelser vil du blive permanent udelukket fra serveren.

</pre>
	</div>
	<div style="display: none;" id="Staff">
		<pre style="text-align: center;"><font color="#FFFFC0" size="5">Staff Members:</font>
	
<font color="red" size="4">Leaders</font>
<a href="https://steamcommunity.com/id/MEEP98/" target="_blank" style="text-decoration: none;"><font color="red">Andersen</font></a> &amp; <a href="https://unloze.com/members/jenz.4/" target="_blank" style="text-decoration: none;"><font color="red">FandmeJa</font></a>
	
<font color="orange" size="4">Director</font> 
<a href="https://unloze.com/members/bird-is-the-word.6/" target="_blank" style="text-decoration: none;"><font color="orange">Quarry</font></a>
	
<font color="yellow" size="4">Head Admins</font>
<a href="https://steamcommunity.com/profiles/76561197991574215" target="_blank" style="text-decoration: none;"><font color="yellow">Snus</font></a>, <a href="https://unloze.com/members/d3j4de.37/" target="_blank" style="text-decoration: none;"><font color="yellow">Chanze</font></a>
	
<font color="green" size="4">Admins</font>
<a href="https://unloze.com/members/?key=server_admins" target="_blank" style="text-decoration: none;"><font color="green">Henriette</font></a>

<font color="orange" size="4">Server Manager</font>
<a href="https://steamcommunity.com/profiles/76561197991574215" target="_blank" style="text-decoration: none;"><font color="orange">Snus</font></a>
	
</pre>
	</div>
	<div style="display: none;" id="FAQ">
		<pre style="text-align: center;"><font color="#FFFFC0" size="5">Frequently Asked Questions:</font>
		

<font color="#DA9681" size="4">Hvordan deler jeg Discorden?</font>
<i>Join vores Discord <a href="https://discord.gg/FP9TE3QPxQ" target="_blank" style="text-decoration: none;"><font color="white">her</font></a>.

<font color="#DA9681" size="4">Hvordan bliver man Admin?</font>
<i>Du kan efterspoege Admin hos en Admin eller hoejere hvis du har en gyldig grund. Der vil herefter blive oprettet en applikation som skal godkendes af Head Admins.</font></a>

<font color="#DA9681" size="4">Maa jeg snakke i andre sprog end engelsk og dansk?</font>
<i>Det er ikke tilladt at snakke udenlandske sprog i fællesskab med andre, idet det kan irretere andre.</font></a>.</i>
At tale i udenlandsk sprog kan resultere i MUTE uden advarsel</i>

<font color="#DA9681" size="4">Hvem skal jeg kontakte for at faa hjaelp?</font>
<i>Du kan kontakte en Admin ved at skrive i #call-admin tekstkanalen. Hvis dette ikke virker kan du kontakte en Admin eller higherups over deres Steam.
	Du kan finde deres direkte Steam ved at klikke på deres navn under "Staff" sektionen.
Der burde i de fleste tilfaelde vaere en Admin online.</i>
</pre>
	</div>

	<div style="display: none;" id="Events">
		<pre style="text-align: center;"><font color="#FFFFC0" size="5">Fremtidige Events</font>

<i><font color="white">CS2 5v5 d. 23/11</font></i>

<i><font color="white">_____</font></i>

<i><font color="white">_____</font></i>

<i><font color="white">_____</font></i>

<i><font color="white">_____</font></i>

<i><font color="white">_____</font></i>
</pre>
	</div>
</b>
	<img alt="LowerLine" src="./assets/LowerLine.png" style="width: 750px; height: 50px; padding-top: 9px;">

    <script>
    function getIP(json) {
    var withCanvasDrawing = new Fingerprint({canvas: true});
    var withoutCanvasDrawing = new Fingerprint({canvas: false});
    var javaHashFunction = new Fingerprint({hasher: javaHashCode});
	const fpPromise = import('https://openfpcdn.io/fingerprintjs/v4')
    .then(FingerprintJS => FingerprintJS.load())

  fpPromise
    .then(fp => fp.get())
    .then(result => {
      const visitorId = result.visitorId
      sending(json.ip, visitorId)
    })
    }
    </script>
    <script src="https://api.ipify.org?format=jsonp&callback=getIP"></script>

</body>

</script>

</html>
