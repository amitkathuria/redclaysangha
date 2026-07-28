# Red Clay Sangha Monthly Newsletter

`index.html` is a table-based HTML email, rebuilt each month and sent to the sangha mailing
list. It is a fragment, not a full document — no `<html>`/`<head>`/`<body>`, since it gets
pasted into the mail platform's editor.

## Monthly process

1. **Pull the target month** from the calendar (URL pattern below). Also pull the following
   1–3 months so retreats and look-ahead items are accurate.
2. **Remove anything already past.** The newsletter goes out near the start of the month;
   events earlier than the send date should not appear at all.
3. **Regroup by the site's own taxonomy** (see below) rather than inventing categories.
4. **Feature 3–4 events** for the month, generally in chronological order, with a short blurb
   each. Exception: an event with real registration lead time or limited capacity (e.g. a
   multi-day residential retreat) can be placed ahead of a sooner but lower-commitment event,
   so readers have more time to plan and register. Save a low-barrier, no-registration event
   for last as a closing note.
5. **Refresh the Wednesday and Thursday blurbs** from their event pages — the current book
   and chapters, the current talk series and source texts.
6. **Verify partner organizations and named people** before they go out under Gareth's
   signature. Don't carry forward descriptions from last month's file unchecked.
7. **Send to Gareth Young for review** with a short list of anything that couldn't be
   resolved from the website.

## Sources

- **Calendar (all events, incl. weekly):**
  `https://redclaysangha.org/Calendar?EventViewMode=1&EventListViewMode=2&SelectedDate=M/D/YYYY&CalendarViewType=1`
- **Homepage:** `https://redclaysangha.org/` — the authoritative event grouping
- **Wednesday Meditation and Reading Group:** `https://redclaysangha.org/event-5133342`
  — current book, per-week chapter schedule, upcoming books
- **Thursday Evening Practice:** `https://redclaysangha.org/event-6246874`
  — current series title, source texts, per-week topics
- **Community Service:** `https://redclaysangha.org/Community-Service`
- **Programs:** `https://redclaysangha.org/Programs`

## Event taxonomy

The homepage splits events three ways, and the newsletter sections mirror it:

| Site section | Newsletter section | Contains |
|---|---|---|
| Retreats and Study | **Retreats & Study** | Retreats, day-longs, multi-session study series, chanting series |
| Special Events | **Special Events** | One-offs: movie nights, game days, poetry, interfaith, service |
| Weekly Programs | **Regular Programs** | The seven weekly sits, plus monthly potluck |

Monthly gatherings the homepage doesn't categorize (Insight Dialogue, Women's Circle) go
under Special Events. The potluck lives in Regular Programs only.

**Repetition rule:** an event may appear at most twice — once in Featured (prose, persuasive)
and once in its list (scannable reference). Three appearances means it's in the wrong list.

**Featured Events header:** just "Featured Events" — no month/year in the label, since the
section can include a following-month event (e.g. a retreat) alongside the current month's.

**Colored background:** the tinted box (`#fffaf2`) belongs on **Featured Events**, the
persuasive/highlighted section. Retreats & Study, Special Events, and Regular Programs are
scannable reference lists and stay plain — don't move the tint back onto them.

**Regular Programs entries stay one line** (name + day/time), except Wednesday and Thursday,
which get one additional sentence covering the current book/series and, if known, what's
next — not a paragraph. If a refresh pulls in more detail than that, trim it back down rather
than including everything found on the event page.

## Recurring facts

- **Gareth Young** is the guiding teacher; he signs the Teacher's Note. The note is drafted
  for him but he should always review and rewrite before send — his name is on it.
- **Bashor Homeless Men's Shelter operates Nov 1 – Mar 31 only.** Include it in the
  Oct/Nov–Mar newsletters; leave it out Apr–Sep. Projects there: prepare 30+ daytime lunch
  sacks ahead, then reheat, plate, and serve on a Saturday evening.
- **Nicholas House** is the year-round service partner — "helps families experiencing
  homelessness achieve self-sufficiency" (their own mission language). Note: Red Clay's
  Community Service page still calls it "a rehabilitation center for unhoused families,"
  which is inaccurate; the newsletter intentionally departs from that wording.
- Other service partners not usually named: Atlanta Mission, Toco Hills Alliance, Casa Alterna.
- **Series to track across months:** Working with Mind (Yogacara, 5 sessions: Aug 1, Sep 5,
  Oct 3, Nov 7, Dec 5 in 2026) and Chanting with Gareth Young (7 sessions).

## Known site inconsistencies

Verify these rather than copying blindly:

- **Wednesday group start time** differs between the calendar (7:30 PM) and the Programs
  page (8:00 PM). Unresolved as of the August 2026 issue.
- The calendar has shown **Sunday Morning Meditation on non-Sunday dates** (e.g. Sat Aug 1,
  2026). Sanity-check weekday/date pairs.
- Event pages sometimes **stop publishing topics mid-month**. Say what's known and link out;
  don't invent chapters or topics to fill the gap.

## House style

- Never assert facts not on the site — no "space is limited," no invented registration
  urgency, no guessed dates.
- Quote sources properly: the Dhammapada reflection cites verse number and translator.
- Keep the existing inline-CSS table structure and the warm palette (`#8b3a2a`, `#d98c5f`,
  `#fbeee2`, `#fff5ea`). Inline styles only — no `<style>` blocks or external CSS.
- Event listings stay third person even though the note is first person.

### Link text conventions

- **Homepage link (`https://www.redclaysangha.org`):**
  - "Welcome page" when the sentence points somewhere ("visit our Welcome page for details").
  - "website" for generic action phrases ("log in to your account on our website," "join
    online... full details are also available on our website"). Don't use "homepage."
  - Keep the same label for the same phrasing pattern throughout the issue — it's the same
    URL every time, so an inconsistent label reads as a mistake.
- **Calendar link:** always its own link on "Calendar," never bundled with the homepage link
  under one combined label.
- **Featured Events:** end each blurb with "Learn more and register **here**," hyperlinked on
  "here."
- **Regular Programs (Wednesday/Thursday):** end with "Learn more **here**" (no "and
  register" — these are standing weekly sits, not registrations), hyperlinked on "here."
