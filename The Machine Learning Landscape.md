# The Machine Learning Landscape

---

## Machine Learning Shu Chhe? (What Is Machine Learning?)

Machine Learning e computers ne program karvanu **science (ane art)** chhe jethi teo **data mathi learn kari shake**.

#### General Definition:
> [Machine Learning e] study no field chhe je computers ne explicitly program karya vagar learn karvani ability aape chhe.
>
> — *Arthur Samuel, 1959*

#### Engineering-Oriented Definition:
> Ek computer program ne evu kehvay ke te experience *E* mathi koi task *T* ane koi performance measure *P* na sandarbh ma learn kare chhe, jo teni performance *T* par, je *P* dwara mapvama aave chhe, te experience *E* sathe improve thay.
>
> — *Tom Mitchell, 1997*

**Saral shabdo ma:** Jo tame fakt Wikipedia ni ek copy download karo, to tamara computer pase ghano data aavi jay chhe, parantu te achanak koi pan task ma vadhare smart nathi thai jatu. Aam, fakt data download karvo e Machine Learning nathi. Machine Learning e data mathi patterns shikhi ne potani jate smart banvani prakriya chhe.

---

## Machine Learning Keni Mate Use Karvu? (Why Use Machine Learning?)

Machine Learning evu problems mate best chhe je:
1.  **Traditional approach mate vadhare complex hoy:** Ghana badha rules lakhva pade.
2.  **Jeno koi sacho solution na hoy:** ML navo solution shodhi shake chhe.
3.  **Environment satat badlatu hoy:** ML nava data પ્રમાણે adapt thai shake chhe.
4.  **Mota data mathi insights joiye:** ML data mathi evi patterns shodhi kade chhe je manviya mate jovi aghri hoy (aane **Data Mining** pan kahevay chhe).

#### Traditional Approach vs. ML Approach (Spam Filter Example)

* **Traditional Approach:**
    1.  Tame spam kevu dekhay chhe te study karo (e.g., "free", "credit card" jeva shabdo).
    2.  Aa badha shabdo mate **rules** lakho.
    3.  Program ne test karo ane jarur pade to rules ne update karo.
    * **Problem:** Aa process ma ghana complex rules bane chhe jene maintain karva aghra chhe. Jo spammer "For U" ne badle "4U" lakhvanu sharu kare, to tamare navo rule lakhvo pade.

* **Machine Learning Approach:**
    1.  ML algorithm ne hajaro spam ane non-spam (ham) emails aapvama aave chhe.
    2.  Algorithm potani jate j shikhi le chhe ke kaya shabdo ke patterns spam indicate kare chhe.
    * **Faydo:** Aa program nano, maintain karvama saral, ane vadhare accurate hoy chhe. Jo spammers "For U" no upyog karvanu sharu kare, to system automatically aa navi pattern ne shikhi le chhe ane tene block karvanu sharu kari de chhe.

---

## Applications na Examples (Examples of Applications)

* **Production line par products ni images ne analyze karvi**
    * Aa *image classification* chhe.

* **Brain scans ma tumors ne detect karva**
    * Aa *semantic segmentation* chhe.

* **News articles ne automatically classify karva**
    * Aa *Natural Language Processing (NLP)* ane *text classification* chhe.

* **Discussion forums par offensive comments ne automatically flag karvi**
    * Aa pan *text classification* chhe.

* **Lamba documents ne automatically summarize karva**
    * Aa *text summarization* chhe.

* **Ek chatbot athva personal assistant banavvu**
    * Aama *Natural Language Understanding (NLU)* no upyog thay chhe.

* **Company ni aavta varsh ni revenue nu anuman lagavvu**
    * Aa ek *regression task* chhe.

* **Tamari app ne voice commands par react karavvi**
    * Aa *speech recognition* chhe.

* **Credit card fraud ne detect karvu**
    * Aa *anomaly detection* chhe.

* **Clients ne temni purchases na aadhare alag-alag group ma vechva**
    * Aa *clustering* chhe.

* **Ek game mate intelligent bot banavvu**
    * Aa *Reinforcement Learning (RL)* no upyog kare chhe.
 
# Types of Machine Learning Systems

Machine Learning systems ne samanya rite 3 mukhya criteria na aadhare alag-alag categories ma vechvama aave chhe:

### 1. Based on Human Supervision (Training Method)
Aa joy chhe ke system ne train karva mate **human supervision** (manviya dekhrekh) ni jarur chhe ke nahi.
- **Supervised Learning**
- **Unsupervised Learning**
- **Semisupervised Learning**
- **Reinforcement Learning**

### 2. Based on Incremental Learning (Learning Ability)
Aa joy chhe ke system incrementally 'on the fly' (satat) navo data aave tenathi shikhi shake chhe ke nahi.
- **Online Learning:** 'On the fly' nava data aave em-em incrementally shikhe.
- **Batch Learning:** Ek sathe badha available data (batch) mathi offline mode ma shikhe.

### 3. Based on Generalization Method (Working Logic)
Aa joy chhe ke system navi situation ma prediction kevi rite kare chhe.
- **Instance-Based Learning:** Nava data ne known data points sathe simply **compare** karine kaam kare.
- **Model-Based Learning:** Training data mathi patterns **detect** karine ek predictive **model build** kare chhe.

**Note:** Aa categories ne combine kari shakay chhe. Jm ke, ek advanced spam filter **online**, **model-based**, ane **supervised** system hoi shake chhe.

# Supervised Learning

Supervised Learning ma, algorithm ne je **training data** aapvama aave chhe tema solutions pahelathi j shamil hoy chhe. Aa solutions ne **Labels** kahevay chhe. Algorithm nu kaam input data (features) ane output (labels) vachhe na pattern ne shikhavanu chhe.

### Supervised Learning na Mukhya Prakaro (Types)

1.  **Classification:**
    - **Goal:** Koi item ne predefined **category** athva **class** ma mukvu.
    - **Example:** Email ne 'Spam' or 'Ham' ma classify karvi.

2.  **Regression:**
    - **Goal:** Input features na aadhare ek continuous (numeric) **value** ne predict karvi.
    - **Example:** Car ni price teni `mileage`, `age`, ane `brand` na aadhare predict karvi.

### Key Terminology

- **Labels:** Training data ma aapela sacha javabo (correct answers).
- **Features:** Prediction karva mate use thata input variables (e.g., car ni mileage, age).
- **Attribute:** Ek data type (e.g., "mileage").
- **Feature:** Attribute ane teni value banne (e.g., "mileage = 15,000").

### Mahatva na Supervised Learning Algorithms

- k-Nearest Neighbors
- Linear Regression
- Logistic Regression
- Support Vector Machines (SVMs)
- Decision Trees and Random Forests
- Neural Networks
