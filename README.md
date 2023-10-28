# Philosophers
42 Paris School Project Philosophers

# Subject 
Dining Philosophers Simulation:

- Development of a program to model the behavior of philosophers sitting around a table, sharing forks.

- Each philosopher is a thread and can starve to death.

- Objective: Prevent starvation, achieve proper synchronization without data races between the threads, and generate logs for each action.

# RUN / USAGE
at dir root, run ```make```

Usage is ```./philo <arg1> <arg2> <arg3> <arg4> [arg5]```
- arg1 = number_of_philosophers
- arg2 = time_to_die
- arg3 = time_to_eat
- arg4 = time_to_sleep
- arg5 = (optional) number_of_times_each_philosopher_must_eat (times in ms)

## Case examples

```./philo 2 800 200 200``` no one dies

```./philo 5 800 200 200``` no one dies

```./philo 5 0 200 200```   a philo dies at 0ms

```./philo 4 410 200 200``` no one dies

```./philo 2 600 200 800``` a philo dies at 600ms

```./philo 8 800 400 400``` a philo dies at 800ms

```./philo 8 820 400 400``` no one dies

```./philo 50 800 200 200``` no one dies