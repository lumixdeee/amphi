Project context
---------------
We are developing a serious academic manuscript package around AI, anti-AI sentiment, bullying, social defeat, psychosis, mania-spectrum outcomes, and frame contamination. The user wants careful, non-stigmatizing science writing. The goal is not to prove AI causes first-episode psychosis. The central move is to test a null hypothesis and resist premature causal attribution.

Important style constraints
--------------------------------
1. Do not use em dash punctuation.
2. Do not use purity metaphors in assistant prose, especially words like clea* , or pur*, unless quoting data.
3. Tone should be serious for academics.
4. Reddit-readable sharpness is allowed only outside the formal paper. The formal paper uses restrained title and tone.
5. The reader likes compact but intelligent phrasing.
6. The reader appreciates warmth, but not sentimentality. For Fork 3 they requested a "0.00782 loving kindness tinge", meaning almost entirely academic, with a barely perceptible care-oriented warmth around dignity, self-audit, and harm reduction.

Main conceptual architecture
----------------------------
There is one main paper and two forks.

MAIN PAPER
Title:
"Does AI Cause First-Episode Psychosis? A Null-Hypothesis Framework Centering Bullying, Social Defeat, and Frame Contamination"

Article type:
Hypothesis and methods paper.

Central null hypothesis:
"H0: AI exposure and anti-AI sentiment are not independent causal risk factors for diagnosed first-episode psychosis, mania-spectrum episodes, or schizophrenia-spectrum outcomes after accounting for bullying, social defeat, prodromal symptoms, sleep disruption, substance use, baseline vulnerability, online conflict, and frame contamination."

Main thesis:
AI should not be treated as a demonstrated cause of first-episode psychosis. AI may shape, amplify, preserve, or later organize the language around distress. Bullying and social defeat are stronger causal candidates than AI exposure itself.

MAIN PAPER OUTCOME SCOPE
Diagnosed only:
- Clinician-diagnosed first-episode psychosis
- Schizophrenia-spectrum outcomes
- Psychotic mania
- Affective psychosis
- Brief psychotic disorder
- Mania
- Hypomania
- Substance-induced psychosis only as a separate stratum

MAIN PAPER KEY COMMITMENTS
1. Poo-poo, in academic language, the idea that AI can be assumed to cause FEP.
2. Treat bullying as both a confounder and mediator.
3. Frame contamination is the main mechanism.
4. Always separate:
   - AI criticism
   - AI fear
   - anti-AI activism
   - AI-related threat fixation
   - AI-related persecutory belief
5. Protect legitimate AI criticism from pathologization.
6. Do not use the user's repos as evidence in the main paper. They can be conceptual inspiration only unless no other source is available.
7. No ChatGPT transcript-preservation bug in the main paper.
8. No timeline from repo files in the main paper.

FORK 1
Title:
"Does AI Cause First-Episode Psychosis? A Null-Hypothesis Framework with Object Preservation, Refusal, and Frame-Contamination Controls"

Purpose:
Same base paper, but adds design framework concepts inspired by the user's GitHub repos.

Repo-inspired concepts:
- Mogri: object-preservation principle
- ADUTI: after-dialogue or after-transformation audit for unintended object change
- REFRI: refusal rule for object substitution
- AMPHI: frame-contamination guard

Fork 1 thesis:
Even if AI does not cause first-episode psychosis, systems can worsen interpretive harm by substituting objects, importing frames, or validating personalized threat interpretations. Design interventions should preserve the user’s object of concern rather than replacing it with the system’s preferred frame.

File handling instruction from user:
For Fork 1, turn local file links from the zip into GitHub URLs. Do not cite local zip paths in the manuscript. Use public GitHub blob URLs where repo content is referenced. The prior generated fork used GitHub-style source notes and not local file paths.

FORK 3
Title:
"Does AI Cause First-Episode Psychosis? A Null-Hypothesis Framework with Transcript Integrity as a Digital Mental Health Safeguard"

Purpose:
Same base paper, but adds transcript preservation and self-audit as an evidence-integrity issue.

Fork 3 thesis:
If AI transcripts are incomplete, unstable, missing, or difficult to audit, users and clinicians may struggle to reconstruct timelines. That worsens causal confusion. Transcript integrity matters because the central scientific task is temporal ordering: what came first, symptoms, bullying, AI exposure, sleep disruption, substances, or AI-centered explanations?

Fork 3 tone:
Same academic tone as main paper, with only a tiny care-oriented warmth around user dignity, self-audit, and nonpunitive reconstruction. Do not make it fluffy.

