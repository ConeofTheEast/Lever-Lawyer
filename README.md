# Lever Lawyer

A 2D courtroom game for reviewing the three lever classes of the human body (SEHS).
You defend a client against sham claims by building the joint as a see-saw lever and
showing the jury that the claim is physically impossible.

**Play:** https://coneoftheeast.github.io/Lever-Lawyer/

Works on desktop and phones (drag tokens, or tap a token and then a slot).
Progress is saved in the student's own browser (localStorage plus a cookie backup).

## For teachers
- Menu → **Submit results to teacher** gives each student a code (name, trial reached, accuracy by lever class).
- Menu → **Teacher tools** decodes pasted codes into a class table (copy as CSV) and edits custom claims.
- Custom claims can be shared with students using the share code in the editor.

The whole game is one file, `index.html`, with no build step or dependencies.

## Review section
Menu → **Review the basics** is a 13-page review built from the B1.4 Levers pre-reading
(what a lever is, parts, moment of force, effort/load arms, mechanical advantage with an
interactive demo, the three classes with anatomical figures, muscle-insertion diagrams,
the arm as a lever, external levers) and ends with a 7-question self-check. It is offered automatically
the first time a student creates their lawyer.

The textbook figures used in the review are in `img/`. If you do not have permission
to publish them, delete the files in `img/`; the pages still work (the diagrams drawn
in the game remain, the textbook pictures are simply hidden).

## Keeping your character on another device
Progress is saved automatically in the browser you are using. To move it to a phone or
another Chromebook, open Menu → **Save / transfer my character** and use any of:
- **Copy code**, then paste it into **Load a character** on the other device
- **Copy link**: opening the link on the other device offers to load the character
- **Show QR code**: scan it with a phone camera
- **Download file** / **Load from file**

Loading a save replaces the character on that device, so save the old one first if you
want to keep it. Third-party code: `lib/qrcode.js` is qrcode-generator by Kazuhiko Arase (MIT licence).

## Anatomy diagrams
The review page **Where is the effort? Muscle insertions** has six simplified, original
diagrams (biceps, triceps, calf, quadriceps, neck, deltoid) with the muscle insertion
highlighted as the effort location. After a claim is resolved, a **See the anatomy**
button opens the matching diagram for claims about those joints.
