---
title: Space AI Forum 2026
layout: default
---

<link rel="icon" href="{{ '/favicon.ico' | relative_url }}">

<script>
document.addEventListener('DOMContentLoaded', function(){
  const b = document.querySelector('.page-header .btn');
  if (!b) return;
  b.textContent = 'Call for Papers';
  b.href = 'https://openreview.net/group?id=SAF%2F2026%2FConference';
  b.target = '_blank';
  b.rel = 'noopener';
});
</script>

<style>
/* Hide the GitHub Pages footer */
.site-footer, .site-footer-credits, .site-footer-owner { display:none !important; }
</style>

<script>
document.addEventListener('DOMContentLoaded', function () {
  ['.site-footer', '.site-footer-owner', '.site-footer-credits']
    .forEach(sel => { const n = document.querySelector(sel); if (n) n.remove(); });
});
</script> 

<nav class="topnav" markdown="1">
[CFP](#call-for-papers) • [Dates](#important-dates) • [Submit](#submission) • [Program](#program) • [Reviewers](#call-for-reviewers) • [Contact](#contact)
</nav>

<style>
.topnav{position:sticky;top:0;z-index:9;background:#fff;text-align:center;padding:.5rem 0;border-bottom:1px solid #eaeaea}
.topnav a{margin:0 .35rem}
@media (max-width:640px){.topnav a{display:inline-block;margin:.2rem .45rem}}
</style>
<!-- Option A black
<style>
.page-header{
  background:#000 !important;
  background-image:none !important;
  color:#fff;
}
.page-header .project-name,
.page-header .project-tagline{color:#fff}
.page-header .btn{
  background:transparent;border:1px solid rgba(255,255,255,.9);color:#fff
}
.page-header .btn:hover{background:#fff;color:#000}
</style> -->

<!-- Option B image header -->
<style>
/* Image header with dark overlay for readability */
.page-header{
  background:
    linear-gradient(rgba(0,0,0,.55), rgba(0,0,0,.55)),
    url("{{ '/space_ai_forum_hero.jpg' | relative_url }}") center/cover no-repeat !important;
  color:#fff;
}
.page-header .project-name,
.page-header .project-tagline{color:#fff}
.page-header .btn{
  background:transparent;border:1px solid rgba(255,255,255,.9);color:#fff
}
.page-header .btn:hover{background:#fff;color:#000}
</style>
<!-- 
space_ai_forum_hero_3200x1200.jpg
Good: 2560 × 960 px
Minimum: 1920 × 720 px
JPEG at 75–85% quality. Target ≤ 600 KB.
-->

<style>
/* Section heading color */
.main-content h2,
.main-content h3 { color:#3d85c6; } 
</style>

## Overview
Space AI Forum gathers researchers and practitioners working on AI for satellites, planetary robotics, ground and flight segments, mission operations, and science data systems. The focus is practical exchange across algorithms, hardware, safety, and deployment.

## Primer

<iframe
  class="saf-pdf"
  src="https://mozilla.github.io/pdf.js/web/viewer.html?file={{ '/Space-AI-Forum-2026-Pre-Workshop-Overview-v01.pdf' | absolute_url | url_encode }}#pagemode=none&zoom=page-width">
</iframe>

<style>
.saf-pdf{width:100%;height:80vh;min-height:560px;border:1px solid #eaeaea}
@media (max-width:700px){.saf-pdf{height:65vh;min-height:420px}}
</style>

<!-- Inline PDF viewer
<div class="saf-pdf">
  <object
    data="{{ '/Space-AI-Forum-2026-Pre-Workshop-Overview-v01.pdf' | relative_url }}#toolbar=0&navpanes=0&zoom=page-width"
    type="application/pdf">
    <p>Your browser can’t display this PDF.
      <a href="{{ '/Space-AI-Forum-2026-Pre-Workshop-Overview-v01.pdf' | relative_url }}" target="_blank" rel="noopener">Open the PDF</a>
    </p>
  </object>
</div>

<style>
.saf-pdf{height:80vh;min-height:560px;margin:12px 0}
.saf-pdf object{width:100%;height:100%;display:block;border:1px solid #eaeaea}
@media (max-width:700px){.saf-pdf{height:65vh;min-height:420px}}
</style> -->

## Call for Papers
We welcome short papers reporting research, negative results with lessons, systems notes, or position pieces.

### Topics
- Autonomy for flight and surface assets
- On-board learning and inference on constrained hardware
- Sensing, perception, tracking, and navigation
- Verification, validation, testing, and runtime monitoring
- Robustness to faults, radiation, and anomalies
- Scheduling, planning, and resource management
- Communications, compression, and federated methods
- LLMs and agents for ops and ground tools
- Data pipelines from lab to orbit and surface
- Science applications in EO and planetary pipelines
- Mission science planning and data assimilation
- Ethics, safety, policy, and standards for AI in space

## Author kit
- Length 4–6 pages excluding references, PDF only
- Anonymity: double-blind. Remove names and affiliations
- License: CC BY 4.0 for camera-ready files
- Figures, tables, and links allowed
- Supplementary: optional PDF or single ZIP, anonymized
- Concurrent submissions: allowed only if the other venue permits. Disclose in the submission

## Important dates
- Location Online
- Time zone GMT
- Submissions open 1 Nov 2025
- Submission deadline 29 Jan 2026 23:59
- Notifications 17 Feb 2026
- Camera-ready 3 Mar 2026
- Event 14 Mar 2026

## Submission
- Space AI Forum Template: <a href="{{ '/saf2025_author_kit.zip' | relative_url }}" target="_blank" rel="noopener">download the author package (ZIP)</a> or <a href="https://www.overleaf.com/read/skcycybvfdjb#c4beb1" target="_blank" rel="noopener">clone the Overleaf template</a>
- Download the 1-page CFP (PDF): <a href="{{ '/Space_AI_Forum_2026_CFP.pdf' | relative_url }}" target="_blank" rel="noopener">Space_AI_Forum_2026_CFP.pdf</a>
- Submit on OpenReview: <a href="https://openreview.net/group?id=SAF%2F2026%2FConference" target="_blank" rel="noopener">start your submission</a>
- After acceptance, upload a camera-ready with author names. Authors are encouraged to post to arXiv and add the link on the OpenReview record

## Program
Target size 6–10 accepted papers  
Invited talks 1–2 speakers, 20–30 minutes plus Q&A  
Format single track, live video with recordings published afterward  
Detailed schedule will appear here after notifications

## Presentation
Each accepted paper gets a 10-minute talk and a 5-minute Q&A  
Slides or short video due one week before the event  
Recordings published for authors who opt in

## Tentative schedule (GMT)
15:00–15:10 Opening  
15:10–16:00 Paper session 1  
16:00–16:20 Invited talk  
16:20–16:30 Break  
16:30–17:20 Paper session 2  
17:20–17:45 Panel and Q&A  
17:45–18:00 Closing

## Committee
Program chair Prof. Sylvester Kaczmarek  
PC 6–10 reviewers drawn from academia and industry

## Registration and support
No required fee for the first edition  
Support the event via [Buy Me a Coffee](https://buymeacoffee.com/space.sylvester)

## Supporters
Thanks to attendees who choose to support the event  
Add your name at checkout and we will list it here if you wish

## Proceedings
Accepted PDFs remain public on OpenReview. A Zenodo community archive may be created for easy citation

## Call for reviewers
We welcome reviewers with expertise in space systems, robotics, autonomy, ML, and safety  
How to apply: email research@sylvesterkaczmarek.com with your homepage or Google Scholar and 3–5 keywords  
Service window Feb–Mar 2026. Expected load 2–3 papers

## Accessibility
Live captions will be enabled. If you need assistance, email research@sylvesterkaczmarek.com

## Policies
Be respectful and constructive. Harassment or discrimination is not tolerated  
Privacy notice: We collect only what is needed to run the event. Contact us for removal requests  
Recording consent: Speakers and authors will be asked to opt in before recording  
Conflicts: Reviewers must recuse themselves from papers with conflicts such as same institution, adviser or advisee, recent coauthor, or close collaborator

## Contact
Email research@sylvesterkaczmarek.com

<footer class="saf-footer">
  <img class="saf-logo" src="{{ '/space_ai_forum_logo.jpg' | relative_url }}" alt="Space AI Forum logo">
</footer>
<style>
.saf-footer{ text-align:center; margin:32px 0 36px; }
.saf-logo{
  display:block;
  margin:0 auto;
  height:72px;
  max-width:90vw;
  vertical-align:middle;
  filter:drop-shadow(0 1px 0 rgba(0,0,0,.12));
}
@media (min-width:900px){ .saf-logo{ height:88px; } }
</style>

<hr class="saf-hr">
<p class="saf-copy">Copyright © Space AI Forum {{ 'now' | date: '%Y' }}</p>

<style>
.saf-hr{border:0;border-top:1px solid #eaeaea;margin:24px 0 8px}
.saf-copy{margin:0;text-align:center;color:#6b7280;font-size:14px}
</style>
