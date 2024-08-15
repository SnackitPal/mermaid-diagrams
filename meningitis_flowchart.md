flowchart TD
    A[Suspected Bacterial Meningitis or Meningococcal Disease]
    A --> B{Assess Symptoms and Risk Factors}
    
    B --> C[Bacterial Meningitis Red Flags]
    C --> C1[Fever]
    C --> C2[Headache]
    C --> C3[Neck stiffness]
    C --> C4[Altered level of consciousness or cognition]
    
    B --> D[Meningococcal Disease Red Flags]
    D --> D1[Haemorrhagic, non-blanching rash with lesions > 2mm]
    D --> D2[Rapidly progressive/spreading non-blanching rash]
    D --> D3[Bacterial meningitis symptoms + non-blanching rash]
    
    B --> E[Risk Factors]
    E --> E1[Missed immunizations]
    E --> E2[Reduced/absent spleen function]
    E --> E3[Complement deficiency]
    E --> E4[Student in shared accommodation]
    E --> E5[Family history]
    E --> E6[Recent contact with infected person]
    E --> E7[Previous episode]
    E --> E8[CSF leak]
    E --> E9[Cochlear implant]
    
    B --> F{Strongly Suspect?}
    F -- Yes --> G[Emergency Transfer to Hospital]
    F -- No --> H[Safety Netting]
    
    G --> I{Clinically Significant Delay?}
    I -- Yes --> J[Give Antibiotics Before Transfer]
    I -- No --> K[Transfer Without Antibiotics]
    
    J --> L[Ceftriaxone or Benzylpenicillin IV/IM]
    
    K --> M[Hospital Management]
    
    M --> N[Initial Assessment by Senior Clinician]
    N --> O[Start Antibiotics Within 1 Hour]
    N --> P[Perform Investigations]
    
    P --> Q[Blood Tests]
    Q --> Q1[Blood culture]
    Q --> Q2[White blood cell count]
    Q --> Q3[CRP or PCT]
    Q --> Q4[Blood glucose]
    Q --> Q5[Whole-blood PCR]
    Q --> Q6[HIV test]
    
    P --> R[Lumbar Puncture]
    R --> R1[If safe and won't delay antibiotics]
    R --> R2[CSF investigations]
    
    P --> S[Bacterial Throat Swab]
    
    O --> T{Causative Organism Known?}
    T -- Yes --> U[Targeted Antibiotic Treatment]
    T -- No --> V[Empiric Antibiotic Treatment]
    
    U --> U1[S. pneumoniae: Ceftriaxone 10 days]
    U --> U2[H. influenzae: Ceftriaxone 7-10 days]
    U --> U3[Group B strep: Ceftriaxone 14 days]
    U --> U4[Enterobacterales: Ceftriaxone 21 days]
    U --> U5[L. monocytogenes: Amoxicillin 21 days]
    U --> U6[N. meningitidis: Ceftriaxone 5 days]
    
    V --> V1[Ceftriaxone]
    V --> V2[Consider adding Amoxicillin if Listeria risk]
    
    M --> W[Adjunctive Treatments]
    W --> W1[Corticosteroids for bacterial meningitis]
    W --> W2[No routine corticosteroids for meningococcal disease]
    W --> W3[No routine fluid restriction]
    W --> W4[No routine osmotic agents]
    W --> W5[No routine ICP monitoring]
    
    M --> X[Ongoing Management]
    X --> Y[Identify Complications]
    Y --> Y1[Cognitive/Neurological]
    Y --> Y2[Orthopaedic/Skin]
    Y --> Y3[Hearing Loss]
    Y --> Y4[Psychosocial]
    
    X --> Z[Prepare for Discharge]
    Z --> Z1[Plan follow-up]
    Z --> Z2[Coordinate with community services]
    Z --> Z3[Provide information and support]
    
    X --> AA[Post-Discharge Care]
    AA --> AB[First Review at 4-6 Weeks]
    AA --> AC[Further Reviews as Needed]
    AA --> AD[Long-term Follow-up]
    
    X --> AE[Assess for Recurrence Risk]
    AE --> AF[Immunodeficiency Evaluation]
    AE --> AG[CSF Leak Investigation]
    
    H --> AI[Provide Safety Netting Advice]
    AI --> AJ[Return if symptoms worsen]
    AI --> AK[Watch for rash changes]
