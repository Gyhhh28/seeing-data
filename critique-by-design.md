| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and Redesign: Lazy Cats

For this assignment, I picked a Makeover Monday chart about pet cats and how much time they spend resting in different seasons. I liked the original at first because it is cute and easy to look at. But once I tried to compare the cats more carefully, I realized that the design was doing more decoration than explaining.

## Step one: the visualization

Original visualization: https://makeovermonday.vercel.app/dataset/2025-week-47-lazy-cats
<img width="2410" height="1624" alt="image" src="https://github.com/user-attachments/assets/14cd2bf7-f3a4-432c-a568-8592cae7bee7" />

I chose this visualization mostly because the topic is cute. Cats make people want to look at the chart before they even know what the data is about, which I think is valuable. At the same time, the original design made me curious about what the data was actually saying. I could see lots of cats and different shapes, but I could not quickly tell which cats changed the most between summer and winter.

The dataset includes the same 28 cats in both seasons, so it gave me a clear way to make those comparisons more visible without losing the playful feeling of the original.

## Step two: the critique
I completed the Data Visualization Effectiveness Profile in the Google Form. I gave the original chart credit for being visually interesting. The cats are fun to look at, and the colors make it easy to notice that some cats are indoor-only while others also go outside.

But the more I looked at it, the less sure I was what I was supposed to compare. I could not identify individual cats, and the chart does not show the summer and winter numbers separately. The vertical placement tells me whether a cat was lazier in winter or summer, but not how big that change was. It also uses color, cat shape, horizontal position, and vertical position all at the same time.

My redesign focuses on making the comparison more direct. I decided to show each cat twice—once for summer and once for winter—and connect the two values with a line. That way, a reader can see both the direction of the change and how large it is.

## Step three: Sketch a solution
Before making the final chart, I sketched out a connected dot plot. Each row would be one cat. Blue would stand for summer, orange would stand for winter, and the line between them would show how much the cat changed.

<img width="1897" height="2774" alt="v1" src="https://github.com/user-attachments/assets/1387105c-9789-433b-a7f7-0453c0db8057" />

This felt like a better fit for the data because the reader can compare the two seasons without having to decode cat shapes or guess what the vertical position means. I also sorted the cats by their winter-versus-summer difference. Cats near the top had a bigger increase in resting time during winter; cats near the bottom had a bigger increase during summer.

## Step four: Test the solution

Before sharing the draft, I asked each person three broad questions:

What do you think this chart is showing?
What is the main takeaway you notice?
Is anything confusing or difficult to read?

Results: 
| Question | Interview 1 | Interview 2 |
| --- | --- | --- |
| What do you think this chart is showing? | It compares how much time each cat spent sitting or lying down in summer versus winter. | It shows the difference in resting time between summer and winter for 28 individual cats. |
| What is the main takeaway you notice? | Many cats rested more in winter, but a substantial number actually rested less. Cat 2 appears to have the largest seasonal change. | There is no consistent pattern across all cats. Some become much lazier in winter, while others are more active in winter. |
| Is anything confusing or difficult to read? | The middle section is slightly crowded because some values are very close together. | The colors and labels are clear, but it took a moment to realize that the cats are sorted by the size and direction of the seasonal change. |

Synthesis: 
Both classmates understood the basic comparison without extra explanation, so the connected-dot format was working. They also came away with the same larger point: the cats do not all follow one seasonal pattern.

The useful criticisms were about readability rather than the main idea. One person found the middle a little crowded, and the other did not immediately notice how the cats were sorted. For the final version, I added more spacing, made the sort order explicit in the subtitle, and separated cats that rested more in winter from cats that rested more in summer.

## Step five: build the solution

Both classmates understood the basic comparison without extra explanation, so the connected-dot format was working. They also came away with the same larger point: the cats do not all follow one seasonal pattern.

The useful criticisms were about readability rather than the main idea. One person found the middle a little crowded, and the other did not immediately notice how the cats were sorted. For the final version, I added more spacing, made the sort order explicit in the subtitle, and separated cats that rested more in winter from cats that rested more in summer.

<img width="1897" height="3031" alt="final_version" src="https://github.com/user-attachments/assets/37d56b2c-d12b-4994-98e3-f19b50981ffd" />


## References
https://makeovermonday.vercel.app/dataset/2025-week-47-lazy-cats
https://lazy-cats.netlify.app/
https://bit.ly/4p0Omn3

## AI acknowledgements
I used ChatGPT to help me work through the CSV fields, calculate resting time from propLying + propSitting, and think through possible chart designs. It also helped me create a first digital draft and revise the final layout after I received feedback. I checked the values in the final chart against the supplied dataset.
