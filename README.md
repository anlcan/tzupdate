# tzupdate

Turkiye'nin yaz saatinde kalmasiyla, jre'lerini update etmek isteyen, ancak [TZupdater](http://www.oracle.com/technetwork/java/javase/dst-faq-138158.html) daki [bug](http://www.oracle.com/technetwork/java/javase/tzupdater-readme-136440.html#issues) nedeniyle `VERSION` hatasi alanlarin icin guncellenmis tzupdater seysi. calistirmak icin:

	sudo curl https://github.com/anlcan/tzupdate/raw/master/tzupdate.zip -o tzupdate.zip && unzip tzupdate.zip && cd tzupdate && sudo sh run.sh
	
Windows icin `curl`, `unzip` gibi nimetlerimiz olmadigi icin kocaman powershell scriptleri yazmak gerekebilirdi ama bunun yerine

    1. tzupdate-win.zip dosyasini indir
	2. unzip et (tercihen "C:\" altina)
	3. tzupdate-win klasoru icindeki run.bat'i "Run as Administrator" ile calistir
	
seklinde ilerlemeyi tercih ettik. Ikinci adimda unzip'i "C:\" altina yapmadiysaniz run.bat dosyasini calistirmadan once acip icerigini duzeltmeniz gerekecektir.

Asil isi yapan insan ise [Ali Sadik Kumlali](https://github.com/kumlali). 
  
