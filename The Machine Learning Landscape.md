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

# Unsupervised Learning

Unsupervised Learning e Machine Learning ni ek method chhe jema model **unlabeled data** mathi potani jate j patterns, structures, ane insights shodhe chhe. Aama koi "teacher" nathi hotu ane koi sacha javabo (correct labels) pahelathi aapvama nathi aavta. System nu kaam data ma chhupayeli rachna (hidden structure) ne samjvanu chhe.

---

## Unsupervised Learning na Mukhya Prakaro (Main Types)

### 1. Clustering
Aa sauthi common unsupervised task chhe. Aama data ne teni **similarities** (samanata) na aadhare alag-alag **groups** athva **clusters** ma vechvama aave chhe.
- **Goal:** Ek j group ma aavta data points ekbija sathe vadhare malta-julta hoy, ane alag-alag group na data points ekbija thi alag hoy.
- **Example:** Customers ne teni kharidi karvani aadat (purchasing habits) na aadhare alag-alag groups ma mukva jethi targeted marketing kari shakay.
- **Common Algorithms:**
    - K-Means
    - DBSCAN
    - Hierarchical Cluster Analysis (HCA)

---

### 2. Anomaly Detection
Aa technique no upyog data ma **unusual** athva **outlier** data points ne shodhi kadhva mate thay chhe.
- **Goal:** Normal data pattern thi alag padti vastu ne identify karvi.
- **Example:** Credit card transactions ma **fraud** transaction ne shodhi kadhvu, je samanya transaction pattern thi alag hoy.
- **Common Algorithms:**
    - One-Class SVM
    - Isolation Forest
    - Local Outlier Factor (LOF)

---

### 3. Dimensionality Reduction
Jyare data ma ghana badha **features** (columns) hoy, tyare tene saral banavva mate aa technique vapray chhe.
- **Goal:** Mukhya (important) information ne guamavya vagar features ni sankhya ochhi karvi, jethi data ne store karvu ane process karvu saral bani jay.
- **Example:** Ghani badhi details vali customer survey ne 2-3 mukhya factors ma summarize karvi.
- **Common Algorithms:**
    - Principal Component Analysis (PCA)
    - Kernel PCA
    - t-SNE (t-distributed Stochastic Neighbor Embedding)

---

### 4. Association Rule Learning
Aa technique no upyog mota dataset ma items vachhe na **interesting relationships** shodhi kadhva mate thay chhe.
- **Goal:** Eva rules shodhi kadhva je batavi shake ke ek vastu ni sathe biji kai vastu hovani sambhavna chhe.
- **Example:** Supermarket ma "je loko bread kharide chhe, te loko butter pan kharide chhe" evi pattern shodhi kadhvi.
- **Common Algorithms:**
    - Apriori
    - Eclat

# Semisupervised Learning

Semisupervised Learning e **Supervised** ane **Unsupervised Learning** ni vachhe ni ek hybrid method chhe. Aa approach ma, algorithm ne evu data aapvama aave chhe jema thodo bhag **labeled** (jawab sathe) hoy chhe ane moto bhag **unlabeled** (jawab vagar) hoy chhe.

**Main Idea:** Model pahela thoda labeled data mathi shikhe chhe, ane pachhi e knowledge no upyog unlabeled data ma structure ane patterns shodhi kadhva mate kare chhe. Aam, te potani understanding ne vadhare improve kare chhe.

---

## Semisupervised Learning Keni Mate Use Karvu?

Aa approach tya sauthi vadhare upyogi chhe jya:
1.  **Data Labeling Mehengu Hoy:** Data collect karvu saral hoy, pan tene label karva (jawab aapva) ma ghano samay, paisa, athva human effort lagto hoy.
2.  **Thodo Labeled Data Available Hoy:** Tamari pase thodo labeled data to chhe, pan vadhare accuracy medavva mate e purn nathi.

**Example:**
- **Google Photos:** Tame ek vyakti ne ek var olkho chho ("labeled"), pachhi Google potani jate j e vyakti na bija hajaro photos ne olkhi kade chhe ("unlabeled").
- **Medical Images:** Doctor thoda X-rays ma bimari ne identify kare chhe (labeled). Pachhi model e anubhav parthi baki na hajaro X-rays (unlabeled) ma bimari hovani sambhavna shodhi kade chhe.

