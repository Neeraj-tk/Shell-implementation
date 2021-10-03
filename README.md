# Shell-implementation
## Basic stuff
Shell runs an infinite loop (which will only exit with the ‘exit’ command) and interactively process user commands. The shell should print a prompt that indicate the current working directory followed by ‘$’ character.
## Changing directory
Shell supports ‘cd’ command. The command ‘cd <directoryPath>’ should change its working directory to directoryPath and ‘cd ..’ should change the working directory to the parent directory.
## Incorrect command
An incorrect command format (which your shell is unable to process) will print an error message ‘Shell: Incorrect command’ (do not change this message). If your shell is able to execute the command, but the execution results in error messages generation, those error messages must be displayed to the terminal. An empty command should simply cause the shell to display the prompt again without any error messages.
## Signal handling
Shell will be able to handle signals generated from keyboard using ‘Ctrl + C’ and ‘Ctrl + Z’. When these signals are generated, shell will continue to work and the commands being executed by the shell should respond to these signals.
## Executing multiple commands
Shell supports multiple command execution for sequential execution as well as for parallel execution. The commands separated by ‘&&’ will be executed in parallel and the commands separated by ‘##’ will be executed sequentially.
## Output redirection
Shell will be able to redirect STDOUT for the commands using ‘>’ symbol. For example, ‘ls > info.out’ should write the output of ‘ls’ command to ‘info.out’ file instead of writing it on screen.
