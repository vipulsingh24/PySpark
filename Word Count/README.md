Make sure Hadoop is running, check it by 'jps' command.
If not, move to hadoop sbin directory or type start-all.sh

<ul>
<li>Move the word file to hdfs</li>
hadoop fs -put localfile /home/username/file/path/words.txt /hdfs/path
<li>Run the python code</li>
python word_count.py hdfs:////usr/words.txt
</ul>
