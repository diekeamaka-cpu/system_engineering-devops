# 0x05-processes_and_signals

Bash scripts to explore Linux processes, signals, and process management techniques.

## Scripts

### 0. What Is My PID? (0-what-is-my-pid)
Displays the Process ID (PID) of the script itself.

### 1. List Your Processes (1-list_your_processes)
Shows a list of all currently running processes on the system:  
- Includes processes from all users  
- Includes processes without a TTY  
- Displays in a user-oriented, human-readable format  
- Shows process hierarchy visually

### 2. Show Your Bash PID (2-show_your_bash_pid)
Filters the process list to display only lines containing `bash`.  
- Helps identify the PID of your Bash shell  
- Uses `# shellcheck disable=SC2009` to suppress warnings

### 3. Show Your Bash PID Made Easy (3-show_your_bash_pid_made_easy)
Displays only the PID and process name of all processes containing `bash`.  
- Each output line follows the format: `PID process_name`  
- Does not use the `ps` command

### 4. To Infinity and Beyond (4-to_infinity_and_beyond)
Runs an infinite loop displaying:  
- Phrase: `To infinity and beyond`  
- Pauses 2 seconds between each iteration  
- Must be stopped manually with Ctrl+C

### 5. Don't Stop Me Now! (5-dont_stop_me_now)
Stops the `4-to_infinity_and_beyond` script programmatically using the `kill` command.  
- Finds the PID of the running script before sending the termination signal

### 6. Stop Me if You Can (6-stop_me_if_you_can)
Stops the `4-to_infinity_and_beyond` script using a method other than `kill` or `killall`.  
- Demonstrates alternative ways to control processes in Linux

### 7. Highlander (7-highlander)
Runs an infinite loop like `4-to_infinity_and_beyond` but handles the SIGTERM signal:  
- Displays `I am invincible!!!` instead of terminating when receiving SIGTERM  
- `67-stop_me_if_you_can` is a modified script to target `7-highlander` instead of `4-to_infinity_and_beyond`

### 8. Beheaded Process (8-beheaded_process)
Forcibly kills the `7-highlander` process using the SIGKILL signal (signal 9):  
- Demonstrates that SIGKILL cannot be ignored by processes