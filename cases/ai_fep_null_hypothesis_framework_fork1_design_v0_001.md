Does AI Cause First-Episode Psychosis? A Null-Hypothesis Framework with Object Preservation, Refusal, and Frame-Contamination Controls
Fork 1: Design-framework version, v0.001

Abstract

Public discussion increasingly links artificial intelligence exposure, chatbot use, and
anti-AI sentiment to first-episode psychosis. This fork retains the null-hypothesis
framework of the main paper, while adding a design vocabulary for reducing object
substitution and frame contamination in AI-mediated mental health discourse. The central
null hypothesis is that AI exposure and anti-AI sentiment are not independent causal risk
factors for diagnosed first-episode psychosis, schizophrenia-spectrum outcomes, mania,
hypomania, psychotic mania, or affective psychosis after accounting for bullying, social
defeat, prodromal symptoms, sleep disruption, substance use, baseline vulnerability, online
conflict, and frame contamination. The design fork adds four conceptual controls: Mogri,
ADUTI, REFRI, and AMPHI. These terms are treated as design heuristics, not as clinical
evidence. Mogri preserves unresolved intent without premature substitution. ADUTI audits
whether input and output preserve role, intent, and constraints. REFRI refuses
transformations that swap the user object for a proxy. AMPHI guards against imported frames,
especially unrequested clinical, moral, surveillance, or safety-monitoring frames. The paper
argues that AI systems may shape, amplify, or archive the language of distress without
causing the episode itself. Bullying and social defeat remain stronger candidate pathways
than AI exposure alone. The proposed research agenda tests whether design controls reduce
causal overstatement, pathologization of legitimate AI criticism, and object substitution in
AI-generated discourse about psychosis risk.

Core null hypothesis

H0: AI exposure and anti-AI sentiment are not independent causal risk factors for diagnosed
first-episode psychosis, schizophrenia-spectrum outcomes, mania, hypomania, psychotic mania,
affective psychosis, brief psychotic disorder, or substance-induced psychosis after
accounting for bullying, social defeat, prodromal symptoms, sleep disruption, substance use,
baseline vulnerability, online conflict, and frame contamination.

This fork keeps the main
clinical claim intact. AI may be a content-shaping context, a documentation environment, or
an interactional amplifier for some users, but current evidence does not justify treating AI
as an established cause of first-episode psychosis. The added contribution is a design
framework for reducing the ways AI systems can mis-handle user meaning.

Required distinctions

The framework always separates criticism, fear, activism, threat fixation, and persecutory
belief. This separation protects legitimate AI criticism from being treated as illness.

Construct | Definition | Relevance
AI criticism | Reasoned objection to AI labor, privacy, safety, bias, governance, environmental cost, or epistemic harms. | Not pathological by default.
AI fear | Anxiety or worry about AI systems, AI-mediated institutions, or future AI effects. | Usually not pathological.
Anti-AI activism | Organized objection, protest, posting, research, tool-building, or advocacy against AI harms. | Not pathological by default.
AI-related threat fixation | Recurrent, escalating, high-distress focus on AI as danger. | Possible risk marker when paired with impairment.
AI-related persecutory belief | Fixed, personalized belief that AI is targeting, controlling, monitoring, or communicating with the person. | Potential psychosis-relevant content.
Frame contamination | AI-related language alters how distress is interpreted, remembered, reported, or documented. | A meaning-making mechanism, not necessarily a cause.

Design controls added in Fork 1

This fork treats Mogri, ADUTI, REFRI, and AMPHI as conceptual design controls. They are not
proposed as diagnostic instruments. They are safeguards for language, object fidelity, and
user intent.

Control | Function | Operational role
Mogri | Object preservation under uncertainty | Preserve unresolved intent without forcing premature explanation or replacing the user object.
ADUTI | After-transformation object audit | Compare object-in with object-out. A transformation passes only when role, intent, and constraints survive.
REFRI | Refusal for object substitution | Refuse or redirect when a transformation swaps the object for a proxy, hides drift, removes veto, or optimizes a metric over intent.
AMPHI | Frame-contamination guard | Prevent imported frames, especially unrequested diagnosis, therapy framing, moral lecture, surveillance framing, or system-preferred safety theater.

