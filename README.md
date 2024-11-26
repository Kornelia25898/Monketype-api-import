
[Configuration](#configuration)
## My public Monkeytype [profile](https://monkeytype.com/profile/zp14)


        
## Typing History Stats (Last Updated: 26/11/2024 18:15)

| **Key Stats**               | **Overall Stats**       | **Last 10 Tests Stats**  |
|--------------------------|-------------------------|--------------------------|
| **Total Entries**        | 101           | 10                       |
| **Average WPM**          | 20.42           | 23.66    |
| **Average Accuracy**     | 88.37%          | 91.24%   |
| **Max WPM**              | 35.98               | 27.59        |
| **Min WPM**              | 2.4               | 20.6                        |
| **Total Duration**       | 01:29:00        | 00:10:00                        |


---

### Last 10 results

| | WPM | Accuracy | Consistency | Mode | Date |
| --- | --- | -------- | ----------- | ---- | --------- |
| 1 | 25.4 | 89.31 | 59.37 | time 60 | 26-11-2024 16:22:51 |
| 2 | 23.6 | 91.84 | 50.43 | time 60 | 26-11-2024 16:21:26 |
| 3 | 21.0 | 82.93 | 53.85 | time 60 | 26-11-2024 16:20:21 |
| 4 | 23.59 | 86.71 | 49.25 | time 60 | 26-11-2024 16:19:05 |
| 5 | 21.2 | 87.67 | 56.7 | time 60 | 26-11-2024 16:18:01 |
| 6 | 25.59 | 92.81 | 59.89 | time 60 | 26-11-2024 16:16:16 |
| 7 | 27.0 | 96.58 | 52.4 | time 60 | 26-11-2024 16:15:08 |
| 8 | 27.59 | 97.26 | 54.81 | time 60 | 26-11-2024 16:14:02 |
| 9 | 20.6 | 90.7 | 44.64 | time 60 | 26-11-2024 16:12:57 |
| 10 | 21.0 | 96.61 | 40.92 | time 60 | 26-11-2024 16:11:50 |


 --- 

### Top 10 results

| | WPM | Accuracy | Consistency | Mode | Date |
| --- | --- | -------- | ----------- | ---- | --------- |
| 1 | 35.98 | 100.0 | 52.93 | time 30 | 01-07-2024 11:54:46 |
| 2 | 32.8 | 92.55 | 58.23 | time 30 | 02-07-2024 07:20:14 |
| 3 | 32.79 | 100.0 | 61.15 | time 30 | 25-04-2024 19:42:56 |
| 4 | 32.38 | 96.55 | 57.01 | time 30 | 01-07-2024 11:57:07 |
| 5 | 30.78 | 95.51 | 61.6 | time 30 | 03-07-2024 10:15:24 |
| 6 | 29.99 | 88.64 | 64.87 | time 30 | 03-07-2024 10:12:37 |
| 7 | 29.0 | 96.25 | 57.46 | time 60 | 12-07-2024 16:14:10 |
| 8 | 27.6 | 92.07 | 55.31 | time 60 | 25-11-2024 16:24:40 |
| 9 | 27.59 | 94.77 | 53.98 | time 60 | 12-07-2024 15:59:37 |
| 10 | 27.59 | 97.26 | 54.81 | time 60 | 26-11-2024 16:14:02 |


 --- 

### Avg data for latest 10 dates

| | Date | Tests | WPM | Acuracy | Consistency |
| --- | --- | -------- | ----------- | ---- | --------- |
| 1 | 2024-11-26 | 10 | 23.66 | 91.24 | 52.23 |
| 2 | 2024-11-25 | 11 | 24.14 | 90.43 | 50.78 |
| 3 | 2024-07-16 | 19 | 22.05 | 87.67 | 54.07 |
| 4 | 2024-07-12 | 15 | 21.8 | 90.4 | 50.77 |
| 5 | 2024-07-11 | 21 | 18.24 | 85.37 | 48.53 |
| 6 | 2024-07-09 | 5 | 12.68 | 80.01 | 41.04 |
| 7 | 2024-07-08 | 2 | 16.59 | 88.4 | 36.13 |
| 8 | 2024-07-05 | 2 | 9.4 | 81.81 | 30.23 |
| 9 | 2024-07-04 | 7 | 8.06 | 90.07 | 15.3 |
| 10 | 2024-07-03 | 4 | 26.19 | 88.92 | 56.14 |


 --- 

### Avg data for top 10 dates (minimum 7 tests)

| | Date | Tests | WPM | Acuracy | Consistency |
| --- | --- | -------- | ----------- | ---- | --------- |
| 1 | 2024-11-25 | 11 | 24.14 | 90.43 | 50.78 |
| 2 | 2024-11-26 | 10 | 23.66 | 91.24 | 52.23 |
| 3 | 2024-07-16 | 19 | 22.05 | 87.67 | 54.07 |
| 4 | 2024-07-12 | 15 | 21.8 | 90.4 | 50.77 |
| 5 | 2024-07-11 | 21 | 18.24 | 85.37 | 48.53 |


 --- 


        
![speed trend](typing_speed_trend.png)
![counted chart](count_tests.png)
# Configuration

1. **Get API Key from account settings -> ape keys -> generate new key -> check active button next to apekey's name**
2. **Add generated api key to .env file variable apikey**
3. **Install modules** `pip install -r req.txt`
3. **(If you've got less than 1000 tests completed) Run get_data_max_1000.py script that will load data from [Monkeytype](https://monkeytype.com/) and insert into sqllite3 db history.db (this wont be stored on your GitHub)**
4. **Error logs will be stored into logfile.log, and import status will be stored into import_status.log**
5. **stats.py script will get data from db and push them into GitHub account**
6. **You can use API call via ApeKey 30 times per day, so after you reach this limit you wont get any answear and in logfile you will see *Problem with inserting data 0* row**
7. **incremental_import.py will check for the last result time in db and download just those tests that are younger than that. It will also update automatically into GitHub account unless you comment last 2 line of code.**

# UPDATE for 1000+ tests
    
**As monkeytype API enables just 1000 rows to be downloaded via API call, for proper inintial insertion to db tests where there are more than 1000 on your profile
you should export csv file from [Monkeytype account](https://monkeytype.com/account) (over results at the bottom of the site)
and put this csv file into project folder (or set proper path to this file into variable csv_file), then run inintial_csv_read.py script.**
    