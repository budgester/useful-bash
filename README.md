# useful-bash

Kill all tasks from a grep..

ps -ef | grep [p]hp | awk '{print $2}' | xargs kill -9

grep -E "Received Input - 811 " babylon-ussd.2016-11-15.log | awk  '{print $12}' | sort |uniq -c | wc -l
