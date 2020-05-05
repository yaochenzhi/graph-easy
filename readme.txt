[ install ]
    yum install cpanminus
    cpanm Graph::Easy
    
[ doc ]
    http://search.cpan.org/~tels/Graph-Easy/bin/graph-easy

[ eg ]
    ls https://github.com/ironcamel/Graph-Easy/tree/master/examples/*.txt | xargs -i cat {} | graph-easy
