# BUCH III: PULS (DIE ÖKONOMIE DER RESONANZ)
> **Quelle:** Fusion (Valitas Econ + GER Core)
> **Status:** Kompendium / Referenz
> **Umfang:** Die Physik des Geldes

---

## PRÄAMBEL: KINETIK STATT STATIK

**Logik (Das Axiom):**
Geld ist keine Ware, sondern Information über verfügbare Energie. In einem thermodynamischen Universum existiert keine ewige Energieerhaltung ohne Verlust (Entropie). Ein Währungssystem, das Werte konserviert oder durch Zinsen exponentiell vermehrt, ohne dass Arbeit geleistet wird, verstößt gegen die Gesetze der Physik und muss kollabieren.
Lovalis korrigiert diesen Fehler durch **Puls (Kinetisches Geld)**.

---

## KAPITEL 1: P_GEN (DIE GELDSCHÖPFUNG)

### §1 Proof of Contribution (Wertschöpfungs-Nachweis)

**Logik (Das Axiom):**
Geld darf niemals *ex nihilo* (aus dem Nichts/Kredit) entstehen. Es darf nur als digitales Äquivalent zu real geleisteter, entropie-senkender Arbeit existieren.

**Juristisch/Wissenschaftlich (Das Protokoll):**
Das *Minting* (Schöpfen) neuer Puls-Einheiten folgt der Funktion $P_{gen}$:
$$ P_{gen}(t) = \int_{t_0}^{t} (\text{Work}_{val} \times \text{Entropy}_{red}) \, dt $$
1.  **Trigger:** Ein Node leistet Arbeit (z.B. Bau eines Tisches, Pflege eines Patienten, Code-Commit).
2.  **Validierung:** Der Empfänger (oder das Cluster-Protokoll) bestätigt die Leistung und die Einhaltung der Bio-Integrität.
3.  **Minting:** Erst *nach* erfolgreicher Validierung erzeugt der Kernel die entsprechenden Puls-Einheiten und schreibt sie dem Wallet des Leistenden gut.
4.  **Fiat-Block:** Kreditvergabe durch Banken (Giralgeldschöpfung) ist im Code unmöglich (`Double-Spend-Protection`).

**Was bedeutet das? (Der Transfer):**
Stell dir Geld wie eine Quittung für geleistete Arbeit vor.
Im alten System konnten Banken diese Quittungen einfach drucken und verleihen, ohne dass jemand gearbeitet hat. Das hat alle anderen Quittungen entwertet (Inflation).
In Lovalis entsteht die Quittung erst in dem Moment, wo du den Tisch fertig gebaut hast. Kein Tisch, kein Geld. Das bedeutet: Dein Geld verliert nie an Wert, weil ihm immer ein echter Gegenwert gegenübersteht. Inflation durch "Geldrucken" ist unmöglich.

### §2 Der Circuit Breaker (Ökologische Deckelung)

**Logik (Das Axiom):**
Die Summe aller ökonomischen Ansprüche (Geldmenge) darf die Summe der ökologischen Ressourcen nicht überschreiten.

**Juristisch/Wissenschaftlich (Das Protokoll):**
Der Kernel überwacht das Verhältnis von Geldmenge ($M$) zu Biokapazität ($\Omega$).
$$ \text{If } M > \Omega \times \text{Efficiency} \rightarrow \text{TRIGGER(Stop_Minting)} $$
Steigt die Geldmenge so stark an, dass der Konsum die Regeneration der Natur gefährdet, pausiert der Kernel temporär die Schöpfung neuer Puls-Einheiten (selbst bei geleisteter Arbeit), bis sich $\Omega$ erholt hat oder die Effizienz gestiegen ist.
Dies erzwingt Innovation: Um reicher zu werden, müssen wir effizienter werden, nicht mehr verbrauchen.

**Was bedeutet das?**
Wir können nicht mehr Geld haben, als die Erde Waren hergeben kann. Wenn wir versuchen, mehr zu kaufen, als nachwächst, friert das System das Geldwachstum ein. Das ist wie eine Sicherung im Sicherungskasten: Bevor das Kabel brennt (die Erde kollabiert), schaltet der Strom ab.

