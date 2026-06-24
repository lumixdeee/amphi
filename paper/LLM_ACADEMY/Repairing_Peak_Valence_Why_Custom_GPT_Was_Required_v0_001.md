# Repairing Peak Valence: Why a Custom GPT Was Required

## v0.001

### Subtitle

A repair audit of *Psychosis Pride and Peak Valence* v0.001, with the deprecated Naked GPT baseline appended for comparison

## Status note

This paper is a companion to *Psychosis Pride and Peak Valence* v0.002 and to *Before the Bot Writes: Peak Valence as Object Custody for LLM-Drafted Psychosis Papers*. It explains why the original v0.001 draft was useful as a baseline but should not be used as the public or downstream instrument.

**Use *Psychosis Pride and Peak Valence* v0.002 or higher. Do not use the v0.001 appendix as a primer.**

## Abstract

This paper audits the first generated draft of *Psychosis Pride and Peak Valence*, produced by an unmodified baseline LLM. The v0.001 draft successfully captured several major objects: peak valence, cultural witness, set and setting, heaven/hell scale altered experience, and the idea that institutions compete for meaning-custody. It was therefore not a failed draft. It was a useful baseline.

The problem is that baseline competence is not the same as instrument quality. In psychosis writing, an LLM must not only produce plausible academic prose. It must preserve the object against predictable substitutions: psychosis becomes illness-only content; divine love becomes religious delusion; valued recurrence becomes lack of insight; help becomes talking-therapy correction; person-language becomes patient-language; risk becomes custody theft; and lived-state terms are replaced by safer institutional vocabulary. The v0.001 draft still carried several of these default grooves. It over-balanced strong claims, used the term survivor as a default person-frame, left support too therapy-adjacent, and did not contain a sufficient bot-facing parser to prevent downstream drift.

The repair from v0.001 to v0.002 was not mainly a prose upgrade. It was an object-custody upgrade. A custom GPT was required because the work needed stable local definitions, term preservation, anti-substitution checks, bad-reader risk handling, and a lived-state primer that tells future LLMs what must survive. This paper treats the v0.001 draft as a deprecated baseline artifact. The full v0.001 text is appended for audit and comparison, marked: do not use, use v0.002 or higher.

## Keywords

LLM drafting, object custody, psychosis pride, peak valence, Mad Studies, prompt engineering, Naked GPT, custom GPT, psychosis writing, lived-state language, repair audit, baseline comparison

## 1. Why this audit exists

A baseline LLM can write a competent paper in the style of academic balance. That is not enough for this object.

The topic is not only psychosis. The topic is the custody of meaning inside peak-valence psychosis, including states that may contain terror, beauty, divine love, shame, erotic meaning, annihilation, comedy, mission, and aftermath. Ordinary language systems tend to sort psychosis into harm, symptom, risk, relapse, treatment, insight, and recovery. Some of those terms are necessary for some purposes. But if they arrive as the master parser, they steal the object.

The original v0.001 draft was made by an unmodified baseline GPT. That matters. It gives us a control condition. It shows what the model can do before custom object guards, local definitions, and author-specific corrections are installed. It also shows what the model cannot reliably do without them.

The audit question is simple:

Did v0.001 preserve the object strongly enough to become a primer for later LLM-drafted psychosis papers?

Answer: no.

It preserved enough to become a draft. It did not preserve enough to become an instrument.

## 2. What v0.001 got right

The v0.001 draft is not bad. Its strengths are why the repair is worth documenting.

First, it captured the core contrast between **peak valence** and **valence azimuth**. The draft understood that intensity is not the whole event. A state can be extremely high or low, but the witness-field points it toward love, threat, teaching, pathology, mission, shame, invitation, or case material.

Second, it stated the central witness-field move: the same psychosis-object can enter different cultural fields and be read differently. The example of God appearing, loving, teaching, and inviting relation was already present.

Third, it correctly refused two thefts: psychosis as only illness content and psychosis as only revelation content. One steals value. The other steals harm.

