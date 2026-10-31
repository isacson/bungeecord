# bungeecord

Estimates how long it will take you to finish a list of tasks, and fits them around the meetings and appointments that happen at fixed times.

You give it your to-do list and how long each thing should take. It tells you when each one will be done and when you'll finish for the day. Meetings stay put at their times. Your other tasks fit into the gaps, and you can see how much free time you have left.

Everything happens in one web page. There's nothing to install and no account to create, and your list stays on your own computer.

---

## Getting started

1. Go to **https://github.com/isacson/bungeecord/blob/main/bungeecord.html**
2. Near the top right of the page, click the **Download raw file** button (a small arrow pointing down into a tray).
3. Find the downloaded file, **bungeecord.html**, in your Downloads folder. Move it somewhere easy to find, like your Desktop or Documents folder.
4. **Double-click** it. It opens in your web browser (Chrome, Safari, Edge or Firefox).
5. Bookmark the page so you can come back to it easily.

> Your list is saved inside your web browser on this computer. If you close the page and come back later, using the same browser on the same computer, your list will still be there.

---

## Planning your day

### 1. Check the start time

At the top, **Start Time** shows the current time and keeps itself up to date. If you want to plan from a different time, for example tomorrow at 9:00, click the time and change it. To go back to following the clock, click **Now**.

### 2. Add your tasks

1. Click the red **Add Task** button. On a computer, you can also press **⌘-1** (Mac) or **Ctrl-1** (Windows).
2. Type what the task is, for example "Answer email."
3. Enter how long you think it will take, in hours and minutes.
4. Leave **Fixed start time** empty for ordinary tasks. (It's for meetings; see below.)
5. Click **Add Task**, or press **Enter**.

Each task shows **Done by** and the time you'll finish it. Your overall finish time appears in red at the bottom.

The colored box with each task's length gives you a quick sense of size: **green** for short tasks (under 40 minutes), **orange** for medium ones, **red** for long ones.

### 3. Add meetings and appointments (things at a fixed time)

Some things have to happen at a particular time, like meetings, calls, school pickup or lunch with a friend. "Pin" these to their time so they stay where they belong.

**One at a time:** click **Add Task** as usual, and also fill in the **Fixed start time**.

**Several at once (the quick way):**

1. Click **Paste meetings**.
2. Type your meetings, or copy them from your calendar and paste them in. Put one per line, like this:
   ```
   9:30 Team meeting 30
   12–1pm Lunch with Sam
   3:00 Pick up kids 20
   ```
   Each line needs a **time** and a **name**. You can also add how long it lasts (`30`, `45 min`, `1h`), or give a time range like `2–3pm`. If you leave out the length, it's set to 30 minutes.
3. Below the box, check the preview to make sure each line was understood correctly. Lines without a time are skipped.
4. Click **Add**.

Pinned items have a **blue stripe** on the left and a 📌 pin. They show their start and end time, and they stay at that time no matter what you change elsewhere.

**How tasks and meetings fit together:**

- Your tasks fill the time around your meetings. If a task runs into a meeting, it pauses for the meeting and finishes afterward. The task then says **⏸ paused for** and the meeting's name, and its "Done by" time includes the meeting.
- Gray rows like **"40 minutes free"** show open time before a meeting. You could fit another task in there.
- A red **⚠️ overlaps** warning means two pinned items are scheduled at the same time.

---

## Changing things as your day goes on

| To do this… | …do this |
|---|---|
| **Mark a task done** | Tick the checkbox on the left. It fades out, and the times below it move earlier. |
| **Rename a task** | Click its name and type. |
| **Change how long a task takes** | Click the number in the colored box and type a new one. |
| **Reorder tasks** | Drag the ↕️ handle up or down. On a phone, press and hold the ↕️, then slide. |
| **Do a task after a meeting instead of before it** | Drag the task below the meeting. It will wait until the meeting is over. |
| **Change a meeting's time** | Click the time on the meeting's row and change it. |
| **Pin an ordinary task to its current time** | Click its faded 📌. |
| **Unpin a meeting** (make it an ordinary task) | Click its 📌. |
| **Delete one item** | Click the red ❌. |
| **Start a fresh list** | Click **Clear All Tasks**. You'll be asked to confirm first. |
| **Easier on the eyes at night** | Click **Toggle Dark Mode** at the bottom right. |

---

## Moving your list to another computer or browser

Your list lives in one browser on one computer. To take it somewhere else:

1. Click **Export these tasks** at the bottom of the page. This saves a file called **tasks.json** to your Downloads folder.
2. Get that file to the other computer, for example by emailing it to yourself.
3. On the other computer, open bungeecord.html and click **Choose File** under "Import a .json file…". Then pick tasks.json.

Importing **replaces** the list that's already on that computer. It doesn't add to it.

Exporting is also a handy way to keep a backup, or to save a "typical day" list you can reload whenever you like.

---

## Questions

**Does this send my information anywhere?**
No. The page works entirely on your own computer. Your tasks aren't uploaded or shared with anyone.

**My list disappeared!**
Make sure you're using the same browser on the same computer as before. Your list may also be lost if you clear your browser's history or "site data," or if you use a private or incognito window. Exporting your list now and then protects you against this.

**A pasted meeting got the wrong time.**
A time from 1:00 to 6:59 without "am" or "pm" is read as afternoon. Write `8am` or `8:00 AM` to be sure. You can also fix any time afterward by clicking it on the meeting's row.
