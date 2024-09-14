I examined a Facebook social network graph using data and offering insights into the connections and relationships that exist within the network.

Data loading: A Gzip-compressed file containing social network data is read and decompressed by the software. It then uses a hash map to parse this data into a graph representation where each node is connected to its neighbors.

Graph Analysis: It examines the loaded graph using a number of analyses, including:
● Average Distance: Determines and outputs the graph's average distance between each
node.
● Friendship Strength: Based on mutual connections, this function calculates and shows the
friendship strengths between pairs of nodes.
● Six Degrees of Separation: This function determines whether two nodes are within a
given degree of separation, such as six degrees, and outputs the outcome.
● Top 10 Friendship Strengths: This list highlights and lists the top ten qualities of
friendship.

Testing: A test module including unit tests for the functions in the graph_analysis module is part of the project. These experiments confirm that the functions involved in calculating average distance, degree of separation, and friendship strength are accurate.

Data: https://snap.stanford.edu/data/ego-Facebook.html
