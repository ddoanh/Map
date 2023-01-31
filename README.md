# Maps (https://c88c.org/sp22/proj/maps/)
In this project, I created a visualization of restaurant scores using machine learning and the Yelp academic dataset. 

![voronoi](https://user-images.githubusercontent.com/98563830/215883391-2650b84e-1624-47cf-bc44-1b4864c5e174.png)

## Description
- In this visualization, Berkeley is segmented into regions, where each region is shaded by the predicted score of the closest restaurant (yellow is 5 stars, blue is 1 star). Specifically, the visualization you will be constructing is a Voronoi diagram.
- In the map above, each dot represents a restaurant. The color of the dot is determined by the restaurant's location.

<p>The <a href="maps.zip">maps.zip</a> archive contains all the starter code and data sets.
<ul>
  <li><code>abstractions.py</code>: Data abstractions used in the project</li>
  <li><code>recommend.py</code>: Machine learning algorithms and data processing</li>
  <li><code>utils.py</code>: Utility functions for data processing</li>
  <li><code>ucb.py</code>: Utility functions for miscellaneous and debugging</li>
  <li><code>data</code>: A directory of Yelp users, restaurants, and reviews</li>
  <li><code>ok</code>: The autograder</li>
  <li><code>proj1.ok</code>: The <code>ok</code> configuration file</li>
  <li><code>tests</code>:  A directory of tests used by <code>ok</code></li>
  <li><code>users</code>: A directory of user files</li>
  <li><code>visualize</code>: A directory of tools for drawing the final visualization</li>
</ul>

## Unsupervised Learninng
The k-means algorithm is a method for discovering the centers of clusters.
The k-means algorithm finds k centroids within a dataset that each correspond to a cluster of inputs.  k-means begins by choosing k centroids at random, then alternates between the following two steps:
- Group the restaurants into clusters, where each cluster contains all restaurants that are closest to the same centroid.
- Compute a new centroid (average position) for each new cluster.

## Glossary
<ul>
  <li><strong>location</strong>: A pair containing latitude and longitude</li>
  <li><strong>centroid</strong>: A location (see above) that represents the center of a cluster</li>
  <li><strong>restaurant</strong>: A restaurant data abstraction, as defined in <code>abstractions.py</code></li>
  <li><strong>cluster</strong>: A list of restaurants</li>
  <li><strong>user</strong>: A user data abstraction, as defined in <code>abstractions.py</code></li>
  <li><strong>review</strong>: A review data abstraction, as defined in <code>abstractions.py</code></li>
  <li><strong>feature function</strong>: A single-argument function that takes a restaurant
  and returns a number, such as its mean score or price</li>
</ul>
