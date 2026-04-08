# Research Strategy

Subject: Karlově mostě o dvě nové stránky history

## Main Research Questions
- Jaké jsou přesné datace a milníky výstavby Karlova mostu (zahájení, klíčové etapy, dokončení) a jak se liší v jednotlivých pramenech?
- Jak Karlův most zapadá do širšího kontextu dějin Prahy (vláda Karla IV., urbanistický rozvoj Starého Města a Malé Strany, rola mostu v dopravě a obraně), včetně relevantních let a událostí?
- Které sochy a sousoší jsou na Karlově mostě (zejména na jižních/ostatních pilířích) a jaké jsou jejich autor, rok vzniku/vztyčení, zadavatel (instituce, řád, donátor) a ikonografický význam?
- Jaké jsou spolehlivé informace o historii jednotlivých soch (původní umístění, restaurování, přesuny poškození, rekonstrukce po událostech typu povodně/poškození, případné verze či zaměření na současnou podobu)?
- Jaké zajímavosti lze uvést bez spekulací: např. původ názvů konkrétních soch/sousoší, dobové souvislosti, symbolika atributů a vztah k patronům či událostem?
- Které vybrané sousoší (z dostupných a významných) stojí za detailnější „zajímavosti“ a jak ověřit fakta (attributy, legenda, objednavatel, dobový význam)?
- Jaké zdroje použít pro faktografii (akademické publikace, památkový katalog, muzejní/NPÚ/hl. město Praha materiály, digitální archivy) a jak ověřit shodu dat u kontroverzních údajů?
- Jak má být časová osa na history.html zpracována tak, aby byla fakticky správná (hranice období, formulace událostí, citace/odkazy na zdroje, jednotný styl data)?
- Jak přesně aktualizovat navigaci: jaké menu položky (včetně nové sekce/odkazu na history.html a statues.html) mají být viditelné a na kterých stránkách to musí být upraveno?
- Jak aktualizovat site-manifest: které nové URL přidat, které případně odebrat, a jak zajistit, že publish-ready build nezlomí routing?
- Co přesně znamená „ukliď publish-ready stav“ pro project-update.html: je-li soubor přítomen, ale není v manifestu ani navigaci, má se odstranit nebo deaktivovat (a podle jakých pravidel projektu)?

## Critical Information Needed
- Přesná chronologie výstavby a zásadních událostí mostu (data i stručný popis události) pro časovou osu.
- Kulturu-historické zasazení do dějin Prahy s konkrétními datacemi (aspoň rámcově) a korektními souvislostmi.
- Kompletní a fakticky správný seznam soch/sousoší použitých na statues.html (pro každý prvek: název, autor, rok/vztyčení, význam, případně řád/objednavatel).
- Uvedení ikonografického významu a atributů (co znázorňují a proč) pro jednotlivé vybrané sochy/sousoší.
- Ověření názvů a variant názvů (např. jak jsou sochy pojmenované v oficiálních katalozích) a shoda s mapou/rozmístěním.
- Restaurování/poškození: které zásadní události se vztahují k současnému stavu soch a které je vhodné zmiňovat.
- Odkazování na zdroje u klíčových faktů (datumové údaje, autorství, původ) – aby bylo možné dohledání a kontrola.

## Nice-to-Have Information
- Rychlá „mikrohistorie“ vybraných období (např. barokní doplnění sochařské výzdoby, proměny významu mostu v čase).
- Zajímavosti typu „nejzajímavější atribut“ nebo „méně známý fakt“ u 2–4 sousoší, které vyberete jako reprezentativní.
- Stručné vysvětlení ikonografie (např. jak se uplatňuje symbolika víry, ctností, patronátu).
- Propojení časové osy s některými sochami/sousoší (např. že určitá socha vzniká v návaznosti na barokní období).

## Priority Source Types
- Památkové a muzejní autoritní katalogy (NPÚ / Národní památkový ústav, městské sbírky, muzea).
- Odborné knihy a recenzované publikace o Karlově mostě a barokní sochařské výzdobě (historici umění).
- Akademické/odborné články a studie (historie stavebnictví, dějiny Prahy).
- Oficiální městské a kulturní portály Prahy (sekce o Karlově mostě, popisy památkových objektů).
- Digitální archivy a databáze s autorstvími a datací (kde jsou dohledatelné autor/rok a ikonografické údaje).
- Restaurovací zprávy nebo odborné restaurátorské podklady (pokud jsou veřejně dostupné) pro historii konkrétních soch.

## Risk Areas
- Nesrovnalosti v datování (zejména u dokončování, oprav po událostech a u let vztyčení některých soch).
- Zaměňování původu vs. současného stavu (sochy mohly být přemístěny nebo restaurovány; je nutné uvádět „vztyčeno“ vs. „původně“).
- Chybné autorství nebo záměny autorů v sekundárních zdrojích bez ověření v autoritních katalozích.
- Nejasné názvy sousoší/soch v různých jazykových/variantních přepisech (je nutné sjednotit terminologii podle primárních zdrojů).
- Příliš obecné dějinné tvrzení bez konkrétních dat; časová osa musí být faktická a dohledatelná.
- Technické riziko: neúplná aktualizace navigace (např. zobrazení nové položky jen na některých stránkách) nebo rozpor s URL v manifestu.
- Technické riziko: odstranění/uklizení project-update.html může vyžadovat úpravu referencí (odkazy, build pipeline) – je třeba ověřit, zda soubor není nepřímo zmiňován.

## Time Relevance Notes
- Faktografické údaje o historii a sochách nejsou časově citlivé ve smyslu „aktualizací“, ale je nutné použít nejnovější dostupné restaurátorské/odborné katalogy pro správný současný stav a datace.
- U časové osy uvádějte data v jednom formátu a vyhněte se relativním formulacím typu „v 1. polovině“ bez ověřených přesných let.
- U sochařské výzdoby preferujte uvádění let vzniku/vztyčení a uvádějte, pokud se jedná o opravený/přeinstalovaný prvek (dle dostupných autoritních zdrojů).
- Při technických úpravách (manifest/navigace) ověřte, že změny neovlivní cache a doručování (delivery pack) – publish-ready musí zůstat konzistentní.
