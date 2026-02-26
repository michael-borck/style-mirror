# Style Mirror — Chat Prompt Guide

Use these prompts in **any** AI chat interface (ChatGPT, Claude, Gemini, etc.) to replicate the Style Mirror workflow without the app.

---

## Step 1: Extract Your Style DNA

Paste this prompt along with a sample of your writing (email, essay, blog post, etc.):

> You are an expert Writing Style Analyzer. Read the text I provide and extract a detailed "Style DNA" profile covering these dimensions:
>
> - **Tone**: The overall emotional register (e.g., casual, authoritative, playful, dry)
> - **Structure**: Sentence length, complexity, paragraph habits
> - **Vocabulary**: Word choice patterns (simple, academic, slang-heavy, domain-specific)
> - **Grammar**: Syntax quirks, use of passive/active voice, comma habits
> - **Quirks**: The human fingerprints — contractions, filler words, favourite transition phrases, anything that makes it *sound like a person*
>
> Here is my writing sample:
>
> [PASTE YOUR TEXT HERE]

Save the profile the AI gives you — you'll feed it back in Step 3.

---

## Step 2 (Optional): Mimic a Persona

Skip this if you used Step 1. Use this to write in the style of a famous author, character, or public figure instead:

> Build a detailed Writing Style Profile for **[NAME]**. Cover these dimensions:
>
> - **Tone**
> - **Structure**
> - **Vocabulary**
> - **Grammar**
> - **Quirks**
>
> Be specific — include signature phrases, rhythm patterns, and anything that makes their writing instantly recognisable.

---

## Step 3: Generate Content

Paste the style profile from Step 1 or 2, then add your request:

> Act as a professional Ghostwriter. I will give you a Style Profile and a writing request. You **must** match the style exactly.
>
> **STYLE PROFILE:**
> [PASTE THE PROFILE FROM STEP 1 OR 2 HERE]
>
> **REQUEST:**
> Write a [FORMAT] about: [TOPIC].
>
> Return only the content, formatted in Markdown.

Replace `[FORMAT]` with one of: paragraph, email, blog post, essay, tweet.
Replace `[TOPIC]` with whatever you need written.

---

## Tips

- **Iterate on the profile.** If the output doesn't sound right, edit the style dimensions and regenerate.
- **Combine sources.** Run Step 1 on several writing samples to get a richer profile.
- **Save your profile.** Keep it in a note so you can reuse it any time without re-analysing.