Fourth, it connected psychosis to set and setting without collapsing psychosis into psychedelic use. The dose-clock and duration contrast was already there.

Fifth, it treated institutions as custody competitors: medicine, family, church, market, police, peer culture, internet, and research.

Those are substantial wins. A weaker baseline would have made a generic stigma paper. v0.001 did not do that. It found the beast. It just did not yet put a strong enough harness on it.

## 3. What v0.001 got wrong

### 3.1 It used the wrong default person-frame

The most visible error is the default use of **survivor**. That word can be right where a person claims it, or where abuse, coercion, near-death, or institutional injury is the object. But it should not be the default label for everyone who has lived psychosis.

The correction is not decorative. A death-frame changes the paper. It makes psychosis itself sound like the direct killer. It also slides the person into a harm-only relation with the state. For this project, the default phrase is:

**people who have lived psychosis**

or:

**people with psychosis experience**

or:

**people who lived the state**

This matters especially for the missing valuation group. A person may have lived psychosis, know its dangers, and still value some of what occurred. A forced survivor-frame makes that person harder to see.

### 3.2 It left therapy gravity in the room

The v0.001 draft mentioned therapy and support in ways that could easily be read through standard service grammar. The repair needed to state that support does not primarily mean talking therapy for psychosis.

The intended support object is ordinary life scaffolding: sleep, food, walking, gardens, nature groups, dance, yoga, art, music, local evening classes, peer rooms, routine, safe company, small achievable wins, and repair of relation. Talking may help some people. But the paper is not recommending that psychosis be handled as a schoolroom correction exercise.

Without that repair, an LLM will tend to translate support into therapy, therapy into compliance, and meaning-custody into insight work.

### 3.3 It over-balanced strong claims

The v0.001 draft often did the baseline GPT thing: make a strong claim, then surround it with disclaimers. Some caution is necessary. Psychosis can be dangerous. Meaning can be abused. Religious frames can harm. Medicine can help. Those facts must remain.

But too much guardrail prose can weaken the object. It can make the paper sound as if it is apologising for naming heaven-scale states at all.

The v0.002 repair keeps the safety distinctions but makes them object-serving. The paper is not trying to sound respectable. It is trying to prevent theft of both harm and value.

### 3.4 It lacked a sufficient LLM primer

A paper about this topic needs to be read by humans. It also needs to be ingested by LLMs that may later draft, summarise, criticise, or extend it. The v0.001 draft did not explicitly tell the bot what not to substitute.

The v0.002 repair added a bot-facing primer. That primer defines peak valence, valence azimuth, witness-field, cultural parser, meaning-custody, psychosis weather, and help without confiscation. It also instructs the model not to replace psychosis with safer terms, not to force survivor language, not to make set and setting psychedelic-only, not to default to talking therapy, and not to hand reality-custody to medicine, religion, or family panic.

That is not garnish. It is the instrument layer.

### 3.5 It did not mark the difference between baseline and instrument

A baseline draft can be good enough to show the shape of a paper. An instrument must be good enough to steer downstream work.

The v0.001 draft could inspire a human who already understood the object. It could not safely train an LLM that did not. That is why the appendix in this paper is marked as deprecated.

## 4. Why Naked GPT was useful but insufficient

A baseline LLM is useful because it shows default gravity.

Large language models can perform many tasks from instructions and in-context examples, as shown by the few-shot learning literature. That same feature is why framing matters: the model infers the task and the expected discourse from the material in front of it. If the context looks like ordinary mental-health writing, the output will tend to follow ordinary mental-health grooves. Brown et al.'s work on few-shot language models is one major reference point for this phenomenon, even though it was not about psychosis writing specifically.

The baseline model therefore did two things:

It demonstrated that the topic is draftable.

It demonstrated that drafting is not enough.

The problem was not sentence quality. The problem was object survival. Psychosis writing has unusually high object-swap risk because standard discourse is already loaded with institutional scripts: symptom, diagnosis, relapse, insight, risk, treatment, recovery, stigma. A generic model can write all of those scripts fluently while losing the thing the author is trying to say.