---

## Common Techniques and Algorithms

Semisupervised learning samanya rite ketlik assumptions par kaam kare chhe, jevu ke:
- **Continuity Assumption:** Je data points ekbija ni najik chhe, teni label pan sarkhi hovani sambhavna vadhare chhe.
- **Cluster Assumption:** Data samanya rite alag-alag clusters (groups) ma vechayelo hoy chhe. Ek j cluster ma aavta badha data points ni label sarkhi hoy chhe.

### Algorithm Examples:
- **Self-Training:**
    - Aa ek technique chhe jema koi pan supervised classifier no upyog kari shakay. Model pahela labeled data par train thay chhe. Pachhi te unlabeled data par predictions kare chhe. Sauthi confident predictions ne nava "labels" tarike add kari devama aave chhe ane model ne aa nava data sathe farithi train karvama aave chhe.
- **Generative Models:**
    - Aa models data kevi rite generate thayo hashe e shikhavano prayatna kare chhe.
    - *Example:* **Gaussian Mixture Models (GMMs)** no upyog clustering ane classification banne mate thay chhe.
- **Graph-Based Methods:**
    - Aa methods data points ne ek graph na nodes tarike jove chhe ane labels ne graph par "propagate" (felave) chhe.
    - *Examples:* **Label Propagation**, **Label Spreading**.
- **Transductive SVM (TSVM):**
    - Aa Support Vector Machine (SVM) nu ek version chhe je unlabeled data no upyog kari ne best decision boundary shodhavano prayatna kare chhe.

# Reinforcement Learning (RL)

Reinforcement Learning e Machine Learning ni ek aevi branch chhe jema ek **agent** (e.g., ek robot, ek game character) ek **environment** (e.g., ek game, ek real-world scenario) ma potani jate j shikhvanu prayatna kare chhe. Aa `trial and error` method par kaam kare chhe.

**Main Idea:** Agent ek **action** (karya) kare chhe. E action na parinaam swarupe, environment tene ek **reward** (shabashi) athva ek **penalty** (saza) aape chhe. Agent no **goal** e aevi strategy (*policy*) shikhvano chhe jethi te samay sathe potani total reward ne **maximize** (vadhare ma vadhare) kari shake.

---

## Reinforcement Learning na Mukhya Components

- **Agent:** Je shikhe chhe ane nirnay le chhe (e.g., game no player).
- **Environment:** Jeni sathe Agent interact kare chhe (e.g., game nu jagat).
- **Action:** Agent je pan karya kari shake chhe (e.g., aagal chalvu, jump marvo).
- **State:** Environment ni current situation (e.g., player kyan chhe, score shu chhe).
- **Reward:** Saru kaam karva par malto positive feedback (+1 point).
- **Penalty:** Khotu kaam karva par malto negative feedback (-10 points).
- **Policy:** Agent ni strategy, je batavve chhe ke kai state ma kai action levi joiye.

---

## Reinforcement Learning Keni Mate Use Karvu?

Aa approach tya sauthi vadhare upyogi chhe jya problem no koi sidho solution nathi, pan ek goal (lakshya) chhe.
- **Game Playing:** Computer ne potani jate Chess, Go, ke video games ramta shikhadvva (e.g., AlphaGo).
- **Robotics:** Robots ne chalvu, vastu uthavvi, ke complex tasks potani jate j karta shikhadvva.
- **Self-Driving Cars:** Car ne potani jate traffic ma kevi rite chalavvi te shikhadvva.
- **Resource Management:** Ek mota computer network ma resources ne kevi rite best rite manage karva.

---

## Common Reinforcement Learning Algorithms

RL algorithms ne mukhya rite be bhag ma vechi shakay chhe:

### 1. Model-Based
Aa algorithms pahela environment no ek internal model (naksho) banavvano prayatna kare chhe.
- **Example:**
    - Dynamic Programming

