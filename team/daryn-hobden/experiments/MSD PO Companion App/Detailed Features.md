# Detailed App Features — MSD Pet Owner Companion App

Each feature below includes a Lean UX Canvas covering the business problem it addresses, the desired outcomes, the users it serves, hypotheses, and the most important assumptions to test.

---

## 1. Symptom Checklist and Triage Tool

A pre-diagnosis tool that helps pet owners evaluate symptom severity and decide with confidence when to book a vet appointment.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | MSD has no direct touchpoint with pet owners during the critical pre-diagnosis phase. Owners turn to unreliable online sources, often delaying or avoiding vet visits entirely. |
| **Business Outcomes** | Increase in qualified vet referrals and first consultations for atopic dermatitis. Reduction in owners self-treating without professional guidance. |
| **Users** | Pet owners who have noticed their dog scratching, biting, or showing signs of skin irritation but are unsure of the severity or cause. |
| **User Outcomes & Benefits** | Owners feel confident enough to book a vet appointment at the right time. They arrive better informed and less anxious. They stop relying on conflicting online advice. |
| **Solutions** | An interactive symptom checklist ("itch checker") that categorises symptoms as temporary, seasonal, or chronic. Severity scoring that outputs a clear recommendation: monitor at home, book soon, or seek urgent care. |
| **Hypotheses** | If we give pet owners a simple triage tool, they will be more likely to book a vet appointment at the right time, because the main barrier is uncertainty about whether symptoms are serious enough to warrant a visit. |
| **Most Important Thing to Learn** | Do owners trust an app-based triage tool enough to act on its recommendation, or do they dismiss it as generic? |
| **Least Amount of Work to Learn It** | Build a static prototype of the checklist and test it with 5–8 pet owners who have recently noticed symptoms in their pet. Measure whether they say the output matches their intuition and whether they'd act on it. |

---

## 2. Vet Visit Discussion Guide

Structured guides that tell owners exactly what to ask their vet, what information to bring, and what questions the vet is likely to ask them.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Short vet appointments are underutilised. Owners leave confused or without a clear diagnosis because they didn't know what to share or ask. This leads to delayed treatment starts, which delays MSD product adoption. |
| **Business Outcomes** | Higher rates of confirmed atopic dermatitis diagnoses following first consultations. Increased prescription of MSD treatments as owners arrive better prepared. |
| **Users** | Pet owners preparing for their first vet consultation about their pet's skin condition. Also relevant for owners returning after a flare-up. |
| **User Outcomes & Benefits** | Owners feel prepared and in control before the appointment. They extract more value from short consultations. They leave with a clearer diagnosis and treatment plan. |
| **Solutions** | A pre-visit guide with a curated list of questions to ask the vet. A prompt to note down symptoms, frequency, and duration before the appointment. A "what to expect" explainer for the diagnosis process. |
| **Hypotheses** | If we give pet owners a structured discussion guide before their vet visit, they will have more productive consultations, because the main failure point is owners not knowing what information is clinically relevant to share. |
| **Most Important Thing to Learn** | Do vets find that owners who come prepared actually change how the consultation goes, or do vets already lead the conversation anyway? |
| **Least Amount of Work to Learn It** | Interview 3–5 vets about how informed their average pet owner client is and whether owner-led preparation changes the quality or outcome of the consultation. |

---

## 3. Expectation-Setting and Diagnosis Education Content

