---


---

<h1 id="centerzap-wirentcenter"><center>⚡️ wirent</center></h1>
<h2 id="centerlanding-page-pracy-inżynerskiejcenter"><center>landing page pracy inżynerskiej</center></h2>
<h3 id="wykonał-mikołaj-tkaczyk">Wykonał Mikołaj Tkaczyk</h3>
<h2 id="uwaga---strona-jest-oparta-o-hosting-heroku-zawierający-funkcjonalność-dyno-sleeping.-pierwsze-uruchomienie-strony-może-zająć-więcej-czasu-ze-względu-na-wznawianie-procesów-hostingu.">UWAGA - Strona jest oparta o hosting Heroku zawierający funkcjonalność dyno-sleeping. Pierwsze uruchomienie strony może zająć więcej czasu ze względu na wznawianie procesów hostingu.</h2>
<p>Aplikacja została stworzona jako podstawowa strona landing page pracy inżynierskiej, będącej strukturą sieciową IoT w konwencji SaaS. Ma ona na celu prezentację wymaganych do wykonania kroków oraz użytych w celu stworzenia architektury technologii.</p>
<h3 id="ze-względu-na-hosting-na-serwerach-europejskich-prosiłbym-o-zmianę-test-location-na-londyn-uk-ze-względu-na-krótszy-response-time-i-first-contentful-paint.">Ze względu na hosting na serwerach europejskich prosiłbym o zmianę test location na Londyn, UK ze względu na krótszy response time i first contentful paint.</h3>
<h3 id="użyte-technologie">Użyte technologie:</h3>
<ul>
<li><strong>Node.js</strong> - podstawowa technologia służąca za fundament zarówno backendowy jak i frontendowy</li>
<li><strong>Express</strong> - framework backendowy odpowiadający za konfigurację serwera, listener, routing itp.</li>
<li><strong>React</strong> - biblioteka frontendowa służąca do dynamicznego renderowania aplikacji zależnie od stanu</li>
<li><strong>Tailwind CSS</strong> - biblioteka CSS stylizująca elementy na podstawie klas, zaimplementowana z funkcją purge w celu zmniejszenia wielkości pakietu CSS w production build</li>
</ul>
<h3 id="przesłane-archiwum-zawiera">Przesłane archiwum zawiera:</h3>
<ul>
<li><strong>struktura.jpg</strong> - screenshot przedstawiający strukturę katalogów w folerze projektu, mający na celu uwidocznienie zastosowanego modelu MVC (Model - Pliki JSON, View - Katalog client - aplikacja React, Controller - katalog controllers - kontrolery obsługujące uzyskiwanie i przetwarzanie danych po stronie serwera).</li>
<li><strong>server.js</strong> - główny plik serwera backendowego zaimplementowany w Node.js oraz Express. Zawiera podstawową konfigurację listenera oraz routingu.</li>
<li><strong>apiControllers.js</strong> - plik zawierający kontrolery łączące funkcjonalność serwera w formie uzyskiwania danych z plików i przekazywania response na frontend.</li>
<li><strong>templates.js</strong> - plik template zawierający obiekt JSON z zawartością tekstową odpowiednich pól z podziałem na język angielski i polski.</li>
<li><strong>App.js</strong> - podstawowy plik aplikacji React. Obsługuje zapytania na backend poprzez proxy, zawiera główny layout aplikacji bazujący na obecnym stanie widoku.</li>
</ul>

