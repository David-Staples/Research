# Research

Why use a multithreading environment in android? To keep from clogging UI thread
What is a deadlock? 2 threads waiting for each other to unlock methods they other needs
Explain Runnable interface and Thread class runnable interface allows a task to move itself onto a seperate thread
What are Executors? are used to run runables 
What is an ANR and what are the causes of ANR in android? App not Runnablle caused when UI thread is clogged
What is StrictMode? a developer tool that shows potential security performace problems
When should we use an AsyncTask? When we have a task that will take to much time away from main thread
Explain some problems with AsyncTask and their solutions? can only be used for tasks that take a few seconds, must return 
answer to UI thread, can lead to memory leaks
What is a Loader in android? manages streams and downloads data transfers from an out of app sources to a fragment 
When should we use a Loader? TO keep from clogging the UI thread and to monitor data source
what are the benefits of a Loader? active monitoring of data source and proper insert of data into UI que
What is a Handler? methods that handle messages on  thread
What is a Looper? Loopers loop message calls on a thread
What is an AsyncTaskLoader?  abstract loader that provides async task to be loaded
Briefly explain what a HandlerThread is thread that handles looper messages
