| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline
## Project summary

I open social media to catch up on what people are saying, but the feed has already made a choice about what I see first. For my final project, I want to explore how much that choice can affect what people do and what they think. I’ll focus on a seven-week randomized experiment with active U.S. users of X in 2023. The researchers assigned participants to an algorithmically ranked feed or a reverse-chronological feed. I’ll use the study to ask three questions readers can relate to: What shows up in my feed? Who am I more likely to follow? Which political opinions might shift? [Gauthier et al. (2026)](https://doi.org/10.1038/s41586-026-10098-2)

The part I find most interesting is what happens when people switch back to a chronological feed. The study found that turning ranking on increased the likelihood of following conservative political activists and shifted some issue-specific opinions in a more conservative direction. It detected no comparable shifts in political attitudes when a different group, already using the ranked feed, switched it off. I want readers to explore the size and uncertainty of those effects and consider whether their follow lists may help explain why changing a setting can be easier than changing what they see. [Gauthier et al. (2026)](https://doi.org/10.1038/s41586-026-10098-2)

**One-sentence summary.** In a seven-week experiment on X, switching to a ranked feed changed whom some users followed and shifted some political views, while switching to a chronological feed in a separate group produced no detectable reversal in political attitudes.

**Audience and user story.** As someone who scrolls social media for news, I want to compare what happens when algorithmic ranking is turned on or off so I can understand how much a feed setting might shape what I see, whom I follow, and what I think.

## Story outline

| Story beat | Planned screen | What the reader will see and learn |
| --- | --- | --- |
| Setup | **What decides your next post?** | Two mock feeds introduce “For You,” which ranks and recommends posts, and “Following,” which shows posts from followed accounts with newest first. A simple assignment diagram shows that researchers compared switchers with people who stayed on the same feed within each starting group. |
| Conflict | **The two feeds show a different mix** | Paired horizontal bars compare the percentage of sampled posts from political activists and from news organizations in the two feeds. These categories are displayed as separate comparisons. The reader sees how the mix differs before considering outcomes for users. |
| Conflict builds | **Who ends up on your follow list?** | A dot-and-interval chart shows the estimated effect of switching ranking on or off on the likelihood of following conservative political activists, liberal accounts, and news outlets. I’ll start with the conservative activist result, then let readers select the other outcomes for context. |
| Turning point | **Would switching back undo the shift?** | An aligned dot-and-interval chart compares the two switch directions for policy priorities, views on the war in Ukraine, and partisan identity. The chart shows readers which estimates move away from zero and which are compatible with no detectable change. Each panel names its own comparison group. |
| Resolution | **The accounts you follow can shape tomorrow’s feed** | I’ll return to the opening feeds and highlight a followed account that can still appear in the chronological view. The study suggests this as one explanation for the asymmetry. The final caption will identify the scope of the evidence: active U.S. users of X during a seven-week experiment in 2023. |

## Initial sketches
> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  

Text here...

# The data
I’ll use the public data behind Gauthier et al.’s (2026) Nature study, The Political Effects of X’s Feed Algorithm. The study draws on a seven-week randomized experiment with active U.S. users of X in 2023. I’ll use Figure 3 to compare the share of posts from political activists and news organizations in the algorithmically ranked and reverse-chronological feeds. I’ll use Figures 2 and 4 to show how being assigned to switch feeds affected users’ political attitudes and the types of accounts they followed. Study and source data

I’ll use the public replication package to check how the researchers defined each outcome, then organize the published results into two CSV files for Tableau. One will contain the share of sampled posts by feed and source type. The other will contain the estimated effects and their 95% confidence intervals. Each estimate will compare users assigned to switch with users assigned to stay on the same starting feed. This will let readers see how large the estimated effects were and how uncertain they are. Public replication package 


| Name | URL | Description |
|------|-----|-------------|
| *The Political Effects of X’s Feed Algorithm* — Nature Source Data | [Nature article page](https://www.nature.com/articles/s41586-026-10098-2) | The **Source data** section contains downloadable workbooks for Figures 2–4. I’ll use them to visualize political attitudes, what appeared in each feed, and the types of accounts users followed. |
| *The Political Effects of X’s Feed Algorithm* — Figshare Replication Dataset | [Figshare dataset page](https://doi.org/10.6084/m9.figshare.28033772) | The **Download** button provides the anonymized survey data, derived feed and account data, and analysis code. I’ll use these materials to check how the researchers defined each outcome. |

# Method and medium

I’ll use the study’s publicly available source data to create interactive charts in Tableau Public. I’ll embed the charts in a stand-alone Shorthand story so readers can explore what appeared in each feed and how switching feeds affected whom users followed and what they thought.

## References
- Gauthier, G., Hodler, R., Widmer, P., & Zhuravskaya, E. (2026). The political effects of X’s feed algorithm. *Nature, 652*, 416–423. [Article and figure source data](https://doi.org/10.1038/s41586-026-10098-2)

## AI acknowledgements
I came up with a story outline for my project, discussed it with GhatGPT, and asked for suggestions on how to improve it.
