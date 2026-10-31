# Jerry Gamblin

Head of Research at Empirical Security and founder of RogoLabs: I take the CVE list apart and publish what I find.

I work on vulnerability data for a living at [Empirical Security](https://www.empiricalsecurity.com). Then I go home and keep working on it at [RogoLabs](https://rogolabs.net), my open-source lab. Rogo is Latin for "I ask," which is most of the job. I also sit on the CVE Program's Quality, Automation and Consumer working groups.

## The RogoLabs toolkit asks one question per site

| Tool | The question it answers | Code |
|---|---|---|
| [CVE.ICU](https://cve.icu) | What is in the CVE list right now? Rebuilt whenever a fresh NVD snapshot lands. | [RogoLabs/cve.icu](https://github.com/RogoLabs/cve.icu) |
| [CVEForecast](https://cveforecast.org) | How many CVEs are coming next? | [RogoLabs/CVEForecast](https://github.com/RogoLabs/CVEForecast) |
| [CVE Floodline](https://cvefloodline.org) | Is a jump in CVE volume rain or a flood? Uses EPSS and CISA KEV to tell them apart. | [RogoLabs/cvefloodline.org](https://github.com/RogoLabs/cvefloodline.org) |
| [RBP Tracker](https://rbptracker.org) | Which CVE IDs are cited in public advisories but still sit in Reserved? | [RogoLabs/RBP](https://github.com/RogoLabs/RBP) |
| [CNA Scorecard](https://cnascorecard.org) | How complete, accurate and timely is each CNA's data? | [RogoLabs/CNAScoreCard](https://github.com/RogoLabs/CNAScoreCard) |
| [CNAPulse](https://cnapulse.org) | Which CNAs are publishing more, or less, than their own baseline? | [RogoLabs/CNAPulse](https://github.com/RogoLabs/CNAPulse) |
| [PatchThis.app](https://patchthis.app) | What should you patch first, ranked by exploitability instead of CVSS? | [RogoLabs/patchthisapp](https://github.com/RogoLabs/patchthisapp) |
| VulnRadar | Which new CVEs touch your stack? A watchlist that files GitHub issues. | [RogoLabs/VulnRadar](https://github.com/RogoLabs/VulnRadar) |

Talk slides and recordings live on [rogolabs.net](https://rogolabs.net). Data reviews and build logs live on [jerrygamblin.com](https://jerrygamblin.com).

Every number on these sites comes from a public feed and a script you can read. If one looks wrong, open an issue on that repo and show me. I would rather be corrected than believed.
