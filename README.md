# PACMAN-AUTOMATION
Pacman search agent using depth-first search, breadth-first search, uniform cost search, and A* search algorithm for "4" types of mazes.

FILES IN THE PROJECT  
pacman.py         :The main file that runs Pacman games. This file describes a Pacman GameState type, which you use in this project.  
game.py           :The logic behind how the Pacman world works. This file describes several supporting types like AgentState, Agent, Direction, and Grid.  
Util.py           :Data structures in python  
SearchAgents.py   :Search Agents  
Search.py         :Search Algortithms  
graphicsDisplay.py :Graphics for Pacman  
graphicsUtils.py   :Support for Pacman graphics  
textDisplay.py     :ASCII graphics for Pacman  
ghostAgents.py     :Agents to control ghosts  
keyboardAgents.py  :Keyboard interfaces to control Pacman  
layout.py          :Code for reading layout files and storing their content    

RUNNING THIS PROJECT:    
Cd C:\Users\DELL\Desktop\AI\Pycharm Codes\search  
Python pacman.py –l/--layout  type of maze defined in one of files   
                                  -p/--pacman searchAgent defined searchAgent,py      
                                   -a                    Argument passed to the search agent above  
                                   – h                  list of arguments that can be passed to pacman.py  

Eg  
Cd C:\Users\DELL\Desktop\AI\Pycharm Codes\search  
python pacman.py--> run pacmn game      
python pacman.py --l testMaze –p GoWestAgent--> run pacman.py for test maze and agent is GoWestAgent(Reflex agent)    
python pacman.py --l tinyMaze –p GoWestAgent--> run pacman.py for tiny maze and search agent is GoWestAgent(Reflex agent                                                          python pacman.py -l tinyMaze -p SearchAgent --> run pacman.py for tiny maze and search agent is “SearchAgent” and pass     
                                              depth first search as argument(default argument as per code in SearchAgent class)  
python pacman.py -l MediumMaze -p SearchAgent--> run pacman.py for Medium maze and search agent is “SearchAgent” and    
                                                 pass depth first search as argument(default argument as per code in SearchAgent class)    
python pacman.py -l BigMaze -z .5 -p SearchAgent--> run pacman.py forBig  maze and search agent is “SearchAgent and pass   
                                                   depth first search as argument(default argument as per code in SearchAgent class)    
python pacman.py -l tinyMaze -p SearchAgent -a fn=bfs--> run pacman.py for tiny maze and search agent is “SearchAgent and   
                                                        pass breadth first search as argument to Search Agent    



