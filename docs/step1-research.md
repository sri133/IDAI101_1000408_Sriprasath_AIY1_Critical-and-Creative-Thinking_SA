# MindPatch – Step 1: Empathize & Research Digital Wellness

Sri Prasath.P | Registration No. 1000408 | CRS: Artificial Intelligence | Critical and Creative Thinking | Jain Vidyalaya IB World School

*Summative Assessment, Scenario 2 – MindPatch: A Digital Detox and Wellness Planner App Prototype*

## 1. The problem space

Students now study, socialise and relax on the same few devices, so the line between “on” and “off” disappears. The research below links heavy, late-night and problematic phone use with stress, poorer sleep and lower wellbeing among students and young people, although the evidence is not simple (see 2.3). The brief names digital fatigue, academic burnout and screen-time stress as the issues MindPatch must address.

**Approach.** This step combines secondary research (journal articles and WHO/HBSC data), a review of three existing wellness apps (Headspace, Forest, Reflectly), behaviour-change theory, two personas with empathy maps, and a mood board. The personas are fictional composites built from the research, not interview subjects.

## 2. Secondary research

### 2.1 Key studies

| Source | What it found | What it means for MindPatch |
|---|---|---|
| Alkaabba et al. (2025), 102 students at a Saudi university, *Cureus* | Linked excessive screen time, especially in the evening, with high levels of anxiety, depression and stress symptoms. Screen use for more than an hour before bed went with difficulty relaxing, and daily use above about four hours went with poorer mental-health indicators. | Time of day matters, so the AI planner needs a time-of-day input and evening wind-down suggestions. |
| Kaewpradit et al. (2025), 446 students at a Thai university, *Frontiers in Psychiatry* | Found high rates of excessive screen time (use beyond recommended limits), especially on smartphones and tablets, linked to worse mental health, sleep and academic performance. Younger and health-science students were more prone. Recommends interventions that build self-awareness, regulate screen time and improve time management. | Supports a dashboard that builds self-awareness, plus planning features. |
| Bradley & Howard (2023), 187 undergraduates over 12 weeks, *Clinical Psychological Science* | Using device-logged screen time, heavier phone use in a given week did not predict end-of-week mood, and stress was not tied to heavier use. Students who generally used their phones more did report slightly worse mood. The authors conclude that hours of use alone say little about wellbeing. | Hours are a weak signal on their own, so MindPatch combines mood, timing and routine and compares users with their own baseline instead of one universal limit. |
| Rajput et al. (2026), 96 medical students, University of East Sarajevo, *Biomedicinska istraživanja* | Median daily screen time was about five hours. Late-night use was an independent predictor of sleep disturbances, while total screen time was not significant after adjustment. | Weight late-night use more heavily than raw hours in the planner logic. |
| Miranda-Soberón et al. (2026), Peruvian health-programme students, *Comunicar* | Using a phone more than eight hours a day, together with depression or anxiety symptoms, raised the risk of problematic use. | Mood and screen time interact, so use both as planner inputs. |
| Boniel-Nissim et al. (2024), WHO Europe / HBSC Volume 6: almost 280,000 adolescents aged 11, 13 and 15, 44 countries and regions | Problematic social-media use rose from 7% (2018) to 11% (2022), was more common among girls, and was associated with lower wellbeing, poorer school outcomes and more sleep problems. Heavy but non-problematic users reported stronger peer support. | Heavy use is not automatically harmful. MindPatch should promote balance, not abstinence. |
| Jacob et al. (2022), APHA conference abstract, US college students surveyed in 2019 | Daily subjective screen time was associated with co-occurring mental-health symptoms, and social support weakened the relationship. The authors suggest support rather than blanket restriction. | Include connection-friendly suggestions (e.g. call a friend), not just blocking. |
| Eske (2023), University of Twente bachelor's thesis, 38 participants | Over two weeks, higher daily screen time went with lower positive mood, suggesting mood may influence phone behaviour. Small sample. | Supporting evidence for logging mood and screen time together. |

### 2.2 Five takeaways that shape the design

1. **Timing matters as much as total hours.** Evening and late-night use stands out across studies.
2. **Hours alone are a weak signal.** Several studies link screen time with mood and mental-health symptoms, but the 12-week Carleton study found no week-to-week link. So the planner reads mood, timing and routine together, not hours alone.
3. **Self-awareness comes first.** Researchers recommend building awareness before regulation, which justifies the dashboard and mood log.
4. **Support and balance beat bans.** Social connection can buffer the effects of heavy use, so plans should protect healthy screen time, not just cut it.
5. **Personalise to the person.** Baselines and routines differ, so the AI should adapt to each user's patterns over time.

