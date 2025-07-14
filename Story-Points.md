## Gli SP (Story Points)

✅ **COSA SONO GLI STORY POINTS?**

- Non sono **ore**, non sono **giorni**, e nemmeno una stima lineare del tempo.
- Sono un **indice relativo** che misura:
  - La **complessità tecnica** del task.
  - Il **volume di lavoro** percepito.
  - I **rischi/incertezze** associati.

In pratica rispondono alla domanda:

- 👉 _“Quanto è grande/difficile questo lavoro rispetto ad altri che conosciamo?”_

---

📏 **C’È UNA SCALA STANDARD?**

- Sì, la scala più usata è quella di **Fibonacci** (1, 2, 3, 5, 8, 13, 21...).
- 🔹 Perché? Perché rende evidente la differenza tra task piccoli e grandi: un task da 13 è MOLTO più grande di uno da 5.
- 🔹 Alternative: scale lineari (1–10) o T-shirt sizes (XS, S, M, L, XL).

---

📝 **COME VENGONO ASSEGNATI?**

1. Durante lo **Sprint Planning** o una **refinement session**.
2. Il team discute ogni User Story.
3. Si usa spesso il **Planning Poker**:

   - Ogni membro assegna in segreto un numero di story points alla story.
   - Tutti scoprono le carte insieme.
   - Se c’è disaccordo (es: uno dice 3, uno dice 13), si discute per capire perché e si rivotano.

📌 Nota importante:

- Gli story points sono **decisi dal team di sviluppo**, non dal Product Owner o Scrum Master.
- Sono **relativi tra loro**. Es: “Se la Story A vale 5 e la B ci sembra il doppio del lavoro, allora B vale 8 o 13”.

---

📊 **SONO “A CASO”?**
No. Non sono rigorosi come le ore, ma sono **coerenti** nel tempo per quel team. Ogni team ha il suo “metro” e non esiste confronto tra team diversi.

---

🔥 TL;DR:

- Sì, sono un **indice di difficoltà/complessità relativa**.
- La scala più comune è **Fibonacci**.
- Vengono decisi dal team con **Planning Poker** o simili.
- NON rappresentano tempo, ma aiutano a stimare la **velocity** e pianificare sprint realistici.

---

**Tabella pratica** che mostra come di solito i team interpretano gli **story points** con esempi concreti:

---

| 📋 **Story Points**  | 📖 **Tipologia di lavoro**                                 | 💡 **Esempio pratico**                                          |
| -------------------- | ---------------------------------------------------------- | --------------------------------------------------------------- |
| **1 (Extra Small)**  | Micro-task banale, quasi nessuna complessità               | Correzione di un typo, aggiungere una label a un bottone        |
| **2 (Small)**        | Task semplice, chiaro, con poco rischio                    | Aggiornare un testo statico su una pagina, modificare un colore |
| **3 (Small-Medium)** | Task chiaro ma richiede un minimo di attenzione            | Creare un endpoint REST già definito in uno schema esistente    |
| **5 (Medium)**       | Task di media complessità o con più parti coinvolte        | Integrare un API esterna già documentata                        |
| **8 (Large)**        | Feature complessa o task con incertezze/ambiguità moderate | Implementare autenticazione con OAuth2                          |
| **13 (Extra Large)** | Feature molto complessa o con alto rischio tecnico         | Riscrivere un modulo legacy per adattarlo a un nuovo framework  |
| **21 (Epic)**        | Enorme, va sicuramente splittato in più storie             | Redesign completo dell’UI di un’app mobile                      |

---

📌 **Note importanti:**

- 🛑 Oltre **13–21** si sconsiglia di assegnare punti perché vuol dire che il lavoro è **troppo grosso** → va spezzato in **storie più piccole**.
- 🔥 Gli **story points non sono ore**, ma nella mente del team di solito si crea un’associazione implicita (es: 1 = mezz’ora, 5 = mezza giornata, 13 = più giorni).
- 📦 Ogni team crea il proprio metro di misura: un “5” per un team può essere un “8” per un altro.

---

## SP in days 🛑 (sconsigliato)

Anche se Scrum **sconsiglia di tradurre direttamente gli story points in ore/giorni** (perché lo scopo è stimare **complessità relativa**, non tempo), ti preparo comunque una **tabella “realistica”** che molti team usano nella pratica per orientarsi all’inizio:

---

| 📋 **Story Points**  | 📖 **Tipologia di lavoro**                                   | ⏳ **Corrispondenza approssimativa (tempo)** |
| -------------------- | ------------------------------------------------------------ | -------------------------------------------- |
| **1 (Extra Small)**  | Task banale, nessuna complessità                             | **\~30 minuti – 1 ora**                      |
| **2 (Small)**        | Task semplice e chiaro                                       | **\~1–2 ore**                                |
| **3 (Small-Medium)** | Task con più passi, ma senza rischi particolari              | **\~2–4 ore (mezza giornata)**               |
| **5 (Medium)**       | Task di media complessità con piccole incertezze             | **\~4–8 ore (1 giornata)**                   |
| **8 (Large)**        | Task complesso o con dipendenze esterne                      | **\~1,5–2 giornate**                         |
| **13 (Extra Large)** | Feature complessa o ad alto rischio tecnico                  | **\~3–5 giornate (quasi 1 settimana)**       |
| **21 (Epic)**        | Lavoro enorme da spezzare, troppo grande per uno sprint solo | **\~1 settimana o più**                      |

---

📌 **Cose da ricordare**:
🔹 Queste stime sono **indicative** e valgono solo per un team **coeso e stabile**.
🔹 La **velocity del team** (es. 30 punti/sprint) aiuta a capire quante storie possono stare in uno sprint da 2 settimane.
🔹 Se una storia è **13+ punti**, è un segnale che va **suddivisa in più storie**.
