<h1><strong>Basic-Web-Development-Setup-2019:</strong> <br>Gulp Website Template. Optional Gulp 3 oder 4, SASS oder SCSS. Browserify, Uglify. RSYNC funktion für Netlify oder GithubPages</h1>

<p>
	<img src="https://i.imgur.com/AHhUYVq.png" alt="Start HTML Template">
</p>

<p>Author: <a href="/" target="_blank">D36u9</a></p>

<p>Basic-Web-Development-Setup-2019 ist eine umfassende HTML5-Vorlage mit Bootstrap 4 (grid & reboot), Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS, Uglify, Browserify. Rsync für Netlify und GithubPages. Die Vorlage enthält eine <strong>.htaccess</strong>- Datei mit Cache-Regeln für den Webserver.</p>

<p><strong>Basic-Web-Development-Setup-2019</strong> verwendet die Best Practices der Webentwicklung.</p>

<p>Browserübergreifende Kompatibilität: IE9 +.</p>

<p>Die Vorlage verwendet eine Sass mit <strong>Sass</strong> oder <strong>Scss</strong> syntax (optional).</p>

<h2>So verwendest du Basic-Web-Development-Setup-2019</h2>

<ol>
	<li>Lade<strong>Basic-Web-Development-Setup-2019</strong> von GitHub;<a href="https://github.com/agragregra/OptimizedHTML-4/archive/master.zip">herunter</a></li>
	<li>Oder clone das Repository im Terminal mit <strong>git clone https://github.com/D36u92/Basic-Web-Development-Setup-2019.git</strong></li>
	<li>gehe ins erstellte Verzeichnis und installiere die Node Modules mit: <strong>npm i</strong></li>
	<li>Führe die Vorlage aus: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp-Aufgaben:</h2>

<ul>
	<li><strong>gulp</strong>: Standardgulp-Task (sass, js, watch, browserSync) für die Webentwicklung ausführen.</li>
	<li><strong>gulp rsync</strong>: Projektbereitstellung auf dem Server vom Ordner <strong>dist</strong>über <strong>RSYNC</strong></li>
	<li><strong>gulp deploy</strong>: Projektbereitstellung auf dem Server vom Ordner <strong>dist</strong>über <strong>GithubPages</strong></li>
</ul>

<h2>Regeln für das Arbeiten mit Basic-Web-Development-Setup-2019</h2>

<ol>
	<li>Alle HTML-Dateien sollten einen ähnlichen Anfangsinhalt haben wie in <strong>app/index.html</strong>;</li>
	<li><strong>Vorlagen-Grundbilder</strong> beachte den Kommentar in der app/index.html - alle deine Vorlagen-Grundbilder (og:image for social networking, favicons for a variety of devices) werden dor verlinkt.</li>
	<li><strong>Benutzerdefinierte Browser Farbe</strong> beachte den Kommentar in app/index.html: Lege die Farbe des Browserkopfs auf einer Vielzahl von Geräten fest.</li>
	<li><strong>Angepasste HTML</strong> beachte den Kommentar in app/index.html - hier landet dein ganz persönlicher HTML code.</li>
	<li>Um die neue jQuery-Bibliothek zu installieren oder weitere externe Bibliotheken wie animejs etc, führe einfach den Befehl "<strong>npm i "packetname"</strong>" im Terminal aus. Danach müssen die Bibliothekspfade nur noch in der <strong>(gulpfile.js)</strong> in den <strong>scriptsTask</strong>auf Zeile 39 eingefügt werden.</li>
	<li>Alle benutzerdefinierten JS Dateien findet ihr in <strong>app/js/common.js</strong>.</li>
	<li>Alle Sass variablen findet ihr in <strong>app/sass/_vars.sass | app/scss/_vars.scss</strong>;</li>
	<li>Alle Bootstrap media queries findet ihr in <strong>app/sass/_media.sass | app/scss/_media.scss</strong>;</li>
	<li>Alle CSS libraries und styles findet ihr in <strong>app/sass/_libs.sass | app/scss/_libs.scss</strong>;</li>
	<li>Benenne die <strong>ht.access</strong> zu <strong>.htaccess</strong> um bevor du sie auf deinen Webserver platzierst. Diese Datei enthält Regeln für das Zwischenspeichern von Dateien auf dem Webserver.</li>
</ol>

<h2>Weitere Fragen oder Hilfe benötigt?</h2>
<p>Melde dich auf <a href="https://discord.gg/kXdmQmD">Discord</a></p>
