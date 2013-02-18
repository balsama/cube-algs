<h2>Professor (5x5) and up</h2>

<h3>Edge Flip + Swap</h3>

<p>You can usually get to this place with a little work. For me, I end up with
single edge flip more often than not; and most times I can get it to this
which is much easier.</p>

<pre><code>
                            ___ ___ ___ ___ ___
                          /___/_c_/_c_/_a_/___/|
                         /___/___/___/___/___/||
                        /___/___/___/___/___/|||
                       /___/___/___/___/___/||||
                      /___/_b_/_b_/_d_/___/|||||
                     |   | a | a | c |   | |||||
                     |___|___|___|___|___|/|||||
                     |   |   |   |   |   | |||||
                     |___|___|___|___|___|/|||||
                     |   |   |   |   |   | ||||' 
                     |___|___|___|___|___|/|||/
                     |   |   |   |   |   | ||/  
                     |___|___|___|___|___|/|/ 
                     |   |   |   |   |   | /
                     |___|___|___|___|___|/
</code></pre>


<pre>(Ll)1   U2   (Ll)1   U2   F2   (Ll)1   F2   (Rr)   U2   (Rr)1   U2   (Ll)2</pre>


<h3>Single Edge Flip</h3>

<p>They say this is the "worst" situation, but this is the only parity that
happens to me if it's not solved outright. Of course it can usually be 
transformed into the easier Edge Flip + Swap above or one of the other easier
algs.

<pre><code>
                            ___ ___ ___ ___ ___
                          /___/___/___/___/___/|
                         /___/___/___/___/___/||
                        /___/___/___/___/___/|||
                       /___/___/___/___/___/||||
                      /___/_b_/_a_/_b_/___/|||||
                     |   | a | b | a |   | |||||
                     |___|___|___|___|___|/|||||
                     |   |   |   |   |   | |||||
                     |___|___|___|___|___|/|||||
                     |   |   |   |   |   | ||||' 
                     |___|___|___|___|___|/|||/
                     |   |   |   |   |   | ||/  
                     |___|___|___|___|___|/|/ 
                     |   |   |   |   |   | /
                     |___|___|___|___|___|/
</code></pre>

<pre>(Rr)2   B2   U2   (Ll)   U2   (Rr)1   U2   (Rr)   U2   F2   (Rr(    F2   (Ll)1   B2   (Rr)2</pre>

<h3>Checkerboard</h3>

<pre><code>
                            ___ ___ ___ ___ ___
                          /___/_b_/_a_/_c_/___/|
                         /___/___/___/___/___/||
                        /___/___/___/___/___/|||
                       /___/___/___/___/___/||||
                      /___/_b_/_d_/_c_/___/|||||
                     |   | a | c | d |   | |||||
                     |___|___|___|___|___|/|||||
                     |   |   |   |   |   | |||||
                     |___|___|___|___|___|/|||||
                     |   |   |   |   |   | ||||' 
                     |___|___|___|___|___|/|||/
                     |   |   |   |   |   | ||/  
                     |___|___|___|___|___|/|/ 
                     |   |   |   |   |   | /
                     |___|___|___|___|___|/
</code></pre>

<pre>
(Ll)   U2   (Ll)2   U2   (Ll)1   U2   (Ll)   U2   (Ll)1   U2   (Ll)2   U2   (Ll)
</pre>

<h2>4x4 and other even # Flip</h2>

<h3>Single Edge Flip</h3>

This alg is for a complete cube with one edge completely flipped. (Usually the
`b` color is yellow.)

<pre><code>
                               ___ ___ ___ ___
                             /___/___/___/___/|
                            /___/___/___/___/||
                           /___/___/___/___/|||
                          /_b_/_a_/_a_/_b_/||||
                         | a | b | b | a | ||||
                         |___|___|___|___|/||||
                         |   |   |   |   | ||||
                         |___|___|___|___|/|||
                         |   |   |   |   | ||/ 
                         |___|___|___|___|/|/
                         |   |   |   |   | /  
                         |___|___|___|___|/
</code></pre>

<pre>r2   B2   U2   l   U2   r1   U2   r   U2   F2   r   F2   l1   B2   r2</pr>

<h3>Edge Flip + Swap</h3>

This ald swaps front and back edges while flipping one. Again, it is used on an
otherwise completed cube. `b` is yellow in this example. The `c` color is on 
the opposite side of the cube.

<pre><code>
                                    c   c
                               ___ _v_ _v_ ___
                             /_b_/_b_/_b_/_b_/|
                            /___/___/___/___/||
                           /___/___/___/___/|||
                          /_b_/_a_/_a_/_b_/||||
                         | c | b | b | c | ||||
                         |___|___|___|___|/||||
                         |   |   |   |   | ||||
                         |___|___|___|___|/|||
                         |   |   |   |   | ||/ 
                         |___|___|___|___|/|/
                         |   |   |   |   | /  
                         |___|___|___|___|/
</code></pre>

