# ucla-soccer

Application for a student analyst position at UCLA soccer(Bryan Mui)

Idea: Interactive dashboard(like stiddle compare date) that allows comparison of various metrics 

Variables that Coach is interested in:    
  + Box entries  
    - How many instances did the attack allow entering the box
    - *metric not really recorded*
  + Touches in the box
    - How many touches were allowed in the box
    - *metric not really recorded*, *paired with touches in the penalty area*
  + Positional attacks
    - How many possessions lead to a shot 
    - *metric recorded*
  + Turnover in own half  
    - Losing the ball in our team's own half
    - *need a separate idea for this* 
  + Crosses and area  
    - Which area were the crosses and how accurate were they 
    - *Crosses recorded, not area*
    
Spec: 
  + Report comparing the data of 2022 season to 2024. 
  + Should compare 4 ways - 2022 home vs opp, 2024 home vs opp, and 2022 home vs 2024 home, and 2022 away vs 2024 away
  + Vars: 
    - Box entries(Same as penalty area entries)
      + Runs
      + Crosses
    - Touches in the box(Same as touches in the penalty box)
    - Positional Attacks / (Attacks w/ shot)
    - Crosses / (Accurate crosses)
  + Radial Chart 
  + Parallel Coordinates Plot
    
