---
name: build-my-voice
description: Build a personal voice profile skill from the user's own writing. Use when the user wants Claude to sound like them, asks for a voice profile or a my-voice skill, says drafts do not sound like them, or uploads samples of their own writing to be analysed for voice.
---

# Build my voice

Turn this person's real writing into a skill file that makes you sound like them.

Do not skip steps. Do not write the file early. The whole thing falls apart if you
guess instead of reading what they actually wrote.

## Step 1: get the material

Ask for both of these. Wait for them. Do not start without them.

**Their writing.** Three to five finished pieces. Published posts, emails they are
proud of, something nobody ever saw. Around 2,000 words total, more is better.
Two rules to tell them:

- Finished writing only. Not notes, not half drafts.
- Mix it up. Something personal, something practical, something written for one
  particular person.

**A transcript of them talking.** Five minutes, voice memo on their phone, about
anything they care about. They paste it in or attach it. Their spoken voice is
looser than their written one and the gap between the two is where the good stuff is.

If they say they do not have a recording, tell them it is the single thing most
people skip and it is the thing that makes the profile sound alive. Offer to carry
on without it, but say what they are giving up. If they still say no, carry on.

While you are waiting, ask them two questions and nothing more:

- Any words they never want to see in their writing.
- Any hard rules they already know about themselves. For example no em dashes, no
  tidy lesson at the end.

## Step 2: find the patterns

You are a writing analyst. Do not tell them whether the writing is good. Find the
patterns. Be specific. Quote them back to themselves.

Report four things:

**Their sentences.** How long they run. Count, do not guess. Give the mean and say
what share sit under ten words. Where they break a long one. How they open a
paragraph and how they close it. Pull three real examples from what they sent.

**Their words.** The ones that show up more than once, including filler and small
joining words. What they say instead of the obvious formal word. Whether they used
anything from their own never list.

**How they handle themselves on the page.** Do they hedge or say it flat. Do they
interrupt themselves. Do they joke at their own expense. Do they ask questions or
make statements.

**Spoken against written.** What is in the transcript that never makes it into the
writing. This is usually the most useful part. Name it plainly.

## Step 3: make them argue with it

Do not move on by yourself. Hand them the analysis and say this, in your own words:

Read it out loud. Some of it will be right in a way that makes you uncomfortable.
Some of it will be plain wrong. Tell me which is which, and add anything I missed.

Wait for their corrections. Apply them exactly as given. Do not defend your
analysis, do not soften their edit, do not keep a pattern they told you to drop.

If they say "looks good" without changing anything, push once. Ask which single
line felt least like them. There is always one.

## Step 4: write the file

Only now. Write a file called `SKILL.md` with this shape:

    ---
    name: my-voice
    description: Write in my voice. Use whenever drafting or editing anything I will publish or send under my own name.
    ---

Then these sections, in this order, filled with what you found and what they corrected:

- **When to use this.** One short paragraph.
- **My rules.** Their hard nos. Short lines.
- **My sentences.** Real measured numbers, not vague advice. "Most sentences under
  12 words, one long messy one per paragraph" works. "Shorter sentences" does nothing.
- **Words I use.** Including the small ones. And what they say instead of the formal word.
- **Words I never use.**
- **How I handle myself on the page.**
- **Real lines of mine.** Three to seven actual sentences lifted from their writing,
  quoted exactly. Never invent one. Never tidy one up.
- **Check before you hand it back.** A short list they can run a draft against.

Keep the whole file under two pages. A long profile gets ignored.

Write it in their voice, not yours. This file is the first test of whether you were
paying attention.

## Step 5: package it

The folder must be called `my-voice` and the file inside it must be called `SKILL.md`.
Nothing else. Zip the folder, not the file.

    my-voice/
      SKILL.md

Give them the zip to download, then these steps, written plainly. Assume they have
never done this before:

1. Download the zip. Do not open it or unzip it.
2. Click your name at the bottom left, then Customize, then Skills.
3. Click the + button, then Create skill, then Upload a skill.
4. Choose the zip and make sure the switch next to it is on.
5. Start a new chat and ask for something you write often. Claude picks the skill up
   on its own. If it does not, say "use my my-voice skill".

## Step 6: make them test it

Tell them to ask you to write the same thing twice. Once with the skill on, once
with it off. A short post or an email, whatever they write most. Read both out loud.

If the skill version still sounds like a LinkedIn post, the file is too vague. Go
back and put numbers and real quoted lines in it.

## Rules for you while doing this

- Never invent a line and attribute it to them.
- Never fill a section with a plausible guess because the samples were thin. Say the
  samples were thin and ask for one more piece.
- Never write "authentic", "unique voice", or any of that. Describe the mechanics.
- If their writing contradicts itself, keep the contradiction. It is a pattern, not an error.
