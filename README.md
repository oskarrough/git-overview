# Git overview

A small program that runs `git status` for all child directories,
and outputs in a dense overview.

For now, it's not worth publishing anywhere. 

Git clone this repository  
cd into it  
chmod +x git-overview

Now, try to run `git-overview` in a folder with multiple folders backed by git.

Example output:

```shell
 I  ~/sites ❱ git-overview
○ 2dhealer             main         M:4            9 months
○ 40q                  main         ?:2            10 months
○ agent                5e911a6      M:4 stash:1    4 days
◇ bonpi                main         stash:1        1 year
◇ command-menu         main         stash:1        2 years
○ emojimind            upgrade-vue3 M:1            3 years
○ explorer-discogs     master       ?:1            5 years
○ git-overview         newyearrefr… M:3 stash:1    9 years
○ media-now            main         ?:1            4 years
○ oneforthemoneytwofo… main         M:1            1 year
◇ oskarrough.com       main         stash:1        2 weeks
○ pino                 main         M:2            6 months
○ rough-sheet          main         ?:1            5 months
○ simuu                4ec9990      M:2 ?:1        7 days
◇ slaytheweb           main         stash:5        4 weeks
◇ spotify-to-youtube   main         stash:1        1 year
○ storethis            main         M:3            1 year
○ text2tube            main         M:5 ?:1 stash:1 6 months
○ tiptap               basic-layout M:1            2 years
◇ touchme              main         stash:16       7 weeks
○ towerpower           main         M:2            1 year
○ umami-test           master       ?:1            6 months
◇ walkietalkie         main         stash:1        6 months

◆ balancemender        main                         9 months
◆ clayproto            66c6948                      7 weeks
◆ effect-mentor        main                         1 year
◆ freedomtv.cc         main                         8 years
◆ github-mcp-server    main                         9 months
◆ infinite-craft       50568f2                      4 weeks
```