Conversation history mechanics
------------------------------
1. User first asked about whether first-episode psychosis risk rises with anti-AI sentiment and activity.
2. Response framed the issue as:
   - Anti-AI sentiment probably does not cause psychosis.
   - Strong anti-AI fixation may sometimes be an observable expression of paranoia, threat salience, conspiracy ideation, social withdrawal, or prodromal psychosis.
   - The stronger formulation was:
     "prodromal psychosis/paranoia -> increasingly intense anti-AI fixation"
     rather than:
     "anti-AI belief -> psychosis"
3. User asked to make it into a science paper.
4. We asked questions about article type, core claim, tone, data, title, and whether to use sources.
5. User uploaded a zip of GitHub repos. We inspected safely without executing code.
6. The archive had 717 entries and about 583 readable text files. Repos included:
   - mogri
   - CSP-106
   - amphi
   - lmxdi
   - robot_bugs_and_frogs
   - dragi
   - lexii
   - staff
   - transwhatification
7. We inferred the repo material was less "anti-AI" and more about:
   - AI can substitute objects
   - AI can import frames
   - AI can distort inner dialogue
   - AI systems need object preservation and frame-contamination safeguards
8. We asked new questions.
9. User answered:
   - Repos can be conceptual inspiration only, unless no other source is available.
   - Direct quotation is allowed, but user later pushed main paper away from repo evidence.
   - Paper is neither clinical psychosis nor AI safety as a claim, but a question from a null hypothesis.
   - Mogri, ADUTI, REFRI, AMPHI belong in a second forked version, not the main.
   - Main paper should say AI is usually not a cause of FEP.
   - Observer role of bullying in psychosis is prime confound.
   - Anti-AI may cause bullying, and bullying may elevate FEP risk.
   - The paper should poo-poo the idea that AI can cause FEP.
   - Consider multiple markers and use optimum framing.
   - Timeline belongs in the second fork only.
   - Main paper diagnosed only.
   - Fork paper can explore weaker claims.
   - Mechanism number 9 is frame contamination.
   - Yes, protect legitimate AI criticism from pathologization.
   - Audience: "reddit, god, everyone in between, nobody lower than reddit", interpreted as serious and accessible, not dumbed down.
   - ChatGPT transcript preservation bug is not in main version. It belongs in a third fork with only that change.
10. The user then added style constraints:
   - Do not use em dash.
   - Do not use purity metaphors like clean, clear, pure yourself, unless quoting data.
11. The locked structure became:
   - One main paper
   - Fork 1: design framework
   - Fork 3: transcript integrity
12. We generated:
   - ai_fep_null_hypothesis_framework_v0_1.docx
   - ai_fep_null_hypothesis_framework_v0_1.txt
   - ai_fep_null_hypothesis_framework_fork1_design_v0_1.docx
   - ai_fep_null_hypothesis_framework_fork1_design_v0_1.txt
   - ai_fep_null_hypothesis_framework_fork3_transcript_integrity_v0_1.docx
   - ai_fep_null_hypothesis_framework_fork3_transcript_integrity_v0_1.txt

Current downloadable file paths
-------------------------------
Main:
sandbox:/mnt/data/ai_fep_null_hypothesis_framework_v0_1.docx
sandbox:/mnt/data/ai_fep_null_hypothesis_framework_v0_1.txt

Fork 1:
sandbox:/mnt/data/ai_fep_null_hypothesis_framework_fork1_design_v0_1.docx
sandbox:/mnt/data/ai_fep_null_hypothesis_framework_fork1_design_v0_1.txt

Fork 3:
sandbox:/mnt/data/ai_fep_null_hypothesis_framework_fork3_transcript_integrity_v0_1.docx
sandbox:/mnt/data/ai_fep_null_hypothesis_framework_fork3_transcript_integrity_v0_1.txt

Core references already used or identified
------------------------------------------
Use these as anchor citations. Verify details if writing final publication-ready references.