In-app content that explains the diagnosis journey, prepares owners for the trial-and-error nature of treatment, and sets realistic expectations for lifelong management.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Owners who don't understand that atopic dermatitis is chronic and requires ongoing management stop treatment when symptoms temporarily improve. This directly causes compliance slips and lost revenue. |
| **Business Outcomes** | Reduction in early treatment drop-off rates. Increase in long-term prescription refill rates. Improved owner retention in loyalty and rebate programmes. |
| **Users** | Newly diagnosed pet owners who are starting a treatment plan for the first time. |
| **User Outcomes & Benefits** | Owners understand that improvement is not a cure. They persist through the trial-and-error phase without losing confidence. They feel mentally prepared for the long-term nature of the condition. |
| **Solutions** | A "What to expect" content series covering: how diagnosis works, why treatment takes time, what a flare-up means, and why lifelong management is normal. Delivered as short articles, animated explainers, or vet-narrated videos. |
| **Hypotheses** | If we educate owners about the chronic nature of atopic dermatitis early in the diagnosis journey, they will maintain treatment compliance for longer, because compliance slips are primarily driven by the false belief that improvement equals cure. |
| **Most Important Thing to Learn** | At what point in the journey is this content most influential — before the first vet visit, immediately after diagnosis, or at the first sign of improvement? |
| **Least Amount of Work to Learn It** | Run a content timing test: show the same education content to two groups at different journey stages and measure which group reports higher confidence and stated intent to continue treatment after 4 weeks. |

---

## 4. Emotional Reassurance and Empathetic Storytelling

Content that uses peer testimonials, video case studies, and empathetic messaging to reduce owner guilt and anxiety around their pet's condition.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Owners who feel shame or guilt about their pet's condition are less likely to engage consistently with the app, seek help proactively, or share their experience — limiting community growth and word-of-mouth. |
| **Business Outcomes** | Increased app engagement and session frequency. Higher rates of community participation and user-generated content. Improved net promoter score and brand sentiment. |
| **Users** | Pet owners experiencing guilt, anxiety, or emotional fatigue from managing a pet with a chronic condition — particularly those early in the journey or mid-flare-up. |
| **User Outcomes & Benefits** | Owners feel less alone and less responsible for causing the condition. They feel understood by the brand. They are more open to seeking help and sharing their own story. |
| **Solutions** | A library of video case studies and written testimonials from other pet owners. Empathetic, non-judgmental UI copy throughout the app. Onboarding messaging that explicitly normalises the condition. KOL and vet video content that validates owner emotions. |
| **Hypotheses** | If we lead with empathetic peer storytelling rather than clinical information, owners will engage more deeply with the app, because emotional connection and the sense of not being alone is a stronger motivator than information alone at the early stage of the journey. |
| **Most Important Thing to Learn** | Does peer storytelling actually shift owner sentiment, or does it just feel good in research but have no measurable effect on behaviour? |
| **Least Amount of Work to Learn It** | A/B test two onboarding flows with new users: one leading with peer stories, one leading with clinical information. Measure 7-day and 30-day retention rates. |

---

## 5. Digital Reminders and Behavioural Nudges

Push notifications, SMS, and in-app reminders timed to the pet's treatment schedule to prevent compliance slips.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Treatment compliance slips are one of the most direct causes of lost revenue. Owners skip doses or stop treatment when symptoms improve, reducing the effectiveness of the product and the likelihood of repeat prescriptions. |
| **Business Outcomes** | Measurable improvement in treatment adherence rates. Reduction in gaps between prescription refills. Increase in the average length of a treatment cycle. |
| **Users** | Pet owners who are mid-treatment for atopic dermatitis, particularly those managing a daily or regular medication schedule. |
| **User Outcomes & Benefits** | Owners never miss a dose. The care routine becomes habitual rather than effortful. They feel less mental load around remembering treatment. |
| **Solutions** | Customisable push notification reminders tied to treatment type and frequency. Vet-synced scheduling that imports the exact treatment plan from the clinic. Escalating nudges for missed doses. Optional SMS fallback for low-engagement users. |
| **Hypotheses** | If we send timely, personalised treatment reminders, pet owners will maintain higher compliance rates, because the primary cause of missed doses is forgetting rather than intentional non-compliance. |
| **Most Important Thing to Learn** | Do owners turn off reminders after the first few weeks, making them ineffective long-term? And what reminder format (push, SMS, in-app) has the lowest opt-out rate? |
| **Least Amount of Work to Learn It** | Run a 30-day pilot with a small group of existing users. Track notification opt-out rates, reminder interaction rates, and self-reported compliance at the end of the period. |