### 2.3 Limits of the evidence

- Most findings are correlational, so they cannot show that screens cause distress. Results are also mixed: the Carleton study found no week-to-week link between phone use and mood, and the Sarajevo study found total hours mattered less than timing.
- Samples differ: health-science students in Saudi Arabia, Peru and Bosnia, Thai students, adolescents aged 11–15 in HBSC, and one small thesis. Results may not transfer to every student.
- Several studies rely on self-reported screen time.
- **Design response:** MindPatch makes soft, optional suggestions, does not diagnose, and presents itself as wellbeing support rather than treatment.

## 3. Existing app analysis

| App | Core features | Engagement strategy | Limitations |
|---|---|---|---|
| **Headspace** | Guided meditations from a few minutes up to about half an hour, sleep content, and the Ebb AI companion (launched October 2024 for US consumer subscribers) that uses motivational interviewing to recommend content. | Personalised recommendations based on mood and goals, reminders, progress and streak tracking. | Full library and Ebb sit behind a subscription. The structured, goal-oriented style can feel rigid to some. Content-led: the sources reviewed mention no screen-time input. |
| **Forest** | Focus timer (10–120 minutes). A virtual tree grows during a session and withers if you leave the app. Coins unlock tree types or fund real tree planting. | Visual growth metaphor, loss aversion, a collection that becomes a forest, group sessions. | Centred on focus sessions and does not use mood. Reviews note group pressure can cause anxiety, and it is a soft nudge rather than a hard lock. |
| **Reflectly** | Mood check-ins (emoji), journaling with AI-generated prompts in a CBT and positive-psychology style, voice notes, photos, mood statistics over time. | Calm, uncluttered design and daily prompts that lower the barrier to journaling. | Lacks goal tracking. Full prompt library and insights need premium. Some reviewers find the personalisation shallow. No link to screen-time data. |

**The gap.** In the reviews consulted, none of the three connects mood, screen-time data and the user's schedule to produce a detox plan that explains itself. Headspace offers content, Forest offers focus sessions, Reflectly offers reflection. MindPatch can combine them in one calm app and show *why* each suggestion appears.

**What to borrow, and what to avoid.** Borrow Forest's growth metaphor, Reflectly's quick emoji mood input and uncluttered look, and Headspace's short sessions. Avoid punishment and guilt mechanics.

## 4. Behaviour-change principles

- **Nudge theory** (Thaler & Sunstein, 2008): small design choices steer behaviour while keeping the user free to choose.
- **Fogg Behavior Model, B = MAP** (Fogg): a behaviour happens when motivation, ability and a prompt come together at the same moment. Making the action easier is usually more reliable than boosting motivation. Prompts come in three types: *spark* (high ability, low motivation), *facilitator* (high motivation, low ability) and *signal* (both high).
- **Habit loop** (Duhigg, 2012): cue, then routine, then reward.

| Principle | How MindPatch applies it |
|---|---|
| Nudge | Suggestions are offered, never forced, with ‘Not now’ and ‘Snooze’. Default breaks are small (5 to 20 minutes). |
| Spark prompt | A warm message tied to a motivator, e.g. ‘Your 4-day streak is waiting’. |
| Facilitator prompt | One-tap ‘Start a 5-minute breathing break’. |
| Signal prompt | A well-timed notification such as ‘Take a tech-free walk’ after a long screen block. |
| Habit loop | Cue (evening reminder), routine (log mood, short gratitude entry), reward (streak, badge, calm visual). |
| Tiny steps | Every task is short, so low-energy days still work. |

**Ethical guardrails.** Notifications are opt-in and adjustable. Every AI suggestion shows its reason (transparency). Mood and journal entries are treated as sensitive: minimal data, user control, private by default. No guilt-based mechanics. MindPatch is not a medical tool, so persistently low mood triggers a gentle ‘talk to someone you trust’ prompt, similar to how Headspace's Ebb can point users to crisis support.

## 5. Personas

*Fictional composites informed by the research above.*

### Persona 1: Aarav, 17, final-year school student

- **Context:** Heavy exam-year workload, studies with his phone nearby.
- **Behaviour:** Scrolls videos late at night after studying, uses his phone in bed, checks messages first thing in the morning.
- **Goals:** Fall asleep earlier and finish study blocks without drifting to his phone.
- **Frustrations:** Knows he should cut down but is too tired to fight the urge by evening. Blockers feel punishing and leave him guilty.
- **Needs:** Low-effort, non-judgemental evening nudges, and a way to see how late scrolling affects the next day's mood.
- **Fogg profile:** High ability, low motivation in the evening, so *spark* prompts.
- **Illustrative quote:** “I'm not addicted, I'm just tired, and scrolling is the easiest thing to do.”

