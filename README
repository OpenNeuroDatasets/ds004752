### Dataset of intracranial EEG, scalp EEG and beamforming sources from human epilepsy patients performing a verbal working memory task

#### Description
We present an electrophysiological dataset recorded from fifteen subjects during a verbal working memory task. Subjects were epilepsy patients undergoing intracranial monitoring for localization of epileptic seizures. Subjects performed a modified Sternberg task in which the encoding of memory items, maintenance, and recall were temporally separated. The dataset includes simultaneously recorded scalp EEG with the 10-20 system, intracranial EEG (iEEG) recorded with depth electrodes, waveforms, and the MNI coordinates and anatomical labels of all intracranial electrodes. The dataset includes also reconstructed virtual sensor data that were created by performing LCMV beamforming on the EEG at specific brain regions including, temporal superior lobe, lateral prefrontal cortex, occipital cortex, posterior parietal cortex, and Broca.  Subject characteristics and information on sessions (set size, match/mismatch, correct/incorrect, response, response time for each trial) are also provided. This dataset enables the investigation of working memory by providing simultaneous scalp EEG and iEEG recordings, which can be used for connectivity analysis, alongside reconstructed beamforming EEG sources that can enable further cognitive analysis such as replay of memory items.

### Repository structure

### Main directory (verbal WM)

Contains metadata files in the BIDS standard about the participants and the study. Folders are explained below.

### Subfolders

-   verbal WM/sub-/ Contains folders for each subject, named sub- and session information.
-   verbal WM/sub-/ses-/ieeg/ Contains the raw iEEG data in .edf format for each subject. Each subject performed more than 1 working memory session (ses-0x) each of which includes ~50 trials.  Each *ieeg.edf file contains continuous iEEG data during the working memory task. Details about the channels are given in the corresponding .tsv file. We also provide the information on the trial start and end in the events.tsv files by specifying the start and end sample of each trial.
-   verbal WM/sub-/ses-/eeg/ Contains the raw EEG data in .edf format for each subject. Each subject performed more than 1 working memory session (ses-0x) each of which includes ~50 trials.  Each *eeg.edf file contains continuous EEG data during the working memory task. Details about the channels are given in the corresponding .tsv file. We also provide the information on the trial start and end in the events.tsv files by specifying the start and end sample of each trial.

### BIDS Conversion

bids-starter-kid and custom Matlab scripts were used to convert the dataset into BIDS format.

### References
[1] Dimakopoulos V, Megevand P, Stieglitz LH, Imbach L, Sarnthein J. Information flows from hippocampus to auditory cortex during replay of verbal working memory items. Elife 2022;11. 10.7554/eLife.78677

[2] Boran E, Fedele T, Klaver P, Hilfiker P, Stieglitz L, Grunwald T, et al. Persistent hippocampal neural firing and hippocampal-cortical coupling predict verbal working memory load. Science Advances 2019;5(3):eaav3687. 10.1126/sciadv.aav3687

[3] Boran E, Fedele T, Steiner A, Hilfiker P, Stieglitz L, Grunwald T, et al. Dataset of human medial temporal lobe neurons, scalp and intracranial EEG during a verbal working memory task. Scientific Data 2020;7(1):30. 10.1038/s41597-020-0364-3