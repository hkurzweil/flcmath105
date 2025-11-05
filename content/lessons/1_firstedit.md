# What are Statistics?

## Introduction

The science of statistics deals with the collection, analysis, interpretation, and presentation of data. We see and use data in our everyday lives.  One of the goals of this class is to help you learn to pay attention to the data all around you, and the statistics produced from them. 

In statistics, we would love to study an entire population. You can think of a **population** as the whole collection of persons, things, or objects under study. However, studying every person, for example, is nearly (if not absolutely) impossible. So, to study the population, we almost always select a **sample** from that population. The idea of sampling is to select a portion (or subset) of the larger population and study that portion (the sample) to gain information about the population. Data are the result of sampling from a population.

Why would we want to sample? Why not just collect the data from the whole population? Populations tend to be very large, like all US residents, or all automobiles. It is very difficult, expensive, and time-consuming, to collect data from so many subjects. Maybe you would like to know the average number of siblings of a Fort Lewis student.  While, yes, you might be able to track down every single student that is enrolled here and ask them, this is really not realistic.  Instead, you would select a sample of students who would tell you how many siblings that they have, calculate the average, then generalize that average to ALL Fort Lewis students. By doing this, you can make an inference about the larger population based on the data from the sample you were able to obtain.

So just what is a **statistic**? Generally speaking, it is a numerical characteristic of a sample.  For example, finding an ‘average’ is a statistic of the data that it is calculated from. This course will cover many types of statistics, not so much how to calculate them by hand (luckily for all of us!), but more about how to use technology to get them and, more importantly, how to contextually interpret them.  The counterpart to a statistic is called a parameter. A **parameter** is a numerical characteristic of the population, that can be estimated or inferred by using a statistic.  The average number of siblings of ALL Fort Lewis students would be a parameter.  The average number of siblings of the students who were sampled is a statistic. #TLDR: Statistic is to sample as parameter is to population!

## Variables

A **variable** is a characteristic or measurement that you wish to study, and collect data about.  Recall from Algebra, a variable must be able to change. If we were interested in the average number of siblings of a Fort Lewis student, the variable we wish to measure (and collect data about) is number of siblings.  Each subject/student who participates in the study would tell the researcher how many siblings that they have. Be sure not to confuse a variable with a constant.  In this study, all of the subjects must be Fort Lewis students in order to participate.  Being a Fort Lewis student would be a constant, rather than a variable.

### Independent versus Dependent Variables

The **independent** variable has several possible meanings in statistics.  If a variable is being controlled by the researcher, it would be known as an independent variable. We also look to see if the independent variable causes, or affects, changes in the dependent variable. The **dependent** variable changes in response to the independent variable, The independent variable is also known as the explanatory variable; while the dependent variable is also known as the response variable.  These alternate vocabulary will be discussed when we get to Correlation and Regression.

A die hard baseball fan wants to see if there is a difference in the average number of hits between Babe Ruth and Hank Aaron.  In this situation, the fan would look at the number of hits for each player, where the number of hits depends upon which player it is.  The number of hits would be the dependent variable, while the player (Ruth or Aaron) would be the independent variable.

*Situations in statistics do not always have two variables.  Some of the data that we wish to analyze will only have a single variable.*  When that is the case, the variable is designated as the dependent (response) variable.  Perhaps someone is interested in whether the height of Fort Lewis students, in inches, differs from the national average height of college students.  In this situation, there is only one variable.  The height of FLC students, in inches, is the dependent variable; this is the only data being collected.  The national average is a statistic being used for comparison, a known value, and would not be a variable.

It is also possible to have three or more variables that you are interested in analyzing.  While you will come across a few situations in this class that have three or more variables, we will not be doing actual analysis of these situations in this course.


### Quantitative and Qualitative Variables

In statistics, it is critical to be aware of which type of data that you are working with.  Data can be **quantitative**, which means that it consists of meaningful numerical values.  Number of hits by a baseball player is quantitative data.  Data can also be qualitative, sometimes known as categorical.  **Qualitative** data consists of categories or qualities, or sometimes, numbers that have no meaning.  Baseball players would be qualitative. Other qualitative data includes hair color, eye color, favorite type of food. Position that you finish in a race, ie 1st, 2nd, 3rd, etc, is actually qualitative.  Even though it seems like you are collecting numerical values, those values, 1st, 2nd, 3rd, are not actually meaningful.  They are just the categorical name of finishing position.

