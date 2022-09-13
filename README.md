1. Dataset.zip (our dataset) that we upload is fetched from:

https://lopez-ibanez.eu/tsptw-instances
https://homepages.dcc.ufmg.br/~rfsilva/tsptw/

We unzip the dataset.zip. We then see many files .txt. They are instances. The format of the instances is as follows:
Number of nodes (including the depot).
Distance matrix. The first row is the distance from the depot to the other nodes. The first column is the distance from the other nodes to the depot. This distance typically represents the travel time between nodes i and j, plus the service time at node i, if one is given in the original instance. The distance matrix is not necessarily symmetrical.
Time windows (earliest, latest) for each node, one per line. The first node is the depot.
Optional comments prefixed by #that provide non-essential information, for example, the sum of service times.
2. Code.zip (our code): Our program is coded by C# dotnet. Please unzip the code to see everything. You need to install visual studio 2022 (link: ​​https://visualstudio.microsoft.com/fr/).
3. Our_Results.xlsx (our results): It is the output of our algorithm. The format is .xlsx. Our file consists of two sheets: the TSPTW and TRPTW sheets are the output of our algorithm for the TSPTW and TRPTW, respectively.
The sheet includes three columns: 1) instance is the name of instance; 2) cost is the objective function cost; 3) solution is the tour.
instances
cost
solution
n20w20.001.txt
378
0 16 9 19 17 18 10 5 15 1 11 12 6 13 7 2 4 8 20 3 14
n20w20.002.txt
286
0 1 14 18 4 8 7 5 15 11 16 19 17 10 12 3 6 2 20 9 13
…
…
…