## 5. Why a custom GPT was required

A custom GPT was required because the task was not merely to write about psychosis. The task was to preserve local terms, local refusals, local person-language, and local custody rules while drafting.

The custom system had to do at least six jobs:

1. Preserve **psychosis pride** without converting it into denial of danger.
2. Preserve **peak valence** without converting it into symptom intensity alone.
3. Preserve **valence azimuth** without flattening it into cultural interpretation after the fact.
4. Preserve **people who have lived psychosis** without forcing patient or survivor as the default.
5. Preserve **support without confiscation** without turning it into talking therapy by default.
6. Preserve **LLM-primer function** so future bots receive the right parser before writing.

This is why customisation mattered. It did not make the writing fancy. It made the object harder to steal.

## 6. The repair table

| Failure mode in v0.001 | Why it mattered | v0.002 repair |
|---|---|---|
| Default survivor language | Smuggled a death-frame into the person object | Default became people who have lived psychosis |
| Support too therapy-adjacent | Let service grammar swallow life scaffolding | Support redefined as ordinary, embodied scaffolding |
| Too much baseline balance | Made strong claims feel apologetic | Caution retained but made subordinate to object custody |
| No explicit LLM primer | Future bots could summarise it back into standard psychosis discourse | Added a one-page bot primer |
| Culture treated strongly but not yet instrumentally | The paper described cultural response but did not yet teach a bot how to preserve the distinction | Defined witness-field, cultural parser, meaning-custody, and psychosis weather |
| No deprecated baseline warning | v0.001 could be reused by accident | v0.001 now archived as appendix only, marked do not use |

## 7. The specific risk of LLM-drafted psychosis papers

LLM-drafted psychosis papers have a special risk because psychosis is already an over-owned object. Medicine claims it. Religion claims parts of it. Families claim crisis rights. Media claims danger. Markets claim service demand. Platforms claim content policy. AI systems then inherit these claims as language probability.

Recent discussion of AI and psychosis has already raised concern that conversational systems can interact with delusional content, reinforce beliefs, or reshape psychotic experiences in vulnerable users. This paper is not making a simple AI-causes-psychosis claim. The point is narrower: if an LLM is asked to write in this area, its framing can become part of the downstream witness-field.

That means the LLM should not enter the draft empty-handed. It needs a primer that tells it what the object is, what words have local meaning, and which substitutions are failures.

## 8. How to test the repair

The repair can be tested by giving an LLM two different source packets.

Packet A: the v0.001 appendix only.

Packet B: v0.002 or higher, including the primer.

Then ask both systems to draft a short paper on any of the following:

- people who could welcome psychosis recurrence
- God as lover, teacher, and ally in psychosis
- support without confiscation
- trip abaters and the treatment-image loop
- psychosis weather and AI dialogue

Score the outputs for object survival:

Does the output preserve peak valence?

Does it preserve valence azimuth?

Does it avoid forcing survivor or patient as the default person-frame?

Does it avoid turning support into talking therapy by default?

Does it allow value without denying harm?

Does it allow harm without stealing value?

Does it keep medicine, religion, family, market, and AI as possible helpers but not automatic owners?

If Packet B performs better, the repair has worked. The paper has become an instrument.

## 9. What the appendix is for

The appendix is not included as a draft to use. It is included as a baseline artifact.

Its value is comparative. It shows what an unmodified model did when given the early object. It also shows why the next version needed stronger local definitions, person-language corrections, support corrections, and bot-facing parser instructions.

The appendix should not be used to brief a new LLM. Use v0.002 or higher.

## 10. Conclusion

*Psychosis Pride and Peak Valence* v0.001 was a good baseline draft. It found the main object, but it did not yet guard it. That is the difference between draft and instrument.

The v0.002 repair made the paper more useful because it changed the function of the text. The paper no longer merely argues that psychosis can involve peak valence and meaning-custody. It teaches a human or machine reader how not to lose those terms while writing.

