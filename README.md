# Make Claude sound like you

Claude writes fine. It just does not write like you. This fixes that.

No coding. Nothing to install. You download a file, upload it into Claude, and turn
it on. If you can attach a photo to an email, you can do this.

Works on free, Pro and Max.

## What is in here

**`build-my-voice`** - the done for you version. You hand Claude your own writing.
It works out how you write, checks it with you, then writes your voice file for you.
Start here.

**`my-voice-template`** - the blank version. The same file, empty, if you would
rather fill it in yourself.

## What a "skill" is

A skill is a set of instructions you give Claude once, and it remembers them in
every chat. That is all. You upload it as a file, flick a switch, and it is on.

## Step 1: turn on file creation

Claude hides the Skills section until you do this.

1. Open Claude
2. Click your name at the bottom left, then **Settings**
3. Click **Capabilities**
4. Turn on **code execution and file creation**

## Step 2: download the file

1. Click the **download** folder at the top of this page
2. Click **build-my-voice.zip**
3. Click the download button (it looks like an arrow pointing down)

Leave the zip alone. Do not open it or unzip it. Claude wants it exactly as it is.

## Step 3: put it into Claude

1. In Claude, click your name at the bottom left, then **Customize**
2. Click **Skills**
3. Click the **+** button, then **Create skill**, then **Upload a skill**
4. Choose the zip you just downloaded
5. Make sure the switch next to it is on

That is the setup done. You never have to do this part again.

## Step 4: gather your writing

Find three to five pieces you actually wrote and finished. Published posts, emails
you are proud of, something nobody ever saw. Around 2,000 words in total is plenty.
More is better.

Two rules:

- Finished writing only. Not notes, not half drafts.
- Mix it up. Something personal, something practical, and something you wrote for
  one particular person.

Then the part most people skip. Record yourself talking for five minutes about
anything you care about. Just the voice memo app on your phone. You talk differently
from how you write, and the difference between the two is where your voice actually
lives.

Put it all somewhere you can copy from, or save it as one document.

## Step 5: open a new chat and ask

Start a **brand new chat**. A fresh one, so nothing from your old chats gets mixed in.

Paste your writing in, or attach it using the paperclip. Attach the voice memo too,
or paste the transcript if you have one.

Then type this:

> Use my build-my-voice skill.

Say the name out loud like that and it works every time. You can just type "build my
voice" and Claude will usually pick it up on its own, but naming it takes the guessing
out.

If your Claude shows a menu of your skills when you type `/`, you can choose it from
there instead. Same result.

You will know it worked because Claude starts asking you questions instead of writing
something. From there it walks you through the rest.

If it ignores you and just chats, check the switch next to the skill is still on.

## Step 6: argue with what it tells you

This is the step that makes the difference, and it is the one people skip.

Claude will come back with a page describing how you write. Some of it will be right
in a way that makes you a bit uncomfortable. Some of it will be plain wrong. It has
read five pieces of your writing, not your whole life.

Read it out loud. Then say what is wrong, in normal words:

> The bit about short paragraphs is right. The bit about me asking questions isn't,
> I do that when I talk, not when I write. Take it out. Also add: I never start a
> sentence with "because".

Keep going until it sounds like you. Two or three rounds is normal.

## Step 7: upload the file it gives you

When you are happy, Claude writes the file and hands you a zip called `my-voice.zip`.

Download it, then do **Step 3** again with this new zip. Customize, Skills, +,
Create skill, Upload a skill, switch it on.

Now every time you ask Claude to write something, it writes it your way.

## Step 8: check it actually worked

Ask Claude to write the same thing twice. Once with your skill switched on, once
with it off. A short post, an email, whatever you write most.

Read both out loud. You will hear it straight away.

If the one with your skill on still sounds like a LinkedIn post, your file is too
vague. Open it and get specific. "Shorter sentences" tells Claude nothing. "Most
sentences under 12 words, one long messy one every paragraph" tells it everything.

## If something goes wrong

**I can't find Skills anywhere.** Step 1 is not done. Turn on code execution and
file creation in Settings, Capabilities.

**The upload was rejected.** The zip has to hold one folder, and that folder has to
hold one file called `SKILL.md`, spelled exactly like that with the capitals. Like
this:

    my-voice/
      SKILL.md

If your zip looks different, that is the problem. Ask Claude to rebuild it.

**Claude is ignoring my skill.** Check the switch next to it is on, then say
"Use my build-my-voice skill" in the chat.

**It sounds like me but a bit dead.** You probably skipped the voice memo. Go back
and add it. It matters more than the writing samples.

## The fill it in yourself version

Download `my-voice-template.zip` from the **download** folder, unzip it, and open
`SKILL.md` in any text editor. Replace everything inside square brackets with your
own answers. Save it, zip the `my-voice` folder back up, and upload it the same way.

Ten minutes, if you already know how you write.

## Keeping it good

A voice file built from five pieces is a starting point, not a finished thing. Every
few months, hand Claude your newest writing and ask it to update the file. Your
voice moves. The file should follow it.