### 2. Model-Free
Aa algorithms environment no koi model banavya vagar, sidha trial and error parthi policy shikhe chhe. Aa vadhare common chhe.
- **Examples:**
    - **Q-Learning:** Ek popular algorithm je Q-table no upyog karine shikhe chhe ke koi pan state ma kai action levathi sauthi vadhare reward malshe.
    - **SARSA (State-Action-Reward-State-Action):** Q-Learning jevo j chhe pan thodo alag rite update thay chhe.
    - **Deep Q-Networks (DQN):** Jyare states ni sankhya khub j vadhare hoy (jevuke, video game ni screen), tyare Q-table ni jagyae Neural Network no upyog kare chhe.
    - **Policy Gradient Methods (e.g., REINFORCE, A2C, A3C):** Aa algorithms sidhi rite policy ne j optimize karvano prayatna kare chhe.

# Batch Learning (Offline Learning)

Batch Learning, jene **Offline Learning** pan kahevay chhe, e Machine Learning ni ek training method chhe jema model ne **badha j available data** par ek sathe train karvama aave chhe. Ek var training purn thai jay, pachhi model ne "launch" karvama aave chhe ane te potani jate kai navu shikhtu nathi.

**Main Idea:** Model ne train karva mate ek "batch" (samuh) ma badho data aapvama aave chhe. Navi vastu shikhva mate, tene badha **juna ane nava data** par **farithi pahelathi (from scratch)** train karvu pade chhe.

---

## Batch Learning ni Process

1.  **Data Collection:** Badho j jaruri data ektho karvama aave chhe.
2.  **Offline Training:** Model ne aa sampurn dataset par train karvama aave chhe. Aa process ghano samay ane computing resources (CPU, memory) lai shake chhe.
3.  **Launch Model:** Ek var model taiyar thai jay, tene system ma deploy karvama aave chhe jya te predictions karvanu sharu kare chhe. Aa stage par te kai navu shikhtu nathi.
4.  **Retraining:** Jyare pan tamari pase navo data aave athva system ni performance ochhi thay, tyare tamare model ne **sampurn dataset (jun + navu)** par farithi train karvu pade chhe ane navu version launch karvu pade chhe.

---

## Characteristics

### Fayda (Pros):
- **Simplicity:** Aa process sidhi ane saral chhe.
- **Stability:** Jo data representative hoy, to model ghanu stable bane chhe.

### Gerfayda (Cons):
- **Resource Intensive:** Training mate ghano samay ane powerful hardware ni jarur pade chhe.
- **Not for Rapidly Changing Data:** Je systems ma data satat badlato hoy (jevuke, stock market), tena mate aa yogya nathi.
- **No Incremental Learning:** Te dhire-dhire navi vastu nathi shikhi shaktu. Darekvakhte aakhi process farithi karvi pade chhe.

---

## Example: Image Classifier

Dharo ke tamare ek model banavvu chhe je **kutta (dogs)** ane **biladi (cats)** na photos ne olkhi shake.

1.  **Training (Batch Process):**
    - Tame 50,000 kutta na ane 50,000 biladi na photos (total 1 lakh photos no ek **batch**) collect karo chho.
    - Tame aa 1 lakh photos par tamara model ne kayi divaso sudhi **train** karo chho.

2.  **Launch:**
    - Have tamaru model taiyar chhe. Tame tene ek app ma muko chho jya te nava photos ne kutta ke biladi tarike classify kare chhe.

3.  **Retraining Scenario:**
    - Have tamare **ghoda (horses)** ne pan olkhavva chhe.
    - Tamare 50,000 ghoda na photos collect karva padshe.
    - Have tame model ne fakt ghoda na photos par train nahi kari shako. Tamare **badha j 1.5 lakh photos (kutta + biladi + ghoda)** par model ne **farithi shuruaat thi** train karvu padshe.
  
# Online Learning

Online Learning e Machine Learning ni ek dynamic training method chhe jema model **incrementally** (tukde-tukde ma) nava data mathi satat shikhtu rahe chhe. Aa data ne **individually** athva **mini-batches** (nana groups) ma process kare chhe.

**Main Idea:** System ne badha data par ek sathe train karvani jarur nathi. Jevo navo data aave, system **tarat j (on the fly)** tenathi shikhi le chhe ane potana knowledge ne update kari de chhe. Aa batch learning thi bilkul ultu chhe.

---

## Online Learning ni Process

1.  **Data Input:** System ne ek pachhi ek data point athva data no ek nano batch aapvama aave chhe.
2.  **Instant Learning:** System e data par prediction kare chhe, teni bhul (error) ne mape chhe, ane e bhul na aadhare potana parameters ne **tarat j update** kare chhe.
3.  **Discard Data:** Ek var data mathi shikhai jay, pachhi tene store karvani jarur nathi (jo tame ichho to kari shako), jethi memory ni bachat thay chhe.
4.  **Repeat:** Aa process satat chalti rahe chhe jevo-jevo navo data aavto jay.