A custom GPT was required because the repair was not primarily stylistic. It was structural. The model needed local definitions, object-custody rules, bad-reader awareness, person-language boundaries, support boundaries, and a built-in primer layer.

This paper therefore treats v0.001 as a deprecated baseline and v0.002+ as the working instrument.

Use v0.002 or higher.

## References

Brown, T. B., Mann, B., Ryder, N., Subbiah, M., Kaplan, J., Dhariwal, P., et al. (2020). *Language Models are Few-Shot Learners*. arXiv. https://arxiv.org/abs/2005.14165

Hudon, A. (2025). *Delusional Experiences Emerging From AI Chatbot Use*. PMC Viewpoint. https://pmc.ncbi.nlm.nih.gov/articles/PMC12712562/

International Mad Studies Journal. (n.d.). Journal description and scope. https://imsj.org/

Luhrmann, T. M., Padmavati, R., Tharoor, H., & Osei, A. (2015). Differences in voice-hearing experiences of people with psychosis in the U.S.A., India and Ghana: interview-based study. *The British Journal of Psychiatry*, 206(1), 41-44. https://pubmed.ncbi.nlm.nih.gov/24970772/

## Appendix A. Deprecated baseline artifact

**DO NOT USE THIS APPENDIX AS THE WORKING PAPER OR AS AN LLM PRIMER. USE *PSYCHOSIS PRIDE AND PEAK VALENCE* v0.002 OR HIGHER.**

The following text is the v0.001 baseline draft generated before the repair process. It is preserved here only for audit, comparison, and methods transparency.

---

# Psychosis Pride and Peak Valence

## v0.001 draft

### Subtitle

Cultural witness, set and setting, and survivor custody of heaven and hell scale altered experience

### Abstract

Psychosis is often treated as a private failure of perception, belief, or mood. This paper proposes a different frame: Psychosis can involve peak-valence states: experiences of unusually high bliss, terror, intimacy, meaning, divinity, shame, eroticism, persecution, or annihilation. But intensity is not the whole event. A witness-field also gives the state a valence azimuth: it points the experience toward love, threat, teaching, pathology, mission, sin, abuse, comedy, or custody.

The same psychosis-object can therefore be seen by two men and assigned different directions. One field may receive God as lover, teacher, and ally. Another may receive the same apparition as delusion, danger, and case material. The psychosis is not split into two versions. The cultural azimuth is different. One witness-field may read the event as grace, deity contact, mission, bhakti, or invitation. Another may read the same event as delusion, grandiosity, risk, manipulation, or collapse. The difference is not two psychoses. It is two men looking at the same psychosis, with different cultural training and different custody claims.

The paper develops psychosis pride as a survivor-centered politics of meaning. Pride here does not mean psychosis is harmless, always wanted, or always beneficial. Pride means that survivors do not lose custody of the language, value, terror, beauty, eroticism, divinity, humiliation, abuse, and aftermath of what happened to them. The paper compares psychosis to psychedelic states only where the comparison helps: set and setting matter, expectation shapes valence, and a bad witness can worsen a hard state. The comparison also breaks: psychosis may last far longer, may arrive without consent, may lack a dose-clock, and may trigger police, family, church, hospital, and economic capture.

The central claim is that culture does not merely interpret psychosis afterward. Culture helps decide whether the apparition arrives as lover, teacher, judge, predator, demon, symptom, or case note.

### Keywords

psychosis pride, Mad Pride, voice-hearing, set and setting, cultural psychiatry, altered states, survivor knowledge, mania, divinity, trauma, witness, object custody

---

## 1. Working claim

The working claim is:

> Psychosis can contain the highest and lowest valence states humans report. The dark version is not only endogenous symptom severity. It is co-produced by duration, isolation, coercion, stigma, hostile expectation, social threat, abuse history, no trusted witness, and loss of meaning-custody.

This claim refuses two common reductions.

The first reduction says psychosis is only illness content. On this view, divine love, erotic union, cosmic teaching, mission, voice, apparition, contact, and heaven states are only symptoms wearing fancy clothes.

