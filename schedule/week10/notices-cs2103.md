## RepoSense

- We use a new tool called `RepoSense` to identify your contributions to the project.
  - The tool is setup for the module and the report is available under the [project-dashboard link](https://nus-cs2103-ay1819s2.github.io/cs2103-dashboard). 

- Ensure your code is RepoSense compatible. [Instructions here]({{ module_website }}/admin/project-w10-mid-v13.html#ensuring-your-code-is-reposense-compatible).


- Follow the [user guide for RepoSense](https://github.com/reposense/RepoSense/blob/release/docs/UserGuide.md) and fix the issues, if you don't see your contributions detected.


### FAQ:

1. My contributions are not detected in the Reposense report, why?
    1. Check:
        1. Have you set the `user.name` to your GitHub user name that you provided in the premodule survey?
        1. Have you used different git user name while doing the work? Run `git log` command on the command line/terminal and look for the `Author` field.
    1. If the above are correct, you may want to provide a config file to give additional details to Reposense (check the Reposense documentation mentioned above)
        1. You need to commit the config file before running Reposense, else the config won't be picked up by the tool.
    1. Do note: _if you include a config file, entries pertaining to all members of the team must be in the config file_.

1. I have done everything given in 1, but I still can't see my contributions. How to resolve?
    1. Use `@@author` tags to identify your code contribution in the source files. 
    1. Follow the instructions given in the Reposense documentation for this

1. I did 1 & 2, however, I cannot still see my contributions. Help!!
    1. Usually, most cases will be taken care of by 1 and 2 above. 
    1. In case your contributions are still not detected, please post the issue on this forum, we will get the reposense team to take a look.

1. How frequently is the Reposense report generated?
    1. Reposense is configured to run the report every Monday. i.e., the report is generated weekly.

1. My friend and I worked on a piece of code together, but only my friend committed. Now how?
    1. Use `@@author` tags to indicate chunks of the file that is your contribution. Arrive at a consensus with your friend/teammate before claiming part of the code as yours.

1. What is considered **good contribution**?
    1. Speaking from code-quality evaluation perspective, you need to have contiguous code chunks in your contribution (e.g., some full classes, some significantly long full methods).
    1. If the code is fragmented (e.g., you only added one additional field to a class, and entire code has fragmented one-two lines that work with the additional field you creates) it becomes hard to grade the code quality.