# A Net Promoter Score (NPS) type question for LimeSurvey
**A custom question theme that transforms a list-radio type question into a Net Promoter Score type question (scale 0-10).**

Compatible with LimeSurvey versions 3.x or newer.

![Image Net Promoter Score 1](/Net-Promoter-Score/survey/questions/answer/listradio/assets/images/nps_1.png)

**Implementation:**

1) - **Manual installation (all supported versions)** - Extract the download and upload the *Net-Promoter-Score* folder to */pathToLimeSurvey/upload/themes/question/*. If version 4.x or newer, activate the theme in the theme manager.
    - **Theme manager (4.x or newer)** - Extract the download, compress (zip) the *Net-Promoter-Score* folder and import via the theme manager.

2) Create a list-radio question, click Save.

3) Set the question setting "Question theme" to "Net Promoter Score", click Save.  
![Image Net Promoter Score 2](/Net-Promoter-Score/survey/questions/answer/listradio/assets/images/nps_2.png)

4) Adjust the settings in the "Custom options" question attributes. ("Show/Hide colours" will display the coloured top borders)  
![Image Net Promoter Score 3](/Net-Promoter-Score/survey/questions/answer/listradio/assets/images/nps_3.png)

5) Create answer options with codes 0-10. You must have **exactly 11 answer options coded 0-10**.(the answer texts are irrelevant as the question theme pipes only the answer codes into the selectable items)

**Notes:**

1) Due to the large number of question attributes, you may need to increase the 'max_input_vars' setting in your PHP configuration (php.ini file). Try 5000 or 10000.

2) The styles for the theme can be modified in */pathToLimeSurvey/upload/themes/question/Net-Promoter-Score/survey/questions/answer/listradio/assets/css/nps.css*.

3) Demo survey in */Net-Promoter-Score/survey/questions/answer/listradio/assets/demo/*.
    
    
*Custom themes are given without any warranty, implied or otherwise.*
