# Fonctionnement:

### Scripts de génération des data:
* __cve-generate-chartdata__ appelle le script __cve-report.py__ pour générer les .txt à partir des .json du dossier __cve_check__
* __patchmetrics-generate-chartdata__ génère à partir de __patch-status.json__ __patch-status-pie.json__ et __patch-status-byday.json__
* L'ensemble des fichiers générés sont mis dans le dossier __patch-status__ qui contient le .html

### Notes:
* Les fichiers générés ici ne se trouvent pas dans les répos __yocto-metrics__ et __yocto-metrics-meta-oe__
* Les scripts de génération ne sont pas présents de base dans les repos __metrics__
* Ces scripts sont issus du repo __yocto-autobuilder-helper__
* Pour tester localement, ces fichiers sont mis dans le dossier __patch-status__

### Preview des charts
* [meta-oe](https://html-preview.github.io/?url=https://github.com/AkaiRyussei/Test-metrics-graph/blob/main/meta-oe/patch-status/index.html)
* [OE-core](https://html-preview.github.io/?url=https://github.com/AkaiRyussei/Test-metrics-graph/blob/main/OE-core/patch-status/index.html)
