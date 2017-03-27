# 15 Puzzle Using OpenMP (High Performance Computing)
15 Puzzle Heuristic Approach using OpenMP (C Code)

# Introduction
The 15-puzzle (also called Gem Puzzle, Boss Puzzle, Game of Fifteen, Mystic Square and many others) is a sliding puzzle that consists of a frame of numbered square tiles in random order with one tile missing. The puzzle also exists in other sizes, particularly the smaller 8-puzzle. If the size is 3×3 tiles, the puzzle is called the 8-puzzle or 9-puzzle, and if 4×4 tiles, the puzzle is called the 15-puzzle or 16-puzzle named, respectively, for the number of tiles and the number of spaces. The object of the puzzle is to place the tiles in order by making sliding moves that use the empty space.

# To Compile 15 Puzzle Program (LineX)
    g++ _15Puzzle.c -std=c++11 -fopenmp -o _15Puzzle
    ./_puzzle
    
# Input and Output
 ------------------------------ ------------------------------
 -- Inputs and Output with Time
 ------------------------------ ------------------------------

 --15 Puzzle Input (Random):

    06  |  02  |  04  |  15  
  ------ ------ ------ ------ 
    03  |  12  |  07  |  14  
  ------ ------ ------ ------ 
    01  |  10  |  00  |  08  
  ------ ------ ------ ------ 
    05  |  09  |  13  |  11  

-- Total Nodes Generated: 1596
-- Elapsed time: 0.698 seconds.

------------------------------ ------------------------------

--15 Puzzle Input (Random):

    01  |  02  |  03  |  07  
  ------ ------ ------ ------ 
    00  |  09  |  06  |  11  
  ------ ------ ------ ------ 
    14  |  05  |  12  |  04  
  ------ ------ ------ ------ 
    10  |  13  |  15  |  08  

-- Total Nodes Generated: 7602
-- Elapsed time: 13.7 seconds.

------------------------------ ------------------------------

 --15 Puzzle Input (Random):

    05  |  01  |  03  |  04  
  ------ ------ ------ ------ 
    02  |  07  |  06  |  12  
  ------ ------ ------ ------ 
    13  |  00  |  11  |  14  
  ------ ------ ------ ------ 
    08  |  09  |  10  |  15  

-- Total Nodes Generated: 8475
-- Elapsed time: 18.9 seconds.

------------------------------ ------------------------------

--15 Puzzle Input (Random):

    10  |  05  |  03  |  04  
  ------ ------ ------ ------ 
    02  |  01  |  06  |  08  
  ------ ------ ------ ------ 
    13  |  09  |  11  |  12  
  ------ ------ ------ ------ 
    07  |  00  |  14  |  15  

-- Total Nodes Generated: 251
-- Elapsed time: 0.0225 seconds.

------------------------------ ------------------------------
    
# License
15-Puzzle is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

15-Puzzle is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
