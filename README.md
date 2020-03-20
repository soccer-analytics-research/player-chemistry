# Player Chemistry: Striving for a Perfectly Balanced Soccer Team

This repository provides additional results for the *Player Chemistry: Striving for a Perfectly Balanced Soccer Team* paper that was presented at the [MIT Sloan Sports Analytics Conference](http://www.sloansportsconference.com) in Boston. 

The paper is available on the [conference website](http://www.sloansportsconference.com/content/player-chemistry-striving-for-a-perfectly-balanced-soccer-team/) and on [arXiv](https://arxiv.org/abs/2003.01712). The video recording of the talk that was given at the 2020 MIT Sloan Sports Analytics Conference is available on [YouTube](https://youtu.be/jeD5cq2PAJk) and the accompanying presentation slides are available on [Google Drive](https://docs.google.com/presentation/d/1AkvGilnpC2HoAQ5MmPqtdiRFcz8uk1RbV52hlexxclY/edit?usp=sharing).


## Paper summary
Soccer scouts typically ignore the team balance and team chemistry when evaluating potential signings for their teams. Instead, they focus on the individual qualities of the players in isolation. To overcome this limitation of their recruitment process, this paper takes a first step towards objectively providing insight into the question: How well does a team of soccer players gel? We address that question in both an observational and a predictive setting. In the former setting, we observe the chemistry between players who have actually played together, which is relevant when selecting the best possible line-up for a match. In the latter setting, we predict the chemistry between players who have never played together before, which is particularly relevant to assess the fit of a potential signing with the players who are already on the team.

We introduce two chemistry metrics that measure the offensive and defensive chemistry for a pair of players, respectively. The offensive chemistry metric measures the pair's joint performance in terms of scoring goals, whereas the defensive chemistry metric measures their joint performance in preventing their opponents from scoring goals. We compute our metrics for 361 seasons in 106 different competitions and present a number of concrete use cases. For instance, we show that the partnership between Mohamed Salah and Roberto Firmino in Liverpool's 2017/2018 Champions League campaign exhibited the highest mutual chemistry between two players. Furthermore, we show that Mesut Özil's chemistry has rapidly started declining following Alexis Sánchez' departure to Manchester United in 2018.

## Additional results
We computed the offensive and defensive player pair chemistries for all player pairs in over 350 seasons in over 100 different competitions across the world. 
The following files contain the top 5 player pairs for each of these seasons in terms of offensive player chemistry and defensive player chemistry, respectively.

* [Offensive player chemistry](offensive.md)
* [Defensive player chemistry](defensive.md)

## Authors
* [Lotte Bransen](www.linkedin.com/in/lotte-bransen/), Lead Data Scientist at [SciSports](scisports.com). 

* [Jan Van Haaren](www.linkedin.com/in/janvanhaaren/),  Chief Product & Technology Officer at [SciSports](scisports.com) and Research Fellow at [KU Leuven](www.kuleuven.be). 
