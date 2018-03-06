---
layout: post
title: Short analysis of sportsbook websites
---

Recently I’ve registered at different sportsbook websites to make some bets trying to earn money with the Sure Bets (I wrote [this article]({{ site.baseurl }}{% post_url 2018-03-05-experiencing-sure-bets %}) about it). I gave up with the idea when I realized that betting houses makes this task hard. However, I’ve experienced how these websites work, and they not perform always as good as one expects when dealing with companies allegedly earning a lot of money and even showing ads on TV. I want to share this experience with a short analysis of functionalities and UX of these websites.

# What am I analyzing?
With this article I want to give an overview of the functionalities of sportsbook websites and the user experience given by them. I will highlight those facts that deviate the websites from a correct operation or usability, or they stand out in a positive manner. Therefore, this document can be used as a guide for the same or other betting houses to improve their websites.

I will revise only the desktop version of the websites while accessing through the Chrome browser in a Windows 10 computer.

The following sportsbook websites, accessed from Spain, have been taken into account:

* Marca Apuestas: https://www.marcaapuestas.es
* Betfair: https://www.betfair.es
* Interwetten: https://www.interwetten.es
* William Hill: https://www.williamhill.es
* Bwin: https://www.bwin.es

I’ve chosen these betting houses because they appear in the bets-comparing website www.elcomparador.com, they are well known and they usually gather the most interesting odds.

There are a lot of different sports and types of betting but I’ve focused on: 

* Soccer, because it’s a sport that I understand well enough and it has only 3 possible outcomes
* and only in bets on the final result (1 X 2), and not other types like result at the match break, both teams score, etc.

# General functionalities
In this section I analyze some general functionalities of these websites.

## Navigation
In general, all the betting houses have a more or less comfortable and fast website.

* Marca Apuestas: This website stands out negatively in this part because of two facts. First, it’s the website with more loading delay and, second, the User area opens in a new window. There a few cases where opening a new browser window is reasonable, and accessing a part of the website like the User area is totally unnecessary and counter-productive for a comfortable user interaction. The problem is that the User area is a key area of the website that is accessed quite often, what means that the user has to deal with different windows frequently and this isn’t comfortable. 

## Login
This should be a simple and safe process for the user. 

* Marca Apuestas: After the login a quite annoying modal window appears that, for security reasons, shows the information about the last login access done. This could be improved:
1. This big modal is not need for such a so short datum.
2. I would replace the modal window with an alert box. This way the security information is still given to the user but without interrupting his/her activity.
3. The date and time format could be more clear and meaningful for the user. I would change “2018-02-26 00:16:05” into something like “Monday, February 26, 2018 at time 00:16:05”.
* William Hill: On the main page, when you click on the username input, the focus is lost if the window/program is changed and you go back to it later. This is a strange behavior and prevent the usage of programs like Keepass that automatize the introduction of username and password. If the first login fails you are redirected to a new page with the login form where this strange behavior doesn’t appear anymore.

## Information about payment methods
When choosing a betting house I think it’s important to know beforehand the payment methods provided, the fees applied and also the processing times. This lack of information for all the website visitors can lead to a loss of potential users from those that are undecided about what betting house to use.

* Interwetten: There isn’t a document where the payment methods are listed. Only after registering and trying your first deposit you will know the existing options. Furthermore, the information given about the applied fees is not visible enough, and in those cases where there is no fee a “No fees” message is missing, so you don’t know if they are going to charge you with a fee until the transaction ends.
* Betfair: Here this information is also missing. Or maybe it’s located in a lost page between the several questions and answers of the help center.

## Support
On a successful website experience we wouldn’t need to contact the support team. But in those cases we need to do it, wishing that they are only a few, we would like to be assisted quickly, in a friendly way and with a satisfactory answer. 

* Marca Apuestas: I want to underline the positive fact that support team can be easily contacted and their answers are good enough. Besides, they can be contacted 24 / 7 and by different means: chat, email, free telephone number and even by snail mail.
* Interwetten: They give very short answers, so the doubts are not always entirely resolved. It looks like they have a set of already written answers, and those are what they use to answer your doubts.

## Identity check
This is a process that all the betting houses do following the local regulations. However, I don’t think the law says in which moment this check should be done and this way the betting house just do it when the user is going to withdraw money, while you are free do deposits without any check.
In this process, besides your identity, they can also check your address and, when using bank transfers for withdrawing, that you are the owner of the bank account used. 
In all the betting houses this process has been more or less simple and it took more or less time. However, there was one house where this process lasted too much time. 

