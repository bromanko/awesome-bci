# Single-entry integration example

Saved research reused for one correction; no new entry research and no full-catalog freshness run. Real production history collection, Opus history review, patch/link checks and report rendering were exercised.

**1 ready for review · 0 held**

1 checked · 0 unchanged · 1 saved assessment reused · 0 source checks unavailable

<h2>PsychToolBox — Ready for maintainer review</h2>

```diff
--- a/README.md
+++ b/README.md
@@ -62,7 +62,7 @@
 * [NeuroPype](https://www.neuropype.io/): platform for real-time brain-computer interfacing (BCI), neuroimaging, and neural signal processing, which supports a range of biosignal modalities including EEG, fNIRS, ExG, etc.
 * [MNE](https://mne.tools/stable/install/mne_tools_suite.html): MNE-Python is an open-source Python module for processing, analysis, and visualization of functional neuroimaging data (EEG, MEG, sEEG, ECoG, and fNIRS). The tools suite includes interoperable packages in Python, MATLAB, C++, etc., which operate in GUI, CLI, or API.
 * [PsychoPy Builder](https://www.psychopy.org/builder/): PsychoPy is an open-source application for creating experiments in neuroscience, psychology, and psychophysics.
-* [PsychToolBox](http://psychtoolbox.org/): Psychophysics Toolbox Version 3 (PTB-3) is a free set of Matlab and GNU Octave functions for vision and neuroscience research.
+* [PsychToolBox](http://psychtoolbox.org/): Psychophysics Toolbox Version 3 (PTB-3) is an open-source set of Matlab and GNU Octave functions for vision and neuroscience research.
 * [VibeMyExpt](https://vibemyexpt.com/): Browser-based platform for building jsPsych experiments, with AI-assisted, editable code, that sends event markers to EEG, fNIRS and eye-tracking recordings through Lab Streaming Layer or USB TTL trigger boxes. Has a free plan.
 
 ### Matlab Toolboxes
```

<details>
<summary>Evidence and checks</summary>

<p>The site is live and relevant, but the &#x27;free set&#x27; claim is outdated. The official homepage now calls PTB-3 &#x27;an open-source set of Matlab and GNU Octave functions&#x27;. Official notices say that from Psychtoolbox 3.0.20, use on macOS and Windows needs a paid subscription license key after a 14-day free trial. The proposed text uses the official current wording.</p>

<p>https://psychtoolbox.org/ — &#x27;Psychophysics Toolbox Version 3 (PTB-3) is an open-source set of Matlab and GNU Octave functions for vision and neuroscience research.&#x27; The navigation links to a &#x27;Software License keys FAQ&#x27; and to psychtoolbox.net for licenses.</p>

<p>https://psychtoolbox.org/FreeTrialShutdown.html — April 2025 notice: free time-limited trials of Psychtoolbox 3.0.20 and later for macOS and Windows end 14 days after first use, after which &#x27;further use of the software will require a paid software subscription license key&#x27;.</p>

<p>https://psychtoolbox.org/PTB-3.0.22-Released.html — Psychtoolbox 3.0.22.3 was released on 14 August 2026, so the project is actively maintained.</p>

<p>Caveats: Licensing terms for Linux/Octave were not fully checked; they may differ from macOS/Windows.; The same project is also listed as id 75 under Matlab Toolboxes, a possible duplicate under the &#x27;Avoid duplicates&#x27; rule. Whether to keep both is left to the maintainer.</p>

<p>related: The search finished (complete=true) and found one record: PR #104, which was merged on 2026-11-09. That PR adds a new VibeMyExpt entry right after the PsychToolBox line in the BCI Experiment Design and Analysis section. In its patch, the PsychToolBox line only appears as unchanged context. It still reads &#x27;a free set of Matlab and GNU Octave functions&#x27;. So the PR does not change the description, URL or name of this entry, and it is not the same correction. It does not make the proposal obsolete, and it is not a competing open PR. The only review is a collaborator approval of the VibeMyExpt addition. Nobody objected to changing the PsychToolBox wording. The PR is still relevant context: the section around line 63 changed recently, so the proposed edit should be applied against the current README (the catalog SHA may need a refresh). Searches run: &#x27;PsychToolBox&#x27; and &#x27;http://psychtoolbox.org/&#x27; in NeuroTechX/awesome-bci and in bromanko/awesome-bci. Checks passed; existing unrelated link failures are listed separately.</p>

</details>

<details>
<summary>Saved review baseline</summary>

0 new completed reviews · 1 pending.

To retain completed reviews, review and commit the bundled `baseline.json` as `.um/freshness/baseline.json`.

</details>

<details>
<summary>Full research and run details</summary>

# Freshness research

Advisory only; every suggested change requires maintainer review.
No list edits, PRs, comments, or reviews were submitted.

Catalog revision: `14968c7e3c87a5ca07e9606f6b807c801e2c9c67`
Scope: one selected entry from saved research
Catalog recheck: unchanged

Sources below are agent-reported observations, not independent verification.

## Entry 65

<pre>PsychToolBox

The site is live and relevant, but the &#x27;free set&#x27; claim is outdated. The official homepage now calls PTB-3 &#x27;an open-source set of Matlab and GNU Octave functions&#x27;. Official notices say that from Psychtoolbox 3.0.20, use on macOS and Windows needs a paid subscription license key after a 14-day free trial. The proposed text uses the official current wording.

https://psychtoolbox.org/
&#x27;Psychophysics Toolbox Version 3 (PTB-3) is an open-source set of Matlab and GNU Octave functions for vision and neuroscience research.&#x27; The navigation links to a &#x27;Software License keys FAQ&#x27; and to psychtoolbox.net for licenses.
https://psychtoolbox.org/FreeTrialShutdown.html
April 2025 notice: free time-limited trials of Psychtoolbox 3.0.20 and later for macOS and Windows end 14 days after first use, after which &#x27;further use of the software will require a paid software subscription license key&#x27;.
https://psychtoolbox.org/PTB-3.0.22-Released.html
Psychtoolbox 3.0.22.3 was released on 14 August 2026, so the project is actively maintained.

Blocking uncertainties:
None reported.

Informational caveats:
Licensing terms for Linux/Octave were not fully checked; they may differ from macOS/Windows.
The same project is also listed as id 75 under Matlab Toolboxes, a possible duplicate under the &#x27;Avoid duplicates&#x27; rule. Whether to keep both is left to the maintainer.

Recommendation: update
Proposed name: None
Proposed URL: None
Proposed description: Psychophysics Toolbox Version 3 (PTB-3) is an open-source set of Matlab and GNU Octave functions for vision and neuroscience research.</pre>


</details>

Proposals only; no catalog edits or PRs submitted. Full records and checked patches are in the run artifacts.
