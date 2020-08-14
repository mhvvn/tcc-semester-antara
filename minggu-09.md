## Docker swarm 


Docker Swarm adalah Salah satu product nya docker untuk dapat mendeploy container pada multihost.
Multihost disini adalah di banyak server. Misalnya kita mempunyai 2 server, misalnya server A dan server B. Masing - masing server akan dilakukan instalasi docker, dan masing - masing docker mempunyai 1 container yang sedang berjalan. Bagaimana caranya agar container yang terdapat pada server A dan melakukan komunikasi dengan container yang ada pada server B, sedangkan jaringan yang terdapat pada server berbeda dengan jaringan yang terdapat di dalam masing - masing container. Dengan menggunakan docker swarm, dengan menggunakan docker swarm maka docker yang yang terdapat di dalam beberapa host dapat kita lakukan cluster sehingga seakan - akan docker tersebut terdapat pada 1 host. 

Dengan menggunakan docker swarm, kita bebas menetukan container tersebut ingin di deploy ke host yang diinginkan.