# hashlookup project

The [hashlookup project](https://github.com/hashlookup) provides a complete set of open source tools and [open standards](https://datatracker.ietf.org/doc/draft-dulaunoy-hashlookup-format/) to lookup hash values against known database of files. Hashlookup helps to improve and speed-up Digital Forensic and Incident Response (DFIR) by providing a readily-accessible list of known files metadata published. 

## Presentations

- 2021 at "Unlock Your Brain, Harden Your System" conference in Brest - [How to improve and speed-up DFIR with hashlookup - indexing all the published software](https://github.com/hashlookup/hashlookup-format/blob/main/slides/2021-Unlock-Your-Brain/main.pdf) 
- 2022 at FIRSTCON22 conference in Dublin - [How to Secure Your Software Supply Chain and Speed-Up DFIR with Hashlookup](https://raw.githubusercontent.com/hashlookup/hashlookup.io/main/slides/20220630-FIRSTCON22-hashlookup.pdf)

## Public online hashlookup services

- [CIRCL hashlookup (hashlookup.circl.lu)](https://www.circl.lu/services/hashlookup/) - API [hashlookup.circl.lu](https://hashlookup.circl.lu/)
- [Metalookup public web interface - Find published software by hashes](https://www.metalookup.com/) 

### Tools using hashlookup services or dataset

- [hashlookup-forensic-analyser](https://github.com/hashlookup/hashlookup-forensic-analyser) Analyse a forensic target (such as a directory) to find and report files found and not found from CIRCL hashlookup public service or offline with Bloom filters. This tool can help a digital forensic investigator to know the context, origin of specific files during a digital forensic investigation.
- [PyHashlookup](https://github.com/hashlookup/PyHashlookup) is a client API in Python to query CIRCL hashlookup.
- [The Hive Project - Cortex Analyzers](https://github.com/TheHive-Project/Cortex-Analyzers/pull/1015) pull-request to be integrated in The Hive Cortex Analyzers.
- [MISP module hashlookup expansion](https://misp.github.io/misp-modules/expansion/#hashlookup) is a [MISP module](https://www.misp-project.org/) allowing to lookup and expand from hashlookup.
- [munin - Online Hash Checker for Virustotal and Other Services](https://github.com/Neo23x0/munin) includes the support for hashlookup.
- [R package to query hashlookup](https://github.com/hrbrmstr/hashlookup).
- [PyOTI - Python Open Threat Intelligence](https://github.com/RH-ISAC/PyOTI).
- [Demisto - CIRCL Hashlookup on Cortex XSOAR](https://github.com/demisto/content/tree/30abdb6a7f2f7a9ec3486948df76d34d5a61c792/Packs/CIRCLHashlookup/Integrations/CIRCLEHashlookup).
- [FACT - core](https://github.com/fkie-cad/FACT_core/tree/master/src/plugins/analysis/hashlookup) - The Firmware Analysis and Comparison Tool (FACT).
- [Hash Hunter](https://github.com/mattnotmax/hash_hunter).
- [UAC_processor](https://github.com/timtaylor3/UAC_processor).

## Public dataset

- [CIRCL hashlookup Bloom Filter dataset](https://cra.circl.lu/hashlookup/hashlookup-full.bloom) ( :warning: 800+ MB) with all the known SHA-1 values from hashlookup.circl.lu.

## Who is behind the hashlookup project

The project is run by [@adulau](https://github.com/adulau/), [@gallypette](https://github.com/gallypette) with the help of many contributors.