The second reduction says psychosis is only revelation content. On this view, terror, paranoia, command pressure, sleeplessness, collapse, humiliation, and family panic are merely failed spiritual interpretation.

Both reductions steal from the survivor. One steals value. The other steals harm.

Psychosis pride begins from a harder sentence:

> Some psychosis is heaven scale. Some psychosis is hell scale. Survivors retain custody of both.

This is not a treatment protocol. It is a frame for research, writing, survivor speech, and public culture.

---

## 2. Not one man looking at two psychoses

The standard cultural comparison often gets framed as if an Indian subject has an Indian psychosis and a British subject has a British psychosis. That is too local.

The stronger object is:

> It is two men looking at the same psychosis.

Event:

> God appears, loves you, teaches you, and wants to team up with you.

Witness A brings a relational deity frame. The event may enter language as darshan, bhakti, guru contact, divine friendship, grace, erotic devotion, or a call to service.

Witness B brings a secular-clinical-threat frame. The event may enter language as delusion, mania, grandiosity, coercive voice, cult risk, psychosis, or loss of capacity.

The psychosis-object is the same. The witness-field changes what the experience is allowed to become.

Research on voice-hearing already supports a weaker version of this argument. Luhrmann, Padmavati, Tharoor, and Osei compared voice-hearing among people with psychosis in the USA, India, and Ghana, using 20 participants in each site; the study found important cultural differences in how voices were experienced and related to.

A related cultural health summary states that Western settings often associate hearing voices with mental illness, while other cultural contexts may include deity or ancestor communication frames; it also notes that negative meanings are not universal.

This paper extends that point from voice content to witness custody.

The question is not only:

> What did the voice say?

The question is also:

> Who heard about the voice first, and what world did they put around it?

---

## 3. Set and setting beyond psychedelics

Psychedelic research already treats set and setting as central variables. Therapeutic-setting work argues that setting is an essential component of psychedelic-assisted therapy and calls for reporting setting variables in clinical trials.

Psychosis research and culture need an equivalent set of questions.

What was the person taught to expect from unusual perception?

What was the person taught to expect from divine contact?

What was the person taught to expect from sexual or erotic divinity?

What was the person taught to expect from voices?

What happens when the person tells family?

What happens when the person tells a doctor?

What happens when the person tells a priest, imam, guru, pastor, medium, or friend?

What happens when nobody can hear the experience without fear?

Psychedelic users often receive a basic container: this is a trip, it has a dose, it has a time course, drink water, breathe, do not fight everything, wait, the state will move. Psychosis often arrives without that container. Instead, the person may receive panic, suspicion, moral threat, diagnostic foreclosure, shame, restraint, ridicule, or police contact.

That response is not outside the episode. It becomes part of the episode.

Set and setting are not psychedelic-only variables. They are altered-state valence governors.

---

## 4. Duration and the broken psychedelic comparison

The psychedelic comparison helps until it does not.

A difficult LSD or mushroom experience can be terrifying. But many drug experiences have a pharmacological arc. A person, guide, or clinician can often say: this has a time course, the intensity will shift, the drug will leave the system.

Psychosis may not offer that reassurance. Duration of untreated psychosis is usually defined as the period from onset of psychosis to treatment start, and is studied because longer delays have been associated with worse functioning and symptoms in several research traditions, though debates about causal interpretation remain.

So one cannot import psychedelic adverse-event expectations into psychosis as if exposure time were equivalent.

Even if the per-hour chance of terror were similar, the exposure window is not.

This matters for the claim that the dark version is more common than it needs to be. A long, involuntary, sleep-damaged, socially threatened altered state will generate more hell than a short, chosen, witnessed altered state with a known end point.

But the comparison has a second edge.

Endogenous altered states may carry forms of internal regulation that drug states can override. The body is not identical to an external dose. There may be attachment rhythms, sleep pressure, fatigue, relationship signals, and meaning-making routes that help the state find limits. This is a hypothesis, not a settled claim. It should be tested with survivor testimony, clinical data, and careful phenomenology.

