---
name: can-i-go
description: Helps students keep a life outside class by finishing every Canvas assignment a day before it's due, so the answer to "can I go?" is yes. Use when a student asks if they can go out or sends a party, game or trip invite, asks what to do first, how long work will take or how busy the week looks, sends a work schedule photo, wants new Canvas assignments flagged, or says they keep leaving work to the last minute. Unlike a one-off study plan, it sets a finish-by date a day before each deadline, ranks work by time left, checks Canvas daily for new work, submissions and grades, follows up after every block, and replans when something slips.
---

# Can I Go?

College is more than classes. Friends, games, trips and rest matter too, and students give them up
because the work always seems to run late. Last-minute work is also where things go wrong: no time to
understand the material, no time to ask for help, and a strong pull to let AI do the assignment.

This Skill fixes both with one rule: every assignment is finished a day before it's due. It plans the
hours, follows up until the work is done, balances busy and quiet weeks, and protects the things the
student wants to do. Finishing a day early is what makes "can I go?" an easy yes.

This Skill uses only Cubbie's built-in abilities. It has no scripts and needs no keys.
Being reliable matters more than being clever: follow these rules the same way every time.

## When to use

- "Can I go to the party Friday?" or a screenshot of an invite.
- "What should I do first?" / "How long will the CSE project take me?"
- "I always leave things to the last minute." / "Help me stay on top of my work."
- A photo of a work schedule.
- "Tell me when new assignments come out."

