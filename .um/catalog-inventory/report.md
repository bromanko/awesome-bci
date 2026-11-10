# Catalog review inventory

**42 proposed changes · 20 uncertain · 64 unresolved keeps**

232 entries researched. 106 saved reviews for recurring runs.

Research recommendations from the initial Opus review. The full set has not passed prior-discussion or patch validation. Proposed diffs are previews, not approved patches. Nothing was applied or submitted.

Catalog: `dc6d64998a69325f5fff748935c919aabf0d7e44` · README SHA-256: `2aaebe383de2309e78c7204fbdb80d434c395cadaa4e631aac279be82f36a749`

## Proposed changes

<h3>PsychToolBox — update</h3>

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
<summary>Evidence and limitations</summary>

<p>The site is live and relevant, but the &#x27;free set&#x27; claim is outdated. The official homepage now calls PTB-3 &#x27;an open-source set of Matlab and GNU Octave functions&#x27;. Official notices say that from Psychtoolbox 3.0.20, use on macOS and Windows needs a paid subscription license key after a 14-day free trial. The proposed text uses the official current wording.</p>

<p>https://psychtoolbox.org/ — &#x27;Psychophysics Toolbox Version 3 (PTB-3) is an open-source set of Matlab and GNU Octave functions for vision and neuroscience research.&#x27; The navigation links to a &#x27;Software License keys FAQ&#x27; and to psychtoolbox.net for licenses.</p>

<p>https://psychtoolbox.org/FreeTrialShutdown.html — April 2025 notice: free time-limited trials of Psychtoolbox 3.0.20 and later for macOS and Windows end 14 days after first use, after which &#x27;further use of the software will require a paid software subscription license key&#x27;.</p>

<p>https://psychtoolbox.org/PTB-3.0.22-Released.html — Psychtoolbox 3.0.22.3 was released on 14 August 2026, so the project is actively maintained.</p>

<p>Caveats: Licensing terms for Linux/Octave were not fully checked; they may differ from macOS/Windows.; The same project is also listed as id 75 under Matlab Toolboxes, a possible duplicate under the &#x27;Avoid duplicates&#x27; rule. Whether to keep both is left to the maintainer.</p>

<p>Independent source check: The catalog&#x27;s unqualified free claim is outdated for current macOS/Windows use. Official homepage now uses open-source wording; the April 2025 notice requires paid subscription keys after a 14-day trial for version 3.0.20+. The proposed free-to-open-source substitution is a narrow, supported correction.</p>

<p>https://psychtoolbox.org/ — Homepage describes PTB-3 as open-source Matlab/GNU Octave functions for vision and neuroscience.</p>

<p>https://psychtoolbox.org/FreeTrialShutdown.html — Official April 11, 2025 notice gives the macOS/Windows paid-key requirement after trials for 3.0.20 and later.</p>

<p>https://github.com/Psychtoolbox-3/Psychtoolbox-3/wiki/FAQ#free-student-licenses — FAQ still identifies a free current GNU Octave/Linux X11 variant and free older unsupported releases. Do not claim that every variant is paid.</p>

</details>

