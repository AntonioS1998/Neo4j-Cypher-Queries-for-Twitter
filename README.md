# Neo4j-Cypher-Queries-for-Twitter

This repository contains a set of Cypher queries for analyzing a Twitter dataset in Neo4j. The queries cover various aspects of the dataset, such as hashtag prevalence, user centrality, tweet counts, and more.

## Query Descriptions

1. **Identify the most prevalent hashtags**\
Finds the top 5 hashtags used in tweets.

2. **Find the top users with the highest betweenness centrality**\
Lists the top 5 users with the highest betweenness centrality.

3. **Uncover users who have posted the most tweets**\
Finds the top 5 users with the highest number of tweets.

4. **Finding the most frequently shared links in tweets**\
Lists the top 5 most shared links in tweets.

5. **The most commonly used sources for tweeting**\
Finds the top 5 most used sources for tweeting.

6. **Users who mention users with the highest follower counts**\
Lists the top 10 users who mention other users with high follower counts.

7. **Find the most common locations of users**\
Shows the top 3 most common user locations.

8. **Most popular users and their most mentioned users**\
Lists the most popular users and the users they mention the most.

9. **Top user amplifying others and amplified users**\
Finds the top user who amplifies others and their most amplified users.

10. **Users with the highest engagement rate per tweet**\
Lists the top 4 users with the highest engagement rate per tweet.

11. **Mutual interaction clusters among users with common connections**\
Finds clusters of users who have common connections and mutual interactions.

## Usage

You can run these queries directly in the Neo4j Browser or using any Neo4j client libraries. Copy and paste the queries from the list.

## Dataset

The dataset used for these queries is a Neo4j Twitter dataset. This dataset can be accessed online through the following link: [Neo4j Twitter Dataset](https://demo.neo4jlabs.com:7473/browser/?dbms=neo4j://twitter@demo.neo4jlabs.com&db=twitter). You need to import this dataset into a Neo4j instance to execute the queries. Ensure that the dataset structure, labels, and relationships match the ones used in the queries.