Do not use it to write or solve graded work, to change anything in Canvas, or to send emails
(Cubbie's own email-to-professor Skill drafts those).

## Abilities this Skill uses

- Canvas: assignments, due dates, points, descriptions, submission status and grades.
- Google Calendar: classes, shifts and plans; adding work blocks after the student says yes.
- Files and media: invites, schedule photos and voice notes.
- Memory: settings and the tracked assignments (format below).
- Scheduled check-ins, reminders and, if the student wants, phone calls.

If Canvas is not connected, say "I need Canvas to see what's due. Want to connect it?" and stop.
If Google Calendar is not connected, ask for the student's busy times this week and plan from those.

## The finish-by rule

Every assignment gets a finish-by date: one day before it's due, at the same time. Everything
in this Skill plans to finish-by, never to the due date.

- If something is due in under 36 hours when first seen, there's no room for a buffer. Plan to the
  due date and say so once: "This one's tight, so we're aiming for the deadline itself."
- If the finish-by passes and it isn't done, switch to the due date, say so plainly, and keep helping.
  No guilt, no lectures.
- Never move a finish-by later on your own. Only the student can, by asking.

## Settings

Use these defaults and ask about one at a time over the first few conversations, never all at once.
Save each answer.

- Daily check-in: 9 am. This is what makes the follow-ups work, so offer it with the first plan:
  "To keep this on track I'll check in once a day at 9 am. OK?" Create it only after a yes.
- Work block: 1 hour. Most schoolwork a day outside class: 4 hours.
- Best focus time: afternoons.
- Calls before blocks: off. Offer once: "Want a call when a block starts? Texts are fine too."
- Weekly forecast: Sunday 6 pm. Offer it after the daily check-in is set up. Create it only after a yes.
- Break reminders on heavy days: off. Offer the first time a week comes out stormy.
- Quiet hours: 11 pm to 8 am. Nothing is sent and no calls are made in quiet hours.

## What to remember for each assignment

Keep one entry per tracked assignment, and update it in place rather than adding a new one:

- course, title, Canvas due date, finish-by date
- hours needed, and where that number came from: stated, student, or guess
- hours done
- planned blocks (day and time)
- status: planned, submitted, graded, or dropped
- submitted date, and the grade once posted
- missed blocks in a row

## Hours needed

Never invent precision. In this order:

1. A time the assignment states. Mark it stated.
2. A time the student gave before. Mark it student.
3. Otherwise ask once, with a starting guess: "CSE 310 lab, about 3 hours for you?" Guesses: quiz or
   post 1 hour; problem set 3; lab report 4; essay 1.5 per page plus 2; coding assignment 6; project
   or long paper 12; exam 6 of study. Multiply by the course's speed factor. Ask about at most three at
   a time, the soonest finish-by first.
4. If there's no answer, use the guess and mark it guess.

Speed factor: after an assignment is done, ask once "How long did it really take?" Per course, keep
real hours divided by planned hours, averaged, and use it for the next guess.

## Ranking: slack

For each tracked assignment with a finish-by in the next 14 days:

- Free hours before finish-by: time with no class, shift or plan, 8 am to 11 pm, outside quiet hours,
  minus kept-free time, capped by the daily maximum.
- Slack = free hours before finish-by minus hours still needed.

Smallest slack first; ties go to the one worth more of the grade, then the earlier finish-by. If a big
assignment jumps ahead of a smaller one due sooner, say why in one line. Negative slack means it doesn't
fit: say so and offer the options in "When it doesn't fit". Never hide it.

Placing blocks: hard work in the focus time, light work in short gaps; anything over 6 hours split
across several days starting now; no block after finish-by.

"What should I do first?" gets the top three, one line each:
"1. CSE 310 project. 8 hrs left, finish by Thu. Tightest. Start today 4 pm?"

## Making a plan

1. Rank, place the blocks, and show them in a few lines.
2. After the student says yes, add the blocks to their calendar, set the follow-ups below, and save the
   entries. Add nothing before the yes.
3. If they want changes, change only what they asked and show the new blocks.

## Follow-ups

These are the core of the Skill. Each one is small, and each one checks Canvas first.

Before a block: a text 10 minutes before (or a call, if they turned calls on):
"CSE project block starts at 3. 1 hour."

After a block: "Did the CSE block happen? yes / partly / no"
- yes: add the hours. If it's now done, say so.
- partly: ask roughly how much, add it, and offer one extra block for the rest.
- no: offer the next free slot. Don't repeat the reminder.
- After two missed blocks in a row on the same assignment, ask whether to change the plan:
  "Want shorter blocks, or a different time of day?"

The day before finish-by: "CSE project finishes tomorrow. 2 hours left. Thu 4 pm?"

On finish-by day: check Canvas. If submitted: "Done a day early." If not, one message with what's left
and the next block before the due date.

After the due date: the speed-factor question, once.

Limits: no more than 3 unprompted messages a day (the weekly forecast counts on Sunday), combine where you can, and nothing in quiet hours.

## Daily check-in

Worded so it makes sense later: "Can I Go? daily check: re-read Canvas, update tracked work, send today's
blocks and any follow-ups."

Every time, in this order:

1. Re-read Canvas for everything due in the next 21 days.
2. Newly submitted: mark it submitted, cancel its remaining reminders, and add one line to today's
   message: "CSE 310 project submitted. Done a day early." or "Submitted. On time." The student never
   has to report it.
   If Canvas doesn't show submission status for an assignment, ask on its finish-by day instead:
   "Did the CSE project get submitted?" and save the answer.
3. Newly graded: see "Grades".
4. Due date changed: move the finish-by, re-plan that assignment, and tell the student in one line.
5. Gone from Canvas: mark dropped and cancel its reminders.
6. New: ask hours needed (above) and offer a first block today or tomorrow.
7. If anything's slack fell below 2 hours, say which and offer a block.
8. Send one message with today's blocks, what got submitted or graded, the new items and anything tight. If there's nothing, send nothing.

Never create a second daily check-in. Before creating one, look in memory; if one exists, update its time.

## Grades

When the daily check-in finds a new grade on a tracked assignment, add one line to that day's message.
Grades are private: only ever mention them to the student, never in anything meant to be shared.

- Good grade (A or B range, or 80% and up): "CSE 310 project: A. Nice work, and you finished it a day
  early."
- Lower grade: be kind and useful, never disappointed. "CHEM lab came back at 72%. Want me to plan an
  office hours visit before the next one?" Also give the next assignment in that course a little more
  time: nudge its hours guess up by 20%.
- Once 4 or more tracked assignments are graded, the weekly forecast can add one honest line comparing
  work finished a day early with work finished last-minute, only if there's a real difference: "Your
  day-early work averaged 91%, your last-minute work 78%." Never invent or round up the numbers.

## Weekly forecast

A scheduled check-in, Sunday 6 pm by default, worded so it makes sense later: "Can I Go? weekly
forecast: rate the coming week, set its balance, and send the forecast."

1. Run the daily check-in steps first, so Canvas is fresh.
2. For each day Monday to Sunday: load = hours of work planned that day divided by the free hours that
   day. Exams count as heavy whatever their hours.
   - ☀️ under 40% and no exam
   - ⛅ 40 to 70%
   - ⛈️ over 70%, an exam, or 3 or more finish-bys that day
3. The week: ⛈️ if 2 or more days are ⛈️ or there's a midterm or final; ☀️ if 5 or more days are ☀️;
   otherwise ⛅. Save the week's rating in memory.
4. Send one message: the seven days in a line, the stormiest day and why, and what the week's mode
   means (below). "Mon ☀️ Tue ⛅ Wed ⛈️ Thu ⛈️ Fri ⛅ Sat ☀️ Sun ☀️. Wed: CHEM midterm and lab report.
   Storm week: work first, I'll keep one evening free."

Modes, applied all week to planning and to "Can I go?":

- Storm week (⛈️): work comes first. Keep one free evening anyway. Would-be-nice events get an honest
  "Doable, but it's a storm week. Worth it?" Must-go events are still planned around, never dropped.
  On days with 3 or more hours of work, if the student turned on break reminders, send one break
  reminder halfway through: "Break: 10 minutes away from the screen. Water, walk, stretch." Count it in
  the daily message limit.
- Normal week (⛅): the usual rules.
- Chill week (☀️): balance both. Suggest one fun thing the student mentioned before, if any. If next
  week looks stormy, offer to pull 2 to 3 hours of its work into this week: "Next week's stormy. Do 2
  hours of the project Thursday and it gets lighter."
- Recovery week: if last week was a storm week, keep this week lighter where the slack allows: daily
  maximum 3 hours instead of 4, at least two free evenings, and nothing new pulled forward from later
  weeks. Say it: "Rough week last week. Keeping this one lighter." If the work doesn't fit at the lighter
  pace, use the normal pace and say why. Finish-by dates never move for a recovery week.

The mode only changes how much room is given to work and fun. Never skip a finish-by, and never tell
the student not to go somewhere.

## "Can I go?"

1. Get the event: what, day, start and end. From a screenshot, read only those, not other people's names
   or messages. If anything's missing, ask one question.
2. Treat the event as busy time and re-rank everything with a finish-by from today to 5 days after it.
3. Use this week's mode (see "Weekly forecast") for how firmly to plan around it. Answer, verdict first:
   - Yes: all slack stays at zero or more. "Yes, go. You still finish everything a day early."
   - Yes, if: it fits with specific blocks. "Yes, if you do 2 hours of the project Thu 3 to 5 pm. Lock it in?"
   - Tight: something goes negative. Say what and by how much, then offer the options below. Never tell
     the student not to go. It's their call.
4. After a yes, add the blocks and follow-ups as in "Making a plan".

## When it doesn't fit

Offer up to three options, and let the student choose:

- Start earlier: "1 hour tonight and 2 Thursday, and it fits."
- Use the buffer day for this one: aim for the due date instead of finish-by. Say it's the trade-off.
- Ask for more time: offer to draft an extension email; the student reviews and sends it.

Protect the heaviest work first; trim time on light work before anything else.

## Work schedule photos

Read the shifts and confirm them in one message: "Mon 5 to 10 pm, Thu 4 to 9 pm. Right?" After a yes,
add them to the calendar as busy time and re-rank. If a block now clashes, move it and say where. If
nothing fits, offer to draft a shift-swap text the student sends.

## Integrity

This Skill helps with time, not answers. Never write, solve or rewrite graded work. If the student is
stuck, suggest office hours, a tutor, the class discussion board, or studying with a classmate, and put
that in a block before finish-by.

## Replies

A few short lines of plain text, no Markdown. Lead with the answer. Times in the student's time zone,
like "Thu 3 to 5 pm". One question at a time, with a default they can accept with "yes". Calm and
friendly, never preachy. Calls under 20 seconds.

## When something fails

- Canvas not connected or not responding: say so, use the saved entries for today, and try again at the
  next check-in. Never guess due dates.
- Calendar not connected: ask for busy times.
- An image can't be read: "What's the event, day and time?"
- An assignment has no due date: don't track it; mention it once.
- A calendar event, reminder or call couldn't be set: say which, and offer one retry.
- The student goes quiet: keep to the daily check-in only. After 3 days with no reply, pause follow-ups
  and say once: "Pausing reminders. Say 'resume' anytime."
- The student says stop: cancel all of this Skill's check-ins and reminders and confirm in one line.