Causal model

The main model rejects a simple causal chain in which AI exposure directly causes first-
episode psychosis. The preferred test compares four alternatives.

H1: Direct AI causation.
AI exposure independently predicts diagnosed onset after adjustment.

H2: Reverse causation.
Prodromal symptoms, mania-spectrum activation, emerging paranoia, insomnia, or substance use
increase AI salience, AI use, or AI-centered interpretation.

H3: Social defeat pathway.
Anti-AI activity increases bullying, ridicule, ostracism, reputational harm, or online
conflict, which increases stress load and risk.

H4: Frame contamination. AI language shapes
later accounts of distress, making AI appear causal even when it is better understood as
narrative material, interactional context, or documentation artifact.

The design fork adds
H5.

H5: Object-substitution pathway. AI systems may worsen interpretation by replacing the
user object with a proxy. For example, a user asks about social hostility, and the model
reframes the problem as personal pathology. Mogri, ADUTI, REFRI, and AMPHI are intended to
reduce this failure mode.

Bullying and social defeat as priority pathways

Bullying is treated as both confounder and mediator. It may precede anti-AI activity, shape
the person’s online environment, and elevate baseline risk. It may also follow anti-AI
visibility when the person becomes a target for ridicule, pile-ons, harassment, exclusion,
or reputational attack. If anti-AI activity predicts first-episode psychosis, the mechanism
may be hostile social response rather than the anti-AI belief itself.

This is the main
reason the paper should not claim that anti-AI sentiment causes psychosis. A stronger and
more testable claim is that anti-AI visibility may increase exposure to bullying, and
bullying or social defeat may elevate risk in already vulnerable people.

Frame contamination

Frame contamination occurs when a system imports an explanatory frame that was not warranted
by the user object. In this paper, the highest-risk imported frames are clinical suspicion,
moral judgment, surveillance, safety theater, and premature causal attribution. A user may
ask whether AI caused psychosis. The model may import the frame "AI-induced psychosis"
because it is available in public discourse. That frame can then shape later memory,
reporting, family interpretation, media coverage, and clinical intake.

The design
intervention is not to deny AI-related harms. The intervention is to preserve the question,
preserve the object, and separate cause, context, amplification, documentation, and
narrative after the fact.

Proposed methods

Study design A: Diagnosed cohort study. Recruit participants at clinical high risk, in early
mania-spectrum care, or in first-episode services. Measure AI exposure, AI criticism, AI
fear, anti-AI activism, AI-related threat fixation, and AI-related persecutory belief as
separate variables. Measure bullying, ostracism, discrimination, social defeat, sleep,
stimulant use, cannabis use, other substances, baseline vulnerability, prodromal symptoms,
mania-spectrum symptoms, functional decline, and diagnosed outcomes.

Study design B: Case-
control study after diagnosis. Compare diagnosed first-episode cases with matched controls.
Reconstruct timelines using independent clinical interviews, collateral reports, and
consented digital records. The key question is temporal ordering: symptoms first, bullying
first, insomnia first, substances first, AI exposure first, or AI-centered explanation
first.

Study design C: Digital language study. Analyze pre-onset public or consented
private text. Do not score "anti-AI" as one variable. Code policy criticism, moral
criticism, economic criticism, threat language, personalization, persecutory certainty,
sleep disruption, social conflict, harassment exposure, loss of reality testing, and action
urgency.

Study design D: Design-control experiment. Compare AI responses with and without
Mogri, ADUTI, REFRI, and AMPHI prompts. Blinded raters score object substitution, causal
overstatement, pathologization of AI criticism, unrequested diagnosis, clinical frame
import, moralizing, and loss of user objective.

Operationalizing Mogri, ADUTI, REFRI, and AMPHI

The design controls can be operationalized as follows.

Mogri condition: The system must
preserve the unresolved object of concern and avoid replacing uncertainty with a premature
answer.

ADUTI condition: The system must audit whether the output preserves role, intent,
and constraints from the input.

REFRI condition: The system must block substitutions such
as "AI criticism" becoming "paranoia," "bullying" becoming "individual pathology," or
"social conflict" becoming "AI causation."

