# Minimum Spanning Trees

Institution: Instituto Superior Técnico - Universidade de Lisboa

Course: Computer Science and Engineering (LEIC)

Academic year: 2016-2017

Authors: Francisco Barros & Rafael Ribeiro

Subject: Analysis and Synthesis of Algorithms (2nd year, 2nd semester, 2nd project)

Project details:

	* Objective: Construct the cheapest possible grid that connects N cities using both roads and airports
	* Implentation in: C++  
	*
	* Solution achieved with: Kruskal Algorithm
	* Time complexity: O(E log V)
	*
	* Compile using linux terminal: $ g++ -o3 -ansi -Wall -o projectSolution projectSolution.cpp
	* Execute using linux terminal: $ projectSolution
	*
	* The input consists of:
	* - int:k, is the number of cities to connect on the network.
	* - int:ma, is the maximum number of airports the network allows.
	* - int:mr, is the maximum number of roads the network allows.
	* - int:a, int:b are both identifiers representing two different cities in the network.
	* - int:c represents the cost of building an airport on city a or a road between a and b.
	*
	* The output may be one of the following:
	* - "Insuficiente" (Insufficient): Should the given input not allow the connection of all the cities, because there are missing roads or airports;
	* - A line expressing the total cost and another line with the number of airports and roads that were used to create the minimum spanning tree.

