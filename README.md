# assignment2-Charlet
for class

# Here is a header of max size
### Home

Home is my apartment here in Maryville. I like it because it's **quiet** and **peaceful**. I don't have to talk to anyone there.

__________________________

#### Directions:

1. Stay in Maryville.
    - You're already there.
2. sampletext.txt
    - nestedItem.v2.01
    - nestedItem.v2.02

#### Things you should bring:

 - You
 - no one else
 - computer/phone with wifi (optional)

___________________________

### Table

Here is a table of foods you should definitely try. They are pretty exotic foods, so you'll need to be really
adventurous.

| Food | Where to find | Price |
| ---- | ------------- | ----- |
| Big Mac | McDonalds | 5$ |
| McChicken | McDonalds | 1.50$ |
| Sprite | McDonalds | 1$ |
| Fries | McDonalds | 2$ |

____________________________

### Quotes

> People don't care about what someone says about you in a movie - or even what you say, right?

 \- *Mark Zuckerberg*

> It was three or 4 years ago. I don't know what I said.

 \- *Jessie Eisenberg as Mark Zuckerberg in a movie*


______________________________

### Code Fencing
#### Aparently there are no swords involved*

#### Depth-First Search

> Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm
> starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as
> far as possible along each branch before backtracking.

[Wikipedia "Depth-first search"](https://en.wikipedia.org/wiki/Depth-first_search)

#### Implementation

```
vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices

vector<bool> visited;

void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}
```





[About Me](aboutme.md)