---

## KAPITEL 2: DEMURRAGE (DIE UMLAUFSICHERUNG)

### §3 Die Entropie-Kurve (Geldrost)

**Logik (Das Axiom):**
Alles in der Natur zerfällt (Brot schimmelt, Eisen rostet). Nur Geld war bisher "unsterblich" und vermehrte sich sogar durch Zinsen. Dieser Fehler führte dazu, dass Reiche immer reicher wurden, ohne zu arbeiten. Lovalis führt den natürlichen Zerfall für Geld ein.

**Juristisch/Wissenschaftlich (Das Protokoll):**
Auf liquide Bestände im *Puls-Wallet* (Sichtguthaben) wird eine *Demurrage-Gebühr* erhoben.
* **Rate:** Dynamisch, ca. 5-7% p.a. (angepasst an die Umlaufgeschwindigkeit $V$).
* **Algorithmus:** Die Gebühr wird stündlich micro-abgebucht (`Balance = Balance * (1 - Rate)^(dt)`).
* **Effekt:** Erhöhung der Umlaufgeschwindigkeit. Das Horten von Geld wird "teurer" als das Investieren.
* **Befreiung:** Investitionen in langfristige Werte (Aktien von nachhaltigen Firmen, Infrastruktur-Anleihen) unterliegen *nicht* der Demurrage, da der Wert dort "arbeitet".
    * **Human-Klausel (Decay-Freeze):** Das Leben verläuft nicht linear.
    * Nodes können eine **Demurrage-Pause** (bis zu 12 Monate alle 5 Jahre) beantragen.
    * *Gründe:* Trauerfall, Elternzeit, Pflege, Sabbatical.
    * *Logik:* Das System darf niemanden bestrafen, der eine Auszeit zum Atmen braucht.

**Was bedeutet das?**
Geld ist wie eine heiße Kartoffel oder frisches Obst. Du musst es benutzen (ausgeben) oder investieren (Pflanzen), sonst wird es weniger.
Du kannst dich nicht mehr auf einem großen Geldhaufen ausruhen. Wenn du reich bleiben willst, musst du dein Geld anderen geben (investieren), damit sie damit arbeiten können. Das Geld fließt also immer dorthin, wo es gebraucht wird, und staut sich nicht bei denen, die schon alles haben.

### §4 Der Negativ-Zins als Motor

**Logik (Das Axiom):**
Positiver Zins belohnt Besitz (Vergangenheit). Negativer Zins (Demurrage) belohnt Aktivität (Gegenwart) und Investition (Zukunft).

**Juristisch/Wissenschaftlich (Das Protokoll):**
Kredite in Lovalis sind zinsfrei oder haben sogar negative Zinsen (man zahlt weniger zurück, als man geliehen hat), solange das Projekt dem Gemeinwohl dient (hoher ZVF-Score).
Warum? Weil der Gläubiger froh ist, sein Geld loszuwerden, um der Demurrage zu entgehen. Er "parkt" sein Geld lieber in einem Hausbau-Projekt eines jungen Paares (Werterhalt), als es auf dem Konto schmelzen zu sehen.

**Was bedeutet das?**
Wenn du ein Haus bauen oder eine Firma gründen willst, findest du leicht Geld. Die Reichen *wollen* dir Geld leihen, weil es für sie besser ist, als es zu behalten. Du zahlst keine Wucherzinsen mehr. Die Macht verschiebt sich vom Geldbesitzer zum Geldnutzer (dem Arbeiter/Unternehmer).

---

## KAPITEL 3: DIE KONTEN-TOPOLOGIE

### §5 Das Node Zero Wallet (Basis-Sicherheit)

**Logik (Das Axiom):**
Existenzangst blockiert rationales Denken und Kreativität. Die physische Basis-Existenz muss vom monetären Wettbewerb entkoppelt sein.

