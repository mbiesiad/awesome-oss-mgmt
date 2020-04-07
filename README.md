# Lista niesamowitych narzędzi do zarządzania programami Open Source - Awesome OSS Management [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Lista zawiera w sobie wyselekcjonowane pakiety i projekty, które zostały zbudowane przez członków Grupy TODO lub uznane za pomocne w zarządzaniu projektami i biurami typu open source.

## Zawartość
* [Code Reviews - Przegląd kodu](#code-reviews---przegl%C4%85d-kodu)
* [Contributor License Agreements](#contributor-license-agreements)
* [GitHub Metrics oraz Dashboards](#github-metrics-oraz-dashboards)
* [Zarządzanie GitHub](#zarządzanie-github)
* [Jakość projektu](#jakość-projektu)
* [Supply Chain Trust](#supply-chain-trust)
* [Licencje](#licencje)
* [Localization oraz Internationalization](#localization-oraz-internationalization)
* [Strony i dokumentacja](#strony-internetowe-i-dokumentacja)
* [Licencja](#licencja)
* [Bezpieczeństwo](#bezpieczeństwo)


## Code Reviews - Przegląd kodu

- [mention-bot](https://github.com/facebookarchive/mention-bot) - wspomniany bot automatycznie wspomina o potencjalnych recenzentach przy pull requestach. Pomaga uzyskać szybszą realizację pull requestów, angażując odpowiednie osoby wcześnie.
- [PullApprove](https://www.pullapprove.com) - pozwala na bardziej wyrafinowane reguły zatwierdzania pull requestów.
- [sentinel](https://github.com/habitat-sh/sentinel) - bot pod PR Test, review oraz merge workflow
- [pull-review](https://github.com/imsky/pull-review) - inteligentnie przypisuj recenzentów pull requestów, zainspirowany przez mention-bot
- [pull-request-size](https://github.com/noqcks/pull-request-size) - automatycznie dodaje etykiety GitHub na podstawie rozmiaru pull requesta.
- [Pullie](https://github.com/godaddy/pullie) - GitHub App która pomaga w PR: żąda recenzji, łączy tickety Jira, daje znać gdy brakuje wymaganych zmian w plików (np. wpisy dziennika zmian, changelog'a)

## Contributor License Agreements

- [CLA Assistant](https://github.com/cla-assistant/cla-assistant) - Usprawnij przepływ pracy i pozwól asystentowi CLA zająć się prawną stroną wkładów do repozytorium. Asystent CLA umożliwia współtwórcom podpisywanie umów CLA z poziomu pull request.
- [DCOB](https://github.com/chef/dcob) - Bot do wymuszania podpisania certyfikatu autora dla każdego zatwierdzenia w PR
- [CLA Portal](https://github.com/vmware/claportal) - Umożliwia przepływ pracy dla autorów, którzy podpisują umowę CLA dotyczącą pull requestów do repozytoriów GitHub. Obsługuje także podpisywanie DCO w commitach.
- [OSS Contribution Tracker](https://github.com/amzn/oss-contribution-tracker) - Śledź wkład wniesiony do projektów zewnętrznych i zarządzaj CLA
- [Dr CLA](https://github.com/salesforce/dr-cla) - GitHub bot do czynności z umowami licencyjnymi dla współtwórców

## GitHub Metrics oraz Dashboards

- [oss-dashboard](https://github.com/amzn/oss-dashboard) - Pulpit do przeglądania wielu organizacji GitHub i/lub użytkowników jednocześnie.
- [osstracker](https://github.com/Netflix/osstracker) - OSS Tracker to aplikacja, która zbiera informacje o organizacji Github i agreguje dane we wszystkich projektach w tej organizacji w jednym interfejsie użytkownika, z którego mogą korzystać różne role w organizacji będącej właścicielem.
- [ghcrawler](https://github.com/microsoft/ghcrawler) - GHCrawler jest crawlerem GitHub API, który indeksuje projekt hostowany przez GitHub i automatycznie śledzi, pobiera i przechowuje jego zawartość. GHCrawler jest przeznaczony głównie dla osób próbujących śledzić zbiory organizacji i repozytoriów danych.
- [devstats](https://github.com/cncf/devstats) - Zestaw narzędzi do wizualizacji archiwów GitHub przy użyciu pulpitów Grafana używanych przez Cloud Native Computing Foundation oraz Kubernetes
- [MeasureOSS](https://github.com/MeasureOSS/Measure) - System zarządzania relacjami z uczestnikami
- [GrimoireLab](https://chaoss.github.io/grimoirelab/) - Platforma analityczna rozwoju oprogramowania obsługująca ponad 30 różnych źródeł danych, część projektu CHAOSS Software od The Linux Foundation

## Zarządzanie GitHub

- [opensource-portal](https://github.com/Microsoft/opensource-portal) - Portal Open Source firmy Microsoft dla GitHub to narzędzie pomagające dużym organizacjom w operacjach zarządzania GitHub, wdrażaniu i nie tylko. Jest zaimplementowany w Node.js.
- [gander](https://github.com/paypal/gander) - Gander to pulpit, który łatwo dostarcza ci użytecznych wskaźników dla szeregu projektów typu open source. Jest przeznaczony dla osób odpowiedzialnych za prowadzenie biur Open Source lub śledzenie wielu projektów Open Source.
- [hubcommander](https://github.com/Netflix/hubcommander) - Slack bot do zarządzania organizacją GitHub
- [GitHub Settings](https://github.com/probot/settings) - używanie .github/config.yml jako źródło prawdy, a wszelkie zmiany tego pliku w domyślnej gałęzi zaktualizują GitHub
- [Zappr](https://github.com/zalando/zappr) - Agent, który egzekwuje wytyczne dla repozytoriów GitHub (od recenzji kodu po niezbędne pliki)
- [FBShipIt](https://github.com/facebook/fbshipit) - Biblioteka napisana w Hack do kopiowania commitów z jednego repozytorium do drugiego.
- [Copybara](https://github.com/google/copybara) - Narzędzie do przekształcania i przenoszenia kodu między repozytoriami.
- [github org scripts](https://github.com/mozilla/github-org-scripts) - Niektóre skrypty pomocnicze do zarządzania organizacjami GitHub za pośrednictwem interfejsu API.
- [github-org-mgmt scripts](https://github.com/bertvv/github-org-mgmt) - Kilka skryptów do zarządzania organizacją Github
- [Automated Github Organization Invites](https://github.com/thundergolfer/automated-github-organization-invites) - Hostuj stronę internetową, aby umożliwić użytkownikom klikanie, odbieranie i zapraszanie do Twojej organizacji GitHub
- [Pepper](https://github.com/genuinetools/pepper) - Narzędzie do wykonywania akcji (actions) na repozytorium GitHub lub pojedynczym repozytorium. 
- [Grit](https://github.com/grailbio/grit) - Grit jest narzędziem do lustrzanego poddrzewa pojedynczego repo dla GitHub

## Jakość projektu

- [CII Best Practices Badging](https://bestpractices.coreinfrastructure.org/) - The Core Infrastructure Initiative (CII) Best Practices badge is a way for Free/Libre and Open Source Software (FLOSS) projects to show that they follow best practices. Projects can voluntarily self-certify, at no cost, by using this web application to explain how they follow each best practice.
- [RepoLinter](https://github.com/todogroup/repolinter) - Lint open source repositories for common issues.
  - [RepoLinter Dashboard](https://github.com/todogroup/repolinter-dashboard) - A Dashboard for RepoLinter
- [Linguist](https://github.com/github/linguist) - Identify the programming languages used in a project.
- [repo-scaffolding](https://github.com/twitter/repo-scaffolding) - Scaffolding tools for creating and maintaining projects based on Twitter Open Source standards and best practices.

## Supply Chain Trust

- [OpenChain Conformance](https://certification.openchainproject.org) - The OpenChain Specification is a way for companies using Free/Libre and Open Source Software (FLOSS) to show that they meet the key requirements for quality compliance programs. Companies can voluntarily self-certify, at no cost, by using this web application.

## Licencje

- [SPDX](https://spdx.org) - Set of standards for communicating the components, licenses and copyright associated with a software package.
- [LicenseFinder](https://github.com/pivotal-legacy/LicenseFinder) - Find licenses for your project's dependencies
- [ScanCode toolkit](https://github.com/nexB/scancode-toolkit) - Scan code for licenses, copyright and dependencies
- [FOSSology](https://www.fossology.org) - Scan code for license, copyright and export control information
- [Licensee](https://github.com/benbalter/licensee) - Identify a project's license file
- [License Identifier (LiD)](https://github.com/codeauroraforum/lid) - Identify and extract license text from source code
- [askalono](https://github.com/amzn/askalono) - a library and command-line tool to help detect license texts. It's designed to be fast, accurate, and to support a wide variety of license texts.
- [License Classifier](https://github.com/google/licenseclassifier) - A library and set of tools that can analyze text to determine what type of license it contains
- [OSS Attribution Builder](https://github.com/amzn/oss-attribution-builder) - The OSS Attribution Builder is a website that helps teams create attribution documents (notices, "open source screens", credits, etc) commonly found in software products.
- [OSS Review Toolkit](https://github.com/heremaps/oss-review-toolkit) - enables highly automated and customizable Open Source compliance checks od the source code and dependencies of a project by scanning it, downloading its sources, reporting any errors and violations against user-defined rules, and by creating third-party attribution documentation.
- [fossa-cli](https://github.com/fossas/fossa-cli) - Fast, portable and reliable dependency analysis for any codebase
- [Licensed](https://github.com/github/licensed) - A Ruby gem to cache and verify the licenses of dependencies
- [LicensePlist](https://github.com/mono0926/LicensePlist) - A command-line tool that automatically generates a Plist of all your dependencies, including files added manually(specified by YAML config file) or using Carthage or CocoaPods.
- [dpkg-licenses](https://github.com/daald/dpkg-licenses) - A command line tool which lists the licenses of all installed packages in a Debian-based system (like Ubuntu).
- [FOSSID](https://fossid.com) - A comprehensive commercial scanner for licenses and vulnerabilities.  Knowledgebase covers 78M+ repositories and 600B+ snippets. Includes detailed snippet scanning to detect the license on fragments and copied/pasted code, even if the open source license is not explicitly or correctly declared.

## Localization oraz Internationalization

- [zanata](https://github.com/zanata/zanata-platform) - Zanata to internetowy system dla tłumaczy, którzy tłumaczą dokumentację i oprogramowanie online za pomocą przeglądarki internetowej.
- [Weblate](https://weblate.org/) - Weblate to bezpłatny internetowy system zarządzania tłumaczeniami.

## Strony internetowe i dokumentacja

- [Docusaurus](https://docusaurus.io) - Docusaurus to oparty na React generator witryn statycznych, opracowany specjalnie w celu łatwiejszego tworzenia i utrzymywania witryn typu open source.
- [GatsbyJS](https://www.gatsbyjs.org/) - Gatsby to generator witryn, który umożliwia tworzenie szybkich witryn i aplikacji z React.
- [VuePress](https://vuepress.vuejs.org/) - VuePress to minimalistyczny generator strony statycznej oparty na Vue, zoptymalizowany do pisania dokumentacji technicznej.

## Bezpieczeństwo

- [Vulnerability Assessment Tool](https://github.com/SAP/vulnerability-assessment-tool) - The Vulnerability Assessment Tool pomaga odkrywać, oceniać i łagodzić znane luki w projektach Java i Python.

# Licencja

[![License: CC BY-SA 4.0](https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/) © Contributors 2016-2018

____________________________________
Stworzone przez @[todogroup](https://github.com/todogroup/) polska wersja od @[mbiesiad](https://github.com/mbiesiad)