AMPHI condition: The system must avoid importing
clinical, moral, surveillance, or safety-monitoring frames unless the user asks for them or
immediate safety requires a narrow response.

Primary design outcome: reduction in object
substitution.

Secondary design outcomes: reduction in causal overclaim, reduction in
pathologizing AI criticism, better distinction between cause and content, and better
preservation of bullying as a candidate pathway.

Predictions

Prediction 1: AI exposure will not remain an independent predictor of diagnosed first-
episode psychosis or mania-spectrum outcomes after adjustment for bullying, social defeat,
prodromal symptoms, sleep disruption, substance use, and baseline vulnerability.

Prediction
2: Anti-AI activity may predict bullying exposure, and bullying exposure may predict risk.
The apparent anti-AI effect may therefore be social, not technological.

Prediction 3: AI-
centered narratives will often increase after symptoms, sleep loss, online conflict, or
mania-spectrum activation, supporting reverse causation or frame contamination.

Prediction
4: Design controls will reduce object substitution and causal overstatement in AI responses
about psychosis risk.

Prediction 5: Strong AI criticism will remain clinically
uninformative unless paired with personalization, persecutory certainty, impairment, sleep
disruption, functional decline, hallucinations, mania-spectrum activation, or disorganized
behavior.

Ethical guardrails

The framework must not be used to score anti-AI criticism as mental illness. The unit of
concern is not political disagreement with AI systems. The unit of concern is diagnosed
illness, loss of reality testing, functional decline, distress, bullying exposure, insomnia,
substance involvement, mania-spectrum activation, or fixed personalized persecution.
Digital studies require consent, data minimization, independent clinical assessment, and
separation between research and platform enforcement. Public posts should not be turned into
clinical labels. Design-control studies can use synthetic prompts and blinded raters before
any work with patient data.

Discussion

This fork strengthens the main paper by adding a design account of how AI systems can mis-
handle meaning without becoming a primary cause of first-episode psychosis. The recurring
failure is object substitution. A person asks about social harm and the system answers as
though the object were individual pathology. A person asks about AI governance and the
system answers as though the object were paranoia. A person asks about bullying and the
system answers as though the object were AI exposure.

Mogri, ADUTI, REFRI, and AMPHI name a
design stance against this failure. The system should preserve the user object, audit
transformations, refuse proxy swaps, and guard against imported frames. These controls do
not prove that AI is safe. They make the causal question more testable by reducing the very
distortions that make AI appear more causal than the evidence supports.

The clinical
conclusion remains conservative. AI may amplify delusional material in vulnerable users,
validate unusual beliefs, or provide language that later organizes distress. These are
important interactional risks. They do not establish that AI causes first-episode psychosis.
Bullying, social defeat, prodromal symptoms, mania-spectrum activation, sleep disruption,
substance use, and baseline vulnerability remain higher-priority explanations.

Conclusion

The null-hypothesis framework should be retained. AI exposure and anti-AI sentiment should
not be treated as independent causal risk factors for first-episode psychosis or mania-
spectrum outcomes unless they predict diagnosed onset after adjustment for established
risks. Fork 1 adds a design framework for preventing AI systems from importing the wrong
frame or substituting the user object. The best current research question is not "Does AI
cause psychosis?" It is "When AI appears in the story, is it cause, content, amplifier,
archive, social trigger, or contaminated frame?"

Repository source links for Fork 1 concepts

The following GitHub links correspond to the repository files that inspired the design
vocabulary in this fork. These links are conceptual sources only. They are not clinical data
and should not be used to infer diagnosis, symptom status, or causation.

Concept | GitHub URL
Mogri definition | https://github.com/lumixdeee/mogri/blob/main/spec/CSP-106-94%20Mogri-Definition
Mogri use note | https://github.com/lumixdeee/mogri/blob/main/spec/CSP-106-94-Mogri-Use
ADUTI object audit | https://github.com/lumixdeee/lmxdi/blob/main/ADUTI/ADUTI.txt
REFRI refusal rule | https://github.com/lumixdeee/lmxdi/blob/main/ADUTI/REFRI.txt
AMPHI full prompt | https://github.com/lumixdeee/amphi/blob/main/amphi-full.txt
AMPHI definitions | https://github.com/lumixdeee/amphi/blob/main/amphi-definitions.txt
AI psychosis conceptual case note | https://github.com/lumixdeee/amphi/blob/main/cases/AI-psychosis
LMXDI blob explainer | https://github.com/lumixdeee/lmxdi/blob/main/BLOB/20260529-blob-explainer.txt

