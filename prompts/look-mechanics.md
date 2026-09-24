# Usagi directional look mechanics

User requests the folded-paw pose from looking.png. Use that stance for all sixteen directions; restore complete lower body/feet. No table, background, text, keyboard, book, or rod in shared look rows. Canonical neutral-cell.png supplies upright body height and baseline; sleeping idle is intentionally not a neutral gaze reference.

Keep feet, lower torso and folded paws anchored. Use natural head yaw and pitch with corresponding redraw of eyes, cheeks and mouth on the face. Preserve flat dark cartoon eyes, white highlights, brows and small mouth; no replacement white eyeballs or detached pupils. Ears follow slightly while preserving length and pink inner markings. Keep face volume and identity stable; do not rotate/warp the whole sprite.

000 up: face broadly frontal, chin/mouth lift and eyes look visibly toward top, ears follow slightly back. 090 screen-right: head turns toward viewer right, nose/mouth and eyes lie right of head center, far eye/cheek foreshorten. 180 down: chin and eye line lower, more crown shows, lowered eyelids and muzzle look visibly below. 270 screen-left: opposite 090, nose/mouth and eyes lie left of head center, far cheek foreshortens.

Sixteen poses proceed clockwise in even 22.5-degree steps: row 9 up through right to down-right; row 10 down through left to up-left. Feet never slide. Each neighbor changes head yaw/pitch by a small comparable amount. 157.5 to 180 and 337.5 to 000 must continue smoothly. No props or whole-body rotation; user folded paws remain consistent.
