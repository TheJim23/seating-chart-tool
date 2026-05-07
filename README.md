# Wedding Seating Chart Tool

A beautiful, fully offline drag-and-drop wedding seating chart — no account, no internet required (after first load), no data ever sent anywhere. Just open the file and go.

---

## Getting Started

1. **Open `seating_chart.html`** in any modern browser (Chrome, Firefox, Safari, Edge)
2. Edit the event name, date, and venue directly in the header
3. Add parties in the left sidebar and tables on the floor, then start dragging

---

## Features at a Glance

- Drag-and-drop party assignment to tables
- Individual seat assignment mode — click any table to open a circle view and assign specific seats to each guest within a party
- Round-table circle diagram for each table (also printable)
- Per-guest meal tracking (three configurable meal types + kids option)
- Dietary restriction flags with visual warnings
- Bride / Groom side labels and Wedding Party flag per party
- RSVP status per party (Confirmed ✅ / Mixed ⚠️ / Pending 🔲)
- Stagger layout toggle — offsets the middle column for a hexagonal table arrangement
- Hide Full Tables toggle to focus on open spots
- Table drag-to-reorder, inline number/name editing
- Sweetheart table display at the top of the floor
- Three print modes: guest list with meals, guest list only, table circle diagrams
- Save to file — downloads a self-contained HTML snapshot; re-open to resume exactly where you left off

---

## How To Use

### Adding Guests
- In the left sidebar, click **+ Add New Party**, type a name (or comma-separated names for a group), and press Enter or click **Add**
- Each entry becomes a draggable party card in the sidebar

### Seating Guests
- **Drag** a party card from the sidebar onto any table on the floor
- Drag cards **between tables** to rearrange
- Drag a card back to the **sidebar** to unassign

### Assign Seats Mode
- Click **Assign Seats** on any table card to open the seat view
- The table is shown as a circle diagram with numbered slots around it; neighboring tables appear at reduced scale to show context
- **Drag guests** from the pool panel (right side) onto specific seat slots
- Click the **✕** on a filled slot to un-assign that person back to the pool
- Click the neighboring table thumbnails to navigate to them

### Editing a Party
- Hover any party card to reveal the **✏️ edit** button
- Inside the editor you can:
  - Rename individual members and set their meal selection
  - Add dietary restriction notes (shown as ⚠️ warnings on the card)
  - Add new members or **↗ Split out** a member into their own separate party card
  - Set **Bride / Groom** side and toggle **Wedding Party** status
  - Add freeform seating notes
  - Delete the entire party

### Managing Tables
- Click **＋ Add Table** to add a table; empty tables show a **🗑** button to remove them
- **Drag the ⠿ handle** on any table header to move it to a different floor position
- Click the table number badge (e.g. `TABLE 3`) to edit the number inline
- Click the name field to give a table a custom name (e.g. "Head Table")
- The capacity counter (e.g. `6/8`) turns amber when full and red if over capacity

### Floor Layout
- Tables are arranged in a 3-column grid
- **⬡ Stagger** shifts the middle column down by half a row to create a hexagonal arrangement — useful for venues where round tables are offset

### Printing
- **🖨 List w/ Meals** — a card per table showing each seated guest with their meal badge
- **🖨 List w/o Info** — same layout but names only, no meal info
- **🖨 Print Diagrams** — a grid of round-table circle diagrams showing who sits where

### RSVP Color Coding
| Color | Meaning |
|-------|---------|
| 🟢 Green left border | Confirmed |
| 🟡 Amber left border | Partial / Mixed response |
| ⬜ Faint border | No response yet |

### Saving Your Work
- Click **💾 Save** at any time — it downloads an updated `seating_chart.html`
- Re-open that file to pick up right where you left off
- The file is completely self-contained — share it and anyone can open it

---

## Requirements

- Any modern web browser
- Internet connection only needed on first load (Google Fonts) — works fully offline after that

---

*Built with ♥ — no frameworks, no dependencies, just one HTML file.*
