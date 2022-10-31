# Purpose of This Repo

This repository contains the starter code to launch in the SDC Planning course workspace. 

# Setup Instructions

- Terminal 1
```
1. su - student
// Will say permission denied, ignore and continue 
2. cd /opt/carla-simulator/
3. SDL_VIDEODRIVER=offscreen ./CarlaUE4.sh -opengl
```

- Terminal 2
```
4. git clone https://github.com/udacity/nd013-c5-planning-starter.git
5. cd nd013-c5-planning-starter/project
6 ./install-ubuntu.sh
7. cd starter_files/
9. cmake .
10. make
11. cd nd013-c5-planning-starter/project
12. ./run_main.sh
// This will silently fail 
13. ctrl + C to stop 
14. ./run_main.sh again
15. Go to desktop mode to see CARLA

// If error bind is already in use, or address already being used
ps -aux | grep carla
kill id
```

