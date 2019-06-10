# BootCampHomework04-2019-06-12
[Jupyter Notebook Solution](https://github.com/ekenigsberg/BootCampHomework04-2019-06-12/blob/master/PyCitySchools.ipynb) to [Data Analytics Boot Camp Homework #4](https://github.com/the-Coding-Boot-Camp-at-UT/UTAMCB201904DATA3/tree/master/04-Pandas/Homework/Instructions)
# PyCity Schools Analysis

* Two clear trends appear in the data:
  * **Charter schools performed better than district schools.** The average charter math and reading scores showed a respective 5 point and 3 point edge over the district schools, resulting in a math passing rate over 25 percentage points higher, and a reading passing rate over 15 points higher.
  * **Smaller schools--measured by total students, total budget, or, most surprisingly, budget per student--had better math and reading test scores than larger schools.** In each size analysis, the bottom two quintiles' schools' test scores were over 5 points better in math, and over 3 points better in reading than the larger schools. This translated into passing rates for math and reading 20 and 10 percentage points higher, respectively, in the two smallest-quintile schools.

* One complicating wrinkle is that **the charter schools are all smaller**. Wilson High, the largest charter school, serves almost 500 fewer students than Ford High, the smallest district school.

* One argument against directly attributing better scores to school size: the charter schools' better scores do not vary by school size. The district schools' scores vary little by school size as well.
  
* The next challenge is to determine whether there is a systematic difference in the composition of the charter school student population versus the district school student population.

Two observations:
* Squashing the SettingWithCopyWarning issue was tricky. I most benefited from
  * [This explanation](https://www.dataquest.io/blog/settingwithcopywarning/) and
  * the [suggestion to use df.copy()](https://bit.ly/settingwithcopywarning).
* It's frustrating that some Jupyter Notebook tables don't display correctly in GitHub.
