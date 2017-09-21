# NBA_Hackathon_ApplicationQuestions


## 1) REQUIRED: After the Golden State Warriors acquired former MVP Kevin Durant in 2016, some NBA fans speculated that the Warriors would not lose consecutive games at any point of the season.*

### a) If you wanted to determine the probability that this prediction would be true (i.e., that the Warriors would never lose consecutive games at any point during an 82-game season), what is one approach (or a few approaches) you may use to solve the problem? What answer do you get? Exact answers are of course welcome, but approaches that lead to approximations (and those approximations) are fine, too (please specify the precision of your estimate). Assume the Warriors have an 80% chance of winning each individual game.

### b) So, would you have agreed with that hypothesis?

### c) Finally, at least what % of a team's games would a team need to be expected to win (assuming that win probability stays constant from game to game) for there to be a greater than 50% chance that the team never suffers consecutive losses at any point in the season?


## 2) BONUS: For an upcoming presentation, you are asked to predict total gate revenue for the entire NBA Playoffs. You should use the win probabilities data provided in this file and the Hypothetical Playoff Gate Data tab in this file to answer part b of the question.


### a) As a primer, let’s think about an individual series. Team East1 plays Team East8 in the First Round. Suppose the probability that East1 defeats East8 at home (8 @ 1) is p_H, and the probability that East1 defeats East8 on the road (1 @ 8) is p_A. In terms of p_H and p_A, what is the probability that the series goes exactly N games for N in {4,5,6,7}, regardless of winner? Please give closed-form analytical solutions.

## b) Now suppose that the regular season has just concluded and the NBA playoff picture is set. Team Finance has forecasted gate revenue per game for every team in each possible round – these per-game forecasts for each (team, round) combination are given in the Hypothetical Playoff Gate Data tab in the attached Excel file. Further suppose you are given win_probabilities.csv, which describes the probability that a given team defeats any other team, either at home or on the road. (The format of the probabilities in each row may not be standard.) Note that there is no re-seeding in the NBA Playoffs and that each series follows a 2-2-1-1-1 format. If equal seeds make the Finals, suppose the West team has home court advantage; otherwise, suppose the better seed has home court. Build a playoff simulator that tracks gate revenue using this data. (Assume each game is independent.) 

## c) How do you propose to present a solution to the team? You want to ensure the team understands that there is a relatively wide distribution of possible outcomes. What is the solution?

## d) What is the probability that West1 meets East1 in the Finals? What is the expected total Playoffs gate revenue if West1 meets East1 in the Finals? What if West1 does not meet East1 in the Finals? How does your solution change if – independent of all other series – East5 defeats East4 in the First Round? You don’t know how many games the series went; you just know the outcome.

## 3) BONUS: You should use the data provided in this LINK. Suppose you are given a sample data set of 1,000 individuals that includes their last twelve months’ worth of total revenue spend, games watched, income, fan satisfaction (self-reported, 1 to 7, 7 is best), logged complaints and number of years in our database at present (in the Training Data tab). You intend to predict spend metrics for another data set of 100 people whose revenue spend is unknown (in the Prediction tab). Construct a model for 1) A projected twelve-month total revenue sepnd number 2) The probability that total revenue spend is at least 250. Run each of the accounts in the prediction tab through both models and fill in your results in 1) the TotRevSpend column on the Prediction tab and in 2) the LikelihoodOver250 column on the Prediction tab. Please include a clearly labeled updated Excel file, any code, and any additional materials you used to generate your answer in a zip folder.