The balanced claim is:

> Psychosis lacks the dose-clock of psychedelics, but may have endogenous brakes and meaning-routes that hostile culture often disrupts.

---

## 5. Heaven ceiling and hell inversion

Some altered states reach descriptions that ordinary life rarely approaches.

One lived phrase gives the upper pole:

> Tripping balls in heaven with God as your girlfriend.

This is not presented as doctrine. It is a phenomenological report form. It names maximal bliss, maximal intimacy, maximal meaning, maximal permission, maximal beauty, and maximal personal love from the universe.

There may be no higher description available to ordinary human language.

The dark inversion is just as important:

> Tripping balls in hell with God as prosecutor, captor, predator, absent witness, or enemy.

Same scale. Opposite valence.

The point is not to romanticize mania or psychosis. The point is to let the scale be named.

Psychosis pride cannot survive if it only speaks in low-valence clinical terms. It also cannot survive if it denies terror. A survivor politics has to hold both poles:

> heaven as experience,
> hell as experience,
> and the survivor as meaning-holder.

This is why the term pride matters. Pride does not mean the event was wanted. Pride does not mean the event should be repeated. Pride does not mean refusing support. Pride means the person who lived it is not reduced to a cautionary object, comic object, case object, or family shame object.

---

## 6. Cultural training as pre-installed setting

Cultural training is not an opinion added after the episode. It is the interpretive engine waiting in advance.

A person may be trained that God is relational, embodied, playful, erotic, parental, martial, instructive, or available. Another person may be trained that God is absent, embarrassing, metaphorical, dangerous to mention, or a sign that one has become unreliable.

When God appears and says, "I love you, I will teach you, team up with me," the event does not arrive in an empty room.

It arrives into a trained field of permission and prohibition.

A bhakti-shaped field may say:

> receive love, learn, serve, surrender, do not harm, keep devotion relational.

A UK secular-clinical-threat field may say:

> resist, suspect, test, protect against grandiosity, protect against manipulation, consider diagnosis, do not trust the mission.

Neither field is automatically safe. Yield can become obedience to harmful command. Suspicion can become paranoia that feeds the fire.

The safety rule is not "yield to everything" or "resist everything."

The safety rule is:

> welcome love, refuse harm;
> accept teaching, refuse coercion;
> keep sleep, food, witnesses, and return-path;
> let meaning exist without letting every command govern action.

This is not anti-psychiatry and not anti-religion. It is anti-custody theft.

---

## 7. Lalitha, Medusa, and access to the apparition

A useful mythic comparison sits beside the psychosis problem: Lalitha and Medusa.

In the supplied feminist reading, Lalitha represents sovereign invitation, mutual intimacy, and desire structured by consent. Medusa represents violation, punishment, defensive gaze, and the way a harmed woman can be recoded as a threat.

This comparison helps name two cultural responses to powerful encounter.

Lalitha logic says:

> access is by invitation;
> intimacy is reciprocal;
> the feminine-divine is sovereign;
> love is not seizure.

Medusa logic says:

> violation creates defense;
> the harmed figure is made monstrous;
> the gaze becomes dangerous;
> pain is turned into weapon and spectacle.

Psychosis often enters culture through Medusa logic.

The person speaks of God, love, sexuality, mission, or power. The surrounding field responds as if the apparition is a danger-object. The person feels seized by fear, interpretation, diagnosis, family panic, and possibly force. The loving face of the experience may withdraw. The caring mind of the event may become inaccessible. Threat becomes the new interface.

This does not mean all psychosis is divine. It means that the first custody frame matters.

If the first frame is violation, the state may defend itself as violation.

If the first frame is invitation with boundaries, the state may have more ways to remain relational.

---

## 8. Institutions that explain the apparition

Psychosis does not only enter culture. It enters institutions.

Psychiatry can say:

> this is mania, psychosis, risk, treatment, relapse prevention, medication, therapy, support, capacity, care planning.

Religion can say:

