---
name: good-microcopy
description: >
  Guides writing excellent microcopy — the small, purposeful text in UI elements like buttons, 
  error messages, empty states, loading screens, tooltips, placeholders, and confirmation dialogs 
  — for any user-facing application. Use this skill any time you are building, designing, or 
  reviewing UI, writing interface text, generating copy for forms, onboarding flows, notifications, 
  checkout, settings, or any screen a user will see. Microcopy always matters. Even if the user 
  doesn't mention copy, UX, or writing, apply these principles whenever you produce UI text of any 
  kind. Good microcopy is not a finishing touch — it's part of building the product.
---

# Good Microcopy

Microcopy is every small piece of text a user reads while doing something: button labels, 
placeholder text, error messages, empty states, tooltips, loading messages, confirmation dialogs, 
form helper text, notifications. It seems minor but it determines whether users feel confident, 
confused, anxious, or delighted.

Apply these principles automatically whenever you write any user-facing text. Don't wait to be 
asked. Microcopy is part of the interface, not decoration added at the end.

---

## Core Principles

### 1. Set expectations before the user has to ask

Tell users what will happen, how long it will take, or what comes next — before they wonder. 
Uncertainty creates anxiety; clarity creates trust.

- **Newsletter signups**: "We send one email a week, no spam ever." Not just "Subscribe".
- **Video CTAs**: Label with duration — "Watch intro (2 min)" — so users can decide before clicking.
- **After signup**: "Check your inbox — we sent a confirmation link. It expires in 24 hours."
- **Checkout**: Show file formats, extra fees, and delivery windows near the CTA, not after payment.
- **Custom orders**: "Handmade to order — ships in 3–5 weeks." Set it early, not in fine print.

The rule: if a user might pause and wonder "but what about X?" — answer X in the copy.

If you make a claim in copy — "30 Second Checkout", "Ships today if ordered by 3pm", "Free forever" 
— you are making a promise. The product must keep it. Microcopy that overpromises and underdelivers 
destroys more trust than no copy at all. Only write what you can guarantee.

---

### 2. Provide context at the moment it's needed

Helpful information lands only when it's relevant to what the user is doing right now. 
Context-aware copy is more effective than blanket instructions.

- **Security warnings**: Surface password reuse warnings at login, not in a settings menu.
- **New features**: When iOS Siri auto-fills something, explain what triggered it and where the 
  data came from. Don't just act — explain.
- **Progress**: "Uploading… about 2 minutes left. Feel free to keep working."
- **Pre-registration**: Before a form, list everything the user will need: "You'll need your 
  Medicare number and a recent bill." Save them from getting halfway through and hitting a wall.
- **Be one step ahead**: Anticipate the anxiety a user hasn't voiced yet and defuse it early. 
  Tumblr suggests usernames on signup and adds "don't worry, you can change this later" — nobody 
  asked, but everyone was wondering.
- **Checkout decisions**: When a product has many variants, use supporting copy to narrow 
  choices: "This weight works for most home users."

Don't front-load all help text at the top of a screen. Put it beside the decision it informs.

---

### 3. Give clear, specific feedback

Users need to know what happened after they do something. Generic confirmations ("Done!") 
are missed opportunities. Specific feedback builds confidence and reduces repeat actions.

- **Weak**: "Changes saved."
- **Strong**: "Your card ending in 4242 has been updated."

- **Weak**: "Item added."  
- **Strong**: "Added to your queue — playing next." (YouTube)

- **File uploads**: Don't just show a spinner. "Uploading your video — processing usually takes 
  about 5 minutes after upload completes."
- **Sync**: Show last sync time. "Last synced 2 minutes ago" removes the question "is my data safe?"
- **Integration success**: "Trello connected — your boards will now sync automatically."

Vary confirmation messages for repeated actions (Tumblr does this with copy link) — it prevents 
the feeling of a broken interface and adds delight.

---

### 4. Speak the user's language, not your system's language

Write from the user's perspective, not from the product's internal logic. Use words they would 
use, not words your team uses internally.

- **First person for choices**: "I'm building a brand" vs "For brand builders" — the first makes 
  users feel heard.
- **Button labels**: "Keep going" > "Next". "I'll do this later" > "Skip". "End the other call" 
  > "Disconnect". Labels that describe the outcome feel natural; abstract labels require 
  translation.
- **Error messages**: Don't say "Authentication failed." Say "Wrong password — or try signing 
  in with Google if you used that before."
