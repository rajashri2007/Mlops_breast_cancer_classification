\# Practical 3: Dataset Tracking and Versioning Using DVC



\## Aim

To track and manage different versions of the Breast Cancer dataset using Data Version Control (DVC).



\## Tools and Technologies

\- Python

\- Git

\- DVC

\- Pandas

\- PowerShell

\- Visual Studio Code



\## Dataset

Breast Cancer Wisconsin Dataset



\- Total records: 569

\- Total columns: 31

\- Target: Benign and Malignant



\## Objectives

1\. Initialize Git and DVC.

2\. Track the dataset using DVC.

3\. Create multiple dataset versions.

4\. Store dataset versions using DVC remote storage.

5\. Restore an earlier dataset version.



\## Procedure

1\. Initialized Git and DVC in the project.

2\. Added the Breast Cancer dataset using `dvc add`.

3\. Committed Version 1 using Git.

4\. Pushed the dataset to DVC storage using `dvc push`.

5\. Modified the dataset and created Version 2.

6\. Committed and pushed Version 2.

7\. Restored Version 1 using `git checkout` and `dvc checkout`.

8\. Verified the restored dataset using `dvc status`.



\## Version History



| Version | Git Commit |

|---|---|

| Version 1 | `b7644e0` |

| Version 2 | `96cb4db` |



\## Result

Successfully tracked, versioned, stored, and restored the Breast Cancer dataset using Git and DVC.



\## Conclusion

DVC helps manage large datasets and maintain different versions. It allows us to restore previous dataset versions whenever required.

