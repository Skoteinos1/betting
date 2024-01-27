# Risk Free Betting

![Football Stadium](https://github.com/Skoteinos1/betting/blob/main/football.jpg)

Everybody wants to play. Nobody wants to lose. There is a way to beat bookmakers in their own game... You have to be really good in math... and you need tool which will make all necessary calculations million times faster. 

OK. I am not going to upload this code here. There is no free lunch. If you want this code you will have to pay me or figure it out by yourself. But I can show you how it works when we meet in person.

Theory:<br>
Imagine you bet on coin toss. There are only 2 options Heads or Tails, 50:50. Fair odds are 2 for Heads and 2 for Tails. If you would bet 1000x you would end up pretty much with same amount of money you had at beginning. If Bookmakers want to make money, they will give you odds of 1.8 for Heads and 1.8 for Tails. Now if you play 1000x you are going to loose everything. This is very lucrative business which attracts competition. Now why would you bet with Bookmaker which gives you 1.8 oddds if you can bet next door with odds 1.9 or 1.95? Now imagine Rich guy comes in and bets 1 000 000 on Heads. So what will Bookmaker do to balance his books? He will change odds. 1.5 on Heads and 2.2 on Tails. And this is moment when you can make money. You can bet with one bookmaker on Heads with odds 1.95 and then bet with second bookmaker on Tails with odds 2.2. If you devide your money correctly, no matter if there is Heads or Tails you will always win.

Sport is not a coin toss and chances are not 50:50. Which means no one really knows what chances really are. One bookmaker thinks they are 30:70, second 33:67, and third 40:60. Add competition in the mix, imbalances in books, mistakes and cultural bias and suddenly you will find odds of 1.51 for Team A and 3.1 for team B. If you don't get it, with these odds you can make 7.1% of your money risk free, no matter who wins.

How my code works:
1. Scraps multiple websites.
2. Joins data in one big table.
3. Looks for odds which are too high.
4. Prints result.
5. I automated it. It run in background and also place bets.

On paper all is cool and dandy until you find out that Bookmakers have ways to screw you.
1. Coming up with an excuse and they just give you back your money instead of paying you money you won.
2. Limit your betting.
3. Ban you completely.
4. Misleading team names. You can bet on regular teams with one bookmaker and youth teams at another.
5. Some Bookmakers include Draw some others don't.
6. Sometimes there is Handicap for one team. They can't just win. They have to win with 2+ goals.