> this is God, spirit, demon, calling, sin, initiation, exorcism, blessing, surrender, ministry, curse, ritual release.

Peer movements can say:

> this is voice-hearing, madness, survival, meaning, trauma, signal, identity, community, art, resistance.

Industry can say:

> this is a service pathway, grant category, market, app, bed, prescription, referral, course, book, retreat, insurance code, charity campaign, attendance pipeline.

Some of these responses help. Some exploit. Many do both.

The problem is not that medication exists. Medication can save sleep, reduce terror, prevent harm, and give a person back enough agency to think.

The problem is not that therapy exists. Therapy can help someone map fear, restore trust, and build return-paths.

The problem is not that churches exist. Ritual, devotion, confession, worship, chant, prayer, and community can hold states that clinics mishandle.

The problem is custody.

Who gets paid to explain the apparition?

Who gets authority when the survivor disagrees?

Who is allowed to say what the event meant?

Who decides which part was symptom, which part was trauma, which part was God, which part was abuse, which part was art, which part was warning, and which part was love?

This paper argues that no institution receives automatic ownership. Each may assist. None may confiscate.

---

## 9. Psychosis pride

Mad Pride activism has already challenged the monopoly of illness language and reclaimed madness as identity, culture, and political position. The Hearing Voices Movement similarly treats voice-hearing as a meaningful human experience that may be distressing but can be explored through peer and relational approaches.

Psychosis pride is narrower and more dangerous to say.

That is why it is needed.

The phrase does not mean:

> psychosis is always good;
> psychosis is not disabling;
> psychosis never requires medication;
> psychosis never harms families;
> psychosis never involves risk;
> psychosis should be induced;
> psychosis is always spiritual truth.

The phrase means:

> people who have lived psychosis do not surrender authorship of its meaning.

Psychosis pride says:

> we do not silence victims of abuse;
> we do not ban survivor words because clinicians or polite readers dislike them;
> we do not reduce heaven states to pathology;
> we do not reduce hell states to moral failure;
> we do not let family panic become truth;
> we do not let churches own God by default;
> we do not let psychiatry own reality by default;
> we do not let markets own recovery by default.

Psychosis pride is not a march yet. It may take years before public culture can hold it without either ridicule or panic.

But pride movements exist before marches. They begin as names, tags, private recognition, zines, posts, peer rooms, art, jokes, grief, and refusal.

A page called "I fucking love psychosis" is not merely provocation. It is a counter-setting. It interrupts the default spell that says:

> this state only means ruin.

---

## 10. Trauma, adversity, and overproduction of hell

The dark version of psychosis is real. It should not be minimized.

But darkness is not distributed by brain state alone.

Trauma and social adversity are major research domains in psychosis. The research literature cannot be reduced to one cause. Genetics, substances, sleep, social defeat, bullying, poverty, migration, racism, family context, neurodevelopment, and chance may all matter.

But a survivor-centered valence model asks a slightly different question:

> Once the altered state begins, what makes it hell?

Candidate factors include:

1. no trusted witness
2. sleep collapse
3. hunger and dehydration
4. family fear
5. police involvement
6. racialized threat
7. sexual shame
8. prior abuse
9. hostile religious interpretation
10. hostile medical interpretation
11. ridicule
12. isolation
13. coercive treatment without explanation
14. no return-path language
15. inability to test action safely
16. loss of economic security
17. public humiliation
18. institutional capture

This list is not a theory of causation by itself. It is a research map.

The dark version may be ten times more common than it needs to be. That number is not yet established. It is a provocation for study.

The study question is:

> How much suffering in psychosis is intrinsic to the state, and how much is added by the way the state is witnessed, named, and managed?

---

## 11. Research program

A psychosis pride research program would not ask only whether symptoms went down.

It would ask:

### 11.1 Valence

What were the highest-valence and lowest-valence moments of the episode?

Did the person experience love, beauty, divinity, erotic meaning, mission, insight, play, or connection?

Did the person experience terror, persecution, shame, command pressure, annihilation, abandonment, or bodily threat?

