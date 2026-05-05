
# awesome-api-italia

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)
[![Lingua](https://img.shields.io/badge/lingua-Italiano-blue)](#)
[![GitHub Stars](https://img.shields.io/github/stars/openapi/awesome-api-italia?style=social)](https://github.com/openapi/awesome-api-italia)

> Una lista curata di API italiane e internazionali con dati italiani — dati pubblici, PA, catasto, fisco, automotive, imprese e molto altro.

**Scope:** Questa lista include API di enti italiani (PA, privati, aggregatori) **e** API internazionali che espongono dataset specifici sull'Italia. Le voci a pagamento sono marcate con 💰. Le voci gratuite o open non hanno marcatura speciale.

**Legenda:**
- 💰 A pagamento o con piano freemium limitato
- 🏛️ Ente pubblico / PA
- 🔑 Richiede registrazione / API key
- 📄 Documentazione ufficiale disponibile

<p align="center">♢</p>

## Contenuti

- [Enti Normativi e Standard di Riferimento](#enti-normativi-e-standard-di-riferimento)
- [Pubblica Amministrazione](#pubblica-amministrazione)
    - [Dati Aperti e Open Data](#dati-aperti-e-open-data)
    - [Anagrafe e Identità](#anagrafe-e-identità)
    - [Fisco e Tributi](#fisco-e-tributi)
    - [Previdenza e Lavoro](#previdenza-e-lavoro)
    - [Sanità](#sanità)
    - [Giustizia](#giustizia)
- [Imprese e Persone Giuridiche](#imprese-e-persone-giuridiche)
    - [Registro Imprese e Visure](#registro-imprese-e-visure)
    - [Partite IVA e Codici Fiscali](#partite-iva-e-codici-fiscali)
    - [Rating e Rischio Creditizio](#rating-e-rischio-creditizio)
- [Territorio e Geospaziale](#territorio-e-geospaziale)
    - [Catasto e Immobiliare](#catasto-e-immobiliare)
    - [Comuni, CAP e Codici ISTAT](#comuni-cap-e-codici-istat)
    - [Mappe e Cartografia](#mappe-e-cartografia)
- [Automotive e Veicoli](#automotive-e-veicoli)
- [Finanza e Mercati](#finanza-e-mercati)
    - [Banche e Istituti Finanziari](#banche-e-istituti-finanziari)
    - [Fatturazione Elettronica e SDI](#fatturazione-elettronica-e-sdi)
- [Comunicazione e Marketing Diretto](#comunicazione-e-marketing-diretto)
    - [SMS e Notifiche](#sms-e-notifiche)
    - [PEC e Posta Certificata](#pec-e-posta-certificata)
    - [Email Verification](#email-verification)
- [Identità Digitale e Trust](#identità-digitale-e-trust)
    - [SPID e CIE](#spid-e-cie)
    - [Firma Digitale](#firma-digitale)
- [Immobiliare](#immobiliare)
- [Turismo e Cultura](#turismo-e-cultura)
- [Trasporti e Mobilità](#trasporti-e-mobilità)
- [Meteo e Ambiente](#meteo-e-ambiente)
- [Aggregatori e Marketplace API](#aggregatori-e-marketplace-api)
- [Dataset Internazionali con Dati Italiani](#dataset-internazionali-con-dati-italiani)
- [Strumenti e Librerie per Sviluppatori](#strumenti-e-librerie-per-sviluppatori)
- [Liste Correlate](#liste-correlate)

<p align="center">♢</p>

## Enti Normativi e Standard di Riferimento

> Chi definisce le regole tecniche per le API italiane e la PA digitale.

- 🏛️ [AgID — Agenzia per l'Italia Digitale](https://www.agid.gov.it/) — Ente pubblico che coordina la trasformazione digitale della PA. Pubblica linee guida sulle API REST per la PA italiana.
- 🏛️ [AgID API Guidelines](https://docs.italia.it/italia/piano-triennale-ict/lg-modellointeroperabilita-docs/) — Linee guida ufficiali sul Modello di Interoperabilità (ModI) per le API della PA.
- 🏛️ [ISTAT](https://www.istat.it/it/metodi-e-strumenti/tecnologie-e-standard/sdmx) — Standard SDMX per dati statistici italiani. Base per tutti i dataset ISTAT accessibili via API.
- 🏛️ [DigitPA / ANPR](https://www.anpr.interno.it/) — Standard tecnici per l'Anagrafe Nazionale Popolazione Residente.

<p align="center">♢</p>

## Pubblica Amministrazione

### Dati Aperti e Open Data

- 🏛️ [dati.gov.it API](https://dati.gov.it/api/action/) — Portale nazionale degli open data italiani. API CKAN per ricerca e accesso a dataset della PA.
- 🏛️ [ISTAT API SDMX](https://esploradati.istat.it/databrowser/) — Accesso programmatico ai dati statistici ufficiali italiani (popolazione, economia, lavoro, ecc.) tramite standard SDMX-REST.
- 🏛️ [OpenCoesione](https://opencoesione.gov.it/it/opendata/) — Dati sui fondi europei e investimenti pubblici in Italia. Dataset scaricabili e API REST.
- 🏛️ [BDNCP — Banca Dati Nazionale Contratti Pubblici](https://dati.anticorruzione.it/opendata) — API ANAC per accesso a dati su appalti pubblici italiani.
- 🏛️ [Portale Europeo dei Dati — Italia](https://data.europa.eu/data/datasets?locale=it&country=it) — Dataset italiani pubblicati sul portale europeo, accessibili via API DCAT.

### Anagrafe e Identità

- 🏛️ 🔑 [ANPR — Anagrafe Nazionale Popolazione Residente](https://www.anpr.interno.it/portale/web/anpr/documentazione-tecnica) — API per comuni e PA accreditate. Accesso a dati anagrafici, certificati, cambi di residenza. Accesso riservato a enti autorizzati.
- 🏛️ 🔑 [PDND — Piattaforma Digitale Nazionale Dati](https://docs.pagopa.it/pdnd-interoperabilita) — Infrastruttura di interoperabilità della PA italiana. Abilita l'accesso federato alle API di decine di enti pubblici tramite voucher OAuth2.
- 🏛️ [Codice Fiscale — Algoritmo ufficiale](https://www.agenziaentrate.gov.it/portale/web/guest/schede/istanze/richiesta-ts_cf/informazioni-codice-fiscale-comune) — Non è un'API ufficiale pubblica, ma esistono implementazioni open source validate sull'algoritmo MEF. Vedi sezione [Strumenti](#strumenti-e-librerie-per-sviluppatori).

### Fisco e Tributi

- 🏛️ 🔑 [Agenzia delle Entrate — Verifica Partita IVA](https://www.agenziaentrate.gov.it/portale/web/guest/schede/comunicazioni/verifica-partita-iva) — Servizio VIES per verifica P.IVA italiana ed europea. Disponibile via SOAP/REST.
- 🏛️ [VIES VAT Validation (EU)](https://ec.europa.eu/taxation_customs/vies/#/vat-validation) — API europea per validazione P.IVA comunitarie, incluse quelle italiane (prefisso IT).
- 🏛️ 🔑 [SDI — Sistema di Interscambio (fattura elettronica)](https://www.fatturapa.gov.it/it/sistemainterscambio/specifiche-tecniche/) — API per invio e ricezione fatture elettroniche B2B e PA. Accesso tramite canale accreditato o intermediario.
- 🏛️ [Agenzia delle Entrate Open Data](https://www.agenziaentrate.gov.it/portale/web/guest/schede/istanze/open-data) — Dataset aperti su dichiarazioni fiscali, immobili, statistiche tributarie.

### Previdenza e Lavoro

- 🏛️ 🔑 [INPS API](https://servizi.inps.it/servizi/Sources/HomeSP/index.aspx) — Servizi digitali INPS. Alcune API disponibili per CAF, patronati e intermediari accreditati (estratto conto, domande online).
- 🏛️ 🔑 [INAIL Open Data e Servizi](https://www.inail.it/cs/internet/comunicazione/open-data.html) — Dati su infortuni, malattie professionali, statistiche del lavoro.
- 🏛️ 🔑 [DURC Online](https://www.inps.it/prestazioni-servizi/durc-on-line) — Documento Unico di Regolarità Contributiva. API per verifica contributiva aziendale. Accesso tramite intermediari o direttamente via SPID.

### Sanità

- 🏛️ [Ministero della Salute Open Data](https://www.salute.gov.it/portale/documentazione/p6_2_8_1_1.jsp?lingua=italiano&id=18) — Dataset su strutture sanitarie, farmaci, malattie, vaccinazioni.
- 🏛️ [AIFA — Farmaci](https://www.aifa.gov.it/banca-dati-farmaci) — Banca dati ufficiale dei farmaci autorizzati in Italia. Esportazioni strutturate, in corso sviluppo API REST.
- 🏛️ [ISS — Istituto Superiore di Sanità Open Data](https://www.epicentro.iss.it/coronavirus/open-data) — Dati epidemiologici, sorveglianza, registri.

### Giustizia

- 🏛️ [Portale dei Servizi Telematici — Ministero della Giustizia](https://pst.giustizia.it/PST/) — Accesso telematico agli atti giudiziari. API per operatori abilitati (avvocati, tribunali).
- 🏛️ [ReGIndE](https://pst.giustizia.it/PST/it/pst_2_15.wp) — Registro Generale degli Indirizzi Elettronici. Lookup PEC di avvocati, notai, consulenti tecnici.

<p align="center">♢</p>

## Imprese e Persone Giuridiche

### Registro Imprese e Visure

- 🏛️ 💰 [InfoCamere — API Registro Imprese](https://www.infocamere.it/strumenti/api) — API ufficiali del sistema camerale italiano. Visure camerali, bilanci, atti, protesti, cariche. Il riferimento istituzionale per dati sulle imprese italiane.
- 💰 🔑 [Openapi.com — Business Information IT](https://www.openapi.com/it/api/business-information) — Marketplace API con oltre 70 servizi su imprese italiane: visure, bilanci, rating, DURC, atti notarili, cariche, protesti. Aggregatore certificato ISO 27001.
- 💰 🔑 [CRIF](https://www.crif.com/business-information/) — Credit information e dati su imprese e persone fisiche italiane. API per valutazione del rischio e KYC.
- 💰 🔑 [Cerved](https://api.cerved.com/) — API per informazioni commerciali, rating e scoring su imprese italiane. Reference per risk management e onboarding B2B.
- 💰 🔑 [Registro.it / CCIAA](https://www.registroimprese.it/) — Portale delle Camere di Commercio. Accesso a visure e atti ufficiali (tramite intermediari con API).
- 💰 🔑 [Telemaco (InfoCamere)](https://www.telemaco.infocamere.it/) — Sportello telematico per professionisti. API per accesso diretto al Registro Imprese.

### Partite IVA e Codici Fiscali

- 🔑 [Openapi.com — VAT / Codice Fiscale Check](https://www.openapi.com/it/api/id-trust) — Verifica P.IVA, codice fiscale, e corrispondenza tra i due. Include check di esistenza nel registro tributario.
- [vat-validation (npm)](https://www.npmjs.com/package/vat-validation) — Libreria open source per validazione P.IVA italiana e EU lato client.
- [codicefiscale (npm)](https://www.npmjs.com/package/codicefiscale) — Generazione e validazione codice fiscale italiano secondo algoritmo MEF.
- [python-codicefiscale](https://github.com/fabiocaccamo/python-codicefiscale) — Implementazione Python completa dell'algoritmo codice fiscale.

### Rating e Rischio Creditizio

- 💰 🔑 [Openapi.com — Credit Score IT](https://www.openapi.com/it/api/business-information) — Score creditizio e limiti operativi per imprese italiane.
- 💰 🔑 [Experian Italy](https://www.experian.it/business/products/business-information/) — Credit bureau italiano. API per scoring e informazioni commerciali.
- 💰 🔑 [Modefinance](https://www.modefinance.com/it/api) — FinTech italiana specializzata in rating PMI. API per accesso a rating MORE e analisi di bilancio.

<p align="center">♢</p>

## Territorio e Geospaziale

### Catasto e Immobiliare

- 🏛️ 🔑 [Agenzia delle Entrate — Servizi Catastali](https://www.agenziaentrate.gov.it/portale/web/guest/schede/fabbricatiterreni/consultazione-banca-dati-catastale) — Accesso alla banca dati catastale. Visure catastali, planimetrie, rendite. Accesso istituzionale o tramite servizi convenzionati.
- 🏛️ [OMI — Osservatorio Mercato Immobiliare](https://www.agenziaentrate.gov.it/portale/web/guest/schede/fabbricatiterreni/omi) — Quotazioni immobiliari ufficiali per zona OMI. Dataset scaricabili, in sviluppo API REST.
- 💰 🔑 [Openapi.com — Real Estate](https://www.openapi.com/it/api/real-estate) — 30+ servizi su immobili italiani: valutazioni, dati catastali, ipoteche, storico transazioni.
- 💰 🔑 [Immobiliare.it API](https://www.immobiliare.it/api-privati/) — API del principale portale immobiliare italiano. Annunci, prezzi di mercato, statistiche per zona.
- 💰 🔑 [Casa.it API](https://www.casa.it/) — API del secondo portale immobiliare italiano per annunci residenziali e commerciali.

### Comuni, CAP e Codici ISTAT

- 🏛️ [ISTAT — Codici Comuni e Unità Territoriali](https://www.istat.it/it/archivio/6789) — Dataset ufficiale di tutti i comuni italiani con codici ISTAT, province, regioni. Scaricabile in CSV/XLS, base per qualsiasi API geografica IT.
- 🏛️ [Poste Italiane — CAP](https://www.poste.it/cerca/index.html#/viacap) — Lookup CAP ufficiale. Non espone API pubblica, ma esistono dataset derivati open source.
- 🔑 [Openapi.com — Municipalities](https://www.openapi.com/it/api/person) — API per lookup comuni per CAP, ISTAT, provincia, regione. Incluse fusioni e comuni soppressi.
- [comuni-italiani (npm)](https://www.npmjs.com/package/comuni-italiani) — Dataset completo dei comuni italiani in JSON, aggiornato. Usabile lato client senza API.
- [comuni.json (GitHub)](https://github.com/matteocontrini/comuni-json) — Lista aggiornata comuni italiani in JSON con ISTAT, CAP, coordinate, provincia, regione.
- [cap-comuni-italiani (GitHub)](https://github.com/devdavid/cap-comuni-italiani) — Mapping CAP → comune aggiornato annualmente da fonti ufficiali.

### Mappe e Cartografia

- 🏛️ [Geoportale Nazionale — PCNI](http://www.pcn.minambiente.it/mattm/servizio-wms/) — WMS/WFS ufficiale del Ministero dell'Ambiente. Ortofoto, DTM, cartografia tecnica italiana.
- 🏛️ [Geoportale AGEA](https://www.agea.gov.it/portal/page/portal/AGEASystem/serviziGis) — WMS per aree agricole, particelle catastali rurali, suoli italiani.
- 🏛️ [OpenStreetMap Overpass API](https://overpass-api.de/) — Query geografiche su dati OSM italiani. Altissima copertura per strade, POI, confini amministrativi italiani.
- 🔑 [Google Maps Platform — Italy](https://developers.google.com/maps) 💰 — Geocoding, Places, Directions con dataset italiani. Freemium con 200$/mese di crediti gratuiti.
- 🔑 [HERE Maps — Italy](https://developer.here.com/) 💰 — Alternativa enterprise a Google Maps con dati italiani di alta qualità. Freemium.
- 🔑 [TomTom API — Italy](https://developer.tomtom.com/) 💰 — Routing e traffico con dataset italiani. Forte in automotive.
- [Nominatim (OSM)](https://nominatim.org/release-docs/develop/api/Overview/) — Geocoding/reverse geocoding gratuito basato su OpenStreetMap. Ottima copertura italiana.

<p align="center">♢</p>

## Automotive e Veicoli

- 🏛️ 🔑 [MIT — Motorizzazione Civile](https://www.mit.gov.it/infrastrutture-e-trasporti/motorizzazione/open-data) — Open data su veicoli immatricolati, revisioni, patenti. Accesso istituzionale per interrogazioni puntuali.
- 💰 🔑 [Openapi.com — Automotive](https://www.openapi.com/it/api/automotive) — 17+ API su veicoli italiani: targa → marca/modello/anno, assicurazione attiva, revisione, libretto. Fonte ACI/PRA.
- 💰 🔑 [ACI — PRA (Pubblico Registro Automobilistico)](https://www.aci.it/i-servizi/normative/codice-della-strada/revisione-dei-veicoli.html) — Registro proprietà veicoli. Accesso tramite intermediari convenzionati ACI.
- 💰 🔑 [Targhe e Veicoli API](https://www.targheinfo.it/) — API commerciale italiana per lookup targa: dati tecnici veicolo, scadenza bollo, assicurazione.
- [eurotax / DAT](https://www.dat.de/en/) 💰 — Valutazione veicoli usati italiani. Riferimento per automotive dealer e assicurazioni.

<p align="center">♢</p>

## Finanza e Mercati

### Banche e Istituti Finanziari

- 🏛️ [Banca d'Italia — Open Data](https://www.bancaditalia.it/statistiche/raccolta-dati/open-data/index.html) — Statistiche bancarie, tassi, bilance dei pagamenti, cambi ufficiali. Dataset strutturati e API SDMX.
- 🏛️ [Banca d'Italia — Albo Banche e Intermediari](https://www.bancaditalia.it/compiti/vigilanza/albi-elenchi/index.html) — Lookup ufficiale di banche, SIM, SGR, intermediari finanziari autorizzati in Italia. Scaricabile, in sviluppo API.
- 🏛️ [Consob — Emittenti e Strumenti](https://www.consob.it/web/consob/home) — Dati su società quotate italiane, prospetti, strumenti finanziari.
- 🏛️ [BCE / ECB — Statistical Data Warehouse](https://sdw.ecb.europa.eu/browseExplanation.do?node=9484447) — API SDMX con tassi BCE, cambi Euro, dati bancari italiani aggregati.
- [IBAN Validation — Italy](https://ibanapi.com/) 💰 — Validazione e lookup IBAN italiani (prefisso IT). Verifica BIC/SWIFT, nome banca.

### Fatturazione Elettronica e SDI

- 🏛️ [FatturaPA — Specifiche Tecniche SDI](https://www.fatturapa.gov.it/it/sistemainterscambio/specifiche-tecniche/) — Documentazione ufficiale per integrazione con il Sistema di Interscambio dell'Agenzia delle Entrate.
- 💰 🔑 [Aruba Sign / Aruba PEC](https://www.aruba.it/servizi/fatturazione-elettronica.aspx) — API per invio/ricezione fatture elettroniche tramite intermediario accreditato SDI.
- 💰 🔑 [Fatture in Cloud API](https://developers.fattureincloud.it/) — API REST per gestione fatturazione elettronica italiana. Ampiamente usata da sviluppatori e integrator.
- 💰 🔑 [Invoicecloud / Zucchetti](https://www.zucchetti.it/website/cms/products/1086-fatturazione-elettronica.html) — API enterprise per fatturazione elettronica, conservazione sostitutiva.
- 💰 🔑 [TeamSystem API](https://developer.teamsystem.com/) — Suite API gestionali italiani: fatturazione, contabilità, HR. Ecosistema B2B per software house.

<p align="center">♢</p>

## Comunicazione e Marketing Diretto

### SMS e Notifiche

- 💰 🔑 [eSendex Italy](https://developers.esendex.com/) — API SMS con numeri italiani. Molto usata per OTP e notifiche transazionali.
- 💰 🔑 [Openapi.com — SMS](https://www.openapi.com/it/api/communication) — Invio SMS con prefisso italiano. Parte del marketplace Openapi.
- 💰 🔑 [Twilio — Italy](https://www.twilio.com/docs/sms) — Numeri italiani disponibili. Leader globale con ottima copertura TIM/Vodafone/WindTre.
- 💰 🔑 [Messagebird](https://developers.messagebird.com/) — Alternativa europea a Twilio con numeri IT, ottimizzata per GDPR.

### PEC e Posta Certificata

- 🔑 [Openapi.com — PEC Check](https://www.openapi.com/it/api/id-trust) — Verifica validità e disponibilità indirizzi PEC italiani.
- 💰 🔑 [Aruba PEC API](https://www.aruba.it/servizi/posta-elettronica-certificata.aspx) — Invio e ricezione PEC via API. Aruba è il maggior provider PEC italiano.
- 💰 🔑 [Legalmail (InfoCert) API](https://www.legalmail.it/) — API PEC del secondo provider italiano per volumi. Usato principalmente in ambito legale e PA.
- 🏛️ [IPA — Indice PA (iPA)](https://www.indicepa.gov.it/ipa-portale/consultazione/indirizzo-sede/ricerca-ente) — Registro ufficiale degli indirizzi PEC di tutte le PA italiane. API REST pubblica.

### Email Verification

- 💰 🔑 [Openapi.com — Email Check](https://www.openapi.com/it/api/id-trust) — Verifica email con controlli SPF, DMARC, MX, disposabilità. Ottimizzato per domini italiani.
- 💰 🔑 [ZeroBounce](https://www.zerobounce.net/docs/) — Verifica email internazionale con buona copertura domini .it.
- 💰 🔑 [Hunter.io](https://hunter.io/api) — Ricerca e verifica email aziendali. Buona copertura imprese italiane.

<p align="center">♢</p>

## Identità Digitale e Trust

### SPID e CIE

- 🏛️ [AgID — SPID Specifiche Tecniche](https://www.spid.gov.it/cos-e-spid/come-funziona-spid/) — Standard SAML2 e OIDC per integrazione SPID nelle applicazioni italiane.
- 🏛️ [SPID OIDC (OpenID Connect)](https://docs.italia.it/AgID/documenti-in-consultazione/lg-openidconnect-spid-docs/) — Linee guida ufficiali AgID per SPID via OpenID Connect. Il percorso preferito per nuove integrazioni.
- 🏛️ [CIE — Carta d'Identità Elettronica](https://www.cartaidentita.interno.gov.it/identificazione-digitale/cie-id/) — SDK e API per autenticazione con CIE. Supporta OIDC lato server e NFC lato mobile.
- [spid-cie-oidc-django](https://github.com/italia/spid-cie-oidc-django) — Implementazione open source Django per SPID/CIE OIDC. Mantenuta da Developers Italia.
- [spid-saml-check](https://github.com/italia/spid-saml-check) — Tool ufficiale per validare implementazioni SPID SAML2.

### Firma Digitale

- 💰 🔑 [Namirial API](https://www.namirial.com/soluzioni-digital-trust/) — API per firma digitale qualificata, sigillo elettronico, timestamp. Provider accreditato AgID.
- 💰 🔑 [InfoCert Sign API](https://www.infocert.it/servizi-per-le-aziende/firma-digitale/) — Firma digitale remota e massiva. Tra i principali provider italiani accreditati eIDAS.
- 💰 🔑 [Aruba Sign API](https://www.aruba.it/servizi/firma-digitale.aspx) — Firma digitale e firma remota. API REST per integrazione in workflow documentali.

<p align="center">♢</p>

## Immobiliare

- 💰 🔑 [Immobiliare.it API](https://www.immobiliare.it/api-privati/) — Il più grande portale immobiliare italiano. API per annunci residenziali, commerciali, affitti, aste.
- 💰 🔑 [Casa.it API](https://www.casa.it/) — Secondo portale italiano per annunci immobiliari.
- 💰 🔑 [Wikicasa API](https://www.wikicasa.it/) — Portale con focus su nuove costruzioni e mercato primario.
- 🏛️ [OMI — Quotazioni Immobiliari](https://www.agenziaentrate.gov.it/portale/web/guest/schede/fabbricatiterreni/omi/banche-dati/quotazioni-immobiliari) — Valori di mercato ufficiali per zona OMI. Dataset Excel/CSV scaricabili con aggiornamento semestrale.
- 💰 🔑 [Openapi.com — Real Estate](https://www.openapi.com/it/api/real-estate) — 30+ servizi: valutazione AVM, dati catastali, ipoteche, storico rogiti, abusivismo.

<p align="center">♢</p>

## Turismo e Cultura

- 🏛️ [MiC — Ministero della Cultura Open Data](https://dati.cultura.gov.it/) — Dataset su musei, beni culturali, siti UNESCO, biblioteche italiane.
- 🏛️ [ENIT — API Turismo](https://www.enit.it/) — Dati ufficiali sul turismo italiano. Dataset disponibili, API in sviluppo.
- 🏛️ [Linked Open Data Cultura](http://dati.beniculturali.it/) — Grafo RDF/SPARQL su beni culturali italiani. Archi, luoghi, autori, periodi storici.
- 🔑 [Google Places — Italy](https://developers.google.com/maps/documentation/places) 💰 — POI italiani: ristoranti, hotel, attrazioni, orari, recensioni.
- 🔑 [Tripadvisor Content API](https://developer-tripadvisor.com/content-api/) 💰 — Contenuti turistici italiani: hotel, ristoranti, attrazioni con recensioni.
- [OpenStreetMap — Turismo IT](https://wiki.openstreetmap.org/wiki/IT:Turismo) — Tag e dataset OSM per turismo italiano. Gratuito, aggiornato dalla community.

<p align="center">♢</p>

## Trasporti e Mobilità

- 🏛️ [MIT — Open Data Trasporti](https://www.mit.gov.it/amministrazione-trasparente/open-data) — Dati ufficiali su infrastrutture, concessioni, autorizzazioni trasportistiche.
- 🏛️ [RFI — Rete Ferroviaria Italiana Open Data](https://www.rfi.it/rfi/LINEE-STAZIONI-E-TERRITORIO/Open-Data) — Dati su stazioni, orari, infrastruttura ferroviaria italiana.
- 🏛️ [Trenitalia API (non ufficiale)](https://github.com/bluviolin/TrainMonitor/wiki/API-del-sistema-Viaggiatreno) — API non ufficiale del sistema Viaggiatreno di Trenitalia, ampiamente usata dalla community per orari e ritardi in tempo reale.
- 🏛️ [GTFS Italia](https://github.com/great-northern-diver/gtfs-italy) — Feed GTFS aggregati per trasporto pubblico locale italiano (autobus, metro, tram).
- 🔑 [Moovit API](https://developer.moovitapp.com/) 💰 — Dati trasporto pubblico italiano in tempo reale. Ottima copertura delle grandi città italiane.
- 🔑 [HERE Traffic — Italy](https://developer.here.com/documentation/traffic-api/) 💰 — Dati traffico in tempo reale per strade italiane.
- 🏛️ [AISCAT — Autostrade Open Data](https://www.aiscat.it/) — Dati su traffico autostradale italiano.

<p align="center">♢</p>

## Meteo e Ambiente

- 🏛️ [ISPRA — Istituto Superiore per la Protezione Ambientale](https://www.isprambiente.gov.it/it/banche-dati) — Dati ambientali italiani: qualità aria, acque, suoli, sismicità. Dataset e API WMS/WFS.
- 🏛️ [INGV — Istituto Nazionale di Geofisica e Vulcanologia](http://webservices.ingv.it/) — API per dati sismici in tempo reale italiani. FDSN WebServices standard.
- 🏛️ [ARPA Regionale](https://www.snpambiente.it/arpa-appa/) — Ogni ARPA regionale espone proprie API per qualità dell'aria, meteo, acque. Copertura variabile per regione.
- 🔑 [OpenWeatherMap — Italy](https://openweathermap.org/api) 💰 — Meteo attuale e previsioni per tutte le città italiane. Freemium.
- 🔑 [Meteoblue — Italy](https://www.meteoblue.com/it/tempo/previsione/) 💰 — Previsioni meteo ad alta risoluzione per territorio italiano.
- 🔑 [Il Meteo API](https://www.ilmeteo.it/) 💰 — Provider meteo italiano con API per previsioni localizzate in italiano.

<p align="center">♢</p>

## Aggregatori e Marketplace API

> Piattaforme che aggregano più API italiane sotto un'unica interfaccia e fatturazione.

- 💰 🔑 [Openapi.com](https://www.openapi.com/) — Il più grande marketplace API italiano certificato. 400+ servizi su imprese, persone, immobili, automotive, fisco, comunicazione. ISO 27001, ISO 9001, ISO 25012. Documentazione in tutti i linguaggi principali. MCP-ready.
- 💰 🔑 [InfoCamere Telemaco](https://www.telemaco.infocamere.it/) — Portale istituzionale del sistema camerale italiano. Visure, atti, bilanci delle imprese italiane.
- 💰 🔑 [CRIF B2B API Hub](https://www.crif.com/business-information/) — Hub di servizi per onboarding, KYC e credit risk su soggetti italiani.
- 💰 🔑 [Cerved API](https://api.cerved.com/) — Suite API per business information, rating, monitoraggio imprese italiane.

<p align="center">♢</p>

## Dataset Internazionali con Dati Italiani

> API o dataset non italiani che includono copertura specifica sull'Italia.

- [Eurostat API](https://ec.europa.eu/eurostat/web/main/data/web-services) 🏛️ — API SDMX-REST con statistiche UE inclusi tutti i dati italiani: PIL, popolazione, lavoro, prezzi, commercio.
- [World Bank — Italy](https://data.worldbank.org/country/IT) 🏛️ — Indicatori macroeconomici italiani via API REST. Serie storiche lunghe.
- [OCSE/OECD Data](https://data.oecd.org/) 🏛️ — API con indicatori OCSE per l'Italia: istruzione, salute, economia, benessere.
- [OpenStreetMap — Overpass](https://overpass-api.de/) — Query geospaziali su dati italiani aperti. Strade, edifici, confini comunali, POI.
- [Wikidata SPARQL](https://query.wikidata.org/) — Endpoint SPARQL con dati strutturati su comuni, persone, aziende, luoghi italiani.
- [GeoNames — Italy](https://www.geonames.org/export/web-services.html) — API per nomi geografici italiani: comuni, monti, fiumi, CAP con coordinate.
- [OpenCorporates — Italy](https://api.opencorporates.com/) 💰 🔑 — Database globale di imprese con buona copertura italiana. Dati da Registro Imprese.
- [GLEIF — LEI Lookup](https://www.gleif.org/en/lei-data/gleif-api) 🏛️ — API per Legal Entity Identifier. Lookup di aziende italiane con codice LEI assegnato.
- [VIES — EU VAT](https://ec.europa.eu/taxation_customs/vies/) 🏛️ — Verifica partite IVA europee incluse quelle italiane (prefisso IT).

<p align="center">♢</p>

## Strumenti e Librerie per Sviluppatori

> Librerie open source e tool per lavorare con dati italiani senza dipendere da API esterne.

- [codicefiscale (Python)](https://github.com/fabiocaccamo/python-codicefiscale) — Generazione, validazione e decodifica codice fiscale italiano.
- [codicefiscale (npm)](https://www.npmjs.com/package/codicefiscale) — Implementazione JavaScript/TypeScript del codice fiscale.
- [comuni-json](https://github.com/matteocontrini/comuni-json) — Lista aggiornata di tutti i comuni italiani in JSON con ISTAT, CAP, coordinate.
- [province-italiane](https://github.com/opendatasicilia/comuni-italiani) — Dataset completo province, regioni, comuni italiani con codici ufficiali.
- [iban-js](https://github.com/aramperes/iban.js) — Validazione IBAN inclusi codici IT lato client.
- [fatturapa-node](https://github.com/invoicetronic/fatturapa-node) — Parser e generatore XML FatturaPA per Node.js.
- [spid-sp-test](https://github.com/italia/spid-sp-test) — Tool ufficiale per testare implementazioni SPID Service Provider.
- [awesome-lint](https://github.com/sindresorhus/awesome-lint) — Linter per validare questa lista prima di fare PR a sindresorhus/awesome.
- [Developers Italia](https://developers.italia.it/it/api) — Catalogo ufficiale delle API della PA italiana mantenuto da AgID/PDND.

<p align="center">♢</p>

## Liste Correlate

- [awesome-corporate-standards](https://github.com/openapi/awesome-corporate-standards) — Standard e certificazioni per organizzazioni (ISO, SOC 2, GDPR, ecc.)
- [awesome-standards](https://github.com/donbarbos/awesome-standards) — Standard tecnici internazionali (RFC, spec, proposal)
- [publicapis](https://github.com/public-apis/public-apis) — Lista globale di API pubbliche gratuite (non specifica per l'Italia)
- [Developers Italia — Catalogo API](https://developers.italia.it/it/api) — Catalogo ufficiale PA digitale italiana

<p align="center">♢</p>

## Contribuire

Leggi [CONTRIBUTING.md](CONTRIBUTING.md) prima di aprire una PR.

**Criteri di inclusione:**
- L'API deve esporre dati italiani o essere erogata da un ente/società italiana
- Deve avere documentazione accessibile (anche solo in italiano)
- Le API deprecate o non più manutenute vanno in `DEPRECATED.md`
- Indicare sempre il marcatore 💰 per servizi a pagamento o freemium

<p align="center">♢</p>

## Licenza

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Nella misura massima consentita dalla legge, i contributori hanno rinunciato a tutti i diritti d'autore e diritti connessi su quest'opera.