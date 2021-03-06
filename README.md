# W906_BR-TH
W906 Thaqi Breitenmoser


## Planung
In der Planung haben wir uns Gedanken gemacht, welche Tools wir für welchen Arbeittschritt entscheiden. Als Basis haben wir uns dann für Google Cloud Platform entschieden, da es nicht zu schwer aber auch nicht zu einfach ist. Ausserdem können wir auch ein anderes "Lösungsbeispiel" darstellen als die Anderen. Kevin hatte dafür noch ein Konto mit 300$ Testguthaben. Somit hatten wir genügend Ressourcen um uns in das Thema reinzufuchsen.

## Versionsverwaltung
Für die Versionsverwaltung haben wir uns für Github entschieden. Der Grund dafür ist, dass wir von den verschiedenen Tools die es gibt, Github am besten kennen und einfach zu integrieren ist. Wir haben dafür die Repository "https://github.com/kebab8902/W906_BR-TH" erstellt.

## Code
Unser Code besteht aus einem kleinem HTML-File und einem Docker-file. Unser Dockerfile baut einen Apache 2 Webserver deren Index aus unserem HTML-File besteht. Das HTML-File besteht aus ein paar Zeilen Code und gibt "Hello World" aus.

## Build
Damit wir unser Projekt builden können, haben wir Google Cloud ausgewählt. Google Cloud Platform ermöglicht es ganz einfach unsere Projekte zu builden. Wir können damit verschiedene Trigger aufsetzen die beim Auslösen das Projekt builden. Unser Haupttrigger ist, dass wenn ein Dockerfile gepushed wird, dass er dieses File automatisch builded.

## Continuous Integration
Für CI wollten wir zunächst Jenkins verwenden. Bei unserer Recherche haben wir hauptsächlich nur Gutes gehört.

## Continuous Delivery
Die Continous Delivery geschieht über Google Cloud Run. Dies ist ähnlich wie Kubernetes. Wie vorhin schon beim Build erwähnt, werden auch hier beim Trigger die Updates der Files ausgelöst. Google Cloud Run ist Teil der Google Cloud Platform und deshalb konnten wir dies auch relativ einfach integrieren.

## Reflexion
Uns hat das Thema sehr viel Spass gemacht auch wenn nicht immer alles super funktioniert hat. Wir hatten am Anfang wenig bis keine Ahnung was DevOps überhaupt ist und mussten uns sehr viel informieren, bis wir eine vage Ahnung hatten. Mittlerweile verstehen wir das Thema in der Theorie sehr gut, können uns aber in der Praxis noch ein gutes Stück verbessern. Wir haben sehr viel aus diesem Wahlmodul mitgenommen und es war sicherlich keine schlechte Entscheidung dieses Modul zu wählen.
