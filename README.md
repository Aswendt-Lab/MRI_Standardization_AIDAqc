# AMIRE
Improving MRI quality without overly restrictive standardization - the AMIRE (Animal MrI standaRdization initiativE)

## 1. Aims
### 1.1 Project #1: 
Retrospective, automated MRI quality control (QC) to exclude bad quality data automatically from a large pool of small animal datasets (T1, T2, diffusion, fMRI) acquired in different international MRI labs/core facilities. Developed software: [AIDAqc](https://github.com/Aswendt-Lab/AIDAqc)

### 1.2 Project #2: 
Representative standard phantom measurements according to harmonized protocols to prove the importance of quality assurance (QA) procedures in each MRI lab as the basis for multicenter studies and cross-lab comparisons. 

## 2. Roadmap (updated)

| What | When  | Who  | Outcome/Comment  |
|---|---|---|---|
|  Ideas collected | March 2023 ([during EMIM 2023](https://e-smi.eu/meetings/emim/past-meetings/2023-salzburg/)) | Markus Aswendt, Aref Kalantari, Giovanna Ielacqua | Projects started, goals defined  |
| List of MRI sites defined | April 2023  | Markus Aswendt | Potential cooperation partners collected via Twitter/Email |
| Upload of data started for project #1 | May 2023 | Markus Aswendt, Aref Kalantari    | Finished: 30 June 2023 |
| Data processing project#1 | May-June 2023 | Aref Kalantari, Marc Schneider | Finished: 12 July 2023 |
| Upload of data to GIN for project #1 | <del> June </del> August 2023 | Marc Schneider, Aref Kalantari    | Finished: 19 Sept 2023 |
| Cooperation partner feedback project #1| <del> July August September </del> October 2023 | Markus Aswendt, Aref Kalantari    | in progress |
| Preparing publication project #1 | July-October 2023 | Markus Aswendt, Aref Kalantari, Marc Schneider, Giovanna Ielacqua  | in progress |
| Cooperation partner feedback project #2| July 2023 | Markus Aswendt, Aref Kalantari    | tbc |
| Preparing publication project #2 | September 2023 | Giovanna Ielacqua, Markus Aswendt, Aref Kalantari | tbc |

## 3. Collaborative model 
(adapted from Joanes Grandjean, [awake study](https://github.com/grandjeanlab/awake))

Next to the MRI laboratories previously invited via Email/Twitter/Personal communication at conferences, every laboratory can participate with at least 20 measurements (see 4. Data specification and management). 

### The collaborative model and authorship criteria are as follows:
Every contributing laboratory can nominate any number of collaborators who contributed to the dataset (e.g., acquisition, funding, management, etc..), split between junior and senior collaborators. The AIDAqc team (see 5. Contact) led by Markus Aswendt (MA) will put the dataset collection together and perform the primary analysis. Every collaborator is invited to further contribute to the manuscript preparation, serve as AIDAqc beta tester, and to provide feedback on the code/algorithms.

For both projects, one publication is planned, for which the author list will be as such: junior with an extra contribution, [junior collaborator in alphabetical order], [senior collaborator in alphabetical order], senior with an extra contribution. MA reserves the right to nominate the first and last authors.

## 4. Data specification and management
**What kind of small animal MRI data are suitable?**
Any T1/2-weighted, diffusion, fMRI datasets from small animals (rodents, rabbits, etc.) are interesting for our use case. It should be noted that the purpose of the tool is to find bad-quality data. Therefore, it would be optimal if you also provide the data that you may have already sorted out, so that we can test whether AIDAqc is able to identify them. Please provide the complete Bruker raw data folder for each measurement (containing the 1-n scan folders and all metadata files, necessary to extract image information) OR converted into NiFTY format. 

**What will happen with my data?**
We will screen your data and will try to extract as much information as possible automatically from the files. We will get back to you if more information is needed. If your data is used in the AIDAqc publication, you agree to make the dataset publicly available under the GNU General Public License v3.0. 

**Where will the data be stored and processed later?**
We will transfer the data from the upload locations and store the data locally at our workstation and use automated backups of the University Hospital Cologne IT department. All file operations and data processing will be tracked using [DataLad](https://www.datalad.org) to allow full transparency and FAIR data handling. After the analysis is finished, datasets which have been collectively identified to be necessary for the publication, will be made publicly available on GIN G-Node. 

**How can I withdraw my consent to data use?**
Send an Email to MA (markus.aswendt@uk-koeln.de). We guarantee that only the data you have NOT excluded and which have been collectively identified to be necessary for the publications will be made publicly available as an AIDAqc sample dataset.

## 5. Contact
Join our AIDA Tools Open Office Hour - each Thursday 4:30 pm (UTC+2) [![Zoom](https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor)](https://uni-koeln.zoom.us/meeting/register/tJYsceyorDoqGdX4H8Z7c86_qxoaq6yOdFGM).
For all inquries regarding the projects: aidaqc.share@gmail.com. For questions related to [AIDAqc](https://github.com/Aswendt-Lab/AIDAqc) contact Aref Kalantari (aref.kalantari-sarcheshmeh@uk-koeln.de). The AIDAqc core team currently consists of Markus Aswendt, Aref Kalantari, Marc Schneider, and Giovanna Ielacqua. 
