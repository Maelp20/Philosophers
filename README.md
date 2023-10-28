# Philosophers
42 Project Philosophers

# Subject 
Simulation de salle à manger des philosophes :
    - Création d'un programme pour modéliser le comportement de philosophes autour d'une table partageant des fourchettes.
    - Chaque philosophe est un thread et peut mourir de faim.
    - Objectif : éviter la famine, avoir une bonne synchronisation sans data
    race entre les threads, et créer des logs pour chaque action.

# RUN / USAGE
at dir root, run ```make```

Usage is ```./philo nb_philo time_to_die time_to_eat time_to_sleep [optional_max_nb_time_to_eat]```