---

## Characteristics

### Fayda (Pros):
- **Fast and Efficient:** Te khub j jadapthi nava data sathe adapt thai jay chhe, jethi te rapidly changing data mate ideal chhe.
- **Resource Friendly:** Tene badho data ek sathe store karvani jarur nathi, jethi te ochha resources (memory, disk space) ma kaam kari shake chhe.
- **Scalable:** Te eva vishal datasets (huge datasets) ne handle kari shake chhe je ek machine ni memory ma fit na thai shake.

### Gerfayda (Cons):
- **Sensitive to Bad Data:** Jo system ne kharab quality no data aapvama aave, to teni performance tarat j kharab thai shake chhe.
- **Needs Monitoring:** Samay sathe system ni performance degrade thai shake chhe, etle teni par satat dhyan rakhvu jaruri chhe.

---

## Example: Social Media Feed

Dharo ke tamare ek system banavvi chhe je social media par users ne teni pasand na posts batavve.

1.  **Initial State:** Shuruaat ma, system ne tamara vishe kai khabar nathi, etle te tamne random posts batavve chhe.
2.  **Action and Learning (Online Process):**
    - Tame ek **cat video** par **"Like"** karo chho.
    - System aa **nava data point** ne tarat j process kare chhe ane shikhe chhe ke tamne cats ma interest chhe.
    - Have tamari feed ma te thoda vadhare cat videos batavvanu sharu kari deshe.
    - Pachhi tame ek **cricket match ni highlight** jovo chho.
    - System aa navi information ne pan tarat j add kari deshe ane have tamne cricket related posts pan batavshe.
3.  **Continuous Adaptation:** Aa process satat chalti rahe chhe. Tame je pan like, share, ke skip karo chho, tenathi system **real-time ma** shikhtu rahe chhe ane tamari feed ne vadhare relevant banavtu rahe chhe.

Aa system 24 kalak raah nathi joti ke tame shu karyu, te **dareke-darek action** par potani jate **update** thay chhe.

# Instance-Based Learning

Instance-Based Learning e Machine Learning ni ek aevi method chhe jema system potani jate koi explicit model nathi banavtu. Teni jagyae, te **sampurn training dataset ne j yaad rakhe chhe**. Jyare koi navo data point aave, tyare te aakha training set sathe teni **similarity** (samanata) ne mape chhe ane teno upyog prediction karva mate kare chhe.

Aa approach ne **Lazy Learning** pan kahevay chhe, kem ke te training na samaye kai "shikhtu" nathi, pan prediction na samaye j badhu kaam kare chhe.

---

## Instance-Based Learning ni Process

1.  **Store Data (Training):** Aakha training dataset ne memory ma store kari devama aave chhe. Aa stage par koi computation nathi thatu.
2.  **Measure Similarity (Prediction):** Jyare ek navo, unlabeled instance aave, tyare system ek **similarity measure** (jevuke, Euclidean distance) no upyog karine nava instance ane training set na darek instance vachhe nu antar (distance) calculate kare chhe.
3.  **Predict:** Sauthi vadhare similar (sauthi najik na) training instances na aadhare prediction karvama aave chhe.

---

## Characteristics

### Fayda (Pros):
- **Simple to Implement:** Aano concept khub j saral chhe.
- **Adapts Easily:** Te nava data ne saraltathi adapt kari le chhe, fakt tene dataset ma add kari devanu hoy chhe.
- **Complex Decision Boundaries:** Te khub j complex patterns ne pan olkhi shake chhe.

### Gerfayda (Cons):
- **Slow Predictions:** Jo training dataset khub j moto hoy, to darek nava prediction mate aakha dataset ne scan karvama ghano samay lage chhe.
- **High Memory Usage:** Tene aakho dataset memory ma store karvo pade chhe.
- **Sensitive to Irrelevant Features:** Jo data ma ghani બિનજરૂરી features hoy, to similarity measure sachu kaam nathi karto.

---

## Example: Spam Filter