* Marca Apuestas: Is in this house where more documents are required and, on top of that, in a nonsense way. They ask you for a photo of all documents, what means having those documents in paper. As long they ask for your ID card it’s OK. But ¿what about the household bills? We receive those bills less and less in paper because we are able to download them from the cloud so ¿why I cannot send a PDF directly? I went as far as to print a bill and make a photo in order to accomplish with their requirements.

## Access from abroad
Most of the betting houses don’t allow you to access an account created in the Spain website from another country, I suppose for legal reasons. Although this is reasonable, the user should be warned about it in an understandable way and not showing a message like “Invalid IP address”.

* Marca Apuestas: It detects the country from which the user access but the error message shown isn’t easy to understand.
* Betfair: It detects the country from which the user access and the error message shown is easy to understand.
* Interwetten: It doesn’t detect the country from which the user access.
* William Hill: It doesn’t detect the country from which the user access.
* Bwin: It detects the country from which the user access but the error message shown isn’t easy to understand.

# Bets area

## Directory
In a sportsbook website you will never be short of options for betting. These websites includes more and more leagues or tournaments from around the world and from an increasing amount of sports. Among so much information sometimes is difficult to find the specific sport and/or competition you are interested in. Therefore is important to offer an easy-to-navigate directory.

* Marca Apuestas: In just 2 clicks and with some scrolling is possible to locate the desired tournament or league.
* Betfair: It’s structured in such a way that the most common options are easy to locate, saving some scrolling. The bad thing is that, when something less common is searched, a good bunch of clicks is required. Some training is needed to fast navigate among so many options.
* Interwetten: In just 2 clicks and with some scrolling is possible to locate the desired tournament or league.
* William Hill: 3 clicks and some scrolling is needed to locate a tournament or league.
* Bwin: It’s also structured in such a way that the most common options are shown first, so more clicks are required when searching for a very specific competition. However, is easier to navigate in this directory than in Betfair one.

## Site search
A little but important part of the Bets area is the site search form. It gains importance especially when all websites are invaded by matches from all sports and the navigation through a directory isn’t very easy. The search form should be easy to find inside the web page, work fast and return the interesting information. With “interesting information” I mean: matches and their odds for first team wins, tie and second team wins. If there are more types of betting, like “Number of goals” or “Number of corners”, this information should appear in a second step, selecting a match or at the end of the main listing, in order to avoid returning too many results that are usually not interesting to the user.

* Marca Apuestas: The search input is easy to locate inside the web page, works fast and returns the expected information.
* Betfair: It doesn’t have site search, or I couldn’t be able to find it. This appears so strange to me that I don’t know if there is some hidden commercial strategy behind that.
* Interwetten: The location of the search input could be better. It works fast and returns the expected results. It even shows valid results while typing.
* William Hill: The search input is easy to locate inside the web page and works fast. The drawback is that the results returned are not the expected ones. It returns a huge paginated listing where first entries are related to different types of betting what makes, in practice, this search engine useless.
* Bwin: The search input is easy to locate inside the web page, works fast and returns the expected information. It even shows valid results while typing.

## Odds
The analyzed betting houses usually gather the most interesting odds for a specific result of a match. However, some of them stand out somehow.

* Interwetten: It usually has the higher odds for the most probable result. I suppose this is its strategy to attract more users.
* Betfair: It’s the betting house with the best odds in general. This is, is the house that, according to my calculations, retains the lowest percentage on the money invested on bets. It isn’t difficult to find that it has the best odds for the two least probable results of a match.

## Betting
Once the desired match is found, the user should be able to bet on a specific result easily and quickly. In particular, writing the amount of money to bet should be independent of the use of a comma or a point character and expected gains should be visible enough. Additionally, the user should be able to, optionally, confirm the bet as a second step after its validation. Finally, there’s no need to say that the expected gains should be correctly calculated.

* Marca Apuestas: Both the point and the comma characters are allowed for decimals. Calculations are not always correct, since once I found a case where an odd of 2.38 was not giving the expected gains. I came to the conclusion that the actual odd was 2.375. This kind of errors are quite serious since they can affect the user money.
* Betfair: It only allows the point character for decimal values which is annoying because in Spain the comma character is used and you need to remember to use a different character. A confirmation button can be added after validating the bet.
* Interwetten: Both the point and the comma characters are allowed for decimals. There is no option for confirming the bet after the validation.
* William Hill: Both the point and the comma characters are allowed for decimals. There is no option for confirming the bet after the validation.
* Bwin: Both the point and the comma characters are allowed for decimals. A confirmation button exists after the bet validation.

