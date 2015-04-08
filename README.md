# getSDZ
get all pdf from SDZ alias openclassrooms 
----
DESCRIPTION  - en
----
openclassrooms (formerly SDZ) allowed people to download in PDF the courses
on its platform. It doesn't any more.
however, it doesn't own the previous tutorials it profits from, that's why 
I'm allowing anyone to get them.
The idea was simple :
    - wget -c openclassrooms.com/old-courses-pdf
    - parse data (cat | grep | cut)
    - write to script.
Done !
----
DESCRIPTION - fr
----
Le site openclassrooms.com (ancienement siteduzero) permettait de 
télécharger en pdf les cours. On ne peut plus, même en étant inscrit.
Mais Ces cours viennent de bénévoles (entre autres). Le script permet de 
télécharger la dernière version avant le changement de politique de sdz.
Comment ?
    - wget -c openclassrooms.com/old-courses-pdf
    - parse data (cat | grep | cut)
    - write to script.
Et voilà !
----
USAGE :
----
download script 
chmod u+x getSDZ.sh
./getSDZ.sh
----
