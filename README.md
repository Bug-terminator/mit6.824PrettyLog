## Overview

Pretty log for MIT6.824 distributed system.

![avatar](pics\apearance.png)

## Get Started

### rf.Dprintf

This function is in the util.go file,and generates prefix like`31883: [peer 1 follower at Term 58 with Log 317 230 tailterm 50 ]`.The usage is very simple,for example:

```go
rf.DPrintf("[%d send AEs]",rf.me)
```

will result in

![](pics\result.png)

You can DIY it according to your own needs.

### vscode Highlighter

- Download plug-in

  ![](pics\highliter.png)

- press`ctrl+shift+p` and enter `settings`,choose `preference:open settings(JSON)`,Copy my settings.json into it.

  ![](pics\settings.png)

### go_test_many.sh

You can use this shell script to Parallel test your code.[This video shows how to use it@1:20:30](https://www.youtube.com/watch?v=UzzcUS2OHqo&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB&index=5)

All three files mentioned above are in the kit folder😋Enjoy your Debug journey.

