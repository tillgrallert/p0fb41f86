---
title: "Open Arabic Periodical Editions: a framework for bootstrapped scholarly editions outside the global north"
author: Till Grallert
date: 2020-06-19 12:00:47 +0200
ORCID: orcid.org/0000-0002-5739-8094
---


<!-- importance of periodicals -->
Periodicals are an important cultural artefact but are threatened by decay and destruction and all but inaccessible. 

<!-- need: access -->
Turning to Gil and Ortega's question of "What do we need?"[^6], the answer seems simple: we need access! This *we*, here, shall refer first and foremost to societies of the Global South that have a right to unhampered access to their own cultural record---a cultural record that is frequently held by institutions of the Global North. This *we*, however, also includes global scholarly communities and general audiences interested in reading and studying this cultural artefact {==since this paper and the project at its centre are authored/directed by a white, German, cis man, employed by a publicly funded German research institute in Lebanon.==}{>>improve<<}

[^6]: [@Gil+2016, 29]

<!-- preservation is covered by access since it is a pre-condition for the former -->

<!-- digitisation as solution but foremost a problem -->
Digitisation is the obvious answer to both destruction and access. Arabic periodicals are indeed being digitised and made available to online access for at least 15 years by a combination of private and public, non-profit and for-profit vendors. The terms *Digitised* and *access* have power to evoke hyperbolic promises. Their concrete meanings, however, are the crux of the matter. Depending on who we are, *digitised* artefacts are fraught with multiple layers of *inaccessibility*.  

<!-- history of the press is under researched -->
The first layer of *inaccessibility* {==pre-dates==}{>>better wording needed: this is the pre-condition of digitisation<<} digitisation and is rooted in the physical artefact, its history, and the collections within which it is currently kept. 
First and foremost, we will not know what we are a looking for and where we could do so. This is true for the physical artefact as well as its digital remediation. There is a plethora of encyclopaedic works on the Arabic press, listing titles and dates of first publication, but the individual history of the vast majority of publications remains unknown---particularly for cities beyond Cairo and Beirut.[^1] We simply won't know which titles were published during, let's say, June 1910 in Aleppo.

[^1]: {==Missing footnote==}{>>Arabic literature on the press<<}

<!-- collections: we are not the curators -->
Surviving copies are distributed across libraries worldwide. *we*, in the sense alluded to above, almost never had a chance to participate in curating these collections, which frequently came about by chance and, to a large extent, reflect {>>local, regional and global<<} distribution networks and individual publishers' ability to gift library copies long after their publication.[^3] In the absence of union catalogues for Arabic periodicals,[^2] we would also be at a loss in locating a specific publication or the press output from a particular place at a given time. Finally, we would need to find the online platform(s) the holding institution(s) of a particular periodical collaborated with in digitising this title. 

[^2]: {==Missing footnote==}{>>available union catalogues<<}
[^3]: Muḥammad Kurd ʿAlī, for instance, gifted library copies of *al-Muqtabas* 2 from 1907/08 to his friend Jūrj Fākhūri in 1914 and to the library of al-Ṣalāḥiyya college in Jerusalem in 1916. The former is now held by the University of Minnesota and a facsimile is made available through Hathitrust. The later ended up in the al-Aqṣā Mosque's library in Jerusalem and was digitised by the British Library's Endangered Archives Programme. Handwritten note on [*al-Muqtabas* 2(1), p.1](https://tillgrallert.github.io/digital-muqtabas/xml/oclc_4770057679-i_13.TEIP5.xml#pb_1.d2e814).


<!-- "technical" access: getting hold of the digital artefact -->
<!-- here, the we splits into haves and have-nots  -->

{--If we imagine ourselves to be an Arabic speaker from Syria, Jordan or Palestine with only limited knowledge of foreign languages, particularly English, and no affiliation with wealthy institutions from the Global North, we are faced by multiple levels of *inaccessibility*.--}{>>this needs to a meaningful position<<}
Once we established the potential location of the digitised artefact, we would need to get access to this remediation and immediately run into the second layer of inaccessibility:
First, most *digitised* periodicals are kept in data silos without any means for interchange or interoperability in the form of APIs or the option to download data in standardised, open file formats.
Second, reading *access* to these silos is restricted by paywalls and geo-fencing.
Third, bibliographic metadata is regularly limited to the issue level and woefully inadequate. This is due to ambiguity of data in the physical artefact, limited knowledge about these artefacts among librarians and the contractors, who did the actual digitising work, and software stacks incapable of handling anything but hegemonic Western concepts of dates and names and Western scripts.[^5]
Fourth, proprietary web-interfaces are commonly neither tailored to the display of Arabic material nor themselves available in Arabic.[^4]
Fifth, downloading content that in order to circumvent ill-suited interfaces is limited to individually identifiable users. Bulk download frequently violates terms of use and most vendors try to prevent such violations on the technical level{-----at least in one case, bulk download will result in the vendor punishing subscribing institutions for violations from within their IP range--}.


[^4]: On the need for Arabic interfaces see [@Mansour+2020; @Wrisley+2019; @Wrisley+2016]
[^5]: [@Grallert+2020]. Things are improving over the years and many catalogues can display Arabic script. But re-cataloguing is costly and not a priority for vendors. See EAP's digitisation of the Ottoman newspaper *Yenī Taṣvīr-i Efkār* from Istanbul, which was catalogued with the faulty Arabic title *Taṣwīr Afkār* and as published in Jerusalem; <https://eap.bl.uk/archive-file/EAP119-1-18-1#?c=0&m=0&s=0&cv=0>.{>>try to link to the IIIF manifest<<} 

<!-- accessing the artefact itself: being unable to read -->
Even if we gained access to the digital artefact, we'll find the artefact itself {==inaccessible to==}{>>better? resisting<<} scrutiny: 
*Digitised* frequently means scanned facsimiles with limited or no text layer due, inter alia, to the state of Arabic OCR.[^7] Available text layers are frequently hidden and one cannot find verifiable information on error rates. Vendors tend to foreground full-text "search" that won't ever report false negatives.
<!-- modelling -->

[^7]: Because large-scale digitisation takes time, [@Märgner+2012a] is still relevant for current platforms; see <archie.org>'s claim that Arabic is "currently not OCRable"; e.g. <https://archive.org/details/1_20191109_20191109_1843>. Recent years have seen huge advances in the field with the application of machine-learning algorithms; c.f. [@Kiessling+2017]. They will eventually find their way into Hathitrust etc.; see {==missing reference==}{>>announcement of grant for OpenITI, https://www.hathitrust.org/htrc-awards-three-acs-projects<<}. But without GUI's (in Arabic!) and due to their reliance on server-side computing, which needs to be paid, these remain largely inaccessible {==to the general public==}{>>improve<<}.  