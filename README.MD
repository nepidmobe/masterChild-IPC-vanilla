# communicate between master and child module.
### will use built in module of nodejs calle child_process module.
### this module prvide ability to spawn child processes.
### for that we use fork() method. fork method takes path of module which will execute in separate process.
### fork method returns instance of child process object.child process inp event emitter which allow parent process to register event emitter.
### child process obj has communication channel called IPC to communcate message to and fro betwn parent-child.
### each process has it's own memory and own v8 engines.
### because of allocation of their own resources it is not recommended to spawn many child process.


![Screen Shot 2022-04-27 at 13 06 15](https://user-images.githubusercontent.com/103139099/165464726-80f9a6df-60b7-4c58-bb8a-e49abeebbb22.jpg)

