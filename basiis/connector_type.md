# Connector Type

```shell
graph LR

A --> B
C --- D
E --RUN!--- F
G ---|RUN!| H
I -.- J
K .-> L
M -."RUN(!".-> N
O ==RUN!==> P
Q --RUN!--> R --STOP!--> S

a --> b & c--> d
e & f --> g & h
```

```mermaid
graph LR

A --> B
C --- D
E --RUN!--- F
G ---|RUN!| H
I -.- J
K .-> L
M -."RUN(!".-> N
O ==RUN!==> P
Q --RUN!--> R --STOP!--> S

a --> b & c--> d
e & f --> g & h

```