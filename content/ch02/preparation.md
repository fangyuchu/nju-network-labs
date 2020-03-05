# Task 1: Preparation

There is an example of a switch without learning implemented in `switchyard/examples/exercises/learning_switch/myswitch.py`. Let's start with it.

1. Create a directory named `lab_2` in `switchyard`.
2. Copy `examples/exercises/learning_switch/switchtopo.py` to `lab_2/start_mininet.py`.
3. Make 3 copies of `examples/exercises/learning_switch/myswitch.py` to:
   1. `lab_2/myswitch_to.py`: Your learning switch with timeout based entry removal.
   2. `lab_2/myswitch_lru.py`: Your learning switch with LRU based entry removal.
   3. `lab_2/myswitch_traffic.py`: Your learning switch with traffic volume based entry removal.
4. Create your test files in `lab_2`.
   1. `lab_2/mytests_to.py`: Your test file of `lab_2/myswitch_to.py`.
   2. `lab_2/mytests_lru.py`: Your test file of `lab_2/myswitch_lru.py`.
   3. `lab_2/mytests_traffic.py`: Your test file of `lab_2/myswitch_traffic.py`.

And your project will look like

```
switchyard
  ├─docs/
  ├─.../
+ ├─lab_2
+ │ ├─myswitch_to.py
+ │ ├─myswitch_lru.py
+ │ ├─myswitch_traffic.py
+ │ ├─mytests_to.py
+ │ ├─mytests_lru.py
+ │ ├─mytests_traffic.py
+ │ └─start_mininet.py
  ├─.gitignore
  └─...
```

> [!WARNING]
> All of your modifications should be done on the files under your directory `lab_2`. We will check and compare the **git commits** to judge the originality of your work. So remember to commit every time you complete one small task.