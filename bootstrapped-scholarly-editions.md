---
title: "Open Arabic Periodical Editions"
subtitle: "A framework for bootstrapped scholarly editions outside the global north"
author: Till Grallert
date: 2020-07-03
ORCID: orcid.org/0000-0002-5739-8094
DOI: doi.org/10.5281/zenodo.
licence: http://creativecommons.org/licenses/by-nd/4.0/
bibliography: assets/bibliography/bootstrapped-scholarly-editions.csl.json
# csl: /BachUni/BachBibliothek/CSL/clio-medica.csl
csl: /BachUni/BachBibliothek/CSL/chicago-fullnote-bibliography-with-ibid.csl
lang: en-GB
markdown:
   - pandoc
   - CriticMarkup
tags:
    - periodical studies
    - digital divide
    - Arabic periodicals
    - digital humanities
---

<!-- # processing instructions -->
<!-- pre-process with pancritic -->
<!-- pancritic bootstrapped-scholarly-editions.md -t markdown --critic-mode accept -o bootstrapped-scholarly-editions_changes-accepted.md -->

# Introduction

<!-- importance of periodicals -->
 
Early Arabic periodicals published across the Eastern Mediterranean from the mid-nineteenth to the early twentieth centuries were at the core of social developments and formative discourses of modern(ising) societies that carry continued prominence across the region and beyond: the Arabic (cultural) renaissance (*nahḍa*), Arab nationalism or the Islamic reform movement (*ṣalafiyya*), to name just a few. Yet, the vast majority of journals and newspapers remain obscure and understudied beyond a few well-known titles from Beirut and Cairo. As physical artefacts---frequently printed with cheap ink on cheap paper and handled without care in transit---they are vulnerable to neglect and active destruction. Neoliberal defunding of cultural heritage institutions as a global phenomenon is compounded by an onslaught of iconoclasts, failing institutions, and wars ravaging Syria, Yemen, and Iraq.

<!-- need: access -->
Turning to Gil and Ortega's question of "What do we need?"[^6], the answer, therefore {==is==}{>>seems<<} simple: preservation and access! {--This *we*, here, shall refer first and foremost to --}Societies of the Global South {--that--} have a right to unhampered access to their own cultural record---a cultural record that is frequently held by institutions of the Global North.{>>and on their own terms<<} Access would also allow the scholarly communities concerned with the histories of Middle Eastern societies to study them through their own cultural production. 

[^6]: [@Gil+2016, 29]

