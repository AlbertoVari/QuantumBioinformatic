## Hulk Quantum Bioinformatics Simulator 🧬⚛️💚

Questo progetto è un esperimento didattico e fantascientifico che combina **bioinformatica**, **simulazione di mutazioni genetiche** e **quantum computing**.

Il programma scarica una sequenza genetica reale da NCBI/GenBank, estrae una regione codificante annotata, traduce la sequenza usando il codice genetico standard e simula mutazioni indotte da radiazione gamma in modo probabilistico. Le sequenze originale e mutata vengono poi trasformate in vettori numerici basati su frequenze di codoni o k-mer e codificate in uno stato quantistico tramite PennyLane.

Il confronto tra lo stato quantistico originale e quello mutato viene effettuato tramite **quantum fidelity**, usata come misura di similarità tra i due profili genetici. A partire da dose di radiazione, danno al DNA, cambiamenti proteici, distanza quantistica, capacità di riparazione del DNA e un parametro narrativo di “anger signal”, il programma calcola un indice finale chiamato **Hulk Index**.

L’obiettivo non è costruire un modello biologico predittivo reale, ma mostrare in modo creativo come dati genetici reali possano essere trasformati in feature bioinformatiche e usati come input per circuiti quantistici simulati.

In breve:

* sequenza reale da NCBI;
* estrazione della CDS principale;
* traduzione DNA → proteina;
* simulazione di mutazioni da radiazione gamma;
* confronto tra DNA e proteina originale/mutata;
* codifica quantistica tramite codoni o k-mer;
* calcolo della quantum fidelity;
* classificazione fantascientifica tramite Hulk Index.

Il modello è volutamente ironico: più mutazioni non significano automaticamente “più Hulk”. Se il danno genetico è eccessivo, il programma penalizza il risultato, ad esempio in presenza di stop codon prematuri o frameshift. Questo permette di distinguere tra una trasformazione “compatibile” e un semplice collasso genetico.

Disclaimer scientifico: le radiazioni ionizzanti nella realtà non producono superpoteri. Producono danni molecolari, mutazioni, morte cellulare e aumento del rischio patologico. Questo progetto è solo un esempio educativo e creativo di quantum bioinformatics.




### She-Hulk quantum bioinformatics run 🧬⚛️💚

This run uses a toy **quantum bioinformatics** model to simulate gamma-induced mutations on the real Hepatitis Delta Virus L-HDAg coding sequence (`NC_001653.2`) and encode the resulting genomic profile into a PennyLane quantum state.

Configuration:

```text
Dose gamma: 30 Gy
Gamma sensitivity: 3.0
Cluster strength: 0.2
Anger signal: 0.75
DNA repair efficiency: 0.55
Quantum feature mode: k-mer
KMER_K: 8
Qubits: 16
```

Result summary:

```text
DNA differences: 32 / 645
Protein changes: 26 / 215
Frameshift: False
Indel: False
New stop codons: 2
Quantum fidelity: 0.3987
Quantum distance: 0.6013
Hulk Index: 15.47
Phenotype: stress cellulare gamma
```

Interpretation:

The mutation profile is no longer catastrophic: the reading frame is preserved, no indel is detected, and the protein remains broadly recognizable compared with the reference sequence. The quantum distance indicates a meaningful shift in the encoded genomic state, while the protein-level damage remains moderate.

In Marvel terms: this is not a full Hulk transformation yet, but it looks like a plausible **She-Hulk candidate** — gamma-altered, still coherent, and apparently legally competent.

Scientific disclaimer: this is a playful educational model, not a real radiobiological predictor. Ionizing radiation does not produce superheroes; it produces DNA damage.
