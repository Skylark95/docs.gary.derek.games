---
Title: General
---

General commands.
​
## Commands
- {{% commandref 8 "Ask 8 ball a question." %}}
- {{% commandref choose "Choose between multiple options." %}}
- {{% commandref flip "Flip a coin... or a user." %}}
- {{% commandref lmgtfy "Create a lmgtfy link." %}}
- {{% commandref roll "Roll a random number." %}}
- {{% commandref rps "Play Rock Paper Scissors." %}}
- {{% commandref serverinfo "Show server information." %}}
- {{% commandref stopwatch "Start or stop the stopwatch." %}}
- {{% commandref urban "Search the Urban Dictionary." %}}

{{% command 8 "Ask 8 ball a question." "<question>" "8ball" %}}
Question must end with a question mark.
{{% command choose "Choose between multiple options." "<first> <second> [others...]" %}}
There must be at least 2 options to pick from.<br>
Options are separated by spaces.
{{% command flip "Flip a coin... or a user." "[user]" %}}
Defaults to a coin.
{{% command lmgtfy "Create a lmgtfy link." "<search_terms>" %}}
{{% command roll "Roll a random number." "[number=100]" %}}
The result will be between 1 and `<number>`.

`<number>` defaults to 100.
{{% command rps "Play Rock Paper Scissors." "<your_choice>" %}}
{{% command serverinfo "Show server information." "[details=False] "%}}
`details`: Shows more information when set to True.<br>
Default to False.
{{% command stopwatch "Start or stop the stopwatch." "" "sw" %}}
{{% command urban "Search the Urban Dictionary." "<word>" %}}
This uses the unofficial Urban Dictionary API.