---

## 6. Symptom Tracker and Digital Diary

A tool for logging symptoms, flare-ups, and treatment responses over time to build a visual record of the pet's health progress.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Owners have no structured way to track their pet's progress, making it difficult to assess whether a treatment is working. This increases anxiety, leads to premature treatment switches, and reduces the quality of follow-up vet consultations. |
| **Business Outcomes** | Reduction in unnecessary treatment switches driven by short-term symptom fluctuation. Increase in owner confidence in current treatment. More productive follow-up vet consultations that reinforce continued prescription. |
| **Users** | Pet owners who are mid-treatment and trying to evaluate whether the current plan is effective, as well as owners managing recurring flare-ups. |
| **User Outcomes & Benefits** | Owners can see clear trends in their pet's condition over time. They have concrete evidence to share with their vet at follow-ups. They feel reassured that the treatment is working even when progress feels slow. |
| **Solutions** | A daily or weekly symptom logging tool with a simple severity scale. Photo upload for visual comparison over time. Charts and timeline views showing symptom trends. Exportable reports formatted for vet consultations. |
| **Hypotheses** | If we give owners a simple visual tracking tool, they will feel more confident in their treatment plan and less likely to abandon it prematurely, because seeing progress — even small improvements — is a stronger motivator than being told a treatment takes time. |
| **Most Important Thing to Learn** | Will owners actually log consistently, or does logging fatigue set in within the first two weeks? |
| **Least Amount of Work to Learn It** | Prototype a minimal logging flow (single symptom score + optional photo) and recruit 10 owners to use it daily for 2 weeks. Track completion rates and drop-off points. |

---

## 7. Gamified Milestone Rewards and Points System

A tiered points system that rewards owners for completing treatment milestones, daily care tasks, and app engagement — redeemable for vet care, merchandise, or rebates.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Long-term treatment management feels like a chore with no visible reward. Without motivation, owners disengage from the app and their care routine, reducing compliance and loyalty programme participation. |
| **Business Outcomes** | Increased daily active users. Higher rates of loyalty programme participation. Improved long-term treatment compliance tied to engagement streaks and milestone completion. |
| **Users** | Pet owners who are at least 4–8 weeks into a treatment plan and at risk of routine fatigue or disengagement. |
| **User Outcomes & Benefits** | The care routine feels rewarding rather than burdensome. Owners feel recognised for their effort and dedication. They have tangible incentives to keep going. |
| **Solutions** | A points system earned by completing daily care tasks, logging symptoms, and hitting treatment milestones. Tiered levels that unlock greater earning potential and exclusive rewards. Rewards redeemable for vet care discounts, branded merchandise, or financial rebates. Visual progress indicators and milestone celebrations in the UI. |
| **Hypotheses** | If we make long-term care management feel rewarding through a gamified points system, owners will remain engaged with the app for longer, because routine fatigue — not lack of intention — is the primary driver of disengagement after the first month. |
| **Most Important Thing to Learn** | Are the rewards on offer valuable enough to motivate behaviour, or does the points system feel trivial compared to the effort required? |
| **Least Amount of Work to Learn It** | Conduct a card-sorting exercise with 8–10 pet owners to rank potential rewards by motivational value. Use findings to define the minimum viable reward catalogue before building the system. |

---

## 8. Ambassador Programme