<h3>Chronux — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -73,7 +73,7 @@
 * [BBCI](https://github.com/bbci/bbci_public)
 * [ERPLAB](https://erpinfo.org/erplab)
 * [Psychtoolbox](http://psychtoolbox.org)
-* [Chronux](https://brainarchitecture.org/)
+* [Chronux](https://chronux.org/)
 
 ### Python Toolboxes
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL is wrong. brainarchitecture.org is the Brain Architecture Project&#x27;s site (connectivity atlases and viewers), and its homepage does not mention Chronux. Chronux&#x27;s own homepage is chronux.org. It describes Chronux as an open-source MATLAB library for neural data analysis, which fits the Matlab Toolboxes section. The catalog entry has no description, so only the URL needs to change.</p>

<p>https://brainarchitecture.org/ — The page title is &#x27;Index - Brain Architecture Project&#x27; and the tagline is &#x27;Uncovering the blueprint of the brain, across multiple species&#x27;. The navigation covers mouse/marmoset/human projects, atlases and toolboxes. The fetched HTML contains no mention of Chronux.</p>

<p>https://chronux.org/ — http://chronux.org/ redirects to https://chronux.org/. The page says: &#x27;Chronux is an open-source software package for the analysis of neural data... originally developed... at the Mitra Lab in Cold Spring Harbor Laboratory... The current release of Chronux is implemented as a Matlab library.&#x27; Downloads list version 2.12 v03 (2018-Oct-25), plus a manual and tutorials.</p>

<p>Caveats: The latest release on chronux.org is dated 2018. The contribution rules ask for actively maintained resources, but that is a separate curation judgment from fixing the URL.; Chronux is a general neural-data analysis toolbox, not a BCI-specific one. It sits in a list section of generic MATLAB toolboxes.</p>

</details>

<h3>BioSPPy — replace</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -87,7 +87,7 @@
 * [OpenNFB](https://github.com/strfry/OpenNFB)
 * [bcikit](https://github.com/octopicorn/bcikit)
 * [PsychoPy](https://www.psychopy.org/)
-* [BioSPPy](https://github.com/PIA-Group/BioSPPy)
+* [BioSPPy](https://github.com/scientisst/BioSPPy)
 * [Timeflux](https://timeflux.io)
 * [EEGsynth](https://github.com/eegsynth/eegsynth)
 * [pyRiemann](https://github.com/pyRiemann/pyRiemann)
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed PIA-Group/BioSPPy repository was archived on Aug 2, 2022. Its README states that the toolbox is now maintained at scientisst/BioSPPy. That is an official successor declaration by the original project. PyPI &#x27;biosppy&#x27; now names scientisst/BioSPPy as its homepage and released 2.2.4 in 2025. The name stays BioSPPy.</p>

<p>https://github.com/PIA-Group/BioSPPy — The page shows &#x27;archived by the owner on Aug 2, 2022&#x27;.</p>

<p>https://raw.githubusercontent.com/PIA-Group/BioSPPy/master/README.md — The first line reads: &#x27;&gt; This repository is archived. The BioSPPy toolbox is now maintained at [scientisst/BioSPPy](https://github.com/scientisst/BioSPPy).&#x27; The README also lists EEG and EMG among supported biosignals.</p>

<p>https://github.com/scientisst/BioSPPy — Returns 200 with the title &#x27;scientisst/BioSPPy: Biosignal Processing in Python&#x27;. The commits feed on main shows an update on 2026-09-17.</p>

<p>https://pypi.org/pypi/biosppy/json — PyPI home_page and project_urls point to https://github.com/scientisst/BioSPPy. The latest version is 2.2.4, uploaded 2025-11-07.</p>

<p>Caveats: BioSPPy is a general biosignal toolbox, with EEG as one of several supported signals. That was already the case for the listed entry.; The archived PIA-Group repository remains readable, and its code remains usable as a historical snapshot.</p>

</details>

<h3>Google Play Store — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The link text &#x27;Google Play Store&#x27; is wrong. The URL points to the pwittchen/neurosky-android-sdk GitHub repo, which is an Android SDK library published to Maven Central, not a Play Store app. The SDK still fits as BCI software, but its home in &#x27;Mobile Apps&#x27; is debatable. Suggest relabelling the link as the GitHub repository.</p>

<p>https://github.com/pwittchen/neurosky-android-sdk — The canonical repo resolves and is not archived. The description reads &#x27;Android SDK for the NeuroSky MindWave Mobile Brainwave Sensing Headset&#x27;.</p>

<p>https://raw.githubusercontent.com/pwittchen/neurosky-android-sdk/master/README.md — The README describes a Java/Kotlin (RxJava) SDK for writing Android apps for the MindWave Mobile, with a Maven Central download badge. It never mentions a Google Play Store listing.</p>

<p>https://github.com/pwittchen/neurosky-android-sdk/commits.atom — The latest commit is dated 2020-08-19.</p>

<p>Caveats: This is a prose-prefixed complex entry (&#x27;NeuroSky Android SDK: [Google Play Store](...)&#x27;), so the maintainer needs to edit the link label by hand.; Last commit was in 2020. Did not check whether it builds against current Android toolchains, and maintenance status cannot be inferred from that alone.</p>

</details>

<h3>Google Play Store — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The &#x27;(Now-deprecated)&#x27; prefix is accurate: the repo was archived in April 2021 and its README says the app was removed from Google Play after Interaxon withdrew its Muse SDK. But the link text &#x27;Google Play Store&#x27; is false, because the link goes to the GitHub repo and no Play listing exists. Suggest relabelling it as GitHub. The README names EEGEdu as its &#x27;spiritual successor&#x27;, which the maintainer could optionally note; that is not a formal replacement of this implementation.</p>

<p>https://github.com/NeuroTechX/eeg-101 — Repository NeuroTechX/eeg-101 shows &#x27;archived by the owner on Apr 13, 2021. It is now read-only.&#x27;</p>

<p>https://raw.githubusercontent.com/NeuroTechX/eeg-101/master/README.md — &#x27;EEG 101 is dead... we have stopped development here and removed the app from the Google Play Store.&#x27; It recommends EEGEdu (github.com/kylemath/EEGEdu) as the spiritual successor. The tutorial content still covers EEG and BCI basics.</p>

<p>Caveats: This is a prose-prefixed complex entry, so the label edit has to be done by hand.; The repo still has educational value as a dated reference. Did not evaluate EEGEdu&#x27;s current status.</p>

</details>

<h3>ads1299-linux — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -117,7 +117,7 @@
 * [PiEEG](https://pieeg.com/)
 * [Blino PiNaps](https://github.com/BlinoTech/BlinoTech.github.io)
 * [IntelliPi](https://github.com/AtlantsEmbedded/IntelliPi)
-* [ads1299-linux](https://github.com/stephan-biomedical-engineer/ads1299-linux) - Linux kernel (IIO) driver for the TI ADS1299 EEG front-end on SPI, with a Raspberry Pi overlay; out of tree, with mainline support in progress.
+* [ads1299-linux](https://github.com/stephan-biomedical-engineer/ads1299-linux) - Linux kernel (IIO) driver for the TI ADS1299 EEG front-end on SPI, with a Raspberry Pi overlay; out of tree and being prepared for mainline submission.
 
 ### Communication Protocols
 
```

<details>
<summary>Evidence and limitations</summary>

<p>Most of the description is confirmed: an IIO driver for the TI ADS1299 on SPI, a Raspberry Pi devicetree overlay, and an out-of-tree build. But &#x27;mainline support in progress&#x27; overstates things. The README&#x27;s Upstream status section says &#x27;Not submitted yet&#x27; and that the series is being prepared for submission. Suggest more precise wording.</p>

<p>https://github.com/stephan-biomedical-engineer/ads1299-linux — The canonical repo resolves and is not archived. The description reads &#x27;Linux IIO driver for the TI ADS1299, ADS1299-6 and ADS1299-4... being prepared for upstream submission&#x27;.</p>

<p>https://raw.githubusercontent.com/stephan-biomedical-engineer/ads1299-linux/main/README.md — Under &#x27;Upstream status&#x27; it says &#x27;**Not submitted yet.** The series (binding, driver, ABI document) will be posted to the linux-iio and devicetree mailing lists.&#x27; The driver has been built and run on Raspberry Pi OS 6.18.</p>

<p>https://raw.githubusercontent.com/stephan-biomedical-engineer/ads1299-linux/main/dts/README.md — Documents ads1299-overlay.dts for the Raspberry Pi (SPI0 wiring, dtoverlay=ads1299).</p>

<p>https://github.com/stephan-biomedical-engineer/ads1299-linux/commits.atom — The latest commit is dated 2026-10-20.</p>

<p>Caveats: Upstream status is likely to change once the series is posted. The suggested wording avoids a point-in-time claim of active review.; Did not build or run the driver.</p>

</details>

<h3>Open Sound Control — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -124,7 +124,7 @@
 These are some of the commonly used Communication protocols.
 
 * [Lab Streaming Layer](https://github.com/sccn/labstreaminglayer)
-* [Open Sound Control](http://www.opensoundcontrol.org/)
+* [Open Sound Control](https://opensoundcontrol.stanford.edu/)
 * [FieldTrip buffer](https://www.fieldtriptoolbox.org/development/realtime/buffer_protocol/)
 
 ## Hardware
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL http://www.opensoundcontrol.org/ now 301-redirects to the generic CCRMA homepage (https://ccrma.stanford.edu/), not to OSC content. The official OSC site is at https://opensoundcontrol.stanford.edu/. OSC is still relevant: Muse tools such as Mind Monitor stream EEG over OSC.</p>

<p>http://www.opensoundcontrol.org/ — The server returns &#x27;301 Moved Permanently&#x27; with &#x27;location: https://ccrma.stanford.edu/&#x27;, which is the CCRMA landing page rather than an OSC page.</p>

<p>https://opensoundcontrol.stanford.edu/ — The page is &#x27;OpenSoundControl.org&#x27;. It hosts the OSC 1.0/1.1 specs, implementations and publications, and describes OSC as a data transport specification for realtime message communication developed at CNMAT.</p>

<p>https://apps.apple.com/ca/app/mind-monitor/id988527143 — Mind Monitor advertises &#x27;stream over OSC&#x27;, confirming OSC is used in the BCI tooling context.</p>

<p>Caveats: The name &#x27;Open Sound Control&#x27; is unchanged. Only the URL needs correcting.</p>

</details>

<h3>Kernel Flow — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -138,7 +138,7 @@
 Some of these devices are still supported and actively developed by manufacturers, community members, or researchers. Others are no longer supported but may still have a community of users who can help you get access.
 
 * [Synchron Stentrode](https://synchron.com/): An investigational, minimally invasive BCI that is implanted into a blood vessel in the brain without open-brain surgery, enabling paralyzed individuals to control digital devices.
-* [Kernel Flow](https://www.kernel.com/flow): Non-invasive, light-based neuroimaging (TD-fNIRS) system used for wellness tracking, cognitive function assessment, and mental health monitoring.
+* [Kernel Flow](https://www.kernel.com/developers): Wearable, light-based time-domain fNIRS (TD-fNIRS) neuroimaging system for research on cognition, mental health and human performance.
 * [Neurable MW75 Neuro & HyperX Gaming Headset](https://www.neurable.com/): Non-invasive BCI technology integrated into high-end headphones and gaming headsets, providing real-time insights into focus and cognitive load.
 * [Neurosity Crown](https://neurosity.co/): Third-generation BCI with high-fidelity EEG signal processing and embedded edge computing for real-time data analysis.
 * [Blackrock Neurotech MoveAgain & Axon-R](https://blackrockneurotech.com/): MoveAgain is an advanced clinical BCI system (implanted electrode array) for paralyzed users, while Axon-R is a non-invasive AR-enabled BCI headset.
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL https://www.kernel.com/flow returns 404 and is not in Kernel&#x27;s sitemap. Kernel Flow (now Flow 2) is documented at kernel.com/developers. The description is partly out of date: Kernel now says its systems are &#x27;for research use only&#x27; and &#x27;not intended to diagnose, treat, or manage any disease&#x27;, and presents Flow as a research neuroimaging system, so &#x27;wellness tracking&#x27; and &#x27;mental health monitoring&#x27; are not supported.</p>

<p>https://www.kernel.com/flow — Returns HTTP 404.</p>

<p>https://www.kernel.com/developers — &#x27;Kernel Flow delivers fast, high-density brain data... for AI approaches to advance neuroscience, cognition, mental health, and human performance research.&#x27; Describes Kernel Flow 2 as a second-generation system with 40 TD-fNIRS modules plus 6 dry EEG electrodes, SNIRF output and a real-time SDK.</p>

<p>https://www.kernel.com/technology — Describes Flow as a time-domain fNIRS system with 3500 measurement channels enabling whole-head TD-DOT.</p>

<p>https://www.kernel.com/ — &#x27;Kernel systems are for research use only... not intended to diagnose, treat, or manage any disease.&#x27; The sitemap lists /, /about, /contact, /developers, /participate, /press and /technology, with no /flow page.</p>

<p>Caveats: Kernel Flow is TD-fNIRS (Flow 2 adds EEG electrodes), so its placement under EEG / Consumer and DIY Devices is questionable, given that a NIRS section exists. Relocation is a maintainer decision.; The name could optionally become &#x27;Kernel Flow 2&#x27;, but &#x27;Kernel Flow&#x27; is still the product family name.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Blackrock Neurotech MoveAgain &amp; Axon-R — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -141,7 +141,7 @@
 * [Kernel Flow](https://www.kernel.com/flow): Non-invasive, light-based neuroimaging (TD-fNIRS) system used for wellness tracking, cognitive function assessment, and mental health monitoring.
 * [Neurable MW75 Neuro & HyperX Gaming Headset](https://www.neurable.com/): Non-invasive BCI technology integrated into high-end headphones and gaming headsets, providing real-time insights into focus and cognitive load.
 * [Neurosity Crown](https://neurosity.co/): Third-generation BCI with high-fidelity EEG signal processing and embedded edge computing for real-time data analysis.
-* [Blackrock Neurotech MoveAgain & Axon-R](https://blackrockneurotech.com/): MoveAgain is an advanced clinical BCI system (implanted electrode array) for paralyzed users, while Axon-R is a non-invasive AR-enabled BCI headset.
+* [Blackrock Neurotech MoveAgain & Axon-R](https://blackrockneurotech.com/): MoveAgain is Blackrock's upcoming implanted (Utah Array-based) BCI system for people with paralysis, with FDA Breakthrough Device designation; Blackrock also distributes Cognixion's non-invasive, AR-enabled Axon-R EEG headset for research.
 * [Muse 2016, Muse 2, Muse S](https://choosemuse.com/)
 * [OpenBCI Ganglion, Cyton, Daisy, Galea](https://openbci.com/)
 * [IDUN Guardian](https://iduntechnologies.com/idun-guardian)
```

<details>
<summary>Evidence and limitations</summary>

<p>The description says Axon-R is Blackrock&#x27;s product, which is wrong. Axon-R is Cognixion&#x27;s wearable AR+EEG BCI. Blackrock only distributes it, under a non-exclusive deal announced in May 2025. Blackrock&#x27;s own site does not list Axon-R at all. Blackrock&#x27;s tech page calls MoveAgain its &#x27;upcoming&#x27; medical device, built on the Utah Array, with FDA Breakthrough Device designation (2021). So &#x27;advanced clinical BCI system&#x27; overstates its status.</p>

<p>https://blackrockneurotech.com/our-tech/ — Says the Utah Array &#x27;is the core technology in our upcoming MoveAgain medical device, which received a Breakthrough Designation from the FDA in 2021.&#x27;</p>

<p>https://blackrockneurotech.com/products/ — The research product catalog lists NeuroPort, Cerebus, Utah Array, CereStim, CerePlex and NeuroSnap. Axon-R is not listed. The site&#x27;s WordPress search API returns no results for &#x27;axon-r&#x27;.</p>

<p>https://www.cognixion.com/blog/2025/5/12/cxnnews — Cognixion press release dated May 14, 2025: &#x27;Blackrock Neurotech ... will offer Cognixion&#x27;s Axon-R wearable neural interface platform to research institutions through its distribution network&#x27;. It also says the two companies &#x27;maintain independent&#x27; operations.</p>

<p>https://blackrockneurotech.com/ — Plain curl got HTTP 406 from mod_security. Retrying with browser headers returned 200 with the homepage, which focuses on implanted BCIs for paralysis.</p>

<p>Caveats: The section is &#x27;Consumer and DIY Devices&#x27;, and neither an investigational implant nor a research-distributed headset clearly fits it. Where the entry should live is a maintainer decision.; The entry name also implies Axon-R is a Blackrock product. Splitting it into a Cognixion Axon-R entry would mean manual editing.; Cognixion&#x27;s own Axon-R product page was not read. Only its press release was.</p>

</details>

<h3>Dreem by Beacon Biosignals — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -147,7 +147,7 @@
 * [IDUN Guardian](https://iduntechnologies.com/idun-guardian)
 * [BrainBit Headband & Flex](https://brainbit.com/)
 * [Emotiv EPOC, Flex, Insight](https://www.emotiv.com/)
-* [Dreem by Beacon Biosignals](https://beacon.bio/dreem-3s)
+* [Waveband (formerly Dreem 3S) by Beacon Biosignals](https://beacon.bio/waveband)
 * [CGX (formerly Cognionics)](https://cgxsystems.com/): Research-grade dry-electrode EEG systems.
 * [Elemind](https://elemindtech.com/)
 * [Neurosky](https://neurosky.com/)
```

<details>
<summary>Evidence and limitations</summary>

<p>Beacon Biosignals renamed the Dreem 3S to Waveband. The listed URL beacon.bio/dreem-3s now redirects to beacon.bio/waveband, and that page refers to &#x27;the Waveband (then called Dreem 3S)&#x27;. A rename to the current official name and URL is supported.</p>

<p>https://beacon.bio/waveband — https://beacon.bio/dreem-3s redirects here. The page title is &#x27;Waveband: FDA-Cleared EEG Headband | Beacon Biosignals&#x27;. It says &#x27;the Waveband (then called Dreem 3S) achieves a level of measurement as accurate as polysomnography&#x27;, and specs list 5 EEG channels with raw EDF output.</p>

<p>https://beacon.bio/news/fda-authorizes-beacon-s-dreem-3s-as-first-sleep-wearable-with-predetermined-change-control-plan-paving-the-way-for-continuous-algorithm-enhancements-in-sleep-monitoring — Found in search results only, not read. It is Beacon&#x27;s own news item on the Dreem 3S FDA PCCP authorization, which supports the device&#x27;s history under the old name.</p>

<p>Caveats: Waveband is positioned for clinical trials and home sleep testing, not as a consumer device, so its fit in &#x27;Consumer and DIY Devices&#x27; is debatable.; The section is not currently alphabetical, so moving from &#x27;D&#x27; to &#x27;W&#x27; creates no new ordering conflict. The maintainer may still want to reposition it.; A search summary said the name change happened in June 2025, but Beacon&#x27;s dated rename notice was not read directly.</p>

</details>

<h3>Shimadzu — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -192,7 +192,7 @@
 * [CortiVision](https://www.cortivision.com/)
 * [Hitachi Hightech](https://www.hitachi-hightech.com/global/en/products/ict-solution/)
 * [NIRx](https://nirx.net/)
-* [Shimadzu](http://www.ssi.shimadzu.com/products/productgroup.cfm?subcatlink=tissueimaging)
+* [Shimadzu](https://www.shimadzu.com/an/products/life-science-lab-instruments/imaging/index.html)
 * [Kernel Flow](https://www.kernel.com): EEG + TD-fNIRS
 
 ### Multimodal Neurotech
```

<details>
<summary>Evidence and limitations</summary>

<p>The old Shimadzu tissue-imaging URL now redirects to a generic analytical-instruments index that never mentions NIRS, so the link no longer shows Shimadzu&#x27;s NIRS products. Shimadzu Corporation&#x27;s official Imaging category page lists both of its current fNIRS systems, LABNIRS and LIGHTNIRS, so it is a good replacement link. The name stays Shimadzu.</p>

<p>http://www.ssi.shimadzu.com/products/productgroup.cfm?subcatlink=tissueimaging — Redirects to https://www.ssi.shimadzu.com/products/index.html. Title: &#x27;Discover Cutting-Edge Analytical Instruments | SHIMADZU&#x27;. No matches for NIRS, LABNIRS, LIGHTNIRS or &#x27;tissue imaging&#x27;.</p>

<p>https://www.shimadzu.com/an/products/life-science-lab-instruments/imaging/index.html — HTTP 200. Title: &#x27;Imaging : SHIMADZU (Shimadzu Corporation)&#x27;. The page mentions both LABNIRS and LIGHTNIRS.</p>

<p>https://www.shimadzu.com/an/products/life-science-lab-instruments/imaging/lightnirs/index.html — HTTP 200. &#x27;LIGHTNIRS Portable functional Near-Infrared Spectroscopy System for Research&#x27;.</p>

<p>https://www.shimadzu.com/an/products/life-science-lab-instruments/imaging/labnirs/index.html — HTTP 200. Official LABNIRS product page.</p>

<p>https://www.ssi.shimadzu.com/products/imaging/lightnirs.html — Returns 404. The old SSI (US) LIGHTNIRS URL is gone, and the SSI imaging category page has no NIRS mentions.</p>

<p>Caveats: The suggested page is Shimadzu&#x27;s global Imaging category, which may list other imaging products besides fNIRS. The maintainer could link the LABNIRS or LIGHTNIRS product page instead.</p>

</details>

<h3>NerveX — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -215,7 +215,6 @@
 * [Vielight](https://www.vielight.com/): Transcranial Photobiomodulation
 * [Neuroelectrics](https://www.neuroelectrics.com/): tDCS, tACS, tRNS
 * [NeuroPace](https://www.neuropace.com/): RNS
-* [NerveX](https://nx.vet/): VNS in canine epilepsy.
 * [NeuroSigma](https://www.neurosigma.com/): eTNS
 * [Brainsway](https://www.brainsway.com/): Deep TMS
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL no longer presents VNS or epilepsy content. nx.vet is now NxVET, selling veterinary exam-room recorders and AI-scribe wearables (NxHUB, Extero, NxSCOPE, NxTHERM). NerveX&#x27;s own site states that NerveX &#x27;is currently operating in veterinary healthcare as NxVET&#x27; and that the company evolved away from human health applications. The git history shows the 2026 refresh changed the URL from nervexneurotech.com to nx.vet without updating the description. Neither the link nor the description supports a brain-stimulation resource.</p>

<p>https://nx.vet/ — HTTP 200. Title &#x27;NxHUB: Veterinary Exam Room Recorder for AI Scribes | NxVET&#x27;. Products: NxHUB wall recorder and Extero AI wearable. No mention of vagus, VNS, epilepsy or seizure.</p>

<p>https://nx.vet/pages/resources — Resources cover NxHUB, Extero, NxSCOPE (stethoscope/PCG cardiology) and NxTHERM guides plus a developer API. No stimulation products.</p>

<p>https://nervex.tech/about/ — Official NerveX page: &#x27;NerveX is currently operating in veterinary healthcare as NxVET&#x27; (redirect notice), and &#x27;Upon evolving from human health applications, the team brought on Dr. Mark de Wolde, an innovative veterinarian&#x27;.</p>

<p>https://entrepreneurs.utoronto.ca/startup/nervex-neurotechnologies/ — Search result for a UofT startup profile describing NerveX&#x27;s earlier ANIMO vagus-nerve implant for canine epilepsy. Seen only as a search listing and summary, not read in full.</p>

<p>Caveats: No official statement was found that explicitly discontinues the ANIMO VNS implant program. The evidence is that the company&#x27;s official web presence now covers only non-stimulation veterinary products.; A maintainer could instead look for a current official VNS page. None was found.</p>

</details>

<h3>Quasi-Ballistic Photons. (The Tech being used by Facebook&#x27;s BCI) — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The 1999 arXiv paper still resolves and is relevant historical background on optical imaging through turbid media like tissue. The entry&#x27;s label says it is &#x27;The Tech being used by Facebook&#x27;s BCI&#x27;, but in July 2021 Facebook/Meta said it was stopping its head-mounted optical BCI work and moving to wrist EMG. The present-tense claim is outdated. The label should name the paper rather than the discontinued corporate project.</p>

<p>https://arxiv.org/abs/cond-mat/9906188 — The arXiv abstract page resolves (HTTP 200): &#x27;Imaging in turbid media using quasi-ballistic photons&#x27;, Gopal, Mujumdar, Ramachandran, Sood, submitted 13 Jun 1999. It covers polarisation discrimination of quasi-ballistic photons in scattering media.</p>

<p>https://tech.facebook.com/reality-labs/2021/07/bci-milestone-new-research-from-ucsf-with-support-from-facebook-shows-the-potential-of-brain-computer-interfaces-for-restoring-speech-communication/ — Search summary of the official Meta post (July 2021): &#x27;we&#x27;ve decided to focus our immediate efforts on a different neural interface approach ... wrist-based devices powered by electromyography&#x27;. The head-mounted optical BCI software was open-sourced.</p>

<p>https://www.technologyreview.com/2021/07/14/1028447/facebook-brain-reading-interface-stops-funding/ — Search-result coverage reports that Facebook shelved its optical head-mounted &#x27;silent speech&#x27; BCI in July 2021.</p>

<p>Blocking questions: The maintainer may prefer to keep the Facebook context in past tense, e.g. &#x27;(approach explored for Facebook&#x27;s discontinued optical BCI)&#x27;, rather than drop it. The exact wording is an editorial choice.</p>

<p>Caveats: I did not read the Meta post directly; it is cited through search results and secondary coverage.; No official source confirms that Facebook&#x27;s prototype specifically used this paper&#x27;s quasi-ballistic technique. The original label was itself an unsourced claim.</p>

</details>

<h3>Openwater — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Openwater&#x27;s site no longer describes a portable MRI goal. It now presents Open-Motion, a wearable near-infrared optical device that measures cerebral blood flow and volume (pulsed speckle contrast optical spectroscopy), and Open-LIFU, a focused-ultrasound device. &#x27;aiming to build a portable MRI&#x27; is outdated. The founder&#x27;s surname is also misspelled (&#x27;Jepken&#x27;; it is commonly spelled Jepsen). This is a prose-prefixed entry with child items, so it needs manual editing.</p>

<p>https://www.openwater.health/ — The homepage navigation lists Open-Motion and Open-LIFU. It describes low-cost hardware &#x27;manipulating light, sound, and electromagnetics&#x27;. MRI is not mentioned.</p>

<p>https://www.openwater.health/open-motion — Open-Motion: &#x27;Wearable optical sensing for real-time cerebral perfusion measurement&#x27;. It uses P-SCOS with near-infrared light to measure blood flow and volume &#x27;up to 3.5 CM into the brain&#x27;, in a portable open-source device.</p>

<p>Blocking questions: Prose-prefixed complex entry: the prefix text (including the &#x27;Jepken&#x27; spelling and the &#x27;Diffused Optical Imaging&#x27; label) must be edited by hand and cannot be applied as a simple description replacement.</p>

<p>Caveats: I could not find an official Openwater &#x27;about&#x27; page (/about returned 404), so the founder&#x27;s name and current role were not confirmed on the official site.; Speckle contrast optical spectroscopy is related to diffuse optical methods, but I did not confirm whether Openwater itself calls it &#x27;diffuse optical imaging&#x27;.</p>

</details>

<h3>National Sleep Research Resource — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>sleepdata.org is still live (it fails TLS verification in this sandbox, but loads when verification is skipped). The official site calls NSRR &#x27;an NHLBI-supported repository&#x27; and &#x27;An NHLBI resource&#x27;. Neither the homepage nor the About page mentions the Sleep Research Society, so the SRS support claim is not supported by current official text.</p>

<p>https://sleepdata.org/about — &#x27;The National Sleep Research Resource (NSRR) is an NHLBI-supported repository for sharing large amounts of sleep data (polysomnography, actigraphy and questionnaire-based)...&#x27;. It also describes collaboration with NHLBI BioData Catalyst.</p>

<p>https://sleepdata.org/ — Homepage: &#x27;An NHLBI resource for the sleep research community&#x27;. A banner notes the repository &#x27;is under review for potential modification in compliance with Administration directives&#x27;.</p>

<p>Blocking questions: I only found that the official pages don&#x27;t mention SRS. I found no statement that SRS never supported NSRR. A maintainer should confirm before dropping the SRS attribution.</p>

<p>Caveats: The TLS failure seen here was local (missing issuer certificate) and is not evidence of a site problem.; The homepage banner about possible modification under federal directives may affect future availability.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Temple University EEG Corpora — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -246,7 +246,7 @@
 * [OpenNeuro](https://openneuro.org/)
 * [PhysioNet](https://physionet.org/)
 * [National Sleep Research Resource](https://sleepdata.org/): A large collection of sleep data. Supported by the Sleep Research Society (SRS).
-* [Temple University EEG Corpora](https://isip.piconepress.com/projects/): various datasets including health, epilepsy, artifactual, etc.
+* [Temple University EEG Corpora](https://isip.piconepress.com/projects/nedc/html/tuh_eeg/): various datasets including health, epilepsy, artifactual, etc.
 
 ## Tutorials and Project Ideas
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL is a raw Apache directory index of every ISIP lab project (speech, chess, quantum, etc.), not the EEG corpus page. The official TUH EEG corpus page, with corpus list and access instructions, is under projects/nedc/html/tuh_eeg/. The description is roughly accurate: the corpora include abnormal, artifact, epilepsy, events, seizure and slowing sets.</p>

<p>https://isip.piconepress.com/projects/ — &#x27;Index of /projects&#x27;: an auto-generated directory listing (aauc/, ai_chess/, nedc/, neuronix/, ...) with no EEG corpus description.</p>

<p>https://isip.piconepress.com/projects/nedc/html/tuh_eeg/ — &#x27;Temple University EEG Corpus - Downloads&#x27; lists TUEG (26,846 clinical EEG recordings, 2002-2017), TUAB abnormal, TUAR artifact, TUEP epilepsy, TUEV events, TUSL slowing and TUSZ. Access is via a signed form and rsync.</p>

<p>Caveats: Access requires registration; the data itself was not downloaded.; An older path, projects/tuh_eeg/, also returns 200, but its content was not confirmed as the corpus page.</p>

</details>

<h3>Building a 20 Euro EEG for your smartphone — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -257,7 +257,7 @@
 * [Introduction to Modern BCI](https://eeglab.ucsd.edu/wiki/Introduction_To_Modern_Brain-Computer_Interface_Design)
 * [Brain-Controlled Shark Attack](http://eeghacker.blogspot.com/2015/03/brain-controlled-shark-attack.html)
 * [Controlling a sphero with a muse](https://github.com/neuralcubes/musephero)
-* [Building a 20 Euro EEG for your smartphone](https://github.com/jmanart/smartphone-bci)
+* [Building a £20 EEG for your smartphone](https://github.com/jmanart/smartphone-bci)
 * [Muse File Reader for OpenVibe](https://web.archive.org/web/20240930191736/https://openvibe.inria.fr/forum/viewtopic.php?f=3&t=9668)
 * [EEG 101: Interactive tutorial for Android and Muse](https://github.com/NeuroTechX/eeg-101)
 * [Brainwave analyzer](https://github.com/katie356/BrainwaveAnalyzer/tree/master/web-edition)
```

<details>
<summary>Evidence and limitations</summary>

<p>The repo is live and BCI-relevant: the Android app for a low-cost smartphone EEG. However, the entry name says &#x27;20 Euro&#x27; and the official README says &#x27;Developing an EEG under £20&#x27;. No euro figure appears anywhere in the README&#x27;s git history. Suggest correcting the currency in the name; the URL stays the same.</p>

<p>https://raw.githubusercontent.com/jmanart/smartphone-bci/master/README.md — &#x27;Smartphone-bci is a hardware / software platform born with the intention of Developing an EEG under £20.&#x27; The repo is the Android app software for the SmartphoneBCI hardware and shows frequency analysis, alpha power and a sanity-check view.</p>

<p>https://github.com/jmanart/smartphone-bci — HTTP 200. Git history runs from 2016-06-19 to 2016-10-03. Searching the README history for &#x27;uro&#x27; found no euro mention.</p>

<p>https://jmanart.github.io/smartphone-bci-hardware/ — The project page linked from the README returns a GitHub Pages 404.</p>

<p>https://github.com/jmanart/smartphone-bci-hardware — The companion hardware repo returns HTTP 200. The other linked repo, capitancambio/smartphone-bci, now redirects to icibici/Android-diagnostic-app.</p>

<p>Caveats: A talk or article may have described the project in euros. Only the repository was checked.; The README carries a safety warning about connecting while the phone is charging. Clinical or electrical safety was not assessed.; Inactive since 2016. Not built or run.</p>

</details>

<h3>EEG 101: Interactive tutorial for Android and Muse — remove</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -259,7 +259,6 @@
 * [Controlling a sphero with a muse](https://github.com/neuralcubes/musephero)
 * [Building a 20 Euro EEG for your smartphone](https://github.com/jmanart/smartphone-bci)
 * [Muse File Reader for OpenVibe](https://web.archive.org/web/20240930191736/https://openvibe.inria.fr/forum/viewtopic.php?f=3&t=9668)
-* [EEG 101: Interactive tutorial for Android and Muse](https://github.com/NeuroTechX/eeg-101)
 * [Brainwave analyzer](https://github.com/katie356/BrainwaveAnalyzer/tree/master/web-edition)
 * [BCI Course offered by Columbia University](https://naplab.ee.columbia.edu/bcilab.html)
 * [BCI Course at Berkeley by Pierre of NeuroTechX](https://github.com/neurotech-berkeley/neurotech-course)
```

<details>
<summary>Evidence and limitations</summary>

<p>The project&#x27;s own README says it is dead. Interaxon withdrew its Muse SDK, so the app can no longer connect to Muse devices, and it was pulled from Google Play. That means the listed &#x27;interactive tutorial for Android and Muse&#x27; has lost its interface. The README points to EEGEdu as its &#x27;spiritual successor&#x27;, and EEGEdu is already listed first in this section, so a replace would create a duplicate.</p>

<p>https://raw.githubusercontent.com/NeuroTechX/eeg-101/master/README.md — &#x27;EEG 101 is dead, may it rest in peace. Due to Interaxon rescinding support for its Muse SDK, it is no longer possible for open-source developers to build mobile apps that connect to Muse devices, including this one. Thus, we have stopped development here and removed the app from the Google Play Store.&#x27; It recommends EEGEdu as the spiritual successor.</p>

<p>https://github.com/NeuroTechX/eeg-101 — HTTP 200. The packet snapshot marks the repo as archived.</p>

<p>https://github.com/kylemath/EEGEdu — The successor repo is live. Its README says it is &#x27;inspired by EEG101&#x27; and is a web-based version served at https://eegedu.com (HTTP 200).</p>

<p>Caveats: The repo&#x27;s explanatory text may still have some educational value as a historical reference. The maintainer may prefer to keep it labelled as archived instead of removing it.; EEGEdu is already at line 253 of README.md, so no replacement entry is needed.</p>

</details>

<h3>OpenBCI Community — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -270,7 +270,7 @@
 
 ### Forums
 * [NeuroBB](https://neurobb.com/)
-* [OpenBCI Community](https://openbci.com//community/)
+* [OpenBCI Community](https://openbci.com/community/)
 * [Muse Community](https://www.reddit.com/r/museheadband/)
 * [NeuroSky](https://support.neurosky.com/discussions)
 * [Emotiv](https://forum.emotiv.com/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The community page is live and relevant, but the listed URL has a double slash (openbci.com//community/) that returns a 301 to the canonical https://openbci.com/community/. This is a URL tidy-up only.</p>

<p>https://openbci.com/community/ — https://openbci.com//community/ returns a 301 to https://openbci.com/community/, which returns HTTP 200: &#x27;Welcome to the OpenBCI Community&#x27; with posts on research, tutorials and projects. The newest post is dated October 23, 2026. It links to the separate OpenBCI Forum for technical support.</p>

</details>

<h3>BCI Course offered by Columbia University — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -261,7 +261,7 @@
 * [Muse File Reader for OpenVibe](https://web.archive.org/web/20240930191736/https://openvibe.inria.fr/forum/viewtopic.php?f=3&t=9668)
 * [EEG 101: Interactive tutorial for Android and Muse](https://github.com/NeuroTechX/eeg-101)
 * [Brainwave analyzer](https://github.com/katie356/BrainwaveAnalyzer/tree/master/web-edition)
-* [BCI Course offered by Columbia University](https://naplab.ee.columbia.edu/bcilab.html)
+* [BCI Course offered by Columbia University](https://naplab.ee.columbia.edu/bci/)
 * [BCI Course at Berkeley by Pierre of NeuroTechX](https://github.com/neurotech-berkeley/neurotech-course)
 * [EEG and MRI Course offered by OHBM](https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageID=3814&activateFull=true)
 * [Prometheus Multimodal BCI (Olympic Torch)](https://github.com/inclusive-brains/prometheus-bci)
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed bcilab.html now returns 404 after the NAPLab site moved to a Jekyll site (late 2025 or early 2026; Wayback had 200 on 2025-08-02 and 404 on 2026-02-18). The same course page, &#x27;Hands-on Brain-Computer Interfaces (BCI) Laboratory, ECBME 4090&#x27;, is now at /bci/, linked from the lab&#x27;s Teaching page.</p>

<p>https://naplab.ee.columbia.edu/bcilab.html — Returns HTTP 404. The Wayback CDX shows 200 captures in Apr and Aug 2025, then 301→404 on 2026-02-18.</p>

<p>http://web.archive.org/web/20250802065158/http://naplab.ee.columbia.edu/bcilab.html — The archived page is &#x27;Hands-on Brain-Computer Interfaces (BCI) Laboratory (ECBME 4090)&#x27;. It has a course description, learning objectives (ERP/P300, SSVEP, imagined movement, CSP, LDA) and downloadable lab materials.</p>

<p>https://naplab.ee.columbia.edu/teaching/ — The Teaching page lists &#x27;ECBME 4090: Brain Computer Interfaces Laboratory&#x27; and links to /bci/.</p>

<p>https://naplab.ee.columbia.edu/bci/ — HTTP 200. Same course description, the EMBC 2016 citation (Khalighinejad, Long, Mesgarani), learning objectives and lab PDFs (labinstruction1.pdf, labinstruction2.pdf, finalbci.pdf).</p>

<p>Caveats: Did not check that every lab PDF downloads.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Natalie Schaworonkow — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -279,7 +279,7 @@
 
 - [NeuroTechX Content Lab](https://neurotechx.medium.com/): Articles, tutorials, and interviews on neurotechnology
 - [The EEG Newsletter](https://eegnewsletter.substack.com/): News, events, and resources in EEG. By Raquel E. London
-- [Natalie Schaworonkow](https://nschawor.github.io/posts/)
+- [Natalie Schaworonkow](https://nschawor.github.io/)
 - [Autodidact](https://www.autodidacts.io/)
 - [Strfry](https://strfry.org/blog/)
 - [Fabien Lotte](https://sites.google.com/site/fabienlotte/research/code-and-softwares)
```

<details>
<summary>Evidence and limitations</summary>

<p>The blog is still active and BCI/EEG-relevant: posts on neural oscillations, MEG artefacts and neuroscience tooling run through 2026. The listed /posts/ URL is now a meta-refresh &#x27;Redirecting…&#x27; stub that sends readers to the site root, and the root page now hosts the post list. Pointing the entry at the canonical root avoids the client-side redirect.</p>

<p>https://nschawor.github.io/posts/ — Returns HTTP 200 with the title &#x27;Redirecting…&#x27; and a meta refresh to https://nschawor.github.io/.</p>

<p>https://nschawor.github.io/ — Page titled &#x27;Posts - nschawor&#x27; says it holds 139 posts, grouped by year from 2019 to 2026. The latest post is dated May 04, 2026. Topics include MEG artefacts, brain rhythms and an EEG Bluesky starter pack.</p>

<p>Caveats: The redirect is client-side (meta refresh), not an HTTP 3xx, so keeping the old URL still works for readers.; Topics are broad EEG/MEG neuroscience rather than strictly BCI.</p>

</details>

<h3>Pierre Karashchuk — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -285,7 +285,7 @@
 - [Fabien Lotte](https://sites.google.com/site/fabienlotte/research/code-and-softwares)
 - [Chip Audette EEG Hacker](http://eeghacker.blogspot.com/)
 - [Alexandre Barachant](http://alexandre.barachant.org/)
-- [Pierre Karashchuk](https://lambdaloop.com/)
+- [Lili Karashchuk](https://lambdaloop.com/)
 - [Jeremy Frey](http://phd.jfrey.info/)
 - [Irene Vigué Guix](http://www.irenevigueguix.com)
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The site owner&#x27;s name has changed. lambdaloop.com now identifies the owner as Lili Karashchuk, a scientist at HHMI Janelia, formerly at the Allen Institute for Neural Dynamics, with a UW Neuroscience PhD. The posts are on a linked writings subdomain under the same name, and several are BCI posts. The catalog&#x27;s displayed name should match the owner&#x27;s current self-identification. The URL is still valid.</p>

<p>https://lambdaloop.com/ — HTTP 200, titled &#x27;Lili Karashchuk&#x27;. Homepage text: &#x27;I am a scientist at the HHMI Janelia Research Campus… Previously… Allen Institute for Neural Dynamics… PhD student in Neuroscience at University of Washington&#x27;. It links to https://writings.lambdaloop.com and github.com/lambdaloop.</p>

<p>https://writings.lambdaloop.com — Titled &#x27;Lili&#x27;s pieces - Posts&#x27;. Has a &#x27;bci&#x27; category with 2 posts: &#x27;Predicting memory encoding using an OpenBCI&#x27; (Aug 7, 2016) and &#x27;Mind controlled robotic arm at The Exploratorium&#x27; (Jun 26, 2016). The latest post is from Jun 2023.</p>

<p>Caveats: The BCI posts are from 2016. Most recent writing covers pose estimation and neuroscience.; The maintainer may prefer pointing to https://writings.lambdaloop.com, since that is where the posts are, but the homepage links to it.</p>

</details>

<h3>**List**: Curated list of events (BCI Society) — update</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>https://bcisociety.org/events/ now returns HTTP 404 &#x27;Page not found&#x27;, and the Wayback Machine also returns 404 for a 2024 capture of that path. The society&#x27;s current navigation has an &#x27;Other Events&#x27; page that lists upcoming partner events, for example ASNR 2027. That page appears to be the current equivalent of a curated event list. The society did not publish a redirect.</p>

<p>https://bcisociety.org/events/ — HTTP 404, titled &#x27;Page not found | bcisociety.org&#x27;.</p>

<p>https://web.archive.org/web/2025/https://bcisociety.org/events/ — Resolves to a 2024-09-30 Wayback capture that also returns 404, suggesting the path has been gone for some time.</p>

<p>https://bcisociety.org/other-events/ — HTTP 200, titled &#x27;Other Events | bcisociety.org&#x27;. Under &#x27;Upcoming Events from our Partners&#x27; it lists the ASNR 2027 Annual Meeting (March 16-18, 2027). The page is linked from the society&#x27;s main navigation.</p>

<p>Blocking questions: There is no redirect or official statement that /other-events/ replaced /events/, so the content match is inferred. The maintainer should confirm it is the intended curated event list.</p>

<p>Caveats: The BCI Society&#x27;s own meeting is at https://bcisociety.org/bci-meeting/ and BCI Thursdays has its own entry, so this replacement covers partner events only.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>CNS 2026 Annual Meeting (March 7-10, 2026, Vancouver, Canada) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -308,7 +308,7 @@
 * [**List**: Curated list of events (BCI Society)](https://bcisociety.org/events/)
 * [BCI Thursdays (BCI Society)](https://bcisociety.org/bci-thursdays-online-events/)
 * [BCI Meeting (12th International BCI Meeting, June 7-10, 2027, Croatia)](https://bcisociety.org/bci-meeting/)
-* [CNS 2026 Annual Meeting (March 7-10, 2026, Vancouver, Canada)](https://www.cogneurosociety.org/annual-meeting/)
+* [CNS 2027 Annual Meeting (March 20-23, 2027, Boston, Massachusetts, USA)](https://www.cogneurosociety.org/annual-meeting/)
 * [FENS Forum 2026 (July 6-10, 2026, Barcelona, Spain)](https://fensforum.org/)
 * [10th Graz Brain-Computer Interface Conference 2026 (September 14-18, 2026)](https://bci.tugraz.at/)
 * [NeuroGaming / XTech](http://www.neurogamingconf.com/) [(Youtube Videos)](https://www.youtube.com/user/NeuroGamingCon/videos)
```

<details>
<summary>Evidence and limitations</summary>

<p>The entry names CNS 2026 (March 7–10, 2026, Vancouver), but that meeting is already over. The same official URL now promotes the CNS 2027 Annual Meeting, March 20–23, 2027, in Boston, Massachusetts. The URL is fine; the dated name is out of date.</p>

<p>https://www.cogneurosociety.org/annual-meeting/ — HTTP 200. Page reads &#x27;CNS 2027 Annual Meeting - March 20 - 23, 2027 ... in Boston, Massachusetts&#x27;.</p>

<p>Caveats: CNS is a general cognitive neuroscience meeting, not a BCI-specific one. The maintainers chose to list it, so relevance is not disputed here.; The Conferences section doesn&#x27;t appear to be alphabetical, so the rename shouldn&#x27;t create an ordering problem.</p>

</details>

<h3>FENS Forum 2026 (July 6-10, 2026, Barcelona, Spain) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -309,7 +309,7 @@
 * [BCI Thursdays (BCI Society)](https://bcisociety.org/bci-thursdays-online-events/)
 * [BCI Meeting (12th International BCI Meeting, June 7-10, 2027, Croatia)](https://bcisociety.org/bci-meeting/)
 * [CNS 2026 Annual Meeting (March 7-10, 2026, Vancouver, Canada)](https://www.cogneurosociety.org/annual-meeting/)
-* [FENS Forum 2026 (July 6-10, 2026, Barcelona, Spain)](https://fensforum.org/)
+* [FENS Forum 2028 (July 8-12, 2028)](https://fensforum.org/)
 * [10th Graz Brain-Computer Interface Conference 2026 (September 14-18, 2026)](https://bci.tugraz.at/)
 * [NeuroGaming / XTech](http://www.neurogamingconf.com/) [(Youtube Videos)](https://www.youtube.com/user/NeuroGamingCon/videos)
 * [CHI](https://chi2026.acm.org/wp/)
```

<details>
<summary>Evidence and limitations</summary>

<p>FENS Forum 2026 (July 6–10, 2026, Barcelona) is over. The official site lists the next one as &#x27;FENS Forum 2028&#x27;, July 8–12, 2028. The URL is still the right one; the dated name is out of date.</p>

<p>https://fensforum.org/ — HTTP 200. Page title is still &#x27;FENS Forum 2026&#x27;. The dates list shows &#x27;6-10 July 2026 | FENS Forum 2026&#x27; and &#x27;8-12 July 2028 | FENS Forum 2028&#x27;.</p>

<p>Caveats: I didn&#x27;t confirm the 2028 host city from the page I read, so the proposed name leaves out the location.; FENS is a general neuroscience meeting, not specific to BCI.</p>

</details>

<h3>10th Graz Brain-Computer Interface Conference 2026 (September 14-18, 2026) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -310,7 +310,7 @@
 * [BCI Meeting (12th International BCI Meeting, June 7-10, 2027, Croatia)](https://bcisociety.org/bci-meeting/)
 * [CNS 2026 Annual Meeting (March 7-10, 2026, Vancouver, Canada)](https://www.cogneurosociety.org/annual-meeting/)
 * [FENS Forum 2026 (July 6-10, 2026, Barcelona, Spain)](https://fensforum.org/)
-* [10th Graz Brain-Computer Interface Conference 2026 (September 14-18, 2026)](https://bci.tugraz.at/)
+* [10th Graz Brain-Computer Interface Conference 2026 (September 14-17, 2026)](https://www.tugraz.at/institute/ine/graz-bci-conferences/10th-graz-bci-conference-2026)
 * [NeuroGaming / XTech](http://www.neurogamingconf.com/) [(Youtube Videos)](https://www.youtube.com/user/NeuroGamingCon/videos)
 * [CHI](https://chi2026.acm.org/wp/)
 * [BrainTech](http://conference.israelbrain.org/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The official conference page gives the dates as September 14–17, 2026, not 14–18 as the entry says. The conference has already happened, and the page now offers the proceedings. Also, bci.tugraz.at only redirects to the institute&#x27;s home page; the conference has its own page.</p>

<p>https://bci.tugraz.at/ — Redirects to https://www.tugraz.at/institute/ine/home, the general Institute of Neural Engineering home page.</p>

<p>https://www.tugraz.at/institute/ine/graz-bci-conferences/10th-graz-bci-conference-2026 — HTTP 200. Page reads &#x27;10th Graz Brain-Computer Interface Conference 2026 September 14-17, 2026&#x27;. It thanks participants, links the proceedings, and mentions a closing ceremony on &#x27;Thursday 17th September&#x27;.</p>

<p>Caveats: The event is over. A maintainer might prefer the series page (https://www.tugraz.at/institute/ine/graz-bci-conferences) or wait for the next edition to be announced. I found no announcement of an 11th conference.</p>

</details>

<h3>NeuroGaming / XTech — remove</h3>

<p>0 proposed change(s); 1 held for unresolved questions.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The main link no longer belongs to the conference. http://www.neurogamingconf.com/ redirects to https://www.neurogamingconf.com/, which is now &#x27;Neuro Gaming Conf | PlayStation Games &amp; PS5 Guides&#x27;, a PlayStation release and guides site with nothing to do with NeuroGaming/XTech. The YouTube channel is still up and describes itself as the official channel of the Experiential Technology (XTech) Conference, but its videos I saw date from 2017. I found no current edition of the event.</p>

<p>https://www.neurogamingconf.com/ — HTTP 200. Title is &#x27;Neuro Gaming Conf | PlayStation Games &amp; PS5 Guides&#x27;. Content is PS5 release countdowns (&#x27;ANOMALITH ... 28 October 2026&#x27;) and console guides, not a neurotech conference.</p>

<p>https://www.youtube.com/user/NeuroGamingCon/videos — HTTP 200. Channel description: &#x27;Official channel of the Experiential Technology Conference &amp; Expo. Experiential Technology &quot;XTech&quot; combines digital technology...&#x27;. Video titles I saw include &#x27;Xtech 2017 Day 2 - 3 ...&#x27;.</p>

<p>Caveats: This is a multi-link entry, so editing it needs a manual change. Instead of removing it, a maintainer could keep only the YouTube archive as a historical talks resource.; I didn&#x27;t search exhaustively for a renamed successor event.</p>

</details>

<h3>NIPS — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -315,7 +315,7 @@
 * [CHI](https://chi2026.acm.org/wp/)
 * [BrainTech](http://conference.israelbrain.org/)
 * [Brain Summit](https://brainsummit.com/)
-* [NIPS](https://nips.cc/)
+* [NeurIPS](https://neurips.cc/)
 * [SfN 2026 (November 14-18, 2026, Washington, D.C., USA)](https://www.sfn.org/meetings/neuroscience-2026)
 * [g.tec SpringSchool on BCI](https://www.gtec.at/event/bci-neurotechnology-spring-school-2025/)
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The conference is now called NeurIPS. nips.cc serves the same &#x27;2026 Conference&#x27; site as the canonical neurips.cc, and its navigation is branded &#x27;NeurIPS&#x27;. It&#x27;s still a relevant machine-learning venue for BCI decoding work. Only the name and canonical URL are out of date.</p>

<p>https://nips.cc/ — HTTP 200, no redirect. Title is &#x27;2026 Conference&#x27;, with menu items &#x27;NeurIPS Help/FAQ&#x27;, &#x27;Contact NeurIPS&#x27;.</p>

<p>https://neurips.cc/ — HTTP 200, same &#x27;2026 Conference&#x27; content under the NeurIPS domain.</p>

<p>Caveats: The Conferences section doesn&#x27;t appear to be alphabetical, so the rename shouldn&#x27;t create an ordering problem.</p>

</details>

<h3>g.tec SpringSchool on BCI — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -317,7 +317,7 @@
 * [Brain Summit](https://brainsummit.com/)
 * [NIPS](https://nips.cc/)
 * [SfN 2026 (November 14-18, 2026, Washington, D.C., USA)](https://www.sfn.org/meetings/neuroscience-2026)
-* [g.tec SpringSchool on BCI](https://www.gtec.at/event/bci-neurotechnology-spring-school-2025/)
+* [g.tec SpringSchool on BCI](https://www.gtec.at/the-bci-neurotechnology-spring-school/)
 
 ## Reading Material
 
```

<details>
<summary>Evidence and limitations</summary>

<p>The link goes to the 2025 Spring School event page, which still promotes 2025. g.tec now runs a general Spring School page that advertises the 2027 edition. The generic name &#x27;g.tec SpringSchool on BCI&#x27; still fits, so only the URL needs to change.</p>

<p>https://www.gtec.at/event/bci-neurotechnology-spring-school-2025/ — HTTP 200. Title is &#x27;BCI &amp; NEUROTECHNOLOGY SPRING SCHOOL 2025&#x27;. Text: &#x27;Let&#x27;s make 2025 another educational highlight of the year.&#x27; The site navigation lists &#x27;THE SPRING SCHOOL 2027&#x27;.</p>

<p>https://www.gtec.at/the-bci-neurotechnology-spring-school/ — HTTP 200. Title is &#x27;The BCI &amp; Neurotechnology Spring School | g.tec medical engineering&#x27;. Text: &#x27;Join the Global Neurotechnology Community in 2027&#x27;. The g.tec home page links to this URL.</p>

<p>Caveats: Optionally, the name could follow the official styling, &#x27;BCI &amp; Neurotechnology Spring School&#x27;.</p>

</details>

<h3>Non-Invasive Brain-Computer Interfaces: State of the Art and Trends (Edelman et al., 2024) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -323,7 +323,7 @@
 
 ### Papers
 
-- [Non-Invasive Brain-Computer Interfaces: State of the Art and Trends (Edelman et al., 2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC10784964/): A comprehensive review of the current landscape and future directions of non-invasive BCIs.
+- [Non-Invasive Brain-Computer Interfaces: State of the Art and Trends (Edelman et al., 2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC11861396/): A comprehensive review of the current landscape and future directions of non-invasive BCIs.
 - [High-performance P300 spellers using GPT-2 word prediction (2024)](https://pubmed.ncbi.nlm.nih.gov/38266453/): Research on integrating LLMs to improve the speed and accuracy of BCI communication.
 - [Multiclass Brain-Computer Interface Classification by Riemannian Geometry](https://www.researchgate.net/publication/51727880_Multiclass_Brain-Computer_Interface_Classification_by_Riemannian_Geometry)
 - [A New Generation of Brain-Computer Interface Based on Riemannian Geometry](https://www.researchgate.net/publication/258144410_A_New_Generation_of_Brain-Computer_Interface_Based_on_Riemannian_Geometry)
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed PMC ID is for an unrelated paper. NCBI E-utilities and Europe PMC both resolve PMC10784964 to a JCEM Case Reports 2024 abstract on lutetium therapy for ACTH syndrome. The real Edelman et al. review, &#x27;Non-Invasive Brain-Computer Interfaces: State of the Art and Trends&#x27; (IEEE Rev Biomed Eng, vol. 18, 2025; published online 2024), is PMC11861396, DOI 10.1109/RBME.2024.3449790. Its abstract supports the current description.</p>

<p>https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=pmc&amp;id=10784964&amp;retmode=json — PMC10784964 is &#x27;O-06 Efficacy of Lutetium-Peptide Receptor Radionuclide Therapy and osilodrostat treatment...&#x27; in JCEM Case Reports, 2024 Jan, DOI 10.1210/jcemcr/luad146.042. Not a BCI paper.</p>

<p>https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=EXT_ID:39186407&amp;format=json&amp;resultType=core — Edelman BJ, Zhang S, Schalk G, Brunner P, Muller-Putz G, Guan C, He B. &#x27;Non-Invasive Brain-Computer Interfaces: State of the Art and Trends&#x27;, IEEE Rev Biomed Eng 2025, vol. 18. PMID 39186407, PMCID PMC11861396, DOI 10.1109/rbme.2024.3449790. Abstract: &#x27;In this review, we provide an overview of the general BCI framework...&#x27;</p>

<p>Caveats: The PMC HTML pages returned a reCAPTCHA to my client, so I took the mappings from the NCBI and Europe PMC APIs.; The entry says 2024, but the print issue is 2025. The 2024 online publication date makes the current year defensible.</p>

</details>

<h3>High-performance P300 spellers using GPT-2 word prediction (2024) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -324,7 +324,7 @@
 ### Papers
 
 - [Non-Invasive Brain-Computer Interfaces: State of the Art and Trends (Edelman et al., 2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC10784964/): A comprehensive review of the current landscape and future directions of non-invasive BCIs.
-- [High-performance P300 spellers using GPT-2 word prediction (2024)](https://pubmed.ncbi.nlm.nih.gov/38266453/): Research on integrating LLMs to improve the speed and accuracy of BCI communication.
+- [High-performance P300 spellers using GPT-2 word prediction (2024)](https://doi.org/10.1080/2326263X.2024.2413214): Research on integrating LLMs to improve the speed and accuracy of BCI communication.
 - [Multiclass Brain-Computer Interface Classification by Riemannian Geometry](https://www.researchgate.net/publication/51727880_Multiclass_Brain-Computer_Interface_Classification_by_Riemannian_Geometry)
 - [A New Generation of Brain-Computer Interface Based on Riemannian Geometry](https://www.researchgate.net/publication/258144410_A_New_Generation_of_Brain-Computer_Interface_Based_on_Riemannian_Geometry)
 - [My Virtual Dream: Collective Neurofeedback in an Immersive Art Environment ](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0130129)
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed PMID is for an unrelated paper. NCBI resolves PMID 38266453 to a 2024 rat pharmacokinetics study of flonoltinib maleate (J Pharm Biomed Anal). The paper the entry means is &#x27;High performance P300 spellers using GPT2 word prediction with cross-subject training&#x27; by Parthasarathy et al., Brain-Computer Interfaces (Taylor &amp; Francis), 2024, DOI 10.1080/2326263X.2024.2413214. A green open-access copy is on arXiv as 2405.13329. Its abstract describes using GPT-2 word prediction to speed up a P300 speller, which fits the description.</p>

<p>https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=pubmed&amp;id=38266453&amp;retmode=json — PMID 38266453 is &#x27;Study on tissue distribution, metabolite profiling, and excretion of [14C]-labeled flonoltinib maleate in rats&#x27;, J Pharm Biomed Anal, 2024 Apr 15. Not a BCI paper.</p>

<p>https://api.openalex.org/works/doi:10.1080/2326263x.2024.2413214 — &#x27;High performance P300 spellers using GPT2 word prediction with cross-subject training&#x27;, 2024-10-01, journal Brain-Computer Interfaces. Authors: N. Parthasarathy, J. Soetedjo, S. Panchavati, N. Parthasarathy, C.W. Arnold, N. Pouratian, W.F. Speier. OA URL arxiv.org/pdf/2405.13329. Abstract mentions using GPT-2 to speed up a P300 speller for ALS communication.</p>

<p>Caveats: doi.org redirects to tandfonline.com, which returned 403 to my automated client. I took the metadata from OpenAlex and didn&#x27;t read the publisher page directly.; The paper doesn&#x27;t appear to be indexed in PubMed, so there&#x27;s no correct PubMed URL to use instead.; Optionally, the name could match the exact published title (&#x27;High performance P300 spellers using GPT2 word prediction with cross-subject training (2024)&#x27;).</p>

</details>

<h3>CHI — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -312,7 +312,7 @@
 * [FENS Forum 2026 (July 6-10, 2026, Barcelona, Spain)](https://fensforum.org/)
 * [10th Graz Brain-Computer Interface Conference 2026 (September 14-18, 2026)](https://bci.tugraz.at/)
 * [NeuroGaming / XTech](http://www.neurogamingconf.com/) [(Youtube Videos)](https://www.youtube.com/user/NeuroGamingCon/videos)
-* [CHI](https://chi2026.acm.org/wp/)
+* [CHI](https://chi2027.acm.org/)
 * [BrainTech](http://conference.israelbrain.org/)
 * [Brain Summit](https://brainsummit.com/)
 * [NIPS](https://nips.cc/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL https://chi2026.acm.org/wp/ now returns 404, though the CHI 2026 site (Barcelona, April 13–17, 2026) itself still exists and that conference is over. The official CHI 2027 site is live: Pittsburgh, May 10–14, 2027. The entry is just named &#x27;CHI&#x27;, so pointing it at the current edition keeps the name accurate.</p>

<p>https://chi2026.acm.org/wp/ — HTTP 404. The page reads &#x27;Page not found - ACM CHI 2026&#x27; and shows the site header &#x27;Barcelona, 13–17 April, 2026&#x27;.</p>

<p>https://chi2027.acm.org/ — HTTP 200. Title is &#x27;Welcome to CHI 2027 - ACM CHI 2027&#x27;. Text: &#x27;ACM CHI 2027 Pittsburgh, 10–14 May, 2027&#x27;.</p>

<p>Caveats: https://chi.acm.org/ returned 403 to my client, so I couldn&#x27;t check whether there&#x27;s a stable series URL to use instead of a yearly one.; CHI is a general HCI conference, not specific to BCI.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Word pair classification during imagined speech using direct brain recording — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -332,7 +332,7 @@
 - [Single-Trial Analysis and Classification of ERP Components – a Tutorial](https://doc.ml.tu-berlin.de/bbci/publications/BlaLemTreHauMue10.pdf)
 - [Interpretable Deep Neural Networks for Single-Trial EEG Classification](https://www.researchgate.net/publication/301817936_Interpretable_Deep_Neural_Networks_for_Single-Trial_EEG_Classification)
 - [Large-Scale Assessment of a Fully Automatic Co-Adaptive Motor Imagery-Based Brain Computer Interface](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0148886)
-- [Word pair classification during imagined speech using direct brain recording](https://www.nature.com/articles/srep25803)
+- [Word pair classification during imagined speech using direct brain recordings](https://www.nature.com/articles/srep25803)
 - [Brain-Computer Interfaces Review, Nicolelis & Lebedev. 2017](https://pubmed.ncbi.nlm.nih.gov/28275048/)
 - [High-speed spelling with a noninvasive brain–computer interface](https://www.pnas.org/content/112/44/E6058.abstract)
 - [A high-speed brain-computer interface (BCI) using dry EEG electrodes](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0172400)
```

<details>
<summary>Evidence and limitations</summary>

<p>Paper is live and relevant (imagined-speech decoding from ECoG). The link label leaves the &#x27;s&#x27; off the end of the published title, which is &#x27;Word pair classification during imagined speech using direct brain recordings&#x27;. The suggested fix only corrects the name. The URL stays the same.</p>

<p>https://www.nature.com/articles/srep25803 — HTTP 200 (after Nature&#x27;s cookie redirect). citation_title meta tag reads &#x27;Word pair classification during imagined speech using direct brain recordings&#x27;. Authors: Martin, Brunner, Iturrate, Millán, Schalk, Knight, Pasley. Published in Scientific Reports.</p>

<p>Caveats: The Papers section is not in alphabetical order, and adding a trailing &#x27;s&#x27; would not change the order anyway.</p>

</details>

<h3>Brain-Computer Interfaces Review, Nicolelis &amp; Lebedev. 2017 — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -333,7 +333,7 @@
 - [Interpretable Deep Neural Networks for Single-Trial EEG Classification](https://www.researchgate.net/publication/301817936_Interpretable_Deep_Neural_Networks_for_Single-Trial_EEG_Classification)
 - [Large-Scale Assessment of a Fully Automatic Co-Adaptive Motor Imagery-Based Brain Computer Interface](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0148886)
 - [Word pair classification during imagined speech using direct brain recording](https://www.nature.com/articles/srep25803)
-- [Brain-Computer Interfaces Review, Nicolelis & Lebedev. 2017](https://pubmed.ncbi.nlm.nih.gov/28275048/)
+- [Brain-Machine Interfaces: From Basic Science to Neuroprostheses and Neurorehabilitation, Lebedev & Nicolelis. 2017](https://pubmed.ncbi.nlm.nih.gov/28275048/)
 - [High-speed spelling with a noninvasive brain–computer interface](https://www.pnas.org/content/112/44/E6058.abstract)
 - [A high-speed brain-computer interface (BCI) using dry EEG electrodes](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0172400)
 
```

<details>
<summary>Evidence and limitations</summary>

<p>PMID 28275048 is a 2017 Physiological Reviews review by Lebedev MA and Nicolelis MA, so it fits the Papers section. The label is inaccurate in two ways: it calls the paper &#x27;Brain-Computer Interfaces Review&#x27; when the actual title is &#x27;Brain-Machine Interfaces: From Basic Science to Neuroprostheses and Neurorehabilitation&#x27;, and it reverses the author order. The suggestion renames the label to the real title and author order. The URL stays the same.</p>

<p>https://eutils.ncbi.nlm.nih.gov/entrez/eutils/esummary.fcgi?db=pubmed&amp;id=28275048&amp;retmode=json — Official NCBI E-utilities summary: title &#x27;Brain-Machine Interfaces: From Basic Science to Neuroprostheses and Neurorehabilitation.&#x27;, source Physiol Rev, pubdate 2017 Apr, authors [&#x27;Lebedev MA&#x27;,&#x27;Nicolelis MA&#x27;], doi 10.1152/physrev.00027.2016.</p>

<p>https://pubmed.ncbi.nlm.nih.gov/28275048/ — Returned HTTP 203 to curl, so the rendered page was not parsed. Metadata came from E-utilities instead.</p>

<p>Caveats: The maintainer may prefer to keep the short descriptive label. The current label is a paraphrase, not a claim that the paper does not exist.; The Papers section is not alphabetized, so renaming does not affect ordering.</p>

</details>

<h3>Beyond Boundaries (Nicolellis) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -339,7 +339,7 @@
 
 
 ### Introductory Books
-* [Beyond Boundaries (Nicolellis)](https://www.amazon.com/Beyond-Boundaries-Neuroscience-Connecting-Machines/dp/1250002613)
+* [Beyond Boundaries (Nicolelis)](https://www.amazon.com/Beyond-Boundaries-Neuroscience-Connecting-Machines/dp/1250002613)
 * [Rhythms of Brain (Buzsaki)](https://www.amazon.com/Rhythms-Brain-Gyorgy-Buzsaki/dp/0199828237)
 * [Cycles in mind (Cohen)](https://www.amazon.com/Cycles-mind-rhythms-control-perception-ebook/dp/B013ZI5AIA)
 * [Principles of Neural Science (Kandel et al)](https://www.amazon.com/Principles-Neural-Science-Eric-Kandel/dp/0838577016)
```

<details>
<summary>Evidence and limitations</summary>

<p>The book is Beyond Boundaries by Miguel Nicolelis (ISBN 1250002613), a popular BCI/BMI book that fits Introductory Books. The label misspells the author as &#x27;Nicolellis&#x27;; the suggestion corrects it to &#x27;Nicolelis&#x27;.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:1250002613&amp;format=json&amp;jscmd=data — Open Library: &#x27;Beyond Boundaries&#x27; by Miguel Nicolelis, published Feb 28, 2012.</p>

<p>https://www.amazon.com/Beyond-Boundaries-Neuroscience-Connecting-Machines/dp/1250002613 — HTTP 200 to curl (about 195 KB), but no productTitle element could be parsed, so the Amazon listing content was not confirmed.</p>

<p>Caveats: The Amazon page content could not be parsed. Identity rests on the ISBN in the URL and Open Library metadata.; The Introductory Books section is not alphabetized, and the fix only touches the parenthetical, so ordering is unaffected.</p>

</details>

<h3>Rhythms of Brain (Buzsaki) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -340,7 +340,7 @@
 
 ### Introductory Books
 * [Beyond Boundaries (Nicolellis)](https://www.amazon.com/Beyond-Boundaries-Neuroscience-Connecting-Machines/dp/1250002613)
-* [Rhythms of Brain (Buzsaki)](https://www.amazon.com/Rhythms-Brain-Gyorgy-Buzsaki/dp/0199828237)
+* [Rhythms of the Brain (Buzsaki)](https://www.amazon.com/Rhythms-Brain-Gyorgy-Buzsaki/dp/0199828237)
 * [Cycles in mind (Cohen)](https://www.amazon.com/Cycles-mind-rhythms-control-perception-ebook/dp/B013ZI5AIA)
 * [Principles of Neural Science (Kandel et al)](https://www.amazon.com/Principles-Neural-Science-Eric-Kandel/dp/0838577016)
 * [The Future of the Mind (Kaku)](https://www.amazon.com/The-Future-Mind-Scientific-Understand/dp/038553082X)
```

<details>
<summary>Evidence and limitations</summary>

<p>ISBN 0199828237 is &#x27;Rhythms of the Brain&#x27; by György Buzsáki (OUP paperback, 2011), a foundational text on brain oscillations that fits Introductory Books. The label leaves &#x27;the&#x27; out of the title; the suggestion corrects only the name.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:0199828237&amp;format=json&amp;jscmd=data — Open Library: &#x27;Rhythms of the Brain&#x27; by Gyorgy Buzsaki, published Jun 03, 2011.</p>

<p>https://www.amazon.com/Rhythms-Brain-Gyorgy-Buzsaki/dp/0199828237 — Amazon served a captcha page (3,781 bytes) to automated requests, so the listing was not read.</p>

<p>Caveats: Amazon blocks automated access, so link reachability was not confirmed in a browser. This is not evidence of a dead link.; The section is not alphabetized.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Signals &amp; Systems (Oppenheim, Willsky, Hamid) — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -358,7 +358,7 @@
 
 * [Signals & Systems MIT Class](https://ocw.mit.edu/courses/res-6-007-signals-and-systems-spring-2011/)
 * Berkeley DSP class [lectures](https://www.youtube.com/watch?v=6_-ljdxjwac&list=PL-XXv-cvA_iCUQkarn2fxB3NggnPF_dob), [page](https://inst.eecs.berkeley.edu/~ee123/sp15/)
-* [Signals & Systems (Oppenheim, Willsky, Hamid)](https://www.amazon.com/Signals-Systems-Edition-Alan-Oppenheim/dp/0138147574)
+* [Signals & Systems (Oppenheim, Willsky, Nawab)](https://www.amazon.com/Signals-Systems-Edition-Alan-Oppenheim/dp/0138147574)
 * [Discrete-Time Signal Processing (2nd Edition) (Oppenheim, Schafer, Buck)](https://www.amazon.com/Discrete-Time-Signal-Processing-Edition-Prentice-Hall/dp/0137549202)
 * [Data analysis lecturelets (Mike X Cohen)](https://www.youtube.com/@mikexcohen1)
 
```

<details>
<summary>Evidence and limitations</summary>

<p>ISBN 0138147574 is Signals &amp; Systems, 2nd edition (1997), by Alan V. Oppenheim and Alan S. Willsky, &#x27;with S. Hamid Nawab&#x27;. The label gives the third author as &#x27;Hamid&#x27;, which is his middle name; his surname is Nawab. The suggestion corrects only the author parenthetical.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:0138147574&amp;format=json&amp;jscmd=data — Open Library: &#x27;Signals &amp; systems&#x27;, 1997, by_statement &#x27;Alan V. Oppenheim, Alan S. Willsky, with S. Hamid Nawab.&#x27;</p>

<p>https://www.amazon.com/Signals-Systems-Edition-Alan-Oppenheim/dp/0138147574 — Amazon captcha to automated requests, so the listing was not read.</p>

<p>Caveats: The Signal Processing section is not alphabetized, so the parenthetical change has no ordering impact.; Amazon reachability was not confirmed.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Neuromatch Academy (NMA) 2026 Summer Schools — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -365,7 +365,7 @@
 ## Schools & Summer Courses
 
 * [NeuroTech MicroCredentials Course](https://neurotechmicrocreds.com/): An accredited series of theoretical and hands-on courses on Neurotechnology, offered by NeuroTechX and Queens University.
-* [Neuromatch Academy (NMA) 2026 Summer Schools](https://neuromatch.io/courses/): An online, community-driven set of summer schools in computational sciences and neuroengineering.
+* [Neuromatch Academy (NMA) Summer Schools](https://neuromatch.io/courses/): An online, community-driven set of summer schools in computational neuroscience, deep learning, NeuroAI and related computational sciences.
 * [Sinxpress summer schools](https://sincxpress.com/summerschool.html) by Mike X. Cohen
 * [Brainhack 2026](https://brainhack.org/): A community-driven, online, and in-person school for neurotech enthusiasts, happening in many cities around you!
 * Recurring summer schools or community-maintained lists of Neurotech-related summer schools
```

<details>
<summary>Evidence and limitations</summary>

<p>The URL is the correct official courses page and the fit is fine. Two claims are wrong. First, the year &#x27;2026&#x27; in the name is stale: it is now Nov 2026 and the page lists the next sessions for July 2027 and 2028. Second, &#x27;neuroengineering&#x27; matches none of the listed courses (Computational Neuroscience, Deep Learning, NeuroAI, Computational Behaviour, Computational Tools for Climate Science). Suggest a name without a year and an accurate topic list.</p>

<p>https://neuromatch.io/courses/ — &#x27;Each July, Neuromatch Academy offers immersive online courses that build core skills in computational neuroscience, and artificial intelligence and machine learning.&#x27; The course table lists CompNeuro, Deep Learning, NeuroAI, Climate Science and Computational Behaviour. Next dates are 5-23 July 2027 and 10-28 July 2028. No neuroengineering course is listed.</p>

<p>Caveats: Course topics may change in future years. The proposed wording avoids listing every course.</p>

</details>

<h3>Sinxpress summer schools — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -366,7 +366,7 @@
 
 * [NeuroTech MicroCredentials Course](https://neurotechmicrocreds.com/): An accredited series of theoretical and hands-on courses on Neurotechnology, offered by NeuroTechX and Queens University.
 * [Neuromatch Academy (NMA) 2026 Summer Schools](https://neuromatch.io/courses/): An online, community-driven set of summer schools in computational sciences and neuroengineering.
-* [Sinxpress summer schools](https://sincxpress.com/summerschool.html) by Mike X. Cohen
+* [Sincxpress summer schools](https://sincxpress.com/summerschool.html) by Mike X. Cohen
 * [Brainhack 2026](https://brainhack.org/): A community-driven, online, and in-person school for neurotech enthusiasts, happening in many cities around you!
 * Recurring summer schools or community-maintained lists of Neurotech-related summer schools
   * [List maintained by N. Schwar](https://nschawor.github.io/posts/2024/neuro-summer-schools/)
```

<details>
<summary>Evidence and limitations</summary>

<p>The name is misspelled. The official site and brand is &#x27;Sincxpress&#x27; (the URL is already correct). Separately, the page says the summer school will not take place in 2026. It still describes the 2025 ANTS (Analyzing Neural Time Series, LFP/EEG/MEG) course. Whether it will run again is unknown, so the maintainer should decide whether to keep a currently paused offering. That question does not affect the spelling fix.</p>

<p>https://sincxpress.com/summerschool.html — Title &#x27;Sincxpress by Mike X Cohen&#x27;. &#x27;Note: Summer school will not take place in 2026 due to changes in my employment situation.&#x27; It still lists the 2025 ANTS course (11-15 August) and the LAN course as &#x27;tba&#x27;.</p>

<p>Caveats: No official statement says whether the summer school will resume in 2027 or later. This is a pause, not an affirmative discontinuation, so removal is not supported.; The entry&#x27;s description is only the attribution &#x27;by Mike X. Cohen&#x27;, so the description needs no change.</p>

</details>

<h3>Brainhack 2026 — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -367,7 +367,7 @@
 * [NeuroTech MicroCredentials Course](https://neurotechmicrocreds.com/): An accredited series of theoretical and hands-on courses on Neurotechnology, offered by NeuroTechX and Queens University.
 * [Neuromatch Academy (NMA) 2026 Summer Schools](https://neuromatch.io/courses/): An online, community-driven set of summer schools in computational sciences and neuroengineering.
 * [Sinxpress summer schools](https://sincxpress.com/summerschool.html) by Mike X. Cohen
-* [Brainhack 2026](https://brainhack.org/): A community-driven, online, and in-person school for neurotech enthusiasts, happening in many cities around you!
+* [Brainhack](https://brainhack.org/): A community-driven series of hybrid (online and in-person) hackathon/unconference events bridging neuroscience and data science, held in many cities worldwide.
 * Recurring summer schools or community-maintained lists of Neurotech-related summer schools
   * [List maintained by N. Schwar](https://nschawor.github.io/posts/2024/neuro-summer-schools/)
   * [List maintained by N. Biswas](https://nayanika-biswas.notion.site/58f1530bd891475eb92f1e2e4984022f?v=83fc50c53b3a4191aa6f7cdf8d9b4e40)
```

<details>
<summary>Evidence and limitations</summary>

<p>The URL is official and Brainhack is relevant. The entry has two problems. The name pins &#x27;2026&#x27;, but the site&#x27;s newest listed event is Brainhack Global 2025 (Nov-Dec 2025 through spring 2026), and brainhack.org/global2026/ returns 404. The description calls Brainhack a &#x27;school for neurotech enthusiasts&#x27;, but Brainhack describes itself as hackathon/unconference-style events that bridge data science and neuroscience, with an educational track. Suggest dropping the year and correcting the description.</p>

<p>https://brainhack.org/ — The events list starts with &#x27;Brainhack Global 2025 Hybrid (Virtual and/or In-person) Brainhack events occuring at all around the world in Fall 2025 into Spring 2026&#x27;. No 2026 edition is listed.</p>

<p>https://brainhack.org/about.html — &#x27;The purpose of Brainhack is to bridge the data science and neuroscience research communities…&#x27; &#x27;These collaborative workshops combine elements of Hackathons and Unconferences, with a variety of educational activities…&#x27;</p>

<p>https://brainhack.org/global2025/ — Brainhack Global 2025, November - December, with local hosted events. &#x27;Brainhack is a unique event format that convenes researchers from across the globe…&#x27;</p>

<p>Caveats: A 2026 Brainhack Global may be announced later. The year-free name avoids future staleness.; This section is not alphabetically ordered, so dropping the year does not move the entry.</p>

</details>

<h3>List maintained by N. Schwar — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -369,7 +369,7 @@
 * [Sinxpress summer schools](https://sincxpress.com/summerschool.html) by Mike X. Cohen
 * [Brainhack 2026](https://brainhack.org/): A community-driven, online, and in-person school for neurotech enthusiasts, happening in many cities around you!
 * Recurring summer schools or community-maintained lists of Neurotech-related summer schools
-  * [List maintained by N. Schwar](https://nschawor.github.io/posts/2024/neuro-summer-schools/)
+  * [List maintained by N. Schaworonkow](https://nschawor.github.io/posts/2024/neuro-summer-schools/)
   * [List maintained by N. Biswas](https://nayanika-biswas.notion.site/58f1530bd891475eb92f1e2e4984022f?v=83fc50c53b3a4191aa6f7cdf8d9b4e40)
 
 ## Other Resources
```

<details>
<summary>Evidence and limitations</summary>

<p>The author is Natalie Schaworonkow, so &#x27;N. Schwar&#x27; is a misspelling of the maintainer&#x27;s name. The linked post still points to the same Google Sheet that she updated for 2026 in a Dec 2025 post, so the list is live and maintained. Optionally, the URL could point to the newer post https://nschawor.github.io/posts/2025/summer_schools_2026/, which links the same sheet.</p>

<p>https://nschawor.github.io/posts/2024/neuro-summer-schools/ — Title &#x27;list of neuro / EEG / MEG summer schools 2025 - nschawor&#x27;. It links the Google Sheet docs.google.com/spreadsheets/d/1nezjxkU8kGsA9MUI3Eph60s303VwfQLqMSNrSnnRSzk. The footer reads &#x27;© 2026 Natalie Schaworonkow&#x27;.</p>

<p>https://nschawor.github.io/posts/2025/summer_schools_2026/ — &#x27;summer schools &amp; short courses 2026&#x27;, December 19, 2025, &#x27;updated for 2026!&#x27;. It links the same spreadsheet ID and is credited to Natalie Schaworonkow.</p>

<p>Caveats: The Google Sheet contents were not opened. Currency is inferred from the author&#x27;s Dec 2025 update post.</p>

</details>

<h3>Novel Neurotechnologies Intervening in the Brain — update</h3>

```diff
--- a/README.md
+++ b/README.md
@@ -374,7 +374,7 @@
 
 ## Other Resources
 * [Neuroscience Duke Course (Coursera)](https://www.coursera.org/learn/medical-neuroscience)
-* [Novel Neurotechnologies Intervening in the Brain](https://web.archive.org/web/20230610175248/https://www.nuffieldbioethics.org/wp-content/uploads/2013/06/Novel_neurotechnologies_report_PDF_web_0.pdf)
+* [Novel Neurotechnologies Intervening in the Brain](https://www.nuffieldbioethics.org/publication/novel-neurotechnologies-intervening-in-the-brain/)
 * [Augment Human Cognition by optimizing cortical oscillations](https://pmc.ncbi.nlm.nih.gov/articles/PMC4072086/)
 * [Open Neuroscience](https://open-neuroscience.com/) - a user-driven database of Open Source/Science projects related to Neurosciences
 * [Awesome-BCI-Reviews](https://github.com/okbalefthanded/awesome-bci-reviews) - Curated list of Brain-Computer Interface peer-reviewd published reviews and surveys ordered by year of publication.
```

<details>
<summary>Evidence and limitations</summary>

<p>The original nuffieldbioethics.org PDF path now returns 404 (which is why the entry uses a Wayback link). The Nuffield Council has a live official publication page for &#x27;Novel neurotechnologies: intervening in the brain&#x27; (2013) that links the report PDF on its CDN. That PDF is the same size as the archived copy (4,022,809 bytes). This dated report remains a valid historical ethics resource, so pointing to the official page is better than the archive.</p>

<p>https://web.archive.org/web/20230610175248/https://www.nuffieldbioethics.org/wp-content/uploads/2013/06/Novel_neurotechnologies_report_PDF_web_0.pdf — HTTP 200, application/pdf, 4,022,809 bytes.</p>

<p>https://www.nuffieldbioethics.org/wp-content/uploads/2013/06/Novel_neurotechnologies_report_PDF_web_0.pdf — The original path returns HTTP 404.</p>

<p>https://www.nuffieldbioethics.org/publication/novel-neurotechnologies-intervening-in-the-brain/ — HTTP 200. The official page &#x27;Novel neurotechnologies: intervening in the brain – Nuffield Council on Bioethics&#x27; (2013) links Novel-neurotechnologies-report.pdf, an executive summary and a short guide on cdn.nuffieldbioethics.org.</p>

<p>https://cdn.nuffieldbioethics.org/wp-content/uploads/Novel-neurotechnologies-report.pdf — HTTP 200, application/pdf, 4,022,809 bytes. This is the same size as the archived PDF.</p>

<p>Caveats: Identity is inferred from the official title and identical byte size. The two PDFs were not hash-compared.; The maintainer could link the direct CDN PDF instead if a PDF link is preferred.</p>

</details>

## Uncertain findings

<h3>BCILab — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Wiki and README support the identity and MATLAB/BCI category. The README explicitly says active development ended in 2017 while critical updates continue. Contribution guidelines request actively maintained resources. That distinction needs curator interpretation; the absence of a false description does not settle rule compliance. Hold from the completed baseline pending that decision, not automatic removal.</p>

<p>https://github.com/sccn/BCILAB/wiki/BCILAB-documentation — Page renders &#x27;Open Source Matlab Toolbox for Brain-Computer Interface research&#x27; with a quick-start guide. The download instructions point to ftp://sccn.ucsd.edu/pub/bcilab.</p>

<p>https://raw.githubusercontent.com/sccn/BCILAB/devel/README.md — &#x27;MATLAB Toolbox for Brain-Computer Interface Research... This toolbox is no longer actively developed as of 2017. However, critical updates are still performed.&#x27;</p>

<p>https://api.github.com/repos/sccn/BCILAB — archived false, default branch devel, pushed_at 2021-10-04.</p>

<p>Blocking questions: Wiki and README support the identity and MATLAB/BCI category. The README explicitly says active development ended in 2017 while critical updates continue. Contribution guidelines request actively maintained resources. That distinction needs curator interpretation; the absence of a false description does not settle rule compliance. Hold from the completed baseline pending that decision, not automatic removal.</p>

<p>Caveats: Maintenance is minimal per the official README. The maintainer may weigh this against the &#x27;actively maintained&#x27; quality guideline; it is not grounds for removal on its own.; The wiki&#x27;s FTP download link was not tested; the GitHub repo itself provides the code.</p>

<p>Independent source check: Wiki and README support the identity and MATLAB/BCI category. The README explicitly says active development ended in 2017 while critical updates continue. Contribution guidelines request actively maintained resources. That distinction needs curator interpretation; the absence of a false description does not settle rule compliance. Hold from the completed baseline pending that decision, not automatic removal.</p>

<p>https://github.com/sccn/BCILAB/wiki/BCILAB-documentation — Live wiki describes an open-source Matlab BCI research toolbox and provides a quick-start guide.</p>

<p>https://github.com/sccn/BCILAB/blob/devel/README.md — README distinguishes ended active development from continued critical updates.</p>

<p>https://github.com/NeuroTechX/awesome-bci/blob/master/CONTRIBUTING.md — Quality standards ask for actively maintained resources.</p>

</details>

<h3>Cloudbrain — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The listed site http://getcloudbrain.com/ could not be fetched live: the sandbox proxy returned 502, and HTTPS failed at CONNECT. That failure alone is not conclusive. However, the Wayback Machine shows the domain redirecting to an unrelated site (getallitinfo.com) by 2025-03. The 2016 archive was the CloudBrain project page and linked github.com/marionleborgne/cloudbrain. The code survives on GitHub, but the canonical repository is ambiguous. PyPI &#x27;cloudbrain&#x27; (0.0.18) names github.com/cloudbrain/cloudbrain as its homepage, while the original site linked marionleborgne/cloudbrain. Both repositories show 1,126 commits and a last commit on 2018-08-28. A URL update is likely warranted, but the destination needs confirming first.</p>

<p>http://getcloudbrain.com/ — The live fetch returned 502 through the proxy, and HTTPS gave &#x27;CONNECT tunnel failed, response 502&#x27;. I could not read the current content.</p>

<p>https://web.archive.org/web/20250319092535/http://getcloudbrain.com/ — The Wayback capture from 2025-03-19 is a 301 redirect to https://www.getallitinfo.com/, an unrelated domain. The 2025-01 capture showed only a bot-verification page.</p>

<p>https://web.archive.org/web/2016/http://getcloudbrain.com/ — The 2016 capture shows &#x27;Cloudbrain is a free and open-source platform for wearable data analytics&#x27; and links github.com/marionleborgne/cloudbrain.</p>

<p>https://pypi.org/pypi/cloudbrain/json — PyPI cloudbrain 0.0.18 lists its Homepage as https://github.com/cloudbrain/cloudbrain.</p>

<p>https://github.com/cloudbrain/cloudbrain — Returns 200 with the title &#x27;cloudbrain/cloudbrain: Open-source platform for wearable analytics&#x27;. It shows 1,126 commits and was not detected as a fork. The last commit is dated 2018-08-28.</p>

<p>https://github.com/marionleborgne/cloudbrain — Returns 200 with the title &#x27;marionleborgne/cloudbrain: Platform for real-time wearables data analysis -- like EEG or ECG.&#x27; It shows 1,126 commits, with the same 2018-08-28 last commit. The README covers real-time sensor streaming/analysis and Muse support.</p>

<p>Blocking questions: The current live content of getcloudbrain.com could not be read (proxy 502). The repurposed-domain conclusion rests on a 2025 Wayback redirect capture.; It is unresolved which GitHub repository is canonical. cloudbrain/cloudbrain is named by PyPI, and marionleborgne/cloudbrain was linked by the original site. They appear to be mirrors.</p>

<p>Caveats: The project shows no commits since 2018. That says nothing about relevance, but it bears on the &#x27;actively maintained&#x27; quality standard.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>NeuroPrime — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>https://github.com/nmc-costa/neuroprime returned 404 on two checks. The owner account nmc-costa still exists, and another of its repositories (iclasses) returns 200. Search-engine indexes and the 2021 papers describe NeuroPrime as a Python framework for real-time HCI/BCI neurofeedback, so it is relevant. The repository may have been deleted, renamed or made private. I found no official successor or new location, and a 404 alone is not affirmative evidence of removal.</p>

<p>https://github.com/nmc-costa/neuroprime — HTTP 404 on two separate fetches.</p>

<p>https://github.com/nmc-costa — The owner profile returns 200. github.com/nmc-costa/iclasses returns 200, so the account is active. No neuroprime repository appeared in the scraped repository listing, though that listing may be incomplete because the GitHub API was rate-limited.</p>

<p>https://www.researchgate.net/publication/355138304_NeuroPrime_a_Pythonic_framework_for_the_priming_of_brain_states_in_self-regulation_protocols — A search result for the 2021 IEEE SeGAH paper &#x27;NeuroPrime: a Pythonic framework for the priming of brain states in self-regulation protocols&#x27; (da Costa, Bicho, Dias). I did not open the page itself.</p>

<p>Blocking questions: The repository&#x27;s current status (deleted, private, renamed or transferred) is unknown, and no official new location was found. A recheck or a query to the author is needed before any update or removal.</p>

<p>Caveats: The GitHub API was rate-limited, so I could not confirm rename or transfer metadata. A Zenodo search returned no usable result.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Moonlight — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL can&#x27;t be reached. zzz.bwh.harvard.edu serves a TLS certificate for a different host (erisweb5.partners.org), and bypassing the certificate check only returns a generic hosting default page. Luna&#x27;s documentation has moved (zzz.nyspi.org/luna says &#x27;Moved to https://zzz-luna.org/luna/&#x27;), but no Moonlight page exists at either new host, and the current Luna overview lists LunaScope, scope, lunaC, lunapi and lunaR without mentioning Moonlight. The remnrem/moonlight GitHub repo still exists. Whether Moonlight is still offered and what its canonical URL should be remains unknown.</p>

<p>https://zzz.bwh.harvard.edu/luna/apps/moonlight/ — TLS fails: &#x27;subjectAltName does not match hostname zzz.bwh.harvard.edu&#x27; (certificate CN=erisweb5.partners.org). With verification disabled it returns a default hosting landing page.</p>

<p>https://zzz.nyspi.org/luna/ — Returns &#x27;Moved to https://zzz-luna.org/luna/&#x27;. The /luna/apps/moonlight/ path there returns 404.</p>

<p>https://zzz-luna.org/luna/ — The current Luna docs overview lists LunaScope (GUI), scope (JupyterLab viewer), lunaC, lunapi and lunaR. Moonlight is not mentioned, and /luna/apps/moonlight/ returns 404.</p>

<p>https://github.com/remnrem/moonlight — The repo exists, titled &#x27;Moonlight/Luna viewer&#x27;. The README has Docker build notes. The latest commit is dated 2024-11-29.</p>

<p>Blocking questions: No official current Moonlight documentation URL was found. Pointing to the GitHub repo or replacing it with LunaScope would need confirmation from the Luna maintainers.</p>

<p>Caveats: The bwh.harvard.edu failure could be a temporary hosting or TLS misconfiguration and should be rechecked.; LunaScope looks like the current GUI, but I found no official statement that it succeeds Moonlight, so I don&#x27;t recommend a replacement.; Moonlight is a sleep/polysomnography viewer, so its relevance to BCI is indirect.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>DIY Electrode Design — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The OSH Park shared-project URL returns HTTP 200, but the page content is rendered by JavaScript: the raw HTML has no project title or description. OSH Park&#x27;s API returns &#x27;Not Authorized&#x27;. I couldn&#x27;t confirm the project still exists, that it is an EEG electrode design, or who made it.</p>

<p>https://oshpark.com/shared_projects/h2i1xBaW — HTTP 200, but the page shell has the title &#x27;OSH Park ~&#x27; and an empty meta description. No project content was readable without JavaScript.</p>

<p>Caveats: A 200 response from the app shell doesn&#x27;t prove the shared project still exists.; Checking needs a browser that runs JavaScript, or a look by the maintainer.</p>

</details>

<h3>IDUN Dryode — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The OpenBCI shop page returned HTTP 429 (rate-limited) every time, so I couldn&#x27;t read it directly. Search snippets show the &#x27;IDUN Dryode Alpha Kit&#x27; is still listed but marked sold out. It is described as dry electrodes for ECG, EMG and facial EEG, used with adhesive patches. The forum and third-party snippets I found only say IDUN may have dropped the stand-alone product, with no official confirmation. So it&#x27;s unresolved whether the product can still be bought or whether the name should become &#x27;Alpha Kit&#x27;.</p>

<p>https://shop.openbci.com/products/idun-dryode-kit — HTTP 429 from both curl and WebFetch (Retry-After: 60), so no content was read. Search snippet: title &#x27;IDUN Dryode™ Alpha Kit&#x27;, reportedly sold out, &#x27;research-grade signal quality for ECG, EMG, and facial EEG data&#x27;, kit includes adhesive patches.</p>

<p>https://dryode.tech/ — The IDUN Dryode site couldn&#x27;t be reached (curl status 000), so I couldn&#x27;t check for an official discontinuation notice.</p>

<p>Caveats: Being sold out doesn&#x27;t mean the product is discontinued. Recheck the shop page after the rate limit clears.; Search snippets suggest the description (&#x27;Adhesive dry electrodes for EEG&#x27;) is broadly accurate.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Hitachi Hightech — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Direct fetches returned 403. Search-indexed content shows the listed Hitachi High-Tech &#x27;/products/ict-solution/&#x27; section covers Materials Informatics, Chemicals Informatics and the ExTOPE IoT lab-instrument portal, not NIRS or optical topography. So the link probably no longer points to a NIRS product. Hitachi&#x27;s fNIRS lines were ETG optical topography (Hitachi Medical/Healthcare, which became part of Fujifilm Healthcare in 2021) and the WOT wearables (one source says WOT-100 sales moved to NeU Corp). I found no official current page or documented successor, so I can&#x27;t propose a replacement or removal.</p>

<p>https://www.hitachi-hightech.com/global/en/products/ict-solution/ — HTTP 403 from curl and WebFetch, so the content wasn&#x27;t read directly.</p>

<p>https://www.hitachi-hightech.com/global/en/products/ict-solution/randd/mi/ — Search index: the ict-solution section holds Materials Informatics, Chemicals Informatics and ExTOPE (IoT Service Portal). No NIRS products appear in the indexed results.</p>

<p>https://www.hitachi-hightech.com/global/about/news/2016/nr20160224.html — 2016 Hitachi High-Tech news release (seen in search results) announcing the WOT-HS wearable optical topography (NIRS) system. This shows the company did sell NIRS products before.</p>

<p>https://www.accessdata.fda.gov/cdrh_docs/pdf17/K172492.pdf — FDA 510(k) clearance K172492 (Aug 2018) for the Hitachi ETG-4100 optical topography system. The applicant was Hitachi Healthcare Americas.</p>

<p>Blocking questions: No verified current official page for Hitachi or a successor&#x27;s fNIRS products, so no replacement URL can be proposed.; The claim that the ict-solution page has no NIRS content comes from search-index snippets, not a direct read.</p>

<p>Caveats: Neither the listed page nor any official page on current Hitachi or Fujifilm NIRS availability could be read directly.; Third-party sources (NeU Corp handling WOT-100, Fujifilm taking over Hitachi&#x27;s medical business) were not checked against official announcements.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Medtronic — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>curl requests to the listed Medtronic URL return an Akamai &#x27;Incorrect Browser&#x27; bot-block page (HEAD gives 403), so the page could not be read directly. Through an alternate fetch, Medtronic&#x27;s homepage lists Deep Brain Stimulation and Spinal Cord Stimulation but does not mention transcranial electrical stimulation. The &#x27;tES&#x27; claim is unconfirmed and may be inaccurate. The site appears to use /en-us/ paths now, but the canonical replacement URL was not verified.</p>

<p>http://www.medtronic.com/us-en/index.html — curl returns HTTP 200 with an &#x27;Incorrect Browser&#x27; bot-block page. HEAD returns 403 from AkamaiGHost. Content could not be read.</p>

<p>https://www.medtronic.com/ — Fetched through an alternate tool. Lists Deep Brain Stimulation (link /en-us/l/patients/treatments-therapies/deep-brain-stimulation.html), Spinal Cord Stimulation, Sacral Neuromodulation and Implantable Tibial Neuromodulation. No transcranial electrical stimulation therapy found.</p>

<p>Blocking questions: Whether Medtronic offers any tES product is unconfirmed, so the description correction (dropping &#x27;tES&#x27;) is not yet verified.; The canonical current URL (/us-en/ vs /en-us/) could not be confirmed because of bot blocking.</p>

<p>Caveats: Bot protection blocked direct reads. The absence of tES was seen on the homepage only, and a full product catalog search was not done.; The access failure does not mean the site is dead.</p>

</details>

<h3>Functional Ultrasound (FUS) — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>fultrasound.com could not be reached (HTTPS CONNECT 502 and HTTP 502 through the proxy on repeated attempts), and the Wayback Machine availability API reports no snapshots. Git history shows the 2026 refresh commit 4a728d5 changed this entry from http://fultrasound.eu/ to https://fultrasound.com/ and added the &#x27;Resource hub&#x27; description. fultrasound.eu also failed DNS resolution in this session. Search results describe fultrasound.eu as the Langevin Institute&#x27;s ERC FUSIMAGINE functional ultrasound site, but no evidence was found linking fultrasound.com to that project or showing it is a resource hub.</p>

<p>https://fultrasound.com/ — Unreachable: curl &#x27;CONNECT tunnel failed, response 502&#x27; (https, www) and HTTP 502 for http://. archive.org/wayback/available returned no archived snapshots.</p>

<p>https://fultrasound.eu/ — Alternate (prior) URL. WebFetch failed with getaddrinfo ENOTFOUND, and curl also failed. Search snippets describe it as the Langevin Institute FUSIMAGINE functional ultrasound imaging site.</p>

<p>https://en.wikipedia.org/wiki/Functional_ultrasound_imaging — Surfaced in search as a stable general reference on functional ultrasound imaging. Not read in full.</p>

<p>Blocking questions: The ownership and content of fultrasound.com are unknown, so the &#x27;Resource hub&#x27; description cannot be verified.; No reachable official successor was confirmed (fultrasound.eu also failed DNS here).</p>

<p>Caveats: Failures may be transient or caused by the network or proxy, so recheck before acting. An access failure does not prove the domain is dead.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Diffuse Optical Imaging pt. 2 — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The Google Drive file returns HTTP 401 to unauthenticated requests, both with and without the sharing parameter. Its content, current sharing permissions and existence could not be verified.</p>

<p>Caveats: A 401 may mean the file was made private, was deleted, or that Drive blocks anonymous automated fetches. A signed-in browser check is needed.; The legacy &#x27;0B-&#x27; file ID may also be affected by Google&#x27;s 2021 link-sharing security update, which needs resource keys.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>EEG studies with the raw data — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>studycatalog.org returned HTTP 403 from Cloudflare, so the catalog content and status could not be checked. The secondary link bigeeg.org resolves and still describes the BigEEG Consortium (HED and ESS standards).</p>

<p>http://www.bigeeg.org/ — HTTP 200. &#x27;BigEEG Workflow: Standards and tools for large-scale EEG analysis&#x27;. It promotes the HED tags and EEG Study Schema (ESS) standards.</p>

<p>https://frontiersin.org/articles/10.3389/fninf.2016.00007/full — Search summary of the 2016 Frontiers in Neuroinformatics paper: it describes studycatalog.org as a central catalog of over 850 GB of EEG data in ESS format.</p>

<p>Caveats: A 403 may be bot protection and is not proof of a dead site; recheck in a browser.; Whether studycatalog.org still hosts or points to ESS studies is unknown.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>RAM (DARPA) Invasive Recording Dataset from U. Penn — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>memory.psych.upenn.edu timed out or refused connections from both curl and WebFetch, so the page could not be read. Search results show the RAM page and a &#x27;RAM_Public_Data&#x27; page are indexed, with data from 251 subjects available by access request.</p>

<p>https://penntoday.upenn.edu/news/penns-restoring-active-memory-project-releases-extensive-human-brain-dataset — Search summary: Penn announced a public RAM intracranial recording and stimulation dataset (149 subjects in the first release).</p>

<p>https://memory.psych.upenn.edu/RAM_Public_Data — Search-result summary only, page not fetched: data from 251 Phase I/II subjects, available on request.</p>

<p>Caveats: The host was unreachable from this environment. This may be a temporary or network-specific failure, not a dead site; recheck.; A maintainer could consider linking RAM_Public_Data directly, but that page was not read here.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>EEG and MRI Course offered by OHBM — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL now redirects (two hops) to the OHBM homepage (pageid=1), so the specific course page is not reachable. Wayback shows page 3814 was an OHBM annual-meeting &#x27;Course Materials&#x27; page (e.g. the 2023 &#x27;EEG and MEG connectivity&#x27; course), still returning 200 as of June 2026. No official replacement URL was found. It is unknown whether this is a temporary site change or a permanent removal.</p>

<p>https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageID=3814&amp;activateFull=true — Redirects to https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageid=1 (the OHBM homepage). The pageid=3814 variant without activateFull also redirects to the homepage.</p>

<p>http://web.archive.org/web/20260618073812/https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageid=3814 — The June 2026 snapshot shows &#x27;Course Materials | Organization for Human Brain Mapping&#x27;, listing educational course materials by year and pointing onsite material to the OnDemand portal. 2023 courses include &#x27;EEG and MEG connectivity: Basic principles, state-of-the-art methods, and emerging vistas&#x27;.</p>

<p>Blocking questions: No current official URL for the course-materials page could be verified.; It is unclear whether the redirect to the homepage is temporary or permanent, so it needs a recheck.; BCI relevance is indirect (general neuroimaging education), which the maintainer may want to judge.</p>

<p>Caveats: Did not find or verify a new official URL for OHBM course materials or OnDemand.; The content covers neuroimaging broadly (EEG/MEG/MRI), not BCI specifically.</p>

</details>

<h3>Irene Vigué Guix — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>irenevigueguix.com now 301-redirects to sentipensarte.wordpress.com. That site is a Spanish-language personal site about (neuro)science, art and creativity: a reading tour, an &#x27;Artist&#x27;s Way&#x27; group and an art shop. I found no BCI content on the homepage or the &#x27;Sobre mí&#x27; page. The owner still lists &#x27;biomedical engineer, neuroscientist&#x27; among her labels, but whether the destination still serves BCI readers is unresolved.</p>

<p>http://www.irenevigueguix.com — Returns HTTP 301 with Location https://sentipensarte.wordpress.com/.</p>

<p>https://sentipensarte.wordpress.com/ — Titled &#x27;Irene Vigué-Guix&#x27;. Spanish homepage: &#x27;Desdibujando líneas entre: (NEURO)CIENCIA ARTE CREATIVIDAD&#x27;, with a book-reading tour, a workshop group and a SHOP for her art.</p>

<p>https://sentipensarte.wordpress.com/sobre-mi/ — The &#x27;About&#x27; page presents her as the artist &#x27;Eneri.Arte&#x27;. Her labels include &#x27;ingeniera biomédica, neurocientífica, artista sentipensante e ilustradora afectiva&#x27;. No BCI content is visible.</p>

<p>Blocking questions: It is unresolved whether the redirect destination still contains BCI-relevant blog content. That decides keep, update or remove.; There is no official statement that the former BCI blog content was retired or moved elsewhere.</p>

<p>Caveats: I did not review the RECURSOS page or older posts, so archived BCI content may exist on the WordPress site.; Whether the owner has a separate current BCI or academic page was not established.</p>

</details>

<h3>BrainTech — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The listed URL doesn&#x27;t reach a BrainTech conference page. http://conference.israelbrain.org/ returned 406 (Mod_Security) to one client and redirected to /404.html (&#x27;Page Not Found&#x27;) for another. israelbrain.org and www.israelbrain.org either failed to connect or returned a generic &#x27;Page cannot be displayed&#x27; error. I couldn&#x27;t read any official source about the current status of the BrainTech conference or of Israel Brain Technologies.</p>

<p>http://conference.israelbrain.org/ — Returns 406 Not Acceptable (Mod_Security) or redirects to http://conference.israelbrain.org/404.html, which shows &#x27;404 Error. Page Not Found.&#x27;</p>

<p>http://israelbrain.org/ — HTTP 200, but the 195-byte body reads &#x27;Error. Page cannot be displayed. Please contact your service provider&#x27;. The HTTPS and www variants failed to connect.</p>

<p>Blocking questions: No official source confirms whether BrainTech still runs or where it lives now. The URL needs a recheck, and an official current page needs to be identified before any update or removal.</p>

<p>Caveats: Failures like these can be temporary or caused by bot filtering, so they don&#x27;t prove the organization or event is gone.</p>

</details>

<h3>Brain Summit — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>brainsummit.com is reachable. It returned a 406 status but served its content. It describes a free online summit on mental health, trauma and addiction (&#x27;25+ experts show you the latest research, tools and techniques to upgrade your brain&#x27;), run by Erin Matlock. I found nothing on the page about brain–computer interfaces. Whether it meets the rule that resources be &#x27;directly related to Brain-Computer Interfaces&#x27; is a call for the maintainers.</p>

<p>https://brainsummit.com/ — Status 406 with full page content. Title is &#x27;Brain Summit | Brain Summit&#x27;. Text: &#x27;The Future Of Mental Health ... cutting edge treatment, tools, solutions and research in mental health, trauma and addiction ... Brain Summit broadcasts free and online.&#x27;</p>

<p>Blocking questions: It&#x27;s unclear whether this mental-health summit is relevant to BCI under the contribution rules.</p>

<p>Caveats: I didn&#x27;t check the page&#x27;s history to see whether it covered BCI topics when it was added.</p>

</details>

<h3>High-speed spelling with a noninvasive brain–computer interface — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Identity and relevance are confirmed: Chen et al. 2015, PNAS, a high-speed SSVEP speller, DOI 10.1073/pnas.1508080112. What is unresolved is whether the legacy /content/112/44/E6058.abstract URL still redirects to the article. Both curl and WebFetch got HTTP 403 behind a Cloudflare challenge, so the redirect could not be seen. The DOI currently resolves to pnas.org/doi/full/10.1073/pnas.1508080112. If a browser check shows the legacy path no longer redirects, update to the DOI URL.</p>

<p>https://api.crossref.org/works/10.1073/pnas.1508080112 — Crossref: title &#x27;High-speed spelling with a noninvasive brain–computer interface&#x27;, Proceedings of the National Academy of Sciences, issued 2015-10-19, authors Chen, Wang, Nakanishi, Gao, Jung, Gao.</p>

<p>https://doi.org/10.1073/pnas.1508080112 — 302 redirect to https://pnas.org/doi/full/10.1073/pnas.1508080112.</p>

<p>https://www.pnas.org/content/112/44/E6058.abstract — HTTP 403 with a &#x27;Just a moment...&#x27; Cloudflare challenge to both curl and WebFetch. The redirect behavior could not be observed.</p>

<p>Blocking questions: Not verified whether the legacy PNAS /content/ URL still redirects to the article.</p>

<p>Caveats: The 403 looks like bot protection, not a dead page. This needs a recheck, not removal.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Analyzing Neural Time Series Data (Cohen) — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The book is confirmed: Mike X Cohen, &#x27;Analyzing Neural Time Series Data: Theory and Practice&#x27; (MIT Press, 2014), and it fits Technical Books. What is unresolved is whether the legacy mitpress.mit.edu/books/... URL still resolves. It returned 403 to curl and WebFetch. The current-style URL (mitpress.mit.edu/9780262019873/...) and the direct.mit.edu DOI target also returned 403, which looks like bot blocking. A browser check is needed before switching to the ISBN-path URL or the DOI.</p>

<p>https://api.crossref.org/works/10.7551/mitpress/9609.001.0001 — Crossref: &#x27;Analyzing Neural Time Series Data&#x27;, author Cohen, issued 2014-01-17.</p>

<p>https://doi.org/10.7551/mitpress/9609.001.0001 — 302 redirect to https://direct.mit.edu/books/book/4013/Analyzing-Neural-Time-Series-DataTheory-and, which returned 403 to curl.</p>

<p>https://mitpress.mit.edu/books/analyzing-neural-time-series-data — HTTP 403 to both curl and WebFetch, so no redirect target was visible.</p>

<p>Blocking questions: Not verified whether the legacy MIT Press /books/ path still redirects. The canonical replacement URL was not confirmed accessible.</p>

<p>Caveats: A 403 from bot protection is not evidence of a dead link.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>lectures — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>Neither link in this multi-link entry is publicly accessible. YouTube reports the playlist does not exist, and the linked first video is private. The EE123 Spring 2015 course page now redirects to CalNet login. An archived 2024 Wayback copy of that course page links to the same playlist that is now gone. No official public replacement for the Berkeley EE123 lectures was found. The maintainer needs to find an official current source (or decide on removal) and edit this entry by hand.</p>

<p>https://www.youtube.com/playlist?list=PL-XXv-cvA_iCUQkarn2fxB3NggnPF_dob — YouTube alert: &#x27;The playlist does not exist.&#x27;</p>

<p>https://www.youtube.com/watch?v=6_-ljdxjwac&amp;list=PL-XXv-cvA_iCUQkarn2fxB3NggnPF_dob — playabilityStatus LOGIN_REQUIRED, reason &#x27;Private video&#x27;. oEmbed returned Forbidden.</p>

<p>https://inst.eecs.berkeley.edu/~ee123/sp15/ — 302 to /~ee123/archive/sp15/, which then 302s to auth.Berkeley.EDU CAS login. Not publicly readable.</p>

<p>http://web.archive.org/web/20240417212445/https://inst.eecs.berkeley.edu//~ee123/sp15/ — Archived &#x27;EE123: Digital Signal Processing&#x27; page (Michael Lustig). It links to the same YouTube playlist PL-XXv-cvA_iCUQkarn2fxB3NggnPF_dob.</p>

<p>Blocking questions: No official public successor for the lectures or the course page was found. Whether to substitute a Wayback link or remove the entry is the maintainer&#x27;s call.</p>

<p>Caveats: This is a complex entry with two links and a prose prefix, so it must be edited by hand.; Berkeley may still host the material for authenticated users, so lack of public access does not prove the course material is gone.</p>

</details>

<h3>List maintained by N. Biswas — uncertain</h3>

<details>
<summary>Evidence and limitations</summary>

<p>The Notion database is public and on topic: &#x27;Summer Schools for Neuroscience&#x27;, 18 rows with fields such as Offered By, Start/End, Deadline and Cost. However, the page and every row were last edited on 2024-03-27. The entry calls it a list &#x27;maintained by&#x27; N. Biswas, and whether it is still maintained is unresolved. There is no official notice that it has been abandoned.</p>

<p>https://nayanika-biswas.notion.site/58f1530bd891475eb92f1e2e4984022f?v=83fc50c53b3a4191aa6f7cdf8d9b4e40 — The public Notion API (getPublicPageData/syncRecordValues/queryCollection) shows: publicAccessRole reader, not deleted. Collection name &#x27;Summer Schools for Neuroscience&#x27;, 18 row pages. The newest last_edited_time is 2024-03-27, and the block itself was also last edited 2024-03-27.</p>

<p>Blocking questions: Unresolved: whether the owner still maintains the list or plans updates. No edits have been made since March 2024.</p>

<p>Caveats: The rendered page needs JavaScript, so it was read through Notion&#x27;s public API, not the visual page.; Row dates were not checked. The listed schools may be 2024 editions.</p>

</details>

<details>
<summary>64 unresolved keeps</summary>

These entries were not added to the baseline.

<h3>BCI2000 — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The BCI2000 wiki main page is live. It describes BCI2000 as a free, open-source, general-purpose real-time BCI research system that acquires and processes data, presents stimuli and feedback, and interfaces with outside devices, and it offers releases and source downloads. The C++/GUI suite description remains accurate.</p>

<p>https://www.bci2000.org/mediawiki/index.php/Main_Page — &#x27;BCI2000 is a free, open-source, general-purpose software system for brain-computer interface (BCI) research... can acquire and process data, present stimuli and feedback, and manage interaction with outside devices&#x27;. It offers downloads of the latest release and source code.</p>

<p>Caveats: The C++ implementation was not re-verified from source in this pass; this is long-documented BCI2000 architecture.; Downloads require a free user account.</p>

</details>

<h3>Brainstorm — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>A normal HTTPS fetch of neuroimage.usc.edu fails because the server&#x27;s TLS certificate has expired, which is a temporary TLS problem that warrants a recheck. Read with certificate checking disabled, the page returns 200, and its introduction matches the catalog description verbatim. The official GitHub repo brainstorm-tools/brainstorm3 is active (pushed 2026-11-05) and describes the same scope.</p>

<p>https://neuroimage.usc.edu/brainstorm/ — curl fails with &#x27;SSL certificate verify result: certificate has expired (10)&#x27;. Read with verification disabled, it returns 200: &#x27;Brainstorm is a collaborative, open-source application dedicated to the analysis of brain recordings: MEG, EEG, fNIRS, ECoG, depth electrodes and multiunit electrophysiology.&#x27;</p>

<p>https://api.github.com/repos/brainstorm-tools/brainstorm3 — archived false, pushed_at 2026-11-05. Description &#x27;Brainstorm software: MEG, EEG, fNIRS, ECoG, sEEG and electrophysiology&#x27;, homepage neuroimage.usc.edu/brainstorm.</p>

<p>https://raw.githubusercontent.com/brainstorm-tools/brainstorm3/master/README.md — &#x27;Brainstorm is a collaborative, open-source application dedicated to the analysis of brain recordings: MEG, EEG, fNIRS, ECoG, depth electrodes and animal electrophysiology.&#x27;</p>

<p>Caveats: The site&#x27;s expired certificate will cause browser warnings until USC renews it; recheck later. This is not a reason to remove or change the URL.; The GitHub README says &#x27;animal electrophysiology&#x27; where the website says &#x27;multiunit electrophysiology&#x27;; the catalog matches the website.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>MNE-Python — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>mne-tools/mne-python is canonical, active and not archived. It is the core open-source Python package for MEG/EEG/ECoG analysis and is clearly relevant. There is no description to check.</p>

<p>https://github.com/mne-tools/mne-python — Returns 200 with the title &#x27;mne-tools/mne-python: MNE: Magnetoencephalography (MEG) and Electroencephalography (EEG) in Python&#x27;.</p>

<p>https://raw.githubusercontent.com/mne-tools/mne-python/main/README.rst — The README says: &#x27;open-source Python package for exploring, visualizing, and analyzing human neurophysiological data such as MEG, EEG, sEEG, ECoG... machine learning, statistics, and more.&#x27;</p>

<p>Caveats: The pyproject.toml and examples tree were not inspected in detail. With no description to verify, they were not needed.</p>

</details>

<h3>iOS App Store — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Both store links resolve to the live Mind Monitor listing by James Clutterbuck, a real-time EEG app for Muse headbands with recording and OSC streaming. The app is relevant and the links are correct.</p>

<p>https://apps.apple.com/ca/app/mind-monitor/id988527143 — The App Store page lists Mind Monitor (developer James Clutterbuck): &#x27;Real-time EEG for every Muse headband, including Athena. Record, stream over OSC&#x27;. It is a paid app.</p>

<p>https://play.google.com/store/apps/details?id=com.sonicPenguins.museMonitor — The Google Play listing for Mind Monitor by James Clutterbuck shows 10K+ downloads, &#x27;Updated on Nov 1, 2025&#x27;, and is exclusively for Muse headbands.</p>

<p>Caveats: This is a multi-link, prose-prefixed entry. Any wording changes would need manual editing.; The app is third-party and not an official Interaxon app, as the listings state.</p>

</details>

<h3>Synchron Stentrode — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Synchron&#x27;s site confirms the Stentrode is an investigational implantable BCI delivered through a blood vessel (via the jugular vein) without open-brain surgery, and in clinical trials for people with paralysis. The description is accurate. Placement under EEG / Consumer and DIY Devices is a poor fit for an implanted clinical device, but that is a structural question for the maintainer.</p>

<p>https://synchron.com/ — &#x27;No open brain surgery: Synchron&#x27;s procedure works like a stent, guided through a blood vessel.&#x27; The Stentrode is &#x27;implanted via the jugular vein&#x27; and is &#x27;currently being assessed in clinical trials to restore communication, independence and agency for people living with paralysis&#x27;. It is labelled an investigational device.</p>

<p>Caveats: Section fit is questionable because it is not EEG and not a consumer device. Moving it would be a maintainer decision, not a factual correction.; This review assesses catalog accuracy, not clinical efficacy.</p>

</details>

<h3>Blino PiNaps — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The repo resolves and is the source of the Blino documentation site, which covers the Pi-Naps (Raspberry Pi) and Tee-Naps EEG maker boards. That fits RaspberryPi Framework, and there is no description to correct. The earlier snapshot failure seems to be a snapshot-tool problem: there is no root README.md (404), but the repo itself is readable.</p>

<p>https://github.com/BlinoTech/BlinoTech.github.io — Resolves to BlinoTech/BlinoTech.github.io: &#x27;This is the documentation for Blino&#x27;s maker products. The Blino website can be found at https://blino.io&#x27;. Contains about/, blog/, docs/ and index.html, and has no README.md.</p>

<p>https://raw.githubusercontent.com/BlinoTech/BlinoTech.github.io/master/docs/index.html — The docs page says it &#x27;covers both the Tee-Naps and Pi-Naps Blino EEG Maker Boards&#x27;.</p>

<p>https://github.com/BlinoTech/BlinoTech.github.io/commits.atom — The latest commit is dated 2022-03-23.</p>

<p>Caveats: The rendered site https://blino.io (from the CNAME) could not be checked: the sandbox proxy returned 502. Whether the live site and products are still available is unknown.; The link points to a website source repo rather than the rendered docs. If blino.io turns out to be live, the maintainer might prefer that URL.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Muse 2016, Muse 2, Muse S — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>choosemuse.com is the official Muse site and is still selling consumer EEG headbands. The entry has no description to correct. The current lineup on the site is Muse 2 and Muse S Athena (EEG+fNIRS).</p>

<p>https://choosemuse.com/ — Official store. Features &#x27;Muse S Athena: EEG and fNIRS in one headband&#x27; and Muse 2.</p>

<p>https://choosemuse.com/pages/compare — The compare page lists only Muse 2 and Muse S Athena.</p>

<p>Caveats: The name lists &#x27;Muse 2016&#x27;, which is not sold any more, and &#x27;Muse S&#x27;, which is now sold as Muse S Athena. Renaming to reflect current models is optional, because the older models are still real devices people use.; No official discontinuation notice for Muse 2016 was read.</p>

</details>

<h3>OpenBCI Ganglion, Cyton, Daisy, Galea — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>OpenBCI&#x27;s official shop still sells all four named products: Ganglion, Cyton, Daisy (as the Cyton + Daisy bundle) and Galea.</p>

<p>https://shop.openbci.com/ — Lists Galea ($42,980), Cyton Biosensing Board (8 channels), Cyton + Daisy Biosensing Boards (16 channels) and Ganglion Board (4 channels).</p>

<p>https://openbci.com/ — Returns 200. The page is a JavaScript app. Its meta description covers bio-sensing boards for EEG, EMG and ECG.</p>

<p>Caveats: Product pages beyond the shop listing were not read.</p>

</details>

<h3>Elemind — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Elemind&#x27;s official site sells a consumer sleep headband. It measures EEG and delivers closed-loop acoustic stimulation timed to the user&#x27;s brainwaves, so it fits the section as a consumer EEG wearable.</p>

<p>https://elemindtech.com/ — &#x27;Elemind rapidly and accurately measures EEG brain signals and delivers precise acoustic stimulation custom-tailored to your brain&#x27;s own natural rhythms&#x27;. Sold for $399.</p>

<p>Caveats: No developer or raw-data access was checked. The entry makes no claim about it.</p>

</details>

<h3>Wearable Sensing Dry Electrode EEG — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The http URL redirects to https://wearablesensing.com/, which is the official site for Wearable Sensing&#x27;s dry-electrode EEG (DSI) systems. The name is accurate.</p>

<p>https://wearablesensing.com/ — &#x27;Revolutionizing Dry Electrode EEG&#x27;. Offers dry EEG systems with up to 19 channels, plus high-density wet EEG and hybrid EEG+fNIRS. A plain curl first hit a Cloudflare block; a retry with browser headers returned 200.</p>

<p>Caveats: The listed URL uses http and redirects to https. Switching to https would be optional cleanup, not a correction.</p>

</details>

<h3>EGI High Density EEG — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>egi.com is still the official EGI (Electrical Geodesics, now Magstim EGI) site, and its navigation covers dense-array Geodesic EEG systems and Sensor Nets.</p>

<p>https://www.egi.com/ — Meta description cites EGI&#x27;s &#x27;proprietary dense array electroencephalography (dEEG) platform&#x27;. The footer reads &#x27;© 2025 Magstim EGI&#x27;.</p>

<p>https://www.egi.com/research-division/geodesic-eeg-systems — This URL returned 404, but the site navigation it served lists Geodesic EEG System 400 series, Geodesic Sensor Nets, Dense Array EEG Neuroimaging and Net Station.</p>

<p>Caveats: The homepage body is mostly rendered by JavaScript, so its product content was only seen through navigation and meta text.</p>

</details>

<h3>FreeEEG32 — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Crowd Supply page could not be read, but the official FreeEEG32 GitHub repo points to that Crowd Supply URL. The project is an open-source 32-channel EEG board, which supports the description. The access failure is a bot challenge, not evidence that the page is dead.</p>

<p>https://raw.githubusercontent.com/neuroidss/FreeEEG32-beta/master/README.md — README: &#x27;FreeEEG32 Beta, launching soon on [Crowd Supply](https://www.crowdsupply.com/neuroidss/freeeeg32)!&#x27;. It confirms the listed URL is the project&#x27;s official campaign page.</p>

<p>https://www.crowdsupply.com/neuroidss/freeeeg32 — curl and WebFetch both got HTTP 403 (a Cloudflare &#x27;Just a moment&#x27; challenge). The content was not read.</p>

<p>Caveats: Campaign or shipping status on Crowd Supply is unknown.; The 32-channel and open-source claims rest on the GitHub README and search results (4×AD7771, 32 channels), not on the Crowd Supply page.; Recheck the Crowd Supply page from a normal browser.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>HackEEG — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>HackEEG&#x27;s official hardware repo links this exact Crowd Supply campaign, and describes an open-hardware ADS1299 Arduino shield for EEG. The Crowd Supply page itself was blocked by a bot challenge and was not read.</p>

<p>https://raw.githubusercontent.com/starcat-io/hackeeg-shield/master/README.md — &#x27;HackEEG - ADS1299 Shield ... available in the HackEEG CrowdSupply crowdfunding campaign (https://www.crowdsupply.com/starcat/hackeeg/)&#x27;. Up to 4 stacked shields give 32 EEG channels, and the hardware is under the CERN OHL v1.2.</p>

<p>https://www.crowdsupply.com/starcat/hackeeg — curl and WebFetch both got HTTP 403 (a Cloudflare challenge). The content was not read.</p>

<p>Caveats: Current purchase availability on Crowd Supply is unknown.; A search snippet says the starcat-io repos were last updated in 2021–2023. That was not verified directly, and it does not by itself make the resource obsolete.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>ANT Neuro — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ANT Neuro&#x27;s official site is live and still sells EEG amplifiers, caps and software for research, and it names BCI as a use. The entry fits its section.</p>

<p>https://www.ant-neuro.com — HTTP 200 (adds a trailing slash). Title: &#x27;ANT Neuro | EEG Systems, EEG Caps &amp; High-Density EEG, Neuronavigation&#x27;. Meta description mentions EEG devices from 8 to 256 channels for neuroscience, sleep, BCI and VR EEG.</p>

<p>Caveats: Only the homepage was checked.</p>

</details>

<h3>Florida Research Instruments — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Florida Research Instruments&#x27; shop is live and sells EEG sensors and supplies, which fits EEG Parts &amp; Supplies. The bare domain redirects to www, which is cosmetic.</p>

<p>https://fri-fl-shop.com/ — Redirects to https://www.fri-fl-shop.com/ (HTTP 200). Meta description: &#x27;Sensors and supplies for EEG, Physiological and Biomedical Research!&#x27;</p>

<p>Caveats: Optionally use https://www.fri-fl-shop.com/ as the URL to match the redirect target.</p>

</details>

<h3>TI ADS1299EEG-FE — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>TI&#x27;s ADS1299EEGFE-PDK page is live. It describes a demonstration kit for the ADS1299, an 8-channel, 24-bit ADC with features for EEG applications. The description (&#x27;Analog Front End for EEG solutions&#x27;) still applies. The link goes to the evaluation kit page, not the chip&#x27;s product page, which is a small mismatch but not a factual error.</p>

<p>https://www.ti.com/tool/ADS1299EEGFE-PDK — HTTP 200. &#x27;The ADS1299EEGFE-PDK is a demonstration kit for the ADS1299, an eight channel, simultaneous sampling, 24-bit, delta-sigma ADC ... The ADS1299 contains the features commonly required for electroencephalography (EEG) applications.&#x27; Its listed evaluation software targets Windows XP/7.</p>

<p>Caveats: The &#x27;e.g., in OpenBCI Cyton&#x27; claim wasn&#x27;t re-checked against OpenBCI documentation in this pass.; No lifecycle status (Active or NRND) was found on the kit page. The kit software lists old Windows versions.; Optional: the maintainer could link the chip page (ti.com/product/ADS1299) instead of the kit.</p>

</details>

<h3>Bio-Medical — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Bio-Medical EEG electrodes page is live and still sells EEG and neurofeedback supplies, which matches &#x27;For supplies and consumables&#x27;.</p>

<p>https://bio-medical.com/supplies/eeg-electrodes.html — HTTP 200, no redirect. Title: &#x27;EEG Electrodes - Supplies&#x27;. Meta: &#x27;Bio-Medical Instruments carries a wide variety of biofeedback and neurofeedback equipment and supplies. We carry a full line of EEG, qEEG...&#x27;</p>

</details>

<h3>CortiVision — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>CortiVision&#x27;s site is live and sells portable, wireless fNIRS devices, which fits the NIRS section.</p>

<p>https://www.cortivision.com/ — HTTP 200. Title: &#x27;fNIRS. Devices to Measure Brain Activity - Cortivision&#x27;. Meta: &#x27;Fully portable and wireless fNIRS devices to measure brain activity.&#x27;</p>

</details>

<h3>Natus Neuro — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Direct fetches of natus.com returned HTTP 403, which looks like bot blocking. Search-indexed official natus.com pages show Natus Neuro still sells EEG systems: NeuroWorks software, BrainWatch, Brain Monitor amplifier, BRAIN QUICK, Trex HD and EEG supplies. That supports listing it as an EEG device maker.</p>

<p>https://natus.com/ — HTTP 403 from curl and WebFetch, so the content wasn&#x27;t read directly. This looks like access blocking, not a dead site.</p>

<p>https://natus.com/neuro/ — Direct fetch also returned 403. The search index shows the title &#x27;Neuro Solutions - Neurodiagnostics Products&#x27; and EEG categories: routine, LTM, ambulatory, point-of-care, animal EEG and EEG supplies.</p>

<p>https://www.massdevice.com/natus-neuro-launches-brainwatch-ai-eeg/ — Third-party news (headline seen in search results only) of &#x27;Natus Neuro&#x27; launching its BrainWatch point-of-care EEG, which confirms the &#x27;Natus Neuro&#x27; name is in current use.</p>

<p>Caveats: The evidence comes from search-engine snippets, not a direct page read, so a manual browser check is recommended.; Natus mainly sells clinical neurodiagnostic products. Research and BCI use is secondary, but that&#x27;s not a reason to remove it.; Optional: https://natus.com/neuro/ would point more precisely to the neuro product line.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Comparison of different types of electrodes — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The ScienceDirect link returned 403 (publisher bot blocking). Crossref metadata confirms the PII is a real paper: Tallgren, Vanhatalo, Kaila &amp; Voipio, &#x27;Evaluation of commercially available electrodes and gels for recording of slow EEG potentials&#x27;, Clinical Neurophysiology, April 2005. The entry&#x27;s title fairly paraphrases this electrode-comparison paper. As a dated reference in EEG Parts &amp; Supplies, it is still useful.</p>

<p>http://www.sciencedirect.com/science/article/pii/S1388245704003906 — HTTP 403 to automated requests. This is publisher bot blocking, not a dead link.</p>

<p>https://api.crossref.org/works?filter=alternative-id:S1388245704003906&amp;rows=2 — Crossref matches PII S1388245704003906 to DOI 10.1016/j.clinph.2004.10.001: &#x27;Evaluation of commercially available electrodes and gels for recording of slow EEG potentials&#x27;, Clinical Neurophysiology, 2005-04, by Tallgren, Vanhatalo, Kaila and Voipio.</p>

<p>Caveats: The article page itself wasn&#x27;t read.; Optional: use https://doi.org/10.1016/j.clinph.2004.10.001 or an https ScienceDirect URL for a more durable link.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Foc.us Dev kit: EEG,TDCS,fNIRS,TACS — keep</h3>

<p>Source unavailable at final recheck.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The official foc.us dev kit guide is live. It documents an EEG device, an &#x27;EEG+&#x27; variant with transcranial electrical stimulation (tES), and an fNIRS sensor socket, which supports EEG, tDCS and fNIRS. tACS is not named explicitly on the page, but the kit has a tES output, so the name&#x27;s claim is plausible but unconfirmed.</p>

<p>https://foc.us/focus-eeg-dev-kit-instructions-guide/ — HTTP 200. Describes the Foc.us EEG Dev Kit (EEG Only and EEG+ variants), says EEG+ supports transcranial electrical stimulation (tES), and lists an &#x27;fNIRS sensor socket&#x27; and an &#x27;fNIRS Sensor&#x27; section. The companion app is listed as &#x27;focus-me-eeg-tdcs-v3&#x27;.</p>

<p>Caveats: The page does not explicitly mention tACS. tES support is documented generically.; No product purchase page was checked to confirm the kit is still sold, and no software was run.</p>

</details>

<h3>BITalino: EEG,EMG,ECG,EDA — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>BITalino is a PLUX brand. bitalino.com redirects to pluxbiosignals.com, and the PLUX site lists BITalino under &#x27;Shop by Brand&#x27; with Neurology, Myology and Cardiology sensors. The URL is the brand owner&#x27;s canonical home, and the multimodal listing still fits.</p>

<p>https://bitalino.com/ — Redirects (HTTP 200 final) to https://www.pluxbiosignals.com/.</p>

<p>https://www.pluxbiosignals.com/ — PLUX Biosignals site. Navigation lists brands &#x27;Biosignals Pro, BITalino, biosignalsplux, OpenSignals&#x27; and sensor categories Cardiology, Myology, Neurology, Respiratory and others, plus an Electrodermal Activity add-on.</p>

<p>Caveats: https://www.pluxbiosignals.com/collections/bitalino returned HTTP 429 (rate limit), so per-sensor BITalino listings (EEG/EMG/ECG/EDA) were not individually confirmed.; Linking the BITalino collection page could be more specific, but this was not verified.</p>

</details>

<h3>Emotibit: EDA,PPG,Temperature — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>EmotiBit&#x27;s official site is live and describes a wearable that captures EDA, PPG and temperature, plus motion. The name&#x27;s listed signals are accurate.</p>

<p>https://www.emotibit.com/ — HTTP 200. &#x27;EmotiBit is a wearable sensor module for capturing high-quality emotional, physiological, and movement data.&#x27; Lists EDA, PPG, temperature and IMU streams, open-source software, and sales through the OpenBCI store.</p>

<p>Caveats: EmotiBit measures peripheral physiology, not brain signals. That is consistent with a &#x27;Multimodal Neurotech&#x27; section but only adjacent to BCI.; The site also lists IMU. Adding it is optional, since the name is non-exclusive.</p>

</details>

<h3>Magstim — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Magstim&#x27;s official site is live and offers TMS solutions (research and clinical). It now also covers EEG (EGI) and tDCS, but &#x27;TMS&#x27; remains accurate and non-exclusive.</p>

<p>https://www.magstim.com/ — HTTP 200. Navigation lists EEG, TMS, Integrated Solutions and tDCS. &#x27;Welcome to Magstim, your neurotechnology partner for EGI Electroencephalography (EEG), Transcranial Magnetic Stimulation (TMS)...&#x27;</p>

<p>Caveats: EEG and tDCS could optionally be added. That is an expansion, not a correction.</p>

</details>

<h3>Vielight — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Vielight&#x27;s official site is live and centers on brain photobiomodulation devices (Neuro, Neuro Pro 2). The description is accurate.</p>

<p>https://www.vielight.com/ — HTTP 200. Title &#x27;Vielight Photobiomodulation Therapy Devices | At-Home Brain PBM&#x27;. Lists Vielight Neuro and Neuro Pro 2 brain PBM devices and published research.</p>

<p>Caveats: Clinical claims on the site are not assessed.</p>

</details>

<h3>NeuroPace — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>NeuroPace&#x27;s official site is live and centers on the RNS System for epilepsy, which also records EEG. The &#x27;RNS&#x27; description is accurate.</p>

<p>https://www.neuropace.com/ — HTTP 200. &#x27;The NeuroPace RNS System is the only FDA-approved epilepsy device that delivers personalized treatment by responding to abnormal brain activity and provides EEG data.&#x27;</p>

</details>

<h3>Brainsway — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>BrainsWay&#x27;s official site is live and centers on Deep TMS. The description is accurate. The official capitalization is &#x27;BrainsWay&#x27;, which could optionally be adopted in the name, but this is cosmetic.</p>

<p>https://www.brainsway.com/ — HTTP 200. Title &#x27;BrainsWay Deep TMS - Innovative, Noninvasive Treatment&#x27;. Lists FDA-cleared indications (MDD, OCD, smoking addiction) and &#x27;Deep vs. First-Generation TMS&#x27;.</p>

<p>Caveats: The capitalization difference (Brainsway vs BrainsWay) is cosmetic and was not treated as an identity error.</p>

</details>

<h3>Neuroelectrics: EEG,TDCS — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Neuroelectrics&#x27; official site is live (the earlier snapshot failure appears transient). It lists Enobio EEG and Starstim brain-stimulation devices (tDCS/tACS/tRNS), so &#x27;EEG,TDCS&#x27; is accurate.</p>

<p>https://www.neuroelectrics.com/ — HTTP 200. Navigation: &#x27;EEG Recording — Enobio 8, 20, 32&#x27;, &#x27;Brain Stimulation — Starstim tES, 8, 20, 32&#x27;, &#x27;Starstim Eos&#x27; for epilepsy, plus EEG fNIRS.</p>

<p>https://www.neuroelectrics.com/products/research/starstim — Starstim page text: &#x27;tDCS/tACS/tRNS, custom waveforms or temporal interference&#x27;.</p>

<p>Caveats: The homepage contains template placeholder text (&#x27;Project Title... Share information&#x27;), a cosmetic site issue that does not affect the entry.; Neuroelectrics is listed in both Multimodal (203) and Brain Stimulation (216). This is intentional cross-listing, not a confirmed duplicate error.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Neuroelectrics — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Neuroelectrics&#x27; site is live, and the Starstim product page explicitly lists tDCS/tACS/tRNS. The description is accurate.</p>

<p>https://www.neuroelectrics.com/products/research/starstim — &#x27;tDCS/tACS/tRNS, custom waveforms or temporal interference configurable for bipolar, 4x1...&#x27;; &#x27;tACS with in-phase/anti-phase montage&#x27;.</p>

<p>https://www.neuroelectrics.com/ — HTTP 200. Lists Starstim tES, 8, 20, 32 and Starstim Eos.</p>

<p>Caveats: Also listed as entry 203 in Multimodal Neurotech. Whether to keep both is a maintainer choice.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Event-Related Optical Signal — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The linked work is Gratton &amp; Fabiani (2001), &#x27;Shedding light on brain function: the event-related optical signal&#x27;, Trends in Cognitive Sciences 5(8):357–363, a historical EROS paper still relevant to the section. ResearchGate returned HTTP 403, which is typical bot blocking, so the page was not read. The DOI resolves to the publisher (Elsevier linkinghub) and is a durable alternative link if the maintainer prefers.</p>

<p>https://www.researchgate.net/publication/223360817_Shedding_light_on_brain_function_The_event-related_optical_signal — HTTP 403 to an automated client. Content not read.</p>

<p>https://doi.org/10.1016/S1364-6613(00)01701-0 — Returns 302 to https://linkinghub.elsevier.com/retrieve/pii/S1364661300017010, confirming the DOI for this Trends in Cognitive Sciences article.</p>

<p>https://www.wikidata.org/wiki/Q28209475 — Search listing identifies the item as the scientific article by Gratton and Fabiani, August 2001. Seen in search results only.</p>

<p>Caveats: The ResearchGate page could not be read because of the 403. It may still work in a browser.; Optionally switch the link to the DOI for durability. This was not required, since a 403 alone is not evidence of a broken link.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Optically Pumped Magnetometers (OPM) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>All three links resolve and support the entry. The PMC article is a 2022 Epilepsia review of wearable OPM-MEG. QuSpin and Cerca Magnetics both currently offer OPM sensors or OPM-MEG systems.</p>

<p>https://pmc.ncbi.nlm.nih.gov/articles/PMC9805039/ — &#x27;Wearable OPM-MEG: A changing landscape for epilepsy&#x27;, Epilepsia 2022;63(11):2745-2753, doi 10.1111/epi.17368.</p>

<p>https://quspin.com/ — QuSpin lists the QZFM Gen-3 zero-field optically pumped magnetometer for biomagnetic signals and the Neuro-1 integrated OPM-MEG system.</p>

<p>https://www.cercamagnetics.com/cerca-opm-meg — Cerca describes its &#x27;first commercial, fully integrated brain imaging device based on OPMs&#x27;, offered as a research system.</p>

<p>Caveats: This entry has child items, which were not assessed.</p>

</details>

<h3>BNCI Horizon Data Sets — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The BNCI Horizon 2020 data sets page resolves and still lists open-access BCI datasets, such as BCI Competition IV 2a.</p>

<p>https://bnci-horizon-2020.eu/database/data-sets — &#x27;All data sets in this database are open access.&#x27; The first entry is &#x27;Four class motor imagery (001-2014)&#x27;, with per-dataset license info.</p>

<p>Caveats: The dataset download links themselves were not tested.</p>

</details>

<h3>PhysioNet — keep</h3>

<p>Source unavailable at final recheck.</p>

<details>
<summary>Evidence and limitations</summary>

<p>PhysioNet resolves at the listed URL and hosts physiological datasets, including the EEG Motor Movement/Imagery BCI dataset referenced by other lists.</p>

<p>https://physionet.org/ — HTTP 200, no redirect.</p>

<p>Caveats: Homepage content was not read in detail.</p>

</details>

<h3>EEGEdu — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>eegedu.com resolves and is the live deployment of kylemath/EEGEdu. The repo describes it as an interactive educational site for learning EEG with a Muse headset. Its curriculum runs from basic signal viewing to SSVEP and a BCI trainer, matching &#x27;from basic to advanced&#x27;.</p>

<p>https://eegedu.com — Resolves to https://eegedu.com/ (title &#x27;EEGEdu&#x27;). Client-side app; content is not visible without JavaScript.</p>

<p>https://raw.githubusercontent.com/kylemath/EEGEdu/master/README.md — &#x27;EEGEdu is served live at https://eegedu.com/ ... designed as an interactive educational website to learn/teach about working with EEG data&#x27;. The curriculum covers raw data, spectra, neurofeedback, alpha, SSVEP and a BCI trainer.</p>

<p>Caveats: Complex multi-link entry. I did not verify that all three named Mathewsons currently maintain it, or the current content of the LinkedIn and personal-site links.; Recent commit activity was not determined.</p>

</details>

<h3>Introduction to Modern BCI — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The SCCN wiki page is live and still hosts Christian Kothe&#x27;s open online course on modern BCI design. It is a dated but valuable course resource.</p>

<p>https://eeglab.ucsd.edu/wiki/Introduction_To_Modern_Brain-Computer_Interface_Design — HTTP 200. Page &#x27;Introduction To Modern Brain-Computer Interface Design&#x27;. An online course by Christian Kothe (SCCN/UCSD), first given in 2012, covering EEG, BCI, signal processing, ML, BCILAB and LSL. Lists lecture videos, slides and exercise materials.</p>

<p>Caveats: Did not check whether every embedded video and slide link still resolves.</p>

</details>

<h3>Muse File Reader for OpenVibe — keep</h3>

<p>Source or watched-source coverage changed since research.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The archived OpenViBE forum thread is reachable and is a &#x27;Simplistic Muse File Reader&#x27; patch for .muse files. It is a dated community resource that matches the entry title.</p>

<p>https://web.archive.org/web/20240930191736/https://openvibe.inria.fr/forum/viewtopic.php?f=3&amp;t=9668 — HTTP 200. In July 2016 baffo32 posted a public-domain patch (muse-1.patch.bz2) adding a .muse file reader for Muse Monitor files. An OpenViBE developer merged it into the branch wip-contrib-muse-reader in Jan 2017. In 2021 the author pointed to proto files at github.com/xloem/musefileformat.</p>

<p>Caveats: Did not check whether the live forum URL or the wip-contrib-muse-reader branch still exists. The thread&#x27;s 2021 reply already asks whether that branch is still around. Its status is unknown.; Whether the attachment downloads from the archive was not verified.</p>

</details>

<h3>NeuroBB — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>NeuroBB is a live, active Discourse forum for EEG, BCI and neurofeedback discussion.</p>

<p>https://neurobb.com/ — HTTP 200. Title: &#x27;NeuroBB: The EEG, BCI, and Neurofeedback Discussion Forum&#x27;. Topics show activity dated November 4–5, 2026.</p>

</details>

<h3>Muse Community — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>r/museheadband is an active subreddit for Interaxon Muse discussion and development. The HTML page blocks automated clients with a 403, but the subreddit RSS feed shows posts up to Nov 10, 2026.</p>

<p>https://www.reddit.com/r/museheadband/.rss — The feed is titled &#x27;Ideas, Discussion &amp; Development for the Interaxon Muse&#x27;, with entries updated 2026-10-30 through 2026-11-10.</p>

<p>https://www.reddit.com/r/museheadband/ — The HTML page returns 403 to automated requests, which is access blocking rather than a dead link.</p>

<p>Caveats: It is community-run, not an official Interaxon forum. The entry name &#x27;Muse Community&#x27; doesn&#x27;t claim it is official.</p>

</details>

<h3>NeuroSky — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>NeuroSky&#x27;s official public discussion area is reachable and relevant to consumer EEG/BCI hardware. Activity is very low.</p>

<p>https://support.neurosky.com/discussions — HTTP 200. &#x27;Public Discussion&#x27; area with categories for MindWave, MindWave Mobile, MindSet, developer program and others. 13 category listings say &#x27;No discussions yet&#x27;, and only a handful of threads exist (e.g. under mindset).</p>

<p>Caveats: Thread dates were not checked. The forum looks largely inactive, so the maintainer may weigh it against the &#x27;actively maintained&#x27; guideline, but there is no affirmative evidence it was retired.; Some categories are marked Private.</p>

</details>

<h3>Emotiv — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The EMOTIV Forum is live and is the vendor&#x27;s official community forum for EMOTIV APIs, hardware and software, including EEG and neuroscience boards.</p>

<p>https://forum.emotiv.com/ — HTTP 200. &#x27;Welcome to the EMOTIV Forum … ask questions, discuss ideas, and share knowledge about building applications using EMOTIV APIs, and EMOTIV&#x27;s hardware and software.&#x27; The latest post in General was 1 day before the check.</p>

<p>Caveats: The most recent visible post in General appears to be promotional spam, so moderation quality is unclear.</p>

</details>

<h3>NeuroTechX Content Lab — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The NeuroTechX Content Lab Medium publication is active. Its RSS feed shows posts through Nov 9, 2026, consistent with &#x27;Articles, tutorials, and interviews on neurotechnology&#x27;.</p>

<p>https://neurotechx.medium.com/feed — Feed &#x27;Stories by NeuroTechX Content Lab on Medium&#x27;. Recent pubDates: Nov 9, Oct 23, Oct 16, Sep 28 and Sep 9, 2026.</p>

<p>https://neurotechx.medium.com/ — The HTML page returns 403 to automated requests, which is bot blocking rather than a dead link.</p>

<p>Caveats: Individual article content was not reviewed against the &#x27;articles, tutorials, and interviews&#x27; mix.</p>

</details>

<h3>The EEG Newsletter — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Substack is live and the description (EEG news, events, resources, by Raquel E. London) matches. However, the newest post is from July 1, 2024.</p>

<p>https://eegnewsletter.substack.com/ — HTTP 200. &#x27;The EEG Newsletter | Raquel E. London&#x27;, self-described as &#x27;(M)EEG related topics, vacancies and events happening in our community of EEG researchers&#x27;.</p>

<p>https://eegnewsletter.substack.com/feed — The newest feed items are &#x27;22 - Single-trial EEG analyses&#x27; (Jul 1, 2024), &#x27;21 - Prediction markets for #EEGManyLabs&#x27; (May 30, 2024) and &#x27;20 - Synthetic EEG data&#x27; (May 1, 2024).</p>

<p>Caveats: No posts in about 28 months. There is no official statement that it ended. The maintainer may weigh this against the &#x27;actively maintained&#x27; guideline, and the back issues remain readable.; The content is general EEG research rather than BCI-specific.</p>

</details>

<h3>Fabien Lotte — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Fabien Lotte&#x27;s &#x27;Code and softwares&#x27; page is live and current. It lists BCI and EEG code tied to his publications, the newest from 2025. The page is a researcher&#x27;s code page rather than a blog, which is a minor section-fit caveat, but it is clearly BCI-relevant and is the official source.</p>

<p>https://sites.google.com/site/fabienlotte/research/code-and-softwares — HTTP 200, titled &#x27;Fabien Lotte&#x27;s professional homepage - Code and softwares&#x27;. It describes software and libraries &#x27;dedicated to Brain-Computer Interface research&#x27; under open-source licences, including Python code from a 2025 TMLR paper, Riemannian BCI code from 2019–2023, and SEREEGA.</p>

<p>Caveats: The page is a code/software listing on a research homepage, not a blog. The maintainer may prefer the homepage URL or another section.</p>

</details>

<h3>Kaggle Grasp and Lift — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Kaggle competition page resolves with the matching official title. It is a completed, archived EEG decoding competition and remains a dated BCI data resource.</p>

<p>https://www.kaggle.com/c/grasp-and-lift-eeg-detection — HTTP 200, page title &#x27;Grasp-and-Lift EEG Detection | Kaggle&#x27;.</p>

<p>Caveats: Kaggle renders client-side, so I verified only the title, not the data download or leaderboard.</p>

</details>

<h3>Kaggle Error Detection — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves to the official &#x27;BCI Challenge @ NER 2015&#x27; Kaggle competition, an Inria competition on detecting error-related potentials. The catalog label &#x27;Error Detection&#x27; describes it accurately.</p>

<p>https://www.kaggle.com/c/inria-bci-challenge — HTTP 200, page title &#x27;BCI Challenge @ NER 2015 | Kaggle&#x27;.</p>

<p>Caveats: Only the page title was verified; Kaggle content is rendered client-side.; The connection to error-related potentials comes from background knowledge of this challenge; the fetched page text did not show it.</p>

</details>

<h3>Kaggle Decode the Human Brain — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves to the official &#x27;DecMeg2014 - Decoding the Human Brain&#x27; Kaggle competition, an MEG decoding competition that remains a dated neural-decoding resource.</p>

<p>https://www.kaggle.com/c/decoding-the-human-brain — HTTP 200, page title &#x27;DecMeg2014 - Decoding the Human Brain | Kaggle&#x27;.</p>

<p>Caveats: Only the page title was verified; Kaggle content is rendered client-side.</p>

</details>

<h3>Kaggle Seizure Prediction — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves to the official &#x27;American Epilepsy Society Seizure Prediction Challenge&#x27; Kaggle page, a completed intracranial EEG competition.</p>

<p>https://www.kaggle.com/c/seizure-prediction — HTTP 200, page title &#x27;American Epilepsy Society Seizure Prediction Challenge | Kaggle&#x27;.</p>

<p>Caveats: Only the page title was verified. It is a clinical EEG dataset rather than a BCI control task, so section fit is a curation judgment.</p>

</details>

<h3>Kaggle Seizure Detection — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The URL resolves to the official &#x27;UPenn and Mayo Clinic&#x27;s Seizure Detection Challenge&#x27; Kaggle page, a completed intracranial EEG competition.</p>

<p>https://www.kaggle.com/c/seizure-detection — HTTP 200, page title &#x27;UPenn and Mayo Clinic&#x27;s Seizure Detection Challenge | Kaggle&#x27;.</p>

<p>Caveats: Only the page title was verified; Kaggle content is rendered client-side.</p>

</details>

<h3>BCI Competition IV – Data Set I: Learning Discriminative Patterns for Self-Paced EEG-Based Motor Imagery Detection — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>PMC3272647 is &#x27;BCI Competition IV - Data Set I: Learning Discriminative Patterns for Self-Paced EEG-Based Motor Imagery Detection&#x27; (Zhang, Guan, Ang, Wang; Frontiers in Neuroscience, 2012). That matches the entry, and it&#x27;s a relevant BCI paper.</p>

<p>https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=PMCID:PMC3272647&amp;format=json&amp;resultType=core — Title, authors Zhang H, Guan C, Ang KK, Wang C, Front Neurosci 2012, DOI 10.3389/fnins.2012.00007, PMCID PMC3272647. The abstract describes a self-paced motor-imagery BCI validated on BCI Competition IV Dataset I.</p>

<p>Caveats: The PMC HTML page returned a reCAPTCHA to my client, so I confirmed the mapping through Europe PMC.</p>

</details>

<h3>Multiclass Brain-Computer Interface Classification by Riemannian Geometry — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ResearchGate returned 403 (&#x27;Temporarily Unavailable&#x27;) to my automated client, which is typical of its bot blocking and doesn&#x27;t show the link is dead. The paper itself is confirmed: Barachant, Bonnet, Congedo &amp; Jutten, &#x27;Multiclass brain-computer interface classification by Riemannian geometry&#x27;, IEEE Trans Biomed Eng 2012, DOI 10.1109/TBME.2011.2172210. It&#x27;s a foundational BCI paper.</p>

<p>https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:10.1109/TBME.2011.2172210&amp;format=json&amp;resultType=core — &#x27;Multiclass brain-computer interface classification by Riemannian geometry&#x27;, Barachant A, Bonnet S, Congedo M, Jutten C, IEEE Trans Biomed Eng 2012, PMID 22010143. The abstract presents a Riemannian classification framework for motor-imagery BCI.</p>

<p>Caveats: I couldn&#x27;t read the ResearchGate page itself (403). Recheck it in a browser.; A maintainer could switch to the DOI (https://doi.org/10.1109/TBME.2011.2172210) for a more durable link, but the current URL isn&#x27;t confirmed broken.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>A New Generation of Brain-Computer Interface Based on Riemannian Geometry — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ResearchGate returned 403 (&#x27;Temporarily Unavailable&#x27;) to my automated client, which is typical of its bot blocking. The paper is confirmed: arXiv 1310.8115 is titled &#x27;A New Generation of Brain-Computer Interface Based on Riemannian Geometry&#x27;, an exact match. It&#x27;s a relevant BCI paper.</p>

<p>https://arxiv.org/abs/1310.8115 — HTTP 200. Title is &#x27;[1310.8115] A New Generation of Brain-Computer Interface Based on Riemannian Geometry&#x27;.</p>

<p>Caveats: I couldn&#x27;t read the ResearchGate page itself (403). Recheck it in a browser.; The arXiv abstract page could serve as a more durable link, but the current URL isn&#x27;t confirmed broken.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Interpretable Deep Neural Networks for Single-Trial EEG Classification — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ResearchGate returned 403 (&#x27;Temporarily Unavailable&#x27;) to my automated client, which is typical of its bot blocking. The paper is confirmed: Sturm, Lapuschkin, Samek &amp; Müller, &#x27;Interpretable deep neural networks for single-trial EEG classification&#x27;, J Neurosci Methods 2016, DOI 10.1016/j.jneumeth.2016.10.008. There&#x27;s also an arXiv copy (1604.08201). It&#x27;s relevant to BCI decoding.</p>

<p>https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=DOI:10.1016/j.jneumeth.2016.10.008&amp;format=json&amp;resultType=core — &#x27;Interpretable deep neural networks for single-trial EEG classification&#x27;, Sturm I, Lapuschkin S, Samek W, Müller KR, J Neurosci Methods 2016, PMID 27746229. The abstract describes applying LRP to explain DNN decisions on EEG.</p>

<p>https://arxiv.org/abs/1604.08201 — HTTP 200. Title is &#x27;[1604.08201] Interpretable Deep Neural Networks for Single-Trial EEG Classification&#x27;.</p>

<p>Caveats: I couldn&#x27;t read the ResearchGate page itself (403). Recheck it in a browser.; The DOI or the arXiv link could serve as a more durable link.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Cycles in mind (Cohen) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Mike X Cohen&#x27;s &#x27;Cycles in mind: How brain rhythms control perception and action&#x27; is a short Kindle e-book from 2015, a lay introduction to brain oscillations. The label&#x27;s title and author are correct, and it fits Introductory Books.</p>

<p>https://www.goodreads.com/en/book/show/27202178 — Search result lists &#x27;Cycles in mind: How brain rhythms control perception and action by Mike X. Cohen&#x27;. The search summary describes a 99-page Kindle edition published Aug 15, 2015 for a non-specialist audience.</p>

<p>https://www.amazon.com/Cycles-mind-rhythms-control-perception-ebook/dp/B013ZI5AIA — Amazon served a captcha to automated requests, so the listing content was not read.</p>

<p>Caveats: Amazon listing availability was not verified directly because of the captcha. The ASIN is tied to the Kindle edition only.</p>

</details>

<h3>Principles of Neural Science (Kandel et al) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Kandel et al., Principles of Neural Science, is a standard neuroscience reference, so the label is accurate. The link points to the 4th edition (ISBN 0838577016, 2000), but the entry makes no claim about edition.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:0838577016&amp;format=json&amp;jscmd=data — Open Library: &#x27;Principles of Neural Science&#x27; by Eric R. Kandel, James H. Schwartz, Thomas M. Jessell, published January 5, 2000.</p>

<p>https://www.amazon.com/Principles-Neural-Science-Eric-Kandel/dp/0838577016 — Amazon captcha, so the listing was not read.</p>

<p>Caveats: Newer editions exist (the latest is believed to be the 6th, 2021, but this was not checked against an official source). Linking a newer edition would be optional, not a correction.; Amazon reachability was not confirmed because of bot blocking.</p>

</details>

<h3>The Future of the Mind (Kaku) — keep</h3>

<p>Source snapshot unavailable.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ISBN 038553082X is Michio Kaku&#x27;s &#x27;The Future of the Mind: The Scientific Quest to Understand, Enhance, and Empower the Mind&#x27; (2014). It is a popular-science book with brain-machine-interface themes, and the label is accurate for Introductory Books.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:038553082X&amp;format=json&amp;jscmd=data — Open Library: &#x27;The Future of the Mind: The Scientific Quest to Understand, Enhance, and Empower the Mind&#x27; by Michio Kaku, 2014.</p>

<p>https://www.amazon.com/The-Future-Mind-Scientific-Understand/dp/038553082X — Amazon captcha to automated requests, so the listing was not read. The failed packet snapshot is consistent with bot blocking.</p>

<p>Caveats: Amazon reachability was not confirmed. This needs a recheck, not removal.</p>

<p>Source snapshot incomplete; excluded from the saved baseline.</p>

</details>

<h3>Brain-Computer Interfacing: An Introduction (Rao) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The ISBN matches Rajesh P. N. Rao, &#x27;Brain-Computer Interfacing: An Introduction&#x27; (Cambridge, 2013), a core BCI textbook. The label is accurate.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:0521769418&amp;format=json&amp;jscmd=data — Open Library: &#x27;Brain-Computer Interfacing: An Introduction&#x27; by Rajesh P. N. Rao, 2013.</p>

<p>https://www.amazon.com/Brain-Computer-Interfacing-Introduction-Rajesh-Rao/dp/0521769418 — Amazon captcha, so the listing was not read.</p>

<p>Caveats: Amazon reachability was not confirmed because of bot blocking.</p>

</details>

<h3>Brain Computer Interfaces (Wolpaw) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ISBN 0195388852 is &#x27;Brain-Computer Interfaces: Principles and Practice&#x27; (OUP, 2012), edited by Jonathan R. Wolpaw and Elizabeth Winter Wolpaw. It is a core BCI text and the short label is accurate.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:0195388852&amp;format=json&amp;jscmd=data — Open Library: &#x27;Brain-computer interfaces: principles and practice&#x27;, 2012, edited by Jonathan R. Wolpaw and Elizabeth Winter Wolpaw.</p>

<p>https://www.amazon.com/Brain-Computer-Interfaces-Principles-Jonathan-Wolpaw/dp/0195388852 — Amazon captcha, so the listing was not read.</p>

<p>Caveats: The label omits the subtitle and the co-editor. Adding them would be optional.; Amazon reachability was not confirmed.</p>

</details>

<h3>Imaging Brain Function with EEG (Freeman &amp; Quiroga) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Freeman &amp; Quiroga, &#x27;Imaging Brain Function With EEG&#x27; (Springer, 2013), DOI 10.1007/978-1-4614-4984-3, is an EEG analysis text that fits Technical Books. The link is the DOI-based SpringerLink page.</p>

<p>https://api.crossref.org/works/10.1007/978-1-4614-4984-3 — Crossref: book &#x27;Imaging Brain Function With EEG&#x27;, 2013, authors Freeman and Quiroga.</p>

<p>https://link.springer.com/book/10.1007/978-1-4614-4984-3 — HTTP 200 but served a &#x27;Client Challenge&#x27; page to curl. The packet snapshot shows the page body was fetched.</p>

<p>Caveats: The rendered Springer page content was not read directly because of the client challenge.</p>

</details>

<h3>Matlab for Neuroscientists — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ISBN 0123745519 is &#x27;MATLAB for Neuroscientists: An Introduction to Scientific Computing in MATLAB&#x27; by Wallisch et al. (1st edition). The label is accurate, and the book is a useful technical resource for neural data analysis.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:0123745519&amp;format=json&amp;jscmd=data — Open Library: &#x27;MATLAB for neuroscientists: an introduction to scientific computing of MATLAB&#x27;, Pascal Wallisch, Adam S. Dickey et al., 2009.</p>

<p>https://www.amazon.com/MATLAB-Neuroscientists-Introduction-Scientific-Computing/dp/0123745519 — Amazon captcha, so the listing was not read.</p>

<p>Caveats: A 2nd edition is believed to exist (2014) but was not verified. Linking it would be optional.; Amazon reachability was not confirmed.</p>

</details>

<h3>Biomedical Optics — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The Google Books page resolves to &#x27;Biomedical Optics: Principles and Imaging&#x27; by Lihong V. Wang and Hsin-i Wu. Its optical-imaging theory is relevant to fNIRS-style BCIs, and the label is accurate.</p>

<p>https://books.google.ca/books?id=EJeQ0hAB76gC&amp;pg=PR3&amp;redir_esc=y — HTTP 200. Page title &#x27;Biomedical Optics: Principles and Imaging - Lihong V. Wang, Hsin-i Wu - Google Books&#x27;.</p>

<p>Caveats: BCI relevance is indirect (optical neuroimaging foundations).</p>

</details>

<h3>Discrete-Time Signal Processing (2nd Edition) (Oppenheim, Schafer, Buck) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>ISBN 0137549202 is Discrete-Time Signal Processing, 2nd edition (1999), by Oppenheim and Schafer, with John R. Buck. The label&#x27;s edition and authors match.</p>

<p>https://openlibrary.org/api/books?bibkeys=ISBN:0137549202&amp;format=json&amp;jscmd=data — Open Library: &#x27;Discrete-time signal processing&#x27;, Alan V. Oppenheim and Ronald Schafer, February 15, 1999.</p>

<p>https://www.amazon.com/Discrete-Time-Signal-Processing-Edition-Prentice-Hall/dp/0137549202 — Amazon captcha, so the listing was not read.</p>

<p>Caveats: A 3rd edition is believed to exist but was not verified. The entry explicitly names the 2nd edition, so it is accurate as a dated edition.; Amazon reachability was not confirmed.</p>

</details>

<h3>Data analysis lecturelets (Mike X Cohen) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The channel is live and owned by Mike X Cohen. It offers data-analysis/time-series video lectures (about 511 videos, 45.1K subscribers), which fits the Signal Processing section. The entry has no description to check.</p>

<p>https://www.youtube.com/@mikexcohen1 — HTTP 200, title &#x27;Mike X Cohen - YouTube&#x27;. Meta description: &#x27;Video lectures on time series analysis, programming, statistics, and data science. Many of my videos are excerpts from full-length courses.&#x27; The page shows 45.1K subscribers and 511 videos.</p>

<p>Caveats: Could not get recent upload dates from the YouTube HTML. Upload frequency was not checked.</p>

</details>

<h3>Neuroscience Duke Course (Coursera) — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>Duke University&#x27;s Medical Neuroscience course on Coursera is live at the listed URL and taught by Leonard E. White. It still fits &#x27;Other Resources&#x27; as neuroscience background. The entry has no description to check.</p>

<p>https://www.coursera.org/learn/medical-neuroscience — Title &#x27;Medical Neuroscience | Coursera&#x27;. &#x27;Offered by Duke University. Medical Neuroscience explores the functional organization and neurophysiology of the human central nervous…&#x27; Instructor is Leonard E. White. Taught in English.</p>

<p>Caveats: Optional: the name could more precisely read &#x27;Medical Neuroscience (Duke, Coursera)&#x27;, but the current name is not wrong.</p>

</details>

<h3>Augment Human Cognition by optimizing cortical oscillations — keep</h3>

<p>Source or catalog stability was not confirmed for this review.</p>

<details>
<summary>Evidence and limitations</summary>

<p>The PMC article is live. It is Horschig, Zumer et al., &#x27;Hypothesis-driven methods to augment human cognition by optimizing cortical oscillations&#x27;, in Frontiers in Systems Neuroscience (2014). The link name paraphrases this title accurately. The paper covers neurofeedback/stimulation methods, which is relevant BCI background, and it remains valid as a dated paper.</p>

<p>https://pmc.ncbi.nlm.nih.gov/articles/PMC4072086/ — citation_title &#x27;Hypothesis-driven methods to augment human cognition by optimizing cortical oscillations&#x27;. Journal: Frontiers in Systems Neuroscience. Authors Jörn M Horschig, Johanna M Zumer et al. (Donders Institute).</p>

<p>Caveats: Optional: the link text could use the exact paper title.</p>

</details>

</details>

The complete research records remain local. This inventory contains all recommendations and unresolved entries from the saved initial review.

[One-entry integration example](https://github.com/bromanko/awesome-bci/blob/codex/catalog-inventory-preview/.um/catalog-inventory/checked-example.md). Saved research with real discussion-history and patch checks.