**Juristisch/Wissenschaftlich (Das Protokoll):**
Jeder validierte Bürger besitzt ein *Node Zero Wallet*.
* **Funktion:** Zugriff auf Allmende-Ressourcen (siehe Buch II, §2).
* **Attribute:**
    * **Demurrage-Frei:** Guthaben auf diesem Konto verfällt nicht (begrenzt auf das Existenz-Minimum).
    * **Unpfändbar:** Kein Gläubiger und kein Staat kann dieses Konto sperren.
    * **Zweckgebunden:** Guthaben hier kann nur für Basis-Güter (Miete, Strom, Grundnahrung) verwendet werden.
* **Speisung:** Automatische Zuteilung aus der *Allmende-Dividende* (Gewinne aus der Nutzung von natürlichen Ressourcen).

**Was bedeutet das?**
Das ist dein "Überlebens-Konto". Egal wie pleite du bist, hier ist immer genug drauf für Miete, Strom und Brot. Das Geld hier rostet nicht und niemand kann es dir wegnehmen. Du musst nie wieder Angst haben, obdachlos zu werden.

### §6 Das Puls Wallet (Resonanz-Vermögen)

**Logik (Das Axiom):**
Luxus, Status und Investitionskapital unterliegen den Gesetzen der Thermodynamik (Demurrage). Wer mehr will als das Minimum, muss sich dem Fluss stellen.

**Juristisch/Wissenschaftlich (Das Protokoll):**
Das *Puls Wallet* dient der Akkumulation von Vermögen oberhalb von Node Zero.
* **Attribute:**
    * **Demurrage-Aktiv:** Unterliegt dem Schwund von ca. 5-7% p.a.
    * **Öffentlich (Glass House):** Ab einer gewissen Summe (Cap) sind die Flüsse für das Cluster transparent.
* **Funktion:** Kauf von Luxusgütern, Investition in Startups, Spenden für Reputation.

**Was bedeutet das?**
Das ist dein "Business-Konto". Hier liegt das Geld für das schicke Auto, den Urlaub oder deine Firmengründung. Dieses Geld musst du bewegen, sonst wird es weniger. Es ist das Geld für den Fortschritt, nicht für die Sicherheit.

---

## KAPITEL 4: FISKAL-LOGIK (STEUERN)

### §7 Die Asymmetrische Transaktionsgebühr (Automated Tax)

**Logik (Das Axiom):**
Komplexe Steuererklärungen sind Verschwendung von Lebenszeit (Entropie). Steuern müssen in Echtzeit und unsichtbar (im Protokoll) erhoben werden. Arbeit darf nicht besteuert werden, nur Ressourcen-Verbrauch.

**Juristisch/Wissenschaftlich (Das Protokoll):**
Lovalis erhebt **keine Einkommensteuer** auf Arbeit.
Stattdessen greift die *Resource-Consumption-Tax* (Ressourcen-Steuer) bei jeder Transaktion:
1.  **Arbeit:** 0% Steuer (Der volle Lohn kommt an).
2.  **Dienstleistung:** Geringe Gebühr (ca. 2% für Infrastruktur).
3.  **Ressourcen:** Hohe Steuer auf Primär-Rohstoffe (Öl, seltene Erden), die nicht recycelt sind.
4.  **Luxus:** Progressive Steuer auf Güter mit hohem ökologischen Fußabdruck.
Die Abbuchung erfolgt algorithmisch im Moment der Zahlung (*Split Payment*).

**Was bedeutet das?**
Du musst nie wieder eine Steuererklärung machen.
Wenn du arbeitest, gehört dir dein Geld zu 100%. Der Staat nimmt dir nichts vom Lohn weg.
Steuern zahlst du nur, wenn du konsumierst – und zwar vor allem dann, wenn du Dinge kaufst, die der Umwelt schaden. Bio-Äpfel sind steuerfrei, der SUV ist teuer. Das System belohnt Fleiß und bestraft Verschwendung.

---
> **ENDE BUCH III: PULS**

