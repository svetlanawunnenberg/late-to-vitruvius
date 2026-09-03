# Putting this on GitHub — the whole thing, step by step

No command line. You already have **GitHub Desktop** installed and you are
signed in, so this is about five minutes.

---

## Part 1 — publish the folder (GitHub Desktop)

1. Open **GitHub Desktop**.
2. Menu: **File → Add local repository…**
3. Choose this folder:
   `C:\Users\Svetlana\OneDrive\Desktop\late-to-vitruvius`
4. It will show you the list of files. There should be a first snapshot already
   made, called *"The game, first playable"*. If instead it shows unsaved
   changes, type a short summary in the box at the bottom left and click
   **Commit to main**.
5. Click the blue **Publish repository** button at the top.
6. In the box that appears:
   - **Name:** `late-to-vitruvius`
   - **Description:** *A racing game about the vocabulary of classical architecture*
   - **⚠️ UNTICK "Keep this code private."** This one has to be public, or the
     web link will not work. (The Fairfax wiki is the opposite — that one stays
     private. They are separate folders and separate repositories; nothing here
     touches it.)
7. Click **Publish repository**.

Done. The code is now on GitHub. But it is not yet a *link people can play*.

---

## Part 2 — turn on the web link (GitHub Pages)

This part is in the browser, and it is three clicks.

1. In GitHub Desktop: **Repository → View on GitHub**. Your browser opens.
2. On that page click **Settings** (the gear, along the top row of tabs).
3. In the left-hand column, click **Pages**.
4. Under **Build and deployment → Source**, leave it on **Deploy from a branch**.
5. Under **Branch**, change `None` to **`main`**, leave the folder as `/ (root)`,
   and click **Save**.
6. Wait about one minute, then reload that page. A green bar appears at the top
   with your link:

   ```
   https://svetlanawunnenberg.github.io/late-to-vitruvius/
   ```

That is the link. Send it to anyone. It works on a phone.

---

## Part 3 — every time you change something afterwards

1. Open GitHub Desktop. It will show what changed.
2. Type a short summary in the box at the bottom left.
3. Click **Commit to main**.
4. Click **Push origin** at the top.

The live link updates itself within a minute. There is no separate "upload"
step — pushing *is* publishing. (This is different from the Shared File Search,
where publishing is a hand copy. Here it is automatic, which is why the two
copies cannot drift apart.)

---

## Adding the illustrations later

Put the PNG files into the `assets` folder using the exact names listed in
`README.md`, then do Part 3. They appear in the game on their own — nothing in
the code needs to change, and any file you have not made yet keeps its drawing.

---

## Two things worth knowing

**The repository is public, so treat everything in it as published.** Never put
anything from the Fairfax archive, any client name, any project photograph or
any file from `Y:` or `Z:` into this folder. It is a game about Vitruvius and
nothing else.

**Nothing here is branded yet, on purpose.** Once Richard has read the term list
in the Scriptorium and is happy with it, we add a credit line and it becomes
something the firm can put its name to.
