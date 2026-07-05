## Parth Dhanani

Learning Engineer & SCORM Team Lead at [Kidvento](https://kidvento.com). Based in Mysore, India. Eight years in eLearning — the last year leading a team of 8 shipping 100+ K-12 SCORM packages a year.

The tools in this repo came out of that pipeline. A freeze bug that took two days to find and ten minutes to fix became a build-time linter. A manual four-hour packaging step became a ten-minute script. A video that wouldn't play on low-bandwidth school networks became an adaptive-bitrate packager with no CDN dependency. Each one is the smallest thing that closed the gap.

### Repos worth opening

| Repo | What it does |
|---|---|
| **[scorm-kit](https://github.com/parthdhanani/scorm-kit)** | 9 subcommands: lint, a11y, diff, mock, rum, privacy, i18n, cmi5, report. 31/31 tests. Zero runtime deps. Catches the silent failure modes Storyline's publish step misses. |
| **[storycraft](https://github.com/parthdhanani/storycraft)** | Markdown storyboard → SCORM 1.2 package. Same input, byte-identical zip. 11/11 tests. [Try it in the browser.](https://psidex.com/demos/storycraft/playground.html) |
| **[xapi-doctor](https://github.com/parthdhanani/xapi-doctor)** | 30-rule xAPI 1.0.3 + cmi5 linter (26 xAPI rules + 4 cmi5). Pings LRS endpoints, validates auth, translates 4xx/5xx into plain English. 17/17 tests. Zero deps. |
| **[sb-translation-tool](https://github.com/parthdhanani/sb-translation-tool)** | Flask app that pushes translated storyboard text straight into a Storyline 360 `.story` file — Word doc or PPTX in, updated question text out. Born from doing this by hand across six languages. |

### Writing

**Project case studies**
- [How one freeze bug became a build pipeline — scorm-kit](https://psidex.com/case-studies/08_building_scorm_kit.html)
- [Cutting SCORM packaging from 4 hours to 10 minutes](https://psidex.com/case-studies/01_post_publish_automation.html)
- [Adaptive bitrate video inside a SCORM package, no CDN](https://psidex.com/case-studies/02_adaptive_video_packager.html)
- [The mid-interaction freeze — a duplicate `cmi.interactions.N.id` story](https://psidex.com/case-studies/04_freeze_bug.html)

**Essays**
- [Localising eLearning into six Indian languages](https://psidex.com/case-studies/05_localization_lessons.html)
- [Action Mapping in practice](https://psidex.com/case-studies/06_action_mapping_in_practice.html)
- [Working with subject-matter experts](https://psidex.com/case-studies/07_working_with_smes.html)

### Stack

JavaScript · Node.js · SCORM 1.2 · xAPI 1.0.3 · cmi5 · Articulate Storyline 360 · FFmpeg · Moodle · WCAG 2.2 AA

### Contact

Portfolio: [psidex.com](https://psidex.com) · LinkedIn: [dhananiparth](https://linkedin.com/in/dhananiparth) · Email: parth@psidex.com

Open to senior IC and lead-level roles — remote international or India-based with technical scope.
