# Maps (https://c88c.org/sp22/proj/maps/)
In this project, I created a visualization of restaurant scores using machine learning and the Yelp academic dataset. 

![voronoi](https://user-images.githubusercontent.com/98563830/215883391-2650b84e-1624-47cf-bc44-1b4864c5e174.png)

## Description:
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
