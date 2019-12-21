A simple, dumb time keeper script for auditing time spent doing tasks and making small notes.

Install:

    git clone https://github.com/maksimas-lajauskas/timekeeperscript.git  \
    && ~/.timekeeper && chmod 700 ~/.timekeeper/tk \
    && ~/.timekeeper/./tk init

Timekeeper usage:

    'init' to create 'tk' alias for timekeeper script
    'view' to view log (log autocreates by using any writing commant e.g. 'start')
    #action names and notes longer than one word need to be put in quotes ('single' or "double")
    'start [action name]' and 'stop [action name]' to mark actions in log
    'note [note text]' to annotate log (useful for sparse small notes when working on testing/research)

Dependencies (all core gnu/unix tools):

    #for 'view'
    less
    tac

    #for init
    grep
    tail
    bash (for .bashrc)

    #for writing to log and init
    echo

License:

    Timekeeper script provided 'as is', you may modify and you don't need to credit anyone, however:
        By using this script you agree that you use it at your own risk and accept all consequences arising from said use.
        That means you are liable for any kind of damages, death, injury, loss of work or profits, hostile AI takeover...
        ...and anything else that may be considered a consequence of using this script.


And yes, this script only writes timestamps to a text file. Have fun.
