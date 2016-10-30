# tzupdate

Turkiye'nin yaz saatinde kalmasiyla, jre'lerini update etmek isteyen, ancak [TZupdater](http://www.oracle.com/technetwork/java/javase/dst-faq-138158.html) daki [bug](http://www.oracle.com/technetwork/java/javase/tzupdater-readme-136440.html#issues) nedeniyle `VERSION` hatasi alanlarin icin guncellenmis tzupdater seysi. calistirmak icin:

	sudo curl https://github.com/anlcan/tzupdate/raw/master/tzupdate.zip -o tzupdate.zip && unzip tzupdate.zip && cd tzupdate && sudo sh run.sh

Asil isi yapan insan ise [Ali Sadik Kumlali](https://github.com/kumlali). 
  
