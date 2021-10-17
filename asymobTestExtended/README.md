# ASYM0B
This is a program to illustrate the usage of the ASYM0B metrics. 

#Requirements
Models dependencies:
 * edu/stanford/nlp/models/ner/english.all.3class.distsim.crf.ser.gz
 * universal-sentence-encoder_4 [For confusing phrases]	
 * stanford-corenlp-4.2.0-models [For analysig intents]
 * edu/stanford/nlp/models/sentiment/sentiment [For analysing sentiments]


## Results

BOT METRICS: 
 * ENT = 1 [eInt]
 * INT = 5 [eInt]
 * NL = 1 [eInt]
 * FLOW = 4 [eInt]
 * PATH = 4 [eInt]
 * LPE = 2.00 [eFloat]
 * SPL = 5.50 [eFloat]
 * WL = 6.64 [eFloat]
 * CL = 2 [eInt]
 * FPATH = 1.00 [eFloat]
 * FACT = 2.00 [eFloat]
 * TPI = 2.60 [eFloat]
 * WPTP = 3.48 [eFloat]
 * PPTP = 0.60 [eFloat]
 *  = -1.00 [eFloat]
 * CPOP = 55.20 [eFloat]
 * READ = 12.00 [eFloat]
 * SNT = 0 13 0  [eString]
 * CNF = 3 [eInt]

ENTITY METRICS: 
 * AppointmentType [LPE = 2 | ESPL = 5.50 | EWL = 6.64 | ]

FLOW METRICS: 
 * Fallback Intent [FPATH = 1 | FFL = 1 | FFACT = 1.00 | ]
 * Hours [FPATH = 1 | FFL = 1 | FFACT = 3.00 | ]
 * Welcome Intent [FPATH = 1 | FFL = 1 | FFACT = 2.00 | ]
 * Make Appointment [FPATH = 1 | FFL = 2 | FFACT = 2.00 | ]

INTENT METRICS: 
 * Hours [INTP = 3 | IWPTP = 4.33 | ICPTP = 16.33 | INP = 0 | INPTP = 0.33 | IVPTP = 1.33 | ITS = Neutral [0, 3, 0] | IWL = 6 | ICS = 0.55 | ]
 * Make Appointment [INTP = 7 | IWPTP = 7.57 | ICPTP = 31.86 | INP = 2 | INPTP = 2.43 | IVPTP = 1.71 | ITS = Neutral [0, 7, 0] | IWL = 11 | ICS = 0.39 | ]
 * Make Appointment - custom [INTP = 2 | IWPTP = 4.50 | ICPTP = 16.50 | INP = 1 | INPTP = 1.00 | IVPTP = 1.00 | ITS = Neutral [0, 2, 0] | IWL = 7 | ICS = 0.36 | ]
 * Welcome Intent [INTP = 1 | IWPTP = 1.00 | ICPTP = 5.00 | INP = 0 | INPTP = 0.00 | IVPTP = 0.00 | ITS = Neutral [0, 1, 0] | IWL = 5 | ICS = 0 | ]
 * Fallback Intent [INTP = 0 | IWPTP = 0.00 | ICPTP = 0.00 | INP = 0 | INPTP = 0.00 | IVPTP = 0.00 | ITS = Neutral [0, 0, 0] | IWL = 0 | ICS = 0 | ]

