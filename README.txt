NAVLE Seven-Week Rotation
=========================

A 49-day self-paced study plan for the NAVLE (North American Veterinary
Licensing Examination): one clinical module per day, organized into seven
thematic weeks, with a cumulative exam built into the schedule every
Saturday.

Live version
------------
https://claude.ai/code/artifact/83658d81-7d8c-480b-b5ce-17c7685adfcf

What's here
------------
index.html   The full study plan as a single, self-contained static page
             (no build step, no external dependencies beyond Google Fonts).
             Open it directly in a browser, or serve it with any static
             host.

What's on the page
-------------------
- The four-stage method used for every study day: outline, key clinical
  information, a 30-question quiz, and (Saturdays) a cumulative exam.
- The full 49-day schedule, grouped into 7 weeks:
    Week 1  Foundational sciences
    Week 2  Cardiovascular & respiratory
    Week 3  GI & hepatobiliary
    Week 4  Musculoskeletal, neurology & ophthalmology
    Week 5  Urinary, endocrine, dermatology & hematology
    Week 6  Theriogenology & neonatology
    Week 7  Infectious disease, public health & wrap-up
- A worked Day 1 preview (sample outline, key info, and two sample quiz
  questions with answers) showing the format the daily content follows.

Deploying to GitHub Pages
--------------------------
1. Create a new repository and add index.html to it.
2. In the repo's Settings > Pages, set the source to the branch and root
   folder containing index.html.
3. GitHub will publish the page at:
     https://<your-username>.github.io/<repo-name>/

Note on the daily automation
-----------------------------
The live version above is paired with a scheduled Claude session that
delivers each day's module and 30-question quiz automatically (8:00 PM
America/New_York), plus the Saturday cumulative exam. That automation runs
through Claude, not through this static page, so it will not carry over
if you host index.html independently on GitHub Pages -- what you get there
is the schedule and reference content, not the daily generation.

License
-------
No license specified. Add one (e.g. MIT) if you intend for others to
reuse this content.
