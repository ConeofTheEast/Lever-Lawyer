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
interactive demo, the three classes with anatomical figures, the arm as a lever,
external levers) and ends with a 7-question self-check. It is offered automatically
the first time a student creates their lawyer.

The textbook figures used in the review are in `img/`. If you do not have permission
to publish them, delete the files in `img/`; the pages still work (the diagrams drawn
in the game remain, the textbook pictures are simply hidden).
