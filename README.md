# Goal

The goal of the program is to set my bash prompt to the output of a single
binary:

```lang=bash
PS1="$(bashprompt)"
```

The reason for this project is that I realized how many of the PIDS generated on
my system are a result of creating output for my bash prompt.

In one sense it's amazing that we have these DSLs like bash and awk and shell
pipelines for filtering that make it easy to make complex prompts in a few
lines.

On the other hand the overhead of these complex pipelines compared to a C or C++
project is large.

**Note**: I am not currently using this as my prompt, it's just an experiment.