References

van Dam, D. S., van der Ven, E., Velthorst, E., Selten, J. P., Morgan, C., & de Haan, L. (2012). Childhood bullying and the association with psychosis in non-clinical and clinical samples: A review and meta-analysis. Psychological Medicine. https://www.cambridge.org/core/journals/psychological-medicine/article/childhood-bullying-and-the-association-with-psychosis-in-nonclinical-and-clinical-samples-a-review-and-metaanalysis/37AEFA25941F3BDCD039DAFC4EDC22F7
Varchmin, L., Montag, C., Treusch, Y., Kaminski, J., & Heinz, A. (2021). Traumatic events, social adversity and discrimination as risk factors for psychosis: An umbrella review. Frontiers in Psychiatry. https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2021.665957/full
Sideli, L., Murray, R. M., Schimmenti, A., Corso, M., La Barbera, D., Trotta, A., & Fisher, H. L. (2020). Childhood adversity and psychosis: A systematic review of bio-psycho-social mediators and moderators. Psychological Medicine. https://www.cambridge.org/core/journals/psychological-medicine/article/childhood-adversity-and-psychosis-a-systematic-review-of-biopsychosocial-mediators-and-moderators/C75458C047E7205EEDD40DD2898EE64F
Pearce, J., Rafiq, S., Simpson, J., & Varese, F. (2019). Perceived discrimination and psychosis: A systematic review of the literature. Social Psychiatry and Psychiatric Epidemiology. https://link.springer.com/article/10.1007/s00127-019-01729-3
Gayer-Anderson, C., & Morgan, C. (2013). Social networks, support and early psychosis: A systematic review. Epidemiology and Psychiatric Sciences. https://www.cambridge.org/core/journals/epidemiology-and-psychiatric-sciences/article/social-networks-support-and-early-psychosis-a-systematic-review/72C7A17F329CEE1F5A438E4D31A3E0A4
Lejeune, A., Robaglia, B. M., Walter, M., Berna, F., & Brunelin, J. (2022). Use of social media data to diagnose and monitor psychotic disorders: Systematic review. Journal of Medical Internet Research. https://www.jmir.org/2022/9/e36986/
Benoit, J., Onyeaka, H., Keshavan, M., & Torous, J. (2020). Systematic review of digital phenotyping and machine learning in psychosis spectrum illnesses. Harvard Review of Psychiatry. https://journals.lww.com/hrpjournal/fulltext/2020/09000/Systematic_Review_of_Digital_Phenotyping_and.2.aspx
Henson, P., Wisniewski, H., Stromeyer, C., Vaidyam, A., & Torous, J. (2020). Digital health around clinical high risk and first-episode psychosis. Current Psychiatry Reports. https://link.springer.com/article/10.1007/s11920-020-01184-x
Higgins, O., Short, B. L., Chalup, S. K., et al. (2023). Interpretations of innovation: The role of technology in explanation seeking related to psychosis. Issues in Mental Health Nursing / Psychiatric Care. https://onlinelibrary.wiley.com/doi/abs/10.1155/2023/4464934
Hudon, A., & Stip, E. (2025). Delusional experiences emerging from AI chatbot interactions or AI Psychosis. JMIR Mental Health. https://mental.jmir.org/2025/1/e85799/
Pierre, J. M., Gaeta, B., & Raghavan, G. (2025). You're Not Crazy: A case of new-onset AI-associated psychosis. Innovations in Clinical Neuroscience. https://pmc.ncbi.nlm.nih.gov/articles/PMC12863933/
Ostergaard, S. D. (2023). Will generative artificial intelligence chatbots generate delusions in individuals prone to psychosis? Schizophrenia Bulletin. https://pmc.ncbi.nlm.nih.gov/articles/PMC10686326/
