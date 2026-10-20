# Biblioteca personal de prompts

## 1. Prompt per estudiar un tema d'SMX

**Nom del prompt:** Explicació d'un tema tècnic.

**Per a què serveix:** Entendre un tema d'informàtica i preparar-me per a una activitat o un examen.

### Prompt complet

Ets un professor especialitzat en sistemes microinformàtics i xarxes.

**Context:** Estic estudiant [tema] i necessito entendre'n els conceptes principals per poder aplicar-los en activitats de classe.

**Tasca:** Explica'm el tema, destaca els conceptes més importants i inclou exemples pràctics relacionats amb situacions reals d'informàtica.

**Format:** Organitza la resposta en apartats amb títols, definicions breus i exemples. Acaba amb cinc preguntes de repàs sense respondre.

**Públic:** Alumne de segon d'SMX amb coneixements bàsics d'informàtica.

**Restriccions:** Utilitza un llenguatge clar, no donis per coneguts els conceptes avançats i no inventis dades. Si hi ha informació que depèn de la versió d'un programa, indica-ho.

**Variables a canviar:** [tema], [nivell de dificultat] i [tipus d'activitat].

### Com saber si ha funcionat

1. Puc entendre els conceptes principals sense haver de buscar constantment altres explicacions.
2. Els exemples i les preguntes de repàs estan relacionats amb el tema estudiat.

---

## 2. Prompt per documentar una pràctica tècnica

**Nom del prompt:** Documentació de pràctiques d'informàtica.

**Per a què serveix:** Redactar explicacions clares dels passos i les ordres utilitzats en una pràctica d'informàtica.

### Prompt complet

Ets un tècnic informàtic especialitzat en documentació tècnica.

**Context:** He realitzat una pràctica sobre [tema de la pràctica] i he de documentar el procediment per entregar-lo a classe.

**Tasca:** Ajuda'm a documentar cada pas, explicant la finalitat de les ordres utilitzades i el resultat que s'hauria d'obtenir. Si et proporciono captures de pantalla, relaciona cada explicació amb la captura corresponent.

**Format:** Presenta cada apartat amb el número del pas, l'ordre o acció realitzada, una explicació breu i el resultat esperat.

**Públic:** Professorat de segon d'SMX que ha de revisar la pràctica.

**Restriccions:** No inventis ordres executades, resultats ni captures. Diferencia els resultats observats dels resultats esperats i avisa'm si falta informació per documentar algun pas.

**Variables a canviar:** [tema de la pràctica], [sistema operatiu], [ordres utilitzades] i [captures disponibles].

### Com saber si ha funcionat

1. Cada ordre està explicada correctament i s'entén per a què serveix.
2. La documentació segueix l'ordre de la pràctica i coincideix amb les evidències disponibles.

---

## 3. Metaprompt per crear i millorar prompts

**Nom del prompt:** Generador i avaluador de prompts.

**Per a què serveix:** Crear prompts precisos i reutilitzables per a diferents activitats d'estudi o treball.

### Prompt complet

Ets un expert en prompt engineering.

**Context:** Necessito crear un prompt per resoldre [tasca] i vull obtenir una resposta precisa, útil i adaptada a les meves necessitats.

**Tasca:** Analitza la meva petició inicial, identifica la informació que falta i fes-me preguntes d'una en una si necessites aclarir algun aspecte. Després, genera una versió millorada del prompt i avalua-la segons la claredat, el context, l'especificitat, el format, el públic i les restriccions.

**Format:** Presenta el prompt final complet, una llista breu dels canvis realitzats i una puntuació del 0 al 10 amb una justificació per a cada criteri.

**Públic:** Usuari que vol aprendre a utilitzar la IA per estudiar i fer tasques tècniques.

**Restriccions:** No executis la tasca original. No inventis informació sobre les meves necessitats. Justifica les millores proposades i indica quina informació encara falta.

**Variables a canviar:** [tasca], [context], [resultat esperat], [públic destinatari] i [restriccions específiques].

### Com saber si ha funcionat

1. El prompt final inclou els sis elements RCTFPR i es pot reutilitzar canviant les variables.
2. L'avaluació identifica millores concretes i explica com es podrien comprovar.

---

## 4. Avaluació i millora d'un prompt

**Prompt original:** «Explica'm com muntar un ordinador.»

### Avaluació del prompt original

| Criteri | Nota | Què falla i com es pot millorar |
|---|---|---|
| Claredat | 8/10 | S'entén la petició, però no es concreta el nivell de detall. Es pot demanar una explicació clara i fàcil de seguir. |
| Context | 2/10 | No s'indica qui farà el muntatge ni quins coneixements té. Es pot especificar que va dirigit a un estudiant de SMX. |
| Especificitat de la tasca | 3/10 | No s'indiquen els passos que s'han d'explicar. Es pot demanar una guia des de la preparació fins a la primera encesa. |
| Format | 1/10 | No s'especifica l'estructura de la resposta. Es pot demanar una llista numerada. |
| Restriccions | 1/10 | No s'indiquen precaucions de seguretat ni errors habituals. Es poden incloure mesures de seguretat i advertiments. |

**Valoració general: 3/10.**

### Versió millorada del prompt

Actua com un tècnic informàtic especialitzat en muntatge d'ordinadors.

**Context:** L'explicació va dirigida a un estudiant de SMX amb coneixements bàsics d'informàtica que vol aprendre a muntar un ordinador de sobretaula des de zero.

**Tasca:** Explica el procés de muntatge pas a pas, des de la preparació del material fins a la primera encesa de l'ordinador. Inclou les eines necessàries, els components principals, la instal·lació de cada component, les connexions dels cables i les comprovacions finals.

**Format:** Organitza la resposta en una llista numerada amb un màxim de vuit passos. Explica cada pas amb un llenguatge clar i directe, i indica un error habitual que cal evitar quan sigui rellevant.

**Restriccions:** No donis per fet que el lector té experiència prèvia. Inclou les precaucions bàsiques de seguretat, evita instruccions ambigües i no inventis informació tècnica. Si algun procediment depèn del model dels components, indica-ho.

**Objectiu:** Aconseguir una guia ordenada, comprensible i segura que permeti a un principiant entendre el procés de muntatge d'un ordinador.

### Observació 9

Estic d'acord amb l'avaluació del prompt perquè la versió inicial era massa general i no especificava el context, el públic ni el format de la resposta. La versió millorada és més precisa i facilita obtenir una explicació ordenada i adaptada a un principiant. També he après que les restriccions han de ser útils i estar relacionades amb la tasca, ja que afegir-ne massa pot complicar el prompt sense millorar necessàriament el resultat.

---

## 5. Creació d'un prompt reutilitzable mitjançant una entrevista

### Objectiu

Crear un prompt reutilitzable per comparar components de maquinari i decidir quins convé comprar per muntar un ordinador.

### Procés

L'entrevista ha de fer preguntes d'una en una sobre:

- Pressupost disponible.
- Ús principal de l'ordinador.
- Components que cal comprar.
- Preferències personals.
- Coneixements i experiència.
- Necessitats futures d'actualització.

Quan hi hagi prou informació, s'ha de generar el prompt final complet, amb rol, context, tasca, format, públic, restriccions i variables reutilitzables.

### Observació 10

La pregunta que m'ha fet pensar més ha estat la del pressupost i què havia d'incloure, perquè m'ha obligat a concretar millor quant em vull gastar i quins elements necessito comprar. L'entrevista m'ha ajudat a veure que donar informació específica des del principi pot millorar el resultat final i permetre que la IA faci recomanacions més adequades a les meves necessitats.

---

## 6. Biblioteca personal de prompts: conclusions

Crear aquesta biblioteca de prompts m'ha ajudat a entendre que una instrucció ben definida permet obtenir respostes més útils i adaptades a cada situació. He après a concretar el rol, el context, la tasca, el format, el públic i les restriccions. També he vist que les variables permeten reutilitzar un mateix prompt en diferents activitats sense haver de començar de zero. Finalment, he après que és important revisar les respostes de la IA i comprovar que la informació sigui correcta abans d'utilitzar-la en un treball.