## Bets tracking
Another useful functionality for the user is to make the open bets easy to track and being notified when they close. The former is usually implemented with a listing of open bets. Besides, some houses implement an optional notification system that informs when bets close and what was the result. Finally, I want to mention that most betting houses add, in the open bets listing, the option to close a bet getting back almost all invested money, except for a small fee.

* Marca Apuestas: There is a shorter listing with the open bets in the Bets area and then a complete listing, including closed bets, in another window where the User area is shown. The information in this second listing is complete. There isn’t an option to receive notifications.
* Betfair: There is a shorter listing with the open bets in the Bets area and then a complete listing, including closed bets, in the User area. The information in this second listing is not complete because some data, like the date and the match result, are missing. 
* Interwetten: There is a shorter listing with the open bets in the Bets area and then a complete listing, including closed bets, in the User area. A negative issue is that only the bets done in last 3 months can be visualized. There isn’t an option to receive notifications.
* William Hill: There is a shorter listing with the open bets in the Bets area and then a complete listing, including closed bets, in the User area. This second listing doesn’t show the complete information, however a click on the match sends you to a second page where the complete information is shown. There isn’t an option to receive notifications.
* Bwin: There is a shorter listing with the open bets in the Bets area and then a complete listing, including closed bets, in the User area. This second listing doesn’t show the complete information, however a click on the match sends you to a second page where the complete information is shown. There is an option to receive notifications by email (free service) or SMS (paid service).

# User area
In this area of the website, the user can revise not only his/her personal information and other preferences but also everything about the money deposited or withdrawn, the performed bets, promotional bonuses, etc. This area is normally called “My account”.

## Balance
On a web page called “Summary statement” or “Account statement” the current cash balance is shown. Obviously, the balance should be correctly computed and it should be equal to the balance shown, in all websites, in the page header as a quick reminder for users.

* Interwetten: I’ve experienced a difference of one euro cent between the balance shown in this page and that shown in the page header. It’s a serious issue in my opinion.

## Deposits
Deposits are usually fast transactions and they can have a fee depending on the payment method. Most common payment methods, and that usually have no fees, are Credit/debit card, Paypal and bank transfer. Other methods less known but allowed by betting houses includes Skrill, Paysafecard, Neteller, Trustly, Entropay and Klarna (previously Sofort).

* Interwetten: In this website even the most common payment methods like Credit/debit card and Paypal have a fee. The only common method without a fee is the bank transfer, but of course, you have to wait between 2 and 10 days to see your balance increased. The not very well know payment method that I could successfully use, which is fast and without fees, is called Klarna (previously know as Sofort) by which a cash transfer is performed through your bank account but without waiting days. In order to use this last method you should have an account from a bank supported by Klarna.

## Withdrawals
While deposits are fast, withdrawals are slower and require passing through a check of your identity, address and, when it’s necessary, of the ownership of a bank account. The payment methods are usually the same as those supported in deposits. It should be taken into account, however, that betting houses usually authorize withdrawals only with payments methods previously used for deposits.

* Marca Apuestas: I’ve to tell that they didn’t allow withdrawals for an amount including decimal values until very recently. According to the support team they allowed such amounts only with withdrawals done through a bank account, but I couldn’t test it even after having sent the required documentation and having received their confirmation. Without being informed, one day I could verify that they were accepting amounts of money including decimals through Paypal.

# Final appraisal
I would like to appraise all the betting houses analyzed to summarize what I could experience in a daily use. Please see this as a personal appraisal.
In order of preference, the websites and their appraisals are:

1. Sportsbook website I would regularly use: Bwin. It’s the website where everything worked as expected. It’s fast and well designed. I haven’t practically had any complaint.
2. Sportsbook website I would occasionally use: Betfair and William Hill. I’ve had a few but important complaints about this websites. Besides, the design of the William Hill website could be improved. In general, I’ve to say they work fairly well.
3. Sportsbook website I wouldn’t like to use: Interwetten and Marca Apuestas. Definitively, these websites are not appealing and/or not very usable. They even have some error and/or they are slow. Deposits and withdrawals have fees not clearly shown and/or they take quite a while.
