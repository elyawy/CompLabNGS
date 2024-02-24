# CompLabNGS
Welcome to TAU Life Sciences - Computational Lab in Next Generation Sequencing and Genomics Data Analysis - 0411358701

Course material will be updated weekly prior to our Sunday session. Make sure you grub necessary slides, data and class/HW assignments from the relevant directory.

Course announcements and HW submissions will be delivered via the course's [Moodle site](https://moodle.tau.ac.il/course/view.php?id=411358701) **only!**

Please use the *Issues* tab above to ask questions and report problems. Your questions will be answered by the course staff and/or your fellow students. Please refrain from sending us emails regarding course-related issues. Your questions and our answers will be visible to all students. This way, we can avoid duplicate questions and you can benefit from the questions and answers of your fellow students.

## Setting up your environment

Our course is all about hands-on experience with NGS data analysis. You'll need to set yourself up with a Unix-based environment. Please follow the instructions on [0-SettingUp](https://github.com/hadasvolk/CompLabNGS/blob/main/0-SettingUp/SettingUp.md) for possible solutions to this task.

## Course timeline
| Week | Date | Topic | Slides | Data | Class/HW assignments |
|:----:|:----:|:-----:|:------:|:----:|:---------------------|
| 1 | 31/12/2023 | Introduction to NGS and Genomics | [Lecture 1](https://github.com/hadasvolk/CompLabNGS/blob/main/1-IntroToNGS/Lesson1.pdf) | | [Setting up your environment](https://github.com/hadasvolk/CompLabNGS/blob/main/0-SettingUp/SettingUp.md) |
| 2 | 07/01/2024 | Introduction to Linux and the command line | [Lecture 2](https://github.com/hadasvolk/CompLabNGS/blob/main/2-Linux/Lesson2.pdf) | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/2-Linux/data) | [Class assignment 1](https://github.com/hadasvolk/CompLabNGS/tree/main/2-Linux/hw.md) |
| 3 | 14/01/2024 | NGS data quality control and pre-processing | [Lecture 3](https://github.com/hadasvolk/CompLabNGS/tree/main/3-QC/Lesson3.pdf) | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/3-QC/data) | [Class assignment 2](https://github.com/hadasvolk/CompLabNGS/tree/main/3-QC/hw.md) |
| 4 | 21/01/2024 | "Catching Up" week |
| 5 | 28/01/2024 | Sequence mapping part I | [Lecture 4](https://github.com/hadasvolk/CompLabNGS/tree/main/4-Mapping1/Lesson4.pdf) | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/4-Mapping1/data) | [Class assignment 3](https://github.com/hadasvolk/CompLabNGS/tree/main/4-Mapping1/hw.md) |
| 6 | 04/02/2024 | Sequence mapping part II | [Lecture 5](https://github.com/hadasvolk/CompLabNGS/tree/main/5-Mapping2/Lesson5.pdf) | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/5-Mapping2/data) | [Class assignment 4](https://github.com/hadasvolk/CompLabNGS/tree/main/5-Mapping2/hw.md) |
| 7 | 11/02/2024 | Variant calling | [Lecture 6](https://github.com/hadasvolk/CompLabNGS/tree/main/6-VariantCalling/Lesson6.pdf) | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/6-VariantCalling/data) | [Class assignment 5](https://github.com/hadasvolk/CompLabNGS/tree/main/6-VariantCalling/hw.md) |
| 8 | 18/02/2024 | Assembly | [Lecture 7](https://github.com/hadasvolk/CompLabNGS/tree/main/7-Assembly/Lesson7.pdf) | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/7-Assembly/data) | [Class assignment 6](https://github.com/hadasvolk/CompLabNGS/tree/main/7-Assembly/hw.md) |
| 9 | 25/02/2024 | RNA-Seq I | [Lecture 8](https://github.com/hadasvolk/CompLabNGS/tree/main/8-RNASeq1/Lesson8.pdf) | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/8-RNASeq1/data) | [Class assignment 7](https://github.com/hadasvolk/CompLabNGS/tree/main/8-RNASeq1/hw.md) |

## Roadmap to final grade of 100
30 points - Class assignments
* Starting on lesson 2
* Two weeks to complete each assignment and submit via Moodle
* Pass only - no partial credit
* Must submit at least 8 assignments to pass the course

70 points - Final project
* Can be done in pairs
* Submission deadline: 01.05.2024

## Download the data | git clone
If you wish to pull all data from this repo automatically and not download each file individually, you can use `git` to `clone` the entire repository to your local machine.

Make sure you have `git` installed by running `git --version`. If you don't have it installed, you can download it from [here](https://git-scm.com/downloads). Or simply use the `sudo apt install git` command if you are using a Ubuntu-based system.

You'll also need `git-lfs` to pull the large files. You can download it from [here](https://git-lfs.github.com/).

For Ubuntu do
```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt install git-lfs
```

Then, to clone the repository, use the following command:
```bash
git clone https://github.com/hadasvolk/CompLabNGS.git
```

From now on, you can use `git pull` to get the latest version of the repository. E.g., you can run:
```bash
cd CompLabNGS
git pull
```

Do it every time you want to get the latest version of the repository.
