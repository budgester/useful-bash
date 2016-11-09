# useful-bas

Kill all tasks from a grep..

ps -ef | grep [p]hp | awk '{print $2}' | xargs kill -9
