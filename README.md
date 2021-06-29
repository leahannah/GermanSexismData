# Description

This repository contains the test data used for my Bachelor's Thesis about Sexism Detection in German Tweets. The data is drawn from the first ~2000 tweets in the Germeval 2018 training set  [1]. 
The labels in the data are distributed as follows: 

| total  | none    | sexism |
| ------ | ------- | ------ |
| 250    | 200     | 50     |


## Annotation

The German *test set* is manually annotated by the author of this
thesis. The criteria are specified based on observations and related
papers . The following list provides an overview of criteria that are
considered in the annotation process:

1.  Use of sexist/ misogynous slurs such as *‘Schlampe’*, *‘Luder’*
    (‘slut’), *‘Trulla’* (approx. ‘ridiculous woman’)  
    example:  
    *‘Schickt diese ISIS-Schlampe nach Syrien!’*  
    (‘Send this ISIS slut to Syria!’)

2.  Gender differentiation  
    example:  
    *‘Ein weiterer Grund, den ich häufig erlebe, ist, dass es zu wenig
    Männer (richtige Männer) im Schuldienst gibt. \[...\] Mädchen lieben
    mich, Jungen rebellieren...’*  
    (‘Another reason I often observe is that there are too few men (real
    men) in the teaching profession. \[...\] Girls love me, boys
    rebel...’)

3.  Objectifying/ sexualizing women, comments on their outer
    appearance  
    example:  
    *‘Schickt unsere Verdeidigungsministerin als Stangengirl zur
    Truppenbetreuung an die Front, aber selbst dort wird sie
    Versagen.\[...\]’*  
    (‘Send our Minister of Defense to the front lines as a pole girl to
    take care of the troops, but even there she will fail.\[...\]’)

4.  Enforcing steoreotypes/ viewing women as weaker sex  
    example:  
    *‘Von der Leyen soll sich endlich um ihre Kinder kümmern. Ab an den
    Herd. In ihrem Job absolut unfähig.’*  
    (‘Von der Leyen should finally take care of her children. Back to
    the stove. Absolutely incompetent in her job.’)

5.  Personal insults targeted at female politicians/ public figures are
    generally **not** viewed as sexism, unless they fulfill at least one
    of the criteria 1.-4.  
    example:  
    *‘Gottseidank lachen viele Deutsche schon lange über Merkels hohe
    kriminelle Energie. Verhindern sie es in FR’*  
    (‘Thank God many Germans have been laughing at Merkel’s high
    criminal energy for a long time. Prevent it in FR’)

Based on these guidelines, 50 of the first 2000 tweets from the
*germeval* data set are labeled with ‘sexism’. Many of those are sexist
insults towards female politicians and public figures. Another popular
topic are women in relation to Islam. Thus, intersectional hate speech
is included in the *test set* as well.

## References

[1] Wiegand, J. R. M. S. M. (2018). Proceedings of the GermEval 2018 Workshop.