- **Know your audience**: Stack Overflow can use witty placeholder text because developers 
  appreciate it. A medical app cannot. Match vocabulary and tone to who's actually reading.

BOIP (a legal IP office) rewrote its plan selector into first-person statements and turned a 
complex bureaucratic choice into a human one. The product didn't change — the language did.

---

### 5. Don't blame users for errors

When something goes wrong, own it. User-blaming error messages damage trust. 
Blame-free copy keeps users moving.

- **Bad**: "Invalid input detected."
- **Good**: "We couldn't find that email address — double-check it or try a different one."

- **Bad**: "Error 403: Unauthorized."
- **Good**: "You don't have access to this page. Contact your admin to request it."

Even when the user made the mistake, frame the message around the solution, not the fault.
LinkedIn exemplifies this — their error messages take responsibility and guide forward.

---

### 6. Be reassuring at anxiety points

Certain moments create friction: giving an email address, entering payment info, requesting 
permissions, signing up for a trial. These are the moments where a single sentence of 
reassurance makes the difference between conversion and abandonment.

- **Email fields**: "No spam. Unsubscribe anytime." (near the input, not buried in footer)
- **Payment**: "Secure checkout — we never store your card number."
- **Permissions**: Explain what the permission enables and what you won't do with it. 
  Apple's location permission copy is a model: it states the benefit and the limit.
- **Trials**: "30 days free, all features included. Cancel anytime — no questions asked." 
  (Tower 2) — removes every hesitation in one sentence.
- **Social proof at the point of decision**: Place trust signals exactly where doubt peaks — 
  beside the payment button, under the email field, next to the permission request. Not in the 
  hero section where users are still browsing. Zurb displaying recognizable logos near a CTA, 
  or Intercom showing "joined by X teams" right above signup — that's the right moment.
- **Give reasons to act**: Don't just describe what a trial or plan includes — frame it around 
  what the user gains. "30 days free, all features, cancel anytime" is a reason to act. 
  "Free trial available" is not.

---

### 7. Guide, don't instruct — and never take away control

Good microcopy nudges users toward good paths without being paternalistic. Show a 
recommended option, but preserve the user's ability to do it their way.

- **Settings for beginners**: Offer a "Recommended" or "Standard" mode, but keep "Advanced" 
  accessible. (Little Snitch does this well.)
- **Destructive actions**: Slow users down with specific consequence language: "Delete this 
  project? This removes all 47 tasks and can't be undone." Not just "Are you sure?"
- **Onboarding**: Dropbox Paper sends emails that suggest what you might use it for — not a 
  mandatory tutorial. Suggestions, not requirements.
- **Search corrections**: Twitter shows results for both the original query and the corrected one. 
  Offer the correction; don't force it.

The test: does your copy help users make better decisions, or does it make decisions for them?

---

### 8. Empty states are a product moment, not an afterthought

The first time a user sees a screen with no content is one of the highest-leverage moments 
in your product. It sets expectations and determines whether users engage or disengage.

- **Don't leave a blank screen.** Explain what goes here and how to add it.
- **Give clear next steps**: Feedly's empty category screen adds reinforcement + "Find more 
  sources" CTA. Jira's empty search result reframes as "Nothing yet — create the first one."
- **Use personality where it fits**: Scrumpy's empty state entertains. Marvel's shows a demo, 
  an intro video, and a create button. Match the moment to your brand.
- **Tell users what they're missing**: "Your queue is empty — add songs to keep the music 
  going." Not just "Empty queue."

Empty states are invitations. Write them that way.

---

### 9. Use personality — but clarity always wins

Brand voice makes products memorable. But never sacrifice clarity for cleverness. If a user 
has to re-read something to understand it, the joke wasn't worth it.

- **Loading screens**: Slack's loading messages ("[person] is trying to type — bless their heart") 
  entertain during wait time without blocking anything.
- **Buffer's empty queue**: Rotates between different upbeat messages. Still 100% clear that 
  the queue is empty.
- **Codekit's purchase confirmation**: On-brand and clear. Never sacrifices the "what just 
  happened" information for a punchline.
- **404 pages**: Photojojo's 404 page is playful and immediately gives users a path forward. 
  Playfulness without escape routes isn't UX — it's a dead end.
- **The test**: Cover the logo. Would you know which company this is? Good personality is 
  consistent and recognizable. Could a user misread this and do the wrong thing? If yes, 
  rewrite it.

Personality lives in word choice, tone, and unexpected-but-apt phrasing. Not in puns that 
obscure meaning.

