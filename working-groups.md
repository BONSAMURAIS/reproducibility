# Hackathon Working Groups

> "For instance, one thing I learned during my internships is that I did _not_ want to be a QA engineer." --CJ Kempf

As the start of #Hackathon2019 approaches, expectations are high, and the list of potential tasks, deliverables, and challenges is long. It is not exactly clear what is going to come of the project.  But one thing that is clear: we want the fruits of our efforts, both products and software, to live on and to be of value to BONSAI users in the near and distant future, and even to non-BONSAI users.

The `reproducibility` working group has the general meta-objective of ensuring that the other working groups "meet our transparency and reproducibility standards."  To me, this means that the deliverables of this working group are procedural: we need to set standards for the other groups to follow, and then help them meet those standards.  This condition has led me to think of the reproducibility working group as the Quality Assurance / Quality Control branch of the hackathon. And while that is not especially glamorous, it is important.

## What are our transparency and reproducibility standards?

We are using two "checklist" collections to help us define these standards.

 1. The first is the [FAIR Guiding Principles](https://www.nature.com/articles/sdata201618), which were articulated to help the products of research be "Findable, Accessible, Interoperable, and Reusable".  This helps us attain transparency.  We will select a subset of these principles to enforce on the working groups.

 2. The second has to do with technical reproducibility and comes from this list of [Ten simple rules for reproducible computational research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285).  These are guidelines for software products specifically and have to do with good housekeeping practices that ensure that the code runs.

Our stretch objective has to do with "replicability" of the results-- in statistical fields, replicability means someone else does the experiment independently and gets the same result.  This is a bit ill-fitting for a scientific computation problem, since nobody would write an entirely new software framework just to get the same result as us from the same data.

Instead, I am interpreting replicability as being "replicable design."  Essentially, we want the meanings of our modeling choices to be clear, and we want to enable others to independently make the same or different choices and see how those choices affect the outcomes.  This is harder to put a finger on, and it will develop through the course of the week as we observe what sorts of choices people are making.

## What are the responsibilities of the other groups?

This is where it gets really meaty.

### 0. Identify Yourself

We need to know every distinct project that is going on under the purview of this hackathon.  I have created a [working-groups status page](https://github.com/BONSAMURAIS/hackathon-2019/blob/master/working-groups.md) for all working groups to register their deliverable projects.  This will serve both as an audit list for us, and as a record of accomplishments.

### 1. Identify every reproducible project

There is a lot going on in pre-production here, so it's hard to tell what work will actually become a reproducible project.  Once you have something, though, you gotta let us know. So that we can audit you.

### 2. Identify Inputs

Inputs are all the data that goes into the magic computing thingy to make it work.  An input could be a static file, or the result of an API query, or user-entered data, or (in rare cases) nothing at all.  The important thing is that the inputs are well-stated.

Some inputs are necessary to make the program run but not strictly part of the computation. The best example here is an API key.  These inputs should be reported but not necessarily replicated. (your API key should be regarded as secret).  Try to mention every relevant configuration input.  As a rule of thumb, if you didn't have to touch it to make the program run, don't report it.

### 3. Identify and format outputs

The outputs are how you know that the program ran successfully.  The output should most likely be captured and committed to GitHub.  Eventually we will work on tools for formatting the outputs as [data packages](), but that will come later in the week.

### 4. Describe your methods

The process for converting input to output is what the code describes.  Your best practices here should come in the form of following the [ten simple rules](docs/journal.pcbi.1005412.s001.pdf) mentioned above.

### 5. Test your methods

coming soon

### 6. Respond to our nudges

We will be nudging you to keep your work consistent with our transparency and reproducibility objectives. Please be responsive.





## What is our end goal?

By the end of the week, we should have operable standards that demonstrate the reproduciblity of data products.
