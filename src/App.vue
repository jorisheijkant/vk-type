<template>
	<div id="app">
		<main class="container">
			<div class="disclaimer">
				<code>Dit is de overzichtspagina voor de typografie van de Kijk Verderredactie.</code>
				<button class="code-toggle" @click="toggleCode()" :class="{'button-code-active': codeActive}">Labels: <strong>{{elementtoggle}}</strong></button>
			</div>
			<div class="typography-container">
				<div>
					<h4 class="top-label"><code v-if="codeActive">h4 .top-label</code><span class="top-label-type">Reportage</span> De karavaan</h4>
					
					<h1 class="title"><code v-if="codeActive">h1</code>Hoe de Amerikaanse grenspolitie de dochter wegnam van Arnovis Portillo</h1>
					
					<p class="lead"><code v-if="codeActive">.lead</code>Arnovis Portillo uit El Salvador vluchtte met zijn dochtertje naar de VS. Daar nemen Amerikaanse grenswachters haar mee. Om haar vrij te krijgen belooft Portillo terug te keren naar zijn thuisland. Tevergeefs. ‘Ze hebben je bedrogen.’</p>
					
					<p class="credits"><code v-if="codeActive">.credits</code>Door <strong>Marjolein van de Water</strong><time>30 november 2018, 0:30</time></p>
				</div>
				
				<figure>
					<img src="../img/1240.jpeg">
					<figcaption><code class="code-small" v-if="codeActive">figcaption</code>Arnovis werd thuis weer herenigd met zijn dochter. <span class="caption-credits">Bron: EPA</span></figcaption>
				</figure>
				
				<p class="show-dropcap">A<code v-if="codeActive">p .show-dropcap</code>rnovis Portillo probeert zijn 6-jarige dochter Meybelin onderweg zo rustig en warm mogelijk te houden. Ze mag niet huilen, <a href="#">heeft de mensensmokkelaar met klem gezegd, voordat hij hen met 150 andere migranten in een ijskoude koelwagen propte</a>. De 26-jarige Portillo vreest dat Meybelin in zijn armen dood zal vriezen. ‘Straks wordt alles beter’, fluistert hij zachtjes in haar oor, terwijl ze Mexico doorkruisen. Na 52 uur rijden komen vader en dochter aan in grensstad Reynosa. Uitgehongerd, maar ongedeerd. Het is eind mei. Portillo belt naar huis om zijn moeder gerust te stellen. ‘We zijn er bijna.’ Ze steken de grensrivier over en na een half uur lopen, stuiten ze op een patrouille van de migratiepolitie. ‘Ik wil asiel aanvragen’, zegt Portillo, opgelucht dat ze niet verder hoeven te lopen. Hij denkt dat het ergste achter de rug is.</p>
				
				<h3><code v-if="codeActive">h3</code>Koelwagen</h3>
				
				<p><code v-if="codeActive">p</code>Arnovis Portillo komt uit Corral de Muras, een op het eerste gezicht vreedzaam dorpje aan de Pacifische kust van El Salvador. Tussen de golfplaten huisjes scharrelen honden en kippen, in de schaduw van mango­bomen schommelen dorpelingen in hangmatten. Kinderen slaan met stokken kokosnoten uit palmbomen, en overal ruikt het naar vers gebraden vis. Hier doet hij zijn verhaal.</p>
				
				<vk-blockquote text="Dan krijgt Portillo toestemming om drie minuten te bellen. Hij draait het nummer van een schoonzus die in de VS woont. Ze schakelt de hulp in van Amerikaanse mensenrechtenorganisaties, en het lukt haar Meybelin te lokaliseren.">
				</vk-blockquote>
				
				<code v-if="codeActive">vk-subheading variant="1"</code><vk-subheading text="Dit is de eerste tussenkopstijl" variant="1"/>
				
				<p><code v-if="codeActive">p</code>Net als op veel plaatsen in El Salvador hebben ook in Corral de Muras gewelddadige bendes het voor het zeggen. De Mara Salvatrucha en Barrio 18 vechten een bloedige oorlog uit om territorium, persen de bevolking af en dwingen jonge meisjes en vrouwen tot seks. Wie zich niet aan hun regels houdt, is ten dode opgeschreven.</p>
				
				<code v-if="codeActive">vk-subheading variant="2"</code><vk-subheading text="Dit is de tweede tussenkopstijl" variant="2"/>
				
				<p><code v-if="codeActive">p</code>Portillo is dagloner: hij werkt op nabijgelegen boerderijen voor grootgrondbezitters. Van misdaad wil hij al jaren niets weten. Maar de bende­leiders, altijd op zoek naar nieuwe soldaten, accepteerden geen nee. ‘Je doet mee of je bent dood’, was de boodschap. Ze lieten Portillo niet met rust en in 2016 vluchtte de jonge vader naar de Verenigde Staten, waar hij asiel aanvroeg. Meybelin bleef achter bij haar moeder.</p>
				
				<code v-if="codeActive">vk-subheading variant="3"</code><vk-subheading text="Dit is de derde tussenkopstijl" variant="3"/>
				
				<p><code v-if="codeActive">p</code>Na vier maanden cel werd Portillo’s aanvraag afgewezen. Toen hij na zijn uitzetting terugkwam in zijn dorp, bleek zijn vrouw te zijn vertrokken. Ze heeft Meybelin achtergelaten bij Portillo’s moeder. De bende zat Portillo direct weer op de nek. Hij was doodsbang, pakte opnieuw zijn koffer, en leende 7.000 dollar voor een smokkelaar, die ­vader en dochter naar het noorden loodste. Eerst in een pick-uptruck, en daarna dus verder in de koelwagen.</p>
				
				<code v-if="codeActive">vk-subheading variant="4"</code><vk-subheading text="Dit is de vierde tussenkopstijl" variant="4" number="4" />
				
				<p><code v-if="codeActive">p</code>De Amerikaanse grenspolitie brengt Portillo en Meybelin naar een detentiecentrum waar ze met dertig anderen in een kleine cel worden opgesloten. Portillo moet straks voor een rechter verschijnen, zeggen de agenten. Meybelin moet in de cel op hem wachten. Portillo kijkt om zich heen. Kan hij de medegevangenen vertrouwen? Kan hij zijn dochter alleen laten met al die mannen?</p>
				
				<code v-if="codeActive">vk-subheading variant="5"</code><vk-subheading text="Dit is de vijfde tussenkopstijl" variant="5" number="5" />
				
				<p><code v-if="codeActive">p</code>De bewakers bieden aan om Meybelin naar een andere locatie brengen. ‘Een betere plek’, zeggen ze. ‘Met bedden.’ Portillo twijfelt. ‘We brengen jou daar later vandaag ook heen’, beloven de agenten. Portillo wil zijn dochter bij zich houden, maar ziet dan hoe een ander kind door vier bewakers van een woedende vader wordt losgerukt. Hij beseft dat hij geen keuze heeft. ‘Ga maar met die mannen mee’, zegt hij. ‘Ik kom straks naar je toe.’ Het meisje huilt, maar gehoorzaamt.</p>
				
				<code v-if="codeActive">vk-subheading variant="6"</code><vk-subheading text="Dit is de zesde tussenkopstijl" label="Label" variant="6"/>
				
				<p><code v-if="codeActive">p</code>Meybelin ziet haar vader die dag niet terug. Portillo wordt ook niet voor een rechter gebracht. ‘Morgen misschien’, krijgt hij te horen. Portillo is radeloos. De bewakers lachen hem uit. ‘Ze gaan je kind ter adoptie opgeven’, zeggen ze in vloeiend Spaans. Het zijn Latino’s, zelf ook kinderen van migranten. ‘Over twintig jaar werkt ze hier voor ons’, gaan ze verder. ‘Om mensen zoals jij buiten te houden.’</p>
				
				<code v-if="codeActive">vk-subheading variant="7"</code><vk-subheading text="Dit is de zevende tussenkopstijl" label="label" variant="7"/>
				
				<p><code v-if="codeActive">p</code>Enkele dagen later besluit een rechter dat Portillo niet in de VS mag blijven. Hij wordt overgeplaatst naar een uitzetcentrum in Rio Grande. Portillo klampt iedereen aan, tot een medewerker van de migratiedienst de moeite neemt Meybelins naam op te zoeken. ‘Ze staat niet in het systeem’, concludeert ze.</p>
				
				<code v-if="codeActive">vk-subheading variant="8"</code><vk-subheading text="Dit is de achtste tussenkopstijl" number="8" variant="8"/>
				
				<p><code v-if="codeActive">p</code>Dan krijgt Portillo toestemming om drie minuten te bellen. Hij draait het nummer van een schoonzus die in de VS woont. Ze schakelt de hulp in van Amerikaanse mensenrechtenorganisaties, en het lukt haar Meybelin te lokaliseren. Het meisje mag haar oma in El Salvador bellen. ‘Waarom komen jullie me niet halen’, vraagt ze huilend. ‘Ik wil naar huis.’ Portillo mag Meybelin niet spreken, de migratiedienst duwt hem wel papieren onder de neus. ‘Je moet tekenen voor uitzetting.’</p>
				
				<code v-if="codeActive">vk-subheading variant="7" text_align="center"</code><vk-subheading text="Dit is de zevende tussenkopstijl, gecentreerd" label="label" variant="7" text_align="center"/>
				
				<p><code v-if="codeActive">p</code>‘Zonder mijn dochter teken ik niks’, zegt Portillo. Dan gooien de agenten het over een andere boeg. ‘Als je tekent, brengen we haar naar je broer en schoonzus.’ Portillo laat zich overhalen. Een celgenoot die Engels begrijpt, bekijkt later het ondertekende document. ‘Ze hebben je bedrogen’, zegt hij. ‘Hier staat niks over je dochter, er staat alleen dat jij wordt uitgezet.’</p>
				<code v-if="codeActive">vk-subheading variant="8"</code><vk-subheading text="Dit is de achtste tussenkopstijl, gecentreerd" number="8" variant="8" text_align="center"/>
				
				<p><code v-if="codeActive">p</code>Eenmaal terug in El Salvador trekt Portillo aan de bel bij de lokale autoriteiten. ‘We zullen kijken wat we kunnen doen’, krijgt hij te horen. ‘Maar het kan zeker nog drie maanden duren.’ In zijn piepkleine woning in Corral de Muros komen de houten muren op Portillo af. Hij wordt gek van de aanblik van Meybelins knuffels en wil zo snel mogelijk terug naar de VS om zijn dochter te halen.</p>
				
				<p><code v-if="codeActive">p</code>Dan krijgt hij bezoek van een Amerikaanse journalist. Ze vertelt hem over RAICES (Refugee and Immigrant Center for Education and Legal Services), een organisatie in Texas die gratis juridische hulp verleend aan migranten en vluchtelingen. RAICES ontving meer dan 20 miljoen dollar aan giften nadat de Amerikaanse regering Meybelin en duizenden andere migrantenkinderen had opgesloten. Advocaten werken de klok rond om de families herenigd te krijgen.</p>
				
				<p><code v-if="codeActive">p</code>Portillo belt de organisatie, en dan gaat het snel. ‘We hebben haar gesproken’, zegt een medewerker enkele dagen na het eerste contact. ‘Ze zetten haar deze week nog op het vliegtuig.’ Een maand nadat de Amerikanen Meybelin van hem hebben afgenomen, sluit Portillo zijn dochter op het vliegveld van San Salvador in de armen.</p>
				
				<h3><code v-if="codeActive">h3</code>Terug in El Salvador</h3>
				
				<p><code v-if="codeActive">p</code>De eerste weken thuis huilde Meybelin aan een stuk door. Ze durfde niet naar school, noch naar de kerk. Vreemden joegen haar grote angst aan en ze praatte met niemand. Nu, vier maanden na haar vrijlating, gaat het alweer beter. Over de maand in de VS wil ze niks kwijt, maar Meybelin kletst honderduit over de bloemen in de tuin, en de honden van oma. Boven haar bed hangt een feestelijke witte jurk. Over een paar weken ‘studeert ze af’ aan de kleuterschool. Dat wordt in El Salvador groots gevierd.</p>
				
				<p><code v-if="codeActive">p</code>Voor Portillo zijn de problemen niet voorbij, de dreiging van de bende hangt als een zwaard van Damokles boven zijn hoofd. Hij kan niet blijven, dat is duidelijk. Met hulp van RAICES heeft hij een zaak aangespannen tegen de Amerikaanse overheid, vanwege de manier waarop ze hem hebben behandeld en misleid. De advocaten denken dat Portillo de zaak kan winnen, en dat hij en Meybelin dan alsnog aanspraak kunnen maken op asiel.</p>
				
				<p><code v-if="codeActive">p</code>Portillo heeft al zijn hoop op die zaak gevestigd. ‘Als het niet lukt, moet ik het weer illegaal proberen’, zegt hij. Voor een smokkelaar heeft hij geen geld, voorlopig heeft hij nog slapeloze nachten over het afbetalen van de 7.000 dollar van de vorige reis. ‘Misschien ga ik met een karavaan mee.’ Hij kijkt peinzend naar Meybelin, die voor de derde keer achter elkaar dezelfde boerderijpuzzel legt. ‘Maar dan laat ik Meybelin bij haar oma.’</p>
				
				<h1>Dit is de standaardtitelstijl, voor boven producties</h1>
				<h2>Dit is een iets kleinere titelstijl, voor onder andere visualisaties</h2>
				<h3>Dit is een tussenkopje zoals op de website</h3>
				<h4>Dit is een headingstijl die op de site wordt gebruikt voor labels</h4>
				<h5>Deze h5 stijl wordt niet gebruikt en heeft dezelfde eigenschappen als een h3</h5>
				<h6>Hetzelfde geldt voor de h6</h6>
				
				<button class="vk-button">Waar ligt El Salvador?</button>
				
				<ol>
					<li>List Item 1</li>
					<li>List Item 2</li>
					<li>List Item 3</li>
				</ol>
				
				<ul>
					<li>List Item 1</li>
					<li>List Item 2</li>
					<li>List Item 3</li>
				</ul>
				
				<table>
					<caption>Table Caption</caption>
					<thead>
					<tr>
						<th>Table Heading 1</th>
						<th>Table Heading 2</th>
						<th>Table Heading 3</th>
						<th>Table Heading 4</th>
						<th>Table Heading 5</th>
					</tr>
					</thead>
					<tfoot>
					<tr>
						<th>Table Footer 1</th>
						<th>Table Footer 2</th>
						<th>Table Footer 3</th>
						<th>Table Footer 4</th>
						<th>Table Footer 5</th>
					</tr>
					</tfoot>
					<tbody>
					<tr>
						<td>Table Cell 1</td>
						<td>Table Cell 2</td>
						<td>Table Cell 3</td>
						<td>Table Cell 4</td>
						<td>Table Cell 5</td>
					</tr>
					<tr>
						<td>Table Cell 1</td>
						<td>Table Cell 2</td>
						<td>Table Cell 3</td>
						<td>Table Cell 4</td>
						<td>Table Cell 5</td>
					</tr>
					<tr>
						<td>Table Cell 1</td>
						<td>Table Cell 2</td>
						<td>Table Cell 3</td>
						<td>Table Cell 4</td>
						<td>Table Cell 5</td>
					</tr>
					<tr>
						<td>Table Cell 1</td>
						<td>Table Cell 2</td>
						<td>Table Cell 3</td>
						<td>Table Cell 4</td>
						<td>Table Cell 5</td>
					</tr>
					</tbody>
				</table>
				
				
				
				<div id="forms">
					<form>
						<legend>Verschillende velden met typografie</legend>
						<p>
							<label for="input__text">Text Input</label>
							<input id="input__text" type="text" placeholder="Text Input">
						</p>
						<p>
							<label for="input__search">Search</label>
							<input id="input__search" type="search" placeholder="Enter Search Term">
						</p>
						
						<label for="select">Select</label>
						<select id="select">
							<optgroup label="Option Group">
								<option>Option One</option>
								<option>Option Two</option>
								<option>Option Three</option>
							</optgroup>
						</select>
					</form>
				</div>
			</div>
		</main>
	</div>
</template>

<script>
	import VkSubheading from './components/vk-subheading';
	import VkBlockquote from './components/vk-blockquote';
	
    export default {
        name: 'App',
	    
	    components : {
            VkSubheading, VkBlockquote
	    },
	    
        data() {
            return {
                codeActive: false
            }
        },
	    
	    methods : {
            toggleCode() {
                this.codeActive = !this.codeActive
            }
	    },
	    
	    computed : {
            elementtoggle() {
                return this.codeActive ? 'Aan' : 'Uit'
            }
	    }
    }
</script>

<style lang="scss">
	@import "../css/style";
	@import "../css/font-imports";
</style>