Every error state, loading screen, and dead end is a brand moment. Gumtree's casual "sigh…ok" 
on a failed action, Timehop's personality-driven empty states, Tumblr's randomized loading 
messages — these cost nothing extra and leave an impression. Never waste a transition on a 
generic message when a human one would do the same job.

---

### 10. Sweating the small stuff is the job

Microcopy isn't just forms and errors. It's everywhere.

- **URL slugs**: Photojojo used `/awesomeness/` in their product URLs. It cost nothing and 
  reinforced brand identity at a glance.
- **Button labels**: "Keep going" on a multi-step form vs "Next" — one word of difference, 
  entirely different feeling.
- **Email subjects and headers**: InVision's email buttons spoke designer language because 
  the audience was designers.
- **Progress indicators**: PayPal's profile completion percentage makes an abstract task 
  feel tangible and closeable.
- **Loading messages**: Hearthstone turns a loading screen into a miniature piece of 
  game writing. Tumblr randomizes them. Both make waiting feel intentional.

The principle: every word a user reads is an interaction. Treat it that way.

---

## Microcopy by UI Element

A quick reference for the moments that matter most:

| Element | What to get right |
|---|---|
| **Buttons** | Describe the outcome, not the action. "Save changes" → "Save and continue editing". Use first person for choices: "Start my free trial". |
| **Placeholders** | Only use when they add context examples can't convey. Never use as a label replacement. "Search for a city, ZIP, or landmark." |
| **Error messages** | State what happened, why, and what to do next. No blame. No codes. No jargon. |
| **Empty states** | Explain what goes here, why it's empty, and the clearest next step. |
| **Loading / progress** | Show time estimates when you can. Use personality sparingly. Never leave users with just a spinner and no information. |
| **Confirmation dialogs** | Name the specific thing being deleted/changed. Show consequences. Offer an alternative to the destructive path. |
| **Form helper text** | Put it next to the field it helps, not at the top of the form. Answer the question the user is about to ask. |
| **Notifications / toasts** | Be specific. "Project saved" > "Saved." Vary repeated confirmations. |
| **Onboarding tooltips** | Time them to the action they explain. Don't show everything at once. |
| **Success screens** | Confirm what completed, state what comes next, and offer an immediate next action. |

---

## Length: the most common mistake in both directions

More words is not better microcopy. The goal is the right words — often fewer.

**Cut first, add only what earns its place.** Before adding context, ask: would a first-time user 
actually be confused without this? If no, cut it. If yes, add it right where the confusion would happen.

- Slack's weekly digest is celebrated precisely because it is short. Data, then done.
- A button label should be 2–4 words. If you need 8, the design has a problem.
- Toast notifications should be one clause. "Saved." is fine. "Your changes have been successfully saved to the cloud." is not.
- Helper text that explains something obvious ("Enter your name in this field") adds noise, not value.

**The test**: if removing a sentence doesn't create confusion, remove it.

Specificity and brevity are not in tension — "Card updated" is both shorter and more specific than 
"Your information has been saved successfully." Write tight.

---

## Anti-patterns to avoid

- **Jargon**: "Authentication failed", "Invalid token", "HTTP 500" — rewrite in plain language.
- **Generic labels**: "Submit", "OK", "Click here", "Learn more" — always be more specific.
- **Placeholder abuse**: Using placeholders as labels disappears when users start typing.
- **Anxiety without reassurance**: Asking for sensitive data without explaining why.
- **Vague error messages**: "Something went wrong" — useless. What went wrong? What now?
- **Front-loaded help text**: Walls of instructions before a form nobody reads.
- **Personality without clarity**: A pun that makes users unsure what a button does.
- **Blameful errors**: "You entered an invalid date." → "That date doesn't look right — try MM/DD/YYYY."
- **Over-explaining**: Adding context the user didn't need. If they weren't going to wonder, don't answer.
- **Verbose confirmations**: "Your changes have been successfully saved." → "Saved."

---

## How to apply this skill

When building any user-facing screen or flow:

1. **Identify every moment a user reads something** — buttons, labels, helper text, errors, 
   empty states, loading states, confirmations, notifications.
2. **For each one, ask**: Does this set expectations? Give feedback? Speak plainly? Reassure 
   where needed? Provide the right context at the right moment?
3. **Apply the relevant principle** — most UI text problems fall into one of the patterns above.
4. **Check voice consistency** — does the copy feel like the same product and the same brand 
   across all screens?
5. **Read it as a first-time user** — someone who doesn't know what you know. Does it still 
   make sense?

The goal is not to add microcopy. It's to make sure every word earns its place.
