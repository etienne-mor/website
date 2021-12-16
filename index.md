# Politics in sports media through quotes

## Introduction

Sport and politics have always been and will always be very closely related due to the high media coverage and the emotions involved. From the power demonstrations of nations such as as the Olympic games of Berlin 1936, going through movements such as the "black power" salute on the podium of 1968 Olympics games, to unification symbols such as the 1995 world cup organized and won by South Africa just after the end of apartheid. More recently, movements such as Black Lives Matters have been strongly supported by athletes while the US, Australia, UK and Canada announced a diplomatic boycott of Beijing 2022 Olympic games. 

All of these movements are well known political actions and show how strong the bond between sport and politics is. But what if they were just the tip of the iceberg ? Having a big dataset of quotes, the idea of this data story is to investigate the link between sports media and politics. How much a the quotes in sport article are related to politicians ? Are politicans trying to use sport and the related media coverage to influence the votes ? Are all the medias the same or certain are more politicized ? 

A lot of questions can be raised and the analysis can quickly become complexe. This datastory aims to bring an answer supported by data to certain of these questions.

## Are certain media more prone to publish political quotes in their sports article ?

So far it appears that quotes among sports media are actually linked to politics. However, we still wonder if all medias are the same regarding this bias. To do so, we can have a look to the proportion of political speakers among the different sports media. However, we have more than 2 000 different media sources, so we first need to pick a selection of them. Let's have look to the 30 biggest sports media in terms of number of sport quotes between 2015 and 2020 :

![](ranking.png 'Political speaker according to TOP 30 medias')

We can see that the 30 biggest medias have at least 300 000 quotes whereas only two medias really stand out : Yahoo and MSN with more than 2 million sport quotes.
Now, that we have this selection of sports media, let's see what the proportion of political speakers in sport quotes there is for each media : 

![](Political_speakers_by_media.png 'Political speaker according to TOP 30 medias')

As one can observe on this image, the proportion of political speakers among the different media ranges from 1.5% for Skysports to 71% for krmg. This seems to indicate that certain media are definitely more politicized than others and uses their sports section also for political reasons.

## Evolution of the phenomenon through time

Another interesting question to ask is : how does the phenonenon of having politicized quotes in sports article evolves through time. For instance, does it increases during the during the campaigns of the US presedential elections ? 

To try to bring an answer, we wanted to have a look at the policized sports quotes each month over the years and here is what we obtained : 

![](mounth_frequency.png 'Mounth frequency of sport related quotes')

Unfortunately, as one can observe, it is not possible to identify any trends due to the huge variations of sports quotes through the years, itself related to the variation of all the quotes availble in the database at first. Indeed, we relate the drops in 2016 to the one mentionned in the [article about quotebank](https://dlab.epfl.ch/people/west/pub/Vaucher-Spitz-Catasta-West_WSDM-21.pdf).

However, another approach is to have a look at the media themselves and how their tendancies have evolved through time : 

![](STD.png 'Variation trhough the years')

This first graph shows the standard deviation of the percentage of politicised sports quotes over the 6 years of data. We can observe that certain media are very stable with a standard deviation inferior to 1% over 6 years, whereas other are highly unstable, reaching more than 26% for KRMG. This could be related to a change of internal policy or direction. 

To visualize better what is going on through the years for the most unstable medias, i.e. with a standard deviation superior to 10 :

![](variation.png 'Variation trhough the years')

We can observe that for instance that for MSN there is a downward trend with a sharp drop after 2015, but it stayed relatively stable afterwards. JDSupra shows no clear trends whereas the rest of the medias show relatively upward trends.
 
