# Instruction: Details.md Generation & Maintenance

## Purpose

Details.md is the canonical world-building and established facts document for this chronicle. It covers world mechanics, realm lore, magic systems, locations, and any facts that are significant enough to appear across multiple characters or scenes. Character-specific details belong in the relevant Character-[name].md file unless the detail is significant enough to warrant cross-referencing (e.g. a First Convergence event affects the whole world and should appear in both).

---

## File Structure

Details.md must always begin with the following header block, updated with every batch:

```
# World Details & Established Canon
**Raws Used:** Raw-1, Raw-2, Raw-3, ... [every raw scanned, in order]
**Last Updated:** Raw-[n]
```

The raws-used field must be updated as each individual raw is scanned — not at the end of the batch. This protects against partial updates if a session ends mid-batch.

---

## Update Rules

**Batch size:** Updates are performed in batches of exactly 5 raws. If fewer than 5 new raws exist, do not update Details.md yet. Wait until 5 are available.

**Always use raws, never chapters.** Chapter summaries are compressed and will have lost detail. Raws are the authoritative source.

**Always read the raw in full** before extracting details. Do not rely on memory of prior discussion.

**Order of operations for each raw in the batch:**

1. Read the raw in full.
2. Identify any new world details, canon facts, or mechanics introduced.
3. Check Details.md to confirm the detail is not already present.
4. If it is a new detail — add it to the appropriate section.
5. If it is a mutation of an existing detail — update the detail AND log the mutation at the bottom of the file (see Mutation Log below).
6. Update the Raws Used header to include this raw before moving to the next.

**Archived raws:** Details.md must be kept current enough that archived raws never need to be re-scanned. Do not archive raws that have not yet been processed into Details.md.

---

## Mutation Log

A Mutation Log section must be maintained at the bottom of Details.md. Format:

```
## Mutation Log

### [Topic]
- **Original:** [what the detail said before]
- **Mutated to:** [what it says now]
- **Raw where mutation occurred:** Raw-[n]
- **Notes:** [any relevant context]
```

If a detail evolves gradually across multiple raws, each stage of the mutation gets its own entry.

---

## What Belongs in Details.md vs Character Files

**Details.md:** World mechanics, realm lore, locations, magic systems, military assets, political structures, established canon facts that affect the world broadly, and any detail significant enough to appear across multiple characters or scenes.

**Character-[name].md:** Individual character traits, history, relationships, current status, and character-specific developments — unless the development is world-significant (e.g. a Convergence event, a bonding that changes the nature of power in the realm).

When in doubt: if only one character is affected, it goes in the character file. If the world is affected, it goes in Details.md.