# qit

## A To Do app for the command line

Manage your To Do list from the command line

## Concept

- To add a task, any one of the following

```bash
qit "task 1"
```

```bash
qit a|add "task 1"
```

- To remove a task

```bash
qit rm|remove "task 1"
```

- To modify configuration

```bash
qit config --file "~/qit/qit.yaml"
qit config --repo "~/qit"
qit config --on-save "git add -A && git commit -m <message>"
qit config --alias "save | commit"
```

- To save (i.e. commit to a repository)

```
qit save -m "<message>"
```

- To serve a GUI

```
qit serve
```
