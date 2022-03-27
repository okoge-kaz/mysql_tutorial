O'REILY 初めてのSQL 第3版

## MySQL の起動

1. `brew services list` : 起動しているものの一覧を表示する。
2. `brew services start mysql` : MySQLを起動する。


3. `mysql -u root-p` : MySQLのログイン画面を表示する

```
[sudo] brew services [list] (--json):
    List information about all managed services for the current user (or root).

[sudo] brew services info (formula|--all|--json):
    List all managed services for the current user (or root).

[sudo] brew services run (formula|--all):
    Run the service formula without registering to launch at login (or boot).

[sudo] brew services start (formula|--all):
    Start the service formula immediately and register it to launch at login
(or boot).

[sudo] brew services stop (formula|--all):
    Stop the service formula immediately and unregister it from launching at
login (or boot).

[sudo] brew services kill (formula|--all):
    Stop the service formula immediately but keep it registered to launch at
login (or boot).

[sudo] brew services restart (formula|--all):
    Stop (if necessary) and start the service formula immediately and register
it to launch at login (or boot).

[sudo] brew services cleanup:
    Remove all unused services.

      --file                       Use the plist file from this location to
                                   start or run the service.
      --all                        Run subcommand on all services.
      --json                       Output as JSON.
  -d, --debug                      Display any debugging information.
  -q, --quiet                      Make some output more quiet.
  -v, --verbose                    Make some output more verbose.
  -h, --help                       Show this message.
```