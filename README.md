# Story Protocol - Combined Docs (Flat-File Version)

This repository contains a "flat-file" (single-file) version of the entire official [Story Protocol](https://storyprotocol.xyz/) documentation.

The primary purpose of this repo is to simplify the **indexing** process for AI tools like [Cursor](https://cursor.sh/) or similar assistants. Instead of indexing dozens of separate files across many folders, the AI can index this single, comprehensive file to get the full context of the entire documentation.

---

## 🚀 How to Use (Raw URL)

You likely do not need to clone this repository. To use this in your AI tool, simply provide the **Raw URL** of the file.

**Raw File URL:**

`https://raw.githubusercontent.com/E1eng/Docs-Story-Protocol/refs/heads/main/combined.md`

`https://raw.githubusercontent.com/E1eng/Docs-Story-Protocol/refs/heads/main/full-combined.md`

## 🤖 Cursor Implementation Tutorial

Here is how to teach the Cursor AI to use your combined docs file as its primary source of knowledge for Story Protocol.

### Step 0: Get Your Raw URL

Copy the **Raw File URL** from the section above. Make sure you have replaced the placeholders with your username and repo name.

### Step 1: Open the "Docs" Panel in Cursor

1.  Open your Cursor editor.
2.  Look at the setting panel.
3.  Jump to Indexing & Docs, click the **"Docs"** tab.

### Step 2: Add New Docs

1.  Click the **"Add new docs..."** button or the large `+` icon to add a new source.
2.  In the text box that appears, **paste the Raw URL** you copied from Step 0.

### Step 4: Name and Index

1.  After pasting the URL, Cursor will ask you to **provide a reference name** (an "alias" or "handle"). This is the most important part.
2.  Type a short, memorable name that starts with `@`.
    * **Recommended:** `@story` or `@storyprotocol`
3.  Click the **"Add"** or **"Done"** button.
4.  Once finished, you will see **`@story`** (or whatever you named it) appear in your list of active documentation. Ensure the checkbox next to it is ticked.

### Step 6: How to Use It (Verification)

Now, your Cursor AI is "smart" about Story Protocol. Let's test it:

1.  Go back to the **"Chat"** tab in the AI panel.
2.  In the chat box, type your alias, followed by a question.
3.  When you type `@`, Cursor will show an autocomplete menu—make sure you select your `@story` handle.

**Example Prompts:**

> `@story What is an IP Asset?`

> `@story Explain the difference between registerRootIp and registerIp.`

> `@story Give me a Typescript code example for registering a new IP.`

By using `@story`, you are explicitly telling the AI to **only use your documentation file** to find the answer. This will provide much more accurate and relevant responses than the AI's general knowledge.

---

## 📜 Source

This documentation was pulled and combined from the official docs Story Protocol:
[https://docs.story.foundation/]

