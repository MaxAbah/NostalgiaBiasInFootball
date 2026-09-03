# Nostalgia Bias in Football

### Figuring out if there is a way to quantify the gap between players from past eras or if there is a noticeable gap at all

The first thing you see on Twitter or go talk to your older relatives about football are complaints
about the quality of strikers today. But like many things, this fondness for things gone can be explained
through nostalgia bias. Through this project, I wanted to see if we can quantify how nostalgia bias takes
shape and impacts our memory when looking back at athletes from years past to ones who are playing now.
I did so by doing the following:

* Selected 15 players from 2 eras to compare directly against with their best 5 season stretch in the t5 leagues
* One from the late 90s/2000s, the other 2010s/20s
* Calculated their 'x amount of minutes per G/A' from their Transfermarkt stats
* Capture the median(25th-75th percentile) in a gray band to best depict the avg performance level for the era using numpy
* Highlighted the most unique names from the findings of each era to describe why their data reads off how it does in context

## Findings: 

I found that there is subtle difference in quality of performance between both eras. The 90s/2000s era median from the
25th-75th percentile was 98-122 minutes every goal or assist. The definitive median would then be 105. Meanwhile, the
median from the 25th to 75th percentile of the 2010s/20s cohort was 78-113 minutes every goal or assist. This would make
the definitive median for this era to be 98. We can see through further calculating our readings that with the 90s/2000s group
that they have a higher standard deviation and variance(1003 vs 760, 32 vs 28).

This means that the modern era is a lot more consistent across the board as they didn't deviate too much from their performance
levels like past players. Players like Shevchenko and R9 for example had serious injury issues which affected their output
massively. However, there are others like Andy Cole, Vieri, and Hasselbank who were just more streaky in form than their peers.
The modern age strikers have names like Lewandowski, Suarez, Kane and Aguero who are renowned for their ruthlessness in front
of goal but even players who weren't/aren't classified as being so prolific by the public such as Higuain, Cavani and Osimhen
put up very respectable numbers.

# Conclusions:
Through this research, I did notice that it was harder for me to name out and out strikers from the modern day. It was very
easy to come up with names for the past era group in comparison which made me realize that there is a real conversation
to be had about the fact that past eras enjoyed having a greater amount of strikers of a higher quality as a whole. As you read
the names in the modern group, many are already retired or nearing retirement. That doesn't negate the fact that world
class strikers are still producing at a better rate than the best of those from the past. However, it does raise attention to
the fact that strikers of a certain quality aren't being produced anymore. This can be due to 2 things:

* Youth players getting discouraged from playing there due to increase in physical demands
* Society's fondness shifting over into the winger over the past 2 decades

Many young players who in previous eras would've made their money off running in between the fullback and centre back are being
discouraged from playing as a striker because most now want a physical presence up top. This is due to the change in systems as
2-man striker systems aren't as popular, meaning the little man archetype doesn't exist nearly as much as they once did. This 
also makes those who still exist become very underappreciated. For example, Lautaro Martinez is one of the few strikers today 
standing at less than 6'0 playing for an elite club at striker. He constantly gets underrated due to his numbers but through the
findings, we see he averages a G/A every 110 minutes. In comparison, Crespo averaged a G/A every 104 minutes, Batistuta every
130 minutes, Andy Cole every 114 minutes, and Vieri every 103 minutes.

On top of that, young fans nowadays grow up wanting to be wingers. With what Ronaldo, Messi, and Neymar have gone on to do in
the past 15-20 years, many fans grew up infatuated with beating their man out wide rather than getting on the end of a tap in.
Those who rave about strikers from the past aren't just simply talking about the quality of striker but rather the quantity that
were once commonplace across Europe. In that case, it is reasonable for them to rave about past players but if it is strictly
about quality, then their argument is simply not defendable
