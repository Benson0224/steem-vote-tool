# steem-vote-tool

### Requirements

- python3.7+ installed

- init the virtual environment
    ```
    $python3 -m venv venv
    
    $source venv/bin/activate
    
    $pip install -r requirements.txt 
    ```
    
### Usage
#### step 1: 
（1）Paste the url of the post to the corresponding file

（2）Configure your posting key and username in the steem.yaml file

（3）Configure the weight of the corresponding level post

#### step 2: vote for posts
```
$ python vote.py
Vote for general posts...
[1]   [FAIL] [Voter Exclude] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-23-december-2020-or-cricket-match-after-a-long-time
[2]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/betterlife-or-or-the-diary-game-season-3-monday-16-11-2020-steemit-me-and-my-job
[3]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/the-diary-game-19-11-2020-a-short-day
[4]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@dabeerahmed/the-diary-game-or-28-november-2020-or-rainy-night
[5]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/the-diary-game-thursday-24-09-2020
[6]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/betterlife-or-the-diary-game-season-3-thursday-12-11-2020-busy-life-and-hardwork
[7]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/the-diary-game-season-3-friday-02-10-2020-friday-with-steemit
[8]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diaru-game-or-16-n0vember-2020-or-psl-craze-and-uefa-nations-league-or-100-power-up
[9]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@hasansid/compilation-of-achievement-tasks-by-hasansid-or-or-completed-till-task-4
[10]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@mato445/steemit-pakistan-weekly-engagement-topic-contest-week-4-or-how-i-will-use-the-trx-given-to-me-or-by-mato445-100-power-up
[11]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-27-november-20-or-a-perfect-day
[12]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@hassanabid/betterlife-the-diary-game-data-analytics-and-coffe-night
[13]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/let-s-power-up-steemit-pakistan-or-or-set-your-posts-to-100-power-up-or-or-earn-steem-and-tron-trx
[14]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-21-december-2020-or-stop-advertising-on-walls-or-100-power-up
[15]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-17-november-20-or-psl-final
[16]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@farhanali/the-diary-game-20-12-2020-or-or-sunday-activities
[17]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@janemorane/steemit-pakistan-beauty-of-your-area-contest-share-2-beautiful-pics-with-details-in-your-area-or-my-entry


Vote for medium posts...
[1]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@dabeerahmed/poloniex-exchange-or-part-i
[2]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/the-diary-game-12-11-2020-better-day
[3]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/the-diary-game-23-9-2020-my-friends-ate-fast-food-and-i-could-only-watch-them-eat-100-power-up
[4]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@faisee/betterlife-the-diary-game-a-simple-day-19-11-20
[5]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/the-diary-game-21-9-2020-health-is-wealth
[6]   [FAIL] [Voter Exclude] https://steemit.com/hive-136998/@steemit-pak/steemit-pakistan-ranked-9-in-trending-communities-special-thanks-to-steemit-team-100-powerup
[7]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/the-diary-game-1-10-2020-happy-october
[8]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@hasansid/betterlife-the-diary-game-i-am-back-12-11-20
[9]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@vvarishayy/daily-diary-game-or-orientation-day-at-university-or-october-27-2020
[10]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@hassanabid/betterlife-the-diary-game-season-3-exam-day-and-bbq-night-9-10-20-powerup-100
[11]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@dasuni/the-contest-or-your-hopes-for-2021-or-by-dasuni
[12]  [FAIL] [Voter Exclude] https://steemit.com/hive-136998/@ayeshagul/the-diary-game-25-12-2020-or-shopping-day
[13]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@harisbutt/the-diary-game-or-saturday-03-oct-2020
[14]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/the-diary-game-wednesday-23-09-2020-honesty-is-the-best-policy
[15]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@dabeerahmed/the-dairy-game-or-4-oct-2020-or-a-good-day
[16]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@dabeerahmed/the-dairy-game-or-9-october-2020-or-my-brother-s-wedding


Vote for general posts...
[1]   [FAIL] [Voter Exclude] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-23-december-2020-or-cricket-match-after-a-long-time
[2]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/betterlife-or-or-the-diary-game-season-3-monday-16-11-2020-steemit-me-and-my-job
[3]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/the-diary-game-19-11-2020-a-short-day
[4]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@dabeerahmed/the-diary-game-or-28-november-2020-or-rainy-night
[5]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/the-diary-game-thursday-24-09-2020
[6]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/betterlife-or-the-diary-game-season-3-thursday-12-11-2020-busy-life-and-hardwork
[7]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@rashid001/the-diary-game-season-3-friday-02-10-2020-friday-with-steemit
[8]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diaru-game-or-16-n0vember-2020-or-psl-craze-and-uefa-nations-league-or-100-power-up
[9]   [FAIL] [Time Expired] https://steemit.com/hive-136998/@hasansid/compilation-of-achievement-tasks-by-hasansid-or-or-completed-till-task-4
[10]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@mato445/steemit-pakistan-weekly-engagement-topic-contest-week-4-or-how-i-will-use-the-trx-given-to-me-or-by-mato445-100-power-up
[11]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-27-november-20-or-a-perfect-day
[12]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@hassanabid/betterlife-the-diary-game-data-analytics-and-coffe-night
[13]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@haidermehdi/let-s-power-up-steemit-pakistan-or-or-set-your-posts-to-100-power-up-or-or-earn-steem-and-tron-trx
[14]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-21-december-2020-or-stop-advertising-on-walls-or-100-power-up
[15]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@moohsin/the-diary-game-or-17-november-20-or-psl-final
[16]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@farhanali/the-diary-game-20-12-2020-or-or-sunday-activities
[17]  [FAIL] [Time Expired] https://steemit.com/hive-136998/@janemorane/steemit-pakistan-beauty-of-your-area-contest-share-2-beautiful-pics-with-details-in-your-area-or-my-entry
```
### Fail reason
- Voter Exclude：Repeat voting
- Time Expired：Post time is more than 7 days
- Vote Failed： Voting operation failed
