---
layout: post
title: Experiencing Sure Bets
---

In this article I want to share my knowledge and experience trying to make money with Sure Bets. During the trip I could practice web scraping with a simple JAVA program I wrote. This program can be found [here](https://github.com/marcogalluzzi/surebets). And, at the end, I could leverage the gained experience to write an article comparing the sportsbook websites. This article can be found [here]({{ site.baseurl }}{% post_url 2018-03-05-short-analysis-of-sportsbook-websites %}).

#How betting houses earn money with sports bets
One day, a friend of mine working for a company involved in the calculation of probabilities for sports bets told me how betting houses calculate the odds for a soccer game in order to earn money. In short, they make the sum of odds for the different options, 1 X 2, to be less to what estimated probabilities dictate. Doing that the betting houses always retain between the 2% and 6% of the bets. This can be better understood with an example.

Given the match “Sevilla – Atlético de Madrid” the house estimated that the probability for each result is the following:

* Sevilla wins: 28%
* Tie: 30%
* Atlético de Madrid wins: 42%

The fair odds for this estimations are the following:

* Sevilla wins: 1 / 0.28 =  3.57
* Tie: 1 / 0.30 = 3.33
* Atlético de Madrid wins: 1 / 0.42 = 2.38

If the betting house applied fair odds, it wouldn’t earn money, supposing the betters invest in the different results according to these odds. The earnings obtained with the bets of the two wrong results would be equal to the loss suffered with the bets of the correct result. If I invested 1000€ on this match with fair odds and trying not to lose money whatever the result will be (it wouldn’t be possible to earn money) I would bet this way:

* Sevilla wins: 280€. On a correct guess I would earn: 280 x 3.57 – stake = 1000€ - 1000€ = 0€
* Tie: 300€. On a correct guess I would earn: 300 x 3.33 – stake = 1000€ - 1000€ = 0€
* Atlético de Madrid wins: 420€. On a correct guess I would earn: 420 x 2.38 – stake = 1000€ - 1000€ = 0€

Then, the betting houses lower a bit the odds they offer in order to earn money. In this example we have:

* Sevilla wins: 3.3 → Simple probability: 1 / 3.3 = 30.3%
* Tie: 3.25 → Simple probability: 1 / 3.25 = 30.77%
* Atlético de Madrid wins: 2.3 → Simple probability: 1 / 2.3 = 43.48%

Now the sum of all simple probabilities is 104.55% and this implies a payment rate of 1 / 1.0455 = 0.9565. This means, the betting house would earn the 4.35% (100-95.65) of the total amount of money from all bets for this match. This way, in this example if I bet 1000€ and I tried to minimize the loss, the minimum I would lose would be 43.5€, which is the commission of the betting house.

#Sure bets
As we’ve seen, the betting houses make sure that, whatever you bet on a single match, they earn money while you are not sure about earning money. But in my mind the following idea became clear: ¿isn’t it true that different betting houses have different odds for the same match? ¿would it be possible to combine odds of the same match from different betting houses to achieve a total simple probability lower than 100%, what would mean earning money for sure?

Having a look to different sportsbook websites I couldn’t find an example match that would confirm my hypothesis. By chance I found a website comparing odds from different betting houses for the same match, making easier my manual search. And finally I found an example match that would make anyone to earn money for sure, betting on different sportsbook websites at the same time, even if it would be only a little percentage of the money invested.

Wow! This was looking interesting. However, to try to bet on a regular basis to this kind of matches I considered essential automatize its search and selection. And then the project became even more interesting (from my point of view): I had to create a software to help me with these tasks.

Many functionalities came to my mind for the software I was about to build, but I didn’t know the world of the betting houses so I decided to address the project in this way: I would add functionalities step by step and, at the same time, I would register to the different sportsbook websites and test that the bets defined as “sure” could be done.

The project started and it was looking promising. Even my piece of code was working properly. But  the betting houses started adding obstacles and I decided to stop the project. What remains is the experience with the written source code and, above all, the experience of verifying how the sportsbook websites work, which is not always fine. From this experience I’ve written a [comparison review]({{ site.baseurl }}{% post_url 2018-03-05-short-analysis-of-sportsbook-websites %}). 

On [GitHub](https://github.com/marcogalluzzi/surebets) you can see the software I built to produce a listing of sure bets that helps to decide on which website to bet. It’s a very simple program. It could be improved and it could have more functionalities but I didn’t continue developing it since I decided not to invest more time with the Sure Bets.

# My recommendation
Finally, I don’t recommend invest time in Sure Bets because:

* You can only earn as much as 5%. You can easily find matches that gives you around 2% and this can be enough for you, but for sure you need to invest a good amount of money to see some interesting incomes from that little percentage. In some very unusual cases, you can find very high percentages, like 24%, but be aware that the odds will change very fast.
* The odds can change. This happens because the betting houses adapt the odds to the number of bets being performed by the users. If an odd from a house changes before betting but after  betting on another house we could lose money.
* Some betting houses forbid further bets or limit the stake to a short amount if they detect abnormal bets. I suppose they are looking things like two bets on the same match or the bets stakes are always very specific, with quantities that include decimals.
* You don’t know if your bet will be accepted until you press the confirmation button. If not, it could mean that you lose money If you have already bet on another result of the same match in another house. This can happen because they forbid or limit your bets either because of your behavior (see above) or because for a match there are too much bets on a specific result.
* It takes time to move money between the betting houses. Since we have a limited amount of money for betting, we have to think carefully how to distribute it between the different betting houses and how to move it between them later. When winning or losing bets the cash balance will vary and we will probably need to move a surplus money from a betting house to another, and this movements can take some days because a withdrawal is not fast, although a deposit usually is.