A community-driven programme that rewards owners for sharing testimonials, referring friends, and uploading before-and-after content of their pet's progress.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | MSD lacks direct peer-to-peer advocacy among pet owners. Word-of-mouth is highly influential in this category but is currently untapped and unstructured. |
| **Business Outcomes** | Growth in new app users via referral. Increase in user-generated content that can be used in empathetic storytelling campaigns. Reduction in cost-per-acquisition through organic peer advocacy. |
| **Users** | Engaged, longer-term app users who have seen visible progress in their pet's condition and feel positive about the treatment journey. |
| **User Outcomes & Benefits** | Owners feel valued and recognised for their experience. Sharing their story gives meaning to a difficult journey. They earn tangible rewards for participation. |
| **Solutions** | A structured referral flow with a unique shareable link and reward for both referrer and new user. A content submission tool for before-and-after photos and written testimonials. A visible ambassador status or badge system within the app. |
| **Hypotheses** | If we create a structured ambassador programme, satisfied owners will actively refer others and share their stories, because pet owners in this category already want to share their experiences — they just need a low-friction, rewarded way to do it. |
| **Most Important Thing to Learn** | At what point in the treatment journey does an owner feel positive enough to want to share their story? Is it tied to a specific milestone (e.g., first visible improvement)? |
| **Least Amount of Work to Learn It** | Interview 6–8 owners who have been managing atopic dermatitis for 3+ months. Ask at what point they first felt confident enough to tell someone else about what worked. Use this to determine the trigger point for ambassador recruitment. |

---

## 9. Digital Rebates and Financial Rewards

Simple, in-app access to financial rebates, coupons, and savings on MSD treatments — designed to be significantly easier to use than competitor reward programmes.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | The long-term financial burden of managing a chronic condition leads owners to stop treatment or switch to cheaper alternatives, including competitor products. MSD's existing rebate mechanisms are not digitally accessible or user-friendly. |
| **Business Outcomes** | Increase in rebate programme participation rates. Reduction in treatment drop-off driven by cost. Increased switching from competitor products to MSD treatments by making the total cost more competitive. |
| **Users** | Pet owners who are managing the ongoing cost of treatment and actively looking for ways to reduce spend without compromising their pet's care. |
| **User Outcomes & Benefits** | Owners feel financially supported rather than penalised for long-term commitment. Savings are easy to access and apply — no complex points conversion or confusing terms. They feel the brand is on their side. |
| **Solutions** | In-app digital coupons and rebates linked to the owner's treatment history. A clear, simple savings dashboard showing how much they have saved over time. Clinic-integrated rebate activation that reduces friction at point of purchase. |
| **Hypotheses** | If we offer simple, frictionless digital rebates, owners will remain on MSD treatments for longer, because cost is a primary trigger for switching or stopping — and the main barrier to existing rebate programmes is complexity, not the value of the saving itself. |
| **Most Important Thing to Learn** | Is the current barrier to rebate uptake the complexity of the programme, the awareness of its existence, or the perceived value of the saving? |
| **Least Amount of Work to Learn It** | Survey 20 pet owners who have lapsed on treatment. Ask them to rank the top 3 reasons they stopped and whether they were aware of any savings programmes. This determines whether the problem is product design or marketing. |

---

## 10. At-Home Subscription and Auto-Refill

A subscription model that delivers ongoing treatment supplies directly to the owner's home at a reduced cost, ensuring they never run out before the next vet appointment.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Compliance slips often happen not because an owner chooses to stop, but because they run out of medication and haven't arranged a refill in time. This gap in supply breaks the treatment routine. |
| **Business Outcomes** | Reduction in treatment gaps caused by supply interruption. Increase in average prescription cycle length. New direct-to-consumer revenue stream and stronger retail partnerships. |
| **Users** | Pet owners who are 3+ months into a stable treatment plan and have confirmed that the current treatment is working for their pet. |
| **User Outcomes & Benefits** | Owners never experience a supply gap. The financial commitment feels more manageable through a predictable, discounted subscription. They spend less time managing logistics and more time focused on their pet's wellbeing. |
| **Solutions** | An opt-in subscription flow within the app, linked to the pet's confirmed treatment plan and dosage. Automated refill scheduling with advance notice before each delivery. Bundled pricing that offers a meaningful discount versus ad-hoc purchasing. |
| **Hypotheses** | If we offer an auto-refill subscription for confirmed, stable treatments, owners will experience fewer compliance gaps, because the most common cause of unintentional non-compliance is running out of medication rather than choosing to stop. |
| **Most Important Thing to Learn** | Are owners willing to commit to a subscription before they are confident the treatment is working, or does subscription intent only emerge after seeing results? |
| **Least Amount of Work to Learn It** | Include a subscription interest question in the onboarding flow and at the 8-week treatment milestone. Compare the response rates between the two touchpoints to determine the optimal moment to offer the subscription. |

