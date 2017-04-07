# SF-labs

Microsoft Azure Service Fabric labs

Project contains several labs as independent projects under sub-directories.

For each labs description, browse the code into each directory for each
projects README.md.

Project uses graphs in a syntactic form using on-line renderers like
[Gravizo](http://www.gravizo.com/) to render them:


![Alt text](https://g.gravizo.com/svg?
  digraph G {
    aize ="4,4";
    main [shape=box];
    main -> parse [weight=8];
    parse -> execute;
    main -> init [style=dotted];
    main -> cleanup;
    execute -> { make_string; printf}
    init -> make_string;
    edge [color=red];
    main -> printf [style=bold,label="100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare;
  }
)
