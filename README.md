# Links

**Data Structures & Algorithms**
  * Big O Cheat Sheet: http://bigocheatsheet.com/
  * Graph representations: http://www.geeksforgeeks.org/graph-and-its-representations/
  * Prim's Algorithm w/ Adjacency Matrix O(V^2)
    * http://www.geeksforgeeks.org/greedy-algorithms-set-5-prims-mst-for-adjacency-list-representation/
  * Prim's w/ Adjacency List + Binary Heap - O(ElogV)
    * http://www.geeksforgeeks.org/greedy-algorithms-set-5-prims-mst-for-adjacency-list-representation/
  * Kruskal's Algorithm -  O(ElogE) or O(ElogV), since E is at most V(V-1) = O(V^2)
    * http://www.geeksforgeeks.org/greedy-algorithms-set-2-kruskals-minimum-spanning-tree-mst/


**Useful Terminal Commands**

* **scp** - Copy File from Remote to Desktop and Vice Versa: 
  * http://www.howtogeek.com/66776/how-to-remotely-copy-files-over-ssh-without-entering-your-password/
  * *scp root@IP_ADDRESS:PATH_TO_FILE COPIED_FILE_NAME.txt*

* **wget** - Retrieves/downloads the content at a specified url 
  * *wget https://nodejs.org/download/release/latest/node-v4.1.2.tar.gz* downloads latest version of node

**Useful Instalation Commands**
  * ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sublime
    * Allows you to run "sublime my_file.txt" from terminal to open a file with sublime 
    * See: http://olivierlacan.com/posts/launch-sublime-text-3-from-the-command-line/ for more details 

**Useful Emmet Commands** 
  * ctrl+shift+g = Wrap with Abbreviation
    * div.name-of-class will wrap with a class


**Useful Math**
  * https://en.wikipedia.org/wiki/Divisor_function

**Useful Series**
* *1 + 2 + 3 + 4...* S(n) = n(n+1)/2: 
  * https://en.wikipedia.org/wiki/1_%2B_2_%2B_3_%2B_4_%2B_%E2%8B%AF
  * https://www.mathsisfun.com/algebra/triangular-numbers.html
* *1 + 2^2 + 3^2 + 4^2...* S(n) = n(n+1)(n+0.5)/3: 
    * http://www.trans4mind.com/personal_development/mathematics/series/sumNaturalSquares.htm

**Bitwise Operations**
  * Bit Twiddling Hacks: http://www.graphics.stanford.edu/~seander/bithacks.html

**Number Generation**
* Generating Prime Numbers: 
  * Sieve of Eratosthenes: https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes
* Generating Pythagorean Triplets:
  * https://www.youtube.com/watch?v=4SxYc1J6o7I
  * https://en.wikipedia.org/wiki/Pythagorean_triple#Generating_a_triple

**Server Setup**
* Fantastic explanation of how nginx works with Node.js: https://doesnotscale.com/deploying-node-js-with-pm2-and-nginx/
* Initial Ubuntu Setup (Digital Ocean): https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-14-04

**Github README.md Markdown**
* Basics of Markdown: https://help.github.com/articles/markdown-basics/
* Github Specific: https://help.github.com/articles/github-flavored-markdown/