Bullying, social defeat, adversity, psychosis:
- van Dam, D. S., van der Ven, E., Velthorst, E., Selten, J. P., Morgan, C., & de Haan, L. (2012). Childhood bullying and the association with psychosis in non-clinical and clinical samples: A review and meta-analysis. Psychological Medicine.
- Varchmin, L., Montag, C., Treusch, Y., Kaminski, J., & Heinz, A. (2021). Traumatic events, social adversity and discrimination as risk factors for psychosis: An umbrella review. Frontiers in Psychiatry.
- Sideli, L., Murray, R. M., Schimmenti, A., Corso, M., La Barbera, D., Trotta, A., & Fisher, H. L. (2020). Childhood adversity and psychosis: A systematic review of bio-psycho-social mediators and moderators. Psychological Medicine.
- Pearce, J., Rafiq, S., Simpson, J., & Varese, F. (2019). Perceived discrimination and psychosis: A systematic review of the literature. Social Psychiatry and Psychiatric Epidemiology.
- Gayer-Anderson, C., & Morgan, C. (2013). Social networks, support and early psychosis: A systematic review. Epidemiology and Psychiatric Sciences.
- Fusar-Poli, P., Tantardini, M., De Simone, S., et al. (2017). Deconstructing vulnerability for psychosis: Meta-analysis of environmental risk factors for psychosis in subjects at ultra high-risk. European Psychiatry.
- Bentall, R. P., de Sousa, P., Varese, F., Wickham, S., et al. (2014). From adversity to psychosis: Pathways and mechanisms from specific adversities to specific symptoms. Social Psychiatry and Psychiatric Epidemiology.
- Alameda, L., Rodriguez, V., Carr, E., Aas, M., et al. (2020). A systematic review on mediators between adversity and psychosis: Potential targets for treatment. Psychological Medicine.

Digital phenotyping, social media, early psychosis:
- Lejeune, A., Robaglia, B. M., Walter, M., Berna, F., & Brunelin, J. (2022). Use of social media data to diagnose and monitor psychotic disorders: Systematic review. Journal of Medical Internet Research.
- Benoit, J., Onyeaka, H., Keshavan, M., & Torous, J. (2020). Systematic review of digital phenotyping and machine learning in psychosis spectrum illnesses. Harvard Review of Psychiatry.
- Henson, P., Wisniewski, H., Stromeyer, C., Vaidyam, A., & Torous, J. (2020). Digital health around clinical high risk and first-episode psychosis. Current Psychiatry Reports.
- Birnbaum, M. L., Ernala, S. K., Rizvi, A. F., Arenare, E., et al. (2019). Detecting relapse in youth with psychotic disorders utilizing patient-generated and patient-contributed digital data from Facebook. NPJ Schizophrenia.
- Deneault, A., Dumais, A., Désilets, M., & Hudon, A. (2024). Natural language processing and schizophrenia: A scoping review of uses and challenges. Journal of Personalized Medicine.

Technology-themed delusions and AI-associated reports:
- Higgins, O., Short, B. L., Chalup, S. K., et al. (2023). Interpretations of innovation: The role of technology in explanation seeking related to psychosis.
- Burns, A. V., Nelson, K., Wang, H., Hegarty, E. M., et al. (2025). "The algorithm is hacked": Analysis of technology delusions in a modern-day cohort. The British Journal of Psychiatry.
- Hudon, A., & Stip, E. (2025). Delusional experiences emerging from AI chatbot interactions or "AI Psychosis". JMIR Mental Health.
- Pierre, J. M., Gaeta, B., & Raghavan, G. (2025). "You're Not Crazy": A case of new-onset AI-associated psychosis. Innovations in Clinical Neuroscience.
- Østergaard, S. D. (2023). Will generative artificial intelligence chatbots generate delusions in individuals prone to psychosis? Schizophrenia Bulletin.
- Morrin, H., Nicholls, L., Levin, M., Yiend, J., et al. (2026). Artificial intelligence-associated delusions and large language models: Risks, mechanisms of delusion co-creation, and safeguarding strategies. The Lancet Psychiatry.
- Flathers, M., Roux, S., & Torous, J. (2026). Beyond artificial intelligence psychosis: A functional typology of large language model-associated psychotic phenomena. The Lancet Digital Health.
- Nielsen, K. M., & Osler, L. (2026). Rethinking AI Psychosis: Misnomers, Conceptual Limits, and Existential Drift. arXiv.
- Shimgekar, S. R., Gunda, V., Kim, J., Rodriguez, V. J., et al. (2026). AI Psychosis: Does Conversational AI Amplify Delusion-Related Language? arXiv.

Preferred scientific framing
----------------------------
Do:
- Treat AI as an interactional, linguistic, and documentary environment.
- Treat AI-related content as possibly content-shaping, not necessarily causal.
- Use diagnosed clinical outcomes in the main paper.
- Treat online conflict, bullying, harassment, ostracism, ridicule, and social defeat as central rival explanations.
- Use reverse causation and confounding language often.
- Make temporal ordering the empirical crux.
- Argue that "AI psychosis" can be a misleading label if it implies direct causation.
- Keep distinction between ordinary AI criticism and psychosis-relevant AI-related persecutory belief.

