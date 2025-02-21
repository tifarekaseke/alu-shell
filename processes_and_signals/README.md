## 0-what-is-my-pid

This script displays its own Process ID (PID).

# 1-list_your_processes

This script displays a list of currently running processes, showing all users' processes, including those without a TTY, in a hierarchical format.

# 2-show_your_bash_pid

This script displays lines containing the word 'bash', allowing you to easily find the PID of your Bash processes

# 3-show_your_bash_pid_made_easy

This script displays the PID and process name of processes whose name contains the word 'bash'.

# 4-to_infinity_and_beyond

This script displays "To infinity and beyond" indefinitely, pausing for 2 seconds between each message

# 5-dont_stop_me_now

This script stops the `4-to_infinity_and_beyond` process using the `kill` command.

# 6-stop_me_if_you_can

This script stops the `4-to_infinity_and_beyond` process without using `kill` or `killall`.

##7-highlander
This script displays "To infinity and beyond" indefinitely and responds to a SIGTERM signal by printing "I am invincible!!!".

# 8-beheaded_process

This script kills the `7-highlander` process.

# 10-process_and_pid_file

This script creates a PID file at `/var/run/myscript.pid`, displays "To infinity and beyond" indefinitely, and handles various signals.

.
