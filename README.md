# Breadth-First-Search-AI-01

Variables workingCandidate, openList, closedList
Set workingCandidate = StartSolution
Test (working candidate)
While (goal not reached AND Openlist not empty) Do
If (working candidate is not infeasible)
Generate all 1-step offspring and add to openList
Move working candidate to closedList
Move last item in openList into working candidate
Test (working candidate)