Dharo ke tamare ek spam filter banavvu chhe je **instance-based learning** no upyog kare.

1.  **Training (Storing):**
    - System hajaro emails ne teni "spam" ke "not spam" (ham) label sathe potani memory ma **store** kari le chhe. Te kai shikhtu nathi, fakt yaad rakhe chhe.

2.  **Prediction (Comparing):**
    - Have ek **navo email** aave chhe.
    - System aa nava email ne potani memory ma rahela **badha juna emails sathe compare** kare chhe. Te joy chhe ke nava email ma je shabdo chhe, e juna spam emails sathe vadhare male chhe ke juna ham emails sathe.
    - Dharo ke system ne khabar pade chhe ke navo email potani memory ma rahela **10 spam emails sathe 90% similar chhe** ane **3 ham emails sathe 15% similar chhe.**

3.  **Final Decision:**
    - Kem ke navo email spam emails sathe vadhare similar chhe, system tene **"Spam"** tarike classify kari deshe.

Aa badhi process ma, system e koi "rule" nathi banavyo ke "free" shabd aave to spam hoy. Tene fakt similarity na aadhare nirnay lidho.

# Model-Based Learning

Model-based learning e Machine Learning ni ek **"smart"** approach chhe jema system pahela data ne study kare chhe, tema ek **pattern** shodhe chhe, ane e pattern na aadhare ek niyam (**rule**) athva **model** banave chhe. Pachhi, navi vastu par prediction karva mate, te aakha data ne farithi jovani jagyae potana banavela model no j upyog kare chhe.

**Main Idea:** Data mathi shikho -> Ek general rule (model) banavo -> E rule no upyog kari ne predictions karo.

---

## Model-Based Learning ni Process

1.  **Study the Data:** Pahela, data ne analyze karvama aave chhe jethi tema koi trend ke pattern chhe ke nahi e khabar pade.
2.  **Select a Model:** Data na trend na aadhare ek model no prakar select karvama aave chhe (e.g., linear model, polynomial model).
3.  **Train the Model:** Have, training data no upyog karine model na best **parameters** (values) shodhavama aave chhe. Aa process no goal ek evu model banavvano chhe je training data par sauthi best રીતે fit thay. Aane **"training"** kahevay chhe.
4.  **Inference (Prediction):** Ek var model train thai jay, pachhi te nava data par predictions karva mate taiyar chhe. Aa stage ne **inference** kahevay chhe.

---

## Characteristics

### Fayda (Pros) ✅

* **Fast Predictions:** Ek var model taiyar thai jay, pachhi predictions karva khub j jadapthi thay chhe.
* **Less Memory:** Tene aakho dataset yaad rakhvani jarur nathi, fakt train thayela model na parameters j yaad rakhva pade chhe.
* **Good Generalization:** Saru model nava, anjaan data par pan sara predictions aapi shake chhe.

### Gerfayda (Cons) ❌

* **Upfront Work:** Saru model select karva ane tene train karva ma vadhare mehenat ane samay lage chhe.
* **Bad Assumptions:** Jo shuruaat ma j khoto model select karvama aave, to predictions pan khota j aavshe.

---

## Example: Paisa ane Khushi (Money and Happiness) 💰😊

Dharo ke tamare e janvu chhe ke vadhare paisa (GDP) hovathi shu deshna loko vadhare khush (Life Satisfaction) hoy chhe?

1.  **Study the Data:** Tame alag-alag desho no GDP ane Life Satisfaction no data jovo chho. Tamne ek trend dekhay chhe: je desh no GDP vadhare chhe, teno Life Satisfaction score pan vadhare chhe.

2.  **Select a Model:** Aa trend lagbhag ek sidhi line jevo lage chhe, etle tame ek **Linear Model** select karo chho. Tamaro niyam (model) kaik aavo hashe:
    ```
    life_satisfaction = Param1 + Param2 × GDP_per_capita
    ```

3.  **Train the Model:** Have, tame tamara data no upyog karine computer ne `Param1` ane `Param2` ni sauthi best value shodhavanu kaho chho jethi tamari line data points thi sauthi najik rahe. Training pachi, computer tamne kahe chhe ke `Param1 = 4.85` ane `Param2 = 0.0000491` chhe. Have tamaro final model taiyar chhe!

