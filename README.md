# Deception-and-Disruption

## 1. Deception in Cybersecurity (دھوکہ دینا / چالاکی سے گمراہ کرنا)
#### Definition:
**English:**
Deception is a security technique where fake systems, data, or services are deployed to trick attackers, detect them early, and study their behavior.

**Urdu:**
Deception ka matlab hai attacker ko dhoka dena – aise fake systems ya traps use karna jo attacker ko asli system samajh aayein, lekin asal mein wo sirf attacker ko pakarnay ka zariya hotay hain.

####  Goals of Deception:
Detect attackers early
(جلدی پتا چل جائے کہ کوئی حملہ آور آیا ہے)

Distract them from real systems
(حقیقی ڈیٹا سے دور رکھنا)

Gather intelligence about attacker behavior
(حملہ آور کے طریقے کو سمجھنا)

## Deception Techniques:
### Technique -----------------------	Explanation (English + Urdu)

### Honeypots -----------------------	Fake servers designed to attract attackers.
Urdu: جعلی سسٹمز جنہیں hacker attack karta hai, lekin asli data nahi hota.

### Honeytokens ---------------------	Fake files or credentials used to detect misuse.
Urdu: جعلی password ya document – agar use kiya jaye to alert mil jaye.

### Honeynets ---------------------------	A network of honeypots.
Urdu: پورا نیٹ ورک جو attacker ko trap karne ke liye design kiya gaya ho.

### Decoy Systems -------------	Fake user accounts, fake databases.
Urdu: جھوٹے data sets aur users jo asli nahi hote.

### Deceptive Credentials -----------------	Login info jo agar koi chura le to hum trace kar sakein.
Urdu: Fake credentials jo leak hone par alert de dete hain.

## Benefits of Deception:
Low-cost way to detect intrusions

Attacker ko gumrah karta hai

Real systems secure rehte hain

Intelligence collect ki ja sakti hai

## 2. Disruption in Cybersecurity (خلل ڈالنا / نظام کو روکنا)
### Definition:
**English:**
Disruption refers to the act of interrupting or halting the functionality of a system, service, or network—either by an attacker or a defensive response.

**Urdu:**
Disruption ka matlab hai kisi system, network, ya service mein kaam mein rukawat dalna ya use band kar dena, taake ya to attacker ka access roka ja sake ya unka attack fail ho jaye.

### Goals of Disruption:
Attackers ko stop karna
(حملہ آور کا حملہ روکنا)

System ko temporarily band karke reset karna
(سسٹم کو وقتی طور پر بند کرنا)

Prevent data theft or misuse
(ڈیٹا کے چوری ہونے سے بچاؤ)

## Types of Disruption Attacks:
### Type ---------------------------	Explanation (English + Urdu)

### DDoS (Distributed Denial of Service) -----------------	Overloading a system with traffic to make it crash.
Urdu: Bohat zyada traffic bhejna taake system band ho jaye.

### Ransomware ----------------	Locking or encrypting data to stop system use.
Urdu: Data ko lock kar dena aur ransom mangna.

### Service Takedown -----------------------	Disabling a service temporarily.
Urdu: Kisi website ya network ko forcefully offline kar dena.

### Network Jamming	 ----------------- Disrupting wireless signals.
Urdu: Wireless signals mein khalal dalna taake communication band ho jaye.

## Defensive Disruption (اچھا disruption):
Some cyber defenders use disruption as a strategy to stop attackers.

## Method	Urdu Explanation
Kill switch	Emergency shutdown button to protect systems.
فوری طور پر سسٹم بند کرنے کا طریقہ
Connection reset	Forcefully disconnect attacker.
حملہ آور کا رابطہ توڑ دینا
Isolate infected systems	Network se cut karna taake virus na phaylay.
متاثرہ سسٹم کو الگ کر دینا

### Difference Between Deception and Disruption
Aspect----------------	Deception ------------------------	Disruption

Purpose ----------------	Mislead attacker ---------------	Interrupt attacker or system

Nature ----------------	Passive/Intelligent	----------------Active/Forceful

Used by -----------------	Security teams (to trap) --------	Both attackers and defenders

Urdu	دھوکہ دینا	نظام میں خلل ڈالنا
