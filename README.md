# mealanalysis

Build a program to analyze app usage data for a hypothetical menu planning calendar app. On any day, a user can plan multiple meals, and each meal may have multiple dishes. The program you build will analyze how engaged users are with the app. Style

There are many ways to write such a program. When choosing your style, imagine that you are building a system that will evolve to handling many more features in the very near future, so structure your code in a way that would support such a future. Language

Use a language of your choice. Include instructions to get from unzipping to runnable state, including details of what OS/version your code is meant to be run on.

NOTE: Some candidates chose to code their solution in "the language I've wanted to play with for a while but never had a chance to". We do not recommend this. We want to see the candidate's coding skills (naming, layout, design, readability, use of libraries, idioms, best practices) at their absolute best, and using a new and unfamiliar language is unlikely to produce optimal results, unless the candidate spends far more time on this question (to learn the language well) than we are comfortable asking for. Data

In the ./data folder, you will find a bunch of files in the form userId.json. They contain app data for a bunch of users. The structure should be fairly obvious upon examination. Output

./dist/run active 2016-09-01 2016-09-08

should result in a list of comma- separated user ids that were “active” during the specified period, where “active” means they had at least 5 meals. ./dist/run superactive 2016-09-01 2016-09-08

should result in a list of comma- separated user ids that were “super-active” during the specified period, which means they had more than 10 meals. ./dist/run bored 2016-09-01 2016-09-08

should result in a list of comma- separated user ids that were “bored” during the specified period, meaning that they were “active” in the preceding period, but didn’t make the “active” threshold in the specified period. Assumptions

Please explicitly state any assumptions you make. Clarifications

Feel free to email for clarifications if something is unclear. Submission

Please submit a tarball containing the code, data, build instructions, and whatever else you deem necessary to help us reach our stated evaluation goals. Expected Amount of Work

We expect this work to be completed in about 3 to 4 hours. If it starts looking like it will take longer than that, possibly your coding speed is slower than we were hoping for. Speed is only one facet of building software, and we’d love to evaluate as many facets as we can in this exercise, but do not want to cost you any more time beyond what we expect and thus consider reasonable.

So, if 2 hours into it you think you’ll run way overtime, please cut scope, in a way that maximizes your chance of demonstrating the things listed in the “purpose” section of this document. Having some runnable code is better than having a bunch of code that doesn’t run.
