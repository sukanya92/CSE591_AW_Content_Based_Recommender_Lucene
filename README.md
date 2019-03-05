CSE591_AW_Content_Based_Recommender_Lucene

Instruction to Run the Application:

1. Download the zip file Assign2-SukanyaPanda, which contains the .war file (source code), Instructions in Readme.doc and a video recording of the       application.

2. Extract the content from the zip file.

3. Download and install server apache-tomcat-8.5.33 for running the application (WAR file)

4. Now, place the .WAR file in the webapps folder of the apache-tomcat-8.5.33.

5. Then, go to the bin folder of the apache-tomcat-8.5.33 where there is a startup.bat (batch) file and double click on the same. 

   If the app is being tested on a mac machine, please make sure the user has permission to run all shell script (.sh) files. If not run the command        	   sudo chmod 777 *.sh
 
   and then run the command ./catalina.sh start from terminal


6. Give the following link there to run the application:

	LINK:
  
	http://localhost:8080/CSE591_Assignment1/


7. Please put the file "data.xslx" (the one given on Canvas) on the local desktop before running the application since it takes the questions from the file.

8. Once the application opens, Please click on the start button so that the web pages get crawled and then are stored as documents(.txt files).

9. On crawling the Java Programming Wikibooks page, the crawled pages are stored on the local Desktop inside a folder named "Sukanya". 

10. Now, all the questions appear on the webpage. For recommendation, click on the '+' icon of the questions so that 10 relevant recommendations are shown       to the end user.

11. The explainantions on how the indexing, text processing of stop words are done is mentioned at the end of the webpage.

12. As an addition to the user experience, once the user hovers the mouse on each of the recommendations, user can see a tooltip showing the details and     once the user click on the recommendation a .txt file gets downloaded which contains all the relevantdetails of the recommendation.  