---

## 11. AI-Powered Environmental Alerts and Proactive Education

Personalised push notifications about local environmental triggers (allergens, humidity, pollen) with pre-emptive care recommendations to stop flare-ups before they begin.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Reactive treatment of flare-ups is more costly and distressing than prevention. Owners currently have no way to anticipate environmental triggers, so flare-ups feel random and uncontrollable — increasing anxiety and reducing confidence in treatment. |
| **Business Outcomes** | Reduction in severity and frequency of reported flare-ups among app users. Increase in proactive product usage (e.g., topical treatments applied pre-emptively). Differentiation from competitors through a unique, data-driven feature. |
| **Users** | Pet owners who have identified that their dog's condition has seasonal or environmental patterns, and who are managing ongoing atopic dermatitis. |
| **User Outcomes & Benefits** | Owners feel proactive rather than reactive. They have a sense of control over an otherwise unpredictable condition. Their pet experiences fewer distressing flare-ups. |
| **Solutions** | Integration with local environmental data APIs (pollen count, humidity, air quality). AI-generated personalised alerts when local conditions exceed a threshold relevant to the pet's known triggers. Paired recommendations for pre-emptive care actions. Bite-sized educational content about how environmental factors affect atopic dermatitis. |
| **Hypotheses** | If we send owners personalised environmental alerts before conditions that are likely to trigger a flare-up, they will take pre-emptive action and experience fewer severe episodes, because owners want to feel in control and proactive care is more motivating than reactive treatment. |
| **Most Important Thing to Learn** | Do owners currently perceive a link between environmental conditions and their pet's flare-ups, or is this connection too abstract to be immediately actionable? |
| **Least Amount of Work to Learn It** | In user interviews, ask owners to describe the circumstances of their last 3 flare-ups. Determine whether environmental triggers are already part of their mental model. If they are not, the educational prerequisite becomes the priority before alerts will be acted upon. |

---

## 12. Peer Community and Support Network

An in-app community where pet owners managing chronic conditions can connect, share experiences, find moral support, and access authentic peer reviews of treatments.

| Canvas Section | Detail |
|---|---|
| **Business Problem** | Emotional fatigue from managing a chronic pet condition leads to disengagement, compliance slips, and reduced brand loyalty. Owners feel isolated and unsupported between vet visits. Third-party communities (Reddit, Facebook groups) currently fill this gap with content that may be inaccurate or promote competitor products. |
| **Business Outcomes** | Increased app session frequency and time-in-app. Reduction in churn driven by emotional burnout. Creation of a first-party community platform that keeps engagement within the MSD ecosystem. |
| **Users** | Pet owners who are 1+ months into managing a chronic condition and experiencing emotional fatigue, or those who are newly diagnosed and looking for reassurance from others who have been through the same journey. |
| **User Outcomes & Benefits** | Owners feel less alone. They receive practical advice from peers who have lived experience. They have a trusted space to ask questions without fear of judgement. |
| **Solutions** | A moderated community feed or forum within the app. Peer Q&A functionality. Topic-based groups (e.g., by breed, by treatment type, by condition severity). Highlighting of vet-verified answers alongside peer responses for credibility. |
| **Hypotheses** | If we provide an in-app peer community, owners will feel more emotionally supported and engage with the app more frequently, because the emotional isolation of managing a chronic condition is a key driver of disengagement — and peer validation is more credible to owners than brand-produced content. |
| **Most Important Thing to Learn** | Will owners engage in a branded community hosted by a pharmaceutical company, or does the brand association undermine the perceived authenticity of the peer connection? |
| **Least Amount of Work to Learn It** | Run a concept test: show owners a prototype of the community feature with and without visible MSD branding. Measure whether brand association increases or decreases stated willingness to participate. Use this to determine whether a white-label or lightly branded approach is needed. |
