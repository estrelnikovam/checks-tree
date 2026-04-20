# How to update rta-checks-tree.html using Claude

Use the prompts below to ask Claude to make changes to `rta-checks-tree.html`.  
Node path format: `Element name > Category > Check name` (e.g. `Glulam beam > ULS > Bending (pure)`).

---

## Update check status

> In `rta-checks-tree.html`, update the status of `[Element] > [Category] > [Check name]` to `[status]`.

Available statuses: `todo`, `methodology`, `analysis`, `dev`, `qa`, `export`, `review`, `done`, `onhold`.

**Example:**
> In `rta-checks-tree.html`, update the status of `Glulam beam > ULS > Bending (pure)` to `done`.

---

## Add a link to a check

> In `rta-checks-tree.html`, add a link to `[Element] > [Category] > [Check name]` pointing to `[url]`.

---

## Update an existing link

> In `rta-checks-tree.html`, update the link on `[Element] > [Category] > [Check name]` to `[new-url]`.

---

## Remove a link from a check

> In `rta-checks-tree.html`, remove the link from `[Element] > [Category] > [Check name]`.

---

## Add a new check

> In `rta-checks-tree.html`, add a new check `[Check name]` under `[Element] > [Category]`, after `[Sibling check name]`, with status `[status]`.

---

## Remove a check

> In `rta-checks-tree.html`, remove check `[Check name]` from `[Element] > [Category]`.

---

## Rename a check

> In `rta-checks-tree.html`, rename check `[Old name]` under `[Element] > [Category]` to `[New name]`.

---

## Bulk status update

> In `rta-checks-tree.html`, set status `[status]` on the following checks: `[Element] > [Category] > [Check name]`, `[Element] > [Category] > [Check name]`, ...

---

## Add a new load type

> In `rta-checks-tree.html`, add load type `[Load name]` under `[Element] > Load types`, with status `[status]`.

---

## Add a new element type

> In `rta-checks-tree.html`, add a new element type `[Element name]` under `[Beams | Columns | Slabs]` with the following checks: `[Category > Check name, status]`, ...

---

## Remove an element type

> In `rta-checks-tree.html`, remove the entire element `[Element name]` and all its checks.

---

## Add a ULS Fire section

> In `rta-checks-tree.html`, add a ULS Fire section under `[Element name]`, mirroring the ULS checks, with all statuses set to `[status]`.

---

## Move a check to a different category

> In `rta-checks-tree.html`, move check `[Check name]` from `[Element] > [Category]` to `[Element] > [New category]`, after `[Sibling check name]`.

---

## Link all checks of an element to a Confluence page

> In `rta-checks-tree.html`, link the ULS/SLS checks of `[Element name]` to the corresponding sections of `[Confluence page url]`. Mapping: `[Check name → Section name]`, ...
