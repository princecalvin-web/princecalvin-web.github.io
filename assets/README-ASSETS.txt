═══════════════════════════════════════════════
  PRINCE CALVIN — PORTFOLIO ASSETS
  How to add, replace, or remove files
═══════════════════════════════════════════════

📸  PROFILE PHOTO
───────────────────────────────────────────────
  Expected filename : prince-photo.jpg  (or prince-photo.jpg.png if Windows added double extension)
  Location          : this folder (assets/)
  Supported formats : .jpg  .jpeg  .png  .webp

  CURRENT FILE      : prince-photo.jpg.png  ✓ (active)

  To REPLACE your photo:
    Simply overwrite the existing photo file with your new one.
    If the new file has a different name, update src="" in index.html line ~129.

  To REMOVE / hide your photo:
    Open  index.html  and find this line:
      <img src="assets/prince-photo.jpg" ...
    Change it to:
      <!-- <img src="assets/prince-photo.jpg" ... /> -->
    The placeholder card will show automatically.

  To use a DIFFERENT filename (e.g. headshot.png):
    In index.html, change:
      src="assets/prince-photo.jpg"
    to:
      src="assets/headshot.png"

───────────────────────────────────────────────

📄  RESUME (PDF)
───────────────────────────────────────────────
  Expected filename : prince-calvin-resume.pdf
  Location          : this folder (assets/)

  To ADD your resume:
    Copy your PDF here and name it: prince-calvin-resume.pdf

  To REPLACE your resume:
    Simply overwrite prince-calvin-resume.pdf.

  To use a DIFFERENT filename (e.g. resume-v2.pdf):
    Open index.html and replace ALL occurrences of:
      assets/prince-calvin-resume.pdf
    with:
      assets/resume-v2.pdf

═══════════════════════════════════════════════
