## Hey there, I'm Alex! :wave:

I'm currently an :man_student: **applied sciences student** at :round_pushpin: **Fulda University**. While studying I've not only created subject-related programs but I've developed my own based on either interests or subject-related topics (e.g. data processing with information extraction).
The **latest project** started is an interest-based and subject-related one. I'm creating a simple **application for information extraction out of data** using Python. More projects I've worked on earlier or working on in the free time can be read about below.

<details>
<summary>Playful way to introduce my coding skills (at least in Java)</summary>

```java
public class AboutMe {

    public static void main(String[] args) {
        List<Skill> skillSet = new ArrayList<>();
        addSkill(skillSet, "Realizing idea-based apps into code", 3);
        // Let's pretend, here are several more lines of code adding skills of mine to the list ... ;)
        listSkills(skillSet);
    }

    private static void listSkills(List<Skill> skillSet) {
        System.out.println("Things I'm good at:\n");
        for (Skill skill : skillSet) {
            if (skill.getLevel() > 1) {
                skill.showSkill();
            }
        }

        System.out.println("\nSkills I need to work out yet:\n");
        for (Skill skill : skillSet) {
            if (skill.getLevel() == 1) {
                skill.showSkill();
            }
        }
    }

    private static void addSkill(List<Skill> skillSet, String skill, int level) {
        skillSet.add(new Skill(skill, level));
    }
}
```

```console
java AboutMe
```

```
Things I'm good at:

Realizing idea-based apps into code (Professional)
Java (Advanced)
Python (Advanced)
Regex (Advanced)

Skills I need to work out yet:

JavaFX
Git
Terminal (Unix)
```

</details>

## Projects I'm currently working on

**Data Mining App** (*Python*) is an idea-based and subject-related application to work with files of CSV-like type in the first place.
<details><summary>...</summary>

Its functionalities up to now are
- the ***creation of a data matrix out of a CSV-like file*** with resulting data like the header of the dataset, the raw data itself and the variables' types (nominal, ordinal or metric),
- the application of algorithms on data columns to ***calculate the entropy, mean, median and mode***,
- the ***creation of new columns based on user-chosen functions*** like `date_diff_years(header1, today())` where in this case executing `custom_calculation("date_diff_years(header1, today())", "NewHeader")` will result in determining the current date, calculating the difference between that date and the dates in `header1`, and creating a new column named `NewHeader` with the difference rounded at a precision of two decimal places, and
- the ***creation of decision trees***.

</details>

**WebScraper** (*Java, regex*) is a project to simplify processes by automating them.

<details>
<summary>...</summary>

The processes implemented yet are
- the ***search for words and phrases*** on a web page,
- ***getting a list of email addresses*** listed on a page and
- ***downloading files*** of a given extention type from a page.

</details>

## Coding languages and structures I prefer or I'm learning yet

Since school I've gained some experience in **C language** and developed some small but interesting projects. There also was some interest in developing for the web using JavaScript and related languages, but I stuck to delelopment using C with then reaching for as of now more prioritized languages, e.g. **Java** and **Python**, with some related and just interesting structures, namely **regex**, **JavaFX** and more.