In this class, you will frequently be asked to identify your variables for various situations.  In general, this means that you will have to state the actual variables, classify as quantitative or qualitative, and if appropriate, designate independent and dependent.  Going back to the baseball situation which was looking for a difference in the average number of hits between Babe Ruth and Hank Aaron, completely defining the variables would be:

- Independent variable: player (Ruth or Aaron), qualitative.
- Dependent variable: number of runs, quantitative.

### Levels of Measurement (LOM)

Quantitative and qualitative variable classification can further be broken down into four levels of measurement: Nominal, Ordinal, Interval and Ratio.

A designation of **nominal** is given to a qualitative variable which is simply a name, category or quality. Which type of running shoe you prefer is a nominal measure.

**Ordinal** measures are also names and categories, ie qualitative, but they also have a specific order to those names. An example of this would be Olympic medals. Bronze, silver and gold are categories, but there is a clear order to these in that gold is the highest achievement, then silver, then bronze.

Numerical, ie quantitative, variables are classified as either interval or ratio.

The **interval** designation is the level of measurement when the numerical values have meaningful distance between them. **Ratio** data goes beyond just meaningful distance between the values, and also includes a true zero to the data AND meaningful magnitude. Temperature measurements in Celsius and Fahrenheit are interval measures, because they are meaningful numerical values, but lack both a true zero and magnitude.  0 degrees Celsius does not mean the absence of temperature, nor is 100 degrees twice as warm as 50 degrees. The volume in a can of sparkling water measured in mL is ratio data. 0 mL is the absence of volume in a can, ie the can is empty. Also, a 16 oz can has twice as much volume as a can with only 8 oz.

One important thing to remember is that when asked a variable’s level of measurement, there is only ONE response.  If the variable qualifies to be ratio, then it is only designated as ratio. If a variable is ordinal, it is only designated as ordinal...at least when it comes to levels of measurement. However, we do typically classify quantitative variables with one other marker: either discrete or continuous. This isn't a level of measurement, but it is a way we describe the *types* of numbers you can expect to see. **Discrete** data can only take on certain values, and includes things that can be counted. **Continuous** data can be measured, and always includes some sort of units.  The number of students in your Statistics class is discrete data.  You would count the students; there would never be part of a student.  How many plants you have ever owned is also discrete. The height of a person, in inches, is continuous data – you would measure this variable. A summary of these levels of measurements and labels can be seen below in #fig_qualLOM and #fig_quantLOM. 

```{figure} https://github.com/hkurzweil/flcmath105/main/content/figures/qualLOM.png
:label: fig_qualLOM
:width: 70%
:align: center

Depiction of the various levels of measurement for qualitative data
```
```{figure} https://github.com/hkurzweil/flcmath105/main/content/figures/quantLOM.png
:label: fig_quantLOM
:width: 70%
:align: center

Depiction of the various levels of measurement and label identifiers for quantitative data
```
### Lurking or Confounding Variables ###

Two variables may be related, but this does not guarantee that one variable is influencing the other. In a study of weight gain in cats, researchers found that there was a strong connection between activity level and weight gain, indicating that less activity corresponds to greater weight gain. But, there are other factors that might be at play here. Age of the cat, or species may be lurking variables. A **lurking** variable (sometimes called a confounding variable) is not an independent/explanatory variable that we are studying, BUT it is a variable that is having a confounding effect on the variables that we are studying. We would need to design our study such that age is consistent among the cats, and sample from cats of the same species in order to eliminate age and species as lurking variables. Otherwise, age and species may be having some effect on cat weight gain, when we are really just interested in a connection between activity level and weight gain. 

#### Next Steps ####

This reading, the associated lecture notes, and your time in class discussing these topics should be the start you need to complete this week's first homework assignment! **Add private links later to Canvas course using Shane's email with repo instructions** 
**Also figure out how to include slides in this repo**
**Also figure out naming system at the end**