### Persona 2: Meera, 20, second-year university student with a part-time job

- **Context:** Lectures, assignments, a part-time job and busy group chats. Uses social media for both comfort and connection.
- **Behaviour:** Checks her weekly screen-time summary. Has tried a focus timer and a journaling app but dropped both after a few weeks.
- **Goals:** Feel less overwhelmed, stay in touch with friends without constant scrolling, and build a routine that lasts.
- **Frustrations:** Too many separate apps, generic advice that ignores her timetable, and guilt after ‘bad’ days.
- **Needs:** One calm app, plans that fit her schedule, and streaks that forgive missed days.
- **Fogg profile:** High motivation, low ability on busy days, so *facilitator* prompts.
- **Illustrative quote:** “I know what I should do. I just don't have the energy to plan it.”

## 6. Empathy maps

### Aarav

| Says | Thinks | Does | Feels |
|---|---|---|---|
| “Just five more minutes.” “I'll sleep early tomorrow.” | “Everyone else is online.” “I'm wasting time and I'll pay for it tomorrow.” | Scrolls after studying, uses his phone in bed, checks notifications mid-study. | Tired, guilty, restless, anxious about exams. |

**Pains:** Late-night scrolling, poor sleep, guilt-based tools that feel punishing.
**Gains:** Falling asleep earlier, a clear head in the morning, feeling in control.

### Meera

| Says | Thinks | Does | Feels |
|---|---|---|---|
| “I need to cut down.” “I don't have time to set this up.” | “Maybe a new app will fix it.” “Missing a day means I've failed.” | Jumps between apps, checks screen-time summaries, abandons trackers after missed days. | Overwhelmed, stretched, guilty after slips, hopeful with new routines. |

**Pains:** Too many tools, generic advice, all-or-nothing streaks.
**Gains:** One simple routine, plans that fit her timetable, progress that forgives slips, time with friends without doom-scrolling.

## 7. Mood board

![MindPatch mood board](../images/mood-board.png)

*The board defines the look and feel of MindPatch before the wireframes and prototype.*

**Feeling keywords:** calm, safe, supported, light, gentle, balanced, hopeful. These come straight from the personas: Aarav needs low-effort, non-judgemental support, and Meera needs something simple that forgives missed days.

