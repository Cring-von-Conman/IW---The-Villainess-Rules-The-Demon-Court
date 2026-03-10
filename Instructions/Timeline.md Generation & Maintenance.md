# Instruction: Timeline.md Generation & Maintenance

## Purpose

Timeline.md is a linear, chronological record of story events — what has happened, what is happening now, and what is coming. It has exactly three sections: Past, Present, and Future. Within each section, entries run in strict chronological order, oldest at the top and most recent at the bottom.

---

## File Structure

Timeline.md must always begin with the following header block, updated with every batch:

```
# Timeline

**Last Updated:** Raw-[n]
**Current Story Date:** Day [n], Week [n]
```

Below the header, the file contains exactly three sections in this order:

```
## Past

[chronological entries, oldest at top]

---

## Present

[entries covering approximately one hour of story time centred on the current moment]

---

## Future

[chronological entries, nearest at top]
```

No other sections. No grouping within sections. No sub-headers. Each entry is a single line describing one event or development, with a time reference where known.

---

## Section Definitions

**Past:** Everything that has happened before the present window. The full history of the story from the beginning. Entries are never removed — they accumulate. As time passes in the story, entries that were in Present roll down into Past.

**Present:** Approximately one hour of story time, centred as closely as possible on the current moment. Should capture what is actively happening right now — where characters are, what they are doing, what has just resolved or just begun. As the story moves forward, entries leave Present and enter Past.

**Future:** Everything that is scheduled, committed to, or expected but has not yet happened, in the order it is expected to occur. When a future event happens, it leaves Future and eventually rolls through Present into Past. If timing is approximate or unconfirmed, note it inline.

---

## Update Rules

**Batch size:** Updates are performed in batches of exactly 5 raws. If fewer than 5 new raws exist, do not update Timeline.md yet. Wait until 5 are available.

**Each batch is presented in its own message for review.** After processing a batch of 5, present the updated Timeline.md and wait for confirmation before proceeding to the next batch. Do not process multiple batches in a single message.

**Always use raws, never chapters.** Chapter summaries are compressed and will have lost detail. Raws are the authoritative source.

**Always read the raw in full** before extracting timeline entries. Do not rely on memory of prior discussion.

**Order of operations for each raw in the batch:**

1. Read the raw in full.
2. Identify what has now happened that belongs in Past, what is currently happening that belongs in Present, and what is newly scheduled that belongs in Future.
3. Move any Present entries that are no longer current into Past.
4. Move any Future entries that have now occurred into Past (via Present if the raw captures the moment directly).
5. Add new entries to the appropriate section.
6. Update the current story date in the header if the raw crosses a day boundary.
7. Update the Last Updated field to reflect this raw before moving to the next.

---

## What Belongs in Timeline.md vs Other Documents

**Timeline.md:** Events — things that happen at a point in time. What occurred, when.

**Details.md:** Facts — things that are true about the world. How things work, what exists, what has been established as canon.

**Character files:** Character-specific status, traits, relationships, and history.

**Chapter summaries:** Narrative record of completed story beats in full.

When in doubt: if it happened at a specific moment, it is a timeline entry. If it is permanently true, it is a Details or Character entry.

---

## No Mutation Log

Timeline.md does not require a mutation log. Entries moving between sections and new entries being added is normal operation, not an exception.