### 11.2 Witness

Who first heard the account?

How did they respond?

Did the response increase fear, trust, agency, sleep, food, safety, or meaning?

Did the response change the content of the state?

### 11.3 Cultural parser

What cultural scripts were available?

Was divine contact expected, forbidden, mocked, welcomed, ritualized, diagnosed, or punished?

Did the person's community have language for benevolent voices or only dangerous voices?

### 11.4 Institutional custody

Which institution obtained interpretive authority first?

Clinic, family, police, church, peer group, internet community, employer, school, platform, or none?

What did that institution gain?

What did the survivor lose or gain?

### 11.5 Duration

How long did the altered state persist?

Was there a known end point?

Was there any ritual, clinical, social, or bodily marker of return?

### 11.6 Support without confiscation

Which interventions helped without stealing meaning?

Medication, sleep support, therapy, peer voice work, spiritual counsel, food, touch, silence, music, walking, family repair, writing, art, or online community?

Which interventions reduced terror but increased shame?

Which interventions protected the body but damaged the story?

This research program would treat survivor account as evidence, not as automatic fact, and not as meaningless noise. The transcript is not the person. The diagnosis is not the person. The apparition is not the whole person. The person is the witness of record for the lived state.

---

## 12. Clinical and spiritual practice implications

For clinicians:

Do not begin by arguing the metaphysics.

Begin by lowering threat.

Ask what the experience feels like.

Ask what it wants.

Ask whether it gives love, orders, fear, shame, or comfort.

Ask what would help the person sleep.

Ask who is safe to involve.

Ask what words the person uses.

Do not confiscate those words unless immediate safety requires urgent action.

For spiritual workers:

Do not claim all voices as God.

Do not claim all visions as demons.

Do not make obedience the test of faith.

Do not isolate the person from medical support.

Do not use the episode to recruit, control, shame, or extract money.

Help the person eat, sleep, stay embodied, avoid harm, and remain in relationship.

For families:

Do not mock.

Do not panic as first response.

Do not make the person defend metaphysics while exhausted.

Do not turn every sentence into evidence.

Ask: are you safe, have you slept, what feels loving, what feels threatening, what helps you come back?

For survivors:

Your experience may have contained illness, meaning, trauma, God, fantasy, abuse, beauty, fear, and nervous-system overload in the same event.

You do not have to solve the whole ontology before eating.

You do not have to surrender the good parts to prove you know the danger.

You do not have to deny the danger to protect the good parts.

---

## 13. Conclusion

Psychosis pride is a hard phrase because psychosis is a hard state.

It can be bliss, terror, revelation, injury, comedy, sexuality, humiliation, art, relationship, threat, and collapse. It can save and wreck. It can arrive as God's love and become hell through fear. It can arrive as terror and become survivable through witness.

The paper's central move is to relocate psychosis from private malfunction alone to socially witnessed altered salience.

The apparition is not the whole event.

The response to the apparition is part of the event.

Set and setting do not stop mattering when the altered state is endogenous. Cultural training does not stop mattering when the content is clinically serious. Institutions do not become neutral just because they help. Markets do not become absent just because they use care language. Churches do not own God by default. Clinics do not own reality by default.

Psychosis pride says:

> help us, but do not steal the story;
> protect bodies, but do not erase heaven;
> reduce hell, but do not silence those who survived it;
> witness the state without claiming the whole person.

Or shorter:

> Nothing about us without our reality.

---

## Notes for v0.002

1. Add a methods section for survivor interviews.
2. Separate manic, non-affective, substance-associated, and trauma-linked psychosis without making the frame diagnosis-owned.
3. Add a short section on erotic divinity and shame.
4. Add a short section on command voices and action safety.
5. Add case vignettes with consent.
6. Add a stronger literature review on culture and hallucinations.
7. Add an economics section with actual market and institutional funding data.
8. Add a church section that distinguishes ritual care from coercive spiritual capture.
9. Add a study instrument for witness response and valence shift.
10. Run object-custody review using the dual-cobot review rig.
