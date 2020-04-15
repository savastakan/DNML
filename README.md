# De Novo Markup Language, A Standard To Represent De Novo Sequencing Results From Ms/Ms Data

## Savas TAKAN, Jens ALLMER

Proteomics is the study of the proteins that can be derived from a genome. For the identification and sequencing of proteins mass spectrometry has become the tool of choice. Within mass spectrometry-based proteomics proteins can be identified or sequenced by either database search or de novo sequencing. Both methods have certain advantages and drawbacks but in the long run we envision de novo sequencing to become the predominant tool. Currently, de novo sequencing results are stored in arbitrary file formats, depending on the developers of the algorithms. We identified this as a big, unnecessary obstacle while integrating results from multiple de novo sequencing algorithms. Therefore, we designed a standard file format for the representation of de novo sequencing results. We further developed an advanced programming interface since we identified the missing of proper APIs as another obstacle, introducing a needlessly high learning curve for developers.

## USAGE
* download and extract dnml library
* start terminal ("C:\Windows\System32\cmd.exe" , in windows 10)
* find path where you extract dnml.zip in terminal
* write command in terminal such as
* example command for validatation : "java -jar dnml.jar validate file.dnml"
* example command for merge : "java -jar dnml.jar merge file1.mzxml file2.mzml file.lut pepnovo.txt output.dnml"
* example command for convert : "java -jar dnml.jar convert file.lut output.dnml"

