| [home page](https://huanghsintzu.github.io/hsintzuh_tell_stories_with_data/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Which Animals Do U.S. Adults Consider Unacceptable to Eat?

I redesigned a Statista chart about the ethics of eating different animals. I started with the original chart’s “one in four” takeaway about octopus, sketched a ranked bar chart, and tested the sketch with three classmates. In Tableau, I added a comparison between women’s and men’s survey responses.

## Step one: the visualization

I selected Anna Fleck’s Statista chart, “[One in Four Americans Say It’s Wrong To Eat an Octopus](https://www.statista.com/chart/30299/us-survey-on-ethics-of-eating-animals/).” The chart draws on a 2023 YouGov survey that asked U.S. adult citizens whether they thought it was morally acceptable for other people to eat each animal under normal circumstances.

The headline caught my attention because it made 24% easy to understand. It also made me curious about where octopus fell among the other animals in the survey. I wanted readers to be able to find the main takeaway quickly and then explore how attitudes varied by animal and by gender.

## Step two: the critique

### What stood out, and what worked well or could be improved?

The headline and the octopus illustration were the first things I noticed in the Makeover Monday chart. I liked how the headline expressed 24% as “one in four,” which made the proportion easy to grasp. I also liked the idea of using a different color to highlight octopus. In practice, the brighter reds drew my eye more than the dark red used for octopus, and the large illustration competed with the data. At first, I thought the chart showed how many people considered eating each animal acceptable. I also read the labels as counts because they lacked percent signs. I had to read the subtitle to understand what the values represented.

### Who is the primary audience, and is the visualization effective for them?

I think the primary audience is general readers who are curious about Americans’ attitudes toward eating different animals. The headline gives them a memorable takeaway in everyday language. Someone skimming the bars, though, could easily miss that the numbers are percentages of respondents who considered eating each animal morally unacceptable.

### What did I focus on in my redesign?

I wanted a title that clearly stated what the chart measured and a separate “one in four” callout. I planned to add percent signs to the labels, use a bolder color for octopus, and mute the other bars. For the sketch, I also wanted to try replacing the large illustration with four small icons, highlighting one and placing the exact value of 24% beside them.

## Step three: Sketch a solution

I drew a horizontal bar chart with all 16 animals ranked by the overall share who said eating each animal was morally unacceptable. I wrote the percentages at the end of the bars so readers could see exact values without estimating from the axis. I used orange for octopus and repeated that color in a boxed “About 1 in 4” callout above the chart. I also added a subtitle to explain what the percentages represented.

The sketch helped me think about how a reader would move from the headline to the ranked bars. It also gave me a way to test whether the callout made sense to someone seeing the chart for the first time.

<!-- Optional: upload your sketch photo next to this Markdown file as octopus-sketch.jpg, then uncomment the image below. -->
<!-- ![Hand-drawn sketch with 16 ranked horizontal bars and an orange callout for octopus at 24%.](./octopus-sketch.jpg) -->

## Step four: Test the solution

I showed my paper sketch to three graduate student peers. I took notes across the conversations and recorded the feedback collectively.


### Results

I recorded the comments together. The placement of comments under the numbered columns is illustrative because my notes do not identify who gave each response.

| Question | Interviewer 1: female MSPPM-DA student| Interviewer 2: female MISM-BIDA student | Interviewer 3: Make MISM student |
| --- | --- | --- | --- |
| What made the chart easy to read? | Descending order made the bars easier to scan. | Percentage labels made exact values easy to find. | The title and subtitle helped explain the chart. |
| What stood out? | The visual emphasis drew attention. | The bold headline stood out. | — |
| What was confusing? | The title could be worded more clearly. | The purpose of the callout was unclear. | It was unclear why octopus was singled out. |
| What would you change? | Reword the title. | Explore grouping the animals. | Make the reason for highlighting octopus clearer. |

### Synthesis

The feedback showed me that readers could spot the highlight and still wonder why it was there. I kept the direct percentage labels and the title-and-subtitle structure from the sketch. For the Tableau version, I rewrote the title as a question and kept the octopus callout focused on a specific finding. Grouping the animals was another idea from the interviews, but I wanted readers to be able to compare responses across animals without first having to interpret a set of animal groups.

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1794540296510' style='position: relative'><noscript><a href='#'><img alt='Which Animals Do US Adults Consider Unacceptable to Eat? (Female vs. Male)Share of US adults who says it&#39;s normally unacceptable to eat these animals under circumstancesAbout 1 in 4 people says it&#39;s not okay to eat octupus! ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnimlasUnacceptableToEat&#47;BarChartwVariance&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AnimlasUnacceptableToEat&#47;BarChartwVariance' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;An&#47;AnimlasUnacceptableToEat&#47;BarChartwVariance&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1794540296510');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>




[See on Tableau Public](https://public.tableau.com/views/AnimlasUnacceptableToEat/BarChartwVariance?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) 

I built the final version in Tableau with a question as the title and a subtitle that explains what the survey percentages measure. I chose horizontal bars because the animal names fit comfortably and the common percentage scale makes it easier to compare responses. The gender breakdown adds a comparison that was missing from my paper sketch. Readers can now compare the shares of women and men who considered eating each animal morally unacceptable.

The octopus callout connects the redesign to the finding that drew me to the original chart. In the YouGov results, 24% of respondents overall considered eating octopus morally unacceptable, including 26% of women and 22% of men. The overall figure explains the “about one in four” callout, while the breakdown shows a four-percentage-point difference for octopus.

## References

- MakeoverMonday [One in Four Americans Say It’s Wrong To Eat an Octopus](https://makeovermonday.vercel.app/dataset/one-in-four-americans-say-its-wrong-to-eat-an-octopus)
- Tutorial Video: Andy Kriebel-Watch me Viz [WHAT??? 27% of US adults think it's ok to eat dogs!](https://youtu.be/ClTtIlp4r_w?si=uoGRTKAqC-NpUjSV)

## AI acknowledgements

I used ChatGPT to help refine the title, get guidance on formatting category labels in Tableau.

