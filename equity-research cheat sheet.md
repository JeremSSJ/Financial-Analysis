# Equity research cheat sheet

| Command                             | What it does                                                                        | When to use it                                             |
| ----------------------------------- | ----------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| `/equity-research:screen`           | Screens for stock ideas (value, growth, quality, short, special situations, themes) | You don't know yet which company to look at                |
| `/equity-research:sector`           | Industry report: market size, competitors, trends, valuations                       | Before studying a company, to understand its industry      |
| `/equity-research:initiate`         | Full first analysis in 5 tasks: research → model → valuation → charts → report      | Deep dive on a company you're seriously considering        |
| `/equity-research:earnings-preview` | What to watch, consensus, bull/base/bear scenarios                                  | A few days **before** a company reports                    |
| `/equity-research:earnings`         | Beat/miss analysis, updated estimates, thesis impact                                | 1–2 days **after** a company reports                       |
| `/equity-research:model-update`     | Plugs in new numbers, revises estimates and price target                            | After earnings, new guidance or a macro change             |
| `/equity-research:thesis`           | Records and checks why you own a stock                                              | When news comes in, or to ask "is my thesis still intact?" |
| `/equity-research:catalysts`        | Calendar of upcoming events for a list of stocks                                    | To see what's coming in the next weeks or quarter          |
| `/equity-research:morning-note`     | One-page daily digest of news on your stocks                                        | At the start of the day                                    |

You can also just ask in plain words ("do an earnings analysis of ASML's last quarter") and the right skill loads on its own.

## Typical flow

```
screen / sector → initiate (tasks 1–5) → thesis
catalysts → earnings-preview → [results] → earnings → model-update → thesis
```

Run initiate before earnings or model-update on a new company: they assume the earlier work exists.