4.  **Prediction (Inference):** Have tamare Cyprus desh mate Life Satisfaction janvvo chhe, jeno data tamari pase nathi. Tame fakt Cyprus no GDP ($22,587) shodho chho ane tene tamara model ma muko chho:
    ```
    Prediction = 4.85 + 0.0000491 × 22587
    Jawab = 5.96
    ```
    Tame aakha data ne joya vagar, fakt tamara banavela model no upyog karine jawab medhavi lidho.
# Machine Learning na Mukhya Challenges

Machine Learning ma project banavti vakhte, be mukhya vastu khoti thai shake chhe: "**kharab algorithm**" athva "**kharab data**". Ahi aapne kharab data na ek mukhya prakar par dhyan aapishu.

## Apurti Matra ma Training Data (Insufficient Quantity of Training Data)

Aa ML ni sauthi common samasya chhe. Manviya magaj (jevuke, ek nanu badak) thoda j examples mathi "safarjan" shu chhe e shikhi le chhe, pan Machine Learning algorithms ne barabar kaam karva mate khub j vadhare data ni jarur pade chhe.

### Key Points:

* **Data ni Jaruriyat:** Saral problems mate pan hajaro examples joiye, jyare image/speech recognition jeva complex problems mate lakhotha examples ni jarur padi shake chhe.
* **"The Unreasonable Effectiveness of Data":** Ek famous research paper e batavyu ke ghani var, complex problems mate, alag-alag algorithms ni performance lagbhag sarkhi j hoy chhe jo temne purn matra ma data aapvama aave.
* **Data vs. Algorithm:** Aa batavve chhe ke ghana cases ma, ek saro algorithm shodva par mehenat karva karta, vadhare data ektho karva par dhyan aapvu vadhare faydakarak hoi shake chhe.

### Conclusion:

Jo ke, nana ane medium-sized datasets haji pan common chhe ane navo data medavvo hamesha saral ke sasto nathi hoto. Etle, data sauthi mahatva no chhe, pan algorithms ne pan bhuli na javay.

# Nonrepresentative Training Data (Apratinidhi Training Data)

Machine Learning ma saru generalization karva mate e khub j jaruri chhe ke tamaro training data e asli duniya (real-world cases) no sacho pratinidhi (representative) hoy. Jo tamaro training data biased (pakshpati) hashe, to tamaru model sacha predictions nahi kari shake.

## Samasya Shu Chhe?

Imagine karo ke tame ek model ne "kutro" olkhta shikhavva mate fakt Golden Retriever na j photos batavo chho.

* **Model Shu Shikshe?:** Model evu shikhi leshe ke "kutro etle ek motu, golden color nu, lamba val vadu prani."
* **Asli Duniya ma Shu Thashe?:** Jyare aa model ek nano, kalo Pug ke ek safed street dog ne joshe, tyare te kahishe, "Aa kutro nathi!" kem ke te teni training ma joyela examples jevu nathi.

Aa bhul etle thai kem ke training data asli duniya na badha j kutra no representative nohto.

## Nonrepresentative Data na Karano

### 1. Sampling Noise

* **Shu Chhe?:** Jyare tamaro sample size khub j nano hoy, tyare tak (chance) na karane evu bani shake ke tamne nonrepresentative data mali jay.
* **Example:** Jo tame fakt 5 loko na j group parthi aakha desh mate anuman lagavo, to e sachu na hoi shake.

### 2. Sampling Bias

* **Shu Chhe?:** Aa ek vadhare gambhir samasya chhe. Aama, bhale tamaro sample size moto hoy, pan tamari data collect karvani method ma j khami hoy chhe.
* **Famous Example (1936 US Election):**
    * Ek magazine (Literary Digest) e 1 crore lokone poll moklyo ane predict karyu ke Landon jitshe. Pan, Roosevelt jiti gaya.
    * **Bhul Shu Hati?:**
        * Temne mail mokalva mate telephone directories ane magazine subscriber lists no upyog karyo hato, jema tenaj samay ma vadhare paisadar loko hata. Paisadar loko Landon ne support karta hata.
        * Fakt 25% loko e j jawab apyo. Je loko e jawab na apyo (nonresponse bias), te alag group na hoi shake chhe.

### Conclusion:

Tamaro training set je cases par tame anuman lagavva mango chho teno sacho aaino (mirror) hovo joiye.
