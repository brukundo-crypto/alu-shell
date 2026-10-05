# Processes and Signals

Bash scripts covering PIDs, processes, signals and process management.

- 0-what-is-my-pid: displays its own PID.
- 1-list_your_processes: displays a list of currently running processes with hierarchy.
- 2-show_your_bash_pid: displays lines containing the word bash from the process list.
- 3-show_your_bash_pid_made_easy: displays the PID and name of processes containing bash.
- 4-to_infinity_and_beyond: displays "To infinity and beyond" indefinitely.
- 5-dont_stop_me_now: stops the 4-to_infinity_and_beyond process using kill.
- 6-stop_me_if_you_can: stops the 4-to_infinity_and_beyond process without kill or killall.
- 7-highlander: loops indefinitely and displays "I am invincible!!!" on SIGTERM.
- 67-stop_me_if_you_can: stops the 7-highlander process without kill or killall.
- 8-beheaded_process: kills the 7-highlander process.
- 10-process_and_pid_file: manages a PID file and handles SIGTERM, SIGINT and SIGQUIT.
- manage_my_process: indefinitely writes "I am alive!" to /tmp/my_process.
- 11-manage_my_process: init script to start, stop and restart manage_my_process.