| Mood board element | Choice | Why |
|---|---|---|
| Colour | Blue and lavender as the calm base, pink for warmth (mood and gratitude), sage green for growth and goals met, amber for caution, coral red only for gentle alerts | The brief asks for a calm palette of soft hues. Strong red and green are kept to small accents, and always paired with an icon or label for colour-blind users. |
| Mood scale | Faces with a text label and a tint, never colour alone | The brief asks for emoji sliders or colour-coded mood entries, and accessibility requires more than colour. |
| Typography | Rounded, friendly sans-serif with generous sizes | Keeps cognitive load low and text readable. |
| Imagery | Soft sunrise, growing leaf, quiet night, gentle waves, open journal, breathing circle | Each image maps to a feature: fresh start (Home), growth (Habits, borrowed from Forest's growth idea without its guilt), wind-down (Wind-Down Mode), steady rhythm (Screen Time), reflection (Gratitude Journal), pause (Breathing Break). |
| UI feel | Rounded cards, pill buttons, line icons, lots of white space | Echoes Reflectly's uncluttered layout and Headspace's friendly shapes, and keeps tap targets large. |
| What to avoid | Harsh alert colours, dense dashboards, guilt wording, leaderboards | Research and personas show guilt-based tools push people away (see Forest's group-pressure limitation in Section 3). |

## 8. Define

**Point of view.** Students aged roughly 16 to 22 who feel drained by constant connectivity need a gentle, non-judgemental way to see how their mood and screen habits connect, and to act on it in small steps, because motivation is least reliable exactly when they are tired or stressed.

**How might we…**

1. …help students notice how mood and screen habits connect without feeling judged?
2. …suggest breaks that fit a student's mood, schedule and time of day?
3. …make healthy routines easy enough to start on low-energy days?
4. …reward progress without punishing slips?
5. …protect the privacy and trust of users who share mood data?

**App goal.** To design MindPatch, a calm, AI-assisted wellness planner that lets students log mood, see their screen time, and receive transparent, personalised detox suggestions, building small healthy routines through gentle nudges and rewards.

**Design principles.** Calm and minimal. Low cognitive load. Explain the ‘why’. Tiny steps. Forgiving streaks. Accessible (strong contrast, readable text, never colour alone for mood). Private by default.

| Research insight | Compulsory feature it shapes |
|---|---|
| Self-awareness comes first | Mood Logging and Screen-Time Dashboard |
| Timing and mood both matter | AI-Generated Detox Planner |
| Balance and positive support help | Gratitude Journal |
| Small, forgiving habits last | Habit Tracker with Rewards |

## 9. References

**Research sources**

- Alkaabba, A., Hussein, G., Albader, M., Assiri, O. F., Alosaimi, B. M., Al Musaad, M. N., Khamsah, M. A., Alzahrani, B. M., Al Sharani, A. H., Asiri, N. A., Alotaibi, A. F., Alshahwan, A., & Alwalah, M. A. (2025). The digital dilemma: Patterns of screen time, sleep quality, and mental health among Saudi university students. *Cureus, 17*(9), e91882. https://doi.org/10.7759/cureus.91882
- Boniel-Nissim, M., Marino, C., Galeotti, T., Blinka, L., Ozoliņa, K., Craig, W., Lahti, H., Wong, S. L., Brown, J., Wilson, M., Inchley, J., & van den Eijnden, R. (2024). *A focus on adolescent social media use and gaming in Europe, central Asia and Canada: Health Behaviour in School-aged Children international report from the 2021/2022 survey. Volume 6.* WHO Regional Office for Europe. https://www.who.int/europe/publications/i/item/9789289061322
- Bradley, A. H., & Howard, A. L. (2023). Stress and mood associations with smartphone use in university students: A 12-week longitudinal study. *Clinical Psychological Science, 11*(5), 921–941. https://doi.org/10.1177/21677026221116889
- Eske, J. (2023). *Exploring the association between smartphone-based screen time and positive and negative affect in university students using experience sampling methodology* [Bachelor's thesis, University of Twente]. https://purl.utwente.nl/essays/95238
- Jacob, S., Noel, J., & Rosenthal, S. (2022, November 6–9). *Smartphone screen time and co-morbid mental illness in university students* [Conference presentation]. American Public Health Association Annual Meeting and Expo, Boston, MA, United States. Summarised in Marzella, M. (2022). Study sees link between smartphone screen time, symptoms of mental illness. *Drug Topics, 166*(12). https://www.drugtopics.com/view/study-sees-link-between-smartphone-screen-time-symptoms-of-mental-illness
- Kaewpradit, K., Ngamchaliew, P., & Buathong, N. (2025). Digital screen time usage, prevalence of excessive digital screen time, and its association with mental health, sleep quality, and academic performance among Southern University students. *Frontiers in Psychiatry, 16*, 1535631. https://doi.org/10.3389/fpsyt.2025.1535631
- Miranda-Soberón, U., Pino-Arana, I., Miranda-Pérez, J., Córdova-Delgado, M., Velásquez-Quispe, Y., Chauca, C., & del Rio-Mendoza, J. (2026). Problematic smartphone use and its relationship with depression, anxiety, and usage time among university students. *Comunicar, 34*(85), 1–11. https://doi.org/10.5281/zenodo.19689448
- Rajput, L., Bhardwaj, A., Vempaty, S., Spaić, D., Milinković, B., Bokonjić, D., & Grujičić, M. (2026). Screen time and its impact on university students. *Biomedicinska istraživanja, 17*(1), 1–10. https://biomedicinskaistrazivanja.mef.ues.rs.ba/article/618

**Behaviour-change sources**

- Duhigg, C. (2012). *The power of habit: Why we do what we do in life and business.* Random House.
- Fogg, B. J. (2019). *Tiny Habits: The small changes that change everything.* Houghton Mifflin Harcourt. Fogg Behavior Model: https://www.behaviormodel.org/
- Thaler, R. H., & Sunstein, C. R. (2008). *Nudge: Improving decisions about health, wealth, and happiness.* Yale University Press.

**App analysis sources**

- Headspace. App Store listing: https://apps.apple.com/us/app/headspace-com-meditation-mindfulness/id493145008. MedCity News coverage of the Ebb AI companion: https://medcitynews.com/?p=130583
- Forest. Product page: https://forestapp.cc/llms-full.txt. Review: https://goalsandprogress.com/boost-your-focus-with-the-forest-app/
- Reflectly. TechRadar review: https://www.techradar.com/reviews/reflectly. ChoosingTherapy review: https://www.choosingtherapy.com/?p=18867
