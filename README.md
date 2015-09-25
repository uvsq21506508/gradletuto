# gradletuto
Un court tutoriel Gradle

## Première tâche
```
$ gradle tasks
...
$ gradle Hello
:Hello
Hello !

BUILD SUCCESSFUL

Total time: 0.991 secs
```

## Dépendances entre tâches
```
$ gradle world
:hello
Hello, :world
world !

BUILD SUCCESSFUL

Total time: 0.989 secs
```