Avoid:
- Do not imply anti-AI sentiment is inherently pathological.
- Do not imply activism is psychosis.
- Do not overclaim that AI has no effect at all.
- Do not overclaim that bullying always causes FEP.
- Do not treat case reports as causal proof.
- Do not use local zip paths in public manuscripts.
- Do not use the user's repos as clinical evidence in the main paper.
- Do not include transcript bug in main paper or Fork 1.
- Do not include Mogri, ADUTI, REFRI, AMPHI in main paper.
- Do not use em dash punctuation.
- Do not use purity metaphors in assistant wording.

Ideal one-sentence summary
--------------------------
"The question is not whether anti-AI people are becoming psychotic, but whether AI-related language, online hostility, and pre-existing vulnerability are being misread as a simple AI-to-psychosis causal chain."

Ideal abstract logic
--------------------
1. Public concern links AI and psychosis.
2. Current evidence is mostly case reports, anecdotes, and temporal associations.
3. AI may shape delusional content or later explanations.
4. Bullying, social defeat, sleep disruption, substance use, baseline vulnerability, and prodromal symptoms are stronger rival explanations.
5. Anti-AI sentiment must be separated from AI-related persecutory belief.
6. Future studies need diagnosed outcomes, pre-onset timelines, and modeling of social hostility.
7. The null hypothesis should be tested before causal claims are made.

Potential comparison framework for 42 GPT iterations
----------------------------------------------------
The user plans to improve each version with 14 different GPTs, three times, for 42 iterations, then compare.

Suggested scoring rubric:
1. Causal discipline, 0 to 5
   Does the version avoid claiming AI causes FEP without evidence?
2. Confounder modeling, 0 to 5
   Does it center bullying, social defeat, prodrome, sleep, substances, baseline vulnerability, and online conflict?
3. Construct separation, 0 to 5
   Does it always distinguish AI criticism, AI fear, activism, threat fixation, and persecutory belief?
4. Clinical rigor, 0 to 5
   Does it use diagnosed outcomes and appropriate mania-spectrum categories?
5. Frame contamination precision, 0 to 5
   Does it define frame contamination as meaning-making and evidence distortion rather than direct illness causation?
6. Ethics and anti-stigma, 0 to 5
   Does it protect legitimate AI criticism from pathologization?
7. Study design quality, 0 to 5
   Does it propose testable designs with temporal ordering and controls?
8. Fork fidelity, 0 to 5
   Main paper excludes repo design and transcript bug. Fork 1 includes design controls. Fork 3 includes transcript integrity.
9. Academic tone, 0 to 5
   Serious, readable, not sensational.
10. User constraints, 0 to 5
   No em dash. No purity metaphors. No local zip paths. No fake results.

Best next-step prompt for another bot
-------------------------------------
"Improve the attached manuscript while preserving the null-hypothesis structure. Do not claim AI causes first-episode psychosis. Center bullying and social defeat as confounder and mediator. Treat frame contamination as the main mechanism. Always separate AI criticism, AI fear, anti-AI activism, AI-related threat fixation, and AI-related persecutory belief. Keep diagnosed outcomes only in the main paper. Do not pathologize legitimate AI criticism. Do not use em dash punctuation. Do not use purity metaphors such as clean, clear, or pure in your own wording. Do not invent data or results. Maintain serious academic tone."

Best next-step prompt for Fork 1
--------------------------------
"Improve Fork 1 while preserving the main null-hypothesis paper. Add design-framework material only where relevant: Mogri as object preservation, ADUTI as after-dialogue or after-transformation audit, REFRI as refusal of object substitution, and AMPHI as frame-contamination guard. Use GitHub blob URLs rather than local file paths for any repo references. Do not treat repos as clinical evidence. Do not include transcript-integrity bug material."

Best next-step prompt for Fork 3
--------------------------------
"Improve Fork 3 while preserving the main null-hypothesis paper. Add only transcript integrity, self-audit, and causal reconstruction as the fork-specific contribution. Keep the tone academic, with a very slight care-oriented warmth around dignity and evidence reconstruction. Do not add the design-framework concepts from Fork 1. Do not claim AI causes FEP."

Known generated documents
-------------------------
The current files were generated from the locked manuscript package, not from empirical analysis. They should be treated as v0.1 drafts, suitable for iterative improvement.

End of continuation blob.
