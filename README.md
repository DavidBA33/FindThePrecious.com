<!DOCTYPE html>
<html>
<head>
	<title>FindTheprecious</title>
	<meta charset="utf-8">
</head>
<body>
	<header>
		<nav>
			<ul id="liens">
				<li><a href="#fellows">FindThePrecious.com</a></li>
				<li><a href="#fellows">Fellows</a></li>
				<li><a href="#ring">The Ring</a></li>
				<li><a href="#reward">Get my reward</a></li>
				<li><a href="#hunters">Best Hunters</a></li>
				<li><a href="#army">Join the army</a></li>
				<li><a href="#contact">Contact Us</a></li>
			</ul>
		</nav>

		<section id="intro">
			<img src="http://via.placeholder.com/740x140" alt="image intro">
			<h1>Dangerous fellowship try to destroy the ring</h1>
			<p>Orcs,Balrogs,protect your master Sauron!</p>
		</section>

		<section id="wanted">
			<p><span class="titre_wanted">Fellows wanted dead</span> (or alive if you want to eat them later)</p>
			<ul class="liens_wanted">
				<li class="most_wanted"><a href="#">Most wanted</a></li>
				<li class="most_dangerous"><a href="#">Most dangerous</a></li>
				<li class="already_captured"><a href="#">Already captured</a></li>
			</ul>
		</section>


		<section id="photos_des_wanted">
			<article id="wizard">
				<p class="1000coins">Reward 1000 gold coins</p>
				<img src="http://via.placeholder.com/150x150" alt="photo_wizard">
				<h1>The Wizard</h1>
				<p>small description...</p>
			</article>
			<article id="hobbit">
				<p class=dead>Dead</p>
				<img src="http://via.placeholder.com/150x150" alt="photo_hobbit">
				<h1>Hobbit #3</h1>
				<p>Small description...</p>
			</article>
			<article id="dwarf">
				<p class="250coins">Reward 250 gold coins</p>
				<img src="http://via.placeholder.com/150x150" alt="photo_dwarf">
				<h1>Yummy Dwarf</h1>
				<p>Small description</p>
			</article>
		</section>

	</header>
	
	<section id="reward">
		<img src="http://via.placeholder.com/150x150" alt="photo_reward">
		<h1>I have captured one of them, how to get my reward ?</h1>
		<p>Huic Arabia est conserta, ex alio latere Nabataeis contigua; opima varietate conmerciorum castrisque oppleta validis et castellis, quae ad repellendos gentium vicinarum excursus sollicitudo pervigil veterum per oportunos saltus erexit et cautos. haec quoque civitates habet inter oppida quaedam ingentes Bostram et Gerasam atque Philadelphiam murorum firmitate cautissimas. hanc provinciae inposito nomine rectoreque adtributo obtemperare legibus nostris Traianus conpulit imperator incolarum tumore saepe contunso cum glorioso marte Mediam urgeret et Parthos.</p>
		<form method="post" action="traitement.php">
			<p><input type="submit" value="Contact Us" class="contact_us_reward"></p>
		</form>
	</section>

	<section id="hunters">
		<h1>Best hunters</h1>
		<div class="ElvesKiller22">
			<img src="http://via.placeholder.com/70x70" class="photo_hunter1" alt="ElvesKiller22">
			<p class="nom_hunter1">ElvesKiller22</p>
			<p><span class="nbcapture1">2 captures - </span><span class="profile1">Profile</span></p>
			<img src="http://via.placeholder.com/50x40" class="photo_like1" alt="photo_like1">
		</div>
		<div class="Goblin45">
			<img src="http://via.placeholder.com/70x70" class="photo_hunter2" alt="Goblin45">
			<p class="nom_hunter2">Goblin45</p>
			<p><span class="nbcapture2">1 capture - </span><span class="profile2">Profile</span></p>
			<img src="http://via.placeholder.com/50x40" class="photo_like2" alt="photo_like2">
		</div>
	</section>

	<section id="ring">
		<h1>About the ring</h1>
		<div class="capabilities">
			<p class="ring_capabilities">Ring Capabilities</p>
			<p class="titretableau">What can our master Sauron do with the ring ?</p>
			<table class="tableau">
				<tr class="features">
					<th>Feature</th>
					<th>description</th>
				</tr>
				<tr class="main">
					<th>Main</th>
					<th>One ring to rule them all</th>
				</tr>
				<tr class="invisibility">
					<th>Invisibility</th>
					<th>You can't see me</th>
				</tr>
				<tr class="power">
					<th>Power</th>
					<th>Destroy the world</th>
				</tr>
			</table>
		</div>
		<div class="awesome">
			<h1>Why the ring is awesome ?</h1>
			<img src="http://via.placeholder.com/110x110" class="photogollum" alt="photo de gollum">
			<p class="phrasegollum">My preciooooooussssss! Hrk Krk, we want our preciooooouuussssss !!</p>
			<p class="signaturegollum">Gollum</p>
		</div>
	</section>

	<section id="army">
		<h1 class="slogan_army">Join Mordor Army, we need you !</h1>
		<img src="http://via.placeholder.com/140x140" class="photo_army" alt="photo de l'armée">
		<p class="laius_army">Dum apud Persas, ut supra narravimus, perfidia regis motus agitat insperatos, et in eois tractibus bella rediviva consurgunt, anno sexto decimo et eo diutius post Nepotiani exitium, saeviens per urbem aeternam urebat cuncta Bellona, ex primordiis minimis ad clades excita luctuosas, quas obliterasset utinam iuge silentium! ne forte paria quandoque temptentur, plus exemplis generalibus nocitura quam delictis.</p>
		<form method="post" action="traitement.php">
			<p><input type="submit" value=" More info on SauronRulesThemAll.com" class="infos_army"></p>
		</form>
	</section>

	<section id="contact">
		<h1 class="titre_contact_us">Contact US</h1>
		<form method="post" action="traitement.php">
			<p>
				<label for="mail"></label>
				<input type="email" name="mail" id="mail" value="@"/>
			</p>
		</form>
		<form method="post" action="traitement.php">
			<p>
				<label for="oneofthem" value="i have seen one of them"></label>
				<select name="oneofthem" id="oneofthem">
					<option value ="i have seen one of them">I have seen of them</option>
					<option value="i have captured one of them">I have captured one of them</option>
					<option value="i want to join your army">I want to join your army</option>
				</select>
			</p>
		</form>
		<form method="post" action="traitement.php">
			<p>
				<label for="message"></label>
				<textarea name="message" id="message" value="Your Message"></textarea>
			</p>
		</form>
	</section>
	<footer>
		<div class="liensfooter1">
			<ul>
				<li><a href="#">About Us</a></li>
				<li><a href="#">Fellows</a></li>
				<li><a href="#">Join our army</a></li>
			</ul>
		</div>
		<div class="liensfooter2">
			<ul>
				<li><a href="#"></a>FAQ</li>
				<li><a href="#"></a>Reward conditions</li>
				<li><a href="#"></a>Legal mentions</li>
			</ul>
		</div>
		<div class="liensfooter3">
			<ul>
				<li><a href="#"></a>Sauron4Ever.com</li>
				<li><a href="#"></a>Follow him also on twitter</li>
			</ul>
		</div>
	</footer>
</body>
</html>


