#### References ####
Adapted from [“Week 1 Introduction to Statistics and Variable Reading”](https://courses.fortlewis.edu/courses/17335/pages/week-1-introduction-to-statistics-and-variables-reading?module_item_id=438249) by Sherri Spriggs and Sandi Dang is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)


## Your first change

As explained in the previous chapter, your files are on GitHub and the template ensures the book is built.
You can make changes directly to the files online in GitHub, and create or upload new files.

Some files are already present in the template book.
The folder structure is shown below

:::{literalinclude} ../../myst.yml
:start-after: toc
:end-at: - file: content/software.md
:lineno-match:
:caption: The Table of Contents (ToC) for this book.
:label: lesson1_code_toc
:::

We will now make a small change to one of the files and then look at the result of that change.

````{exercise} Your first change
::::{tab-set}
:::{tab-item} GH IDE
Navigate to the file `Content/Lessons/1_firstedit.md`. Then click on the pencil on the right (edit this file).

Change the text after the `#`. This is the **title** of the file.

```{iframe} https://www.youtube.com/embed/bLhvq4a-03U?si=GQaFuZGn2-3E4b5Z
:align: center
:width: 100%

Choose your file, click on edit and make changes. Ready? Commit your changes to your repository and see the output.
```

Optionally, make other changes in the text editor and when you're done, commit your changes to the "remote repository" by clicking the green `Commit changes` button.

The book will now be rebuilt. Once that's done, you can view the result on the GitHub page.
:::
:::{tab-item} Locally
Navigate to the file `Content/Lessons/1_firstedit.md` and open the file.

Change the text after the `#`. This is the **title** of the file.

Optionally, make other changes in the text editor.
Check the results by running `myst start` in the CLI and opening the local server `http://localhost:3000/`.
When you're done, commit your changes to the "remote repository".

The book will now be rebuilt.
Once that's done, you can view the result on the GitHub page as well.

:::
::::
````

:::{note} Commit summary
:class: dropdown
If you are working with multiple people in GitHub, or on a large project yourself, it is wise to give the commit a recognizable title (commit message) and optionally add a summary (extended description) of exactly what was changed, see also [this more elaborative description](https://book.the-turing-way.org/collaboration/github-novice/github-novice-firststeps/#committing-or-saving-your-changes). 
This way, you can detect and undo any errors early. You can also explain why certain changes were made.
:::

## Adding a page

The [](xref:myst-guide/table-of-contents) defines the structure of your Jupyter Book.
Items in your `myst.yml`'s `toc` will be added to the book's table of contents.
Markdown, TeX and Jupyter Notebook files will be rendered as pages (in the case of a website) or chapters (in the case of a document).

To add a new page from a Markdown file,

1. Create a new markdown file
2. Add some content to the file
3. Include in the [ToC](#lesson1_code_toc)

```{exercise} Add a new page
:label: ex-add-a-page
::::{tab-set}
:::{tab-item} Using the GitHub IDE
1. Create a new markdown file
  - navigate to the folder where you want to include the sourcefile
  - click `add file` / `+ Create new file`
  - create a clear name for the file and use the .md extension (e.g. `newfile.md`)
2. Create a [H1 heading](#headings_cheat_sheet)
  - use for the header `#` and include the title
  - commit your changes
3. Include the file in the [ToC](#lesson1_code_toc).
  - navigate to the `myst.yml` file in the root
  - at the right location in your book, include the path to your file (e.g. `- file: content/lessons/newfile.md`)
  - commit your changes and check the output on GitHub pages.
:::
:::{tab-item} Locally
1. Create a new markdown file
  - navigate to the folder where you want to include the sourcefile
  - create a new file
  - create a clear name for the file and use the .md extension (e.g. `newfile.md`)
2. Create a [H1 heading](#headings_cheat_sheet)
  - use for the header `#` and include the title
  - save your file
3. Include the file in the [ToC](#lesson1_code_toc).
  - navigate to the `myst.yml` file in the root folder
  - at the right location in your book, include the path to your file (e.g. `- file: content/lessons/newfile.md`)
  - save your changes and check the out on your local server.
:::
::::
```



