# Perilous Paths

Perilous Paths is a tower defense game with an emphasis on dynamic enemy pathfinding. Enemies determine their routes dynamically using the A* algorithm and an evolving landscape of weighted tiles. Each tile has a starting weight determined by its type (road, grass, or water), and that weight increases each time an enemy is defeated near it. This design plays against the typical tower defense strategy of "death boxes" by allowing enemies to effectively be aware of particularly dangerous zones. The player can, however, block potential paths by building impassable structures.