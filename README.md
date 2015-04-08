# getSDZ
get all pdf from SDZ alias openclassrooms 
----
openclassrooms (formerly SDZ) allowed people to download in PDF the courses
on its platform. It doesn't any more.
however, it doesn't own the previous tutorials it profits from, hat's why 
I'm allowing anyone to get them.
The idea was simple :
    - wget -c openclassrooms.com/old-courses-pdf
    - parse data (cat | grep | cut)
    - write to script.
Done !