{>>missing bit: brief summary of following sections<<}
{>>missing bit: comment on OpenArabicPE's corpus<<}
The following paper consists of two parts. I begin with challenging the equation of "digitisation = access" by outlining the various layers of inaccessibility inherent to existing digitisation efforts. The second part introduces the project Open Arabic Periodical Editions as an attempt to address some of the layers of inaccessibility through bootstrapping existing data, tools, and infrastructures into a framework to produce and distribute scholarly periodical editions under the affordances of {==the Global South==}{>>a specific region<<}.{>>I argue that by ...<<}

<!-- preservation is covered by access since it is a pre-condition for the former -->

# Inaccessibility of digitised Arabic periodicals

<!-- digitisation as solution but foremost a problem -->
Digitisation is the obvious answer to the need of preservation and access. Arabic periodicals are indeed being digitised and made available to online access for at least 15 years by a combination of private and public, non-profit and for-profit vendors. The terms *digitised* and *access* have power to evoke hyperbolic promises but they have always a concrete meaning bound to their particular historical context. Depending on who we are, digitised artefacts are fraught with multiple layers of *inaccessibility*.  

<!-- history of the press is under researched -->

The first layer of *inaccessibility* is rooted in the physical artefact and its history{--, and the collections within which it is currently kept--}{>>see next paragraph<<}. First and foremost, we will not know what we are a looking for and where we could do so. {--This is true for the physical artefact as well as its digital remediation.--} There is a plethora of encyclopaedic works on the Arabic press, listing titles and dates of first publication, but the individual history of the vast majority of publications remains unknown---particularly for cities beyond Cairo and Beirut.[^1] If we were interested in the series of food riots that shook cities across the pre-dominantly Arabic speaking provinces of the Ottoman Empire in summer 1910, we simply would not know which titles were actually published in Homs, Hama or Gaza. 

[^1]: E.g. {--[@Jundī+1925; @Shaykhū+1926; @Sarkīs+1928],--} {==[@Muruwwa+1961; @AlRifāʿī+1969b; @Dāghir+1950; @Dāghir+1978; @Ilyās+1982; @Khūrīya+1976; @ʿAbduh+1948; @Tikrītī+1969; @Ḥasanī+1957]==}{>>Arabic literature on the press<<}

The second layer of *inaccessibility* can be summarised by survival bias, collection bias, and digitisation bias. Surviving copies of early Arabic periodicals are scattered across libraries and private collections worldwide. {--Many collections remain unknown to scholarly communities.--} Known collections are frequently incomplete and predominantly located in the Global North. {--*We*, in the sense alluded to above, almost never had a chance to participate in curating these collections, which frequently--} Many of these periodical collections came about by chance and, to a large extent, reflect local, regional and global distribution networks and individual publishers' ability to gift library copies long after their publication.[^3] Existing catalogues are not necessarily published and with union catalogues haven fallen out of fashion,[^12] we would also be at a loss in locating a specific publication or the press output from a particular place at a given time. 
Digitisation and hosting digital artefacts are expensive and the cost scales almost linearly. In need to justify their expenses, curators will almost always turn to the rare and beautiful.{>><<} Hundreds of thousands of periodical pages in foreign languages are frequently not considered important enough to warrant this investment for institutions in the Global North. Funds, infrastructures and access to the physical artefacts, on the other hand, are commonly not available in the Global South. In consequence, we witness a neo-colonial absence of the Global South from the digital cultural record.[^23] In the absence of aggregators or an index, specific titles are incredibly hard to find in the patchwork of existing, eclectic collections of digitised periodicals.[^25]{-- we would need to identify the online platform(s) holding institutions of a particular periodical collaborated with in digitising this title.--}

![Map 1: Geographic distribution of library holdings of *al-Muqtabas* as recorded by Worldcat](../s0fb41f86/map-oclc_4770057679-holdings-vol_1-9.png)

{>>since we don't know how much was published, we cannot establish the relative amount of digitisation. Also, many institutions choose to scan the same periodical over and over again.<<}

[^3]: Muḥammad Kurd ʿAlī, for instance, gifted library copies of *al-Muqtabas* 2 from 1907/08 to his friend Jūrj Fākhūri in 1914 and to the library of al-Ṣalāḥiyya college in Jerusalem in 1916. The former is now held by the University of Minnesota and a facsimile is made available through [Hathitrust][hathitrust]. The later ended up in the al-Aqṣā Mosque's library in Jerusalem and was digitised by the British Library's [Endangered Archives Programme][eap]. Handwritten note on [*al-Muqtabas* 2(1), p.1](https://tillgrallert.github.io/digital-muqtabas/xml/oclc_4770057679-i_13.TEIP5.xml#pb_1.d2e814).
[^12]: [@ElHadi+1965; @Hopwood+1970; @Aman+1979; @DeJong+1979; @Iḥdādan+1984; @Khūrī+1985; @Höpp+1994; @Atabaki+1995]. {>>add comment on Arabic Union Catalogue <https://www.aruc.org/>: The Saudi platform *al-Fihris al-ʿArabī al-muwaḥḥad* (Arabic Union Catalogue) is unfortunately of limited use only because the information on holding institutions is rudimentary. Similar to Worldcat, ArUC allows multiple entries for the same entity.<<} 
[^23]: [@Risam+2019], c.f. [@Gooding+2018].{>>pages?<<}
[^25]: I am part of the endeavour to gather and openly share information on all holdings of  Arabic periodicals; [@Sadgrove+2012].


<!-- "technical" access: getting hold of the digital artefact -->
<!-- here, the we splits into haves and have-nots  -->

Once we established the potential location of the digitised artefact, we would need to get access to this remediation and immediately run into the third---{==socio-technical==}---layer of inaccessibility: Digital infrastructures, despite all promises towards the opposite, are rooted in the epistemic hegemony of late twentieth-century, anglo-american neoliberal capitalism. 
Most *digitised* periodicals are kept in data silos without any means for interchange or interoperability in the form of APIs or the option to download data in standardised, open file formats. Reading *access* to these silos is restricted by paywalls and geo-fencing.
Proprietary web-interfaces are commonly neither tailored to the display of Arabic material nor themselves available in Arabic.[^4] Downloading content in order to circumvent {>>geo-fencing and<<} ill-suited interfaces is limited to individually identifiable users. Bulk download frequently violates terms of use and most vendors try to prevent this on the technical level{-----at least in one case, bulk download will result in the vendor punishing subscribing institutions for violations from within their IP range--}.
Finally, bibliographic metadata is regularly limited to the issue level and woefully inadequate. This is due to ambiguity of data in the physical artefact, limited knowledge about these artefacts among librarians and the contractors, who did the actual digitising work, and software stacks incapable of handling anything but hegemonic Western concepts of dates and names and Western scripts. In consequence, bibliographic metadata are recorded and shared in transcription to Latin script---of which there are as many varieties as there are languages written in Latin script.[^5]


[^4]: On the need for Arabic interfaces see [@Mansour+2020; @Wrisley+2019; @Wrisley+2016]
[^5]: [@Grallert+2020]. Things have been improving over the years and many catalogues can now display Arabic script. But re-cataloguing is costly and not a priority for vendors. For an example, see EAP's digitisation of the Ottoman newspaper *Yenī Taṣvīr-i Efkār* from Istanbul, which was catalogued with the faulty Arabic title *Taṣwīr Afkār* and as published in Jerusalem; <https://eap.bl.uk/archive-file/EAP119-1-18-1#?c=0&m=0&s=0&cv=0>.{>>try to link to the IIIF manifest<<} 

<!-- table: ../../s0fb41f86/table_accessibility-of-digitised-collections.md -->

<!-- accessing the artefact itself: being unable to read -->

The fourth level of *inaccessibility* is the digital artefact itself: 
*Digitised* commonly means scanned facsimiles with limited or no text layer due, inter alia, to the abysmal state of Arabic OCR.[^7] Available text layers are frequently hidden, while vendors foreground full-text "search" that won't ever report false negatives and verifiable information on error rates is either inexistent or not published.
On the other hand, {~~grey~>informal~~} online-libraries of Arabic literature, most prominent and popular among them  [*al-Maktaba al-shāmila*][shamela] (The Comprehensive Library),[^27] {--[*Mishkāt*][almeshkat], [*Ṣayyid al-Fawāʾid*][saaid] or [*al-Waraq*][alwaraq]--} provide access to a small number of full-text editions of Arabic periodicals based on the work of anonymous human transcribers. Unfortunately, they do not provide information on editorial principles, the quality of the transcription or the material artefact they were based on.[^8] In addition, such informal "editions" lack information linking the digital remediation to the original artefact, namely bibliographic metadata and page breaks, which makes them almost impossible to employ for scholarly research. In a final twist, I found out that the informal editions from *al-Maktaba al-shāmila*, with all their gaps and omissions, were rendered as images with a pseudo-original layout to provide "fakesimiles" served through [*Arshīf al-majallāt al-adabiyya wa-l-thaqāfiyya al-ʿarabiyya*][alsharekh] (Archive of literary and cultural Arabic journals), the largest Arabic online platform for historical periodicals.[^28] {>>missing: consequence for scholarly research<<}
<!-- modelling? Na! -->

[^27]: {==missing footnote==}{>>on shamela.ws<<}
[^28]: There is a huge and unmarked gap in *al-Maktaba al-shāmila*'s transcription of *al-Muqtabas* 5(7) between [p.463](https://tillgrallert.github.io/digital-muqtabas/xml/oclc_4770057679-i_54.TEIP5.xml#pb_61.d1e2036) and [p.466](https://tillgrallert.github.io/digital-muqtabas/xml/oclc_4770057679-i_54.TEIP5.xml#pb_64.d1e2045), which is reproduced in [this "fakesimile"](https://archive.alsharekh.org/MagazinePages/Magazine_JPG/AL_moqtabs/Al_moqtabs_1910/Issue_7/605.JPG).

[^7]: [@Märgner+2012a] is still relevant for current platforms; see the Internet Archive's claim that Arabic is "currently not OCRable"; e.g. <https://archive.org/details/1_20191109_20191109_1843>. Recent years have seen huge advances with the application of machine-learning algorithms; c.f. [@Kiessling+2017]. They will eventually find their way into Hathitrust etc.; see {==missing reference==}{>>announcement of grant for OpenITI, https://www.hathitrust.org/htrc-awards-three-acs-projects<<}. But without GUI's (in Arabic!) and due to their reliance on server-side computing, which needs to be paid, these also remain largely inaccessible {==to the general public==}{>>improve<<}.  

[^8]: We found that *al-Maktaba al-shāmila* consequently removed footnotes and terms in scripts other than Arabic. Transcribers normalised the text occasionally left notes in the text, stating that they couldn't decipher a line etc., from which we know that they were Arabic speakers. For evaluations of *al-Maktaba al-shāmila* as the basis for scholarly corpus building efforts see [@Belinkov+2016; @Alrabiah+2013].

<!-- Affordances of the Global South -->
These layers of inaccessibility have an already crippling effect on any Arabic speaker from Syria, Jordan or Palestine with only limited knowledge of foreign languages, particularly English, and no affiliation with wealthy institutions from the Global North.{--, we are faced by multiple levels of *inaccessibility*.--} They are, however, further compounded by the infrastructural dependencies of digital remediations on access to devices, internet connections, and electricity. Neither of these can be taken for granted for the societies of the Global South. In the---all too frequent---worst case, devices are old, internet connections are slow, traffic is prohibitively expensive, and electricity is perilously scarce.[^11] Let me illustrate this multi-layered "digital divide"[^15] with the Lebanese example: At least 30 per cent of the population live on less than 120 USD a month in Lebanon.[^9] Mobile internet connection costs about 40 USD for 20GB traffic or 30-days, whatever is less. People depend on mobile internet because landlords avoid paying council tax by not registering contracts with the council. Without a registered rent contract, people cannot sing-up for a landline.[^10] Electricity is another major issue. The single, state-run utility relies on insufficient power plants and imported fuel and even the capital city of Beirut suffers from regular daily power cuts of three hours.[^26] Although heavily subsidised {>>one third of the state budget?<<}, electricity is expensive and easily comes in at about 120 USD per month per household. There is no available data on the cost of generator subscriptions, but we pay another 80 USD in an up-market neighbourhood of Beirut.
The impact of these infrastructural realities is not limited to users of digital cultural artefacts but also severely impacts institutions planning to host them. {--My employer, a well-funded, mid-sized academic research institute of some 20 employees, has recently doubled its broadband speed to 24 Mbps.--}

<!-- impact on institutional digitisation efforts -->
[^26]: Corruption and waste are not the only culprits to blame. Israel deliberately damaged and destroyed power plants in the 2006 war.
[^15]: {==For a recent conceptualisation of the term see [@Ragnedda+2019]. Unfortunately, while acknowledging the multiple socio-technological layers, they focus solely on the internet and do not mention the hegemony of English.==}{>>This is also true for [@Townsend+2013, 168-193]. add literature on the digital divide. This might also alread be part of [^11]<<}
[^9]: [@chadi2018UNDPLatestPoverty; @fadel2018ThirdLebaneseLive]  with reference to inaccessible UNDP report "Rapid Poverty Assessment in Lebanon" for 2016.
[^10]: According to [@CentralIntelligenceAgency+2020] only 15% of inhabitants have access to a landline and less than 1% have a broadband subscription, while 73% have a mobile phone. 
[^11]: C.f. [@Aiyegbusi+2019]


# Bootstrapping for access

["Open Arabic Periodical Editions" (OpenArabicPE)][openarabicpe_blog] was born out of frustration in August 2015 in order to address the socio-technical layers of inaccessibility of existing digitised Arabic periodicals with the affordances of the Global South. {>>I met Alex Gil in spring and summer 2015<<} Building on the guiding principles of *simplicity* and *credibility* for the sake of *accessibility* and *sustainability*, OpenArabicPE was inspired by Alex Gil's talk on *minimal computing* at [Digital Humanities Institute---Beirut][dhib] and discussions at [Digital Humanities Summer Institute][dhsi] 2015. The idea is simple: re-use---sometimes creatively---openly available data, tools, and infrastructures {--in order --}to produce open, collaborative, scholarly digital editions of early Arabic periodicals. OpenArabicPE's resources are extremely constrained: we have no funds, no staff and no equipment beyond volunteering interns. {==My employer certainly enjoys patting me on the shoulder for engaging the digital humanities but I still mostly work on it after hours and on my own computer.==}  OpenArabicPE, therefore, also represents (and reflects the changing boundaries of) my own ability "to produce, disseminate, and preserve digital scholarship ourselves, without the help we can't get, even as we fight to build the infrastructures we need at the intersection of, with, and beyond institutional libraries and schools."[^22] As such, OpenArabicPE resembles an attempt at what Valeria Graziano, Marcell Mars and Tomislav Meda have recently called "pirate care".[^24]

[^22]: [@Gil+2016, 29]
[^24]: [@Graziano+2019]. See also [@Mars+2019].

## The data layer

On the data level, OpenArabicPE combines the virtues of immensely popular, but non-academic {--(and, at least under US copyright laws, occasionally illegal)--}{~~grey~>informal~~} online libraries of volunteers on the one hand with academic/institutional scanning efforts as well as editorial expertise on the other. To this end, we transformed the digital text (EPub, HTML) of six periodicals from [*al-Maktaba al-shāmila*][shamela][^30] into an open, standardised file format (XML) following the [Text Encoding Initiative (TEI)][tei]'s guidelines[^2] and link each page to digital facsimiles from various sources, namely [EAP][eap], [HathiTrust][hathitrust], and [*Arshīf al-majallāt al-adabiyya wa-l-thaqāfiyya al-ʿarabiyya*][alsharekh]. We also model the periodicals with light structural mark-up for articles, sections, mastheads and bylines and other bibliographic information.[^13] Bibliographic metadata on every article and in common standardised formats such as BibTeX and MODS (Metadata Object Description Schema) is then automatically generated from the modelled source.[^16] Thus, we provide the advantages of truly digital editions and a means to verify the text layer and our mark-up against facsimiles of the original artefact. Linking page breaks to facsimiles, although trivial, is extremely labour-intensive because they seemingly did not matter enough to the anonymous transcribers of *al-Maktaba al-shāmila* to be consistently recorded. Each of the c.8000 page breaks in [*al-Muqtabas*][muqtabas_git] and [*al-Ḥaqāʾiq*][haqaiq_git], therefore, needed to be manually marked up by volunteers.[^14] My gratitude goes to Dimitar Dragnev, Talha Güzel, Dilan Hatun, Hans Magne Jaatun, Xaver Kretzschmar, Daniel Lloyd, Klara Mayer, Tobias Sick, Manzi Tanna-Händel and Layla Youssef, who have contributed their time to this task.

[^30]: {==Footnote on shamela.ws? or is the first one sufficient?==}
[^2]: [@teiconsortium2020TEIP5Guidelines]. TEI XML is the quasi-standard of textual editing and required by funding bodies and repositories for long-term archiving; cf. [@DfgPraxisregelnDigitalisierung+2016].
[^13]: Our TEI customisation for Arabic periodicals is openly available at <https://github.com/OpenArabicPE/OpenArabicPE_ODD>.
[^14]: In other instances, such as the journals [*Lughat al-ʿArab*][lughat_git] and [*al-Ustādh*][ustadh_git], *al-Maktaba al-shāmila* did provide page breaks that correspond to a printed edition.
[^16]: Our code is openly available at <https://github.com/OpenArabicPE/convert_tei-to-bibliographic-data>. It uses `<tei:biblStruct>` as an intermediary format and can also generate YAML and Zotero RDF.

{>>add table of our corpus<<}

## The presentation layer

TEI XML is certainly not *simple* and comes with a steep learning curve. Bidirectional XML with left-to-right tags and right-to-left text is not particularly *accessible* either, even if specialised XML-editing software would better support it. However, TEI is both *sustainable* and *credible* as an underlying format and the direction of a script is only relevant if rendered on a two-dimensional surface for human readers and editors. 

Presenting facsimiles and text layers side-by-side for the validation of the latter with the help of the former is core to OpenArabicPE's claim of credibility. Therefore, and in order to make the editions accessible to readers with as little overhead as possible, we heavily modified the [TEI Boilerplate](http://dcl.slis.indiana.edu/teibp/) for the use with Arabic texts. Our adaptation of the TEI Boilerplate also provides access to a table of contents, limited browsing to neighbouring issues, and bibliographic metadata on the article level.[^17] By rendering XML files locally in a web browser on the reader's computer with XSLT and CSS, we remove the need for backend servers and internet connections. Editions can be downloaded, distributed through USB keys, and run locally. This also removes the need to produce reading surrogates whenever the main TEI XML was changed.

[^17]: [@walsh2016TEIBoilerplate; @walsh2013TEIBoilerplate]. Our version of the TEI Boilerplate is openly available at <https://github.com/OpenArabicPE/tei-boilerplate-arabic-editions>.

Linking to digital facsimiles already available on the internet is commonly legal and since hosting and serving large files is expensive, it is the preferred option from our project's point of view. If we were to produce our own facsimiles through scanning, I would recommend uploading them to the [Internet Archive][internetarchive], which currently develops IIIF support.[^21] From the readers' perspective, linked online facsimiles require stable, fast and affordable internet connections. Downloading them once and serving them {~~from the local machine~>locally~~} would be the preferred option but will most likely violate user agreements, licences and copyright depending on vendors and jurisdictions (It is, nevertheless, trivial since the links are an inherent part of the TEI XML files' `<facsimile>` node). 

[^21]: According to example code in the documentation, IIIF support is in development since at least 2015; [@IIIFDocumentation].

<!-- Zotero: solves the problem of browsing/search across issues with no backend -->
Distributing digital corpora of hundreds of periodical issues without a backend severely restricts the ability to search and browse across issues. The (academic) reference manager [Zotero][zotero] is a staple of the open-source community, which, among many other things, allows sharing an unlimited amount of bibliographic references for free. I, therefore, opted to host all bibliographic metadata in a constantly updated public [Zotero Group][openarabicpe_zotero] instead of building a static website with pre-computed indexes, tables of contents etc. Each reference in Zotero links to the relevant section in the periodical editions through a stable URL. Readers can, therefore, use either Zotero's web interface or standalone client as a port of entry to all of OpenArabicPE's editions. {>>I also contemplate attaching the full text of each article to the Zotero references as a note to provide basic full-text search across the entire corpus.<<}

## Facilitating re-use through licenses

{--There are great arguments for copyleft but --}Within the academic framework we are operating in, we depend on explicit licences to facilitate the use and re-use of our data and tools.[^18] We assume that the content of periodicals published across the Eastern Mediterranean before 1920 is in the public domain even under the most restrictive definitions (i.e. US copyright law). {>>this view is obviously shared by all vendors of facsimiles<<} The enormous amount of human labour required for digitising cultural artefacts, on the other hand, is commonly actively hidden---within academic historiography, for instance, using digital remediations is still frowned upon as cheating (everybody does it but only few talk about it).[^29] Retaining copyright of our own editorial contributions in the form of [Creative Commons Attribution-ShareAlike 4.0 International][cc-by-sa-4] {==is at least a reminder that all contributors need to be transparently credited==}{>>phrasing<<} for their work. {==We share our tools under a [MIT licence][mit-license] whenever possible. ==}{>>this needs more work<<}

[^18]: For a great introduction to the conceptual critique of copyrights see [@Hall+2016, 1-9]. For a specific application to TEI XML files see [@Hannesschläger+2020].
[^29]: This is evidenced by the few references to the URLs of works from *al-Maktaba al-shāmila* in academic texts. JSTOR returns a total of 16 hits{>> 2020-07-07: <https://www.jstor.org/action/doBasicResults?acc=off&Query=shamela.ws&wc=on&fc=off&group=none&refreqid=search%3Ab890d4a34c3e21a4999f950b7d357685> <<}. 

## The infrastructure

Editions and tools are maintained using a combination of `.git` and [GitHub](github) for distributed version control. Each edit is transparently credited to a contributor with an email address and a timestamp. Github also provides free hosting of the TEI Boilerplate-based webview for our editions through [GitHub Pages][gh-pages]. Github, of course, is a commercial platform and nowadays owned by Microsoft. They might go out of business at any point in the future but they are a core staple of the open-source movement. The platform itself is built on open-source software, protecting us against a lock-in of our data, and its {==services==}{>>expand on what they are<<} are free-of-cost to the user.

<!-- Zenodo -->
While platforms for shared version control, such as GitHub, are great for collaborative editing and hosting data, they cannot replace an archive or long-term repository. We use [Zenodo][zenodo] for this purpose. Zenodo is an open and free-to-use, EU-funded research data repository originally developed by the European Organization for Nuclear Research (CERN). Zenodo registers (versioned) [Digital Object Identifiers (DOI)][doi] and integrates with various Open Science infrastructures such as scholarly aggregators of metadata or [Open Researcher and Contributor ID (ORCID)][orcid] for unambiguously identifying contributors. Zenodo also integrates with GitHub by automatically archiving each release of data and tools and recording all contributors as found in the `.git` repository. 


## Problems of bootstrapping

The main problem of bootstrapping is the reliance on external data, tools, and services, which are beyond our control. Every one of these dependencies will eventually break. The only question is when. The main mitigation strategies are open and widely supported standards and a minimal software stack. On the data level, the links to the facsimiles are the most volatile component and we already encountered three major instances of link rot. Two were caused by vendors moving servers and changing protocols: The British Library moved the Endangered Archives Programme to IIIF in 2017 and *Arshīf al-majallāt al-adabiyya wa-l-thaqāfiyya al-ʿarabiyya* moved to {==a new domain==}{>>from http://archive.sakhrit.co to http://archive.alsharekh.org/ <<} in 2019. In another instance, Hathitrust removed the facsimiles of Princeton's copy of *al-Haqāʾiq* (vol.1, 1910) from the public domain in 2016.[^31]

[^31]: My inquiries about the legal basis for this decision have not been replied to

On the representation layer, TEI Boilerplate was the only viable option to render TEI XML files in the browser without a backend in 2015 and it still works. However, web browsers and the TEI {--world--} have moved on. All major browsers still support XSLT transformation but with two limitations: First, {==the web has moved on==}{>>better phrasing<<} to Javascript and JSON. XSLT support is stuck with version 1, which was superseded by XSLT 2 in 2007 and XSLT 3 in 2017. If (!) browsers continue to support XSLT, it won't be further developed. Second, browser vendors tighten the screws on security. Running XSLT transformations on local files is considered attempted cross-site scripting and, consequently, aborted by Google's Chrome. Firefox will transform local XML files but only with remotely hosted XSLT. At the time of writing, only Apple's Safari allows for rendering our editions without any internet connection.{>>According to the documentation, a local webserver, i.e. `localhost`, is fine<<} Third, [CETEIcean][ceteicean] has matured into a Javascript-based alternative to TEI Boilerplate with the support of the TEI consortium.[^19] All future developments of OpenArabicPE's webview will therefore move to CETEIcean.

Hosting is another challenge. I originally decided to directly render XML files as available in the GitHub repositories. This made sure that readers always saw the most current version of the data without any additional steps. [Rawgit][rawgit-old] allowed to directly serve files from any branch of a GitHub repository with the correct content type. But the service was shut down in 2019 because people ran malware exploits directly from their GitHub repositories.[^20] OpenArabicPE has therefore moved to GitHub's own [GitHub Pages][gh-pages] service, which serves files from the `gh-pages` branch.

[^19]: [@cayless2020CETEIcean; @cayless2018CETEIceanTEIBrowser]
[^20]: <http://rawgit.com> shut down in 2019. There since emerged a replacement service at <https://rawgit.org/>.

{>>comment on the necessity of an internet connection for loading the images<<}

# conclusion

{==still missing==}


[almeshkat]: http://almeshkat.net/
[alsharekh]: http://archive.alsharekh.org/
[alwaraq]: http://www.alwaraq.net/
[bibalex]: http://ima.bibalex.org/IMA/presentation/home/list.jsf
[cc-by-sa-4]: http://creativecommons.org/licenses/by-sa/4.0/
[ceteicean]: https://github.com/TEIC/CETEIcean
[dhib]: https://dhibeirut.wordpress.com/
[dhsi]: https://dhsi.org/
[doi]: https://doi.org
[eap]: http://eap.bl.uk/
[github]: https://www.github.com
[gh-pages]: https://pages.github.com/
[hathitrust]: http://catalog.hathitrust.org/
[internetarchive]: https://archive.org/
[menadoc]: http://menadoc.bibliothek.uni-halle.de/
[mit-license]: https://opensource.org/licenses/MIT
[muqtabas_git]: https://github.com/tillgrallert/digital-muqtabas 
[haqaiq_git]: https://github.com/OpenArabicPE/journal_al-haqaiq
[lughat_git]: https://github.com/OpenArabicPE/journal_lughat-al-arab
[ustadh_git]: https://github.com/OpenArabicPE/journal_al-ustadh
[openarabicpe_schema]: https://github.com/OpenArabicPE/OpenArabicPE_ODD
[openarabicpe_blog]: https://openarabicpe.github.io
[openarabicpe_zotero]: https://www.zotero.org/groups/OpenArabicPE
[orcid]: https://orcid.org/
[rawgit-old]: https://github.com/rgrove/rawgit
[saaid]: http://saaid.net/
[sakhrit]: http://archive.sakhrit.co
[shamela]: http://www.shamela.ws/
[tei]: https://www.tei-c.org
[zenodo]: https://www.zenodo.org
[zotero]: https://www.zotero.org

