# Medusa
Medusa is a Python based vulnerability reporter which utilises an amended rapidscan Python 2.7 file to run vunlerability scans against a given website. 
By following the below and running the vulnerability_reporter.py in Python 3.8+, a professional report with high-level findings can be produced based on the rapidscan results.



1	Log into Kali Linux and head to directory where rapidscan.py is located	2m

2	Run rapidscan with website for assessment
  ./rapidscan {targer url}
  Use ‘CTRL-C’ to skip any scans that take >10mins to complete
  
3	Open directory where rapidscan.py is located and open threatreport.txt

4	Copy results in threatreport.txt from Linux environment and paste in rapidreport.txt file on the Windows environment

5	Open vulnerability_reporter.py in the same directory of rapidreport.txt and use ‘F5’ to run

6	A new docx file will appear in the same directory of Auto_Report.py and rapidreport.txt. Open the new docx file and review
 
