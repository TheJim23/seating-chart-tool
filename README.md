# 💍 Wedding Seating Chart Tool

A beautiful, fully offline drag-and-drop wedding seating chart — no account, no internet required (after first load), no data ever sent anywhere. Just open the file and go.

---

## Getting Started

1. **Open `seating_chart.html`** in any modern browser (Chrome, Firefox, Safari, Edge)
2. A **setup screen** will appear — fill in your names, date, venue, and how many tables you want to start with
3. Click **"Let's Go ✦"** and start building your seating chart!

---

## How To Use

### Adding Guests
- In the left sidebar, type a name (or comma-separated names for a group/party) in the **"+ Add New Party"** box and hit Enter or click **Add**
- Each entry becomes a draggable "party card" in the sidebar

### Seating Guests
- **Drag** a party card from the sidebar onto any table on the right
- Drag cards **between tables** to rearrange
- Drag a card back to the **sidebar** to unassign them

### Editing a Party
- Hover any party card to reveal the **✏️ edit** button
- Inside the editor you can:
  - **Rename** individual members
  - Set each member's **RSVP status** (✅ Confirmed / 🔲 Pending / ❌ Declined)
  - **Add** new members to the party
  - **↗ Split out** a single member into their own separate party card
  - Set **Side A / Side B** and add dietary or seating **notes**
  - **🗑 Delete** the entire party

### Managing Tables
- Click **＋ Add Table** to add more tables at any time
- Empty tables show a **🗑** button to delete them
- Click the **table number** (e.g. `TABLE 3`) to edit it inline — useful if your venue uses non-sequential numbering
- **Drag the ⠿ badge** on any table header to reorder tables on the floor
- Click any table's name field to give it a custom name (shown below the number)
- **Hide Full Tables** button dims fully-seated tables so you can focus on open spots

### Printing
- Click **🖨 Print List** to open the print dialog with a clean, card-per-table layout
- Each card shows the table number, optional name, and every seated guest listed individually
- Empty tables are excluded automatically
- The interactive UI is hidden during print — only the guest list cards appear on paper

### RSVP Color Coding
| Color | Meaning |
|-------|---------|
| 🟢 Green left border | Confirmed |
| 🟡 Amber left border | Partial / Mixed response |
| ⬜ Faint border | No response yet |

### Saving Your Work
- Click **💾 Save** at any time — it downloads an updated copy of `seating_chart.html`
- Re-open that downloaded file to pick up right where you left off
- The file is completely self-contained — share it with your partner or planner and they can open it too!

---

## Tips

- The capacity counter (e.g. `6/8`) turns **amber** at full capacity and **red** if over
- The "Side A / Side B" labels are fully generic — use them however makes sense for your event (family sides, friend groups, etc.)
- There's no limit on guests, tables, or saves

---

## Requirements

- Any modern web browser
- Internet connection only needed for the first load (to fetch fonts from Google Fonts) — after that it works offline

---

*Built with ♥ — no frameworks, no dependencies, just one HTML file.*
